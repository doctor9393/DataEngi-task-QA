# DataEngi-Task3
**1. Discover backend API for UI requests (https://github.com/dataengi/crm-seed) and save the result of testing as a project on the own repository. Create bug reports if they are.**
==================================
**Description of the testing process**

Testing was carried out manually using docker. Relying on API requests which are implemented in Swagger, which can find in docker by using port 9000 and adding " /docs" to link in the address bar. API requests were analyzed.
Requests were analyzed in such a way(on the example "Create a Contact Group"):

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

Testing was carried out manually using docker. Relying on API requests which are implemented in Swagger, which can find in docker by using port 9000 and adding " /docs" to link in the address bar. API requests were analyzed.

**The testing process was as follows for  "POST /api/v1/contacts/group/create Create new group":**

1. Analysis of request data for "POST /api/v1/contacts/group/create Create new group"

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/API1.jpg)

2. Analysis of data through function "Inspect Element" in the browser for check "Delete a Contact" for "POST /api/v1/contacts/group/create Create new group"

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/API2.jpg)

3. Enter invalid data for request (Obtaining Error (code 400)):

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/API3.jpg)

4. Enter valid data for request (Obtaining an existing record(code 200)):

![Image alt](https://github.com/doctor9393/DataEngi-task-QA/blob/master/Task3/photos/API4.jpg)
