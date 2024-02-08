# How to contribute

Support and contributions from the open source community are essential for keeping
`@Shrinivasofficial` up to date and always improving! There are a few guidelines that we need
contributors to follow to keep the project consistent, as well as allow us to keep
maintaining `@Shrinivasofficial` in a reasonable amount of time.

Please note that this project is released with a ontributor Code of Conduct.
By participating in this project you agree to abide by its terms.

[coc]: ./CODE_OF_CONDUCT.md

## Creating an Issue

Before you create a new Issue:

1. Please make sure there is no open inssue yet.
2. If it is a bug report, include the steps to reproduce the issue and please create a reproducible test case on runkit.com 
3. If it is a feature request, please share the motivation for the new feature and how you would implement it.
4. Please include links to the corresponding github documentation.

## Making Changes

Here is an overview of how it works.

- Create a topic branch from the main branch.
- Check for unnecessary whitespace / changes with `git diff --check` before committing.
- Keep git commit messages clear and appropriate. Ideally follow commit conventions described below.

## Submitting the Pull Request

- Push your changes to your topic branch on your fork of the repo.
- Submit a pull request from your topic branch to the main branch.
- Be sure to tag any issues your pull request is taking care of / contributing to. \* Adding "Closes #123" to a pull request description will auto close the issue once the pull request is merged in.

## Merging the Pull Request & releasing a new version

Only one version number is bumped at a time, the highest version change trumps the others.
Besides publishing a new version to npm, semantic-release also creates a git tag and release
on GitHub, generates changelogs from the commit messages and puts them into the release notes.

If the pull request looks good but does not follow the commit conventions, use the "Squash & merge" button.
