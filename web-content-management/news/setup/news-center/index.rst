Setup News Center
===========================

1. Go to the start page of a publishing site.
2. Create a new sub site.
 .. image:: wcm-news-createsubsite.png
 
 .. image:: wcm-news-peopleandgroups.png
3. Go to Omnia Admin > Features.
4. Ensure the tenant scoped feature “Omnia Intranet News Core” is activated.
5. Activate the site collection scoped feature “Omnia Intranet News Infrastructure”.
6. Activate the following site scoped features:
 - Omnia Intranet News Center
 - Omnia Intranet Social
7. Go to the start page of the News Center.
8. Go to “Site Settings” > “Page layouts and site templates”.
9. Limit the available page layouts to “News article” and click ok.
10. Go back to “Page layouts and site templates” and click ok in order to get the correct default layout.
11. Go to Omnia Admin > Layouts.
12. Select the News Center site using the Site Picker.
13. Uncheck “Inherit Parent Settings”.
14. Remove the following layouts:
 - Omnia Intranet Start
 - Page with left navigation
 - Page no left navigation
15. Make the layout “News article” default.
16. Go to Features and activate the site feature “Omnia Image Picker Settings”.
17. Click on Image Picker in the left-hand navigation.
18. Select the local Images library.
19. Select the renditions “Square” and “Landscape (New)”. (Note! These renditions are used in the New UX experience in the News Viewer.)
20. Go to the start page of the news center using its quick page url https://customer.sharepoint.com/sites/intra/#/news/Pages/NewsStartPage.aspx.
21. Go into edit mode using the Omnia Edit Switch.
22. Add the fields Article Date and Enterprise Keywords as filters and change the paging type to Scroll.
 .. image:: wcm-news-setfields.png
23. Publish the page and create a couple of news articles to validate that all settings are applied as expected.