# Teams

## Teams overview

![Manage teams](MSS_manage_teams.jpg)

If the admin has chosen the option "teams" in the [settings](#settings) it is possible to create teams.
By selecting the option "Teambeheer" in the admin console the list of teams becomes visible.
Here the admin will have the option to [create new team](#create-a-new-team), set the existing teams to active/inactive
or [delete a team](#Delete-a-team).
You can also [modify](#modify-a-team) this team. After setting a team in the list to inactive, the slider will
change to give a visual indication of the changed team state.
If you select a team you will see this teams details, and you can add and delete:

- Leaders
- Members

Additionally, the admin can [connect clients and projects to a team](#Clients-and-projects-in-a-team) to all clients and
projects and [set each client and project inactive](#Setting-clients-and-projects-inactive) for a team.

## Create a new team

<img src="TeamCreateAddButtonHighlighted.png" width = "750">
<img src="TeamCreateSaveButtonHighlighted.png" width = "750">
<img src="TeamCreateErrorMessageHighlighted.png" width = "750">

The admin will be able to create a team.
He can do this from the teams page by clicking on "New Team".
He will be able to provide a team name which is mandatory to fill out. When entering a new team's name, the system will also check the existing list of teams to find a match, to prevent double entries. An error message will be shown when the name is already in use. After pressing the save button, a new team is created and the application will navigate to the created [team detail page](#team-leaders-and-members).

## Modify a team

![Modify a team](MSS_modify_team.jpg)

To modify a team the admin can select it in the team overview. On the 'modify team' page it is possible to change the:

- name of the team

## Delete a team

By selecting the bin symbol behind a team a confirmation dialogue will appear to confirm the deletion of the selected
team.  
By confirming the team will be removed from the list.  
If there is at least one work-clocking on a team the team wil be archived.  
If there are no work-clockings the team will be permanently removed.

## Team leaders and members

By selecting a team a new page will open with a list of leaders and members for the selected team. Here you can add
and delete leaders and members. If there are no leaders and/or members in the team only the titles will be visible.
A user can either be a leader for the team or a member but not both. Users can be assigned to different teams as
leaders or members. The users can be set to inactive within a team with the slider behind their name.
After setting a leader or a member in the list to inactive, the slider will change to give a visual indication of the
changed state for that leader or user.

### Adding team leaders

![Adding team leaders](MSS_add_team_leader.jpg)

Using the add leaders button will open a selection dialog where you can select a user as leader for the team. You can
add multiple, unique users as leader for the team.

### Removing team leaders

By selecting the bin symbol behind a leader of the team, this user will be removed from the
list of the selected team. The user can be restored as leader by the adding leaders to the team option.

### Adding members to a team

![Adding team members](MSS_add_team_user.jpg)

Using the add members button will open a selection dialog where you can select a user as member for the team. You
can add multiple, unique users as member for the team.

### Removing members from a team

By selecting the bin symbol behind a member of the team, this user will be removed from the
list of the selected team. The user can be restored as member by the adding members to the team option.

### Clockings team members

When a user has the role of team leader he can add clockings for the team members. After loging in the team leader can select 'Team Leden' from the menu.

![See team members](ClockingMembers_001b.png)

This will open a list of users of the teams in which the user is set as team leader. By clicking on one of the users the calendar of that user opens.

![Select calendar team member](ClockingMembers_002.png)

![Calendar team member](ClockingMembers_003.png)

Now the team leader can add work clockings and/or absences for the team member see [Calendar](#calendar).

## Clients and projects in a team

### Adding clients and projects to a team

![Adding clients to a team](MSS_add_team_clients.jpg)

In the detail screen of a team the admin can connect the team to clients and projects. When clicking the button the list
of clients will appear.
By setting a client inactive all clients and users wil be connected to the team. This works only for a client without
active projects.
When all clients have active projects just open the projects of that client by clicking on the client name. Set one of
the projects to inactive.
This also connects all clients and projects to the team.

### Setting clients and projects inactive

In the detail screen of a team select the list of clients. With the slider behind the client you can set that client to
inactive (or active).
A client can only be set to inactive if there are no more active projects for that client. By selecting the client an
overview page with the list
of projects wil become visible. Here you can use the sliders behind the projects to set them to inactive.
After setting a client or project to inactive the slider will change to give a visual indication of the changed
state for that leader or user.
