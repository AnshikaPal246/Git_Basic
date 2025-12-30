# There are 2 different type of VCS; DVCS & CVCS.

# Git: Important Theory

Git is a **version control system (VCS)** used to track changes in files and coordinate work among multiple developers. It is widely used in software development.

---

## 1. Types of Version Control Systems (VCS)

### a) Centralized Version Control System (CVCS)
- In CVCS, there is a **single central repository** where all developers commit their changes.
- Examples: SVN, CVS.
- Characteristics:
  - Developers do not have a complete copy of the project history.
  - Requires network access to the central server for most operations.
  - Single point of failure: if the server goes down, developers cannot save changes.

### b) Distributed Version Control System (DVCS)
- Git is a DVCS.
- In DVCS, **each developer has a full copy of the repository**, including the entire history.
- Examples: Git, Mercurial.
- Characteristics:
  - Developers can work offline and commit locally.
  - Full project history exists on every developer’s machine.
  - Synchronization happens by pushing/pulling changes between repositories.

---

## 2. Git Architecture

1. **Working Directory**  
   - The current state of files on your computer.
   - Editable files not yet staged.

2. **Staging Area (Index)**  
   - Temporary area where changes are prepared before committing.
   - You decide what goes into the next commit.

3. **Local Repository**  
   - Your machine’s copy of the Git repository.
   - Contains all commits and history.

4. **Remote Repository**  
   - Central/shared repository (e.g., GitHub, GitLab).
   - Developers synchronize with remote using `push` and `pull`.

---

## 3. Key Git Concepts

- **Commit:** A snapshot of the project at a specific time.
- **Branch:** An independent line of development.
- **Merge:** Combining changes from different branches.
- **HEAD:** Pointer to the current commit.
- **Clone:** Copying a remote repository to your local machine.
- **Pull:** Fetching and merging changes from a remote repository.
- **Push:** Sending local commits to a remote repository.

---

## 4. Git Workflow Overview

1. Make changes in the **working directory**.
2. Stage changes using the **staging area**.
3. Commit changes to the **local repository**.
4. Synchronize with a **remote repository** by pushing/pulling changes.

---

## 5. Advantages of Git (DVCS)

- Complete history available locally.
- Can work offline.
- Easy branching and merging.
- No single point of failure.

---

_End of File: `Redmi.MD`_
