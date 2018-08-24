Change Default Language
===========================

A common implementation problem is that a  tenant is installed with two working languages in the term store (for example English and Swedish) and English is default, but the main publishing site is set up with Swedish. This could lead to non-wanted behavior in Manage Content.
It is possible to change the default language in the term store afterwards, but it requires some manual work and should be done off working hours for customers that are already in production.

1. Go to SharePoint Admin Center > term store.
2. Make sure that you are a Term Store Administrator.
3. Change the Default Language.
 .. image:: multilingualpages-cmproperties.png
4. Go to Omnia Admin > System > Caching.
5. Delete all keys that belong to the Region “intranetnavigationlanguagecache”.
6. Go to start page of the main publishing site.
7. Open Manage Content. The following message should now appear on the start node.
 .. image:: multilingualpages-repairlanguage.png
 
Repeat the same procedure for all pages in the navigation structure.