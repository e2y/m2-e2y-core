# Module E2Y Core

    ``e2y/module-core``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)


## Main Functionalities
e2y configuration tab for Magento 2

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/E2Y`
 - Enable the module by running `php bin/magento module:enable E2Y_Core`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Install the module composer by running `composer require e2y/module-core`
 - enable the module by running `php bin/magento module:enable E2Y_Core`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`