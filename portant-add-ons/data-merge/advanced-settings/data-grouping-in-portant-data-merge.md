---
description: How and when to use data grouping into your template document.
---

# Data Grouping in Portant Data Merge

Portant Data Merge can group data within your source spreadsheet and place it into tables within your document. If your source spreadsheet contains multiple rows that should be grouped and inserted into one table then this is the feature for you. A good example use case is when you need to include multiple Google Sheet rows into an[ _invoice_ template](https://www.portant.co/google-sheets-invoice-template) or _purchase order._

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60e53259c96f3f012945434a_ezgif.com-gif-maker.gif" alt=""><figcaption></figcaption></figure>

If you need to use this feature your source spreadsheet will normally have rows which are grouped together like the example below.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60e5330240d2f95a93cc23e3_Screen%20Shot%202021-07-07%20at%202.51.12%20pm.png" alt=""><figcaption></figcaption></figure>

‍

You can easily place a table into a document in a few easy steps:

**Step 1**

Add a table into the document (Insert > Table).

> Note | You can also apply data grouping when using Google Slides as a template within your workflows.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60e543a4bf58a06c0cff6065_Document%20Table%20-%20Insert%20Table%20(2).gif" alt=""><figcaption></figcaption></figure>

> Optional: You can add header and footer rows to the top and bottom rows of the table and format as appropriate. The additional rows will only be placed immediately after the row with tags.

**Step 2**

Then add the tags into the table. These are the tags of the data that will have multiple lines per document. Please ensure the tags are only added on one row.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60e543c9a7cea90a41ae29bf_Document%20Table%20-%20Insert%20Tag%20(2).gif" alt=""><figcaption></figcaption></figure>

**Step 3**

After you have inserted the tags you need to set the table grouping (Data merge Options > Data grouping). Then select the column the table data will be grouped by. This column needs to be unique (e.g. no columns which are named _Invoice Number_ and _Invoice No._ with the same data in the column.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60e543dce989500d967a4559_Document%20Table%20-%20Set%20Grouping%20Column%20(2).gif" alt=""><figcaption></figcaption></figure>

**Step 4**

In the example above we have grouped by invoice number because we want to create a separate document for each unique invoice number as shown in the source spreadsheet below.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60e5330240d2f95a93cc23e3_Screen%20Shot%202021-07-07%20at%202.51.12%20pm.png" alt=""><figcaption></figcaption></figure>

‍

After you have set up the grouping and other document settings (e.g. Document name, pdf or email etc) you can click the Create Documents button, and _voila!_, invoice will be made including tables with multiple lines from the spreadsheet source!\
‍

> Note: You can only use data grouping in "Create multiple documents" mode. Ensure this is selected in the Data Merge box.

‍\


### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\


Thanks,\


Blake and James
