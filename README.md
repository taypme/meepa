# Meepa

Meepa is a small, dependency-free PHP experiment. The repository keeps the
current entry point alongside an earlier versioned implementation so the code
can be inspected, included, and evolved without a framework or build step.

## Files

- `meepa.php` — primary PHP entry point.
- `lib_v1.php` — version 1 library implementation.

## Usage

Include the file you want from PHP:

```php
require_once __DIR__ . '/meepa.php';
```

`lib_v1.php` is retained as the version 1 implementation/reference. Read the
source before relying on an API; this is an experimental library rather than a
published Composer package.

## Development

There is no dependency installation or automated test suite at present. Make
small changes, run PHP syntax checks, and exercise the entry point in the
calling application.
