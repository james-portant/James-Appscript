---
description: How to add conditional logic to control when emails are sent
---

# Conditional logic for emails

The conditional logic is a great way to control who an email is sent to, what is in the email and when they are sent.

**In this article you’ll learn how to:**

1. Add a condition to an email.
2. How to add multiple conditions

#### How to add a condition to an email?

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60f8c542485e64d7e024acae_Open%20Email%20Modal%20(1).gif" alt=""><figcaption></figcaption></figure>

To add a condition to an email first you need to open up the Email settings by clicking the **'Automatically email created docs'** checkbox within the **'Share via email'** box. After the **'Email Settings'** modal opens you can see the **'Sending conditions'** on the right side under **'Attachments'**.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/61010a4246772f080d4bbe82_Screen%20Shot%202021-07-28%20at%205.39.24%20pm.png" alt=""><figcaption></figcaption></figure>

To enable sending conditions click the **'Send emails based on defined rules'** checkbox, which will open up the **'Email conditions modal'.** In the top right hand corner of the box there is a field where you can enter a name of the condition.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/61010b2fdab1af3da1acb3e8_Screen%20Shot%202021-07-28%20at%205.41.08%20pm.png" alt=""><figcaption></figcaption></figure>

To set a condition select a field the condition will be based on in the first dropdown menu then select an operator between:

* equal
* not equals
* contains
* not contains
* is empty
* is nonempty

When you have selected your operator, you can enter the value to reference in the final field.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/61010c01e74ecc5557707b1f_Screen%20Shot%202021-07-28%20at%205.41.20%20pm.png" alt=""><figcaption></figcaption></figure>

You can then add another rule that will be used with the first rule this can be one of two options:

* AND - will only be true if **all** the rules are true
* OR - will be true if **any** of the rules are true

After you have selected this type of rule, all subsequent rules must either all be AND or all be OR.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/61010c6e138a68892b45f249_Screen%20Shot%202021-07-28%20at%205.41.30%20pm.png" alt=""><figcaption></figcaption></figure>

Finally, if you need to remove any rule there is a trash can on the far right hand side of the rule. Click this to delete the rule.

When you are finished click **'Save'** (in the bottom right hand corner) and the modal will close.

#### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\


Thanks,\


Blake and James
