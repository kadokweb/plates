# Plates

**NOTE: V4 docs are currently a work in progress. Contributions are welcome.**

[![Maintainer](http://img.shields.io/badge/maintainer-@kadokweb-blue.svg?style=flat-square)](https://twitter.com/kadokweb)
[![Source Code](http://img.shields.io/badge/source-KadokWeb/plates-blue.svg?style=flat-square)](https://github.com/kadokweb/plates)
[![Latest Version](https://img.shields.io/github/release/kadokweb/plates.svg?style=flat-square)](https://github.com/kadokweb/plates/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)
[![Build Status](https://img.shields.io/travis/kadokweb/plates/master.svg?style=flat-square)](https://travis-ci.org/kadokweb/plates)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/kadokweb/plates.svg?style=flat-square)](https://scrutinizer-ci.com/g/kadokweb/plates/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/kadokweb/plates.svg?style=flat-square)](https://scrutinizer-ci.com/g/kadokweb/plates)
[![Total Downloads](https://img.shields.io/packagist/dt/KadokWeb/plates.svg?style=flat-square)](https://packagist.org/packages/KadokWeb/plates)

Plates is a native PHP template system that's fast, easy to use and easy to extend. It's inspired by the excellent [Twig](http://twig.sensiolabs.org/) template engine and strives to bring modern template language functionality to native PHP templates. Plates is designed for developers who prefer to use native PHP templates over compiled template languages, such as Twig or Blade.

### Highlights

- Native PHP templates, no new [syntax](http://kadok.com.br/templates/syntax/) to learn
- Plates is a template system, not a template language
- Plates encourages the use of existing PHP functions and conventions
- Increase code reuse with template [layouts](http://kadok.com.br/templates/layouts/) and [inheritance](http://kadok.com.br/templates/inheritance/)
- Template [folders](http://kadok.com.br/engine/folders/) for grouping templates into namespaces
- [Data](http://kadok.com.br/templates/data/#preassigned-and-shared-data) sharing across templates
- Preassign [data](http://kadok.com.br/templates/data/#preassigned-and-shared-data) to specific templates
- Built-in [escaping](http://kadok.com.br/templates/escaping/) helpers
- Simple design crafted for extendability - most features are built as extensions
- Everything is customizable, don't like the behavior of something, you can change it
- Composable naming strategies allowing relative templates, folders, and dynamic base paths.
- Framework-agnostic, will work with any project
- Decoupled design makes templates easy to test
- Supports non-php file rendering for img or svg files to include in your templates.
- Composer ready and PSR-2 compliant

## Installation

Plates is available via Composer:

```bash
composer require KadokWeb/plates
```

```bash
"kadokweb/plates": "1.0.*"
```

## Documentation

Full documentation can be found at [kadok.com.br](http://kadok.com.br/).

## Testing

```bash
make test
```

## Contributing

Please see [CONTRIBUTING](https://github.com/kadokweb/plates/blob/master/CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email rj@bighead.net instead of using the issue tracker.

## Credits

- [Doka Silva](https://github.com/kadokweb) (Current Maintainer)
- [kadok](https://github.com/kadokweb) (Original Author)
- [All Contributors](https://github.com/kadokweb/plates/contributors)

## License

The MIT License (MIT). Please see [License File](https://github.com/kadokweb/plates/blob/master/LICENSE) for more information.
