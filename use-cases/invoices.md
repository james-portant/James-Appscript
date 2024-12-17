---
description: How to easily automate your invoicing process
---

# Invoices

Utilizing automated invoicing can significantly enhance efficiency by saving valuable time and minimizing the risk of mistakes. Moreover, you can conveniently manage all your data in your existing Google Sheet and track invoices seamlessly.

**In this article, you'll learn how to:**

1. How to create a new workflow[ ](https://www.youtube.com/watch?v=ovSJh7Wt7jo\&t=103s)
2. How to customize your invoice[ ](https://www.youtube.com/watch?v=ovSJh7Wt7jo\&t=130s)
3. How to add calculations
4. How to share your invoices via email
5. How to customize the file settings[ ](https://www.youtube.com/watch?v=ovSJh7Wt7jo\&t=189s)
6. How to set up a "Record Outputs" block
7. How to run the automation[ ](https://www.youtube.com/watch?v=ovSJh7Wt7jo\&t=219s)
8. How to automatically run a workflow directly from the template gallery

#### **How to create a new workflow**

The first step is to click on "+ Add Workflow":

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f54232c67ea1302fa9_PvnK8zoaFtZtwvIXr1Cy0vla9MBwbvzHcSNFR8LD2bECkdrt0LZryU-OkAaijD-hHQD5C6GHYgFzpDJc-y6kL2ABVTj0hf9dUGdjK5cF76d6bXLk0YFuItwYBVxS3GbN5ezkjjEhNGRclnDsUycjWiw.png" alt=""><figcaption></figcaption></figure>

Next, choose a source document. All the data in your invoice document will be retrieved from a Google Sheet document:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f55824b3ba5795939c_8TWhmf0Nh3_wTDs_VcU5dOQ0ZZ4hPallZuqlXLLuDIcr1sXnkThjsLQHJEhowFSSRES6EQxQJSp1NlTNZ5qVht1ZJTRo-_wgLUdbPWxX4hPNdZt_wQxlwfyXUyKj5Kmg56sdUkZO_LjL0SpjAG8oifU.png" alt=""><figcaption></figcaption></figure>

Now that you've chosen your source document, click on the plus icon to select your template document:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f4a57b0641da597533_XyIVZFveZX1LBUm9a9zoHFZxdV5T2VvbwqUnJTToy9-EzRKz8qLfUN1T8caQv3vvQ7JGvhMYtuoB-pw5uvavnlTc6cRnE0SiTFtWQmn1s1VjB3-hri3MQTvHjZL9sTStgOy45WPmMLaLa5sRuXFqLFE.png" alt=""><figcaption></figcaption></figure>

Select a Google Doc template:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f461baa3fb6f12127a_Xw150dtVMMN8JEAgdNgzWgK150CmIRnG0U5vaJ3-Gz0-D6_LYVH1ekUwF_UPxfY6gWWzHq5SsRJCLgvAz0-ZshJNVC2ChbapNUlm8Oie4mM0b9pl6IvZXR9v2-2Xz-oPCDwaKocLnWRz4tcK_vuMhA0.png" alt=""><figcaption></figcaption></figure>

#### **How to customize your invoice**[ ](https://www.youtube.com/watch?v=ovSJh7Wt7jo\&t=130s)

After selecting your invoice template, take note that on the right side of your screen, you'll find a source table. This table can be used to easily copy all the tags you require for placement into your invoice document template:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f48e8c43a311ad912f_cOdIwHEzQIoi9smbCXaWwuioUHyq6-i2nw1Lc2IbR1dR1bmSz-iLPy022iGQ-M41LaUXhKzf86uhI0rkuaPg2j2tjrLlE5IBnxayzg16vZbbiIEjvMFiig2Erquc5NNKnq3OYvY8bhkX1aKCc7OCb8c.png" alt=""><figcaption></figcaption></figure>

> **Note:** A \{{tag\}} is how Portant identifies where the source data is inserted in your template.

Next, designate an Output Name for the documents you're about to generate. Keep in mind that you can also incorporate tags here. In this particular instance, we are utilizing the tags "\{{Invoice Number\}}" and "\{{Customer Name\}}". And don’t forget to click enter to same the new file name structure

‍

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f6d3786344ea50bb86_zMCfVBVl8mx1yMn3ntOl2WmDYFYUD3qWXW5oTO1rR-BRsJOEUKHBlqnJG_p0-l6RoG_livo0jXNz06lGdd74qZoxlNtF5HFIoI9wAVk17Fbt1JpVCtnwR0sBSVtD3JAqYScfGwuycDK-m5RaeWiFiOM.png" alt=""><figcaption></figcaption></figure>

Activate the "Create PDF copy" option. By doing so, you ensure that a PDF copy of the invoice will be saved in your output page and Google Drive folder:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f4f9df919ea1851961_4cdFMwLoiAggXMsRwSqkKYO1csosAsqSXmi6BDmkC73JLcbnuGoj1ZQIknmcsOjuHx_qbr8aJScLYRA5nXcsZUPOf-1igwvcgVbOBINjXmLEkHT7dwX13OuDVcmfzlleR2YSL3fRgzXU9p1kdYe-DLI.png" alt=""><figcaption></figcaption></figure>

#### ‍**How to add calculations to your invoices**

Sometimes you might need a way to add a total to your invoice (or other types of calculation). Within Portant, you can add calculations for a few simple formulas.&#x20;

> **Note:** These formulas only work with Data Grouped fields

**Sum**\
To add all field values within a Data Group together

\{{=SUM(\*Field name\*)\}}

**Average**\
To average all field values within a Data Group

\{{=AVG(\*Field name\*)\}}

**Maximum**\
To find the Maximum value from a group of field values within a Data Group

\{{=MAX(\*Field name\*)\}}

**Minimum**\
To find the Minimum value from a group of field values within a Data Group

\{{=MIN(\*Field name\*)\}}

#### **How to share your invoices via email**

Click on  "Share document via Gmail".

> **Note:** You may also share the created documents by Outlook.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f457a0defc2e8efaac_welyVcqLqF1XOhC69_axqgzw4UgICs6zd67XjQLC42fTwPnEi-z-lJjCXp2PO8uxDqBfxrAF1OL56CiQkME4sZt-HHvtx2OETX008Jx8fLFcaMB5-iEWEOXnGS4iSBEId7CJ901HMlj-m46QPUgPx2Q.png" alt=""><figcaption></figcaption></figure>

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f6ffcd94972da0545a_GE-diHNWMF5um7bqv_BFkN_KEmrTxuan9PDr0DOww7CpURO7w30BgYCnRO2_anSbCkfuwJ4h1fGRBXfS9MUmttkrf_03uJGmXY3FXKXw8WDFUYUrsp655QV6-YdujOzzAkhuZPou7TG5-Tku2uQpqiA.png" alt=""><figcaption></figcaption></figure>

Tailor your email to your preferences by incorporating the tags you deem most suitable:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f6b37d89728092d083_StZPekDRckdQr6PcnyNNT2rGccUJTTY64wmHW47MxhbZZMMx8fKjhKP0IkU7ax7PFHwYsDLPf5Tby2jyqdln_MzKTOLQUgTkb4__wdVsi0fSXqYrSxLtVNQGEky-mkUxEggk8btV3HndG74MgDAtqkw.png" alt=""><figcaption></figcaption></figure>

> **Note:** Alternatively, you can add the email block by clicking the plus icon here:

‍

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/65294c0c532f1fa906429728_H1Ys3s3DOhqtmaon9KpgrOWhFTjoQAR_4hxCpXKy5is1e33QAmjBz53J28RdMnQDREIO1PKmrv8i4vawgaPbL3y3rgaqahWuSJQgagCim5KMw1aUzOZ6VGMYaG8RyGvzCS5xg7IsBa26c2TgyjmhWmQ.png" alt=""><figcaption></figcaption></figure>

#### **How to customize the file settings**[ ](https://www.youtube.com/watch?v=ovSJh7Wt7jo\&t=189s)

Click on "Add attachments"

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f64ea2fd17ae768b0c_wljsmrdBJM31_jRFPhnUoEPpsGDKt_eqrOXrMRQRd-CIieYDF7AEKZlBIh16y62_UdAgy7jd6hT_P43Co-WbsNP3_or0690oTD0m_1ymCgfmpyHFhx2wJE-qQpl2Z2fqLgpCTkgWJWJtS49moW-p4RI.png" alt=""><figcaption></figcaption></figure>

Select the desired attachment format for sending the invoice. In this example, we are choosing to send it as a PDF file:\


<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f461f8baff8f39a70c_SkXXu8r-lq_rydXiIQh6G0oGe4OCyAiW6Ohu2vi1j70Cu_Y_TRTCRY2RFLOCHgLWesrE-H5rKnP0oyRKnUuktiW8a3WqNY0dKQ9WPtavdXe2f8KmUS0R7aWBF91GsEp9VsXJrDwVesBawia95XXRzxo.png" alt=""><figcaption></figcaption></figure>

Then, save:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f5a43386c0b96fae83_5JqaRUo94l0reizB2_AweFVEzG-q03kvlBO_HSRVyxXh0tnVtWarf1hTdsJvGCE9CwU9mfzG2y7qmDbHXsaHWb99x6qRpwRzfEk_z1VsjktvjZrkJARcNAX5jsqI_90BGttO4CfqvIfKAzqdX9rpgBs.png" alt=""><figcaption></figcaption></figure>

‍

#### **How to set up a "Record Outputs" block**

You also have the option to include a "Record Outputs" block. This block adds a link to the generated output in a new column in your source document.

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f60c8ab9c9f5fa5528_UyUJ54GfPsBjCWl-Kv42f8ov_LT05wovy50jajqLM1HTzFpog65LoH-u874OnCxoffGiGVr3H37azDEvplUePetkZqY3Ckeea3TQ7EPeQgagyedLR2eHIaVe5bNRebzn_P0ixLSuzDSP05QWDKSM5wU.png" alt=""><figcaption></figcaption></figure>

Here are the columns that will be generated in your source document, each containing links to the corresponding generated outputs:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f7315d96abb5e6230b_MHlUHT6nEMKDRKm54NO-iMvVT_TWKOMMdisd3G1Hsxm9kxaH3TNPFzKNVVsUUxkz1Wf9zMg60fmxiNCFM2q2ot1ofa7hSaWArfEgeEAKgr7ouVor0WUT_1gjx6M0RRw4sPPLt25q5NpYrVZGVUYoK1c.png" alt=""><figcaption></figcaption></figure>

Since we have enabled the "Create PDF copy" option, we will also see the generated output files  on our output page for viewing:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f4d8e9ce77bf7db786_CHrWq-cauZ2q5K4TNXESrdAMrVtSxgSbkC0n5ObuwUTa0xIQnZEqzsJ2XCVkvxwTkIgBty_8MLnurPp-LxKvIdKA75rZ17WGJvs4Unp0qmcUopw8bxIJOmTgwTLG5YUBdrEoAcKLG6urwjW1hiL3pVA.png" alt=""><figcaption></figcaption></figure>

#### **How to run the automation**[ ](https://www.youtube.com/watch?v=ovSJh7Wt7jo\&t=219s)

If you click on the lightning icon, you will see all your workflow blocks. The green ticks show that all stages are correctly set up:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f415e2cd917496adc0_sJwko_gBUKOFP4U9WcpF38tEWgpIXeQVDSMSaZbU8X0JrXg7HqNxvIcbz16GzNhWylv9ZFluKZzh4SbTW_QFU_eMAkBKd1Cnz4p1OZ8hPAeVYrbHWzX3AzpkxrfhTnH8w4l73MPlI-YfeDbEMwaDtjY.png" alt=""><figcaption></figcaption></figure>

Click "Automate" and then click "Start". Your invoice documents will now be created:If

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f5586d94cb329b6b6f_sRbtt085hdndwEVC1c6dozEKC8ifxTeKbO1jMgrqGNCiOWfw1mHOXSgTGW-sRf8F86AvuP6Ctzkk5BqM74Jy0b2AoEkfY41zHAM57cgc2yROpudB8tCCfRNRz2Ril09zRj83FQwRJcL7llFXfdyuJUU.png" alt=""><figcaption></figcaption></figure>

Keep in mind that you can execute this workflow for a specific customer range rather than processing all the data from your source document. To do this, select the "customer range" option as shown below:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f5980499d48e3304d1_UvevwPCSlf9n5-2cuBrb2CTRe_KP0IxPsVPlog9pR_G9yNEZe0k16zg8OsTA-W1MoeYe3KmkHlwUgKihYPxrT352CL9lX2iyVrw2ujp6TyDpc0v-7IH4ULY_Uzn0iWkujd17rC06beqGl0Ans4gNPjo.png" alt=""><figcaption></figcaption></figure>

Finally, if you want Portant to automatically run this workflow every time new data is detected in your source document, activate the "Auto-Create" mode. For more information on this feature, please,[ **click here**](https://www.portant.co/guide-article/google-sheets-auto-create).&#x20;

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/6525b4f4d9d6537fa076a138_anndwxlHS_V34bP7UhdrKPmjI6syYnsr7EF-CGtOgI-bzTIQhgsoXfjemJM216v2iEvuk4Un2LEyOpVJ4G2VymLJM_ZjPTe-I6DNNnJVZgNetJuIIcgbj2OruQHS6sZGNhvklF3ccB48eQZ4kJFcgVc.png" alt=""><figcaption></figcaption></figure>

#### **How to automatically run a workflow directly from the template gallery**

Keep in mind that our template gallery offers a wide variety of workflow templates, accessible at this [**link**](https://app.portant.co/templates). We will provide you with a template and a source document that you can easily edit directly within Portant. Simply navigate to our template page and select the workflow of your choice. In this instance, we have opted for the Invoice Workflow template:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/65294c10db833920ec9adeba_XwYqrfj2qn5MeKAuGq4etTe9GS79Lr4MkYCaJmibv1iJxSGs0bADcMBOf0D-eFn3GKGKUH6um7c98HqAJAPXUPxCTVIuHkBpXbSAf2pto6ozWUJY__IBbKBwWGcfOC4Hco7eUIzY0blxeE787068OnY.png" alt=""><figcaption></figcaption></figure>

After selecting the workflow you want, click "Copy Workflow":\


<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/65294c0ce58053b985ce0713_LgDQ54gPbgNfP4bb6GYgLqMMEqhStPrqHn8vbfWxehRmPMkfE3yHbmrRUPOsVB8Okf8HcDoWVb2EO6K_sqoh51PRfVEiMhHM0ezs9JD-035z5-HSNIcRoxhmA1AYx_cH8CRVuKTX1FqmFvn-XCy6t58.png" alt=""><figcaption></figcaption></figure>

\
Portant now will create a copy of this workflow within the workflow gallery:

<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/65294c0e3da2c9890a47a63e_e3kd4amRlcJny8fZPUT3VEFUelLOBO_QgGYSWdVWymP3z3Xngr6p6b0-Su3yT0QUMJfGToT0qegmN9Hw2fCbtkK3pAKc4B2b2FdGXFPM97DzG2BwNjlnXVkbqRJQXMbkz-AQdN_Qb0ChdT0PAcbiJII.png" alt=""><figcaption></figcaption></figure>

\
You now have all your workflow blocks already configured like this:\


<figure><img src="https://assets-global.website-files.com/5f3b57b5405f8bd0f98b5e14/65294c0e02a5d4b75a5a9fd5_aaLleGJgVZKzbF5Oieva-MASWSHu2k-TzRKQLMSV_7Dsaxsf72QZGD_gc3sqAKseyRsj4zAg15APJ-nEN2i-6A5YTmGCqo7Uqkvb1i5MYLZz0YL1Ny5bx5t5A5wswvdKo_GeXQ_5ZdX_BgRYkKky-nU.png" alt=""><figcaption></figcaption></figure>

Subsequently, customize each block to align with your specific requirements, as exemplified earlier in this article.

#### **Feedback and feature suggestions**

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at contact@portant.co
