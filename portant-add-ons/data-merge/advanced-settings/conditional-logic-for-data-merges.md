---
description: >-
  How to use conditional logic to set the Data Merge to only operate on certain
  rows
---

# Conditional Logic for Data Merges

Conditional logic is a great setting if you want to create documents only from certain rows within a spreadsheet. It can be selected from the dropdown list within the Data Merge box.

**In this article you’ll learn how to:**

1. Set up a condition
2. Advanced settings for conditions

#### How to set up a condition

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/610100bc900a3f7acb09e3fa_Screen%20Shot%202021-07-28%20at%204.59.47%20pm.png" alt=""><figcaption></figcaption></figure>

If you would like to set up a condition for a data merge, all you need to do is go to the Data Merge box and select '**condition**' in the drop down menu.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/6100fbf0498ac45d2de2b5ed_Screen%20Shot%202021-07-28%20at%204.40.24%20pm.png" alt=""><figcaption></figcaption></figure>

After you have selected condition, the next step is to select the field the condition is based on. Open the next drop down menu and select the field. If the field you want is not there you might have to click refresh in the the top right hand corner on the data sources table.

After that enter the value the field has to equal for the automation to run and bam! You're done :)

#### How to add advanced settings for conditions

It is possible to add a more advance filter that is based on two conditions (or a different operator other than 'equal') by adding another column to your spreadsheet. In this new column you can add a formula that contains the advanced conditions and then use the result of this column for the data merge. For example you could use formulae like these:

Returns 'Merge' when two different words (Apple & Orange) are entered in two seperate columns (Column A & Column B):\
\=IF(AND(A4="Apple",B4="Orange"),"Merge","")

Returns 'Merge' when either word (Apple or Orange) is entered in one column (Column A):\
\=IFERROR(IFS(A2="Apple", "Merge", A2="Orange", "Merge"),"")\
‍

Then you could set the condition in Portant to Merge based on when this column equals 'Merge'.\


This is quite a good guide on using 'IF' & 'AND' functions together:\
[https://infoinspired.com/google-docs/spreadsheet/combined-use-of-if-and-or-logical-functions-in-google-doc-spreadsheet/](https://infoinspired.com/google-docs/spreadsheet/combined-use-of-if-and-or-logical-functions-in-google-doc-spreadsheet/)\


‍\


#### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co) \


Thanks,\


Blake and James
