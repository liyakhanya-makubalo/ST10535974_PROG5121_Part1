# Chat Application - Part 1

## Student Information
-Name: Liyakhanya

-Student Number: ST10535974

-Module: PROG5121

---
##Project Information

I have created a chat app that consists of three classes:
-Login.java
-MainApp.java
-LoginTest.java

##Login.java

I first created a Login class that included of a username, password and a phone number. The user's details after being entered will be captured. User's details have requirements and restrictions on how the infromation they enter should be.

-Username: The username needs to contain five characters or less and also include an underscore

-Password: The password needs to be eight characters long, hava a special character in it, A number or 2 and an uppercase.

-Phone number: The number needs to start with the South African code and the characters need to be twelve characters long.

Ater the user's details have been logged in, the information will be compared with the one that is saved and if they do not match they will get a return message if successful that says, "Welcome" + username + " it is great to see you agin." or if unsuccessful "Username or password incorrect, please try again"

##MainApp.java

The MainApp allows the application to work and users to register.I started by importing the scanner class inside so that methods created in the login class can be used. A scanner object is created inside main method to allow user to enter their details. Then the registerUser method is used and the results are shown. User is then asked to enter details to login. After entering them a message will pop up to show if lohin was sucessful or not.


##LoginTest.java

you then do a login in test to know if your code is working or not.

---
##Features

### Username Validation

The username must contain an underscore and should contain five or less characters

### Password Validation

The password must be eight characters long, should include a capital letter and a special character

###Phone Number Validation

The number must start with a South African code and must be twelve characters long



