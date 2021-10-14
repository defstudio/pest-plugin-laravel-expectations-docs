---
title: Installation & Configuration
menuTitle: 'Installation'
description: ''
position: 2
category: 'GETTING STARTED'
---

<alert type="info">**Note:** This plugin assumes you already have a working [Pest](https://pestphp.com) test suite in your Laravel project.</alert>

----

## Installation

You can install the package via composer:

``` bash
composer require --dev defstudio/pest-plugin-laravel-expectations
```

The expectations added by this plugin are automatically loaded into Pest's expectation system. They can be used along other expectations.


## Autocompletion

For PhpStorm users, a nice Plugin has been developed by [Oliver Nybroe](https://github.com/olivernybroe). It adds full autocompletion to ours Laravel Expectations, it is worth to take a look: [https://github.com/pestphp/pest-intellij](https://github.com/pestphp/pest-intellij)
