Release Notes September 2018 Patch 1
========================================

Omnia.Foundation (1.0.13674)
----------------------------------------
- Fixed the problem that certain CSS styles in Vuetify spilled over into classic SharePoint.
- Fixed missing localization label for the Close button in the Strengthen Profile block.
- Fixed issues with the Strenghten Profile UI on mobile devices.
- Fixed problem with missing js file for German localization.
- Fixed issue with missing values for Person fields in Site Request form.
- Fixed some general localization problems with the new modern blocks.

Omnia.Intranet (1.0.13697)
----------------------------------------
- If central naming policies are applied to Office 365 Groups, the create site wizard will raise a warning if the name of the new site does not align with the policies. (In a coming release, the create site UI will help the user to be compliant with the policies).
- Fixed issue with german localization in Aggregated Calendar.
- Added a possibility for web authors to see which status the page is in (draft, published, waiting for approval). It the page is not published, an info icon will be shown next to the Quick Edit button on the page.)
- Made sure a page is not checked out when clicking on the quick edit button if the page is in waiting for approval status.
- Fixed issues with approval for translated pages.
- Fixed issue with the Go to News Archive button in the News Viewer with IE11 on Windows 7.
- Fixed issue with the setting Preferred Language in the News Viewer.
- Fixed issue with the paging control in the News Archive.
- Fixed issue with long descriptions in an event in the aggregated calendar.
- Fixed issue with Show all Events in mobile mode.
- Fixed issue with targeting in the RSS reader block.
- Fixed issue with event details not being shown for certain users.
- Fixed issue with redirect to quick page when clicking on the physical page url (for example in the page library).
- Fixed issue with following feature in My Sites creating duplicate rows. (If a user already have duplicate rows, the user needs to unfollow and follow the site again to get rid of the duplicates.)
- Fixed problems with My Sites and My Links navigation in mobile mode.

Omnia.DocumentManagement (1.0.13718)
----------------------------------------
- Fixed problem with the metadata replace feature in DOCX making the page numbering fields corrupt.
- Fixed issues with the process related documents API used by Omnia.QMS.
- Fixed some issues with the documents bulk update feature.
- Fixed issue that could happen with Person Properties when moving a controlled document from one site to another.
- Fixed issue with certain placeholders in DOCX not being able to be replaced if a color style is applied to the text.