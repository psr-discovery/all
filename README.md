**Lightweight library that discovers available [PSR](https://www.php-fig.org/psr/) implementations by searching for a list of well-known classes that implement the relevant interface, and returns an instance of the first one that is found.**

This is a metapackage that includes all of the [PSR Discovery](https://github.com/psr-discovery) utility suit. This package bundles discovery support for [PSR-18 HTTP Clients](https://github.com/psr-discovery/http-client-implementations), [PSR-17 HTTP Factories](https://github.com/psr-discovery/http-factory-implementations), [PSR-14 Event Dispatchers](https://github.com/psr-discovery/event-dispatcher-implementations), [PSR-11 Containers](https://github.com/psr-discovery/container-implementations), [PSR-6 Caches](https://github.com/psr-discovery/cache-implementations) and [PSR-3 Logs](https://github.com/psr-discovery/log-implementations).

This suite is largely intended for inclusion in libraries like SDKs that wish to support PSRs without requiring hard dependencies on specific implementations or demanding extra configuration by users.

-   [Requirements](#requirements)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Contributing](#contributing)

## Requirements

-   PHP 8.0+
-   Composer 2.0+

Successful discovery requires the presence of a compatible implementation in the host application. This library does not install any implementations for you.

## Installation

```bash
composer require psr-discovery/all
```

## Usage

Usage instructions for each discovery library can be found at the links below:

-   [PSR-18 HTTP Clients](https://github.com/psr-discovery/http-client-implementations)
-   [PSR-17 HTTP Factories](https://github.com/psr-discovery/http-factory-implementations)
-   [PSR-14 Event Dispatchers](https://github.com/psr-discovery/event-dispatcher-implementations)
-   [PSR-11 Containers](https://github.com/psr-discovery/container-implementations)
-   [PSR-6 Caches](https://github.com/psr-discovery/cache-implementations)
-   [PSR-3 Logs](https://github.com/psr-discovery/log-implementations)

## Contributing

Contributions are welcome! Please create issues and pull requests on the repository for the specific discovery library you're interested in.

As a metapackage, this repository is not intended to accept contributions.

---

This library is not produced or endorsed by, or otherwise affiliated with, the PHP-FIG.
