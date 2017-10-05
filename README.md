# Read Me

PHP Masterpass Merchant Checkout SDK for use with PHP Core SDK on MasterCard Developer Zone (https://developer.mastercard.com) 

Pre-Requisites for using PHP MasterCard Masterpass Merchant Checkout SDK:

 *  PHP 5.5 or Higher
 *  Download MasterCardCoreSDK.phar from https://github.com/Masterpass/MasterCardCoreSDK-PHP
 *  Download MastercardMerchantCheckout.phar for using masterpass merchant checkout sdk, github url: https://github.com/Masterpass/MasterPassMerchantSDK-PHP
 
##### Note: Refer to mastercard developer zone for documentation on SDKs for implementation reference and avoid potential break in your existing code if you upgrade with higher version.
 
 
##### Documentation for SDK Integration: 

For Masterpass V6 :

For configuration and pre-requisites: https://developer.mastercard.com/documentation/masterpass-merchant-integration/ 
For standard/express checkout integration: https://developer.mastercard.com/documentation/masterpass-merchant-integration/#tutorials

For Masterpass V7:

For configuration and pre-requisites https://developer.mastercard.com/documentation/masterpass-merchant-integration/v7 
For standard checkout integration: https://developer.mastercard.com/documentation/masterpass-merchant-integration/v7#standard-checkout

These phar can be downloaded from github directly or by using composer dependency.
 
If you do not have composer installed you can download it from https://getcomposer.org/
 
To download these phar as composer dependency, put a file named composer.json at the root of your project, containing as your project dependencies:
 
MasterCardMasterPassMerchant SDK v6 :
  
 ```
 {
  "require": {
  	"masterpass/masterpassmerchantsdk":"1.1.0"
   }
 }
```
 
MastercardMerchantCheckout SDK v7 :
  
 ```
 {
  "require": {
  	"masterpass/masterpassmerchantsdk":"2.1.0"
   }
 }
```
In order to import above package in your application, you need to use following composer command after installing composer locally:

> composer install or composer update

You can get more information about integrating MasterCard Merchant Checkout Service SDK from MasterCard Developer Zone - 
##### Merchant Integration section. 