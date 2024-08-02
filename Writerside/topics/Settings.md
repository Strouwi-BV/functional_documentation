# Settings

The admin can adjust some parameters of the app by choosing "instellingen" in the [admin-console](#admin-console).
Here he can change the settings of:

- Maximum days an employee can register a work clocking in the past
- Enable or disable teams
- Maximum days an employee can register an absence in the past

## Clocking in the past

![Clockings in the past](MSS_settings_maxClockingsPast.jpg)

By selecting "MaxDaysClockingInThePast" the admin is able to enter a number of days that an employee is allowed to
register a work clocking before the current date. Standard the amount is set to 10 days.
If set to zero the employees can only register a work clocking on the current date.
The settings do not limit the ability of the admin to enter or adjust a work clocking on a previous date.

## Enable teams

![Enable teams](MSS_settings_disable_team.jpg)

By selecting "EnableTeamsOption" the admin is able to activate or de-activate the use of teams. When set to true the
admin can [manage teams](#manage-teams). If set to false the option "teambeheer" will be removed from
the [admin-console](#admin-console).  
If the admin has created one (or more teams) and then disables the option the details of the team wil be hidden but not
deleted. If the admin later decides to enable the teams option the team (or teams) will be visible again
in the list of teams.

## Absences in the past

![Absences in the past](MSS_settings_maxAbsencePast.jpg)

By selecting "MaxDaysAbsenceInThePast" the admin is able to enter a number of days that an employee is allowed to
register an absence before the current date. Standard the amount is set to 10 days.
If set to zero the employees can only register an absence on the current date.
The settings do not limit the ability of the admin to enter or adjust an absence on a previous date.