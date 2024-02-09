# Clients

![Manage-clients](MSS_worksite_management.jpg)

### Clients and projects overview

After selecting the option "werfbeheer" in the admin console, you will see a list of clients and their projects. On this
page you will be able to [create a client](#create-a-client.) or set existing clients and projects to active/inactive.

![Set-project-inactive](MSS_worksite_management_non-active.jpg)

### Create a client

![Add-client-and-project](MSS_add_worksite.jpg)

The admin will be able to create new clients.  
He will be able to provide a client name. The system will generate a client specific code which will also be visible in
the overview.  
When entering a new client's name, the system will also check the existing list of clients to find a match, to prevent
double entries. When creating a new client, the admin also has to enter a [new project](#create-a-project.) for this
client.
After entering a new project the admin also has to enter the starting date for the client. The admin will then have the
option of entering an end date. The end date is not mandatory but when given it can not be
before the starting date. The dates refer to both the client as the project. The dates can be modified in the
modify client or project page.



### Create a project

![Add-project](MSS_add_project.jpg)

The admin will be able to create projects for existing or new clients.  
He will be able to provide a project name and the distance of the project. In addition, the admin
has to enter a start date. The end date is not necessary but if used it can not be before
th start date. The system will generate a project specific
code which will also be visible.

### Modify client or project

To modify a client or a project you can select it in the overview.

![Change-client](MSS_modify_client.jpg)

When modifying a client, you can change its name, the start date and the end date. You can not access its projects from this page.

![Change-project](MSS_modify_project.jpg)

When modifying a project, you can change the client for whom the project is, the project's name and the distance to the
project, the start and end date. You can not edit the client's details from this page, only couple the project to a different client.

When selecting a project the name is already filled out in the form for a new project. The user can adjust the
name or enter a new name for the project. Only after pressing the button wil the project be modified. After modifying a new project it will
appear in the list.

### Deleting client and project

The admin will be able to delete existing clients and projects. Only clients and or projects with no logged working hours
can be deleted. If there are logged working hours the client and or project will be archived for future purposes.

#### Deleting client

When deleting a client a popup will ask you to confirm that you want to delete the client. After confirming this
the client will no longer be visible in the list. Only clients with no logged working hours will be completely removed. If a client
has logged working hours the client will be kept in the archive.

#### Deleting project

When deleting a project a popup will ask you to confirm that you want to delete the project. After confirming this
the project will no longer be visible in the list. If the project had no logged working hours it is completely removed. In
case there are logged working hours the project will be kept in the archive.

### Merge existing projects (Optional: not in project scope)

In the event of a double entry for the same project, the admin will be able to merge these entries to make sure all the
worked hours for these entries are properly linked to one project.
