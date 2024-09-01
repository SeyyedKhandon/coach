# Git Flow and Contribution Guidelines

Welcome to our project! This README provides an overview of our Git flow and contribution guidelines to ensure smooth collaboration and maintain a stable project. Please follow these guidelines for efficient teamwork.

## Branching Strategy

1. **Main and Develop Branches**:

The `main` and `develop` branches are protected and should not be used directly.

2. **Creating Feature Branches**:

Always create a new branch based on `develop` to work on a new feature. Use the following command to create a feature branch:

`git checkout -b feature1`

## Pull Requests

3. **Creating Pull Requests**: When you have completed your work on a feature branch, create a pull request to merge it into the `develop` branch.

4. **Reviewer Approval**: Each pull request requires at least one reviewer's approval before it can be merged.

## Main Branch Release

5. **Merging to Main**: Only the `develop` branch can be merged into the `main` branch following this pattern:

   - Create a `release` branch based on the `main` branch.
   - Merge the `develop` branch into the `release` branch.
   - After receiving at least one approval, merge the `release` branch into the `main` branch.

## QA/Review Issue/pull-requests

Please write down your QA process via a comment under the issues.

Remember to communicate and coordinate with your team members throughout the process. By following these guidelines, we can ensure a reliable and well-maintained codebase.

If you have any questions, you can create any issue for that or just email me: `seyyedkhandon@gmail.com`
