---
description: A guide on how to customise the Data Merge settings for a Google Sheets source
---

# Data Merge Settings for Google Sheets sources

After you have customised the format of your document and added your tags, the next thing to do is set-up your Data Merge Settings. This is where you can edit how the Data Merge Automation will run and filter the data Portant will use to make the outputs.

**In this article you’ll learn how to:**

1. Choose the type of Data Merge
2. Filter the data used for the Data Merge
3. Other options for Google Sheets Data Merge

#### Choosing the type of Data Merge

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60f7d90aec04febf69ee5a07_Screen%20Shot%202021-07-21%20at%206.21.16%20pm.png" alt=""><figcaption></figcaption></figure>

There are two different types of Data Merge possible with Google Sheets. These are:

* **Create multiple documents** - This setting creates seperate documents from each row/response/card
* **Combine into one document** - This setting combines multiple rows of data into one document (only works with Sheets)

#### Filter the data used for the Data Merge

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60f7d985de0f6ffd83e3fa3c_Screen%20Shot%202021-07-21%20at%206.20.09%20pm.png" alt=""><figcaption></figcaption></figure>

This is how you filter what data from your spreadsheet you would like to make documents with. There are a few different options you can use:

* **All rows** - this creates documents for all rows within the spreadsheet (apart from the header row)
* **Latest rows** - Portant merges all the data added to the spreadsheet since the last time an automation was run
* **Custom rows** - select a bespoke range of rows to make documents from
* **A single row** - select a single row to make a document from
* **Condition** - enter a condition that has to be true for Portant to merge the data (e.g. Column A **is equal to** "Yes")

#### Other options for Google Sheets Data Merge

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60f7f4793a070594060260c1_Screen%20Shot%202021-07-21%20at%208.17.09%20pm.png" alt=""><figcaption></figcaption></figure>

If you open the options menu in the top right hand corner of the Data Merge box you will find additional options for the data merge. These are:

**Auto-create**

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60a22678c98ebefabac514c5_Screen%20Shot%202021-05-17%20at%206.15.51%20pm.png" alt=""><figcaption></figcaption></figure>

Portant will periodically check the source file every hour or day. When new data is found in the source Google Sheet, a new document is created.

**Document Links**

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60fa06f3abbc0f69cbef0d45_Screen%20Shot%202021-07-23%20at%2010.01.36%20am.png" alt=""><figcaption></figcaption></figure>

When selected, Portant will automatically insert document (and pdf) URLs next to the last column of your spreadsheet. like this:

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60fa079a2d484d10467e02a5_Screen%20Shot%202021-07-23%20at%2010.04.29%20am.png" alt=""><figcaption></figcaption></figure>

‍

**Data Grouping**

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60e53259c96f3f012945434a_ezgif.com-gif-maker.gif" alt=""><figcaption></figcaption></figure>

‍**‍**Portant will add extra rows to tables containing template tags to capture all grouped rows in your spreadsheet. Learn more

> **Note** - These additional options are only available in 'Create multiple documents mode'

#### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\


Thanks,\


Blake and James
