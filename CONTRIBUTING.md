# Contributing to @qutang projects

Thank you for your help and willing to contribute.

This contributing guideline is adapted from https://github.com/atom/atom/blob/master/CONTRIBUTING.md.

The following is a set of guidelines for contributing to @qutang projects, which are hosted on [GitHub](https://github.com/qutang). These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](CODE_OF_CONDUCT.md)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Code Contribution](#code-contribution)

## How Can I Contribute?

### Reporting Bugs

1. Bugs should be reproducible. Non-reproducible bugs will not be prioritized.
2. Make sure you search for existing issues (open or close) and vote to avoid replicated reports.
3. Bug report should include
    1. Your running or development environment
    2. If it is data processing project, a sample data file that can be used to reproduce the problem
    3. The steps to reproduce the bug
    4. You may use the bug report template when creating the issue for each project

### Suggesting Enhancements

1. Make sure you search for existing issues (open or close) and vote to avoid replicated reports.
1. Feature suggestion should include
    1. A summary of the feature
    2. The reason you think this feature is important
    3. A brief yet sufficient description of the expected behavior
    4. A viable path (if you can think of) to achive it

### Code Contribution

1. Follow standard fork and pull request procedure with Github when you want to work on the code.
2. Follow developer guidance on each project to bootstrap. This includes understanding
    1. The styling of source codes
    2. The styling of documentation
        1. R projects: [roxygen2 format](https://roxygen2.r-lib.org/)
        2. Python projects: [Google docstring format](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html)
    3. The styling of commit messages: All projects use [conventional commits format](https://www.conventionalcommits.org/en/v1.0.0-beta.3/).
    4. The styling of changelog format: All projects use [Keep a changelog](https://keepachangelog.com/en/1.0.0/) style. The section headings can be any texts.
    5. Steps to build/compile and run the development version of a project
    6. Steps to run test locally
3. Use Github Website to create pull request.
4. Pull requests will only be considered when it passes all CI tests on github actions.


