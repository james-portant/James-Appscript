---
description: >-
  How to automatically create a document every time a new row is added to your
  spreadsheet (or a row has changed)
---

# Google Sheets Auto-create

> **Note** - this is a **✨ Pro feature** only avalaible on paid Portant Subscriptions

You can use Auto-create in Google Sheets source workflows to create automated workflows. These workflows can be triggered when a new row is added, or when data in a row is changed. In this guide we will show you how to:

1. Turn on Auto-create
2. How often does Auto-create run?
3. Auto-create when data in a row changes&#x20;
4. Auto-create when a specific value changes e.g. Status

#### Turn on Auto-create

When you have created a workflow with Google Sheets as the source, you can turn on Auto-create in the top right corner. When you turn on Auto-create you will see the following options:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64928fc316eed3fa15bdf5f5_Auto-create%20Sheets.png" alt=""><figcaption></figcaption></figure>

When you tun on Auto-create an Auto-create status will always be displayed in the top right corner here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6492905c24f87f95922c6771_Auto-create%20Sheets%20%E2%80%93%201.png" alt=""><figcaption><p>If you can't see this status, Auto-create is not on.</p></figcaption></figure>

When Auto create is turned on, it will process any new rows of data added to the bottom of the spreadsheet table from the point in time it is turned on.

> Note: Auto-create does not process any rows of data already stored in the spreadsheet. Only new rows of data added to the bottom of the spreadsheet will be processed

#### **How Auto-create works**

When Auto-create is turned on, Portant counts how many rows of data are in the spreadsheet. Then when Auto-create is ON, and a row of data is added after the last row, it will be processed by the workflow automatically.

If you want to have a spreadsheet with a formula in one of the columns, we recommend wrapping the formula in an IF Statement, to display nothing if there is nothing in the row, like this:\
&#xNAN;**=IF(A17="","",(\*\***_**Your Formula**_**\*\*))**

**‍**\
If you don't do this, then Portant will only process rows added below the the last row with a formula in it. For example:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6493a47b801c0b39bd7c8256_Auto-create%20Sheets%20%E2%80%93%203.png" alt=""><figcaption></figcaption></figure>

####

#### Auto-create when row data changes

Sometimes you might want to run auto-create when data in a row changes. Portant takes a snapshot of the data in your spreadsheet at the time this feature is turned on. Then whenever a change in the data is detected, Auto-create will process the row with the changed data. To turn on this feature, you can select the check box in the Automation panel here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64929c1bc475e74ad6e4146c_Auto-create%20Sheets%20%E2%80%93%202.png" alt=""><figcaption></figcaption></figure>

#### Auto-create when a specific value changes e.g. Status&#x20;

You can combine this feature with a [workflow filter](https://www.portant.co/guide-article/how-to-use-workflow-filters) that enables you to only process rows when a status is true. For example, you could have a status in a Spreadsheet that is either '**Draft**' or '**Send**'. Then when you want to process the row of data, you change the status to '**Send**' like this:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6493a62b1f2a4fa8cc82c028_Auto-create%20Sheets%20%E2%80%93%204.png" alt=""><figcaption></figcaption></figure>

To build this, you would turn on Auto-create when a specific value changes and then add a [workflow filter](../../automation/workflow-filters.md) to only process data when the '**Status**' is '**Send**'

> This can also be a great solution to prevent partially completed rows to be processes by Auto-create.

#### Feedback and feature suggestions

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)
