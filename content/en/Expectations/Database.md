---
title: Database Expectations
menuTitle: Database
description: ''
category: 'Expectations'
fullscreen: false
---

### `toBeInDatabase()`

Assert that the given _where condition_ exists in the database.

```php
expect(['name' => 'Fabio'])->toBeInDatabase(table: 'users');
 ```
