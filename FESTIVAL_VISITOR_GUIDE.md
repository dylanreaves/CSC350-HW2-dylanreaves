# Festival Visitor Guide

## Student Information

- Name: Dylan Reaves
- Course and section: CSC 350H Section: 1300
- Date: 9/12/2026

## Repository Evidence

- Current branch: main
- Personal Homework 2 GitHub URL: https://github.com/dylanreaves/CSC-350-HW2.git
- Starting `git status`: On branch main nothing to commit, working tree clean
- Starting preparation commit ID: bd125dd

## Festival Identity

- Festival name: Video Game Festival
- Location: BMCC Campus, New York
- Intended audience: Students
- Theme: Fun, Chill, Relaxed

## Prediction Before the First Commit

1. Where does the saved change currently live?

   Working tree

2. Has it been staged or committed?

   No, it has not been staged or commited

## Arrival Information

- Transit or parking: Use public transit and arrive at the BMCC campus.
- Entrance or meeting location: Meet at the entrance to the main campus.

## Accessibility Information

1. Wheelchair accessible entrances and elevators will be avaliable for visitors who need them.
2. Accessible seating areas will be reserved near activities and presentations.

## Visitor Reminder

Please keep walkways and accessible entrances clear and follow safety instructions.

## GitHub Verification

Verified on GitHub by Dylan Reaves.

## Commit Evidence

| Checkpoint | Short commit ID | Required message |
|---|---|---|
| Personalized guide | [c9790ca] | `docs: personalize festival visitor guide` |
| Visitor access information | [fed7a30] | `docs: add visitor access information` |
| GitHub verification | [fbb216a] | `docs: verify independent homework on GitHub` |
| Final reflection | [47e8868] | `docs: complete independent Git reflection` |

## Individual Reflection

1. What is the difference between saving a file and committing it?

   Saving a file only saves it on the working tree. Commiting a file saves a snapshot of that file into the git history so it can be accessed at a later date.

2. What is the difference between `git diff` and `git diff --staged`?

   git diff shows current changes between files on the working tree, while git diff --staged shows only the changes between staged files.

3. Why did the GitHub verification sentence not appear locally before `git pull`?

   Because the changes were made on github they were not replicated to my local machine. Since I made a new commit I had to then pull those changes to synchronize my local working tree with the github remote.

4. What did `-u` accomplish in `git push -u origin main`?

   The -u sets the branch as the upstream branch for my local main branch. This allows git push and git pull to know which remote branch to use without needing to specify origin main.

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

   git status will show that my local branch is up to date with the main branch and the working tree is clean. I can also compare the commit history on github and my local to see if they match.

