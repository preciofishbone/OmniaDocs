Controlled Documents Viewer
===========================

The Omnia Controlled Documents Viewer can be used on any publishing page to make certain controlled documents available for users. The control can even be used several times on the same page, for different lists of controlled documents.

Access permissions apply, the controlled documents the user can find using the control, are documents that the user has read permission to. Read permissions are handled in the team sites used by authors to publish Controlled Documents.

The Omnia Controlled Documents Viewer can be added and edited by any editor that has edit access to the page.

The user experience
*******************
Once a Controlled Documents Viewer has been added to a publishing page and set up by an editor to decide what Controlled Documents to display, any user that has access to the page can use the control to find Controlled Documents.
 
Normally (but this can be set, see below), at the start the list contains all documents the control has been set up to display. The refiners can be used to display only the documents tagged with a certain property value.

.. image:: document-center.png

In this example there are 7 documents tagged with the product Cheetah and if that refiner is selected, the list could look like this:

.. image:: document-center-cheetah.png

Search (if turned on, which is the default) can be used to search for content in the displayed documents.

The columns contain information about the documents. To the right there can be two very useful icons (if turned on, which is default).

Users can click the i-icon to display all properties for the document.

.. image:: controlled-documents-viewer-refined-info.png

Here's an example:

.. image:: controlled-documents-viewer-properties-new3.png

Everyone can use the links at the top (to be able to open this window, a user must have access to the document) to see the Document History or go to the library to read the other Controlled Documents published from there.

Everyone can also choose to follow a document from here. See this page for more information about how this works: :doc:`Followed Controlled Documents </document-management/end-user/followed-controlled-documents/index>`

If you are assigned as author to the Controlled Documents library where the document reside, you can use the buttons at the bottom to create a new draft of the documents or unpublish the document. No one else will see these buttons.

The icon to the far right...

.. image:: controlled-documents-viewer-refined-feedback-icon.png

... can be used to send feedback on the document.

.. image:: controlled-documents-viewer-feedback-new.png

The feedback is sent to the Controlled Documents library from where the document is published, and the authors can read it there. A mail can also be sent (depends on settings) to either the document owner or the approver.

Additional columns can be added, see below. 

Settings for the control
*************************
The settings are organized in six tabs, see the sections below.

The General tab
-----------------
On this tab the following settings are available:

.. image:: controlled-documents-viewer-general-new3.png

+ **Title**: Add the title shown to users for the control.
+ **Search scope**: The search scope can be either Published Documents or Archived Documents. Published Document is the default.
+ **Default Sort Order**: You can select a default sort order from the list.
+ **Sort Direction**: Set sort direction - Ascending or Descending.
+ **Page Size**: Set the number of documents to be shown on ech "page" of the list.
+ **Paging Type**: Select "Classic", as seen in the images at the top of the page, or "Scroll".
+ **Show Search Box**: If users should be able to search the documents displayed by the controll, the option should be checked.
+ **Open in Office Web Apps**: If a document, when a user clicks the link, should be opened in Office Web Apps, the option should be checked. If not checked, documents will open in the full application.
+ **Open in new window**: If the documents should be opened in a new window, when the user clicks a link, select this option.
+ **Show "Subscribe To..."**: If the "Subscribe To" link should be displayed, helping users to subscribe to the documents that are listed in this control, select the box.

**Note!** Do not use "Show Subscribe To .." for a control using filters. When a user clicks the subscribe link, the subscription added is always for the default list, no matter what filtering the user has done, making it difficult for a user to understand what he or she subscribes to.

There are two alternatives to following all documents in a list (cklick the links for more information):

+ :doc:`Controlled Documents Subscription </document-management/end-user/controlled-documents-subscription/index>`
+ Followed Controlled Documents (link to be added).

The Query tab
--------------
This tab is used to decide which Controlled Documents to display in the control.

.. image:: controlled-documents-viewer-query-new2.png

+ **Query Builder**: User the Query Builder to build querys for which documents to show here. Note the example in the image.
+ **Select Documents**: Use this option to select a number of documents to be shown in the control. Use search to find the documents. See the example below. Don't forget to save the selection (Save button at the bottom).

.. image:: controlled-documents-viewer-select-dolcuments.png

The Columns tab
-----------------
Use this tab to decide which columns to display for the list.

.. image:: controlled-documents-viewer-columns-new2.png

Just select the columns to display. The options to the far right can be used to set an exact width for the column.

Some of these columns are system fields, other are property fields defined for this Document Management installation. 

The Filters tab
-------------------
On this tab you set filters to show in the viewer:

.. image:: controlled-documents-viewer-filters-new2.png

+ **Location**: Select where to place the filters: Top, Left or Right.
+ **No Of Columns Per Row**: Default settings is 3 columns per row. Set a different value if needed.
+ **Run query on no filter selection**: If this option is selected, all documents available as per the settings on the Query tab will be shown in the list. If this option is not selected, the list will be empty until the user makes a search.
+ **Filter**: Select the filter(s) to be shown, if any. Then select Type for each filter. 

The Refiners tab
-------------------
This tab is used to set property fields to use as refiners.

.. image:: controlled-documents-viewer-refiners-new3.png

+ **Result Limit**: Here you can set the number of documents that should be displayed in the list.
+ **Location**: Select where the refiners should be placed: left, right, top.
+ **No Of Columns Per Row**: Set the number of refiners that should be displayed per row.
+ **Refiner**: Select the refiners to be used here and set limit and order ny to the right for each refiner.

The Design tab
---------------
Here you can set the width for the left and right zone and select colors, if needed.

.. image:: controlled-documents-viewer-design-new2.png

