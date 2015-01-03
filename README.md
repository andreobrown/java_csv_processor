André Brown
http://www.odesk.com/users/~~1496387fd982a460

Processing a CSV Demo
=============================

This is a small a small application to demonstrate my understanding of the functional requirements for the project I am applying for.

Demo Contents
=============================

This demo consists of one (1) JAR file and two (2) CSV files:

- PaypalCSVDemo.jar
- PayPalDemo.csv
- Rules.csv

The JAR file is the application which can be run on any computer with Java installed.

What's In The CSV Files
==============================

The PayPalDemo.csv file contains a sample set of transactions.

The Rules.csv file contains a list of rules (what were referred to as categories in the job posting).

The application reads the csv files and compares the transactions against the rules, and outputs transactions which match specific rules.  You may add categories by adding a rule to the Rules.csv file.

Rule Formats
===============================

The format for the rules is as follows:

<Rule Name>,<Field To Match>:<Value To Match>,<Field To Match>:<Value To Match>...

You may include as many field value pairs as required.

The application matches transactions based on rules containing "Name", "Type", "Currency", and "Amount", where "Amount" can be equal to "Debit" or "Credit".

How To Run The Demo on Windows
================================
To run the application simply double-click the RunDemo.bat file.

Other Plaforms
================================

If you are on a platform other than Windows, then you can run this demo from the command line using the following command to be executed from the directory containing the JAR file:

java -jar PaypalCSVDemo.jar

If you wish to have a script created to launch the demo on another platform, please contact me.
