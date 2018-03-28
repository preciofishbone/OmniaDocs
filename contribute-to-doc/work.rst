Work with the documentation
===========================

To work with the source code locally using Sphinx, follow the steps below 

1. Open a command prompt and navigate to the folder containing the source code for the documentation
2. Execute the following command
 
 .. code-block:: powershell
	
	    make livehtml

 After a while the console window will settle down, and you will find a link in the window, like this **Serving on http://127.0.0.1:8000**

3. In a web browser, enter the link from above. A locally rendered version of the documentation will be displayed.

Now, any time you add a file, or edit an existing file and then save it, Sphinx will rebuild the documentation locally and reload the browser window to display the latest changes.

You do edits, additions and deletes by just working with the files in the source code folder in your favorite text editor.

.. note:: The documentation is written with **reStructuredText**. To learn more about this markup language, you can use this link http://sphinx-doc.org/rest.html#rst-primer

To stop Sphinx, press **Ctrl + C** in the command prompt and then select **Y**