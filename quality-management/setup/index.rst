Setup Quality Management
==================================

Prerequisites
---------------------------------------------------------
**Note!** In order to be able to run any Quality Management features, the extension Omnia.QMS needs to be installed.

Set up Term Sets
----------------------------------
1. Go to SharePoint Admin Center > Term Store.
#. Copy the Term Store Id to Notepad for later use.
#. Navigate to the built-in Keywords term set located under System.
 .. image:: qm-setuptermsets.png
4. Copy the Keywords term set id to Notepad for later use.
#. If you already have a term set for Document Types setup, go to step 7.
#. Create a new term set for Document Types.
 .. image:: qm-doctypetermsets.png
7. Copy the Document Types term set id to Notepad for later use.
#. Go to Omnia Admin > System Extensions.
#. Click on Omnia.QMS and set the values:
 - term store id
 - term set id for document type
 - term set id for tags and search tags
 
Core Feature
----------------------------------
1. Go to Omnia Admin > Features.
#. Activate the tenant feature “Omnia QMS Core”.

.. toctree::
   :titlesonly:

   setup-processdirectory/index
   setup-processauthoring/index


Associate a SharePoint Task list to a Process library
--------------------------------------------------------
It is possible to associate a SharePoint Task list to the Process library. If a Task list is associated, actions in issues will become SharePoint tasks.
 
1. Activate the Core Feature (see below).
2. Create the Process Library.
3. Click "Edit".
4. Click the settings icon.

.. image:: associate-tasks-list-click-settings.png

5. Select "Tasks" for "Task List".

.. image:: associate-tasks-list-settings-tasks.png

6. Save.

