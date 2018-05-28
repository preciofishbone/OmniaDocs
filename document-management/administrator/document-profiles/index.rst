Document Profiles
===========================

Here you can set up as many document profiles as you need, in the different languages you're using. A document profile has a specific set of properties, and has one or more defined document layouts.If you just have need of one, edit the name, set properties and select layout for the default document profile.  

Document profiles are used for Document Types. You select one Document Profile for each Document Type and select which Document Layout to use, from the list defined for the Document Profile.

**Note!**
Document profiles inherit properties from it's "parents", but you can change status for the properties on a specific profile when nedded. Therefore it can be a good idea to set up all properties that most of the profiles will share, at the top level. For a Document Profile that will not use a certain property, you can set that property to hidden there. A property can even be hidden at the top level, and shown on other levels. The same is true if you have many Document Profiles and work with groups of profiles, you can set all properties the group will share on the group's top level.

+ To create a new Document Profile, click the plus.
 
.. image:: document-profiles.png

You can even group Document Profiles.

.. image:: document-profiles-2.png

+ To create a sub profile, select the profile and click the plus.

Settings for Document Profiles
*******************************
The settings are organized in three tabs, see the sections below.

The General tab
---------------
Enter or edit the name here. The name is displayed when selecting Document profile for a Document Type. If you are using several languages, the name can be set in each language. Save the name before entering another tab.

.. image:: general-tab-new2.png

The Layouts tab
----------------
A Template is a prepared document that an author can use as a starting point when creating a document of a certain type. A Template Document can contain as much content as is applicable. Regarding Microsoft Word Document Templates, the prepared document will normally contain a set heading and in some cases a set footer, with fields that can be populated with data when the document is published. See separate section for information on how to create Template Documents: (Link) [Creating a Template Document](/Docs/en-us/creating-a-layout-document/index.html)

There can be one or more templates defined for a Document Profile. Here’s an example:

.. image:: templates-tab.png

To see a list of templates for another of the languages you use, select the language in the list.

**Note!** This tab and the "Document templates" setting are connected. Changes you make here for Controlled Documents Templates are reflected in "Document Templates" and vice versa.

Adding a new template
--------------------------
Do the following:

+ Click "Add new template".

.. image:: add-new-template.png

You can either link to an existing, published controlled document, or prepare and upload a new document, to use as a template.

Link to Document
-----------------
To link to a document:

+ Enter the document-id and click "Find".
+ When you have found the document, click "Save".

**Note:** When a new edition of the linked document is published, the template is automatically updated. When an editor creates a new document based on document type with a linked document as template, the latest edition is always used. Existing, published documents are not changed.

Upload document
---------------
To upload a document to use as a template:

+ Select "Upload Document".
+ Set a name. This name is displayed for the author, so make sure it’s really understandable.
+ Click "Browse"  to find the document on your computer and select it.

.. image:: dd-new-template-browse.png

+ Click "Save".

Editing and removing templates
-------------------------------
To edit or remove a template, use the icons:

.. image:: adding-template.png 

**Tip!**
When editing a template you can “update” by uploading another, updated file, but still use the same template name.

.. image:: edit-template-browse.png


