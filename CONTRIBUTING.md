# Contribution Guide

:tada: :tada: Thanks for your interest in contributing to our project! :tada: :tada:

Please take a moment to read our [Contributor Code of Conduct](https://github.com/$PROJECT_STUB/blob/main/CODE_OF_CONDUCT.md) which helps us ensure that we have a safe and inclusive environment for everyone.

## Creating an issue

In this repository, we provide a couple of templates for you to fill in for:

- Bugs
- Feature Requests/Enhancements
- Support / Questions

Please read each section in the templates and provide as much information as you can. Please do not put **any** sensitive information, such as personally identifible information, connection strings or cloud credentials. The more information that you can provide, the better we can help you.

### Creating a Good Code Reproduction When Submitting A Bug Report

#### What is a Code Reproduction?

A code reproduction is a small application that is built to demonstrate a particular issue. The code reproduction should contain the minimum amount of code needed to recreate the issue and should focus on a single issue.

#### Why Should You Create a Reproduction?

A code reproduction of the issue you are experiencing helps us better isolate the cause of the problem. This is an important first step to getting any bug fixed! 

Without a reliable code reproduction, it is unlikely we will be able to resolve the issue, leading to it being closed. In other words, creating a code reproduction of the issue helps us help you.

#### How to Create a Reproduction

* Create a new Ionic application using one of our starter templates. The `blank` starter application is a great choice for this. You can create one using the following Ionic CLI command: `ionic start myApp blank`
* Add the minimum amount of code needed to recreate the issue you are experiencing. Do not include anything that is not required to reproduce the issue. This includes any 3rd party plugins you have installed.
* Publish the application on GitHub and include a link to it when [creating an issue](#creating-an-issue).
* Be sure to include steps to reproduce the issue. These steps should be clear and easy to follow.

## Looking for something to contribute?

All of our issues that we think are easily tackled by the community are tagged with `help-wanted` (and maybe `good-first-issue` if it's an easy entry point to the project).

- [All `help-wanted` issues](https://github.com/$PROJECT_STUB/issues?q=is%3Aissue+is%3Aopen+label%3A"help+wanted")
- [All `good-first-issue` issues](https://github.com/$PROJECT_STUB/issues?q=is%3Aissue+is%3Aopen+label%3A"good+first+issue")

## Creating a pull request

We appreciate you taking the time to contribute! We kindly ask that before you start working on a pull request for your issue/enhancement, you [create an issue](#creating-an-issue) so that everyone knows your working on it. If an issue already exists, please comment on that issue letting us know you would like to submit a pull request for it. This helps us to keep track of the pull request and make sure there isn't duplicated effort.

## Project Setup

TODO :: Add project specific setup

## CI Pipeline

The CI pipeline will automatically build under one of the following conditions:

- A pull request is created/updated against the default branch
- The default branch is updated
- A new tag (release) is created

All the workflows can be found under [Actions](https://github.com/$PROJECT_STUB/actions).
