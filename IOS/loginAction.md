# Login Action

## Test Description

This case tests the functional side of login action.
 ***

## Precondition

* starting the app
* Face ID or Touch ID should be cancelled.
* previous user should sign out.
* if a user logged in before then the user's username should be cleared.

***

## Scenario 1 Empty Username AND/OR Password fields

Checking if we are getting correct error message.

### S1: Input

* AND/OR empty username field
* AND/OR empty password field
* click the login button

### S1: Expected Result

* [ ] Error Message: "Username and password fields cannot be empty"

***

## Scenario 2 Wrong Username AND/OR Password

Checking if we are getting correct error message.

### S2: Input

* AND/OR wrong username field
* AND/OR wrong password field
* click the login button

### S2: Expected Result

* [ ] Error Message: "Error: Invalid credentials!"

***

## Scenario 3 Correct Username AND Password

Checking if "Machines" screen is opened when username and password correct

### S3: Input

* correct username field
* AND correct password field
* click the login button

### S3: Expected Result

* [ ] "Machines" screen is visible

***
