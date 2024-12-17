---
description: Create your first workflow
---

# Quickstart

{% embed url="https://youtu.be/8nWfpEg0jQ4" %}

This article will show you how to set up a workflow in Portant. In this example we will make a workflow that produces PDFs every time a Google Form response is submitted and shares that PDF via email. (Google Forms is the perfect source if you would like to create a workflow that creates documents every time someone completes a form)

### **In this article you’ll learn how to:**

1. Create a new workflow
2. Select a source for your workflow
3. Customise a document with data from the source
4. Share the outputs generated via email
5. Turn on the workflow

### Create a new Workflow

The first step is to create a new workflow by clicking the 'Add Workflow' button in the top right hand corner

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6425053d71f3384e5ed1c4b5_Form%20to%20PDF.png" alt=""><figcaption></figcaption></figure>

### Select a source for your workflow

When you add a workflow, the first step is to pick a Source or document template for your workflow. In this example we are going to start from a Form source (but you could also start from the document template).

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6425064c71f33844e1d1cd1b_Form%20to%20PDF%20%E2%80%93%201.png" alt=""><figcaption></figcaption></figure>

Then select a Google Form from your Google Drive or Portant can create a new Google Form for you:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6425065628c3f842d8da3fb9_Form%20to%20PDF%20%E2%80%93%202.png" alt=""><figcaption></figcaption></figure>

After you have picked your Google Form or created a new one, Portant will display the form responses. If there are no responses yet, Portant will not display anything in this section. From this view you can open the form to edit the questions or appearance, or you can copy the public link.

> You can click the '✎ Change selected file' under the form name to select a new Google Form

### Customise a document template with data from the source

The next step is to select a template document. To connect a template, click the 'Connect' button on the right hand side.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64250723596eeca6672bfd2d_Form%20to%20PDF%20%E2%80%93%203.png" alt=""><figcaption></figcaption></figure>

You can choose to use Google Docs or Slides as your document template. Then, just like before, you can select to create a new google Doc/Slide or select an existing one.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/642508098054c58c38775f18_Form%20to%20PDF%20%E2%80%93%204.png" alt=""><figcaption></figcaption></figure>

> You can also opt to generate an email directly from the source. Additionally, you can choose templates such as Fillable PDFs or Google Sheets. Simply click on "Advanced Options" and select your preferred option.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

When you have selected your document, Portant will open it and you will be able to customise the document with Form answers.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/642508d9aeb353d642aaab96_Form%20to%20PDF%20%E2%80%93%205.png" alt=""><figcaption></figcaption></figure>

In the top right of the page is a table containing all the questions in your form (we call this the Sources Table).

If you want to place a form question answer into the document, click copy and the paste the \{{tag\}} in your document.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/62c5aabc080621d0ef34b7b0_Portant%20Workflow%20-%20Copy%20Tag%20-%20Form.gif" alt="Copy a Form tag"><figcaption></figcaption></figure>

You can also [add image tags to documents and presentations](http://www.portant.co/guide-article/image-tags), and customise tags by clicking on the row.\


When you have customised the document, you can then format how each output document will be named, by placing tags in the 'Output Name' field here

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6425096e7c31857c02e285ec_Form%20to%20PDF%20%E2%80%93%206.png" alt=""><figcaption></figcaption></figure>

Below the Output name field there is the option to save the documents as PDF\
‍

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/62c5ad3462b6215283caced4_Portant%20Workflow%20-%20Save%20as%20PDF.gif" alt="Turn on Save as PDF"><figcaption></figcaption></figure>

> If you have a free account, a Portant watermark will be added in the PDF footer. You can remove this watermark by [upgrading to Pro or Teams](https://app.portant.co/settings/billing)

This is the final step to customise your document. After completing this you can add a step to share the document via email.

### Share the document via email

Once you have formatted the document and got it to look the way you want, you can add a final step to share the document via email. To do this click the '**+**' icon below the document block and select the Email block:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64533cabfbd92f4baea09453_Form%20to%20PDF%20%E2%80%93%209.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64533cb7dcff965cee00e2f2_Form%20to%20PDF%20%E2%80%93%2010.png" alt=""><figcaption></figcaption></figure>

Once you have created a new email block you will see the options to add a To, CC or BCC address in the email block. In these fields you cna type email addresses or use tags from the source table on the righ hand side. Then below that you can also enter a subject line and a message. There are some formatting options that enable you to make the email look the way you want it to:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64533d4b8cdea03bf9124f40_Form%20to%20PDF%20%E2%80%93%2011.png" alt=""><figcaption></figcaption></figure>

Then the last step is to attach the output(s) from the workflow. You can select to share Google Slides/Docs with Viewer, Commenter or Editor permissions

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64533d9ebf2915a7de235fb0_Form%20to%20PDF%20%E2%80%93%2012.png" alt=""><figcaption></figcaption></figure>

Then click save at the bottom and close the email block.

### Turn on the workflow (and test)

When you have finished setting up your workflow, click the 'Automate' button in the top right corner and toggle the Auto-create button ON. This means that any form response that is submitted will be passed through the workflow and generate documents.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64250ace654f2a24875c8a72_Form%20to%20PDF%20%E2%80%93%207.png" alt=""><figcaption></figcaption></figure>

> In this section you can also process old Form responses by using the 'Process Existing Data' feature. With this you can process all the responses or a selection by choosing 'Custom range' from the drop down.

After this, open your form and submit a response to check it is working correctly. If it is, documents should be created in your 'Outputs' tab

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64250b35a127acd903ed49d9_Form%20to%20PDF%20%E2%80%93%208.png" alt=""><figcaption></figcaption></figure>

Voila! You've just created your first workflow 🎉

### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)&#x20;
