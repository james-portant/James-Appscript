---
description: How to add different types of images into your document template.
---

# Inserting Images

Portant Data Merge can add images into your template. All you have to do is identify a source as an image and insert a placeholder image.

#### Adding images

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/60f7d7f59d72cdef5169bd61_Adding%20Images.gif" alt=""><figcaption></figcaption></figure>

You can easily place an image into a document in a few easy steps:

1. Click the Source Row to open the options.
2. Select the '**Insert as image**' checkbox, this marks the row as an image row. To indicate the row as an image, the tag icon in the button changes to an image icon
3. Click the **Insert** button to add a placeholder image.
4. This image can be moved and scaled in your document and then Portant will insert the source images with their native aspect ratio.

Please note, in Google Docs, images can only be placed as **in-line** images. ('wrap', 'break', 'behind', 'in front' image options are not possible in a data merge). If you need to change the layer order of an image in a document please use a Google Slides file as the template (Data Merges with images on multiple layers works in Google Slides).

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/6191a3518fa52f5b5f899d31_Screen%20Shot%202021-11-13%20at%2012.08.47%20pm.png" alt="Google Docs In-line image option"><figcaption></figcaption></figure>

‍\


> **Note** | .jpg, .jpeg, .png and .gif file formats are supported.

Inserted images are always placed into the document with a locked aspect ratio (Portant doesn't distort any images to fit the placeholder). If an inserted image has a different ratio to the placeholder, Portant scales the height while maintaining the ratio ratio until placeholder width is reached.

<figure><img src="https://uploads-ssl.webflow.com/5f3b57b5405f8bd0f98b5e14/609cbde3abaac5bac9ab7053_Image%20constraints.png" alt=""><figcaption></figcaption></figure>

Portant can use the following image links/urls:

* Any public image url
* Any Google Drive image url you have access to
* Any image url uploaded via Google Forms

> Note - When using a Form to collect images, Portant will only be able to insert one per question. If multiple images are uploaded are added, Portant will select the first one. You can limit users to only upload one in [form settings.](https://support.google.com/a/users/answer/9308632?hl=en)

### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at [contact@portant.co](mailto:contact@portant.co)\


Thanks,\


Blake and James

#### Additional resources

Portant can help you [mail merge in Google Docs.](https://www.portant.co/mail-merge-google-docs)

‍
