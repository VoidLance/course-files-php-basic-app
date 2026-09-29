# PHP Basic App

A small, beginner-friendly PHP example that prints a greeting with a user's name and age. The values are defined directly in [`index.php`](index.php).

## Why this project is useful

- See a basic PHP script and variable interpolation in action.
- Get a minimal starting point for experimenting with PHP.
- Run it without installing project dependencies; it uses only PHP's built-in features.

## Get started

### Requirements

- PHP CLI (PHP 7 or later)

### Run from the command line

Clone the repository, move into the project directory, and run:

```sh
php index.php
```

Expected output:

```text
Hello, John! your age is 30.
```

### Run with PHP's development web server

From the project directory, start the server:

```sh
php -S localhost:8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser. Stop the server with `Ctrl+C`.

To change the greeting, edit `$userName` and `$userAge` in `index.php`.

## Get help

For questions or to report a problem, [open an issue](https://github.com/VoidLance/course-files-php-basic-app/issues).

## Maintainers and contributing

This project is maintained by [VoidLance](https://github.com/VoidLance). Contributions are welcome: open an issue to discuss a change, or submit a pull request. Please keep changes focused on this basic PHP learning example.
