# User Management Screen - UI Specification Document

## Requirements:

- The User Management screen is responsible for managing user accounts within the application.
- Users should be able to view existing users in a table format.
- Users should be able to add new users through a panel.
- Users should be able to enable or disable user accounts.

## User Interface Components:

1. User Table:
   - **ID:** Unique identifier of the user.
   - **User Name:** Name of the user.
   - **Email:** Email address of the user.
   - **Enabled:** Toggle switch to enable or disable the user account.

2. Add User Panel:
   - **User Name:** Text field to enter the name of the new user.
   - **Display Name** Text field to enter display name.
   - **Email:** Text field to enter the email address of the new user.
   - **Phone** Text field for user's phone number.
   - **Enabled:** Checkbox to indicate whether the new user account should be enabled or disabled.
   - **User Role** Menubar to pick one role for user.

## Page Behavior:
- Upon loading the User Management screen, the table should display the existing users retrieved from the database.
- Users can toggle the "Enabled" switch in the table to enable or disable the user account.
- Clicking on the "Add User" button should display the Add User Panel.
- After filling in the required information in the Add User Panel, users can click the "Save" button to add the new user to the database.
