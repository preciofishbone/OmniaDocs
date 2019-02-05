Process Library
===========================

The Process library is where members of the team site creates new processes and edit existing ones, and where processes are published so others can see them. 

.. image:: process-library-overall-new2-border.png

A published process is made available through a Process Viewer, see :doc:`Process Viewer </quality-management/end-user/process-viewer/index>`

Published processes can also be made available through a Process Directory, see :doc:`Process Directory </quality-management/end-user/process-directory/index>`

All processes
*************
The main list (see image above) displays a list of all processes in this process library. Click any process for details or to start editing the process.

You can click the headings "Name", "Edition", "Revision", "Modified" and "Owner" to switch between ascending and descending sort order.

Use the following options to filter the list and more:

+ **Search**: Filter the list by process names. All processes that contain the letters you have entered, somewhere in the process name, are shown.
+ **Owner**: Filter the list on an owners name.
+ **Tags**: Filter the list on one or more of the available tags.

Note that these filters are cumulative. An example: if you filter on a process name and a tag, a process must contain the letters in the name AND be tagged with the tag you have chosen, to be shown in the list.

+ **Clear**: Use this button the clear filters and show the full list.
+ **New**: Create a new process by using this button. See below for more information.
+ **Archived processes**: To see the list of archived processes, click this link. See below for more information.

Navigate between processes
*****************************
When you have selected a process you can go back to the main list by selecting "All processes" in the upper left corner and you can go to another process by selecting it in the list to the left. Here's an example:

.. image:: process-library-navigating-new-border.png

Create a new process
**********************
To create a new process:

1. Go to the Processes library and click "New".

The following is shown:

.. image:: create-new-process-new.png

2. Enter a name for the process.
3. Add or delete owners if needed.
4. Choose if you are going to use the shapes from the Omnia QMS library or a custom image.

If you choose to use a custom image, browse for the image and select it using the Omnia Image Browser.

5. Click "Create".

Important note on custom images
-------------------------------
A custom process image with image maps will have a draft status and a published status. The images are stored in the local team site, not in a global image bank (but can be uploaded to the process from any source available).

When editing a process, a new image can be uploaded to replace the existing custom image. The image maps will remain in place, but can of course be edited.

When a custom image is replaced, you always need to  publish to make the changes visible for end users.

Archived processes
*******************
A process that no longer is used can be archived, so it's not shown in the main list. Use the "Archive" button when editing the process.

**Note!** An archived process can not be published. A published process is automatically unpublished when you select to archive the process.

.. image:: archive-button-new-border.png

A list of archived processes can be reached by clicking the link "Archived processes" in the main list, see above.

Here's an example of a list of archived processes:

.. image:: archived-processes-new-border.png

You can search the list and sort it by using the headings. A process can be restored by clicking the icon to the far right, and thus be available in the main list for editing and publishing.

.. image:: restore-archived-new-border.png

Edit a process
****************
You edit a newly created process and an existing one the same way. Note that access mode is read only until you click "Edit". 

1. Open the process from the list, if it's not already open.
2. Click "Edit".

.. image:: edit-process-1-evennewer-border.png

The Graph tab
--------------
Use this tab to work with the graphical presentation.

To add a new process step, do the following:

1. Click "Add process step"

.. image:: add-process-step-graph-new.png

or "Add new process step" - the plus - in any step where you want to create a new step.

.. image:: add-new-step-new-1.png

The following is shown (some options may not be shown, depending on where in the process you add something):

.. image:: add-process-step-new-2.png

+ **Type**: Type can be Process or Activity. When you select "Process", a second list, where you can choose to create a new Process, a Sub Process, or a Linked Process, is shown. 

.. image:: add-process-step-subprocess-new.png

"Activity" is the end of the process or sub process, where you add actions. For an Activity you select which shape to use. When you select "Linked process" you add the link to that process.

+ **Name**: Enter a name for the step here.
+ **Shape**: Select shape for the process step here. For a "Sub Process" you can choose to use to use Shapes or a Custom image. A sub process can have other sub processes, activities or links to other processes.
+ **Position**: Select position for the new step, in relation to the step where you selected to create the new step - After, Before or Parallell.

You can reorder the process graph if needed. Select the menu to the right:

.. image:: select-reorder-new2.png

Choose what you want to do:

.. image:: reorder-options-new.png

Creating a clickable link to a process
---------------------------------------
Here’s how to add clickable areas (image maps) to a custom image you have uploaded.

1. Make sure everything you may want to link to is present in the lilst. If not, use ADD PROCESS STEP and ADD CUSTOM LINK to create Process Steps or links.

.. image:: clickable-step-1.png

2.	Edit the process.
3.	Open the list and select what you want to link to.

.. image:: clickable-link-open-list.png

4. Select the shape for the clickable area.

.. image:: clickable-shape-border.png
 
5.	Draw the area in the right place in the graph.

.. image:: clickable-added.png

6. Adjust width and height for the area. (Point at an edge, and you can grab and draw that edge.)
7.	Click "Save".

.. image:: clickable-save.png
 
If you have placed an area for a clickable link in the wrong place, just drag the area to the right place. 

To delete a clickable are, select it and click the dust bin.

.. image:: clickable-dustbin.png

The General tab
------------------
On this tab you can set the following:

.. image:: process-library-general-new.png

+ **Name**: Edit the Process Name here if needed.
+ **Owner**: Edit process owner(s) here if needed. Note that process owners is separate from site owners. 
+ **Graph type**: You can change from using Shapes to Custom image, or vice versa.

The Content tab
-----------------
Here you add/edit the description for the process. Note the format options. You can also insert images, links and tables.

.. image:: process-library-content-new.png

The Related Documents tab
--------------------------
If Omnia Document Managament is installed in the current tenant, editors of controlled documents can relate a published document to a process. It's then up to the Process Owner to decide to make the document available at the process in the Process viewer, or not. Another way of doing this is that Process Authors can relate published controlled documents to the process.

Any related document is listed on this tab. To relate a new document, click the button.

.. image:: process-library-documents-new.png

Use this dialog to find and select documents:

.. image:: process-library-documents-list-new.png

The Tools tab
-----------------
Use this tab to link to documents. You can also link to pretty much everything, for example pages, bya adding custom links. In i long tools list, you can add headings for separate sections, to make it easier for user to navigate.

.. image:: process-library-tools-new.png

Do the following to link to a document:

1. Select "ADD TOOL".

.. image:: process-library-tools-add-tool.png

2. Select "Document" from the list.
3. Click "Browse".

The list of documents, if any, is shown. If the document isn't uploaded to the team site:

4. Click "Upload Document" and upload the document you want to add to Tools, if needed, and then select the document.
5. Select the document and click "OK".

.. image:: select-document-ok.png

6. As the last step, click "Save" to add the document to the tools list.

.. image:: tools-document-click-save.png

To add a link to anything (for example a page in Omnia, or an internet page) you can reach through a link, select "Custom link" and add the Url, A Title (name for the link), and select to open the link in new window or not, and click "Save".

.. image:: process-library-tool-custom-new.png

To add headings, if nedded, select "Heading, type the heading in the field, and click "Save".

.. image:: process-library-heading-new.png

To edit or delete a tool, click the icon for the tool.

.. image:: process-library-tools-delete-new.png

If you would like the tools to be shown in another order, just use drag and drop.

Don't forget to save before you go on to another tab.

The Advanced tab
-------------------
On this tab you can set the following:

.. image:: process-library-advanced-border.png

+ **Tags**: Add tags for the process. This is a metadata list. You can select tags from the list, you can not create new tags here. The tags are important for search. (Available tags are set up centrally, see :doc:`Setup Quality Management </quality-management/setup-quality-management/index>`.)
+ **Show in Process Directory**: Decide if the process could be shown in a possible Process Directory or not (Default: Show).
+ **Process Site Template**: You can create a "Process Site Template" from this process. You can then create a new team site based on this process. Documents you link to and actions you add here will then be set up in the team site created from this template process.
+ **Review interval**: Set Review interval. When a published process is nearing it's reviewal time, it will be part of the revewial list in Omnia Admin. (See more information about Review below).
+ **Change comment**: Here you can add a comment about the latest changes for this process.

The Deviation/Improvement tab
------------------------------
If set up, users can send feedback to a process, via the link "Feedback" in the Process Viewer, and tag the posting as Improvement, Deviation or Risk. These feedback posts are shown and can be handled on this tab.

.. image:: deviation-tab-new.png

You can use the "New" button to add feedback here yourself.

More information is found here: :doc:`Deviations/Improvements </quality-management/author/deviations-improvements/index>`

Publish a process
******************
To publish the process, just click "Publish".

To be able to publish a process, you have to have the correct permission. If you don't have the permission, the Publish button is grey.

Review processes
-----------------
To see a list of processes that is nearing their review times, do the following:

1. Go to a site where a Process Library is installed.
2. Open Omnia Admin and select "Process Management" under "Site Collection".

.. image:: process-review-process-management.png

Then select "Reviews". Here's an example of a Review list:

.. image:: process-review-list.png

Use the fields at the top to filter the list. Use "Clear" to clear filtering and see the whole list. Use "Export" to export the list that is shown, to Excel.

Also note that you can click the headings to change between ascending and descending sorting.
