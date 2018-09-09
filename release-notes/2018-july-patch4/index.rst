Release Notes July 2018 Patch 4
========================================

Omnia.Foundation (1.0.13011)
----------------------------------------
- Modification of script loading to improve when many News Viewers are loaded on a page.
- Removed localization limitation in Omnia Admin.

Omnia.Intranet (1.0.13008)
----------------------------------------
- The correct comments and likes count are now shown for translated news articles in the News Viewer.
- Fixed bug with draft pages not being deleted in the Pages library in SharePoint.
- Fixed JS error showing up in the developer console. "Cannot read property 'replace' of null...".
- Fixed issue with Tutorial permissions for editors.
- Fixed an issue in targeting of common links. A specific label was not able to be set.
- Removed a reference to "https://r3.res.outlook.com/o365/versionless/wexprereq_3750ce96.js" that is no longer available.
- Fixed issue with deactivating targeting in a News Center.
- Fixed issue with dialog freezing on publishing in specific content structures.
- Fixed issue with banner targeting not working as expected in the Notification Panel.
- Fixed issue with People Rollup showing access denied for external users.
- Fixed issue with encoded characters in Document Rollup query.
- Fixed issue with the text not showing up if News Viewer returns no items.

Omnia.DocumentManagement (1.0.13001)
----------------------------------------
- Fixed issue with workflow history being empty on certain draft documents.
- Fixed issue with the navigation filter in the Controlled Documents Viewer.
- Fixed issue with draft documents showing up (for editors) in the Controlled Documents Viewer when using specific queries.
- Fixed issue with missing controlled documents in the Process Viewer (in QMS) if to many documents selected.
- Fixed issue with PDF converted preview copies showing up in the drafts view when documents where in "waiting for approval" state.
- Made sure that the Document Icon in the top menu is removed when Omnia Document Managemnet is uninstalled.
- Fixed issue with certain documents showing error when clicking on the info icon in the Controlled Documents Viewer.
- Fixed issue with problem when finding specific people in bulk update in Omnia Admin.
- Fixed issue with e-mail not being sent out in workflow for specific people.

Omnia.QMS (1.0.12978)
----------------------------------------
- The breadcrumb in QMS has been changed to support integration with Omnia Intranet. If no specific start node is set in the Process Viewer, the current navigation node in the content structure will be used as start node.
- Fixed specific issues when adding Tools.
- Fixed issue with linking directly to a sub process using a url.