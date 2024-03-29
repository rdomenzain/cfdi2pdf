|![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/Warning.svg/156px-Warning.svg.png) | This project is no longer supported.
|---|---|

# rdomenzain/cfdi2pdf

[![Source Code][badge-source]][source]
[![Software License][badge-license]][license]
[![Total Downloads][badge-downloads]][downloads]

> Create a generic PDF file from a CFDI 3.3

In some cases you just simply need a PDF file from a Mexican CFDI (Comprobante Fiscal Digital por Internet).
This tool help you to create a generic one. You can also use it to build your own and pretty formats.

## Installation

Use [composer](https://getcomposer.org/), so please run

```shell
composer require rdomenzain/cfdi2pdf
```

## Basic usage as a PHP library

```php
<?php

// create the invoice as output.pdf
$converter->createPdfAs($cfdiData, 'output.pdf');
```

## PHP Support

This library is compatible with PHP versions 7.0 and above.
Please, try to use the full potential of the language.

## Contributing

Contributions are welcome! Please read [CONTRIBUTING][] for details
and don't forget to take a look in the [TODO][] and [CHANGELOG][] files.

## Copyright and License

The rdomenzain/cfdi2pdf library is copyright © [Ricardo Domenzain M.](https://ddsis.com.mx/)
and licensed for use under the MIT License (MIT). Please see [LICENSE][] for more information.

[contributing]: https://github.com/rdomenzain/cfdi2pdf/blob/master/CONTRIBUTING.md
[changelog]: https://github.com/rdomenzain/cfdi2pdf/blob/master/docs/CHANGELOG.md
[todo]: https://github.com/rdomenzain/cfdi2pdf/blob/master/docs/TODO.md

[source]: https://github.com/rdomenzain/cfdi2pdf
[license]: https://github.com/rdomenzain/cfdi2pdf/blob/master/LICENSE
[downloads]: https://packagist.org/packages/rdomenzain/cfdi2pdf

[badge-source]: https://img.shields.io/badge/source-rdomenzain/cfdi2pdf-blue?style=flat-square
[badge-license]: https://img.shields.io/badge/licence-MIT-red
[badge-downloads]: https://img.shields.io/badge/downloads-%3E%20999-orange
