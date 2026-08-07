# Git

## Why am I learning Git?

Git is a distributed version control system that helps developers track changes, collaborate safely, and maintain project history.

---

# Lesson 1 - Why Git Exists (2026-08-05)

## Question

Why did programmers need Git?

## My Understanding

When multiple developers work on the same project, they can accidentally overwrite each other's code. Before Git, managing different versions manually was slow and error-prone.

Git solves this by keeping a complete history of changes and allowing developers to work independently before combining their work.

## Commands Learned

git init
git add
git commit
git push
git pull

## New Terms

- Repository
- Commit
- Merge
- Remote
- Origin

## Questions

- Why does Git use SHA hashes?
- What is a blob?


# Git

---

## Why am I Learning Git?

Git is platform that helps developers track changes, collaborate safely, maintain Project history. 

---

# Lesson 1 - Why Git Exists

## Problem

- Why did programmers need Git?
- What problems existed before Git?

---

## My Understanding

- Programmers were unable to track changes, unaware of who changed what.
- Difficult in collaboration. Merge conflict may occur.
- No accountability of actions
- Version control was difficult
- There was no way to go back to the previous code unless ypu had backup
- History wasnt maintained so they had difficulty in uderstanding that why were those changes made or if previous code was more efficient.

---

## Problems Without Version Control

- unable to track changes
- merge conflict
- no maintainance of history
- collaboration difficult, no accountability

(Describe each.)

---

## Key Terms Learned

- Version Control System (VCS)
- Repository
- Merge
- Merge Conflict
- Collaboration

---

## Real-Life Example

We are building a healthcare management system. There are 6 members. 
A  and B are working on fronted, C is working on backend, D is working on integration of interface etc

---

## Commands Practiced Today

- pwd
- ls
- mkdir
- touch
- git init
- git status
- git add
- git commit
- git push
- git pull
- git log --graph

---

## Questions for Tomorrow

- Why wasn't Git the first Version Control System?
- Why did Linus Torvalds create Git?
- What is a Distributed Version Control System?

# Lesson 2 — Version Control

## What is Version Control?

Version control is a system for recording changes made to files over time. It allows developers to maintain the history of a project, inspect previous versions, and collaborate without losing track of changes.

---

## Local Version Control

Local version control stores different versions of a project on an individual's computer.

It is useful for tracking personal changes, but the history is dependent on that machine. If the machine is lost or damaged, the version history may also be lost.

---

## Centralized Version Control

Centralized version control stores the main repository on a central server.

Multiple developers connect to this server to obtain changes and share their work.

The central server becomes an important dependency for collaboration and repository operations.

---

## Distributed Version Control

Distributed version control gives each developer a complete repository, including its history.

Developers can work and create commits locally without requiring an internet connection. They can later exchange their changes with other repositories.

Git uses a distributed version control model.

---

## Comparison

| Feature | Local | Centralized | Distributed |
|---|---|---|---|
| History stored locally | Yes | Limited/No | Yes |
| Central server required | No | Yes | No |
| Offline commits | Yes | Generally limited | Yes |
| Collaboration | Limited | Good | Excellent |
| Complete repository for each developer | Usually | No | Yes |

---

## My Understanding

[Write your own explanation here.]

---

## Questions

- Why does Git store a complete history locally?
- What exactly is a repository?
- What is the difference between a repository and a working directory?
- Why does Git call itself "distributed"?