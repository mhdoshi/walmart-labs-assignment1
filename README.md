# walmart-labs-assignment1

##**Question**

Automate an end-to-end user e-commerce transaction flow using any open source tool for www.walmart.com with an existing customer on Chrome or Safari browser.
* I have used Selenium Webdriver tool, with java as programming language to develop the project and testNG to write my tests.

##**To run the tests you will need:**

* Eclipse
* TestNG plugin for eclipse. You can install the plugin by following the steps on this webpage : http://testng.org/doc/download.html
* Add selenium jars to this project. You can download the jars from: http://www.seleniumhq.org/download/
* To run the tests on Chrome you will need to download and edit the path to chromedriver.exe to the location in your local machine in the EToETransactionFlow  class under src/test folder. Download link for ChromeDriver: https://sites.google.com/a/chromium.org/chromedriver/downloads
* Run the EToETransactionFlow class as testNG tests.

##**About the project**

* The project is developed using the Page Object Model.
* The main/pageObjects folder contains all the Page classes which contain methods used to interact with the elements on that page.
* The main/services folder contains all the services that contains step by step execution of the tests.
* The test folder contains EToETransactionFlow class that contains two tests first one to setup the webdriver and login into your account and the second test shows the end to end transaction from adding an item to the shopping cart and removing it after asserting only one item is added to the cart.
* Every time the test is run a random item from the list containing items: tv, dvd, socks, toys is picked and added to the cart.
* The item iPhone takes a little longer for the page to load and because of the time constraint I have not been able to figure out a good solution for it. Hence I have not added iPhone to the list of items.
* I have also added manual execution steps to the console to give more clarity on how the tests are being executed.

