# DecadisTask2

README.txt

1. Automation Tool/Design/FrameWork Used in Project:

      I have executed this task using Selenium_Webdriver, with Java as programming language with TestNG framework
 and POM design (page object model)

   
2. Project Framework Structure

 Project name : DecaTask02

 

                1. BaseClass                    -               Base1

                2. WebElementPages               -              1.CustomerCreatePage


                3. TestCases                      =             1.VerifyCreateAccPage

                                                                2.VerifyLandingHomePage

3.Test Runner


    *Since i have implemented in a TestNG framework, need to use testng.xml file as runner file

    *you can find testng.xml file at the end of project file after Test-output folder and pom.xml file

    * Open the testng.xml file, already I have written the suite script in the file. So to execute, Right click on the opened file,
      select Run as -> TestNG suite.
    * I have included following 2 test cases in testng suite:

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE suite SYSTEM "https://testng.org/testng-1.0.dtd">
<suite name="TaskSuite" verbose ="2">
  <test name="TaskTestcases" verbose ="2" >
    <classes>
      <class name="Testcases.VerifyCreateAccPage"/>
      <class name="Testcases.VerifyLandingHomePage"/>
      </classes>
  </test>
</suite> 



4. View Report

    * You can view the test results in the console
    * Also can view the test results in Test Out-put folder after refreshing the folder/project
    * Extend the Test out-put folder, select either one junit report/emailable-report.html/index.html

