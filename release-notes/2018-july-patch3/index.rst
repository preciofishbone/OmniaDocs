Release Notes July 2018 Patch 3
========================================

Omnia.Foundation (1.0.12865)
----------------------------------------
- New behaviour in Quick Search. When a quick page is navigated to in the search result, the Quick Search dialog will close.
- Fixed issue with localization being displayed wrong in many controls.
- Fixed issue with the mobile view of My Sites and My Links.
- Made it possible to exclude personal sites from the My Sites all scope.
- Fixed Date Time error when editing a page in German.
- Fixed some issues with the tutorial of type Tooltip.

Omnia.Intranet (1.0.12862)
----------------------------------------
- Fixed issue with really long titles in News Viewer.
- Fixed issue with random events of white space in the bottom of the page.
- Fixed problem with approve/reject for news articles.
- Sort now runs on load in Document Rollup.
- When likes and comments are disabled on a page they do not show up in the News Viewer either anymore.
- Remove targeting values when saving a page with "No targeting".
- Fixed likes and comments count in news viewer for translated pages.
- Fixed issue with icon disappering the first time you search in My Links.
- Fixed issue with top nodes in the mega menu not being able to be opened in new window.
- Fixed spacing in bottom of the Document Rollup control.
- Fixed tooltop on follow in new modern My Sites control.

Omnia.DocumentManagement (1.0.12842)
----------------------------------------
- Fixed issue that could occured when deleting/publishing controlled documents because folders could not be deleted if not empty.
- Fixed issue with creating non-controlled documents in the document wizard.
- Fixed some issues with migrated controlled documents from other system. Placeholders in DOCX were not replaced as expected.
- Fixed issue with certain special characters being replaced on publishing of controlled documents.
- If you double click on the save button in Document Profile Properties, the system will create two identical properties. This issue has been fixed.
- Fixed some exceptions that could happen on publishing when having certain content within a DOCX template.
- Fixed issue with column filtering in controlled documents library after paging of documents.
- The create document wizard "All" tab does not load documents by default anymore.
- Documents with the # character in the filename could not be unpublished. This has been fixed.
- Fixed certain lables in the new document wizard not being localized correctly.
- Fixed some issue with documents being corrupt when merged with template in the draft creation wizard.


Omnia.QMS (1.0.12483)
----------------------------------------
- Fixed some temporary issues with process mapping on custom images disappearing after update.
- Made it possible also to provision task in linked processes.
- Fixed issues with newly uploaded documents in the Tools library not showing up.
- Fixed issue with double process lists on an authoring site.
- Made it possible to add AD security groups when limiting access to a process.