# Oracle APEX - Complete Guide

## Module 1 - What is Oracle APEX?

Oracle APEX can be generically described as a low code web application development platform that runs on top of the Oracle Database. With the release of the Oracle Cloud Free Tier you can quickly and easily get started developing APEX applications completely free of charge. The Oracle Cloud Free Tier is a combination of the Always Free Services and a 30-day Free Trial promotion where you can access a wider range of Oracle products. Because APEX is a part of the Always Free Tier any application you create should be available indefinitely provided you are still within the limitations of the Always Free Services. The full list of Always Free Cloud Services and Free Trial capabilities can be found at: [Oracle Cloud Free Tier](https://www.oracle.com/cloud/free/). Lastly, if you're interested in learning more about APEX on Always Free see my link?

Creating APEX applications is done through the browser based IDE called the "Application Builder". This is where you will use drag and drop functionality to build the basic layout of your application. You can also leverage the capabilities of CSS/HTML and JavaScript to give your application a visually stunning front end. And as this is an Oracle product, SQL and PL/SQL are fully integrated for all your data and database needs.

## Getting Started - Creating an Account & APEX Workspace

An APEX Workspace can be acquired in 2 ways. The first being through the Oracle Cloud Free Tier and the alternatively through apex.oracle.com. I suggest you sign up through the Oracle Cloud Free Tier as this allows you to take advantage of Autonomous Transaction Processing (ATP). There are a few more steps to sign up with ATP but you get a lot more. First with ATP all the mundane activities like database maintenance/cleanup, backup, security, and performance managed by Oracle. This will allow you to focus on developing high quality applications. Second, with ATP you get access to SQL Developer and Oracle Machine Learning SQL Notebooks among other products.

### Oracle Cloud Free Tier - Sign Up

Please review the directions to sign up for an Oracle Cloud Free Tier account below or follow along with this video.

1. Sign up for an Oracle Cloud Free Tier using this [link](https://www.oracle.com/cloud/free/)
      - If you already have a Cloud Account, sign in and skip to [create ATP instance](#create-atp-instance)

2. Click "Start for free"

3. Enter a valid Email address and select your Country/Territory
 
 4. Enter Account Details
      - Account Type: Personal Use
      - Cloud Account Name: Choose a name for your account
      - Home Region: Select the closest Always Free region
      - Enter in Name, Address, City, State, ZIP and Country and Mobile Number
      - Click Next to Verify
5. Enter in 6 Digit code for two-factor authentication
6. Create a password
7. Enter Credit Card information
      - Credit Card information is used **ONLY** to verify your identity
      - You will **NEVER** be charged unless you upgrade to a paid account
      - In this course you will never need to upgrade

8. Complete sign up and create account

#### Create ATP Instance

1. Sign into your Oracle Cloud Account
2. Click on the "Autonomous Transaction Processing - Create a database"
3. Leave the default settings and scroll down to create a password
4. After creating password click "Create Autonomous Database"
      - This is you admin password and used to create APEX Workspaces and manage you instance
5. Wait for your database to be created and provisioned (1-2 min.)
6. Your database is ready once ou see the green ATP logo

#### Create APEX Workspace

1. Click on Service Console
2. Click on Development
3. Click Oracle APEX
4. Login with the password you created above
5. Click Create Workspace
      - Database User: DEMO
      - Password: Enter a password
      - Workspace Name: DEMO
6. Sign into your new workspace


### Alternative apex.oracle.com - Sign Up
If you do not want to sign up for Oracle Cloud Free Tier then you may sign up for a free workspace from [apex.oracle.com](https://www.apex.oracle.com). Please review the directions to create an account using apex.oracle.com or follow along with this video.

1. Click "Get Started For Free"
2. Scroll down until you see "Request a Free Workspace"
3. Enter Workspace Details
      - First Name, Last Name, Email, Workspace
4. Enter in Schema name
5. Complete Survey
6. Accept License Agreement
7. Submit request
8. You will recieve an email to create your workspace
9. Sign into your workspace
