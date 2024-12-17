---
description: How to Trigger a HubSpot Workflow from a Portant Workflow
---

# Trigger HubSpot Workflows from Portant

HubSpot Workflows are a cornerstone for automating and streamlining business processes within Sales and Marketing. This guide aims to guide you through effectively utilising Portant Document Status's as triggers for these workflows, enabling you to streamline your processes.

In this guide you will learn how to:

1. Set up an HubSpot Workflow enrolment trigger
2. Portant Document Statuses that can be used
3. HubSpot Workflow Implementation Strategies
4. Advanced HubSpot Workflow Techniques

One of Portant's key features is the ability to save document links, statuses, and various other types of information as Custom Properties within HubSpot. These Custom Properties are added automatically by Portant when you run your first workflow.

By saving these elements as Custom Properties, you can leverage them to trigger specific HubSpot Workflows. This is made possible through Hubspot's workflow enrolment triggers, which you can learn more about here: [https://knowledge.hubspot.com/workflows/set-your-workflow-enrollment-triggers](https://knowledge.hubspot.com/workflows/set-your-workflow-enrollment-triggers)\


> **Note** - If you are looking to trigger a Portant Workflow from a HubSpot workflow we have a separate guide [here](broken-reference).

### How to set up an Enrolment Trigger

To set up an enrolment trigger in HubSpot, choose the option to trigger the workflow 'When filter criteria is met'

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/656e7c84c62b799ec1642f6b_pika-1701739632075-1x.png" alt=""><figcaption></figcaption></figure>

Then add a filter that is based on Deal/Contact/Company/Ticket properties:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/656e7e4edeeccae54472738e_pika-1701740065610-1x.png" alt=""><figcaption></figcaption></figure>

Then search for the property you would like to trigger the workflow on. In this case, it will be Document Status, but it could be anything.

> You can also combine multiple filters together, for example you could use the 'Document status' and the 'Workflow name', to only trigger the workflow when an NDA has been signed.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/656e7f2a8fae8bf9b4c4ba31_pika-1701740278643-1x.png" alt=""><figcaption></figcaption></figure>

Then select the condition and the status value like this:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/656e8b2b7573bb315396dd71_pika-1701743390188-1x.png" alt=""><figcaption></figcaption></figure>

‍

### Portant Document Statuses that can be used

Here is a list of the document statuses you could use to trigger a HubSpot workflow:

* **Pending** - the document is being created e.g. _You could use this to notify a team member that a document has been requested_
* **Draft** - A draft has been created and requires [approval](https://www.portant.co/guide-article/how-to-use-the-review-block) e.g. _You could use this to send a reminder to the team to review and finalize drafts._
* **Approved** - The document has been [approved](https://www.portant.co/guide-article/how-to-use-the-review-block) e.g. _You could use this to notify the relevant department to proceed with the next steps._
* **Signature Requested** - A signature has been requested e.g. _You could use this to notify sales reps to follow up on documents not yet signed or Send a reminder email to clients to sign the documents._
* **Signed** -The document has been signed e.g. _You could use this to move the deal to the next stage of the pipeline._
* **Sent** - An email has been sent e.g. _You could use this to start a follow-up sequence after a set period since sending._
* **Error** - an error occurred trying to create the document _e.g. You could use this to alert IT or the support team to resolve document errors._

### HubSpot Workflow Implementation Strategies

Here are a few ideas of when to use these triggers to improve processes within your company:

* **Timely Follow-ups:** Use 'Signature requested' or 'Sent' statuses to trigger reminders for your team to follow up on documents not yet actioned by clients.
* **Error Management:** Automate alerts for the support team when a document is in 'Error' status, ensuring quick resolution.
* **Progress Tracking:** Trigger internal notifications or CRM updates when documents change status, maintaining visibility across the sales cycle.

### Advanced HubSpot Workflow Techniques

Here are a few ideas on how to take your HubSpot Workflows to the next level:

* **Combining Triggers:** Implement workflows that trigger on a combination of document statuses and other criteria, like deal stage or lead score, for a more nuanced approach.
* **Automated Escalations:** Set up workflows to escalate issues based on time-sensitive statuses like 'Signature Requested' or 'Draft', ensuring timely actions.

‍

HubSpot Workflows can greatly enhance your team's efficiency. By automating responses and actions based on document statuses, you not only streamline your business process but also provide a more responsive and engaging experience for your clients.

Utilising these triggers effectively can lead to a smoother sales cycle, better client interactions and ultimately contribute to achieving higher sales targets and business growth.

### **Feedback and feature suggestions**

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at contact@portant.co

Thanks,

Blake and James
