# Team Contribution Guidelines

This document outlines the workflow and rules for contributing to the project’s codebase. As a team of 8, maintaining code quality and ensuring consistency is critical. All code changes must be reviewed by at least **two team members** before merging. Follow these guidelines for a smooth collaboration process.

## Workflow Overview

1. **Feature/Task Branches**: Each task should be developed on a separate branch.
2. **Code Review by Two Peers**: Before merging, each pull request (PR) must be approved by at least two team members.
3. **Commit and Push Frequently**: Regular commits help reduce conflicts and provide checkpoints for code review.

## Pull Request Workflow

1. **Create a Task-Specific Branch**: Start by creating a branch named according to the feature or task you are working on. 
   - Naming Convention: `feature/task-name` or `bugfix/issue-description`.
   
2. **Work Incrementally**: Push code to your branch in small, logical commits. This will make reviewing easier for your teammates.

3. **Open a Pull Request (PR)**: 
   - **Title**: Use a clear and concise title.
   - **Description**: Provide a summary of what the code does, including references to related issues.
   
4. **Assign Reviewers**: 
   - Every PR must have at least **two reviewers** from the team.
   - Tag the relevant people in your PR to ensure timely reviews.

5. **Address Feedback**: 
   - Make changes based on reviewer feedback.
   - Once all feedback has been addressed, request final approval.

6. **Approval**: 
   - The PR can only be merged after two team members approve it.
   - Ensure there are no outstanding comments or unresolved issues.

## Code Review Process

1. **Timely Review**: Each team member should aim to review PRs within **24 hours** of being assigned.
   
2. **Review Quality**: Provide constructive and clear feedback. Focus on:
   - **Code readability**: Ensure the code is clean, easy to understand, and follows our conventions.
   - **Functionality**: Test the code to ensure it performs as expected.
   
3. **Approval**: 
   - Leave an approval review only if you're satisfied with the code quality and all issues have been addressed.
   - If you're unsure, ask for clarification or additional context from the author.

4. **Requesting Further Changes**: If the code needs modifications, clearly explain what changes are needed and why.

## Branching and Merging

1. **Branching Strategy**: 
   - Use feature branches for development: `feature/your-feature`.
   
2. **Rebase Before Merging**: Ensure your feature branch is up to date with `develop`. Use `git rebase` to maintain a clean history without unnecessary merge commits.

3. **Squash Commits**: Squash commits during the merge to keep the history clean, especially for small changes and fixes.

4. **Merging to Develop**: Once the PR is approved by two reviewers, you can merge the branch into `develop`. Direct merges to `main` are only for final versions after testing and review.

## Push Rules

1. **No Direct Pushes to `main` or `develop`**: 
   - All changes must go through the pull request and review process.
   
2. **Descriptive Commit Messages**: Follow a clear commit message format, e.g., `fix: resolve bug in navigation system`, `feat: add object detection module`. Refer to [The Convenventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for guidelines on how to commit effectively

3. **Push Often**: Push regularly to keep your branch updated and reduce merge conflicts. 

## Conflict Resolution

1. **Rebase Regularly**: Keep your branch up to date by regularly rebasing it on `develop`. This minimizes conflicts when it’s time to merge.
   
2. **Resolve Conflicts Locally**: If conflicts arise, resolve them on your local machine. Communicate with the team if major refactoring or changes are required to avoid impacting others.
