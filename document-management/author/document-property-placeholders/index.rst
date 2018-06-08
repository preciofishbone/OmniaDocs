Document Property Placeholders
==============================

Template Documents can be created for any application really, but fields that will be populated with information during publication (Document Property Placeholders) can be used in Microsoft Word docx and Excel xlsx documents only. This page describes Microsoft Word Template Documents in detail. Excel document templates works in a similar way. Regarding other file types, you can use any document as a Template Document.

When creating a Microsoft Word or Excel Template Document you place field names in heading and footer, and in a Word template these fields can also be placed in the content – fields that will be populated with information when a document using the template is published.

+ Just place the field’s title, short name or code within double brackets where you want the information to appear.

In all other aspects you work with the document the normal way.

You can use all properties defined for the Document Profile(s) the template will be connected to. You can either use the Title, Short name or the Internal name for the property, but we recommend that you always use the Internal name or the Short name. The Title can be edited later on, but the Internal name can’t.

For the system fields you can use either the Title, Short name or the Code, but we recommend that you always use the Code or Short name here as well, for similar reasons.

The following systems fields are applicable for templates:

**Approved** Code: ODMApproved; Short name: _ApprDate; Comment: Date and time

**Approved by** Code: ODMApprovedBy; Short name; _ApprBy; Comment: Name of approver

**Document Id**	Code: ODMDocId; Short name; _DocId

**Document Id Number** Code: ODMDocIdNumber; Short name: _DocIdN
	
**Document type** Code: ODMDocumentType; Short name: _DocType

**Edition** Code: ODMEdition; Short name: _Edition	

**Edition Comment** Code: ODMEditionComment; Short name: _Comment

**Language** Code: ODMContentLanguage, Short name: _Lang		

**Published** Code: ODMPublished; Short name: _PubDate; Comment: Date and time

**Review date** Code: ODMReviewDate; Short name: _RevDate

**Tip!**
An author can normally edit everything in a template when creating a new Controlled Document, even the Document Property Placeholders. If you want to make sure that the placeholders are not altered, you can first insert a Content Control, add the field code to the control, and then lock the control.
