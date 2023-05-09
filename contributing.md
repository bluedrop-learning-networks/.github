# Contributing Guidelines

This document will guide you through the process of contributing to our projects and help maintain a healthy and
collaborative environment.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Issues](#issues)
3. [Making Changes](#making-changes)
   - [Coding Conventions](#coding-conventions)
4. [Pull Requests](#pull-requests)
   - [For the Author](#for-the-author)
   - [For the Reviewer](#for-the-reviewer)
5. [Testing](#testing)
6. [Questions](#questions)
7. [Code of Conduct](#code-of-conduct)

## Getting Started

To get started, please refer to the [bln-dev-handbook](https://github.com/bluedrop-learning-networks/bln-dev-handbook)
and [bln-ops-handbook](https://github.com/bluedrop-learning-networks/bln-ops-handbook) for an overview of our
development and operational processes. We highly recommend starting with the [Development Environment - From Zero to
Tilt](https://github.com/bluedrop-learning-networks/bln-ops-plan-state/blob/master/local/README.md) article, which will
help you set up an end-to-end local environment for our projects.

Before contributing, make sure to familiarize yourself with the project's documentation, codebase, and any relevant
issues.

## Issues

We use Jira for issue management. You can find our Jira board at `bluedrop360.atlassian.net`. This is where your tasks
will be assigned and where work should be planned out. If you encounter a bug, please create a new issue on Jira,
providing a clear description and any relevant details. Make sure to check for existing issues to avoid duplicates.

## Making Changes

When contributing, please adhere to the typical Git workflow: create branches, submit pull requests, follow coding
conventions, and ensure your code is appropriately tested. Make sure to have your pull request reviewed and follow the
checklist provided in the pull request template.

### Coding Conventions

Please follow the eslint rules and .editorconfig rules for formatting and spacing within a project. Consistent coding
style is essential for readability and maintainability. If you're unsure about a specific coding convention, consult the
project's documentation or ask for guidance from the team.

## Pull Requests

- Code review is a responsibility shared by all team members, regardless of seniority.
- Authors are responsible for their own code and ultimately for merging their own code.
- Generally, at least one approving review is required to merge code. Pull requests containing user-facing functional
  changes require an approving QC review.
- Dismiss stale reviews is disabled to allow addressing optional, non-blocking comments on a PR without incurring
  another round of review. Please refrain from introducing substantive or unrelated changes to a branch after a PR has
  been approved.

### For the Author:

- Provide a clear description and follow the checklist in the PR template for the repository.
- Keep pull requests small, whenever possible.
- Explain any unexpected changes.
- Test your work locally before submitting a pull request. Reviewers should reasonably expect that the work has been
  tested end-to-end by the author before submission, unless otherwise stated.
- When your pull request is ready for review (i.e., GitHub Actions checks are passing, and all pre-review checklist
  items are completed), select 1-2 reviewers who are most familiar with the project or issue.
- If a pull request is a work in progress, set it as a draft pull request.

### For the Reviewer:

- Code reviews present an opportunity for everyone to learn and ensure high-quality code before it reaches production.
  Excellent communication and constructive criticism are essential.
- Provide explicit approval or disapproval with clear reasons.
- Distinguish between blocking and non-blocking comments on code reviews. Blocking comments are those that require
  changes before the PR can be merged, while non-blocking comments are suggestions or improvements that may be addressed
  now or later. If your review contains blocking comments, choose the "request changes" option.
- With regard to code conventions, if it isn't enforced using static analysis in a GitHub Action (e.g., using eslint or
  prettier), consider its importance. If it's important enough, consider writing an eslint rule.
- Pull requests are not the only way to conduct code reviews. Consider doing pair reviews when the situation warrants
  it, such as when working on complex features or when a team member needs guidance on a specific topic.

## Testing

Thorough testing is crucial for ensuring the stability and reliability of our projects. Make sure to write appropriate
tests for your code, covering various scenarios and edge cases. Follow the testing guidelines and best practices
established within the project. Depending on the project, tests could mean unit tests, integration tests (eg. dredd),
storybook stories, or other ways to test components in isolation. 

## Code of Conduct

Our organization is committed to fostering an inclusive and respectful environment. We expect all contributors to adhere
to our [Code of Conduct](https://drive.google.com/file/d/13Uih2iPVQNpRDKlIpZvtezJ0ABG5wJ14/view?usp=share_link), which
outlines our expectations for behavior and provides guidelines for maintaining a positive and welcoming organization.

## Questions

We encourage open communication and collaboration within our organization. If you have questions, need assistance, or
want to share your ideas, don't hesitate to reach out to the project maintainers or team members.

