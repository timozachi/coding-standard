# Coding Standard

[![License](https://img.shields.io/packagist/l/tzachi/coding-standard.svg)](https://packagist.org/packages/tzachi/coding-standard)
[![Build Status](https://travis-ci.org/TimoZachi/coding-standard.svg?branch=master)](https://travis-ci.org/TimoZachi/coding-standard)
[![Total Downloads](https://img.shields.io/packagist/dt/tzachi/coding-standard.svg)](https://packagist.org/packages/tzachi/coding-standard)
[![Latest Stable Version](https://img.shields.io/packagist/v/tzachi/coding-standard.svg?color=blue&label=stable)](https://packagist.org/packages/tzachi/coding-standard)
[![Unstable Version](https://img.shields.io/packagist/vpre/tzachi/coding-standard.svg?label=unstable)](https://packagist.org/packages/tzachi/coding-standard)

This project has a set of [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) rules that are based on
[doctrine/coding-standard](https://github.com/doctrine/coding-standard) rules, but with some small changes and
additions.

## Differences from doctrine coding-standards

* Inline comments should begin with a space, for example: ```// This is an inline comment```
* Docblock annotation groups are grouped a bit different
* Empty catch in try...catch must have a comment saying why the exception is not handled
* There shouldn't be a space after the negation operator ```if (!$cond)```
* Property doc comments shouldn't be a single line. Instead, they should be like this:
```php
/**
 * @var int
 */
```
* Variable/property/function names should be camelCased: ```$camelCaseVariable```