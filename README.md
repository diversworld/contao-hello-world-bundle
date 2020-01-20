# Contao 4 Diversworld hello world bundle

This Bundle ist just a Test and not developed for usage in production.

## Install

Download the skeleton bundle:

```bash
wget https://github.com/diversworld/contao-hello-world-bundle/archive/master.zip
unzip master.zip
mv contao-hello-world-bundle-master [package name]
cd [package name]
```

## Customize

First adjust the following files:

 * `.php_cs.php`
 * `composer.json`
 * `phpunit.xml.dist`
 * `README.md`

Then rename the following files and/or the references to `ContaoHelloWOrldBundle` in
the following files:

 * `src/ContaoManager/Plugin.php`
 * `src/DependencyInjection/ContaoHelloWorldExtension.php`
 * `src/ContaoHelloWOrldBundle.php`
 * `tests/CDiversworldHelloWOrldBundleTest.php`

Finally add your custom classes and resources.

## Release

Run the PHP-CS-Fixer and the unit test before you release your bundle:

```bash
vendor/bin/php-cs-fixer fix -v
vendor/bin/phpunit
```

[1]: https://contao.org
