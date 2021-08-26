# Cognito-Intergation-HTMLJS
Sample code to help with integration of AWS cognito with HTML and JS files. Include Login/Signup and get Session

Follow the below steps to set up AWS Cognito User Pool

Select Create a new user pool

Enter Name and click on Step through settings

The blow page is one time setupu only. Cannot be Changed afterwards. You can select User attributes and also define custom attributes. As of now just select email

In Next step, we define policy for passwords

Next Page is for MFA and how to recover passwords. Keep it as defaults and select checkbox if required.

Next Page is for setting up custom message for verification. 

The next Page is Tags. You can skip it as of now.The next page is Device. You can configure it according to your preference.

Click on add app client in next page. Uncheck Client secret key.

The next Page is Triggers. This can be used if we want to customize the authentication feature. No need to add anything as of now.

Next is the review page. Check the details and create it.


Once done, in the folder .
Go to Config. js and enter details for your own aws cognito user pool.
