---
description: How to use webhooks to connect Portant
---

# Webhooks

If you need to use a source we haven't integrated with yet, you can use webhooks to source data from almost any application on the internet. If an app can send data to a Webhook, you can integrate it with Portant. For instance, you can add the Portant Webhook to Tally or Typeform, so that any time a form in these applications receives a submission, a Portant workflow will be triggered.

**In this article, you’ll learn how to:**

1. Select a Webhooks as a workflow source
2. Generate your webhook address
3. Add your webhook address to your other application
4. Webhook Data Format
5. Create a test submission
6. Format your document
7. Finish your workflow

#### Select a Webhooks as a workflow source

The first step is to select a Webhook as the source for your workflow. So click '**New Workflow**', enter your workflow name icon and colour, then select '**Use a webhook**' as the source.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/63bca1fb1563b3c758579dda_Screenshot%202023-01-10%20at%2010.23.01%20am.png" alt=""><figcaption></figcaption></figure>

#### Generate your webhook address

After you have selected a webhook as the source, Portant will automatically generate a unique webhook address:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/632b1386eab43f792b07077e_Screenshot%202022-09-21%20at%202.36.30%20pm.png" alt=""><figcaption></figcaption></figure>

Copy this address to your clipboard and then open your application's webhook section and paste the link in the webhook field.\


#### Add your webhook address to your other application (e.g. Tally, Typeform, etc)

After you have copied your webhook address, open your other application, navigate to the webhook section, and paste it into the relevant section.

To learn how to add a webhook to [Tally](https://tally.so/), visit this page: [https://tally.so/help/webhooks](https://tally.so/help/webhooks)

To learn how to add a webhook to [Typeform](https://www.typeform.com/), visit this page: [https://www.typeform.com/help/a/webhooks-360029573471/](https://www.typeform.com/help/a/webhooks-360029573471/)

#### Webhook Payload Structure

When sending data to Portant via webhooks, payloads should be structured in a key-value format.&#x20;

Here’s an example payload of how we expect data to be structured for an article:

```json
{
    "article_id": "12345",
    "title": "Understanding Webhooks: A Guide to Key-Value Payloads",
    "author": "Jane Doe",
    "published_date": "2024-10-29T10:30:00Z",
    "content": "This article provides an in-depth look at how to use key-value pair payloads in webhooks...",
    "category": "Tech Guides",
    "url": "https://example.com/articles/webhooks-key-value-payloads",
    "summary": "An introductory article about key-value pairs in webhook payloads, intended for developers.",
    "nestedArray": [
        {
            "nestedFieldName1": "nestedValue1",
            "nestedFieldName2": "nestedValue2"
        },
        {
            "nestedFieldName1": "nestedValue3",
            "nestedFieldName2": "nestedValue4"
        }
    ]
}
```

{% hint style="info" %}
This example also demonstrates how to structure data for table grouping in your document by utilizing[ webhook data grouping](webhook-data-grouping.md)
{% endhint %}

#### Create a test submission

It is important to send a test submission to Portant after you have set up your webhook because this is how Portant sets it up as a source table. The source table is how you add \{{tags\}} into your documents/presentations/emails in order to customise them.

You can either use your application's 'Test submission' functionality. Or you can manually process the data to simulate future submissions.

After you have created a test submission, Portant's webhook block will look like this (with submissions on the left and the fields on the right)

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/632b1bd992bbca7407e7a611_Screenshot%202022-09-21%20at%203.11.41%20pm.png" alt="Webhook block after it has received data"><figcaption></figcaption></figure>

#### Format your document

You can now add a document/presentation/email block to your workflow and use the fields captured in the webhook to customise the document.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/632b1d0b0d757b6ed791bb82_Screenshot%202022-09-21%20at%203.17.05%20pm.png" alt="Customise a document with a webhook"><figcaption></figcaption></figure>

#### Finish your workflow

After you've set up the rest of your workflow, we recommend sending one more test to ensure if it is all formatted correctly.

Then when the workflow is live, you will be able to see webhook submissions in the webhook block and expand the submission to see the data:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/632b1e225d7ff614bd296723_Screenshot%202022-09-21%20at%203.21.57%20pm.png" alt="Webhook event data"><figcaption></figcaption></figure>

The created output documents will be displayed in your output tab and saved in a Google Drive folder:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/632b1ee26e7d218c0f6d2a41_Screenshot%202022-09-21%20at%203.25.26%20pm.png" alt="Webhook workflow output tab"><figcaption></figcaption></figure>

That's all there is to it, you've just set up a document workflow using a webhook as a data source.

#### Feedback and feature suggestions

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\


