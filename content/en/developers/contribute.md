---
title: Contribute
description: ''
category: 'Developers'
fullscreen: false
position: 5
---

Contributions are welcome, and are accepted via pull requests.
Please review these guidelines before submitting any pull requests.

## Process

1. Fork the project
2. Setup your [development environment](/developers/setup)
3. Create a new branch
4. Code, [test](/developers/testing), commit and push
5. Open a pull request in the [main repository](https://github.com/def-studio/pest-plugin-laravel-expectations)  detailing your changes.
6. Open a pull request to update the [documentation repository](https://github.com/def-studio/pest-plugin-laravel-expectations-docs) according to the PR changes
## Guidelines

* Please ensure the coding style running `composer lint`.
* Send a coherent commit history, making sure each individual commit in your pull request is meaningful.
* You may need to [rebase](https://git-scm.com/book/en/v2/Git-Branching-Rebasing) to avoid merge conflicts.
* Please remember that we follow [SemVer](http://semver.org/).

## Setup

Clone your fork, then install the dev dependencies:
```bash
composer install
```
## Lint

Lint your code:
```bash
composer lint
```
## Tests

Run all tests:
```bash
composer test
```

Check types:
```bash
composer test:types
```

Unit tests:
```bash
composer test:unit
```
