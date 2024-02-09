# Buildbase Functional Scope

- [Introduction](#introduction.)
- [Wireframe](#wireframe.)
    - [General](#general.)
    - [Login page](#login-page.)
    - [Homepage](#homepage.)
        - [Calendar](#calendar.)
        - [Counters](#counters.)
    - [Admin console](#admin-console.)
    -  [Manage teams](#manage-teams.)
        - [Team overview](#teams-overview.)
        - [Create a new team](#create-a-new-team.)
        - [modify](#modify-a-team.)
        - [Delete a team](#Delete-a-team.)
        - [Team leaders and members](#Team-leaders-and-members.)
          - [Adding team leaders](#Adding-team-leaders.)
          - [Removing team leaders](#Removing-team-leaders.)
          - [Adding members to a team](#Adding-members-to-a-team.)
          - [Removing members from a team](#Removing-members-from a-team)
        - [Clients and projects in a team](#Clients-and-projects-in-a-team.)
          - [Adding clients and projects to a team](#Adding-clients-and-projects-to-a-team.)
          - [Setting clients and projects inactive](#Setting-clients-and-projects-inactive.)
    - [Manage users](#manage-users.)
        - [User overview](#user-overview.)
        - [Create a new user](#create-a-new-user.)
            - [Statute](#statute.)
        - [Modify a user](#modify-a-user.)
            - [Change password](#change-password.)
    - [Manage clients and projects](#manage-clients-and-projects.)
        - [Clients and projects overview](#clients-and-projects-overview.)
        - [Create a client](#create-a-client.)
        - [Create a project](#create-a-project.)
        - [Modify client or project](#modify-client-or-project.)
        - [Merge existing projects (Optional: not in project scope)](#merge-existing-projects-(Optional:-not-in-project-scope))
    - [Consult employee hours](#consult-employee-hours.)
    - [Change employee hours](#change-employee-hours.)
    - [Settings](#settings.)
      - [Clocking in the past](#clocking-in-the-past.)
      - [Enable teams](#enable-teams.)
      - [Absences in the past](#absences-in-the-past.)
    - [Role management](#role-management.)
        - [Employee](#employee.)
        - [Admin](#admin.)
    - [Configuration](#configuration.)
        - [Statute configuration](#statute-configuration.)
        - [Activities](#activities.)
            - [Register time](#register-time.)
            - [Absence](#absence.)
            - [Color codes](#color-codes.)
                - [White](#white.)
                - [Green](#green.)
                - [Orange](#orange.)
                - [Red](#red.)
            - [Security](#security.)
            - [Calculation rules](#calculation-rules.)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with
markdown-toc</a></i></small>

# Introduction

Buildbase was created by Strouwi BV as a mobile application for construction companies which is usable by employees on their
mobile devices.  
The goal of this application is for employees to [register](#register-time.) worked hours daily, for
specific [clients and projects](#manage-clients-and-projects.).

The managers from construction companies who use buildbase will be able
to [consult these hours based on some parameters via file export](#consult-employee-hours.).

The current plan is to build a custom frontend as a progressive web application. This means it will be accessible
everywhere with the only prerequisites being access to internet and a browser. The language used will be Vue.js.

As backend, we opted for the Java Spring-netflix cloud architecture. This means a microservice framework will be used to
handle default components like authentication, authorization, ... while the specific requirements will be created in a
standalone microservice component.  
All components will be connected using this framework.

# Wireframe

## General

On every page there will be a template header which contains the buildbase logo.

![Logo](logo.jpg)

## Login page

![Login Page](loginpage.jpg)

"Gebruikersnaam" aka username will be granted when administrators of the buildbase
application [create a new user](#create-a-new-user.).  
This username will act as authentication and [authorization](#role-management.) for the person to log into the system.
The combination of username and password will be handed to the employee in person by the administrators.

The password will also be created by buildbase admins when they are [creating a new user](#create-a-new-user.). This password
can only be [changed](#change-password.) by the administrators.

There will be an option to remember the password. This will make sure the user can open the application without the need
to login again every time.

## Homepage

![Homepage_MSS](MSS_homepage.jpg)

On every [secured](#security.) page the username of the currently logged-in user will be clearly visible. This is the
username which was received by buildbase administrators.

There are 3 general options in this main screen: [calendar](#calendar.), [counters](#counters.)
and admin access. Depending on the [role](#role-management.) of the logged-in user, different options will be displayed.

### Calendar

![Calendar](calendar.jpg)

This is a simple clickable calendar. You can see all days of the current month. The days of the weekend (saturday and
sunday) are displayed in grey. All days will be [color coded](#color-codes.). These [color codes](#color-codes.) represent
what [activity](#activities.) has been registered for that day.  
When clicking a specific day you'll see its [details](#register-time.) and will be able to
register [worked time](#register-time.) or [absences](#absence.).

### Counters

![counter](counter.jpg)

The [activities](#activities.) will be visualised in a donut-chart by [color code](#color-codes.). This donut-chart
will [display all the hours registered](#calculation-rules.) for the selected month in the [calendar](#calendar.).  
It will also display the [theoretical hours](#calculation-rules.) which need to be [worked](#calculation-rules.) that
month, based on the current users [statute](#statute.).

[comment]: <> (### Administrator link)

[comment]: <> (![Admin-console-link]&#40;./Resources/admin_console_link.jpg&#41;)

[comment]: <> (This button will only be visible to users with the [role]&#40;#role-management&#41; "admin" and will be a link to)

[comment]: <> (the [admin console]&#40;#admin-console&#41;.)

## Admin console

[comment]: <> (![Admin-console]&#40;./Resources/MSS_admin_console.jpg&#41;)

[comment]: <> (In the admin console, users with the [role]&#40;#role-management&#41; "admin" will be able to [manage hours]&#40;#register-time&#41;)

[comment]: <> (, [manage users]&#40;#create-a-new-user&#41;, [manage clients and projects]&#40;#create-a-client&#41;)

[comment]: <> (or [consult employee hours]&#40;#consult-employee-hours&#41;.)

## Manage teams

### Teams overview

![Manage teams](MSS_manage_teams.jpg)

If the admin has chosen the option "teams" in the [settings](#settings.) it is possible to create teams.
By selecting the option "Teambeheer" in the admin console the list of teams becomes visible.
Here the admin will have the option to [create new team](#create-a-new-team.), set the existing teams to active/inactive or [delete a team](#Delete-a-team.).
You can also [modify](#modify-a-team.) this team. After setting a team in the list to inactive, the slider will
change to give a visual indication of the changed team state.
If you select a team you will see this teams details, and you can add and delete:

- Leaders
- Members

Additionally, the admin can [connect clients and projects to a team](#Clients-and-projects-in-a-team.) to all clients and 
projects and [set each client and project inactive](#Setting-clients-and-projects-inactive.) for a team.

### Create a new team

![Create a team](MSS_add_team.jpg)

When creating a new team, the admin will need to provide a name for the team.

### Modify a team

![Modify a team](MSS_modify_team.jpg)

To modify a team the admin can select it in the team overview. On the 'modify team' page it is possible to change the:

- name of the team

### Delete a team

By selecting the bin symbol behind a team a confirmation dialogue will appear to confirm the deletion of the selected team. 
By confirming the team will be removed from the list.
If there is at least one work-clocking on a team the team wil be archived. If there are no work-clockings the team will be permanently removed.

### Team leaders and members

By selecting a team a new page will open with a list of leaders and members for the selected team. Here you can add
and delete leaders and members. If there are no leaders and/or members in the team only the titles will be visible.
A user can either be a leader for the team or a member but not both. Users can be assigned to different teams as
leaders or members. The users can be set to inactive within a team with the slider behind their name.
After setting a leader or a member in the list to inactive, the slider will change to give a visual indication of the changed 
state for that leader or user.

#### Adding team leaders

![Adding team leaders](MSS_add_team_leader.jpg)

Using the add leaders button will open a selection dialog where you can select a user as leader for the team. You can add
multiple, unique users as leader for the team.

#### Removing team leaders

By selecting the bin symbol behind a leader of the team, this user will be removed from the
list of the selected team. The user can be restored as leader by the adding leaders to the team option.

#### Adding members to a team

![Adding team members](MSS_add_team_user.jpg)

Using the add members button will open a selection dialog where you can select a user as member for the team. You
can add multiple, unique users as member for the team.

#### Removing members from a team

By selecting the bin symbol behind a member of the team, this user will be removed from the
list of the selected team. The user can be restored as member by the adding members to the team option.

### Clients and projects in a team

#### Adding clients and projects to a team

![Adding clients to a team](MSS_add_team_clients.jpg)

In the detail screen of a team the admin can connect the team to clients and projects. When clicking the button the list of clients will appear.
By setting a client inactive all clients and users wil be connected to the team. This works only for a client without active projects.
When all clients have active projects just open the projects of that client by clicking on the client name. Set one of the projects to inactive.
This also connects all clients and projects to the team.

#### Setting clients and projects inactive

In the detail screen of a team select the list of clients. With the slider behind the client you can set that client to inactive (or active).
A client can only be set to inactive if there are no more active projects for that client. By selecting the client an overview page with the list
of projects wil become visible. Here you can use the sliders behind the projects to set them to inactive.
After setting a client or project to inactive the slider will change to give a visual indication of the changed
state for that leader or user.

## Manage users

### User overview

![User-overview](MSS_users.jpg)

After selecting the option "Gebruikers" in the admin console, you will navigate to a page with a list of users.  
Here you will have the option to [create new users](#create-a-new-user.) or set existing users to active/inactive.  
If you select a user, you will see this user's details, and you can [modify](#modify-a-user.) this user.  
After setting a user in the list to inactive, the slider will change to give a visual indication of the changed user
state.

![Quick-inactive](MSS_user_inactive.jpg)

### Create a new user

![Create-user](MSS_add_user.jpg)

When creating a new user, you will need to provide a [username](#create-a-new-user.) and password for this user.  
This information will need to be handed over to this employee in person.

#### Statute

You will need to set a statute for this new employee. This statute represents the required hours to work each week.  
The current possible options are 38 hours or 40 hours which are set default by [configuration](#statute-configuration.)
.  
You will also be able to enter a standard weekly work-schedule for this person.

### Modify a user

![Modify-user](MSS_modify_user.jpg)

To modify a user you can select it in the user overview. On the 'modify user' page, you will be able to change the:

- username
- statute
- work schedule
- password
- activity status

#### Change password

The admin will be able to change an employee's password should he have lost it.  
He will have to hand this new password over to the employee in person.

## Manage clients and projects

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

## Consult employee hours

![Consult-hours-by-worksite](MSS_consult.jpg)

The admin will be able to consult all the [registered hours](#register-time.), including [absences](#absence.), for:

- one employee at a time
- for a specific project
- for a specific client
- for one employee per project
- for all employees by work type

He can request these reports for a chosen time period between a start and end date

![Consult-hours-by-worksite](MSS_consult_worksites.jpg)
![Consult-hours-by-employee](MSS_consult_users.jpg)

## Change employee hours

The admin will be able to change the registered hours by clicking "registratie uren" in
the [admin-console](#admin-console.).  
The admin will see a list of all active employees and will be able to click a specific user. When they do so, they see
the calendar for the specific user and by clicking any date they will see the details of that date, where they can
change the [registered hours](#register-time.).

![Register-employee-hours](MSS_registration_hours.jpg)
![Register-employee-absence](MSS_registration_hours_absence.jpg)

## Settings

The admin can adjust some parameters of the app by choosing "instellingen" in the [admin-console](#admin-console.).
Here he can change the settings of:

- Maximum days an employee can register a work clocking in the past
- Enable or disable teams
- Maximum days an employee can register an absence in the past

### Clocking in the past

![Clockings in the past](MSS_settings_maxClockingsPast.jpg)

By selecting "MaxDaysClockingInThePast" the admin is able to enter a number of days that an employee is allowed to register
a work clocking before the current date. Standard the amount is set to 10 days. If set to zero the employees can only register
a work clocking on the current date. The settings do not limit the ability of the admin to enter or adjust a work clocking on
a previous date.

### Enable teams

![Enable teams](MSS_settings_disable_team.jpg)

By selecting "EnableTeamsOption" the admin is able to activate or de-activate the use of teams. When set to true the admin can
[manage teams](#manage-teams.). If set to false the option "teambeheer" will be removed from the [admin-console](#admin-console.).
If the admin has created one (or more teams) and then disables the option the details of the team wil be hidden but not be deleted. If the admin 
later decides to enable the teams option the team (or teams) will be visible again in the list of teams.

### Absences in the past

![Absences in the past](MSS_settings_maxAbsencePast.jpg)

By selecting "MaxDaysAbsenceInThePast" the admin is able to enter a number of days that an employee is allowed to register
an absence before the current date. Standard the amount is set to 10 days. If set to zero the employees can only register
an absence on the current date. The settings do not limit the ability of the admin to enter or adjust an absence on
a previous date.

## Role management

There are two different roles in the app, which have different functionalities available to them.

### Employee

Employees have access to the [calendar](#calendar.) where they can enter worked hours or [absences](#absence.).

### Admin

In addition to access to the [calendar](#calendar.), Admins have access to the [admin console](#admin-console.), where
they can add new employees, clients or projects, teams and export data.
The admin can also manage some settings of the app.

## Configuration

### Statute configuration

### Activities

#### Register time

![Register-time](ESS_registration_hours_first_time.jpg)

When selecting a specific day on the [calendar](#calendar.) you will be guided to the page where you'll be able to
register worked time per client and project for that specific day. A message will show the expected work hours for that
day for the user, the amount depends on the statute of the user and the selected day. When adding worked hours an
employee has to choose a client out of a list of active clients and a project out of a list of active projects.  
It is possible to edit previously registered worked time only for the amount of days that are set in the apps settings.  
It's only possible to add a new clocking according the amount of days that are set in the apps settings.  
If mistakes were made an employee has to ask an admin to [change registered hours](#change-employee-hours.) of 
days further in the past.

![Register-second-time](ESS_registration_hours_second_time.jpg)

![Adept-registered-time-step1](ESS_registration_hours_modify_previous_entry.jpg)

#### Absence

![Register-absence](ESS_registration_absence.jpg)

Absences can only be added for the current, for future days or for the amount of previous days that the admin has set in the apps settings.  
An employee will not be able to change absences of days further in the past. They will need to ask an admin
to [change the absences](#change-employee-hours.)

You can choose between 4 different absences:

- Legal holiday
- Absence
- Bank holiday
- Other

When selecting other, a text field will become available to explain the reason of absence.

#### Absences longer then one day

After choosing an absence a datepicker will become available. The user can optionally select a future end date for the
absence. When committed the absences are only shown on working days, days when work hours are expected.

When choosing a day in the past a message pops up. The user can then choose a new and valid date or add an absence only
for the selected day

#### Color codes

Registered activities will be visualised in the [calendar](#calendar.) by color code.

##### White

Nothing has been registered for this day, only for the present day or days in the future.

##### Green

If there are registered hours for that day, that day will be green in the calendar. This is only for the present day or
days in the past.

##### Orange

If an [absence](#absence.) has been registered for a day, this day will be orange in the calendar.

##### Red

When a day is in the past and no [activities](#activities.) have been entered, that day will be red in the calendar.

#### Security

#### Calculation rules

The theoretical hours an employee needs to work will be calculated with the statute of the employee and the amount of
workdays in a month.  
Every day an employee works is a 8h work day which totals in a 40h week. If an employee has a 38h statute, Fridays are
6h work days.

e.g.:  
In the images below you can see the calendar for June and Juli for two employees.  
Miguel has a 40h statute so every day is a 8h work day.  
This means that the theoretical hours he needs to work are calculated by multiplying all working days times eight.  
Georges has a 38h statute so every day except Friday is a 8h work day, with Friday being a 6h work day.  
This means that the theoretical hours he needs to work are calculated by multiplying all working days except Fridays by
eight plus all Fridays times six.

In June, this means Miguel has to work 22x8 hours, which is 176 hours and  
Georges has to work (18x8 + 4x6)h, which is 168 hours.  
![Example_juni](calc_rules_example_juni.jpg)  
In Juli, this means Miguel has to work 22x8 hours, which is 176 hours and  
Georges has to work (17x8 + 5x6)h, which is 166 hours.  
![Example_juli](calc_rules_example_juli.jpg)  
