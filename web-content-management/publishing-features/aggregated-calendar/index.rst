Aggregated Calendar
===========================

.. toctree::
   :titlesonly:

   setup/index

The aggregated calendar control displays events from one or more calendars from any site in the tenant.

.. image:: aggregated-calendar-new.png

Using the option "Show all events":

.. image:: show-all-events.png

Users can access and browse the whole aggregated calendar. It can look like this:

.. image:: show-all-events-new.png

Settings for the control
*************************
The following settings are available:

.. image:: aggregated-calendar-settings-0329.png

+ **Add Calendar**: To display events in the aggregated calendar control, at least one calendar needs to be added. See more information below.
+ **Use Targeting**: If targeting should be used for the calendar, select ths box. Targeting has to be set up in Omnia Admin. It's the same settings for all controls that can use targering. 
+ **Accent Color**: Defines the color for some objects, for example date and event name. Another color can be selected from the list.
+ **Default View**: Defines how to show the events. Note! Not all views are suitable for all periods, for example it only makes sense to display the Current Month events for the Month View.
+ **Default Period**: Defines periods for the events to be displayed. 
+ **Item Limit**: Default setting is "No Limit". You can limit the number of rows shown by selecting "Row Limit" and set the number of rows. 
+ **Show Title**: Label to be shown for the control.
+ **Show Legend**: If legends for the calendars should be visible, select this box. (The two images at the top has this option activated).

Add a calendar
***************
Follow these steps to add a new calendar:

1. Click "+ Add calendar".

.. image:: click-add-calendar.png

You can now add calendars from the current site (default) or from any other site in the tenant.

To add calendar from the current site:

1. Open the list "Calendar" and select calendar.
2. Click "Add".

.. image:: add-calendar-add.png

To add a calendar from another site:

1. Active the text box.
2. Enter the url to the site where the calendar is located and click "Resolve".

.. image:: add-site-resolve.png

3. Open the list "Calendar" and select calendar. (If no calendars are found a message will be shown.)
4. Click "Add".

All selected calendars are shown at the top, just under "Query Settings".

Remove a calendar
*******************
To remove a calendar just:

1. Click the x for the calendar in the list of active calendars.

.. image:: remove-calendar.png

Edit a calendar
****************
If you have permissions to edit a calendar, you can do that this way:

1. Click "SHOW ALL EVENTS".

.. image:: aggregated-click-all-events.png

2. Use the list at top left to to select calendar to edit.

.. image:: aggregated-calendar-select-calendar.png

You can add events now. To edit and delete events or edit targeting, select the event.

.. image:: aggregated-calendar-edit-or-delete.png

Targeting a calendar
---------------------
By default all users of the intranet can see all calendars, but you can set that a calendar should be shown just for some users. One example could be a calendar for a specific office. Here's how target a calendar:

1. Select the calendar as shown under *Edit a calendar*.
2. Click "TARGETING".

.. image:: aggregated-targeting.png

3. Click "Target to".

.. image:: click-target-to.png

4. Use the available fields to target to a specific group of users.

Available fields can differ depending on how targeting is set up in Omnia Admin. Here's a common example:

.. image:: aggregated-targering-fields.png

Don't forget to save when you're done.

More on Default views
***********************
The list view displays all events from the selected default period in a list. It is the preferred view if you want to focus on upcoming events. (See the image at the top of the page.)

The Month Calendar view displays all events from the selected default period in a monthly calendar. It is possible to navigate from month to month using the navigation arrows at the top. The current day will be shown with a different background color. The user can hover over an event to show detailed information about it.

.. image:: aggregated-calendar-month.png

The Week Calendar view displays all events from the selected default period in a weekly calendar. It is possible to navigate from week to week using the navigation arrows at the top. The current day will be shown with a different background color. The user can hover over an event to show detailed information about it.

.. image:: aggregated-calendar-week.png

There's also a Summary View:

.. image:: aggregated-calendar-summary.png

This view is used to show events from the actual day and the next day in a special format.

Aggregated Calendar in Notification Panel
******************************************
The Aggregated Calendar control is available in the Notification Panel. If the Aggregated Calendar is added to the panel, a notification count icon will be shown if there are events in the default view, that are new to the user. 

Aggregated Calendar block and Web Part
***************************************
The Aggregated Calendar control can also be added to a Quick Page as a block and to a legacy page as a web part.

