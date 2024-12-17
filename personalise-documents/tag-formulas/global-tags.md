---
description: These are tags that can be used in any document
---

# Global tags

There are some tags that can be used in any document. These tags are:

1. Timestamp
2. Workflow Runner
3. Meaning of life

### Timestamp

This tag will display the date and time that the document was made. &#x20;

\{{Timestamp\}}

> **Note** - make sure to set up your [date format and timezone](https://docs.portant.co/portant-docs/portant-add-ons/data-merge/advanced-settings/timezone-date-and-time-format-settings#how-to-change-the-timezone)

### Workflow runner

This tag can insert the workflow runner's name in the format: "Name" . For example, you can use this tag in the To, Cc, or Bcc field of an email, and it will send the email to the workflow runner as well.&#x20;

\{{Workflow Runner\}}&#x20;

> **Note** - This tag can also be used with \{{=NAMEONLY(Workflow Runner)\}} formula field to extract the name.

### Meaning of life

Of course the list wouldn't be complete without a little easter egg. This tag displays the value 42.

\{{Meaning of life\}}&#x20;



**Feedback and feature suggestions**

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)

Thanks,

Blake and James
