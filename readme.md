PayTm Intgration By Navin : 15/04/2020

1. Integration With Paytm with Android App.
2. Add Paytm Dependency
3. Add Runtime Permission & Paytm Activity
4. Get Merchant ID & Secret Key
5. Upload Checksum Files on Server
6. Generate Paytm Checksum
7. Start Paytm Payment Transaction
8. Run & Make Payment using dummy Credit Card/ Net banking

Follow the Following Link.

https://www.blueappsoftware.com/paytm-payment-gateway-integration-android-studio/

Download the Check Sum Program From PHP

https://developer.paytm.com/docs/all-in-one-sdk/

Go to this link and click on the 

https://github.com/Paytm-Payments/Paytm_App_Checksum_Kit_PHP  : For Check Sum Program : 

and modify the Config file "config_paytm.php" with your Merchant Key : 

<?php
//Change the value of PAYTM_MERCHANT_KEY constant with details received from Paytm.
define('PAYTM_MERCHANT_KEY', 'XXXXXXXXXXXXXXX'); 
?>

Modify the Checksum.java file with the Merchant ID : 
Modify the Check url string in checksum.java file for creation of your checksum.

Create the Merchant ID : 

Goto the Paytm dashboard : https://dashboard.paytm.com 

Create the Api key For Test Purpose : https://dashboard.paytm.com/next/apikeys
 
Go through this document with each word : https://developer.paytm.com/docs/all-in-one-sdk/

Enable Test Mode On to see the Test data transaction : 

Watch Video if required : 

https://www.youtube.com/watch?v=luUtFBHaoZs

For PHP Application Watch this Video : https://www.youtube.com/watch?v=s7GyXQdAQ_Q






