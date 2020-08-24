Web Editor Reports
===========================

When "Content Management" is selected in Omnia Admin, the first page displays an overview over the pages in the Site Collection. Here's an example:

.. image:: content-management-overview-new.png

Note the two units "Past review date", one for "your" pages, and one for all other pages. Your pages are all pages where you are the contact person (your name is added in the field "Contact"). By clicking the unit you can see a list of the pages in question. You can even click the link to the page to go there. The field "Review Date" must be active in "Page Properties" (Content Management - Properties) in Omnia Admin for this to work.

Click for more details. Here's an example from a Past review date report:

.. image:: past-review-date-report.png

**Tip!**: There's also a number of reports available for publishing pages, when you edit a page, see (under "Reports, almost at the end of the page): :doc:`Manage Content </web-content-management/web-pages/manage-content/index>`

Page Review
*************
If Page Review is active (set in Omnia Admin, see below), it works like this: When a page is past it's review date, something like the following is shown for editors (not to users reading the page):

.. image:: page-review-message.png

If the page is ok the editor can directly update the review date, by clicking "here" (if the option is activated in Omnia Admin, see below), and then the following is shown:

.. image:: page-review-update.png

Suggested review date depends on settings in Omnia Admin, see below.

The editor can just click "Update" and it's done!

Page Review settings
----------------------
Under "Content Managament" in Omnia Admin, an administrator can handle a number of settings for page review. Note that these setting are set per site.

The settings are available here:

.. image:: page-review-settings-menu.png

The active site which you set the settings for is shown here:

.. image:: page-review-settings-site.png

In the above example, it's the site Intranet.

To select another site to set review settings for, click the icon:

.. image:: page-review-settings-icon.png

Click the site in the list. Note the link at the bottom, you can use to go to the site and have a look, if in doubt.

.. image:: page-review-settings-icon-list.png

The first step, when the correct site is selected, is to decide if Page Review should be active or not. If it should be active, select "Enable Page Review".

.. image:: page-review-settings-settings-activate.png

Then the following can be set:

.. image:: page-review-settings-settings-new.png

+ **Review Responsible**: Select property in the list. The Review Resonsible is notified by an e-mail when the review date is passed.
+ **Review Date**: First select property that the date will be counted on, then set interval - number of days, months or years.
+ **Notification Text Color**: Set the color for the text, link and background for the notificiation on the page (see above for an example).
+ **Notification Link Color**: Set the color for the link, in the review text.
+ **Notification Background**: Here you can set the background color for the review notification.
+ **Notification Icon**: You can also select an icon for the notification - Built in or Custom, and then select icon. If you select "Custom", you can choose any image as icon. 
+ **Enable Quick Review**: Select to enable Quick Review or not. If Quick Review is active, the link "here" is shown in the notification (see above) so the editor can change review directly. If this option is not active the notification is slightly different. See below for an example.
+ **In Advance Email Review Reminder**: Select this option if the review responsible should be notified before review date has passed, and then set the number of days.
+ **Review Reminder Report Interval**: If this option is not active, the review responsible will be notified once for each site that needs to be reviewed. If you activate this option, you set the number of days, months or years for the interval between notifications for the review reminder report. This means the review responsiböe will receive reminders if a site is not reviewed.

The review notification on the page can look like this when Enable Quick Review is NOT active:

.. image:: page-review-message-not.png

Note the link to the review responsible instead of the "here" link, as seen in the example above.