# Santander Payment Gateway: osCommerce

## Description
Santander’s osCommerce payment gateway module supports customer credit applications with Santander Consumer Bank Services.

## Current version
* Version: 1.0.3os
* Release date: 2015-12-10
* Platform: osCommerce 2.3.4

## Changelog ##

### v 1.0.3os ###
* Bug: Fixes a bug with token that is being incorrect encoded when sent to GetResult().
* Changed: Better informative texts in checkout.

### v 1.0.2os ###
* Opt-out external log access
* Installation date is saved in database
* Removed certificate

### v 1.0.1os ###
* Removed: Santander\base\sendAndDeletePreviousLog() have never been used and is now removed.
* Bug: Solves an issue with verifying user account details.

### v 1.0.0os ###
* First stable release

## Requirements
* PHP version 5.3.0 or greater.
* PHP SoapClient ([http://php.net/manual/en/class.soapclient.php](http://php.net/manual/en/class.soapclient.php))
* Openssl
* cURL lib must be enabled for PHP ([http://php.net/manual/en/book.curl.php](http://php.net/manual/en/book.curl.php))
* libxml [http://php.net/manual/en/book.libxml.php](http://php.net/manual/en/book.libxml.php)

## Documentation
Installation instructions and any other supporting documentation are located in [the docs folder](./docs) folder that accompanies the download.

## Account Setup - Santander
If you have any questions concerning your account details: Shop ID, merchant ID, password etc. please contact Santander [by clicking here](http://santander.consid.se/site/contact?department=2).

## Technical Issues - Consid
If you have any issues installing the module, please contact Santander’s payment gateway IT services partner [by clicking here](http://santander.consid.se/site/contact?department=1).

## About: osCommerce
> OsCommerce ("open source Commerce") is an e-commerce and online store-management software program. It can be used on any web server that has PHP and MySQL installed. It is available as free software under the GNU General Public License.

[osCommerce homepage](http://www.oscommerce.com)