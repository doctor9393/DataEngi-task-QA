# DataEngi-Task3(Bug report)
**Bug 1. Scaling problems when enter a large number of characters in the different fields.**
==================================

**Expected behavior:**

When creating a new contact or group, user can enter same large amount characters in the different fields, and the user interface look correctly.

**Actual behavior:**


When creating a new contact or group, user can enter same large amount characters in the different fields, and the user interface look not correctly.(**"Screenshot. Bug 1", "Screenshot. Bug 2", "Screenshot. Bug 3"**).

**Precondition:**

A user should be login with Root role.


**Steps to reproduce:**

1. Go to tab "Contacts".
2. Click on the button "Add contact".
3. Enter too many characters in the different fields(Look on the **"Screenshot. Bug 2"**).
4. Click button "Submit".

Or

1. Go to tab "Contacts".
2. Click on the button "Group".
3. Enter in the field "Enter new group name" more that 25 characters, the maximum possible amount.
4. Click button "Add".
5. Select checkbox near name of any contact.
6. Click on the item "Add to group"

**Screenshot. Bug 1**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/BugsPhotos/Bug1.jpg)

**Screenshot. Bug 1**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/BugsPhotos/Bug2.jpg)

**Screenshot. Bug 1**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/BugsPhotos/Bug3.jpg)

