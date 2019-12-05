Controlled Documents Library
===========================

When a group site has been set up for Controlled Documents authoring, the following will be available for Controlled Document authors:

+ A documents library (Controlled Documents) that only users defined in the author’s permission group can work with.
+ A Send for Comments Workflow.
+ A Publish Workflow.
+ A Tasks list.
+ Workflow History.
+ Document History for drafts.
+ Document History for the published editions.
+ Options for relating to other documents.
+ Options for relating to QMS Processes (if Omnia QMS is installed).
+ Options for creating a new draft from a published document.
+ Options for unpublishing a published document.

In the Controlled Documents library, authors can find three tabs:

.. image:: controlled-documents-library-1-new.png

"Drafts" is used when creating and editing drafts for new Controlled Documents or when updating an existing document for a new edition. Note that there are several options available for creating a new draft document, see below.

"Tasks" is a list of tasks for the documents – either for review or for publication – both active and finished.

When a document is published (approved for publication) it is removed from Drafts and is available on the "Published" tab. Here the options for creating a new draft, unpublishing and Document History are available.

Most headings can be used to sort the list.

What fields to display on each tab can be selected in the settings, se below.

Settings for the Controlled Documents library
**********************************************
As a Site Collection Administrator you can set a number of settings for the three lists in the Controlled Documents library.

Find the settings this way:

1. Click the cog wheel and select "Edit page".

.. image:: dm-edit-page.png

2. Open the settings.

.. image:: dm-edit-page-settings.png

Don't forget to save when you have changed any settings. The "Save" button is at the very bottom of the window.

The General tab
-----------------
Here you can use the following settings:

.. image:: cdl-settings-general-new-border.png

+ **Default tab**: Decide which tab will be shown when an author enters the Controlled Documents library.
+ **Number of rows to display on each page**: Set the number of rows to display before navigation to the next page will be shown at the bottom of the list.
+ **Open in Office Web Apps**: If documents should be opened in Office Web Apps, instead of a locally installed application, select this option. (If you select this option, authors can still choose to edit the document in the locally installed application, when the document is open.)
+ **Hide Tasks Tab**: If the Tasks tab should not be displayed for authors, select this option.

The Drafts tab
----------------
Here you can set the following:

.. image:: cdl-settings-draft-new2.png

+ **Default Sort Order**: Select the column for default sort order for the list.
+ **Sort Direction**: Select Descending or Ascending for the default column selected above.
+ **Show Search Box**: If authors should be able to search for drafts here, select this option.
+ **Select the columns .....**: Check the columns to display in the Drafts list, and uncheck columns you don't want to display. (But note that the some columns can't be unchecked, they are mandatory.)

The Published tab
-------------------
Here you can set the following:

.. image:: cdl-settings-published-new2.png

+ **Default Sort Order**: Select the column for default sort order for the list.
+ **Sort Direction**: Select Descending or Ascending for the default column selected above.
+ **Show Search Box**: If authors should be able to search for documents in the Published list, select this option.
+ **Select the columns .....**: Check the columns to display in the Published list, and uncheck columns you don't want to display. (But note that the some columns can't be unchecked, they are mandatory.)

The Document Types tab
----------------------
You can set the following on this tab:

.. image:: cdl-settings-types-new.png

+ **Language**: Select language for the Document Types to be shown in the list below.
+ **Document types**: Select which Document Types should be suggested when authors adds new draft documents here. If empty, all Controlled Documents templates will be suggested.

Creating a draft document
**************************
When adding documents to a Controlled Documents library the author can either create a new draft or upload a document. If it’s a Controlled Document the author will actually work with here, a document should normally be created from scratch. 
If it’s a document that will be used as it is, for example as an appendice, it makes more sense to upload the document.

Creating a new draft document
----------------------------------
When creating a new draft document from scratch, the first step is to select "New" in the "Add" menu.

.. image:: dm-add-new.png

The next step is to select language and a document type:

.. image:: new-draft-1-new2.png

The Document Types are set up in Omnia Admin. 

The list displayed the suggested Document Types. To see a complete list, select "Show all".

One or more Document Templates are available for a Document Type. If more than one is available, the next step is to select template.

.. image:: new-draft-2-new2.png

And enter a Title and a File Name.

.. image:: new-draft-2b-new2.png

And then, the next step is to enter information for the document’s properties (metadata). What that will look like depends on the Document Type. Here’s an example:

.. image:: new-draft-3-new2.png

A number of mandatory fields can be present, marked with an asterisk (*). All mandatory fields must be filled in, or the document can  not be published, but it does not have be now.

Metadata can also, in some cases, be used as a filter for document lists, to make Controlled Documents available for users when they are published. Besides that, available approvers can depend on the metadata added. It’s always very important that information in metadata fields are added thoroughly.

A "tag" icon to the right in a field always indicates that it is a managed metadata field, for example:

.. image:: new-draft-4-new2.png

When the properties has been entered and the author clicks "Create", the editing program (for example Microsoft Word for Word files) starts with the chosen document layout. Text and so on is entered the normal way. 

**Note!** Metadata fields visible in the document, displayed within double brackets, should not be used in the editing process. Information will be added to these fields when the document is published.

Uploading documents
--------------------
An alternative is to upload an existing document, but normally it should be used just for documents that will be added as they are, but will still be handled as Controlled Documents, for example with approval before publishing.

Upload is selected in the "Add" menu:

.. image:: dm-add-upload.png

A Document Type has to be selected for an uploaded document and the document has to be tagged with the required metadata, or he document can't be published.

The template for the Document Type is not used for the first edition of the document, the document will be used with the exeisting template (of any). The next time a draft is created for an uploaded document, the template can be altered, if needed.

To select Document Type and add metadata, use the option "Properties" in the document's menu, after the document has been uplodade.

Move a document to the Controlled Documents library
----------------------------------------------------
You can move a document, or several if you like, from any other Documents library in this Team Site, to the Controlled Documents library, and thus make them a Controlled Documents Draft.

Do the following:

1. Click “Add” and select "Move".
2. Open the library.

.. image:: dm-move-library.png

3. Open a folder if needed.
4. Select one or more documents to move.
5. Click “Get Document”.

.. image:: dm-move-library-documents.png
 
Now the selected document(s) are moved from the original Documents library and into the Controlled Documents library as drafts.

Upload Appendices
------------------
To upload documents to use as appendices to another document, the main upload option should not be used.

Note that status must be "Draft" for the option to be available. If a document is sent for comments or for approval, appendices can not be uploaded to that document. Also note that a Document Type contains a setting that states if appendices are allowed or not. For a document tied to a Document Type with appendices not allowed, the Appendices option is not available (gray).

1.	Open the dot menu for the document to add appendices to, and select "Appendices".
2.	Click "Upload" in the window shown.

.. image:: upload-appendices-1-new.png
 
3.	Drag and drop one or more documents to the upload window.
4.	Click "Upload Files" to start the upload.
 
When the upload is finished the file(s) is visible in the Appendices list for the document, for example:

.. image:: upload-appendices-2-new.png
 
"Edit" can be used to edit the content of the appendix, if the file format is editable. "Rename" can be used to change the document's name. Use "Delete" to remove an appendix from this list.

Appendices can be added to this list continuously up to publication of the document. If appendices needs to be removed or added for a published document, a new edition of the document must be published.

**Note!** An appendix uploaded as shown above will not be visible in the Drafts list, but will only exist as a part of the main document. When a document with appendices is published, both the main document and the appendices are approved in one go. The appendices does not have to be approved separately (but also see below).

Published documents as Appendices
-----------------------------------
Another option is to add a copy of a published document as an Appendice. It must be a document that is published in this Controlled Documents library.

**Note!** In this case it is a copy of a document that will be added. There is no link between the published document and the copy, so if a new edition of the Appendice document is published, the copy used as an appendix is NOT updated.

1.	Open the dot menu for the document where you want to add appendices, and select "Appendices".
2.	Click "Copy from other Document" in the window shown.

.. image:: upload-appendices-3-new.png
 
3.	Search for the document. 
4.	Select the documents to add (a copy of) as appendices and click "Copy", for example:

.. image:: upload-appendices-4-new.png
 
The documents added to the Appendices list this way is handled exactly the same way as a document uploaded as an appendix, see above. (And remember that it is a copy of the original document.)

Creating a new draft from a published document
***********************************************
The work on a draft for a new edition of a document can be started whenever it’s convenient. The existing published edition is still available for readers until it’s replaced, when the new edition is published.

To create a new draft of a published document, do the following:

1.	Open the "Published" tab.
2.	Click the dot menu for the document.
3.	Select "Create Draft".

.. image:: create-new-draft-1-new.png

4. Choose what is to be done:

.. image:: create-new-draft-2-new2.png

As you see you can even upload a document to base the new draft on. This can be useful for example when you want to publish a new edition of a document you have uploaded as it is. Perhaps you have received a new version of a document from a supplier?

If you select “Previous Edition”, you can select which of the previous published editions you want to base the new Draft on. If you want to have a look at that edition before deciding, you can download a copy of the previous edition you selected in the list, by clicking this icon:

.. image:: create-new-draft-previous.png

The new draft is created and the "Drafts" tab is automatically activated. The work on the new draft is done exactly as the first time. That a document has been published before does not make any difference.

**Note!** There can be only one draft of a given document. If there already is a draft for the document and an author tries to create another on, a message is shown stating that it's not possible. 
 
New drafts and templates
-------------------------
If there is a new version of the template used for the document, the author will be notified and can choose to use the new version of the template, or stick to the old one.

A special case is when a new draft is created from a Word or Excel document that was uploaded rather than created from scratch. When a new draft for a second edition is created, the template can be altered (or rather selected). But using a template for an uploaded document is never mandatory, the document can always be used as is.

When selecting a template for an uploaded document, it’s always a good idea to use the preview to make sure the selected template actually works for the document.

If a template is selected, this document is from now on related to the template the same way as when a new document is created from scratch on the "Drafts" tab.

Even if a template is not selected for the second edition, the author gets a new chance the next time a new draft is created.

The Tasks tab
***************
Using the Tasks tab you can see three different lists:

Assigned To Me
----------------
As it says, this list displays all tasks that have been assigned to you.

It can be:

+ Tasks from Send for Comments workflows.
+ Tasks from Publish workflows.
+ Tasks for review when set Review Date has passed.

To work with a task, just click the Title. You can click the link to read the document. To see additional information about the document, click the i icon. 
 
If it’s a task for reviewing a document when the Review Date has passed, you check the document and can decide what to do; set a new Review Date, unpublish the document or create a new draft of the document.

Assigned By Me
----------------
This list displays all Tasks created, when you sent a document for comments or when publishing a document. To check the progress for any of the tasks, click the Title. 
 
Completed Tasks
-----------------
As it says, this tab displays a list of completed tasks. You can click the link to a task for more information, for example to see the comment(s).

More useful Options for a published document
********************************************
There are some more useful options for a published document, you can for example check the Properties, see the Document History, see Feedback that users has sent and Move a document.

Related Documents
--------------------
Description of this option is found here: :doc:`Related Documents </document-management/author/related-documents/index>`

Checking a document's properties
---------------------------------
The properties for a published document can be checked this way:

1.	Click the dot menu for the document.
2.	Select "Properties".
 
The Properties window for the document is shown, for example:

.. image:: document-properties-new.png
 
The properties can not be edited here. The properties can only be edited when working on a new edition of the document.

Document History
------------------
There’s information about each published edition available. To see it, do the following:

1.	Click the dot menu for the document.
2.	Select "Document History".
 
Here’s an example:

.. image:: document-history-new2.png
 
You can see the publication date for each edition, the author’s comment, if any, and who the document was approved by. The option "Workflow History" for an edition will show information about when workflows was used and the comments entered during the workflows, so here you can even see information from Send for Comments workflows used for the document.

Check Feedback
---------------
Any user can send feedback on a published document and that feedback is available for authors here. The read feedback for a document:

1.	Click the dot menu for the document.
2.	Select "Feedback".
 
The feedback posts for the document is shown. You can click the dust bin to delete the feedback when you have read it, or keep it for later reference, it’s up to you.

3. To see the comments, expand a post:

.. image:: feedback-expanded.png

Read Receipt Status
--------------------
Read Receipt Status can be checked here. See this page for a description: :doc:`Read & Understood </document-management/author/read-understood/index>`

Move a published document
-----------------------------
A published document can be moved to any other site with a Controlled Documents library. If a draft for a new edition of the document is present, the draft must first be deleted.

**Note!** You must first check and note (or copy) the URL to the site you want to move the document to.

1.	Click the dot menu for the document.
2.	Select "Move Document".
 
The following is shown:

.. image:: move-document-new.png
 
3.	Type the URL (or paste, if you have copied it) to the site in the top field and click "Resolve". If the URL is correct the site title is shown in the second field.
4.	Click "Move".

Unpublish
----------
For information about this option, see this page: :doc:`Unpublish </document-management/administrator/unpublish/index>`

