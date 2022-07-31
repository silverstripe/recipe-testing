## Silverstripe Testing Recipe

[![CI](https://github.com/silverstripe/recipe-testing/actions/workflows/ci.yml/badge.svg)](https://github.com/silverstripe/recipe-testing/actions/workflows/ci.yml)

Standard testing components for behat, phpunit, and code style testing for the Silverstripe Framework
and CMS ([http://silverstripe.org](http://silverstripe.org)).

This includes the components:

 * [phpunit](https://github.com/sebastianbergmann/phpunit): PHP Unit Testing framework.
 * [php-codesniffer](https://github.com/squizlabs/PHP_CodeSniffer): PHP coding standards validator.
 * [behat-extension](https://github.com/silverstripe/silverstripe-behat-extension): Silverstripe behat testing
   framework extension.
 * [silverstripe server](https://github.com/silverstripe/silverstripe-serve): Silverstripe basic server built
   on PHP bundled dev server.
 * [selenium](https://github.com/sveneisenschmidt/selenium-server-standalone): Selenium browser automation framework.

All bootstrapping files, including PHPCS style config, are included.

See the [recipe plugin](https://github.com/silverstripe/recipe-plugin) page for instructions on how
Silverstripe recipes work.

**Note:** If you are not using Behat for end-to-end testing on your module, it is recommended that you install PHPUnit and CodeSniffer directly.
