---
description: How to use Data Grouping with Webhooks
---

# Webhook Data Grouping

Portant Workflow can group data within your webhook payload and place it into tables within your document.  A good example use case is when you need to include multiple objects into an[ invoice template](https://www.portant.co/google-sheets-invoice-template), quote or purchase order, like this:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/60e53259c96f3f012945434a_ezgif.com-gif-maker.gif" alt=""><figcaption></figcaption></figure>

### Step 1

Ensure your webhook payload is set up correctly. Data grouping from webhooks is only valid for an array depth of one and arrays must be of objects.

#### Example payload

```json
{
    "city": "Vancouver",
    "csNo": "QZ2257",
    "narrative": "Test report for testing purposes. ",
    "siteName": "Wanda & Sons Snoopy Landing",
    "clearTime": 1720005608143,
    "onsiteTime": 1720005084713,
    "reportNumber": "R24-113100",
    "responseTime": 24.23,
    "rrAlarmDate": 1720003631000,
    "rrAlarmType": "BURGLARY",
    "siteAddress1": "Unit 36 - 1055 Albert Place",
    "siteAddress2": null,
    "rrInitialZone": 18,
    "rrConfirmedBurg": false,
    "rrConfirmedFire": false,
    "rrPoliceFileNo": [
        {
            "imageLink": "https://drive.usercontent.google.com/download?id=1Hv5r4MMu9_uDf-HyvZcckBRJ-xCRjOGL",
            "imageName": "image_one"
        },
        {
            "imageLink": "https://drive.usercontent.google.com/download?id=1LJhk_pdFtxsnnjyHN0u67kNuWxkYwcL_",
            "imageName": "image_two"
        },
        {
            "imageLink": "https://drive.usercontent.google.com/download?id=11spBeKnsr7oHPZTsJye5fwkJ8SCcQouV",
            "imageName": "image_three"
        }
    ],
    "rrPoliceAttended": false,
    "rrTechnicalIssue": false,
    "rrInitialZoneDesc": "SE Side Patio Door ( new edition room)",
    "rrTechnicalIssueDesc": null
}
```

### **Step 2**

Add or open the document block and insert a table into the document (Insert > Table).

Then add the tags to the table. These are the tags of the data that will have multiple lines per document. Please ensure the tags are only added to one row.

> **Note:** You can also apply data grouping when using Google Slides as a template within your workflows.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63e1e6f84ee37e6f0568ae46_Data%20Grouping%20-%202.png" alt=""><figcaption></figcaption></figure>

> **Optional:** You can add header and footer rows to the top and bottom rows of the table and format as appropriate. The additional rows will only be placed immediately after the row with tags.

‍

### **Step 3**

After you have set up the grouping and other document settings (e.g. Document name, pdf or email, etc) you can click the Create Documents button, and _voila!_ invoices will be made, including tables with multiple lines from the webhook source!

### Feedback and feature suggestions

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)
