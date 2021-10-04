1.30.0
========================================

Fixes
***********************
- Fixed an issue with the paging of the site directory (#117428).
- Stability fixes to the RSS feed viewer (#117428).
- Fixed an issue when picking images causing faulty URL encode (#109054).
- Image rendition on pages now work correctly (#121662)
- Unique per site property settings now works as expected (#127714).
- Site creation prefix for publishing subsites is now localizable (#122393).
- Existing videos can now be correctly edited in Manage content (#108060).
- Corrected an issue with default colors being configured in the RGB format (#108760).
- Corrected an issue with the preview in a multilingual context (#116649).
- Fixed an issue with duplicated link titles for the related links block. (#121021).
- Fixed an issue preventing adding media to the footer.
- Design updates for several components when using IE11.
- Background color is now applied with the same logic for both CDV and Process Rollup.
- Fixed an issue when chaing back and forth between legacy page and quick page (#106316).
- Updated row break logic for the Document Rollup.
- When pressing enter in a filter on the Site Directory, the page is no longer reloaded (#110832).
- Corrected the query logic for my latest documents (#124223).
- Several stability fixes to how page layouts are loaded (#117912).
- Corrected an issue causing the site URL of last updated documents to sometimes be incorrect (#108976).
- Fixed an issue causing preview not to work after moving a page between subsites.
- Corrected an issue with reordering Refiners and Columns in the CDV and People Rollup. (#124261).
- Updated email validation for feedback email in user profile completeness.
- Fixed a deadlock issue that would occur when publishing a page on a deleted node. (#109742).
- Corrected an issue with translation and preview (#116649).
- Corrected an issue in ODM that would give pdf converted files the wrong file ending. (#114673, #118052)
- Publishing sites are now correctly hidden from My Sites, if configured to do so (#102365).
- Fixed an issue with validation of approver in ODM (#128165).
- Ensured Custom action rendering for manage content (#109514).
- Fixed an issue with notifications when publishing controlled documents in certain situations (#128037)
- Fixed an issue with the Trending pages block, it will now correctly default to current site (#107863).
- Corrected an issue with site approval when the approver name is very long (#108567).
- Fixed a glitch that would cause the rendering height to be incorrect (#121667, #117300).
- Corrected an issue with priority that would sometimes cause duplicates (#108597).
- Corrected issues related to manage content and translation preview (#116649).
- Tutorial tooltip enhancements (#115376).
- Corrected an issue what would occur when changing node segments (#119434).
- Fixed an issue with the process step breadcrumb (#128264, #128548).
- Fixed an issue in the localization UI (#129156).
- Corrected an issue with the filtering of  the Manage Content report (#119833).
- Corrected issues regarding statistics (#128437).
- Fixed an issue in regars to document types not being available when creating a new controlled document (#129813).
- Fixed issues with padding on blocks in some situations (#130923).
- Corrected an issue with the prople rollup block not loading any content in some cases (#128585, #130746).
- Corrected an issue with sites not showing up in the "My Sites"-block in some cases (#129892).
- Fixed an issue with the statistics provider (#131137).
- Fixed an issue with users having different UPN and email (#130779, #130358).
- Fixed an issut with saving properties on pages and banners (#131756, #131797, #131896, #131892).
- Corrected the sort order for people rollups (#131208).






Changes
************************
- Updated aggregated calendar to work better with bright accent colors (#113520).
- MS Teams apps can now be enhanced with the query parameters “tenantheader”, “omniaheader” to hide headers when creating an app. (#109700).
- Updated padding for some news viewer views, they now look better in the notification panel (#108563).
- Link to news center now supports being right clicked and opened in a new tab (#107794).
- The omnia master page will now indicate correct language allowing built in browser features to do correct translations.
- Added a feature do exclude files by filetype in the "My Recent Documents" (#102800, #114550)
- Its now possible to search by document id when searching for related documents (#120300).
- Added Start and End dates to the Aggregated Calendar detail’s view.
- Better reactivity in the glue editor, no page reloads should now be needed to see new settings.
- Titles are now more consistent in its word-break behavior.
- There is now a clear button for the current search in the People Rollup.
- Updated validation for site provisioning to avoid collisions with distribution lists (#108471).
- Ensured upgrades of ODM Features will work better in the future (#123319, #117128).
- Added a color setting for the notification bubble of the notification panel in the header (#121289).
- The Aggregated Calendar design has been improved to better handle for example multiple calendars (#117818, #118759, #108871).
- Several stability changes to localization (#120437).
- Updated the permission checking of showing the site quick edit control (#114472).
- The Controlled Document Viewer new correctly word-wrap on space. (#101541, #107194).
- Targeting mappings are now sorted alphabetically(#107658).
- Several stability fixes to the glue page editor (#111295, #110827).
- Responsiveness of the mega menu has been improved (#107814).
- Improved design of the Mobile Refiners in the Document Rollup (#122425).
- "Cascade to left" in the glue editor has been removed (#112301).
- Its now possible to click on the notification indicator (#102926).



New Features
*****************************
- The Footer now has multilingual support (#115318).
- Changed the data storage for QMS to allow for larger processes (#126028, #126056, #124523)
- My Sites now supports a direct link to MS Teams (#119911).

For Developers
*************************
- Corrected the Field provisioning for Lookup Fields.
- HTTP DELETE is now supported in the MSGraph API.


