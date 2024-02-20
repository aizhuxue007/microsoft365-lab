# Microsoft Office 365 (M365) Homelab Setup Guide

This guide outlines the steps for creating Exchange mailboxes, shared calendars, and email distribution groups in Microsoft Office 365 (M365), along with assigning the necessary permissions.

## 1. Setting Up Exchange Mailboxes

### Log into the Microsoft 365 admin center

- Navigate to [https://admin.microsoft.com](https://admin.microsoft.com) and sign in with your admin account.

### Go to Users > Active users

- Click on **Add a user** to create a new user account. Fill in the information, including the user's name and username.

### Assign a Microsoft 365 license

- During the user creation process, make sure to assign a license that includes Exchange Online (for example, Microsoft 365 Business Standard).

### Finish and create the user

- Once the account is created, an Exchange mailbox is automatically provisioned for the user.

## 2. Creating Shared Calendars

### Create a shared mailbox

- In the admin center, navigate to **Teams & Groups > Shared mailboxes**.
- Click **Add a mailbox** and enter a name for the shared mailbox; this mailbox will also have a shared calendar.

### Access the shared calendar

- Users can access the shared calendar by adding the shared mailbox to their Outlook app.

## 3. Setting Up Email Distribution Groups

### Navigate to Teams & Groups > Groups in the admin center

- Click on **Add a group** and select **Distribution** as the group type.
- Fill in the name, description, and email address for the group.
- Add members to the group.

## 4. Assigning Permissions to Mailboxes and Calendars

### Mailbox permissions

- Go to **Users > Active users** and select the user.
- Under "Mail" settings, you can set permissions such as **Read and manage** or **Send as** for another mailbox.

### Shared mailbox permissions

- Navigate to **Teams & Groups > Shared mailboxes**.
- Select the shared mailbox, and under **Mailbox permissions**, add users or groups who need access.

### Shared calendar permissions

- The easiest way to manage permissions is through Outlook. Right-click the calendar in Outlook, choose **Properties**, and go to the **Permissions** tab.
- Here, you can add users and define their level of access (e.g., reviewer, editor).

### Distribution group permissions

- If you need to manage who can send emails to the distribution group, go back to the group settings in the admin center.
- Under **Group delegation**, you can set **Send As** or **Send on Behalf** permissions.

## 5. Verification and Testing

- After setting up mailboxes, shared calendars, and distribution groups, **test** to ensure everything works as expected.
  - Send test emails to the new mailboxes and distribution groups.
  - Schedule a meeting using the shared calendar and make sure all intended participants can see it.
