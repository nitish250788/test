# Test_ProductList

## Overview

A module that displays a list or slideshow of selected products to logged in customers in their 'My Account' section.

## Installation
* Download zip file of this extension
* Place Extrat extension in your Magento 2 installation in the folder `app/code/`
* Enable the extension: `php bin/magento --clear-static-content module:enable Test_ProductList`
* Upgrade db scheme: `php bin/magento setup:upgrade`
* Clear cache : `php bin/magento cache:clean`


## Operation

A configuration section has been added to the administrator area. Visit Stores > Configuration > Test ProductList > Product List Options. From here, you can configure the following:

- Product Limit - Enter a positive value to set a limit on the number of products displayed in the product list.

## Overview

- Additional link added, 'Product List', to the 'My Account' customer section via a layout update.
- Additional frontend controller (with logged-in check) to render a set of products with the handle_display attribute set to yes.
- Product Limit configuration option added to Magento System Configuration.
- Two mode avbailabel- One Normal grid mode and another one is Slider

## Module tested in 2.1.x