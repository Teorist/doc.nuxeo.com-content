---
title: Collections
review:
    comment: ''
    date: '2018-10-15'
    status: ok
toc: true
tree_item_index: 500
description: Web UI user documentation about Collections
labels:

---
{{! multiexcerpt name='definition-collection'}}

Collections are a folder-like document in which you can classify existing documents. Documents are not actually copied or moved into the collection, which only holds a link to the document in its original location.

It enables you to create your own organization of the content without duplicating content and having the size of the content growing uncontrollably.

{{! /multiexcerpt}}

{{! multiexcerpt name='functional-introduction-web-ui'}}
The list of collections available to you is available from the side menu, in the **Collections** tab.

![]({{file name='collections-tab-web-ui.png'}} ?w=250,border=true)

Click on the collection title to go on the collection and see the list of the documents that are classified in it.

![]({{file name='collections-tab-opened-web-ui.png'}} ?w=600,border=true)

Click on a document to consult it. The main view shows the document. The unfolded side panel shows the content of the collection. You can click on the icon&nbsp;![]({{file name='back-icon-web-ui.png' page='icons-index'}}) to see the collections list.

![]({{file name='collections-content-expanded-web-ui.png'}} ?w=600,border=true)
{{! /multiexcerpt}}

## Collecting Documents
{{! multiexcerpt name='collecting-rights'}}
You can classify any type of document in a collection. You just need to have Read access to the document to be able to collect it. Collecting a document doesn't give you more permissions on the document: your permissions are the one defined on the original parent of the document.
{{! /multiexcerpt}}

{{! multiexcerpt name='collecting-web-ui'}}
Documents can be collected:

- Individually by clicking on the icon&nbsp;![]({{file name='add-to-collection-web-ui.png' page='icons-index' space='userdoc'}} ?w=16) of the document
  ![]({{file name='add-to-collection-web-ui.png'}} ?w=250,border=true)
- By batch by selecting documents from a list of documents and clicking on the icon&nbsp;![]({{file name='add-to-collection-web-ui.png' page='icons-index' space='userdoc'}}) in the selection header.

In both cases you can select the collection by:
- Browsing the collections in the list
- Starting to type the collection name and select it
- Typing a new collection name to create it

The list of collections the document is available from is displayed on its **View** tab.
![]({{file name='collections-doc-widget_web-ui.png'}} ?w=300,border=true)
{{! /multiexcerpt}}

## Creating Collections
{{! multiexcerpt name='collections-containment-rule'}}
Collections can be created in workspaces and folders.
{{! /multiexcerpt}}

{{! multiexcerpt name='creating-web-ui'}}
There are two ways to create a collection:
- Like any other document, using the button&nbsp;![]({{file name='create_button.png' space='nxdoc' page='web-ui-overview'}} ?w=30): Just fill in the creation form and the collection is created in the current workspace / folder.
  ![]({{file name='new-collection-web-ui.png'}} ?w=400,border=true)
- Directly from the **Add to collection** popup: collections about to be created are displayed with the icon ![]({{file name='add-icon_web-ui.png' page='icons-index'}} ?w=20), while existing collections are displayed in the drop down list. The collection is created in your personal workspaces, in a **My Collections** folder.
{{! /multiexcerpt}}

## Sharing Collections

{{{multiexcerpt 'sharing' page='userdoc/collections'}}}

## Removing Documents from Collections
{{! multiexcerpt name='removing-web-ui'}}
To remove a document from a collection click on the icon ![]({{file name='delete.png' page='icons-index'}}) of the collection from the document view.

![]({{file name='collections-doc-widget_web-ui.png'}} ?w=300,border=true)

To remove several documents from a collection:
1. Go to the **Collections** tab in your side menu.
2. Click on the collection name that you want to manage.
3. Select the documents to remove using the checkboxes.
4. In the selection header, click on the Remove from collection icon&nbsp;![]({{file name='delete-circle-icon_web-ui.png' page='icons-index'}}).

![]({{file name='remove-from-collection-web-ui.png'}} ?w=600,border=true)

In both ways documents are immediately removed from the collection.
{{! /multiexcerpt}}
* * *

<div class="row" data-equalizer data-equalize-on="medium"><div class="column medium-6">{{#> panel heading='Related Documentation'}}

- [Collections developer documentation]({{page space='nxdoc' page='collections'}})
- [Collections in JSF UI]({{page version='' space='userdoc' page='collections'}})

{{/panel}}</div><div class="column medium-6">

&nbsp;

</div></div>
