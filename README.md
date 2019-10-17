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

The phpcfdi/cfditopdf library is copyright © [Ricardo Domenzain M.](https://ddsis.com.mx/)
and licensed for use under the MIT License (MIT). Please see [LICENSE][] for more information.

[contributing]: https://github.com/rdomenzain/Cfdi2Pdf/blob/master/CONTRIBUTING.md
[changelog]: https://github.com/rdomenzain/Cfdi2Pdf/blob/master/docs/CHANGELOG.md
[todo]: https://github.com/rdomenzain/Cfdi2Pdf/blob/master/docs/TODO.md

[source]: https://github.com/rdomenzain/Cfdi2Pdf
[license]: https://github.com/rdomenzain/Cfdi2Pdf/blob/master/LICENSE
[downloads]: https://packagist.org/packages/rdomenzain/Cfdi2Pdf

[badge-source]: http://img.shields.io/badge/source-phpcfdi/cfditopdf-blue?style=flat-square
[badge-license]: https://img.shields.io/github/license/phpcfdi/cfditopdf?style=flat-square
style=flat-square
[badge-downloads]: https://img.shields.io/packagist/dt/phpcfdi/cfditopdf?style=flat-square