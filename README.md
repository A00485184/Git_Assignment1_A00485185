# MCDA 5512 Assignment #1 - Git

**Student Number:** A00485185  
**GitHub Repository:** [https://github.com/A00485184/Git_Assignment1_A00485185](https://github.com/A00485184/Git_Assignment1_A00485185)

## Overview
This repository contains the completed tasks for MCDA 5512 Assignment #1: Git Fundamentals. The assignment focuses on standard Git workflows, branching, merging, conflict resolution, stashing, and cherry-picking.

## Tasks Completed

The assignment consists of six parts, all of which have been fully executed:

### (1) Repository Initialization and Status Check
* Created the `Git_Assignment1_A00485185` directory.
* Initialized a brand new Git repository.

### (2) File Creation and Version Control
* Created `countries.txt` and `shapes.txt`.
* Staged and committed files with message `"Adding Countries and Shapes"`.
* Created `numbers.txt`, staged, committed, and logged history.

### (3) Branch Creation and Commit
* Created and checked out a new branch named `LearnAnalytics`.
* Created `languages.txt`, committed changes, and verified branches.

### (4) Merging Conflicting Changes
* Created branches `user1` and `user2` mapped from `master`.
* Modified `countries.txt` on `user1` (replacing content) and on `user2` (appending content).
* Created `combine_countries` branch and forcefully caused a merge conflict by merging `user1`. 
* Successfully resolved the conflict by saving the additions from both branches and committing the resolution.

### (5) Stashing and Applying Changes
* Created a new branch named `user3`.
* Modifed `countries.txt` and stashed the changes.
* Switched to `master` and applied new modifications.
* Popped the stash within `user3` and successfully committed both sets of changes.

### (6) Advanced Git Workflow
* Created the `bugfix` branch.
* Added standard commits for `bugfix.txt` and `random.txt`.
* Tested the integration of code across branches by successfully cherry-picking the specific `bugfix.txt` commit hash back into the `master` branch.

## Project Structure (Files Created)
- `countries.txt`
- `shapes.txt`
- `numbers.txt`
- `languages.txt` (LearnAnalytics branch)
- `bugfix.txt`
- `random.txt` (bugfix branch)

## Report
The final screenshots and commands output report (`Git_Assignment1_A00485185_Report.docx`) is generated alongside the development of this structure.
