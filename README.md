# pie-extensions/redis

PIE-compatible mirror of [phpredis/phpredis](https://github.com/phpredis/phpredis).

## Install

```bash
pie install pie-extensions/redis
```

## What is this?

This repository is an automated mirror that repackages the upstream PHP extension for installation via [PIE](https://github.com/php/pie) (PHP Installer for Extensions).

Releases are synced automatically from the upstream repository. Each release contains the unmodified upstream source code with a PIE-compatible `composer.json`.

## Supported platforms

Pre-built binaries are available for the following platforms:

| OS | Arch | libc | Notes |
|----|------|------|-------|
| Linux | x86_64 | glibc | |
| Linux | x86_64 | musl | Requires `libstdc++` and `libgcc` |
| Linux | arm64 | glibc | |
| Linux | arm64 | musl | Requires `libstdc++` and `libgcc` |
| macOS | x86_64 | - | |
| macOS | arm64 | - | |

> **Alpine Linux (musl):** Extensions that use C++ internally require the `libstdc++` and `libgcc` runtime packages, which are not included in minimal Alpine images. Install them with `apk add libstdc++ libgcc`.

## Links

- **Upstream:** https://github.com/phpredis/phpredis
- **PIE:** https://github.com/php/pie
- **Organization:** https://github.com/pie-extensions

## License

This mirror inherits the license of the upstream project. See the upstream repository for license details.

## Issues & Questions

This is an automated mirror repository. Please report all issues and direct questions to the [pie-extensions/core](https://github.com/pie-extensions/core) repository.
