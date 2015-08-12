READ ME

Standard Disclaimer: This code is not official IDX Broker code. It does use their API, but in NO WAY is it supported by IDX Broker. DO NOT contact IDX Broker for any support of this code.
This alo applies to any CRM in this repo. It does use their API, but in NO WAY is it supported by them. DO NOT contact them for any support of this code.

I DO NOT recommend attempting to get and pass lead data every second or evey minute. A goal of "real time" updating is not practical nor useful in my opinion. I would suggest every 15 min.

These examples only pass basic lead information. Additionally information can be added. Some additional infomrmation may require further lead ID specific API calls.

These scripts likley will require you have active accounts with each service you wish pass leads to and from.

You will also need the Force.com PHP tool kit for the Salesforce API call

Remember that changing your password in Salesforce resets you Security Token as well

Rememeber that Enterprise and Partner ahve API calls enabled by default. Group and Professional are another story. Contact Salesforce for details on this.

For more on these calls check the official docs

API Docs:

http://middleware.idxbroker.com/docs/api/1.1/index.php

https://developer.salesforce.com/page/PHP_Toolkit

http://www.bombbomb.com/api/

https://api.followupboss.com/api-documentation/

http://developers.contactually.com/docs/

For more detail on each call visit this wiki for this repo
