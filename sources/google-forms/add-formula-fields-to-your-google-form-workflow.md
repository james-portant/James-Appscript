---
description: How to use and add additional fields to a Google Form workflow
---

# Add formula fields to your Google Form workflow

Sometimes you might need to calculate a value conditionally insert other content based on form answers. e.g. If the users selects an office location, add the address, phone number and email address for the location WITHOUT having to ask the user to select these details as well.

The majority of the time, you can achieve this by using [Tag Formula](../../personalise-documents/tag-formulas/tag-formulas.md) or [Tag IF Statements](../../personalise-documents/tag-formulas/tag-if-statements.md)

But if these don't work, this guide will show you how to set up a Portant Workflow based on a Google Forms Response Sheet and add formula to it.

**In this article, you’ll learn how to:**

1. Set up a data merge for a Google Forms Response Sheet
2. Add formula to the sheet

#### Set up a data merge for the Google Forms Response Sheet

To set up a data merge that uses a Google Form response sheet, you need to switch it on from your Google Form. \
First, open up your Google Form, then click the 'Responses' tab in the centre of the page. Then click the Google Form icon in the top right corner of the page 'Create Spreadsheet'.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6320acf88abf670e369215c9_Screenshot%202022-09-13%20at%205.14.06%20pm.png" alt=""><figcaption></figcaption></figure>

After you have clicked this icon, you can select if you'd like to make a new spreadsheet or add it as a tab in an existing spreadsheet. This means any time you receive a response for your form, the data will be inserted into this Google Sheet.&#x20;

Then create a new workflow in Portant that uses the Google Sheet you just created as the source.

When you turn on Auto-create for this workflow, Portant will check the spreadsheet every 2 minutes and create documents any time it finds new data.&#x20;

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/62c5a55d5afc187cfcf62fe1_Portant%20Workflow%20-%20Auto-create%20on.gif" alt=""><figcaption></figcaption></figure>

### Add formula to the sheet

Ok cool. So what we have made so far is just a slightly more complicated version of a Google Forms source workflow. However, now I'm going to show you how to make it more powerful by adding additional fields which can contain formula, or conditional content based on answers in the form.

There are two ways to do this:

1. Array Formula in row 2 of the Response Sheet
2. Array Formula in a New Tab of the Spreadsheet

#### Array Formula in row 2 of the Response Sheet

To add an array formula to a Google Sheet, which is especially useful for applying a formula to an entire column of data, start by clicking on the cell in Row 2 after your last column of data. Type the equals sign '=', followed by 'ARRAYFORMULA(', and then input your desired formula. Close the parenthesis after your formula is complete. Remember that the array formula will automatically expand and fill the cells in the column or row you specify. Here's a simplified example:

```
=ARRAYFORMULA(A2:A*2)
```

This formula will double the value of every cell in the range A2 through the last row in column A.&#x20;

You can also add an if statement to add content dependant on an answer with the Form response. For example this formula would add "This value is Yes" any time the form response in column A was "Yes" (and it would be blank if it wasn't yes):

```
=ARRAYFORMULA(IF(A2:A="Yes", "This value is Yes",""))
```

Make sure to hit 'Enter' to apply the array formula to the desired range or column.

Then whenever a new response is submitted to the form and added to the bottom of the sheet the array formula will be calculated and added to the response's row of data

#### Array formula in a new Tab of the spreadsheet.

> This is a good option if you aren't as familiar with Array Formula or if you have a formula that doesn't work with Arrays.

The first thing we need to do is to copy the response sheet data into a new tab in your spreadsheet.&#x20;

We recommend using an array formula to do this: **=ARRAYFORMULA(Sheet1!A:X)** with A being the first column of your response and X being the last column of your responses

Then you can add additional formula to the columns after the last column of data in your spreadsheet.&#x20;

#### How add formulae to sheets (which don't display an error when blank)

When you copy a formula onto multiple rows the blank rows (after the last response) can sometimes display an error or a zero, which will interfere with Portant's auto-create. To avoid these errors you need to use a formula to display BLANK instead of a zero or error.

To avoid errors you can use the **IFERROR** **formula**:\
&#xNAN;**=IFERROR("no error", "error")**\
Returns the first argument if it is not an error value, otherwise returns the second argument if present, or a blank if the second argument is absent e.g. **=IFERROR(A2\*100, "")**

To avoid zeros you can use the IF formula:\
&#xNAN;**=IF(logical\_expression, value\_if\_true, value\_if\_false)**\
Returns one value if a logical expression is 'TRUE' and another if it is 'FALSE' e.g. =**IF(A1="","",A1\*100))**

For a Full-Proof way of preventing against Errors or "0" values please combine the formula like this:\
&#xNAN;**=IFERROR((IF(A1="","",A1\*100)),"")**

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6188eeb72ccdfe01d062e52d_Screen%20Shot%202021-11-08%20at%208.30.38%20pm.png" alt=""><figcaption></figcaption></figure>

#### Feedback and feature suggestions

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\


