# Products module

A PrestaShop module to demonstrate all the available customizations in Product pages.

## Screenshots

#### Product Catalog Page

![product_catalog_page](https://user-images.githubusercontent.com/1247388/41238053-5811dace-6d95-11e8-89f9-a85698a93422.png)

#### Product Page

![product_page](https://user-images.githubusercontent.com/1247388/41245569-a582b838-6da8-11e8-890c-3aeeffc325bf.png)

## Requirements

You need a Shop with PrestaShop 1.7.4+, Composer and PHP 7.1 at least.

## Installation

Get the module here and move it into the `modules` folder of your Shop.

Then, you need to install the vendors of the module:

``
cd modules/products && composer install
``

Then install it using the command line:

``
php bin/console prestashop:module install products
``

Or using the Back Office.

## Features demonstrated in the module

### Catalog of products page.

We'll see how you can override the template, to re-order columns for instance.

We'll see also how to manage the available fields and following data to make it available
in templates. We'll add a new field to product page called "alternative_description" and make it
available in the catalog view.

### Product Page

We need to make the new field "alternative_description" available in Product Page.
We'll discover all the templates of Product page and how to choice which one should
ne overridden. We also try the Modules tabs feature, available for people
who need complex forms to be added to product page. 