# Laboratory 9 report

## Introduction

This laboratory explores the principles and practical application of DevOps, focusing on the integration of Continuous Integration (CI) and Continuous Deployment (CD) workflows. \
By utilizing Git and GitHub for version control, GitHub Actions for automated testing, and AWS (CodePipeline and Elastic Beanstalk) for automated deployment, we demonstrate how code moves from a local development environment to a live cloud-based production environment. \
The objective is to observe how automated testing prevents faulty code from being merged and deployed, ensuring stability through a seamless, automated delivery pipeline.

## Evidence

1.  **Git Add and Status (A.2, Step 3):** A screenshot of the terminal showing the `git add` command and the `git status` output where the file is listed under "Changes to be committed."
2.  **Git Log with Commits (A.2, Step 7):** A screenshot of the terminal command `git log --oneline` showing the history of the three commits made in the early stages of the lab.
3.  **Git Merge Graph (A.3, Step 7):** A screenshot of the terminal command `git log --oneline --graph --all` showing the visual representation of the branches joining via the merge commit.
4.  **GitHub Repository History (A.6):** A screenshot of the `git-practice` repository on GitHub, specifically showing the commit history via the "commits" link.
5.  **GitHub Pull/Local Sync (A.7):** A screenshot of the terminal showing the `git log --oneline` command after running `git pull`, demonstrating that the commit made on GitHub has been synchronized to your local laptop.

## Reflection

> **Q1. Is version control convenient for non-code documents?**

Version control is highly convenient for text-based documents like Markdown because Git can track line-by-line changes, allowing for clear "diffs" and easy merging.
In contrast, using version control for Word (.docx) files is less convenient because they > are binary files; Git cannot easily show which specific words changed, often treating the entire file as a single block of changed data.
For documentation and reports, Markdown provides a much more transparent and efficient workflow.
