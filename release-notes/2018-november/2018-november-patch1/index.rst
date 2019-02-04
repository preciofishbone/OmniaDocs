Release Notes November 2018 Patch 1
========================================

Omnia.Foundation (1.0.14988)
----------------------------------------
- Fixed a couple of issues with the Term Picker.
- Fixed issue with validation in People Picker.
- Fixed issue with targeting in RSS Viewer for translated labels.
- Fixed problem with text boxes in settings not being able to be edited in IE11.
- Fixed label that could not be translated correctly in the Media Picker.
- Fixed component omfx-scroll.
- Fixed issue with the Team Site quick edit when browsing from one modern team site to another.
- Fixed issues related to SharePoint 2019.
- Added support for Canadian French language.
- Made sure extensions can use their own version of CSOM.
- Secured the site provisioning flow when the SharePoint API is not responding as expected.
- Removed information logs from the Term Picker.

Omnia.Intranet (1.0.14980)
----------------------------------------
- Fixed a number of issues related to the Aggregated Calendar.
- Fixed issue with the User Feed for customers running in Site Collection Only Mode.
- Fixed issue with Scheduled Publishing if a file is checked out.
- Fixed some missing Swedish translation in the Media Picker.
- Fixed a number of design issues in the new Media Picker.
- Fixed issue in Document Rollup when using Less than query.
- Fixed issue related to HTML being displayed as plain text in the Strengten Profile dialog.
- Fixed issues with read-only fields in the Strengthen Profile dialog.
- Added validation to the feedback in the Strengthen Profile dialog so that empty feedback cannot be sent.
- It is now possible to activate the "Omnia Team Site - Prerequisites" feature on a Communication Site.
- Fixed design issue in the User Feed. The profile picture was cut off in replies.
- Fixed issue with posting in the User Feed on Edge and IE11.
- Fixed problem with the "Open Page" button on news articles always redirecting to the legacy SharePoint version of the page instead of the quick page.
- Fixed problem with images in the Rich Text Editor always having a fixed width and height.
- Fixed graphical bug in Edge in one of the News Viewer views.
- Change margin between title and result in News Viewer if title is used on the block.
- Made sure the People Rollup block doesn't throw an error for external users.
- Fixed issue with comment in user feed not being able to be deleted in Modern Team Sites on certain browsers.
- An Accessibility Theme has been added to Omnia Admin that can be turned on by an end user to allow for better contrast.
- Accessibility has been improved on all controls.
- The Omnia Admin link is now available for all users.
- Fixed graphical bug in the last updated documents block.
- Made sure that pages that are set to be hidden in the current navigation does not show up in the mobile navigation either.
- Fixed issue with profile images being stretched in Quick Search.
- Fixed issue with special characters in comments on important announcements.
- Added image title in the search result in the new Media Picker when hover an image.
- Fixed so that the Related Links block doesn't take up any space if empty.
- Made sure it is possible to set the sort order of refiners in the People Rollup.
- Fixed issue that it was not possible to add a term to an open term set if no terms exists.
- Improved the RSS Reader block to support more types of RSS feeds.
- Fixed icon for DOCM documents in the Document Rollup block.
- Fixed look and feel of the Site Directory on an Android phone.
- Fixed issue with not being able to edit the Controlled Documents Viewer settings on a classic web part page.
- Fixed issue with checkboxes in iPad landscape mode.
- Fixed issue with Site Contents link always going to the root even if on a sub publishing site.
- Fixed problem with share feature in IE11 and Edge.
- Fixed issue with comments and likes not showing on a page if user that made a comment is deleted.
- Fixed some style issues in the Site Directory.
- Fixed problem with the My Links block chaning sort order when the My Links navigation is used in the header.
- Made it possible to have Lotus Notes links in Related Links on a page.
- Fixed rare issue that the title on the page could end up over the page image.
- Fixed word wrap issue in the People Rollup block.
- Fixed issue with Important Announcements in the notification panel not rendering HTML text correctly.
- Fixed issue with Date Pickers in the news center on certain sites.
- Fixed missing space character in Swedish upload text in the Media Picker.
- Fixed issue with the Advanced Search button disappearing in Quick Search when you navigate between pages.
- Fixed design issue in News Viewer when comments and likes where missing on an article.
- Fixed design issue with paging control in News Center if only one new article exists.
- Fixed design issue in certain dialogs in IE11. Icons from the header was shown above the dialog.
- Fixed issue in IE11 in the actions menu when words wrap.
- Made sure column settings in the People Rollup block fall back to default language if translation does not exist.
- Fixed issues related to moving pages in Manage Content from one sub site to another.
- Fixed stretch profile images People Rollup and Page Properties blocks.
- Fixed critical issue with Followed Sites in My Sites navigation and Last Updated Documents caused by an update by Microsoft in SharePoint Online.

Omnia.DocumentManagement (1.0.14997)
----------------------------------------
- All dependencies to Angular 1 have been removed. Document Management is no longer dependent on the feature "Omnia Angular1 Support" being activated.
- Fixed issue with a certain status on a controlled document in the Drafts view making it stuck when loading the view.
- Fixed issue with the following tab in the Create Document wizard not showing all followed sites.
- Fixed issue that certain term sets did not showing children in the Create Document Wizard.
- Fixed issue with the Controlled Documents Library filters on newly created sites.
- Fixed problem with the links in the statistics report in Omnia pointing to the wrong url's.
- Fixed issue showing many related controlled documents in the process viewer.
- Fixed issue with missing sub term in termset in filters.
- Fixed issue with tasks in My Tasks not redirecting to the correct view.
- Fixed issue with HTML in custom localizations not being rendered as expected.
- Performance improvements when getting Document Types.
- Fixed issue with buttons in Controlled Documents Library not being displayed correctly in some environments.
- Ensured the Edition property is shown again in the Properties dialog.
- Made sure HTML was rendered correctly for custom localization texts.

Omnia.QMS (1.0.14859)
-----------------------------------------
- Fixed issue with loading linked process using direct url.
- Fixed issue with custom process image showing wrong cursor icon on hover.
