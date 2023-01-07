# Contributing

Welcome, and thank you for considering contributing to this repository/organization.
Contributions are made to this repository/organization via Issues and Pull Requests (PRs).
Please read and follow these guidelines to make the process easy and transparent.
Use Discussions (if enabled) in case of any further questions.

## Reporting Bugs

- Make sure the bug was not already reported.
- Report bugs by creating an Issue. 
  The bug report should be thorough and include the following:
  - A bug description that is concise and specific,
  - A small code snippet and steps to reproduce the problem,
  - Resulting and expected behaviors,
  - Other helpful information, e.g. test data.

## Adding New Features

- Proposals of new features are always welcome.
  We highly appreciate your input.
- Create an Issue before changing any code, and provide sufficient details regarding the new feature.
- The owner of the repository could reject feature proposals for code maintenance reasons.
  But if the use case was described well in the Issue, you could expect feedback on how to implement the feature on your side.
  Besides, it is possible to discuss with the repository owner whether a subset can be implemented in the library to provide the required interfaces to help realize the new feature.

## Pull Request Process

- Create small PRs, i.e., one PR for one concern, and use atomic commits.
- Add executable tests with full code coverage.
- Run the npm test script before you commit (which also runs the linter).
  - [stricter-standard](https://www.npmjs.com/package/stricter-standard/) is used for linting.
    It's based on [standard](https://standardjs.com/) with some additional rules.
    Most problems can be fixed by running `npx stricter-standard --fix`.
    The errors should be self-explanatory in cases where manual interventions are required.
- Write proper commit messages.
  - This repository/organization uses the [Semantic Versioning](https://semver.org/) scheme.
  - Write messages following the [Conventional Commits Specification](https://www.conventionalcommits.org/en/v1.0.0/).
  - When unsure, choose one from the following keywords:
    - `feat`: for new features,
    - `fix`: for bug fixes,
    - `chore`: for CI and other maintenance-related changes, 
    - `!`: for breaking changes
- Write *what* has been done in the title of the PR
- Write a comment in the PR:
  - Summarize the change details (*how*)
  - Refer to the issue, which should contain details of *why* the PR was created.
