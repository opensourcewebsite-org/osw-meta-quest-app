# Contributing Guidelines

First off, thanks for taking the time to contribute!

Please read through our [Installation Instructions](INSTALL.md).

## Getting Started

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the core team before making a change.

- Make sure you have a [GitHub account](https://github.com/login).
- Submit a GitHub issue for your issue if one does not already exist.
  - A issue is not necessary for trivial changes.
- [Fork](https://help.github.com/en/articles/working-with-forks) the repository on GitHub.
    - [Configuring a remote for a fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork)
    - [Syncing a fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)
      - `git fetch upstream`
      - `git checkout master`
      - `git merge upstream/master`
    - [Merging an upstream repository into your fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/merging-an-upstream-repository-into-your-fork)
      - `git checkout master`
      - `git pull upstream master`
      - Commit the merge
      - `git push origin master`
- When working on an issue, create a new branch from `master` named for issue number or custom name. Name the branch `issue/<issue-number>` or `issue/<custom-name>`. For example `issue/22` for fixing issue #22.
- Make your changes.
  - Follow the [Style Guides](#style-guides).
  - [Avoid platform-dependent code](https://flight-manual.atom.io/hacking-atom/sections/cross-platform-compatibility/).
  - Add tests if your changes contains new, testable behavior.
  - Make the tests pass.
- Create a [pull request](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork) to the repository.

### Tips and tricks for using the Git

- [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet)
- [git-tips](https://github.com/git-tips/tips)

### Key branches

- `main` is the latest, deployed version

## Contribute to the core code or bug fixes

### Your First Code Contribution

Start by looking through these issues:

- [Beginner issues](https://github.com/opensourcewebsite-org/osw-meta-quest-app/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22+sort%3Acomments-desc) - issues which should only require a few lines of code, and a test or two. Issues are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.
- TODO issues - find comments with keyword `TODO` in the source code, with a description of a issue, and suggestions to resolve it.

## Style Guides

### Git Commit Messages

- Include an issue number to the beginning of the first line (if applicable). Example `#234 YOUR_COMMIT_NAME`.
- Use the present tense ("Add feature" not "Added feature").
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
- In case changing only texts or documentations include `[ci skip]` to the end of the first line.
- Limit the first line to 72 characters or less.
- Reference issues and pull requests liberally after the first line.

### Documentation Style Guide

All `*.md` files must adhere to [Markdown Syntax](https://www.markdownguide.org/basic-syntax/).

### Kotlin Style Guide

Kotlin Code MUST adhere to [Kotlin Coding Conventions](https://kotlinlang.org/docs/coding-conventions.html).

Recommended IDE:
  - [VS Code](https://code.visualstudio.com)
    - [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  - [IntelliJ IDEA](https://www.jetbrains.com/idea/)
  - [Android Studio](https://developer.android.com/studio/)

### Programming principles and recommendations

- [KISS principle (keep it simple, stupid)](https://en.wikipedia.org/wiki/KISS_principle)
- [Don't repeat yourself (DRY)](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
- [You aren't gonna need it (YAGNI)](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it)
- [Worse is better](https://en.wikipedia.org/wiki/Worse_is_better)
- [SOLID](https://en.wikipedia.org/wiki/SOLID)
- [GRASP](https://en.wikipedia.org/wiki/GRASP_(object-oriented_design))

## Additional information

- [Kotlin for Android](https://kotlinlang.org/docs/android-overview.html)
