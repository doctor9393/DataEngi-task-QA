# DataEngi-Task3
**1. Write user story for Customer contact add according to Agile best practice**
==================================
**1. User story for Customer contacts :**

**As an employee of the company I want to get convenient access to the contact database of clients with the purpose to manage of customer contacts and their accounting.**

**Acceptance criteria:**
1. As an employee of the company, I have the opportunity to create a new contact.
2. As an employee of the company, I have the opportunity to edit the contact.
3. As an employee of the company, I have the opportunity to remove the contact.
4. As an employee of the company, I have the opportunity to filter contacts on the specified fields.
5. As an employee of the company, I have the opportunity to create a group of contacts.
6. As an employee of the company, I have the opportunity to add contacts to the group.
7. As an employee of the company, I have the opportunity to delete a contact group.
8. As an employee of the company, I have the opportunity to remove a contact from the group.
9. As an employee of the company, I have the opportunity to use the search for contacts for certain data.

**2. User story for Customer contact add :**

**As an employee of the company, I want to add customer contacts to the customer contact database for the purpose of their accounting.**

**Acceptance criteria:**
1. As an employee of the company, I have the opportunity to create a new contact.
2. As an employee of the company, I must fill in the required fields to create a new contact.
3. As an employee of the company, I have the opportunity to create a new contact with several email addresses and phone numbers.

**2. Write 2 use cases for Customer contact add according to Agile best practice**
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

**3. Write 3 requirements for Customer contact add**
==================================

**Functional requirements:**
1.	A user with the appropriate rights must be able to add a new contact.
2.	For the add a contact necessary fill out in the required fields (Name, Email (Main), Phone (Main)) with valid data. Other fields can be blank or filled out with valid data ("Zip code" field).
3.	When creating a new contact, user can specify few email addresses and phone numbers. However, it must necessarily be indicated Email (Main), Phone (Main)

**Add five new contacts from table:**
![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/forTask2.jpg)

