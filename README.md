[![PHP version](https://img.shields.io/badge/PHP-%3E%3D7.1-8892BF.svg?style=flat-square)](http://php.net)
[![Latest Version](https://img.shields.io/packagist/v/phpgears/ddd.svg?style=flat-square)](https://packagist.org/packages/phpgears/ddd)
[![License](https://img.shields.io/github/license/phpgears/ddd.svg?style=flat-square)](https://github.com/phpgears/ddd/blob/master/LICENSE)

[![Total Downloads](https://img.shields.io/packagist/dt/phpgears/ddd.svg?style=flat-square)](https://packagist.org/packages/phpgears/ddd/stats)
[![Monthly Downloads](https://img.shields.io/packagist/dm/phpgears/ddd.svg?style=flat-square)](https://packagist.org/packages/phpgears/ddd/stats)

# ddd

Metapackage to DDD building blocks

## Installation

### Composer

```
composer require phpgears/ddd
```

## Usage

Require composer autoload file

```php
require './vendor/autoload.php';
```

[Building blocks of DDD](https://en.wikipedia.org/wiki/Domain-driven_design#Building_blocks) provided by this library

|                                                                               |                         |
|-------------------------------------------------------------------------------|-------------------------|
| [phpgears/identity](https://packagist.org/packages/phpgears/identity)         | Identity                |
| [phpgears/value-object](https://packagist.org/packages/phpgears/value-object) | Value Object            |
| [phpgears/aggregate](https://packagist.org/packages/phpgears/aggregate)       | Aggregate Root, Entity  |
| [phpgears/event](https://packagist.org/packages/phpgears/event)               | Domain Event, Event Bus |

#### Supporting packages

Packages that provide supporting functionality

|                                                                               |                         |
|-------------------------------------------------------------------------------|-------------------------|
| [phpgears/immutability](https://packagist.org/packages/phpgears/immutability) | PHP object immutability     |
| [phpgears/dto](https://packagist.org/packages/phpgears/dto)                   | Data Transfer Object    |

#### Related packages

Concepts and packages, related and complementing DDD, you might be interested in but are NOT included

|                                                                                   |                                          |
|-----------------------------------------------------------------------------------|------------------------------------------|
| [phpgears/enum](https://packagist.org/packages/phpgears/enum)                     | Enumerables                              |
| [phpgears/cqrs](https://packagist.org/packages/phpgears/cqrs)                     | Command/Query Responsibility Segregation |
| [phpgears/event-sourcing](https://packagist.org/packages/phpgears/event-sourcing) | Event Sourcing                           |

## License

See file [LICENSE](https://github.com/phpgears/ddd/blob/master/LICENSE) included with the source code for a copy of the license terms.
