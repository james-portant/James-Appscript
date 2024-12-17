---
description: How to connect a Glide data source to Portant Workflow
---

# Glide

[Glide](https://www.glideapps.com/) provides a fast, easy, and affordable way to build functional and scalable web and mobile apps, without requiring extensive technical expertise. But did you know that Glide can also use Portant to generate documents & emails as features of their apps? This article will explore the various ways in which Glide data can be used to create customized documents, from waivers to customer invoices.

**In this article you’ll learn how to:**

1. Login to Portant and create a workflow
2. Select Glide as your Workflow Source
3. Format and customise your document template
4. Generate your first document
5. Send document links back to Glide Tables

#### Login to Portant and create a workflow

If you don't already have a Portant account, you can sign up for one for free here: [app.portant.co/signup](https://app.portant.co/signup)

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63d45f5703e041ca6f259b77_HubSpot%20Screenshot%201%20%E2%80%93%2010.png" alt=""><figcaption></figcaption></figure>

After you have signed up, click the blue button in the top right-hand corner: **New Workflow**.

#### Select Glide as your Workflow Source

The next step is to select Glide as the source for your workflow.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2c37c48a58b47a3bee5f0_Glide%20Integration%20-%201.png" alt=""><figcaption></figcaption></figure>

#### Connect Portant to your Glide App

After you have selected Glide as a Source, Portant will display the steps to connect your Glide source:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2c53bf9b3c8048d350410_Glide%20Integration%20-%202.png" alt=""><figcaption></figcaption></figure>

Portant can run workflows whenever an action is triggered in Glide. So the first step is to navigate to Glide and add a [Trigger Webhook action](https://www.glideapps.com/docs/reference/actions/webhook) to your App.

When you have selected the Trigger Webhook action, you need to add a new webhook in the dropdown here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2da43b68fbb3259a55594_Screenshot%202023-02-20%20at%201.25.24%20pm.png" alt=""><figcaption></figcaption></figure>

When you click 'Add new Webhook' a new modal pops up where you can name it and add a webhook address. The webhook address shown in step 4 of the Glide Source Block in Portant.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2da97700f681515523613_Screenshot%202023-02-20%20at%201.24.39%20pm.png" alt=""><figcaption></figcaption></figure>

The next step is to add values to be sent in the Webhook. The values you have access to will depend on your context. (You should also name the values so it's clear how to use the data in Portant)

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2dbc649b46c3dcec6cc62_Screenshot%202023-02-20%20at%201.32.16%20pm.png" alt=""><figcaption></figcaption></figure>

Now that we've set up our webhook, every time an action is triggered – these values will be sent to Portant. To test it, trigger the action in Glide (e.g. by clicking the button in the layout view)

When Portant receives data from Glide, a response table will appear like this:\


<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2ddb02d342c41820f7ee0_Glide%20Integration%20-%203.png" alt=""><figcaption></figcaption></figure>

> **Note:** You can rename the Glide Source in Portant Glide Block. Just click 'rename' under the title.

#### Format and customise your document template

Now you have successfully connected Portant to Glide, the next step is to connect a document template. You can do this by clicking the **Connect** button in the right panel. Here you can select to connect a Google Doc, Slides or even email template to be customised and generated from Glide data.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2ddb02d342c41820f7ee0_Glide%20Integration%20-%203.png" alt=""><figcaption></figcaption></figure>

When you have picked your document template, you can customise it by placing Glide tags from the Source table into the document. To insert a tag, click **Copy** and then insert your cursor where you'd like the tag to be placed and hit **CTRL + V** or **CMD(⌘) + V**

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2debbdd42adc6dc7036f8_Glide%20Integration%20-%204.png" alt=""><figcaption></figcaption></figure>

You can also customise the file name in the right panel and select if you'd like the document to be saved as a PDF.

> **Note:** All PDFs in the Free tier have a Portant watermark in the footer. To remove the watermark, please upgrade to our [Teams or Pro plans](https://app.portant.co/settings/billing)

#### Generate your first document

After you have customised the template and are happy with the formatting, it's time to generate your first document. To generate a document, navigate back to Glide and click trigger the action again (e.g. click the button the action is attached to). This will start the document generation process. It will take a few seconds to generate the document.

That's all there is to it, you've just set up a document workflow using Glide as a data source.

#### Send document links back to Glide Tables

> **Note:** The Glide API is limited to Team/Business/Enterprise level apps

The first step is to identify a column you want to insert the document link into. If you haven't already created a column for this data, scroll to the end of the table and insert a new column

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e5b8e5b3e02433aa82ac_Screenshot%202023-02-20%20at%202.13.49%20pm.png" alt=""><figcaption></figcaption></figure>

Give this column a unique name, select the type as a URL, and click Done.

After you have set up a column for the document link, you can select to send the document links back to [Glide Tables](https://www.glideapps.com/docs/reference/data-sources/glide-tables). To do this, select to add another workflow block and select the 'Glide' block in the Sharing section.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e03c85872a433e9e6a66_Glide%20Integration%20-%205.png" alt=""><figcaption></figcaption></figure>

If this is the first time you have added this type of block, you will need to connect the Glide API with Portant. To do this, you can click the hyperlink at the bottom of the page here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e16a48a58b2a9ec149aa_Glide%20Integration%20-%207.png" alt=""><figcaption></figcaption></figure>

To find the Authentication token, navigate back to Glide, to the Data Editor section and right click on the table you'd like to send the document link to, and then click 'Show API':

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e2687e5f1a3b4391df8c_Screenshot%202023-02-20%20at%201.57.37%20pm.png" alt=""><figcaption></figcaption></figure>

This will then display some information about the API. Click to copy one of the paragraphs of API instructions

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e29c222b9b65efe93c4a_Screenshot%202023-02-20%20at%201.58.55%20pm.png" alt=""><figcaption></figcaption></figure>

Then paste the text into a word editor and copy this section:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64181acec7afb7075984940d_Screenshot%202023-03-20%20at%207.34.09%20pm.png" alt=""><figcaption></figcaption></figure>

And paste it into the Glide section here and click '**Update**':

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e375e5b3e0adbcaa4f72_Glide%20Integration%20-%206.png" alt=""><figcaption></figcaption></figure>

After you have done this, the warning message at the bottom of the table will disappear and you will be able to enter the other values.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e45c48a58b5d8cc181ef_Glide%20Integration%20-%208.png" alt=""><figcaption></figcaption></figure>

You can find the App ID here in the same paragraph of text you copied from the API instructions here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64181adfa18bb6e7b7de4988_Screenshot%202023-03-20%20at%207.34.31%20pm.png" alt=""><figcaption></figcaption></figure>

The next thing you want to add is the Table Name which can also be found here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/64181aea5aac656332a76d46_Screenshot%202023-03-20%20at%207.34.24%20pm.png" alt=""><figcaption></figcaption></figure>

The final step is to identify the column you want to insert the document link into. (If you haven't already created a column for this data, scroll to the end of the table and insert a new column.) Copy the column name from here:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/647d5bb65e0046ec9b067017_Screenshot%202023-06-05%20at%201.50.22%20pm.png" alt=""><figcaption></figcaption></figure>

Then go back to Portant, add this column name in the 'Column name' field and click 'Update'

The final part to check is that you are sending the Row ID as part of your webhook. This is the ID that specifies which row to place the document link into. Add this data as the first row in your webhook like this:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/647d5c17df963a10c4a7a02e_unnamed%20(5).png" alt=""><figcaption></figcaption></figure>

Where the Field name is "Row ID" and the data is Row ID.

> Note the Field name needs to be only "Row ID", no emojis like "🔓 Row ID" or other text.

Now whenever the workflow is run, the document link will be placed in this column.

#### Bonus step

You can create buttons in Glide that are only shown if there is data in a certain column. You can do this by adding a condition to the action: '**Allow action when \*Invoice Link\* is not empty**' like this:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63f2e6f2dd42ad747b70f5f2_Screenshot%202023-02-20%20at%202.19.37%20pm.png" alt=""><figcaption></figcaption></figure>

In this combination of actions, we have one button that generates the invoice and one that opens the invoice, which is only shown when the invoice is generated.

#### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\


