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

**3. Verify Customer contacts management (Customer contacts managements) according API Security Checklist. Make report in SOLUTION.md and commit it.**
==================================

