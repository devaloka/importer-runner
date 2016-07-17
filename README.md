# Importer Runner

[![Latest Stable Version][stable-image]][stable-url]
[![Latest Unstable Version][unstable-image]][unstable-url]
[![License][license-image]][license-url]
[![Build Status][travis-image]][travis-url]

Programmatically extensible Importer runner that allows you to run
various Importers.

## Installation

### Manual Installation

1.  Just copy all files into `<ABSPATH>wp-content/plugins/importer-runner/`.

### Manual Installation (as a Must-Use plugin)

1.  Just copy all files into
    `<ABSPATH>wp-content/mu-plugins/importer-runner/`.

2.  Move `importer-runner/loader/50-importer-runner-loader.php`
    into `<ABSPATH>wp-content/mu-plugins/`.

### Installation via Composer

1.  Install via Composer.

    ```sh
    composer require devaloka/importer-runner
    ```

### Installation via Composer (as a Must-Use plugin)

1.  Install via Composer.

    ```sh
    composer require devaloka/importer-runner
    ```

2.  Move `importer-runner` directory into
    `<ABSPATH>wp-content/mu-plugins/`.

3.  Move `importer-runner/loader/50-importer-runner-loader.php`
    into `<ABSPATH>wp-content/mu-plugins/`.

[stable-image]: https://poser.pugx.org/devaloka/importer-runner/v/stable
[stable-url]: https://packagist.org/packages/devaloka/importer-runner

[unstable-image]: https://poser.pugx.org/devaloka/importer-runner/v/unstable
[unstable-url]: https://packagist.org/packages/devaloka/importer-runner

[license-image]: https://poser.pugx.org/devaloka/importer-runner/license
[license-url]: https://packagist.org/packages/devaloka/importer-runner

[travis-image]: https://travis-ci.org/devaloka/importer-runner.svg?branch=master
[travis-url]: https://travis-ci.org/devaloka/importer-runner
