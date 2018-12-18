Becopay payment module for Joomla 2.5/3.x and HikaShop
====================

Version: 1.0.0

License: [Apache 2.0](https://opensource.org/licenses/Apache-2.0)

Tags: online payment, payment, payment gateway, becopay, joomla, hikashop

## System requirements

* PHP 5.3+
* [cURL extension](http://php.net/manual/en/book.curl.php)
* [Joomla](http://www.joomla.org/download.html) (the module was tested with version 3.9.1)
* [HikaShop](https://www.hikashop.com/) (the module was tested with version 4.0.1)


## Prerequisites


You must have a Becopay merchant account to use this plugin.  It's free and easy to [sign-up for a becopay merchant account](https://becopay.com/en/merchant-register/).


## The module installation

1. [Download Hikashop-Becopay-Gateway.zip](https://github.com/becopay/Hikashop-Becopay-Gateway/releases)
2. Go to __`Joomla's administration panel`__
3. Via the top menu go to __`Extensions > Manage > Install`__
4. Install the module package
	1. Select the __`Upload Package File`__ tab
	2. Select the module package file saved at the step 1.
  	3. Click __`Upload & Install`__ to install the module
  	4. Via the top menu go to __`Extensions > Plugins`__
  	5. Locate the plugin __`Hikashop Becopay Payment Plugin`__ and enable it

## The module configuration

1. Go to __`Joomla's administration panel`__
2. Go to HikaShop's administration panel via __`Components > HikaShop > Configuration`__
3. Go to the menu  __`System > Payment methods`__
4. Click the button __`New`__ and select __`Hikashop Becopay Payment Plugin`__
5. Configure the module
    1. On __`Main information`__ block setup the payment method name and description
    2. On __`Specific configuration`__ block enter your becopay gateway configuration
    	* __Mobile__  - Enter the phone number you registered in the Becopay here.If you don't have Becopay merchat account register [here](https://becopay.com/en/merchant-register/).
		* __Api Base Url__  - Enter Becopay api base url here. If you don't have Becopay merchat account register [here](https://becopay.com/en/merchant-register/).
		* __Api Key__  - Enter your Becopay Api Key here. If you don't have Becopay merchat account register [here](https://becopay.com/en/merchant-register/).
		* __Merchant Currency__ - Enter your money's currency wants to receive.e.g: IRR
		* __Debug__ - If enable it show the all of the error message and useful for debugging
		* __Invalid status__ - Status given to order if has error
		* __Verified status__ - Status given to order after the payment has been completed
6. Publish the payment method
    1. Select the configured payment method in the list of payment methods
	2. Publish it by clicking an icon in the column __`Published`__



## Becopay Support:

* [GitHub Issues](https://github.com/becopay/Hikashop-Becopay-Gateway/issues)
  * Open an issue if you are having issues with this plugin
* [Support](https://becopay.com/en/support/#contact-us)
  * Becopay support
* [Documentation](https://becopay.com/en/io#api)
  * Technical documentation

## Contribute

Would you like to help with this project?  Great!  You don't have to be a developer, either.  If you've found a bug or have an idea for an improvement, please open an [issue](https://github.com/becopay/Hikashop-Becopay-Gateway/issues) and tell us about it.

If you *are* a developer wanting contribute an enhancement, bug fix or other patch to this project, please fork this repository and submit a pull request detailing your changes. We review all PRs!

This open source project is released under the [Apache 2.0 license](https://opensource.org/licenses/Apache-2.0) which means if you would like to use this project's code in your own project you are free to do so.  Speaking of, if you have used our code in a cool new project we would like to hear about it!  [Please send us an email](mailto:io@becopay.com).

## License

Please refer to the [LICENSE](https://opensource.org/licenses/Apache-2.0) file that came with this project.