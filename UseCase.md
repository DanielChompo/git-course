# Use Case for QA Challenge

### User Goals and System functions:
Log in Successfully to https://qa-challenge.ensolvers.com and manage the to-do items and folders, validate that all the functions works as planned by creating items and folders.
  -	Validate the log in screen
  -	Validate the to-do items functions
  -	Validate the Folders funcitons

### Basic Flow to validate:
  - 1.- On Log In screen user insert a Valid User and Valid Password.
  - 2.- User Clicks on “Log In” button.
  - 3.- User successfully access to Ensolvers QA Challenge.
  - 4.- User creates new To-Do Items and Folders.

### Alternative Flow:
 - 1.- On Log In screen user insert a Invalid User or Invalid Password.
 - 2.- User Clicks on “Log In” button.
 - 3.- System display an error message

### Test Case (Basic Flow):
#### Test Case ID: TEST-001
#### Test Description: Successful Log In attempt.
#### Preconditions: Having valid credentials.
#### Test Steps:
- 1.- On Log In screen insert a Valid User and Valid Password.
- 2.- Clicks on “Log In” button.
#### Expected Results: System Display Home window and successfully grant access.
#### Test Data: Valid user credentials

### Test Case (Alternative Flow):
#### Test Case ID: TEST-002
#### Test Description: Error on Log In attempt.
#### Preconditions: Having Invalid credentials.
#### Test Steps:
- 1.- On Log In screen insert a Invalid User or Invalid Password.
- 2.- Clicks on “Log In” button.
#### Expected Results: System Display an error message.
#### Test Data: Invalid user credentials

### Test Case (Basic Flow):
#### Test Case ID: TEST-003
#### Test Description: Creation and Modification of a To-Do Item.
#### Preconditions: User is Logged In.
#### Test Steps:
- 1.- Click on “Manage To-Do Items” button.
- 2.- Click on Create new To Do Item.
- 3.- Fill all the information for the Item
- 4.- Save the new To Do Item
- 5.- Edit any information of the created To Do Item
- 6.- Delete the created To Do Item
#### Expected Results: 
- 4.- The Item was successfully created
- 5.- The Item info was successfully edited
- 6.- The Item was successfully deleted
#### Test Data: Valid User credentials to Log In.
 
### Test Case (Alternative Flow):
#### Test Case ID: TEST-004
#### Test Description: Creation of To-Do Item.
#### Preconditions: User is Logged In.
#### Test Steps:
- 1.- Click on “Manage To-Do Items” button.
- 2.- Click on Create new To Do Item.
- 3.- Fill all the information except for the required field of the Item
#### Expected Results: The To Do Item fails to be created since the required field is empty
#### Test Data: Valid User credentials to Log In.

### Test Case (Basic Flow):
#### Test Case ID: TEST-005
#### Test Description: Creation and Modification of a Folder.
#### Preconditions: User is Logged In.
#### Test Steps:
- 1.- Click on “Manage Folders” button.
- 2.- Click on Create new Folder.
- 3.- Fill the Required Name field for the Folder.
- 4.- Save the new Folder.
- 5.- Edit the Name field of the created Folder.
- 6.- Delete the created Folder.
#### Expected Results: 
- 4.- The Folder was successfully created
- 5.- The Folder info was successfully edited
- 6.- The Folder was successfully deleted
#### Test Data: Valid User credentials to Log In.


### Test Case (Alternative Flow):
#### Test Case ID: TEST-006
#### Test Description: Creation of Folder.
#### Preconditions: User is Logged In.
#### Test Steps:
- 1.- Click on “Manage Folders” button.
- 2.- Click on Create new Folder.
- 3.- Leave empty the Required Name field for the Folder.
#### Expected Results: The Folder fails to be created since the required field is empty
#### Test Data: Valid User credentials to Log In.

## CRs created:
https://daniel9899.atlassian.net/browse/QE-1
https://daniel9899.atlassian.net/browse/QE-3



