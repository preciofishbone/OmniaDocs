Setup Publishing Site
===========================

Follow these steps to setup a publishing portal with basic Omnia features activated.

1. Go to SharePoint admin center.
2. Create a new site collection based on the Publishing Portal template.
 .. image:: wcm-new-site-collection.png
3. Go to the start page of the newly created site collection.
4. Go to Omnia Admin > Features.
5. Makes sure that the following tenant scoped features are activated:
 - Omnia Glue Core
 - Omnia Intranet Core
 - Omnia Intranet Content Management Core
 - Omnia Intranet Navigation Core
 - Omnia Intranet Social Core
 - Omnia Statistics Provider Core
6. Navigate to Omnia Profiles and add a new profile for the intranet.
 .. image:: wcm-newomniaprofile.png
7. Click on Default Mapping and select “Intranet” and click save.
8. Navigate to Features.
9. Activate the following Site Collection scoped features:
 - Omnia Core Master Page
 - Omnia Core Image Renditions
 - Omnia Intranet Content Management
 - Omnia Intranet Content Types
 - Omnia Intranet Page Layouts
 - Omnia Start Page Layout
 - Omnia Intranet Web Statistics
10. Activate the following Site scoped feature "Omnia Glue Site".
11. Go back to the start page and Site Settings > Master pages and page layouts.
12.	Find OmniaStartPage.aspx, edit properties and change the Associated Content Type to Web Page.
 .. image:: wcm-associatedcontenttypes.png
13. Publish a new major version of the page layout OmniaStartPage.aspx.
14. Go back to the start page and change the page layout to “Start page”.
 .. image:: wcm-pagelayouts.png
15.	Delete all out of the box web parts from the page and publish it.
16.	Go to “Site Settings” > “Page layouts and site templates”.
17.	Limit the available page layouts according to the below.
 .. image:: wcm-availablepagelayouts.png
18.	Go back into “Page layouts and site templates”, select “Page with left navigation” as default page layout, and click on OK.

Follow these steps to setup quick pages in the publishing portal.

19. Go to Omnia Admin > Content Management.
20. Click on Enable Quick Pages.
21. Select “Yes” and click save.
22. Go to the start page and temporarily change the SharePoint page layout to “Page no left navigation”.
23. Open Manage Content and click on the Start node.
24. Uncheck “Enable legacy web parts” and save the page.
25. Go to the start page again, switch the SharePoint page layout back to “Start page”, and publish the page. 
26. Go to Site Settings > Welcome Page.
27. Change the welcome page so that it points to Omnia.aspx that is located in the root pages library.
 .. image:: wcm-setwelcomepage.png
(Note! It may take some time for the SharePoint cache to release the old welcome page. Now is a good time to get a coffee before you continue.)

Follow these steps to setup basic page properties in the publishing site.

28. Go to the start page of the main publishing site.
29. Go to Omnia Admin > Content Management > Page Properties.
30. Add the page properties that you would like to show on web pages in the publishing site.
 .. image:: wcm-pageproperties.png

 Follow these steps to set up review and content management reports.

31. Go to the start page of the main publishing site.
32. Go to the Site Settings > Site Columns.
33. Edit the Review Date:
 - Change to Date and Time Format to “Date Only”.
 - Set the Default value to “[Today] + 365”.
 .. image:: wcm-reviewdate.png
34. Go to Omnia Admin > Content Management > Page Properties.
35.	Check the box to show the property Review Date in Edit mode and save.
36.	Go back to the start page of the main publishing site.
37.	Open Manage Content and create and publish a new page.
38.	Now it is a good time to grab a coffee, because the search engine needs to crawl this page.
39.	Go to SharePoint Admin Center > Search > Manage Search Schema.
40.	Map the managed property RefinableDate05 to ows_q_DATE_OMIReviewDate.
41.	Map the managed property RefinableString50 to ows_Title, TermTitle and (Category:Office)2.
 .. image:: wcm-managedproperties.png
42. Go back to the main publishing portal.
43.	Go to Site contents > Pages library settings > Advanced settings.
44.	Click on “Reindex Document Library” and click OK.
45.	Go to Omnia Admin > Content Management > Web Report Settings.
46.	Set “Managed Property For Review Date” to RefinableDate05.
47.	Set “Managed Property For Title” to RefinableString50.





