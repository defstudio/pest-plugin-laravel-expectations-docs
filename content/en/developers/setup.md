---
title: Development Environment Setup
menuTitle: Dev. Setup
description: ''
category: 'Developers'
fullscreen: false
position: 5
---

## Setup

1. Fork the [main repository](https://github.com/def-studio/pest-plugin-laravel-expectations) by clicking the **Fork** button

2. Clone your forked project to your development machine

```bash
git clone https://github.com/{your-github-name}/pest-plugin-laravel-expectations
```

3. Create a new branch

```bash
git checkout -b my-awesome-feature
```

4. Install the dev dependencies:
 
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
