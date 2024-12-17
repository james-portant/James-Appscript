---
description: How to manage and select HubSpot properties within your Portant Workflow
---

# How to manage and select HubSpot Properties

Did you know that you can conveniently handle all HubSpot fields using the Portant App and view a complete list of potential fields for your workflow? Moreover, you can seamlessly incorporate custom properties from your HubSpot account. 😀

**In this article you will learn:**

1. How to manage and select HubSpot properties within Portant
2. How to use "Labeled Contact Tags" within a template

### **How to manage and select HubSpot properties within Portant**

This guide dives directly into the management of HubSpot fields through a workflow. If it's your initial experience integrating HubSpot as a source with the Portant App, you may find valuable information in this accompanying [article](https://www.portant.co/guide-article/how-to-connect-a-hubspot-data-source).

Initiate the process by navigating to the Source Block within your workflow and selecting the "Manage HubSpot Fields" option:

<figure><img src="https://lh7-us.googleusercontent.com/rB8UnmOZse0kb7vbHi14kPgfP_xhcxwvN1qF02WOJsHRU0SDAu9fPxx4CgzhEDfeJ0k-5AGGusGmRuX_V3xJ2-cOi1ufW4Kn_NsczpbUGWkUAwpeieIf2v1mGNlBHt_VEkVKPvfGsGJ1SFJE6DnNayE" alt=""><figcaption></figcaption></figure>

Following that, a board will be displayed, presenting all the objects originating from your HubSpot account:

<figure><img src="https://lh7-us.googleusercontent.com/NDfL7izTCXAalqJ1rEVcnYkct_tzlwvTjlM3CvdeWsf8aN3qTeLsewO8UCi0_ybJ4B6h87jtcEOOlFxR-Nk3Tn-oL9nuqvQ67Rye3JNP4nrG8HSpXsJmr2UnlM3NR_a0UPTc2AHIXAaI_FPTq2aNUwE" alt=""><figcaption></figcaption></figure>

Select the dropdown button to unveil the properties associated with each object:

<figure><img src="https://lh7-us.googleusercontent.com/bJet6mLx-TXrwmF_kClqfH2TKJ68qKSsZprywtTky2ChvFbuQPaJyJVEWezYDUbAAvaXnOMAgNGAYCXIh2JP9mGoxYgI-EGUm00dtfysyWxKYHkMsE6-9Le7dsb8UkzUbOxnif9QPvb92Cge5WT374s" alt=""><figcaption></figcaption></figure>

Note that you have the option to exclusively display properties for the selected objects if you prefer:\


<figure><img src="https://lh7-us.googleusercontent.com/muPygWUYMFRIP4WrlT5Y08HdRSuA2LOUdQ4ot_daZMGxrXco6wtMret8BZIjZih_rnUoAqWXyyrVABrutIuCmqqdCh68Z9Yhv0sTczZu10XWVadv0_NZnjAVILmusIRzrsKRV-IpVpcuCsYn_znVyrg" alt=""><figcaption></figcaption></figure>

Once you have chosen or deselected the properties for the desired object, just click "Save," and you're good to go!

### Inserting data from Labeled Contacts (or any [Associated Object](https://knowledge.hubspot.com/object-settings/create-and-use-association-labels))

{% hint style="info" %}
You can use Association Labels for any connected objects in HubSpot
{% endhint %}

If you have multiple contacts associated with your Primary object, you can utilize labeled contact tags. These tags help you easily identify and organize which contact's properties you would like to place within your templates. For detailed instructions on creating and using association labels, refer to this HubSpot guide:[ Create and use association labels](https://knowledge.hubspot.com/object-settings/create-and-use-association-labels).

<figure><img src="../../../.gitbook/assets/Screenshot 2024-09-05 at 11.08.09 PM.png" alt=""><figcaption><p>How to add an "association label" to a contact</p></figcaption></figure>

To include the names of your labeled contacts in your documents, you can use tags like \{{**Label:** Contact First Name\}} (where **Label** is the name of the [Association Label](https://knowledge.hubspot.com/object-settings/create-and-use-association-labels)) If you also want to include their last name, use the tag \{{Label: Contact Last Name\}}.&#x20;

{% hint style="info" %}
**Warning -**  The tag must contain a space after the colon and before property name. e.g. \
❌ \{{**Label:**&#x43;ontact Last Name\}} (no space)

✅ \{{**Label:** Contact Last Name\}} (space after colon)
{% endhint %}

For instance, if your contacts are labeled as "First Signer" and "Co-Signer," the corresponding tags would be:

\{{First Signer: Contact First Name\}} \{{First Signer: Contact Last Name\}}

\{{Co-Signer: Contact First Name\}} \{{Co-Signer: Contact Last Name\}}

<figure><img src="../../../.gitbook/assets/pika-1725574285524-1x.png" alt=""><figcaption><p>Where the Association-labels appear on contacts</p></figcaption></figure>

#### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at contact@portant.co

Thanks,

Blake and James
