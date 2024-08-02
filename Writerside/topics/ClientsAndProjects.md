

# Clients and projects

![Manage-clients](MSS_worksite_management.jpg)

## Clients and projects overview

After selecting the option "werfbeheer" in the admin console, you will see a list of clients and their projects. On this
page you will be able to [create a client](#create-a-client) or set existing clients and projects to active/inactive.

![Set-project-inactive](MSS_worksite_management_non-active.jpg)

## Create a client
<img src="CreateClientButtonHighlighted.png" width="32%"/>
<img src="CreateClientErrorMessageHighlighted.png" width="32%"/>
<img src="CreateClientSaveButtonHighlighted.png" width="32%"/>
The admin will be able to create new clients.  
He will be able to provide a client name. 
When entering a new client's name, the system will also check the existing list of clients to find a match, to prevent double entries. An error message will be shown when the name is already in use. The admin also has to enter the starting date for the client. The admin will then have the option of entering an end date. The end date is not mandatory but when given it can not be before the starting date. After pressing the save button, a new client is created and the application will navigate to the created clients [detail page](#clients).

## Create a project

<img src="ProjectCreateAddButtonHighlighted.png" width = 32%/>
<img src="ProjectCreateClientProjectOverviewCreateHighlighted.png" width = 32%>
<img src="ProjectCreateSaveButtomBasicHighlighted.png" width = 32%/>
<img src="ProjectCreateSaveButtomViaClientHighlighted.png" width = 32%/>
<img src="ProjectCreateErrorMessageHighlighted.png" width = 32%/>

The admin will be able to create projects for existing clients.
He can do this from the projects page and select any of the available clients or do this from a client detail page where he can create a project with that client already selected as the linked client.  
He will be able to provide a project name, linked client, start date, end date and the distance of the project. The project name, linked client, start date and distance are all mandatory fields to fill out. End date is the only field that is not mandatory but when entering an end date it, can not be before the start date. When entering a new project's name, the system will also check the existing list of projects to find a match, to prevent double entries. An error message will be shown when the name is already in use. After pressing the save button, a new project is created and the application will navigate to the created projects [detail page](#projects)

## Modify client or project

### Clients

The admin can navigate towards the client ("KLANTEN") page. Here you will get an overview of all the clients you have created earlier. Here you want to click on the client name in the list. This will open up a new detail page that shows all data linked to that client.
![Client-detail](Client_detail_page.png)

#### Change clientname
The admin can change the clients name by clicking the pencil icon next to the client name.
![Change-client-name](Change_Client_Name.png)

After changing the name you can click the "OPSLAAN" button to navigate back to the detail page of the client.
If you make no changes you can navigate back to the detail page of the client by clicking on "Terug naar ..." under the title.

![Change-client-name](Change_name_detail_page.png)

#### Deactivate or delete client
##### Deactivate client
The admin can also deactivate the client by clicking the "Acties" button and clicking on "Zet op inactief. Like deactivating a client you can also active them again doing the exact same proces as deactivating but clicking "Zet op actief". Deactivating a client will also deactivate all projects linked to that client.

![Change-client-status](Deactivate_Client.png)

##### Delete client
The admin can delete a client and all his projects by clicking the "Acties" button and clicking on "Verwijder". If there are no clockings the client and all his projects will be removed . If there are clockings for this client and at least one project it will archive the client.

#### Change client information
By clicking on the pencil in the title of "Klant informatie" you will open the detail page for the information of the client.

![Change-client-information](Change_client_information.png)

In the client information detail page you can change one or all the information fields. After modifying the information you click on the "OPSLAAN" button and return to the client page. If you make no changes you can navigate back to the detail page of the client by clicking on "Terug naar ..." under the title.

![Change-client-information-details](Change_client_information_detail.png)

#### Change client contact information
By clicking on the pencil in the title of "Contact informatie" you will open the detail page for the contact information of the client.

![Change-client-contact-information](Change_client_contact_information.png)

In the client contact information detail page you can change one or all the information fields. After modifying the information you click on the "OPSLAAN" button and return to the client page. If you make no changes you can navigate back to the detail page of the client by clicking on "Terug naar ..." under the title.

![Change-client-contact-information-details](Change_client_information_detail.png)

#### Adding a project to the client
By clicking on the "+ Nieuw project" the admin can add a new project for the client.

![Client-add-project](Client_ad_project.png)

The admin will be able to create projects for existing or new clients.
He will be able to provide a project name and the distance of the project. In addition, the admin has to enter a start date. The end date is not necessary but if used it can not be before the start date.
After entering the necessary fields you can click on the "OPSLAAN" button. You return to the client page and the new project is visible in the list of projects from the client.

![Client-add-project-detail](Client_ad_project_detail.png)

### Projects
By clicking in the row of one of the projects in the list on the client detail page the admin navigates to a new detail page that shows all data linked to that project.

![Client-open-project](Client_open_project.png)

In the projects detailpage the admin can see and change all the information concerning the project.

![Update-project](Edit_options_project_filled.png)

By clicking on the name of the client the admin will navigate back to the client detailpage.

![Update-project_navigate_to_linked_client](Project_navigate_to_linked_client.png)

#### Change project name
By clicking on the pencil next to the project name a new detail page opens.

![Update-project-name](Change_project_name.png)

After changing the name you can click the "OPSLAAN" button to navigate back to the detail page of the project.
If you make no changes you can navigate back to the detail page of the project by clicking on "Terug naar ..." under the title.

![Update-project-name-detail](Change_project_name_detail.png)

#### Change client for project

The admin can change the client for the project by clicking on the pencil next to the client name.

![Update-project-linked-client](Change_project_linked_client.png)

The admin can choose the name of the client from the dropdown list which contains the available clients. After changing the client you can click the "OPSLAAN" button to navigate back to the detail page of the project.
If you make no changes you can navigate back to the detail page of the project by clicking on "Terug naar ..." under the title.

![Update-project-client](Change_project_client.png)

#### Change project information

By clicking on the pencil in the title of "Project informatie" you will open the detail page for the information of the project.

![Update-project-info](Change_project_information.png)

In the porject information detail page you can change one or all the information fields. After modifying the information you click on the "OPSLAAN" button and return to the project page.
If you make no changes you can navigate back to the detail page of the project by clicking on "Terug naar ..." under the title.

[//]: # (TODO: add project info detail page)


#### Change project contact information

By clicking on the pencil in the title of "Contact informatie" you will open the detail page containiung the contact information of the project.

![Update-project-contact](Change_project_contact_information.png)

In the project contact information detail page you can change one or all the information fields. After modifying the information you click on the "OPSLAAN" button and return to the project page.
If you make no changes you can navigate back to the detail page of the project by clicking on "Terug naar ..." under the title.

![Update-project-contact-details](Change_project_contact_information_detail.png)

#### Change project pictures

The admin can navigate to a detailpage for pictures of the project by clicking on the pencil in the title of the "Project foto's".

![Update-project-pictures](Change_project_pictures.png)

In the detail page for the pictures the admin can upload, download and delete pictures

![Update-project-pictures-details](Change_project_pictures_detail.png)

## Deleting client and project

The admin will be able to delete existing clients and projects. Only clients and or projects with no logged working
hours can be deleted. If there are logged working hours the client and or project will be archived for future purposes.

### Deleting client

When deleting a client a popup will ask you to confirm that you want to delete the client. After confirming this
the client will no longer be visible in the list. Only clients with no logged working hours will be completely removed.
If a client has logged working hours the client will be kept in the archive.

### Deleting project

When deleting a project a popup will ask you to confirm that you want to delete the project. After confirming this
the project will no longer be visible in the list. If the project had no logged working hours it is completely removed.
In case there are logged working hours the project will be kept in the archive.

## Merge existing projects (Optional: not in project scope)

In the event of a double entry for the same project, the admin will be able to merge these entries to make sure all the
worked hours for these entries are properly linked to one project.