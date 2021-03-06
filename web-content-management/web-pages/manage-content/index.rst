Manage Content
===========================

In Omnia there are two different ways of editing publishing pages: The Sharepoint way and the Omnia way (Quick Edit). The Omnia Quick Edit makes it a lot easier for an editor to edit an existing page, and to create, move and remove pages. In this chapter the Quick Edit option will be described.

Omnia Quick Edit can be started for a publishing page this way: 

+ Browse to a web page and click on the Quick Edit icon next to the page title. 

.. image:: quick-edit-button-new.png

The Quick Edit button is always available for any user that has permissions to edit a certain page. No need to select to edit the page in the Action Menu.

When the icon is used to open Quick Edit for a page, that page is automatically checked out, which means no other editor can edit that page until it's published.

Tip:
If you just would like to have a look at the settings for a page, without checking out, open the Settings menu (the cogwheel) and select "Manage Content", to open the Quick edit.

Add Page
******************************
To add a new page in the navigation structure, browse to the location where you want to add the page and click on the plus icon.

.. image:: addpage1.png

A dialog will now open. You are able to create a new page in three different ways:

+ Add simple page
+ Add page and break permission inheritance (advanced settings)
+ Add link to page

Add simple page
-----------------
When you choose to add a simple page, the following is shown:

.. image:: addpage2.png

+ **Title**: The title will be used in the current navigation and as the heading for the page.
+ **Page layout**: Select one of the page layouts available. (If there is only one Page Layout available, it will be preselected.)

For a "simple" page, no more settings are needed.

Advanced settings
-------------------
To add a page and break permission inheritance, you use the advanced settings. This is useful for example if a number of publishing pages should be edited by another group of editors, or if a number of pages should have other properties. An example could be that a publishing site contains product information that just certain editors should have permission to edit, or that just dedicated editors should have permission to edit pages with HR information. Such pages could also very well need other properties.

.. image:: addpage3.png

+ **Publishing site**: Select which site to place the page in.
+ **Create new site**: Select to create a new publishing site, to place the page in. A number of options are displayed. Add a title, a Url (The system will automatically add the prefix /publishing-). Then select an existing SharePoint permission group for editors, or create a new group. If you create a new group, you need to go to the new page and add editors to the permission group. 

If you create a new site, separate libraries and other resources will automatically be created for that site, for example a Documents library and an Image library.

Add link to page
-------------------
If you want to structure the navigation some special way, or if you want to add links to pages in other places in the publishing site for easy access, use "Add link to page".

.. image:: addpage4.png

+ **Title**: The title will be used in the current navigation.
+ **Page**: Select to add a link to a page that already exists in the navigation structure, then browse to the page. 
+ **Custom Url**: Select to add a link that is not in the navigation structure. You have to manually add the Url.
A new navigation term will now be created that will either point to an existing physical page in the system (term-driven page) or point to a static link.

Sort Page
-----------
Use the up and down arrows to decide the internal sort order of the pages in the navigation.

.. image:: sortpage.png

General Tab
**************
The general tab has three fields:

.. image:: manage-content-general-new2.png

+ **Status**: At the top of the page you can see the status of this particular version of the page. If it says "draft", this version is not published, and therefore not available for others.
+ **Title**: This is a required field and sets the title of the page. (If this is a term-driven page it will set the term title. If it is a physical page, it will set the Title field of the aspx page.)
+ **Summary**: This text will be shown below the title on the page. (If this is a term-driven page, it will set the term description. If it is a physical page, it will set the Comments field on the aspx page.)
+ **Enable legacy web parts** If Quick Pages is activated, this check box is displayed. Quick Pages loads much, much faster, but legacy web parts can't be used on such pages. If you are about to add a banner or a quick poll to a page, you must see to that this check box is checked.
+ **Image**: Browse for an image using the built-in asset picker in SharePoint or enter a url to an external image. The image will be shown on top of the page. Leave blank, if the title should appear on top instead. If the image is internal (stored in the current site collection), a link will appear with the possibility to edit image renditions. Note! The system will automatically add "?RenditionID=1001" to the url when you pick an image using the Browse button. Remove this query string if you want to render the image in original format.


Content Tab
************
The content tab includes a content editor based on [TinyMCE] (https://www.tinymce.com). Click "Edit in Advanced Mode" to use SharePoint content editing instead. Note! If Quick Pages has been activated, Advanced mode is not available. "Edit in Advanced Mode" is missing from the image for that reason.

.. image:: manage-content-content-new2.png

Links Tab
**********
Using the links tab you can create structured links that will appear on the right-hand side of a page. 

.. image:: manage-content-links-new2.png

Four different types of items can be added to the list of links:

+ Page
+ Document
+ Custom Link
+ Heading

A custom link can be created to anything you can reach through an Url. A Custom link can also be used to create a mailto link. Headings are use to create sections in a longer link list.

Sort the links
------------------
You can sort the links and headings in the list by using drag and drop.

Edit links
--------------
You can edit any item in the list by selecting it in the list.

"Related links" in this image is an example of how a links list can look when the page is published:

.. image:: manage-content-links-example.png

Properties Tab
****************
The properties tab displays all page properties that have been configured as editable for the current publishing site. The available properties are configured by an administrator using Omnia Admin. 

.. image:: manage-content-properties-new2.png

Note! If the field "Review Date" is present, you should normally add a suitable date there. Then the page will be indicated in "Content Management" in Omnia Admin, when the date is passed.

Navigation Tab
****************
The navigation tab includes all settings related to navigation for the page.

.. image:: manage-content-navigation-new2.png

+ **Navigation Term title**: By default, the navigation title will be the same as the page title, but it is possible to customize the navigation title. Check the box "Customize" and then change the title. All navigation components will now display this title instead of the page title.
+ **Friendly Url Segment**: The friendly url to the page is built up of segments from all parent nodes in the navigation. The last segment in the url can be edited. By default it is set to the title, but excluding special characters.
+ **Navigation Hover Text**: It is also possible to set a hover text. The hover text will appear when the user holds the mouse over the node in the cross-sites-mega-menu and the current navigation.
+ **Visibility in menus**: Check "Show in Global Navigation Menu" if you want the navigation node to appear in the mega menu. Check "Show in Current Navigation Menu" if you want the navigation node to appear in current navigation on the left-hand side of the page.

Note! The navigation node will always be visible in the breadcrumb.

Site Tab
**********
The site tab holds information about the current publishing site. It is possible to navigate to the pages library where the physical page is located.

The site permissions part displays all SharePoint groups that have access to the page. Click on "Edit Permissions" to go to the SharePoint UI and add users to the different groups (at the bottom of the page, not shown in the image below).

.. image:: manage-content-site-new2.png

Statistics tab
**************
Using this tab you can see statistics for the page.

.. image:: manage-content-statistics-vision-pagehits-new.png

Select "Page Hits" or Unique Visitors". If you select Page Hits you can also select "Include Sub Pages".

Also see "Reports" below.

Reports
********
Using this tab you can view and export some reports about publishing pages in the tenant.

.. image:: manage-content-reports-tab.png

Something like the following can be shown:

.. image:: manage-content-reports-new.png

Use the left-most list to select report:

.. image:: manage-content-reports-list-new.png

+ **Usage**: Lists the most viewed pages.
+ **Review**: Lists the pages that needs review.
+ **Checked Out**: Lists pages checked out by users.

You can use the other fields at the top to filter a list:

.. image:: manage-content-reports-list-filter-new.png

Use the button to the far right to export the chosen list (filtered if you have done that) to Excel.

.. image:: manage-content-reports-list-export-excel-new.png

If the list is long, use the navigation below the list, the navigate to any page within the report.

.. image:: manage-content-reports-navigate-pages-border-new.png

Edit - Save - Check in - Publish 
***********************************
If you open the Manage Content UI by clicking on the "Quick Edit" button on a web page, then it will automatically be checked out and ready for editing.

If you click on a page in the navigation structure in the Manage Content UI and the page is not checked out to you, you need to click on "Edit" to start editing.

.. image:: editbutton.png

The following options are avilable for saving (or not):

.. image:: saving.png

+ **Save**: All changes will be saved, but the page will still be checked out to you.
+ **Undo Changes**: Any changes made since the last save will be discarded and the page will be checked in.
+ **Check in**: All changes will saved and the page will be checked in so other authors can see the changes.
+ **Publish**: The page will be published. Note! The page will not be shown in any navigation components until it has been published at least once.

If you want to preview changes before you publish a page, you need to save the changes and then click on "Open Page". The page will now be opened in a separate tab.

If you forgot to save
------------------------
If you leave a page you have edited, without having saved the changes, the following message is shown:

.. image:: page-not-saved.png

You can click "Cancel" to continue editing, and then save the normal way or do any of the other normal actions. When you click "OK" the following is shown:

.. image:: page-not-saved-options.png

Choose what you want to do and click "OK".

Move Page
***********
To be able to move a page, it must be checked out, meaning you must edit the page.

If the page has children (sub pages), you move the page and all sub pages in one go.

Click on "Move Page" and select a target parent page. 

.. image:: move-example.png

If the target parent page is in the same publishing site, the page will be moved to the new location without any further options. If the target parent page is in another publishing site, there are two options:

+ Keep the physical page in the source publishing site and move the navigation node.
+ Move the physical page to the target publishing site.

Delete Page
*************
A prerequisite to be able to delete a page is that it doesn't have any children. Click on "Delete Page" to remove the page together with the navigation node.

Note! In the scenario where several navigation nodes (terms) point to the same physical page, only the navigation node will be removed and the physical page will be kept.

Important!
A deleted page can not be restored by an editor.

Translations
*************
It may be possible to work with the content in several languages. If it is, you can select language while editing a page:

.. image:: translation-1-new2.png

If the page already exists in the selected language, it is displayed and you can continue working on the content.

If the page does not exist in the selected language, you have to create it:

.. image:: translation-2-new-box.png

When the page is created, and only then, all content from the master language is copied. After that, the language editions of the page are different units, with no connection between them.

You can now edit the language edition of the page the normal way. Note that everything can be "translated", even for example links. You can add new new links and other content if needed.

When you are finished, you publish the language edition the same way as for the master page, but now the button is named "Publish Translation". If something went wrong, you can delete the language edition of the page.

.. image:: translation-3-new2.png

Restore a page to the Navigation Menu
***************************************
It's possible to restore a deleted page to the Navigation Menu, if the deleted page is present in the Recycle bin.

**Note!**
If you restore a page in the navigation node that already exists in the structure, a copy will be created in the Pages library.

To restore a page to the Navigation Menu, do the following:

1. Go to the Recycle bin in SharePoint.
2. Restore the aspx page.

.. image:: restorepage-recyclebin-new.png

3. Open "Manage Content" and start the creation of a new page in the location where you want to restore the page.
4. Click on "Advanced Settings" in the "Create Page" dialog and click on "Restore/Copy Page".

.. image:: restorepage-restorecopypage.png

5. Find the page that you restored from the Recycle bin and select it.

.. image:: restorepage-searchpage.png

6. Create the page. 

A new navigation node will now be created related to the restored page in the Pages library.

Permissions
*************
To be able to edit or delete a page, you need the appropriate access rights to the physical page in SharePoint. The physical page is located in a publishing site and the permissions to the publishing site can be found on the Sites tab.

To be able to add a new page (or page link) in the navigation structure, you need SharePoint "Add Item" access rights in the publishing site where the parent page is located. Example: You want to create a new page below "Utility 13". You need "Add Item" access rights on the publishing site where the physical page utility-13.aspx is located.

To be able to sort a page, you need edit access rights to the parent page in the navigation structure.

To be able to move a page, you need edit access rights on the publishing site where the target parent page is located.


