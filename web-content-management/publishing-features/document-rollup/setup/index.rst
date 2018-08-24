Setup Document Rollup
===========================

1. Go to Omnia Admin > Features.
2. Activate the tenant scoped feature “Omnia Intranet Document Rollup Core”.
3. The Document Rollup block is now available in quick pages.
4. If you want to add support for the Document Rollup legacy web part, go to Omnia Admin > Features and activate the site collection scoped feature “Omnia Intranet Document Rollup Web Part”.
5. Go to SharePoint Admin Center > search.
6. Click on Manage Search Schema.
7. Filter on “refinablestring50”.
 .. image:: documentrollup-title.png
8. Edit the managed property and map the following crawled properties.
 .. image:: documentrollup-title-crawled.png
9. Go to Omnia Admin > System > Settings > Search Properties.
10. Add a new Search Property.
 .. image:: documentrollup-title-mapping.png
11. Check the Title Property radio button and save.
 .. image:: documentrollup-title-default.png

Follow these steps to setup a document property.

12. Add a new column to a document library in the solution that you would like to use.
 .. image:: documentrollup-spcolumn.png
 .. image:: documentrollup-termset.png
13. Create a document and set this new property on the document. If the document library has major versioning activated, make sure to check in and publish the document.
14. Now is a good time to grab a cup of coffee before you continue, because the search engine needs to crawl the document and it may take about 15 minutes.
15. Go to SharePoint Admin Center > Search > Manage Search Schema > Crawled Properties.
16. Filter on the name of the newly added column. (Remember that space in column internal names is replaced with _x0020_.
 .. image:: documentrollup-information-crawledproperty.png
17. Map the display name property (ows_Information_x0020_Class) to RefinableString110.
18. Map the id property (ows_taxId_Information_x0020_Class) to RefinableString111. (Note! Remove the out of the box mapped property owstaxInformationx0020Class.)
 .. image:: documentrollup-properties-info.png
19. Go to the document library where the column was added and reindex the library in Library Settings > Advanced.
20. Go to Omnia Admin > System > Settings > Search Properties.
21. Add a Search Property.
 .. image:: documentrollup-mapproperty.png
22. This property can now be used in the Document Rollup block.
