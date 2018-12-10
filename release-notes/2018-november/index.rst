Release Notes November 2018
========================================

Features
---------------------------------

Yammer Integration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

From this release, it is possible to use Yammer as the preferred choice for conversations in an Office 365 Group site template.

.. image:: YammerSetup.png

When this option is selected, a Yammer group will be created in the provisioning flow. The Yammer group will be
automatically connected to a new Office 365 Group and team site.

.. image:: YammerGroup.png

The conversations link in Quick Launch will take you to the connected Yammer group.

.. image:: YammerConversationsLink.png

In order for Yammer group provisioning to be enabled in the solution, the following steps needs to be carried out:

1. Make sure Azure Services is enabled in Omnia Admin.
2. Login to Yammer with a Network Admin account. (This account will be used by Omnia to provision new Yammer groups.)
3. Go to Settings > Apps and register a new app.

.. image:: YammerRegisterApp.png

4. Note down the Client Id and Client Secret.
5. Browse to https://www.yammer.com/oauth2/authorize?client_id=[ClientId]&response_type=code&redirect_uri=https://www.yammer.com
6. Click on Allow to authorize the app.
7. Copy the Code in the url in the page you get redirected to. (Something like: lirOpPqZXwjTpRXx4ctDA)
8. Browse to https://www.yammer.com/oauth2/access_token.json?client_id=[ClientId]&client_secret=[ClientSecret]&code=[Code]
9. Note down the token you receive from the JSON response. (Something like: 11503671-bAjUZJODAyrXENlNKJNA)
10. Go to Omnia Admin > Settings > Azure AD > Yammer Group.
11. Read the prerequisites text and make sure your Yammer network is configured accordingly.
12. Put the token into the Yammer Access Token field.
13. Check the box "I ensure all prerequisites are configured correctly" and save.

Site templates can now use Yammer as its preferred way of handling conversations within a group.


Legacy Site Feed for Modern Sites
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The User Feed block in Omnia has been updated to support the legacy SharePoint Site Feed in Modern Pages.

.. image:: LegacySiteFeedSetup.png

The conversations link in quick launch will take you to a modern page with
the user feed block on configured as a Site Feed.

.. image:: SiteFeedModern.png

New Media Picker
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The new Media Picker can be enabled/disabled in Omnia Admin. Go to Settings > Intranet Core and change the setting "Use New Media Picker".

.. image:: MediaPickerSettings.png

In the November release, the new Media Picker is implemented when picking a Page Image on a web page.

.. image:: MediaPickerPageImage.png

The new Media Picker supports the possibility to paste on image from the clipboard or browse your local computer.

.. image:: MediaPickerMyComputer.png

You can also find images from any existing central image location you have registered in Omnia Admin.

.. image:: MediaPickerCentralImageBank.png

There is also a possibility to use Bing to search for images. When you search for images in Bing using the Media Picker, it only shows images that are free to use and share.

.. image:: MediaPickerBingSearch.png

As an administrator, it is possible to setup predefined Bing search categories for the Media Picker to use.

.. image:: MediaPickerSearchCategories.png

.. image:: MediaPickerBingSearchCategories.png

Once an image has been selected, it is possible to apply a filter and change different ratios of the image.

.. image:: MediaPickerEditPhoto.png

It is possible to select a Video to replace the image on the top of a web page. The Media Picker support Stream and YouTube by default.

.. image:: MediaPickerYouTube.png

All news rollups that display page images have been updated to support the new Media Picker.
The news rollups are backward compatible to  support the previous Image Picker. The SharePoint Image Renditions for landsacpe have been updated to a 16:9 ratio. The new values are:

* 1001 Landscape: 640px * 360px.
* 1004 Landscape (small size): 320px * 180px.
* 1005 Landscape (New): 640px * 360px.

Document Management for Modern Sites (Document Management)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Document Management is now fully supported in Modern Sites.

.. image:: DMModern.png

If the Omnia SPFx Infrastructure feature is activated on a team site,
the Controlled Documents library will be deployed as a modern page.

All existing Document Management sites will be updated to use the new look and feel.

Quality Management for Modern Sites (Quality Management)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Quality Management is now fully supported in Modern Sites.

.. image:: QMSModern.png

If the Omnia SPFx Infrastructure feature is activated on a team site, the Process library
will be deployed as a modern page.

All existing Quality Management sites will be updated to use the new look and feel.


Bug Fixes and Small Improvements
----------------------------------

- Fixed bug in Edit Reusable Banner that could happen in some scenarios.
- Fixed issue with new Date/Time picker when loading a specific type of dialog for the first time (related to new version of QMS).
- Fixed some issue with the aspect ratio in the News Roller.
