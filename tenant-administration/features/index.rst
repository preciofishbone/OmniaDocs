Omnia Features
==============

**Note!** The information on this page is being updated. Unfortunately all information is not up to date at the moment, but will be soon.

Here all Omnia Site collection features and Site features are listed. It's used for activation and installation of features, normally by a programmer.

Note that permissions to handle features (activate, deactivate etc) is set on the "Permissions" page under "System", and only Site Collection Features and Site Features are applicable for this documentation. Only Global Administrators can see and edit Tenant scoped Omnia Features.

Also note that the Features admin page is context sensitive. What will be displayed as on or off relates to the current site.
A number of features is part of Omnia Foundation, see:

Site Collection scoped Omnia Features
***************************************
**Omnia Aggregated Content Web Parts** Deploys web part definitions of the following Omnia Controls to the web part gallery:

+ Announcements
+ Last Updated Documents
+ My Tasks

**Omnia Core Image Renditions** Deploys the following image renditions to the site collection:

+ 1001 Landscape
+ 1002 Square
+ 1003 Portrait
+ 1004 Landscape (small size)

**Omnia Core Master Page** Deploys the Omnia master page “portal.master” to the site and remote event receivers to apply the master page to sub sites created. This master page is required for the Omina features such as Omnia Controls, javascript and CSS to function correctly.

**Omnia Document Management Archive Site** Deploys the Archive Site for Omnia Document Management. Note that only one such site should exist per Site Collection.

**Omnia Document Management Authoring infrastructure** Deploys the required artifacts (content types, site columns etc) on site collection level necessary in order to work with controlled documents.

**Omnia Document Management Web Parts** Deploys the Controlled Documents Viewer web part to the site collection.
Site scoped Omnia Document Management Features


**Omnia Enable External Sharing** Activates the possibility to share the contents of the site collection to external users. It will take central settings, which may prohibit external sharing, into consideration.

**Omnia Intranet Aggregated Calendar Web Part** Deploys a web part definition of the Omnia Control “Aggregated Calendar” to the web part gallery.

**Omnia Intranet Banner Web Part** Deploys a web part definition of the Omnia Control “Banner” to the web part gallery.

**Omnia Intranet Content Management** Requires the SharePoint Publishing Infrastructure to be activated. Deploys the necessary infrastructure for publishing functionality in Omnia. Deploys the following page layouts to the master page gallery:

+ News article
+ News start page

Deploys the content types:

+ News Article
+ News Start Page

**Omnia Intranet My Links Web Part** Deploys a web part definition of the Omnia Control “My Links” to the web part gallery.

**Omnia Intranet News** Deploys the necessary infrastructure for news. Deploys the web part definition of the Omnia Control “News Viewer” to the web gallery. Deploys the following page layouts to the master page gallery:

+ News article
+ News start page

Deploys the content types:

+ News Article
+ News Start Page

**Omnia Intranet Quick Polls WebPart** Deploys a web part definition of the Omnia Control “Quick Polls” to the web part gallery.

**Omnia Legacy Support** Omnia Legacy Support can be turned off by deacticating this Feature. This will disable all code running Angular and decrease the javascript load times. **Important note!** Any custom extensions built on Angular will stop working if legacy mode is turned off. If Legacy Support is turned iff, the following two Site Features needs to be updated: “Omnia Glue Site” and “Omnia Core Master Page”.

**Omnia Site Directory Web Part** Deploys web part definition of the Omnia Control “Site Directory” to the web part gallery.
Omnia User Feed Web Part Deploys a web part definition of the Omnia Control “User Feed” to the web part gallery.

Site scoped Omnia Features
***************************
**Omnia Document Management Authoring site** Deploys the required artifacts (document libraries, controls etc) on site level necessary in order to work with controlled documents.

**Omnia Document Management Create Document Wizard** Deploys the Omnia Create Document Wizard. When this feature is activated, the Omnia Wizard replaces the standard options for "New" in classic Documents libraries and "Add" in Controlled Documents libraries.

**Omnia Intranet News Center** Turns the site into a News Center. Deploys a new welcome page to the site with the News Start Page layout. Deploys the Enterprise keywords column to the pages library and sets the default value to the Article column to [today]. Enables Contact, Article Date and Enterprise Keywords in view and edit mode. Sets the navigation on the site to structured navigation.

**Omnia Intranet Social** Makes comments and likes available in pages on the site.

**Omnia Intranet Team Site – Announcements** Deploys an announcements list to the site. Permission will be broken on the list and the members group will have edit access to the list. The “Recent” node in quick launch will be removed.

**Omnia Intranet Team Site – Calendar** Deploys a calendar to the site. The “Recent” node in quick launch will be removed.

**Omnia Intranet Team Site – Contacts** Deploys a contacts list to the site. The “Recent” node in quick launch will be removed.

**Omnia Intranet Team Site – Controlled Documents** Deploys a document library specifically designed for controlled documents. Minor/Major versioning will be added to the library. Permission will be broken on the list. A SharePoint group “Controlled Documents Readers” will be added to the site and be given read access to the library. Everyone except external will be added to this readers group. The owners group will be the only group with contribute rights on the library. The “Recent” node in quick launch will be removed.

**Omnia Team Site – Is Member** Makes the site available for the “Is Member” filter in the My Sites control. The “Recent” node in quick launch will be removed.

**Omnia Intranet Team Site – Links** Deploys a links list to the site. The “Recent” node in quick launch will be removed.

**Omnia Intranet Team Site - Microsoft Teams Icon** When this feature is activated, an icon indicates if a Team Site is attached to a Microsoft Teams group. This is shown in My Sites and in the Site Diretory.

**Omnia Intranet Team Site – Reporting Documents** Deploys a document library specifically designed for reporting documents. Minor/Major versioning will be added to the library. Permission will be broken on the list. A SharePoint group “Reporting Documents Readers” will be added to the site and be given read access to the library. The owners group will be the only group with contribute rights on the library. The “Recent” node in quick launch will be removed.

**Omnia Intranet Team Site – Tasks** Deploys a tasks list to the site. The “Recent” node in quick launch will be removed.

**Omnia Intranet Team Site - Yammer Icon** When this feature is activated, an icon indicates if a Team Site is attached to a Yammer group. This is shown in My Sites and in the Site Diretory.

**Omnia Intranet Team Site - Yammer Web Part** Mkes it possible to deploy the new Yammer Modern Web Part to the welcome page of a modern team site.


