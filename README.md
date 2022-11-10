## CIS-1051 Work Order App

## Goals

- Develop working universal field work order app.
- Provide researched information about similar apps and software and how developing this app can solve problems other services cannot
- Contribute the application to the open-source community to better improve developers and software globally.
- Develop the application using the DevOps process of developing and maintaining the software.

## Step 1 - Plan

- Decide framework to develop app on - Chose AppSheet - **Complete**
- Organize what data is needed and how it will be stored and organized.
  - User Database - **Complete**
    - First, Last name
    - email
    - password - Google
    - role - User, Admin - **Requires Attention**
      - Flow of what admin user does and regular user does
  - Work Order Database - **Complete**
    - WorkID - Random Numbers
    - Customer Name
    - Customer Address
    - Customer Phone Number
    - Appointment Start - start time
    - Appointment End - end time
    - Status
    - User Assigned
    - Task
    - Notes
- App UI

  - Admin Views
    - Assigned Orders to Users
    - Unassigned Orders
    - Order History By User
      - Group by User
      - Sort By complete date
    - Issue Orders by User
      - Orders marked as issue
      - User still assigned
      - Reschedule Button
        - Copies work order and makes new Work Order ID
        - Sets status to unassigned and move order to "Unassigned Orders"
  - User Views
    - My Orders
      - Issue Buttom
        - Prompts for notes
        - Marks Status as issue
        - Keeps user assigned for Admin action
    - Completed Order History
      - All orders completed by user

- App needs to accomplish key goals
  - Assign work orders to users.
  - Be able to complete work orders
    - Requirements for work order completion?
      - Complete - True/False - Button
      - Signature if needed
      - Signature = True/False
      - Date of completion
      - Notes required
    - Able to complete order and what data needs to be changed upon completion.
      - Changed Data

## Step 2 - Code

- User Database - **In Progress**
  - First, Last name - **Requires Attention**
  - email - **Requires Attention**
  - password - Google - **Complete**
  - role - User, Admin - **Requires Attention**
  - Work Order Database - **In Progress**
    - WorkID - Random Numbers
    - Customer Name
    - Customer Address
    - Customer Phone Number
    - Appointment Start - start time
    - Appointment End - end time
      - Admin Assigns User at time of scheduling
    - Status
    - User Assigned
    - Task
    - Notes
    - Customer Sigature
    - User Start time
    - User End time
- App UI - **In-Progress**
  - Unassigned Orders - Deck View
    - User View
    - Admin View
  - My Orders - Calendar View
