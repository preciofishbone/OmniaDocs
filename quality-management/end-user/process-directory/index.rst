Process Directory
===========================

The Process Directory control is available as a web part for legacy pages and as a block for Quick Pages.

Here's how a Process Directory block can look for end users:

.. image:: process-list-end-users-new.png

**Note!** The control is best suited to the main part of the page. It will need space.

Settings for the control
**************************
The settings are organized in fours tabs, see the sections below.

The General tab
-------------------
On this tab the following settings are available:

.. image:: process-directory-settings.png

+ **Title**: Set the title for the list, that will be displayed for users.
+ **Process viewer page**: (a description will be added soon.)
+ **Number of items per page**: Set the number of items to be displayed on each "page" in the list.
+ **Show filter**: Set if users should be able to filter the list. 
+ **Open process with new tab**: Set what will happen when a users clicks a process link in the list - open in new tab or new page.
+ **Sort Property**: (A description will be added soon.)

The Columns tab
------------------
Use this tab to decide which columns to display for the list.

.. image:: process-directory-columns.png

You can set the column order and set an exact width for the column (default: Auto). You can also turn the filter option on or off for each column, meaning if the column should be used for filtering or not.

The Filters tab
------------------
This tab is used to set filter options if just some of the available processes should be displayed in this list.

.. image:: process-directory-filters.png

Click "Add more filter" to add one or more filters, and then select type of filter from the list, for example:

.. image:: process-directory-select-filter.png

The next step is to add details for the filter:

+ **Title**: Type part of titles to filter on. Example: "dev" would show any process that has these letters in the title, for example Develop and development.
+ **Owner": Type a full name or part of a name.
+ **Edition**: Select an edition number.
+ **Revision**: Select a revision number.
+ **Revision interval**: Select a number for the interval on which to filter.
+ **Tags**: Select one or more of the available tags.

Filtering is cumulative. An example: With this list (not filtered):

.. image:: process-directory-no-filter.png

If the following filters are added:

.. image:: process-directory-filter-example.png

The result could be this list:

.. image:: process-directory-filtered.png

To be shown in this filtered list, a process must contain dev or Dev in the title, AND be tagged with HR.

The Custom Colors tab
-----------------------
You should primarily set colors through Theme colors in Omnia Admin (System/Settings/Default colors). If you still would like custom colors for the control, you can set them using this tab.

.. image:: process-directory-colors.png
