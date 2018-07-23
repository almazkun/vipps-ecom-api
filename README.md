# Vipps eCommerce API version 2

This repo contains developer resources for the Vipps eCommerce API. For more information about this product, "Vipps på Nett", please see: https://www.vipps.no/bedrift/vipps-pa-nett

**IMPORTANT:** This is a work in progress! Expect sudden, breaking changes :boom: The official, stable developer resources for Vipps is still https://vipps.no/developer

If you want to contribute here on GitHub: Great! No issue or pull request is too small 👍

See the main GitHub page for Vipps contact information, etc: https://github.com/vippsas  

You can peruse the api-docs at https://vippsas.github.io/vipps-ecom-api/


# Vipps Developer Portal

This section will explain how merchants can start using Vipps APIs and get access to API credentials.

We start with the typical Sign-in screen.

![Alt text](relative/path/to/img.jpg?raw=true "Title") Sign on screen

You type in your username and password here.
Now remember that there's a difference in both production and test when it comes to Vipps Developer Portal.

Link for Vipps Developer in test: https://apitest-portal.vipps.no/
- You will be given a username that looks like this: username@testapivipps.no
- And a default password. For password-change please contact integration@vipps.no

Link for Vipps Developer in production: https://api-portal.vipps.no/
- You will be given a username that looks like this:
username@apivipps.no
- And a default password. For password-change please contact integration@vipps.no

**IN CASE OF ERROR-SCREEN SHOWN ON THE PICTURE UNDER:**

![Alt text](relative/path/to/img.jpg?raw=true "Title") Error-screen

- Make shure that you are also logged out of other 365-accounts
- Make shure you are in incognito-modus in either Google Chrome or Windows Edge
- Make shure you are using the correct url. Remember https://apitest-portal.vipps.no/ for test, and https://api-portal.vipps.no/ for production.

After an successfull log-in you will see the admin-name up in the right corner of the screen. In the left corner you have several tabs.
The "Manage User" - gives you the possibility to add users. 
