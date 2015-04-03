---
title: Drag and Drop Upload
page_title: Drag and Drop Upload | UI for ASP.NET AJAX Documentation
description: Drag and Drop Upload
slug: asyncupload/functionality/drag-and-drop-upload
tags: drag,and,drop,upload
published: True
position: 2
---

# Drag and Drop Upload



## RadAsyncUpload Drag and Drop

Starting from Q3 2011 __RadAsyncUpload__ provides a new drag and drop functionality for uploading files. The new functionality allows the user to drag a file directly on the__RadAsyncUpload__ control without the use of file dialog. Upon file dropping the upload will start automatically. When the dragged file is positioned over the__RadAsyncUpload__ a drop area appears indicating where to drop the file.![Drag and Drop Upload](images/asyncupload-draganddropupload.png)

From Q3 2012 SP1 this message can be easily localized by using __Localization-DropZone__ property of RadAsyncUpload.

>note The new functionality relies on the HTML5 FileApi and Drag-And-Drop modules and therefore is available only in browsers which support the aforementioned modules.
>As for now such browsers are:
>
* Mozilla Firefox v. 4+
* Google Chrome
* Safari v. 5+
* Internet Explorer 10>


You will need to prevent the default behavior of the browser when the file is not dropped over the__RadAsyncUpload__. More information about the Native HMTL5 Drag and Drop could be found[here](http://www.html5rocks.com/en/tutorials/dnd/basics/).

## DropZones Property

As of Q3 2012 __RadAsyncUpload__ supports the DropZones property. By setting the __DropZones__(which are CSS selectors) the user can upload files by dropping them on different areas of the page.

>note Keep in mind that the drop zones should be listed with comma separator as demonstrated in the[demo here](http://demos.telerik.com/aspnet-ajax/asyncupload/examples/draganddrop/defaultcs.aspx)and the following code __<telerik:RadAsyncUpload runat="server" ID="RadAsyncUpload1" MultipleFileSelection="Automatic" DropZones=".DropZone1,#DropZone2"/>__ 
>


# See Also

 * [Drag and Drop Demo](http://demos.telerik.com/aspnet-ajax/asyncupload/examples/draganddrop/defaultcs.aspx?product=asyncupload)