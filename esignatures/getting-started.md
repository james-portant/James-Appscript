---
description: How to create an eSignature workflow
---

# Getting Started

{% embed url="https://youtu.be/DH5EC7vHD9Q" %}

This article will show you how to set up a workflow in Portant that requests a signature from a recipient automatically. These can be set up from any source, so you can send out batches of signature requests from data within Google Sheets or HubSpot, or request a signature every time an action happens, like a Google Form is responded to or a HubSpot deal reaches a certain stage.

**In this article you’ll learn how to:**

1. Create a new workflow
2. Select a source for your workflow
3. Customise a document with data from the source
4. Add the eSignature placeholders
5. Edit the Signature Request email (optional)
6. Edit the Signature Confirmation email (optional)
7. Turn on the workflow

#### Create a new Workflow

The first step is to create a new workflow by clicking the 'Add Workflow' button in the top right hand corner

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6425053d71f3384e5ed1c4b5_Form%20to%20PDF.png" alt=""><figcaption></figcaption></figure>

#### Select a source for your workflow

When you add a workflow, the first step is to pick a Source or document template for your workflow. In this example we are going to start from a source but you could also start from the document template. We are going to pick a Google Form source, but you can select any source type.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6425064c71f33844e1d1cd1b_Form%20to%20PDF%20%E2%80%93%201.png" alt=""><figcaption></figcaption></figure>

Then select a Google Form from your Google Drive or Portant can create a new Google Form for you:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6425065628c3f842d8da3fb9_Form%20to%20PDF%20%E2%80%93%202.png" alt=""><figcaption></figcaption></figure>

After you have picked your Google Form or created a new one, Portant will display the form responses. If there are no responses yet, Portant will not display anything in this section. From this view you can open the form to edit the questions or appearance, or you can copy the public link.

> **Note:** You can click the '✎ Change selected file' under the form name to select a new Google Form

#### Customise a document template with data from the source

The next step is to select a template document. To connect a template, click the 'Connect' button on the right hand side.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64250723596eeca6672bfd2d_Form%20to%20PDF%20%E2%80%93%203.png" alt=""><figcaption></figcaption></figure>

You can choose to use Google Docs or Slides as your document template. Then, just like before, you can select to create a new Google Docs file or select an existing one.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/642508098054c58c38775f18_Form%20to%20PDF%20%E2%80%93%204.png" alt=""><figcaption></figcaption></figure>

When you have selected your document, Portant will open it and you will be able to customise the document with the source fields.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/646715792cd92087f6dc03bf_eSign%20Workflow%20%E2%80%93%202.png" alt=""><figcaption></figcaption></figure>

In the top right of the page is a table containing all the questions in your form (we call this the Sources Table).

If you want to place a form question answer into the document, click copy and the paste the \{{tag\}} in your document.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/62c5aabc080621d0ef34b7b0_Portant%20Workflow%20-%20Copy%20Tag%20-%20Form.gif" alt="Copy a Form tag"><figcaption></figcaption></figure>

You can also [add image tags to documents and presentations](http://www.portant.co/guide-article/image-tags), and customise tags by clicking on the row.\


When you have customised the document, you can then format how each output document will be named, by placing tags in the 'Output Name' field here

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6467158fd8c2c33c4631c70b_eSign%20Workflow%20%E2%80%93%201.png" alt=""><figcaption></figcaption></figure>

#### Add the eSignature placeholders

Below the Output Name field there is a button to Request a Signature as part of your workflow.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/646714df1c34ab560262ec7c_eSign%20Workflow.png" alt=""><figcaption></figcaption></figure>

When you click this button some additional Signature settings will appear below it. There are three main parts;

1. The email address of the recipient - this can either be a \{{tag\}} from your source or you can type an email (e.g. james@portant.co)
2. The Signature placeholder - this inserts a placeholder image into your document so you can specify where the signature is inserted
3. The Date placeholder - this inserts a placeholder image into your document so you can specify where the date the document was signed is inserted

> **Note:** Introducing our latest feature update: You can now integrate new placeholders like Text Fields and Checkboxes into your templates.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64671673a425fbd1667b7be3_eSign%20Workflow%20%E2%80%93%203.png" alt=""><figcaption></figcaption></figure>

The next step is the add the email address of the signature recipient. You can click the tag button to the right of the box to select one of the fields from your source (or you can type it in).

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/646719dd10db4152d5569e1e_eSign%20Workflow%20%E2%80%93%204.png" alt=""><figcaption></figcaption></figure>

> **Note:** If you are using Google Forms, you can't use the Respondent email field unless you have turned on [this setting in your Google Form](https://support.google.com/docs/answer/139706?hl=en#zippy=%2Ccollect-respondents-email-addresses). (An alternative is to use a question in the form to collect the users email address.)

The next step is to add the signature placeholder. To do this click the "Insert" button next to signature. When you click this button is is **important to note the placeholder will always be placed at the end of your document.** After it is inserted you can move it wherever you like, but the first time it is inserted it will be ant the end of the Doc

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64671a5dc813541f476b6a85_eSign%20Workflow%20%E2%80%93%205.png" alt=""><figcaption></figcaption></figure>

This signature placeholder is a standard image, so it can be scaled to alter the size of the signature.

> **Note:** You can copy and paste this image multiple times in the document and Signatures will be placed in every location the placeholder is saved.

The next step is to add the Date Signed placeholder. To do this, follow the same steps as above. If you need to edit the date format you can click the format preview next to the date, here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64671b848ca7fbe39018833a_eSign%20Workflow%20%E2%80%93%206.png" alt=""><figcaption></figcaption></figure>

This displays a modal where you can pick the date format (and there are some options to change how the eSigning Portal looks available for users on our [Teams Tier](https://www.portant.co/pricing).

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64671c5a76d96422ff543e0f_eSign%20Workflow%20%E2%80%93%207.png" alt=""><figcaption></figcaption></figure>

Finally you can add multiple signature in the document if you need different people to sign the same document. This feature is available in our [Pro Tier](https://www.portant.co/pricing). We have recorded a video about this feature here:

After you have added all the signature placeholders to your document, the next step is to edit the signature request email (if you want, Portant generates a template email that you can use).

> **Note:** If you have a free account, a Portant watermark will be added in the Signed PDF footer. You can remove this watermark by [upgrading to Pro or Teams](https://app.portant.co/settings/billing)

#### Edit the Signature Request email (optional)

Once you have formatted the document and added the signature placeholders, the next step is to edit your signature request email. This is the email that is sent to the recipient to request them to sign the document. To open the Signature Request Email navigate back to the workflow overview by clicking the lightning bolt icon at the top of the page. You will then see the signature request block below your document block:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64673d4622dd1cc63b36a52d_eSign%20Workflow%20%E2%80%93%208.png" alt=""><figcaption></figcaption></figure>

When you click the Signature Request block to open it, you will see the layout is similar to an Email Block with **To**, **Subject** and **Message** fields. You can not edit the **To** field, this is set by the email addresses you add to the signature settings on the previous page. However you can edit the Subject line and the Message. Similar to the Document Block is also possible to add \{{tags\}} to these sections to customise the content.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64673df685409ac9dad1d48d_eSign%20Workflow%20%E2%80%93%209.png" alt=""><figcaption></figcaption></figure>

The final step after you have made all the edits to the email is to click 'Save'.

> **Note:** On the right side, below the Source Table, you can edit the Signed Date format and also customise the Confirmation Page URL and the eSign portal branding (colour and logo).

#### Edit the Signature Confirmation email (optional)

Once you have edited and saved the Signature Request email the next step is to edit your Signature Confirmation email. This is the email that is sent after the document has been signed (by everyone, if there are multiple signatures on one document). To open the Signature Confirmation Email navigate back to the Workflow Overview by clicking the lightning bolt icon at the top of the page. At the end of the workflow there is an email block that is the Signature Confirmation block

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6467447bd8c2c33c46668dd1_eSign%20Workflow%20%E2%80%93%2010.png" alt=""><figcaption></figcaption></figure>



When you open the Signature Confirmation Block you will see the options to add a To, CC, or BCC address in the email block. In these fields, you can type email addresses or use tags from the source table on the right-hand side. Then below that, you can also enter a subject line and a message. There are some formatting options that enable you to make the email look the way you want it to:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/646745279fbe73875698c255_eSign%20Workflow%20%E2%80%93%2011.png" alt=""><figcaption></figcaption></figure>

After you have edited the email, click save at the bottom and close the email block.

#### Turn on the workflow (and test)

When you have finished setting up your workflow, click the 'Automate' button in the top right corner and toggle the Auto-create button ON. This means that any form response that is submitted will be processed by the workflow and request a signature from the recipients specified.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64674630d58fafe12f6a2492_eSign%20Workflow%20%E2%80%93%2012.png" alt=""><figcaption></figcaption></figure>

> **Note:** In this section you can also process old Form responses by using the 'Process Existing Data' feature. With this you can process all the responses or a selection by choosing 'Custom range' from the drop down.

After this, open your form and submit a response to check your workflow is working correctly. If it is, You will receive an email that looks like this:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/646748f71c34ab56029c0394_eSign%20Workflow%20%E2%80%93%2013.png" alt=""><figcaption></figcaption></figure>

When you click the 'Review and Sign' button, you will then see a page that looks like this:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6467492418811631af2071ca_eSign%20Workflow%20%E2%80%93%2014.png" alt=""><figcaption></figcaption></figure>

Then you can sign the document

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64674940925815fd29e009c5_eSign%20Workflow%20%E2%80%93%2015.png" alt=""><figcaption></figcaption></figure>

When you sign the document a signed copy will be stored in your Google Drive Folder, a Signature Confirmation email will be sent and the signed document link will be added to the Output page in Portant\
‍

> **Note:** Please, note that signature requests will expire after 30 days.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/646749d44bb53c2cdca3ce98_eSign%20Workflow%20%E2%80%93%2016.png" alt=""><figcaption></figcaption></figure>

Voila! You've just created your first signature workflow 🎉

#### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)
