magento2-Magonex_DateTime
======================

Magonex DateTime Magento2 extension.

## Installation (Composer)

1. Add this extension to your repository `composer config repositories.magonex/module-datetime git https://github.com/phaelfp/module-datetime.git`
2. Update your composer.json `composer require "magonex/module-datetime":"1.0.0"`

```
./composer.json has been updated
Loading composer repositories with package information
Updating dependencies (including require-dev)              
Package operations: 1 install, 0 updates, 0 removals
  - Installing magonex/module-datetime (1.0.0): Downloading (100%)         
Writing lock file
Generating autoload files
```

3. Enable the module and clear static content.

```
php bin/magento module:enable Magonex_DateTime --clear-static-content
php bin/magento setup:upgrade
php bin/magento setup:di:compile
```

If using OpCache, please clear cache.

## Installation (Manually)
1. Download the code. [Version 1.0.0](https://github.com/phaelfp/module-datetime/archive/1.0.0.tar.gz)
2. Extract the downloaded tar.gz file. Example: `tar -xzf module-datetime-1.0.0.tar.gz`.
3. Copy the code into `./app/code/Magenex/DateTime/`.
4. Enable the module and clear static content.

```
php bin/magento module:enable Magonex_DateTime --clear-static-content
php bin/magento setup:upgrade
php bin/magento setup:di:compile
```

If using OpCache, please clear cache.

## Compatibility

V2.*


## History
===== 1.0.0 =====
* Stable version

## License
[OSL - Open Software Licence 3.0](https://opensource.org/licenses/osl-3.0.php)
[AFL - Academic Free License 3.0](https://opensource.org/licenses/AFL-3.0)
