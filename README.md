# YellowCube from Post AG - Switzerland

## Description



## License

This extension is licensed under OSL v.3.0
Some classes and javascript contain a MIT license.

## System requirements

- Magento CE >= 1.6.x to 1.9.x
- PHP >= 5.3.2
- PHP Soap, DOM Library, mbstring,
- Cron enabled and configured for Magento (set your cron at server level to a period of 5 min to launch internal task related to the rircardo extension
*/5 * * * * php path/to/my/magento/cron.php)


## Installation

### Via MagentoConnect

- You can install the current stable version via [MagentoConnect Website](http://www.magentocommerce.com/magento-connect/)

### Manually



```

git clone https://github.com/swisspost-yellowcube/magento-yellowcube.git

```



Then copy the files and folders in the corresponding Magento folders


### Via Composer

#### Requirements:
  * Unix based OS on host machine (linux/mac os). For Windows machines please use another approach since symlinks are not supported there.
  * Web server must follow symlinks
  * For Magento you must enable "Allow Symlinks" (found under System > Configuration > Advanced > Developer)
  
![Allow Symlinks](https://f.cloud.github.com/assets/1337461/43324/820d4d96-567f-11e2-947a-167bf76db33f.png)

#### Installation:

- Install [composer](http://getcomposer.org/download/)
- Run `composer require swisspost-yellowcube/magento-yellowcube`



## Configuration

## Magento Extension Configuration

In Menu `System > Configuration > General > General`

In the register "Store Information", set the Store Name and telephone number

In Menu `System > Configuration > Shipping Settings

Set the origin of the shipment:
- Country,
- Region, 
- Zip Code,
- City, 
- Street Address
- Street Address 2 (this last if relevant)


In Menu `System > Configuration > Shipping Methods`

Fill all information related to the register "Swisspost YellowCube"
