Setup Multi Lingual Pages
===========================

1. Go to SharePoint Admin Center > term store.
2. Make sure that you are a Term Store Administrator.
3. Add the languages you would like to support in the solution as Working Languages in the term store.
 .. image:: multilingualpages-workinglanguages.png
4. Go to Omnia Admin > System > Caching.
5. Delete all keys that belong to the Region “intranetnavigationlanguagecache”.
 .. image:: multilingualpages-deletecachekeys.png
6. The selected languages should now appear in Manage Content.
 .. image:: multilingualpages-selectedlangs.png

 You need to enable MUI in the publishing site if you want to:

- Make sure that system labels, and not only content, are translated to the end user.
- Make sure that the selected language on a web page defaults to the preferred language of the logged on user.

Follow these steps to enable MUI.

7. Go to the start page of the main publishing site.
8. Go to Site Settings > Language Settings.
9. Add Alternate language(s) and save.

You can decide whether a page property should be for a specific language or if it should be shared between the different translations.

10. Go to the start page of the main publishing site.
11. Go to Site Contents > Pages library settings.
12. Create a new column.
 .. image:: multilingualpages-newcolumn.png
13. Go to Omnia Admin > Content Management > Page Properties.
14. Add the Owner property to edit and view mode and make sure it is Shared.
 .. image:: multilingualpages-cmproperties.png