Toggle
======

Feature toggling for PHP.

## Installation

Install the dependencies with composer:

```
$ composer install
```

## How to use

In the examples folder you'll see the basic usage of the Toggle library.

Basically you create a collection with features, optionally with conditions.
Based on a given Context, the manager will tell you if a feature is active or not.


## Tests

To run the tests you'll need to have redis installed.

Running the tests:

```
$ phpunit
```
