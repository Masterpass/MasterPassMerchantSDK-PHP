# Read Me

PHP Masterpass Merchant Checkout Service SDK for use with PHP Core SDK on MasterCard Developer Zone (https://developer.mastercard.com) 

Pre-Requisites for using PHP MasterCard Masterpass Merchant SDK:

 *  PHP 5.5 or 5.6
 *  Download MasterCardCoreSDK.phar from https://github.com/Masterpass/MasterCardCoreSDK-PHP
 *  Download MasterCardMasterPassMerchant phar file for using masterpass merchant sdk
 
 This phar can be downloaded from github directly or by using composer dependency.
 
 If you do not have composer installed you can download it from https://getcomposer.org/
 
 To download this phar as composer dependency, put a file named composer.json at the root of your project, containing as your project dependencies:
 ```
 {
  "require": {
  "masterpass/masterpassmerchantsdk":"1.0.0"
   }
 }
```

In order to import this package in your application, you need to use following composer command after installing composer locally:

> composer install or composer update

You can get more information about integrating MasterCard Merchant Checkout Service SDK from MasterCard Developer Zone - 
##### Merchant Integration section. 