# Git Flow and Contribution Guidelines

Welcome to the project! This README provides an overview of our Git flow and contribution guidelines to ensure smooth collaboration and maintain a stable project. Please follow these guidelines for efficient teamwork.

## Branching Strategy

1. **Main and Develop Branches**:

The `main` and `develop` branches are protected and should not be used directly.

2. **Creating Feature Branches**:

Always create a new branch based on `develop` to work on a new feature. Use the following command to create a feature branch:

`git checkout -b feature1`

## Pull Requests

3. **Creating Pull Requests**: When you have completed your work on a feature/fix/doc branch, create a pull request to merge it into the `develop` branch.

4. **Reviewer Approval**: Each pull request requires at least one reviewer's approval before it can be merged.

## Main Branch Release

5. **Merging to Main**: Only the `develop` branch can be merged into the `main` branch following this pattern:

   - Create a conventional branch based on the `main` branch.
   - After receiving at least one approval, merge the branch into the `develop` branch and then after getting final approval we can merge the `develop` branch into the `main` branch.

## QA/Review Issue/pull-requests

Please submit your QA through github issues.

If you have any other types of questions that does not fit here such as advertisements, please contact us via email: <cafedx.com@gmail.com>
