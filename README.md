# Attlaz Skeleton

[![Latest Stable Version](https://img.shields.io/packagist/v/attlaz/skeleton.svg)](https://packagist.org/packages/attlaz/skeleton)

The starting point for a PHP project on [Attlaz](https://attlaz.com), a cloud-based iPaaS (Integration Platform as a Service). It scaffolds a ready-to-run project already wired to [`attlaz/project-base`](https://packagist.org/packages/attlaz/project-base), with a sample command, configuration and dependency-injection setup.

## Requirements

- PHP 8.4+
- Docker 18+ (optional — for running via the Attlaz PHP images without a local PHP install)

## Installation

Create a new project from the skeleton:

```sh
composer create-project attlaz/skeleton my-project
```

## Quick start

Run the console to see the available commands:

```sh
# Mac / Linux
bin/console help

# Windows
bin\console help
```

From here, add your own commands under `src/App/` and configure the project in `src/App/etc/`.

## Documentation

Full documentation at [docs.attlaz.com](https://docs.attlaz.com).

## Getting help

- [Issue Tracker](https://github.com/Attlaz-Platform/Project-Skeleton-PHP/issues) — questions, bug reports and feature requests
- Developer support: developers@attlaz.com

## License

[MIT](LICENSE)
