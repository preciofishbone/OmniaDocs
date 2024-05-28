Setup Place Holders in Word and Excel
=========================================

A document property place holder starts with [[ and ends with ]] and can be placed anywhere inside a DOCX document or within the header/footer of an XLSX document. Place holders support any document property. 

**Important Note!** In a template you probably want the published copy of the template to include the placeholders. To ensure that the placeholders are not replaced by document properties on the template, you need to escape the placeholders using the character “\\”. An escaped placeholder would look like this:

\\[\\[_PubDate\\]\\]

Another, and most likely better, way is to use a dedicated Document Type for all templates and there set that the placeholders should not be replaced for documents of that type. In that case, place holders can be added as described below - escape characters are not needed. See the heading "The Publish tab" on this page: :doc:`Document Types </document-management/administrator/document-types/index>` for more information.

Make sure to use the internal name (or the short name) of the property, example:

[[ODMPublished]]

You can use the following short names for built-in properties in ODM:

- _DocId: Document Id including prefix.
- _DocIdN: Document Id number only.
- _Edition: Edition.
- _PubDate: Published Date.
- _Comment: Edition Comment.
- _DocType: Document Type.
- _ApprDate: Approved.
- _ApprBy: Approved By.
- _Lang: Content Language:
- _RevDate: Review Date.

There's also a special Place Holder if you need to show Document History somewhere in a Microsoft Word document (note, this place holders works in Word only):

[[_DocHistory]]

On publication this Place Holder will be replaced with a table listing all editions, for example:

.. image:: place-holder.png

If you want dates to be displayed with the appropriate format you can use the following syntax for date and date including time:

[[_PubDate|Date]]

[[_PubDate]]

**Tip:** If you want to prevent authors from deleting place holders within the document (for example in a header), you can put them inside locked content controls added using the “Developer” tab in Word.



