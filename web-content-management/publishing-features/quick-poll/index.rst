Quick Poll
===========================

Through the Quick Poll control a web editor can add a poll on a web page (the questions are created in Omnia Admin). Quick Polls can be added as a web part to any standard Sharepoint page and as a block to any Quick Page.

Here's an example on how an end users would see a Quick Poll:

.. image:: quick-poll.png

**Note!** As usual you must publish the page for any changes to be shown for the users.

When a user has voted, the present result is shown, for example:

.. image:: quick-poll-result.png

**Note!** Whether a user has answered the poll or not is stored as a cookie in the web browser. If another web browser is used or the cookies are cleared, the user will be able to vote again.

The settings for the control
*****************************
The following settings are available:

.. image:: quick-poll-settings.png

The Question tab
------------------
On this tab you select question.

+ **Question**: Open the list and select which Quick Poll to display.
+ **Display settings**: You should primarily set colors through Theme colors in Omnia Admin, but if needed you can set background color, link color and border color here or on the "Custom colors" tab. 

The selected poll must be available (start date and time, and end date and time), If it's not available, the message "The selected poll is not active" is shown. You then have to select another poll, or have a talk with the administrator to change start- or end time for the poll yopu would like to display.

The General tab
-----------------
On this tab you set the position for the explanation of the result (the Legend). You can also chosse "None" to not display the explanation.

.. image:: quick-poll-General.png

In the example above (Where do you think we should hold the next conference) the Legend is placed at the bottom.

The Targeting tab
-------------------
If targeting is activated (in Omnia Admin), you can select to use targeting for this poll.

Select "Target to" and choose target group in the list.

.. image:: quick-poll-Targeting.png

The Custom Colors tab
--------------------------
You should primarily set colors through Theme colors in Omnia Admin (System/Settings/Default colors). If you still would like custom colors for the control, you can set them using this tab.

.. image:: quick-poll-colors.png)


