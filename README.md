# COMP3104_Group11_Assignment

[![Assignment CI](https://github.com/ethanhakaj3515/COMP3104_Group11_Assignment/actions/workflows/ci.yml/badge.svg)](https://github.com/ethanhakaj3515/COMP3104_Group11_Assignment/actions/workflows/ci.yml)

## Group Members
- **Leader and sole member:** Ethan Hakaj (101465282) - [GitHub](https://github.com/ethanhakaj3515)

This repository records one student's contribution. No teammate contributions
or peer review are claimed. Solo work requires instructor approval because
the supplied assignment requires a group.

## Project Description
A DevOps assignment demonstrating local Git commits, a personal branch,
pull requests, merging, synchronization, and GitHub Actions CI.

## Setup Instructions
```sh
git clone https://github.com/ethanhakaj3515/COMP3104_Group11_Assignment.git
cd COMP3104_Group11_Assignment
git switch 101465282-Ethan
git fetch origin
git merge origin/main
```
Git is required locally. There are no application dependencies.

## Assignment Files
- `101465282_gb.txt`: George Brown College and practical learning.
- `101465282_devops.txt`: version control, branches, and review.
- `101465282_sdlc.txt`: DevOps throughout the development lifecycle.

All three files are at the repository root as required.

## CI/CD Pipeline
`.github/workflows/ci.yml` runs on push, pull request, and manual dispatch.
It uses `ubuntu-latest`, checks out the code, verifies required nonempty files,
and checks text and Markdown files for unresolved merge conflict markers.
This project has CI; it does not deploy an application or monitor uptime.

## Branching Strategy
The member branch is `101465282-Ethan`, following `STUDENTID-Name`.
Changes are committed locally and proposed to main through a pull request.
A merge commit preserves history. Fetching and merging origin/main synchronizes
the member branch after integration. Branch protection is not claimed.

## Contribution and Review
Ethan's files and repository setup were prepared with AI assistance.
The history records actual local changes; commits are not backdated.
The pull request template is `.github/PULL_REQUEST_TEMPLATE.md`.

## Submission Notes
The supplied deadline is October 18, 2026 at 11:59 pm. Work prepared afterward
does not establish an extension or acceptance of a late submission.
The assignment gives conflicting group sizes (4-6 in the instructions and 3-4
in the rubric) and mentions both COMP3104 and COMP 2156.

