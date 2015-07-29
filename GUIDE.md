# Using the BitPay plugin for VirtueMart

## Prerequisites
You must have a BitPay merchant account to use this plugin.  It's free to [sign-up for a BitPay merchant account](https://bitpay.com/start).


## Installation

The VirtueMart Extension Manager expects a zip file for installation. You can download this zip file from the most recent release on the release page of this repository. Otherwise, the contents of the zip file can be found in the upload subdirectory. Create a zip file of everything in the upload directory and then follow the configuration instructions below.

## Configuration

1. Go to Extension Manager -> Install
2. Browse and select the zip file, click Upload & Install.
3. Go to Manage, and find the plugin under "VM Payment - BitPay", and make sure that the plugin is published.
4. Go to Components -> VirtueMart and click on Payment Methods.
5. Click New. and type in the information, selecting "VM Payment - BitPay" as Payment Method, then click Save.
6. Create an Legacy API Key in your BitPay Merchant account at https://bitpay.com.
7. Click Configuration in the Tab menu, and enter your API Key from step 6.
8. Select your network: livenet for real bitcoin, testnet for fake bitcoin and testing purposes. Please double check that the website that you received your API Key from corresponds to the chosen network. 
