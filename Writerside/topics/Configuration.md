# Configuration

## Activities

### Register time

![Register-time](ESS_registration_hours_first_time_without_client.jpg)
%module_client_projectmanagement_name%
When selecting a specific day on the [calendar](#calendar) you will be guided to the page where you'll be able to
register worked time for that specific day. On the page the expected work hours for that
day for the user are shown, the amount depends on the statute of the user and the selected day. When a registration is
made the total registered time will also be shown and if a break has been registered. When adding worked hours the start time
for the new time registration will be set to the end time of the previous registration.
It is possible to edit previously registered worked time only for the amount of days that are set in the apps
settings.  
It's only possible to add a new clocking according the amount of days that are set in the apps settings.  
If mistakes were made an employee has to ask an admin to [change registered hours](#change-employee-hours) of
days further in the past.

![Register-second-time](ESS_registration_hours_second_time_without_client.jpg)

![Adept-registered-time-step1](ESS_registration_hours_modify_previous_entry_without_client.jpg)

### Register time for a client and a project

![Register-time](ESS_registration_hours_first_time.jpg)

When selecting a specific day on the [calendar](#calendar) you will be guided to the page where you'll be able to
register worked time per client and project for that specific day.  On the page the expected work hours for that
day for the user are shown, the amount depends on the statute of the user and the selected day. When a registration is
made the total registered time will also be shown and if a break has been registered. When adding worked hours the start time
for the new time registration will be set to the end time of the previous registration. When adding worked hours an
employee has to choose a client out of a list of active clients and a project out of a list of active projects.  
It is possible to edit previously registered worked time only for the amount of days that are set in the apps
settings.  
It's only possible to add a new clocking according the amount of days that are set in the apps settings.  
If mistakes were made an employee has to ask an admin to [change registered hours](#change-employee-hours) of
days further in the past.

![Register-second-time](ESS_registration_hours_second_time.jpg)

![Adept-registered-time-step1](ESS_registration_hours_modify_previous_entry.jpg)

### Absence

![Register-absence](ESS_registration_absence.jpg)

Absences can only be added for the current, for future days or for the amount of previous days that the admin has set in
the apps settings.  
An employee will not be able to change absences of days further in the past. They will need to ask an admin
to [change the absences](#change-employee-hours)

You can choose between 4 different absences:

- Legal holiday
- Absence
- Bank holiday
- Other

When selecting other, a text field will become available to explain the reason of absence.

### Absences longer then one day

After choosing an absence a datepicker will become available. The user can optionally select a future end date for the
absence. When committed the absences are only shown on working days, days when work hours are expected.

When choosing a day in the past a message pops up. The user can then choose a new and valid date or add an absence only
for the selected day

### Prickings

Prickings can be accessed through the navigation bar on the left of the screen. The button will always display a clock symbol, but its text may vary.

![Alt text](pricking_timer_no_existing.png)  
When there is no ongoing pricking, the button will show the word "Prikking".

![Alt text](pricking_timer.png)  
When there is an ongoing pricking, the button wil dislpay the elapsed time since it started.

![Alt text](pricking_timer_more_than_24.png)  
When the elapsed time is more than 24 hours, "> 24 uur" will be displayed instead.


#### Start pricking
![Alt text](pricking_no_existing_without_client.jpg)
On the pricking page, when there is no ongoing pricking, you will be able to start one.
To start a pricking, all you need to do is press start.

**Note:** it is not possible to start a pricking when another clocking is registered in the future.
#### Stop pricking
![Alt text](pricking_existing_without_client.jpg)  
On the pricking page, when there is an ongoing pricking, you will be able to stop it.
On this page, you can enter a comment and select whether or not you took a break. (Just like with normal work clockings)  
Fields like start and end time , they are purely informational here.

When you press stop, if less than one minute has passed since the pricking started, the pricking will be cancelled. Otherwise the pricking will be converted to a work clocking, disregarding the seconds from the original pricking.

**Note:** the pricking start- and endtime are set in the backend. So there could be a slight delay between when the button is pressed and the registered time.

#### Start pricking for client
![Alt text](pricking_no_existing.png)
On the pricking page, when there is no ongoing pricking, you will be able to start one.
To start a pricking, all you need to do is select the client and project for which you want to start the pricking. Then press start.

**Note:** it is not possible to start a pricking when another clocking is registered in the future.
#### Stop pricking for client
![Alt text](pricking_existing.png)  
On the pricking page, when there is an ongoing pricking, you will be able to stop it.
On this page, you can enter a comment and select whether or not you took a break. (Just like with normal work clockings)  
Fields like start and end time and client and project are not editable, they are purely informational here.

When you press stop, if less than one minute has passed since the pricking started, the pricking will be cancelled. Otherwise the pricking will be converted to a work clocking, disregarding the seconds from the original pricking.

**Note:** the pricking start- and endtime are set in the backend. So there could be a slight delay between when the button is pressed and the registered time.


### Color codes

Registered activities will be visualised in the [calendar](#calendar) by color code.

#### White

Nothing has been registered for this day, only for the present day or days in the future.

#### Green

If there are registered hours for that day, that day will be green in the calendar. This is only for the present day or
days in the past.

#### Orange

If an [absence](#absence) has been registered for a day, this day will be orange in the calendar.

#### Red

When a day is in the past and no [activities](#activities) have been entered, that day will be red in the calendar.

### Security

### Calculation rules

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