Setup People Rollup
===========================

1. Go to Omnia Admin > Features.
2. Activate the tenant scoped feature “Omnia Intranet People Rollup Core”.
3. The People Rollup block is now available in quick pages.
4. If you want to add support for the People Rollup legacy web part, go to Omnia Admin > Features and activate the site collection scoped feature “Omnia Intranet People Rollup Web Part”.

Follow these steps to setup a profile property.

5. Go to SharePoint Admin Center > Search > Manage Search Schema.
6. Filter on “RefinableString100”.
7. Edit the property, map it to People:PreferredName and save the property.
8. (Online, it is a bit tricky to get the user profiles reindexed, which is required in order for new properties to appear. You can wait around for a couple of hours, weeks, months or you can check this blog post: http://www.techmikael.com/2014/12/how-to-trigger-re-indexing-of-user.html).
9. Go to System > Settings > Search Properties.
10. Add a Search Property.
 .. image:: peoplerollup-searchproperty.png
11. This property can now be used to sort on in the People Rollup block.