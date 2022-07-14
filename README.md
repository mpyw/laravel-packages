# Laravel Packages

Library packages list for Laravel.  
Each package follows the latest Laravel version.

## Auth

### [mpyw/scoped-auth](https://github.com/mpyw/scoped-auth)

Apply specific scope for user authentication.

### [mpyw/null-auth](https://github.com/mpyw/null-auth)

Null Guard for Laravel. Designed for Middleware-based authentication and testing.

## Database

### [mpyw/laravel-database-advisory-lock](https://github.com/mpyw/laravel-database-advisory-lock) :fire:

Advisory Locking Features for Postgres/MySQL on Laravel.

### [mpyw/laravel-cached-database-stickiness](https://github.com/mpyw/laravel-cached-database-stickiness) :fire:

Guarantee database stickiness over the same user's consecutive requests.

### [mpyw/eloquent-has-by-non-dependent-subquery](https://github.com/mpyw/eloquent-has-by-non-dependent-subquery) :fire:

Convert `has()` and `whereHas()` constraints to non-dependent subqueries.

### [mpyw/eloquent-has-by-join](https://github.com/mpyw/eloquent-has-by-join)

Convert `has()` and `whereHas()` constraints to `join()` ones for single-result relations.

### [mpyw/laravel-retry-on-duplicate-key](https://github.com/mpyw/laravel-retry-on-duplicate-key)

Automatically retry **non-atomic** upsert operation when unique key constraints are violated.

### [mpyw/compoships-eager-limit](https://github.com/mpyw/compoships-eager-limit)

[topclaudy/compoships](https://github.com/topclaudy/compoships) + [staudenmeir/eloquent-eager-limit](https://github.com/staudenmeir/eloquent-eager-limit)

### [mpyw/laravel-mysql-system-variable-manager](https://github.com/mpyw/laravel-mysql-system-variable-manager)

A tiny extension of `MySqlConnection` that manages session system variables.

### [mpyw/laravel-pdo-emulation-control](https://github.com/mpyw/laravel-pdo-emulation-control)

Temporarily enable/disable `PDO` prepared statement emulation.

### [mpyw/laravel-local-class-scope](https://github.com/mpyw/laravel-local-class-scope)

A tiny macro that reuse a global scope class as a local scope.

### [mpyw/laravel-database-mock](https://github.com/mpyw/laravel-database-mock)

**[Experimental]** Database Mocking Library which mocks PDO underlying Laravel Connection classes.  
(Using [mpyw/mockery-pdo](https://github.com/mpyw/mockery-pdo))

## Pagination

### [lampager/lampager-laravel](https://github.com/lampager/lampager-laravel)

Rapid pagination for Laravel.  
(Using [lampager/lampager](https://github.com/lampager/lampager))

## Validation

### [mpyw/laravel-file-errors](https://github.com/mpyw/laravel-file-errors)

A tiny extension that reports validation error details about uploaded files.

## Console

### [mpyw/streamable-console](https://github.com/mpyw/streamable-console)

Call interactive artisan command using arbitrary stream instead of `STDIN`.
