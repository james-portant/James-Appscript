---
description: >-
  How to combine multiple sheets into one data merge using IMPORTRANGE or
  ARRAYFORMULA functions
---

# How to source data from multiple Sheets

Sometimes you might need to pull data from multiple Google Sheet tabs or multiple Google Sheets files. This guide will show you how to set up a Google Sheet tab that will work with Portant and combine information from multiple Sheets into the same Google Sheet tab.

**In this article, you’ll learn how to:**

1. Set up a Google Sheet Source that combines data from multiple sheets/tabs
2. Add formulae to sheets that don't display an error when blank
3. Use an alternative like [Coefficient](https://coefficient.io/?via=james) that’s much simpler than formula combination to sync live data from multiple sheets (and keep your datasets live, on refresh straight from the source)

#### Set up a Google Sheet Source that combines data from multiple sheets/tabs

To set up a workflow that uses data from 2 or more different sheets, you need to combine all the data into one Google Sheet tab. This could be a new tab in an existing spreadsheet, or you could make a new spreadsheet to combine all the data into.

You can import data from other spreadsheets using the **ImportRange** formula, you can use this formula to import single cells or ranges:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6188eb97b9d0ecd0fec05aee_Screen%20Shot%202021-11-08%20at%208.19.07%20pm.png" alt="an example of the Import Range Google Sheets formula"><figcaption></figcaption></figure>

* To import cells A1 sheet 1 of the abcd123abcd123 spreadsheet, you enter: **=IMPORTRANGE("https://docs.google.com/spreadsheets/d/abcd123abcd123", "sheet1!A1")**&#x200D;
* To import cells A1 through C10 from sheet 1 of the abcd123abcd123 spreadsheet, you enter: **=IMPORTRANGE("https://docs.google.com/spreadsheets/d/abcd123abcd123", "sheet1!A1:C10")**

The first time you connect to a sheet, you may need to allow access, you only need to do this once per spreadsheet, and then all other formulas referencing this sheet will work.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6188eb38ccf1bc95424166cc_Screen%20Shot%202021-11-08%20at%208.16.26%20pm.png" alt="An example of the Allowing Access to a sheet"><figcaption></figcaption></figure>

\
You can also import data from the same spreadsheet using the **Array Formula** formula, you can use this formula to import ranges of cells from other tabs:

* To import cells from columns A through to C from sheet 1 into another tab in the same spreadsheet (for all rows), you enter: **=ARRAYFORMULA("sheet1!A:C")**

After you have combined all the data into one spreadsheet using the =ImportRange() or =ArrayFormula() functions, you are ready to connect the spreadsheet to Portant.

#### How to add formula to sheets (which don't display an error when blank)

Sometimes you may need to copy a formula on multiple rows for future data to be entered. When you copy the formula, the blank rows can sometimes display an error or a zero, which can interfere with Portant. To avoid these errors, you can use the following formulae.

To avoid errors, you can use the **IFERROR** **formula**:\
&#xNAN;**=IFERROR("no error", "error")**\
Returns the first argument if it is not an error value, otherwise returns the second argument if present, or a blank if the second argument is absent e.g. **=IFERROR(A2\*100, "")**

To avoid zeros, you can use the IF formula:\
&#xNAN;**=IF(logical\_expression, value\_if\_true, value\_if\_false)**\
Returns one value if a logical expression is 'TRUE' and another if it is 'FALSE' e.g. =**IF(A1="","",A1\*100))**

You can also combine these formulas for a Full-Proof way of preventing Errors or "0" values.\
&#xNAN;**=IFERROR((IF(A1="","",A1\*100)),"")**

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6188eeb72ccdfe01d062e52d_Screen%20Shot%202021-11-08%20at%208.30.38%20pm.png" alt=""><figcaption></figcaption></figure>

#### Use Coefficient to Sync Live Data From Multiple Sheets & Sources

Coefficient makes linking multiple Google Sheets data a lot easier, more straightforward, and automatic.

With Coefficient, you can choose your Google Sheets data source file, add filters to refine the information you want to pull in, and import the data with a few clicks, and use GPT Copilot to write formulas or build pivots and charts – all from within one easy-to-use Google Sheets extension.

Updating your linked spreadsheets is also a breeze since Coefficient lets you configure auto-refresh schedules. Not only do these auto-refresh schedules allow you to keep your Google Sheets synchronized, but they also allow you to power each sheet with live data directly from your source (and keep it on refresh), whether it’s your CRM, accounting platform, and more.

All of this means – no more manual updates when your data changes or gets new information.\
\
Here’s a quick 2-minute video walkthrough of the process.\


{% embed url="https://www.youtube.com/watch?t=118s&v=Nq1IN5D3vdk" %}

We’ll walk through a similar example below, with images and step-by-step details.&#x20;

**Importing Data from Another Google Sheet with Coefficient**

Let’s go over how Coefficient can help you combine multiple spreadsheets into one using an easier and more streamlined process.

You can [get started with Coefficient by submitting your email here](https://coefficient.io/get-started?via=james).

Once you have Coefficient installed, click Import Data on the Coefficient pane.

<figure><img src="https://lh7-us.googleusercontent.com/l825hyJX2OYQQHmhse3d-a7Pk4OqKCPcB1VAvQIqluIj3VK368wZlOFMPRlkvr8QJRN9uod_Bgr9whED0WrgTS52t3JEGIuK6drmLbohyBoZ7nbgnAol1gHTcEAxGF_YKfbbM7QBI3VorbmdWrtNjVE" alt=""><figcaption></figcaption></figure>

Then, select Google Sheet.

<figure><img src="https://lh7-us.googleusercontent.com/85x8VgvfXzzTV6UqK_M-04quL-mRYDiCs7WZEdfBsL8jHMw2meqAG38whG3gaxuCbwH-5_fSdmbKnb7umtWJDE-HISY-iCcc0GnUKW39LxIPeooilXBYCF0Dp4sv1djVM0jplqLcbKm2kM6S4L42_zI" alt=""><figcaption></figcaption></figure>

Choose any Google Sheet you want from your Google Drive or other documents you have shared access to.

For this example, let’s pull up the same User Subscriptions list we used in the previous steps and click Select.

<figure><img src="https://lh7-us.googleusercontent.com/_KDxUepIIk5fsUTupF0BvVxIf7eciW1k3xDJmW9lXsZZhtVoET2fh_vv-8G-OoG0C_Dr_iT_CPrr7Xh2dSQBBHS-y0eUiH1MnB92tGZRSSGuFQi9742D9A061qyB-vMflPiGIOsCdHOHz1571stZBPc" alt=""><figcaption></figcaption></figure>

Coefficient takes a few seconds to access the data and read the column information. You’ll then see an import panel and the option to filter the data as it comes in.

<figure><img src="https://lh7-us.googleusercontent.com/rv2PJn5AyrFgKfdiKyOXsJ2P4dJFGSq-DntgCXDfxW7ThfcI01Tez-xyLFm-WJf1_vJmL3CgsnPV2VzMIniAbiVva6DcP74EWZMosUUKlIePATMisrm5U1lWdW8aAlEZivrVFyn5N5R3J33U6QoxLzA" alt=""><figcaption></figcaption></figure>

Once you’re done, click Import.

There you have it. Coefficient imports your data almost instantly, and you don’t even need to deal with functions and formulas throughout the entire process.

So maybe now you’re wondering, “How can I get Google Sheets to auto-update a reference to another sheet?”

Coefficient has you covered since you can automatically refresh that data on a schedule, so you won’t need to do it manually.

<figure><img src="https://lh7-us.googleusercontent.com/z4q-igW6T4UpDuTF0jyRZW9gHcMBV3Jr6UtLGHl65fLRUwPIpUOWlm3rd19TZij6cgaz_0u1no5clGVIXqB7TmqrpU0a7_ELakiDHPUGuMlUavQUD5-a4IMGaSatxm0N_tAzYkFPxKxKRQIYds6Uv5M" alt=""><figcaption></figcaption></figure>

The IMPORTRANGE solution allows you to import entire columns at once, but you’ll need to specify bounds for it or it will disrupt your dataset if your data moves too much.

Also, IMPORTRANGE doesn’t offer a built-in way to filter data, so you’ll need to do this separately.

Coefficient takes care of both problems for you by building the filter into the import, including importing any populated rows or columns seamlessly.

If you’re looking to build reports based upon the multiple tabs of data you’ve pulled into one sheet, you can take advantage of GPT Copilot in Coefficient, which can build formulas, pivots, and charts for you. Here’s an example of turning simple text instructions into formulas.

<figure><img src="https://lh7-us.googleusercontent.com/DbyVarLtiqLIrQPEY3rM3Ral9oNWQ6woj0XLH6ia_fEFqY8eeDVVdDtTdYFFEuLOUWVMV9qdskRF2e5FsCqGHX923UyUNuC2BG46H_Ax-ot_1I4Bqsvc06bzgouRuXhkGIwSOP6hn9gOy7XGGP0mbAU" alt="" width="375"><figcaption></figcaption></figure>

Formula Builder will return a formula like below.

<figure><img src="https://lh7-us.googleusercontent.com/61SwS21COYLtja1iJWq8BOve8T10JquEa4WDNu8ExVyK8aIBI48IVTHS8yB_U4sTA0pWySxkkXRs_M1l6LEwc4yAxnuIWhNoCQxTTm5AUV6CAXpSiA44IFA992niBOblt4QcrWCwFxSMs_qdwYKvxe0" alt=""><figcaption></figcaption></figure>

And just like that, you’ve blended data from multiple sources and analyzed it, all without ever leaving Google Sheets!

#### Feedback and feature suggestions

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\
