#Hybrid Framework with Data Driven Approach and Page Object Model (POM) Pattern using PageFactory API in Selenium

##Technologies Used: 
• Selenium WebDriver 
• JDK 12 (Java Development Kit) 
• TestNG (Test Unit Framework) - Data Driven Approach
• Log4j (logging API) 
• Maven (Build Automation Tool) 
• Apache POI API (Read-Write utilities for Excel - Test Data Handling) Eclipse/IntelliJ (Java Editor) 
• Browser - Google Chrome/FireFox

##Automation Framework Architecture: 
• POM (Page Object Model) Design Page Factory API of WebDriver 
• Maven (Build Automation Tool) 
• Test Libraries for different UI Pages 
• Test Utilities for different generic functions 
• Report - Dashboard (Pass/Fail Test) by using Extent Report 
• API Jenkins - Continuous Integration Tool 
• git and GITHub Repo (Code Versioning Tool)

##Features
• Webdriver Fire Event/WebEventListener - improved console logs and screenshot on failure
Location: src\main\java\com\crm\qa\util 
• Extent Report Listener with IReporter Interface (available at TestNG)
Location: src\main\java\com\qa\ExtentReportListener
• @CacheLookup implementation improves script performance
• Data Driven approach (xml file reader through TestNG Data Provider) 

##Note
Make sure you are using the correct browser version.
You can update to your browser version by putting the driver file into the drivers folder at the root of the project.

##Running Test Cases
You can run test cases per each page object separately from each class in src\main\java\com\crm\qa\page or the whole suite through the test runner file located here: src\main\resources\testng.xml file.

##Checking TestNG Reports
• Right click on the project name and select "Refresh".
• Go to test-output folder -> right click on index.html -> Properties -> copy file location -> run index.html file in your browser to see the report.
• To see Extent Report do the same for ExtentReport.html file 

##Emailable TestNG Report
Email this file: emailable-report.html
Go to test-output folder -> right click on emailable-report.html -> copy file location -> run index.html file in your browser to see the report.

##Prerequisites: 
If config file is not populated
set up the account at https://classic.crmpro.com/index.html. Then populate your config.properties with your account values. Set up several contacts at the "Contacts page" - these are the values you are using in your ContactsPage.
