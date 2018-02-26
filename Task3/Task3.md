# DataEngi-Task3
**1. Discover backend API for UI requests (https://github.com/dataengi/crm-seed) and save the result of testing as a project on the own repository. Create bug reports if they are.**
==================================
**Description of the testing process**

Testing was carried out manually using docker. Relying on API requests which are implemented in Swagger, which can find in docker by using port 9000 and adding " /docs" to link in the address bar. API requests were analyzed.
Requests were analyzed in such a way(on the example  added "Create a Contact Group"):

1. Consider individual requests
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/GroupCreate1.jpg)

2. The types of requests for information that is returned are considered

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/GroupCreate2.jpg)

3. Then the requests were executed through the interface of the program.

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/GroupCreate3.jpg)

4. Then the information was analyzed through function "Inspect Element" in the browser.

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/GroupCreate4.jpg)

**Using function "Inspect Element" in the browser for check "Delete a Contact"**

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/Delete%20of%20contacts.jpg)

**Using function "Inspect Element" in the browser for check "Update of group"**

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/UpdateOfGroup.jpg)


**During the testing, problems with the user interface were detected, bugs are described in document "Bug report.md" in folder "Task3".**


**2. Discover Swagger implementation https://github.com/dataengi/crm-seed/blob/master/conf/routes. Try to execute API requests or create bug reports if they are.**
==================================
**1. Use case for adding a new client contact**

**Goals:** add a new contact

**Actors:** user, system

**Precondition:** the user is authorized in the system with the corresponding rights

**Successful scenario:**
1.	User choosing "Contacts" tab from sidebar.
2.	The system displays the page "Contacts".
3.	User сlick on the "Add contact" button.
4.	The system displays dialog window "New contact".
5.	The user fill out required fields (Name, Email (Main), Phone (Main)) with valid data in the "New Contact" form.
6.	User enters valid data in the field "Zip code" or leaves field empty in the "New Contact" form.
7.	User click on the button "Submit".
8.	The system adds new contacts on the "Contacts" page.


**Post conditions:** contacts of the newly added client appear on the page "Contacts"


**2. Use case for adding a new client contact with invalid data**

**Goals:** it is not possible to add a new client contact with empty required fields or with invalid data

**Actors:** user, system

**Precondition:** the user is authorized in the system with the corresponding rights

**Successful scenario:**
1.	User choosing "Contacts" tab from sidebar.
2.	The system displays the page "Contacts".
3.	User сlick on the "Add contact" button.
4.	The system displays dialog window "New contact".
5.	User not fill out any required fields(Name, Email (Main), Phone (Main)) or fill out invalid data in “New Contact” form.
6.	User enters invalid data in field “Zip code” or leaves field empty in “New Contact” form.
7.	User click on the button “Submit”.
8.	The system does not add new customer contacts.


**Post conditions:** the fields which needed to fill are highlighted.

**3. Verify Customer contacts management (Customer contacts managements) according API Security Checklist. Make report in SOLUTION.md and commit it.**
==================================

**Functional requirements:**
1.	A user with the appropriate rights must be able to add a new contact.
2.	For the add a contact necessary fill out in the required fields (Name, Email (Main), Phone (Main)) with valid data. Other fields can be blank or filled out with valid data ("Zip code" field).
3.	When creating a new contact, user can specify few email addresses and phone numbers. However, it must necessarily be indicated Email (Main), Phone (Main)

**Add five new contacts from table:**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/forTask2.jpg)

