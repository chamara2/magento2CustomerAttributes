# Mage2 Module EightMedia CustomerAttributes

    ``eightmedia/module-customerattributes``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities
Signup Fields

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/EightMedia`
 - Enable the module by running `php bin/magento module:enable EightMedia_CustomerAttributes`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require eightmedia/module-customerattributes`
 - enable the module by running `php bin/magento module:enable EightMedia_CustomerAttributes`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration




## Specifications




## Attributes

 - Customer - Street Address (customer_street)

 - Customer - City (customer_city)

 - Customer - State Province (customer_state)

 - Customer - Zip Postal Code (customer_zip)

