# DataEngi-Task3(Bug report)
**Bug 1. Scaling problems when enter a large number of characters in the field "Group name".**
==================================

**Expected behavior:**

When creating a new group, user can enter a maximum of 25 characters in the field "new group name", and the user interface look correctly.

**Actual behavior:**

Users can enter mare thar 25 characters and the system will save the record, and user interface displayed not correctly(Look on the **"Screenshot. Bug 1"**).

**Precondition:**

A user should be login with Root role.


**Steps to reproduce:**

1. Go to tab "Contacts".
2. Click on the button "Group".
3. Enter in the field "Enter new group name" more that 25 characters, the maximum possible amount.
4. Click button "Add".
5. Select checkbox near name of any contact.
6. Click on the item "Add to group"

**Screenshot. Bug 1**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/BugsPhotos/Bug1.jpg)

**Bug 2. Scaling problems when enter a large number of characters in couple fields during creating new contacts.**
==================================

**Expected behavior:**

When creating a new contact, user can enter same large amount characters in the different fields, and the user interface look correctly.

**Actual behavior:**

Users can enter too many characters and the system will save the record, and user interface displayed not correctly(Look on the **"Screenshot. Bug 2"**).

**Precondition:**

A user should be login with Root role.


**Steps to reproduce:**

1. Go to tab "Contacts".
2. Click on the button "Add contact".
3. Enter too many characters in the different fields(Look on the **"Screenshot. Bug 2"**).
4. Click button "Submit".

**Screenshot. Bug 2**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/BugsPhotos/Bug2.jpg)

**Bug 3. Scaling problems when enter a large number of characters in the field "Group name".**
==================================

**Expected behavior:**

When creating a new group, user can enter a maximum of 25 characters in the field "new group name", user interface look correctly.

**Actual behavior:**

Users can enter mare thar 25 characters and the system will save the record, and user interface displayed not correctly, аunction buttons disappear(Look on the **"Screenshot. Bug 3"**).

**Precondition:**

A user should be login with Root role.


**Steps to reproduce:**

1. Go to tab "Contacts".
2. Click on the button "Group".
3. Enter in the field "Enter new group name" more that 25 characters, the maximum possible amount.
4. Click button "Add".
5. Try to delete new group.

**Screenshot. Bug 1**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/BugsPhotos/Bug3.jpg)


