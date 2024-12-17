---
description: The full list of available HubSpot Properties
---

# Full list of available HubSpot Properties

Here's a compilation of standard tags from HubSpot, along with their descriptions for the following objects: Deals, Deals, Contacts, Companies,Tickets, Line Items and  Meetings:

> #### **Note - In this section, you'll find Portant custom objects that are created as part of generating a document in HubSpot**

<details>

<summary>Deals</summary>

\{{Amount in company currency\}}

The amount of the deal, using the exchange rate, in your company's currency.

\{{Days to close\}}

The number of days the deal took to close.

\{{Currency\}}

Currency code for the deal.

\{{Annual contract value\}}

The annual contract value (ACV) of this deal.

\{{Business units\}}

The business units this record is assigned to.

\{{Deal Collaborator\}}

Owner ids of the users involved in closing the deal.

\{{Deal Split Users\}}

The owner ids of all associated Deal Splits. This property is set automatically by HubSpot.

\{{Latest Source\}}

Source for the contact either directly or indirectly associated with the last session activity for this deal.

\{{Latest Source Company\}}

Source for the company with an associated contact with the last session activity for this deal.

\{{Latest Source Contact\}}

Source for the directly associated contact with the last session activity for this deal.

\{{Latest Source Data 1\}}

Additional source details of the last session attributed to any contacts that are directly or indirectly associated with this deal.

\{{Latest Source Data 1 Company\}}

Additional source details of the last session attributed to any contacts that are indirectly associated with this deal (via a company association).

\{{Latest Source Data 1 Contact\}}

Additional source details of the last session attributed to any contacts that are directly associated with this deal.

\{{Latest Source Data 2\}}

Additional source details of the last session attributed to any contacts that are directly or indirectly associated with this deal.

\{{Latest Source Data 2 Company\}}

Additional source details of the last session attributed to any contacts that are indirectly associated with this deal.

\{{Latest Source Data 2 Contact\}}

Additional source details of the last session attributed to any contacts that are directly associated with this deal.

\{{Latest Source Timestamp\}}

Timestamp of when latest source occurred for either a directly or indirectly associated contact.

\{{Latest Source Timestamp Company\}}

Timestamp of when latest source occurred for an indirectly associated contact.

\{{Latest Source Timestamp Contact\}}

Timestamp of when latest source occurred for a directly associated contact.

\{{Original Source Type\}}

Original source for the contact with the earliest activity for this deal.

\{{Original Source Data 1\}}

Additional information about the original source for the associated contact, or associated company if there is no contact, with the oldest value for the Time first seen property.

\{{Original Source Data 2\}}

Additional information about the original source for the associated contact, or associated company if there is no contact, with the oldest value for the Time first seen property.

\{{Annual recurring revenue\}}

The annual recurring revenue (ARR) of this deal.

\{{HubSpot Campaign\}}

The marketing campaign the deal is associated with.

\{{Closed Deal Amount\}}

Returns the amount if the deal is closed. Else, returns 0.

\{{Closed Deal Amount In Home Currency\}}

Returns the amount in home currency if the deal is closed. Else, returns 0.

\{{Closed won count\}}

Returns 1 if this deal is closed won.

\{{Closed Won Date (Internal)\}}

Returns closedate if this deal is closed won.

\{{Created by user ID\}}

The user that created this object. This value is automatically set by HubSpot and may not be modified.

\{{Date entered 'Appointment Scheduled (Sales Pipeline)'\}}

The date and time when the deal entered the 'Appointment Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date entered 'Closed Lost (Sales Pipeline)'\}}

The date and time when the deal entered the 'Closed Lost' stage, 'Sales Pipeline' pipeline.

\{{Date entered 'Closed Won (Sales Pipeline)'\}}

The date and time when the deal entered the 'Closed Won' stage, 'Sales Pipeline' pipeline.

\{{Date entered 'Contract Sent (Sales Pipeline)'\}}

The date and time when the deal entered the 'Contract Sent' stage, 'Sales Pipeline' pipeline.

\{{Date entered 'Decision Maker Bought-In (Sales Pipeline)'\}}

The date and time when the deal entered the 'Decision Maker Bought-In' stage, 'Sales Pipeline' pipeline.

\{{Date entered 'Presentation Scheduled (Sales Pipeline)'\}}

The date and time when the deal entered the 'Presentation Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date entered 'Qualified To Buy (Sales Pipeline)'\}}

The date and time when the deal entered the 'Qualified To Buy' stage, 'Sales Pipeline' pipeline.

\{{Date exited 'Appointment Scheduled (Sales Pipeline)'\}}

The date and time when the deal exited the 'Appointment Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date exited 'Closed Lost (Sales Pipeline)'\}}

The date and time when the deal exited the 'Closed Lost' stage, 'Sales Pipeline' pipeline.

\{{Date exited 'Closed Won (Sales Pipeline)'\}}

The date and time when the deal exited the 'Closed Won' stage, 'Sales Pipeline' pipeline.

\{{Date exited 'Contract Sent (Sales Pipeline)'\}}

The date and time when the deal exited the 'Contract Sent' stage, 'Sales Pipeline' pipeline.

\{{Date exited 'Decision Maker Bought-In (Sales Pipeline)'\}}

The date and time when the deal exited the 'Decision Maker Bought-In' stage, 'Sales Pipeline' pipeline.

\{{Date exited 'Presentation Scheduled (Sales Pipeline)'\}}

The date and time when the deal exited the 'Presentation Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date exited 'Qualified To Buy (Sales Pipeline)'\}}

The date and time when the deal exited the 'Qualified To Buy' stage, 'Sales Pipeline' pipeline.

\{{Days to close (without rounding)\}}

The number of days the deal took to close, without rounding.

\{{Deal amount calculation preference\}}

Specifies how deal amount should be calculated from line items.

\{{Deal Score\}}

The predictive deal score calculated by Hubspot AI to score the deal health.

\{{Deal probability\}}

The probability a deal will close. This defaults to the deal stage probability setting.

\{{Deal stage probability shadow\}}

Fall back property for calculating the deal stage when no customer override exists. Probability between 0 and 1 of the deal stage. Defaults to 0 for unknown deal stages.

\{{Exchange rate\}}

This is the exchange rate used to convert the deal amount into your company currency.

\{{Forecast amount\}}

The custom forecasted deal value calculated by multiplying the forecast probability and deal amount in your company’s currency.

\{{Forecast probability\}}

The custom percent probability a deal will close.

\{{Is Deal Closed?\}}

True if the deal was won or lost.

\{{Is Closed Won\}}

True if the deal is in the closed won state, false otherwise.

\{{Deal Split Added\}}

Indicates if the deal is split between multiple users.

\{{Is open count\}}

1 if the deal is not closed won/lost, else 0.

\{{Last Modified Date\}}

Most recent timestamp of any property update for this deal. This includes HubSpot internal properties, which can be visible or hidden. This property is updated automatically.

\{{Likelihood to close by the close date\}}

Hubspot predicted likelihood between 0 and 1 of the deal to close by the close date.

\{{Global Term Line Item Discount Percentage\}}

For internal HubSpot Application use only. Global term for the discount percentage applied.

\{{Global Term Line Item Discount Percentage Enabled\}}

For internal HubSpot Application use only. Indicates if the Global term for the discount percentage is enabled.

\{{Global Term Line Item Recurring Billing Period\}}

For internal HubSpot Application use only. Global term for product recurring billing duration.

\{{Global Term Line Item Recurring Billing Period Enabled\}}

For internal HubSpot Application use only. Indicates if the Global term for product recurring billing duration is enabled.

\{{Global Term Line Item Recurring Billing Start Date\}}

For internal HubSpot Application use only. Global term for recurring billing start date for a line item.

\{{Global Term Line Item Recurring Billing Start Date Enabled\}}

For internal HubSpot Application use only. Indicates if the Global term for recurring billing start date for a line item is enabled.

\{{Global Term Line Item Recurring Billing Frequency\}}

For internal HubSpot Application use only. Global term for how frequently the product is billed.

\{{Global Term Line Item Recurring Billing Frequency Enabled\}}

For internal HubSpot Application use only. Indicates if the Global term for how frequently the product is billed is enabled.

\{{Forecast category\}}

The likelihood a deal will close. This property is used for manual forecasting your deals.

\{{Merged Deal IDs\}}

The list of Deal record IDs that have been merged into this Deal. This value is automatically set by HubSpot and may not be modified.

\{{Monthly recurring revenue\}}

The monthly recurring revenue (MRR) of this deal.

\{{Next step\}}

A short description of the next step for the deal.

\{{Number of Active Deal Registrations\}}

The number of active deal registrations associated with this deal. This property is set automatically by HubSpot.

\{{Number of Deal Registrations\}}

The number of deal registrations associated with this deal. This property is set automatically by HubSpot.

\{{Number of Deal Splits\}}

The number of deal splits associated with this deal. This property is set automatically by HubSpot.

\{{Number of Associated Line Items\}}

The number of line items associated with this deal.

\{{Number of target accounts\}}

The number of target account companies associated with this deal. This property is set automatically by HubSpot.

\{{Record ID\}}

The unique ID for this record. This value is automatically set by HubSpot and may not be modified.

\{{Record Creation Source\}}

Source (PropertySource) that created this object record.

\{{Record Creation Source ID\}}

The sourceId -- further detail -- of the source that created this object record.

\{{Record Source\}}

How this record was created.

\{{Record Creation Source User ID\}}

User ID of the user who initiated creation of this object record.

\{{Pinned Engagement ID\}}

The object ID of the current pinned engagement. This value is automatically set by HubSpot and may not be modified.

\{{The predicted deal amount\}}

Returns the multiplication of the deal amount times the predicted likelihood of the deal to close by the close date.

\{{The predicted deal amount in your company's currency\}}

Returns the multiplication of the deal amount in your company's currency times the predicted likelihood of the deal to close by the close date.

\{{Priority\}}

The priority of the deal

\{{Weighted amount\}}

Returns the multiplication of the amount times the probability of the deal closing.

\{{Weighted amount in company currency\}}

Returns the multiplication of the amount in home currency times the probability of the deal closing.

\{{Read Only Object\}}

Is the object read only.

\{{Source Object ID\}}

The ID of the object from which the data was migrated. This is set automatically during portal data migration.

\{{Deal Tags\}}

List of tag ids applicable to a deal. This property is set automatically by HubSpot.

\{{Total contract value\}}

The total contract value (TCV) of this deal.

\{{Time in 'Appointment Scheduled (Sales Pipeline)'\}}

The total time in seconds spent by the deal in the 'Appointment Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Time in 'Closed Lost (Sales Pipeline)'\}}

The total time in seconds spent by the deal in the 'Closed Lost' stage, 'Sales Pipeline' pipeline.

\{{Time in 'Closed Won (Sales Pipeline)'\}}

The total time in seconds spent by the deal in the 'Closed Won' stage, 'Sales Pipeline' pipeline.

\{{Time in 'Contract Sent (Sales Pipeline)'\}}

The total time in seconds spent by the deal in the 'Contract Sent' stage, 'Sales Pipeline' pipeline.

\{{Time in 'Decision Maker Bought-In (Sales Pipeline)'\}}

The total time in seconds spent by the deal in the 'Decision Maker Bought-In' stage, 'Sales Pipeline' pipeline.

\{{Time in 'Presentation Scheduled (Sales Pipeline)'\}}

The total time in seconds spent by the deal in the 'Presentation Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Time in 'Qualified To Buy (Sales Pipeline)'\}}

The total time in seconds spent by the deal in the 'Qualified To Buy' stage, 'Sales Pipeline' pipeline.

\{{Unique creation key\}}

Unique property used for idempotent creates.

\{{Updated by user ID\}}

The user that last updated this object. This value is automatically set by HubSpot and may not be modified.

\{{User IDs of all notification followers\}}

The user IDs of all users that have clicked follow within the object to opt-in to getting follow notifications.

\{{User IDs of all notification unfollowers\}}

The user IDs of all object owners that have clicked unfollow within the object to opt-out of getting follow notifications.

\{{User IDs of all owners\}}

The user IDs of all owners of this object.

\{{Cumulative time in "Appointment Scheduled (Sales Pipeline)"\}}

The cumulative time in seconds spent by the deal in the 'Appointment Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Cumulative time in "Closed Lost (Sales Pipeline)"\}}

The cumulative time in seconds spent by the deal in the 'Closed Lost' stage, 'Sales Pipeline' pipeline.

\{{Cumulative time in "Closed Won (Sales Pipeline)"\}}

The cumulative time in seconds spent by the deal in the 'Closed Won' stage, 'Sales Pipeline' pipeline.

\{{Cumulative time in "Contract Sent (Sales Pipeline)"\}}

The cumulative time in seconds spent by the deal in the 'Contract Sent' stage, 'Sales Pipeline' pipeline.

\{{Cumulative time in "Decision Maker Bought-In (Sales Pipeline)"\}}

The cumulative time in seconds spent by the deal in the 'Decision Maker Bought-In' stage, 'Sales Pipeline' pipeline.

\{{Cumulative time in "Presentation Scheduled (Sales Pipeline)"\}}

The cumulative time in seconds spent by the deal in the 'Presentation Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Cumulative time in "Qualified To Buy (Sales Pipeline)"\}}

The cumulative time in seconds spent by the deal in the 'Qualified To Buy' stage, 'Sales Pipeline' pipeline.

\{{Date entered "Appointment Scheduled (Sales Pipeline)"\}}

The date and time when the deal entered the 'Appointment Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date entered "Closed Lost (Sales Pipeline)"\}}

The date and time when the deal entered the 'Closed Lost' stage, 'Sales Pipeline' pipeline.

\{{Date entered "Closed Won (Sales Pipeline)"\}}

The date and time when the deal entered the 'Closed Won' stage, 'Sales Pipeline' pipeline.

\{{Date entered "Contract Sent (Sales Pipeline)"\}}

The date and time when the deal entered the 'Contract Sent' stage, 'Sales Pipeline' pipeline.

\{{Date entered "Decision Maker Bought-In (Sales Pipeline)"\}}

The date and time when the deal entered the 'Decision Maker Bought-In' stage, 'Sales Pipeline' pipeline.

\{{Date entered "Presentation Scheduled (Sales Pipeline)"\}}

The date and time when the deal entered the 'Presentation Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date entered "Qualified To Buy (Sales Pipeline)"\}}

The date and time when the deal entered the 'Qualified To Buy' stage, 'Sales Pipeline' pipeline.

\{{Date exited "Appointment Scheduled (Sales Pipeline)"\}}

The date and time when the deal exited the 'Appointment Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date exited "Closed Lost (Sales Pipeline)"\}}

The date and time when the deal exited the 'Closed Lost' stage, 'Sales Pipeline' pipeline.

\{{Date exited "Closed Won (Sales Pipeline)"\}}

The date and time when the deal exited the 'Closed Won' stage, 'Sales Pipeline' pipeline.

\{{Date exited "Contract Sent (Sales Pipeline)"\}}

The date and time when the deal exited the 'Contract Sent' stage, 'Sales Pipeline' pipeline.

\{{Date exited "Decision Maker Bought-In (Sales Pipeline)"\}}

The date and time when the deal exited the 'Decision Maker Bought-In' stage, 'Sales Pipeline' pipeline.

\{{Date exited "Presentation Scheduled (Sales Pipeline)"\}}

The date and time when the deal exited the 'Presentation Scheduled' stage, 'Sales Pipeline' pipeline.

\{{Date exited "Qualified To Buy (Sales Pipeline)"\}}

The date and time when the deal exited the 'Qualified To Buy' stage, 'Sales Pipeline' pipeline.

\{{Latest time in "Appointment Scheduled (Sales Pipeline)"\}}

The total time in seconds spent by the deal in the 'Appointment Scheduled' stage, 'Sales Pipeline' pipeline since it last entered this stage.

\{{Latest time in "Closed Lost (Sales Pipeline)"\}}

The total time in seconds spent by the deal in the 'Closed Lost' stage, 'Sales Pipeline' pipeline since it last entered this stage.

\{{Latest time in "Closed Won (Sales Pipeline)"\}}

The total time in seconds spent by the deal in the 'Closed Won' stage, 'Sales Pipeline' pipeline since it last entered this stage.

\{{Latest time in "Contract Sent (Sales Pipeline)"\}}

The total time in seconds spent by the deal in the 'Contract Sent' stage, 'Sales Pipeline' pipeline since it last entered this stage.

\{{Latest time in "Decision Maker Bought-In (Sales Pipeline)"\}}

The total time in seconds spent by the deal in the 'Decision Maker Bought-In' stage, 'Sales Pipeline' pipeline since it last entered this stage.

\{{Latest time in "Presentation Scheduled (Sales Pipeline)"\}}

The total time in seconds spent by the deal in the 'Presentation Scheduled' stage, 'Sales Pipeline' pipeline since it last entered this stage.

\{{Latest time in "Qualified To Buy (Sales Pipeline)"\}}

The total time in seconds spent by the deal in the 'Qualified To Buy' stage, 'Sales Pipeline' pipeline since it last entered this stage.

\{{Performed in an import\}}

Object is part of an import.

\{{Owner Assigned Date\}}

The date the most recent deal owner was assigned to a deal. This is updated automatically by HubSpot..

\{{Deal Name\}}

The name given to this deal.

\{{Amount\}}

The total amount of the deal.

\{{Deal Stage\}}

The stage of the deal. Deal stages allow you to categorize and track the progress of the deals that you are working on.

\{{Pipeline\}}

The pipeline the deal is in. This determines which stages are options for the deal.

\{{Close Date\}}

Date the deal was closed. This property is set automatically by HubSpot.

\{{Create Date\}}

Date the deal was created. This property is set automatically by HubSpot.

\{{Date of last meeting booked in meetings tool\}}

The date of the most recent meeting an associated contact has booked through the meetings tool.

\{{Campaign of last booking in meetings tool\}}

This UTM parameter shows which marketing campaign (e.g. a specific email) referred an associated contact to the meetings tool for their most recent booking. This property is only populated when you add tracking parameters to your meeting link.

\{{Medium of last booking in meetings tool\}}

This UTM parameter shows which channel (e.g. email) referred an associated contact to the meetings tool for their most recent booking. This property is only populated when you add tracking parameters to your meeting link.

\{{Source of last booking in meetings tool\}}

This UTM parameter shows which site (e.g. Twitter) referred an associated contact to the meetings tool for their most recent booking. This property is only populated when you add tracking parameters to your meeting link.

\{{Latest meeting activity\}}

The date of the most recent meeting (past or upcoming) logged for, scheduled with, or booked by a contact associated with this deal.

\{{Recent Sales Email Replied Date\}}

The last time a tracked sales email was replied to for this deal.

\{{Deal owner\}}

User the deal is assigned to. Assign additional users to a deal record by creating a custom user property.

\{{Last Contacted\}}

The last time a call, sales email, or meeting was logged for this deal. This is set automatically by HubSpot based on user actions.

\{{Last Activity Date\}}&#x20;

The last time a note, call, email, meeting, or task was logged for a deal. This is updated automatically by HubSpot.

\{{Next Activity Date\}}&#x20;

The date of the next upcoming activity for a deal. This property is set automatically by HubSpot based on user action. This includes logging a future call, sales email, or meeting using the Log feature, as well as creating a future task or scheduling a future meeting. This is updated automatically by HubSpot.

\{{Number of times contacted\}}&#x20;

The total number of sales activities (notes, calls, emails, meetings, or tasks) logged for a deal. This is updated automatically by HubSpot.

\{{Number of Sales Activities\}}&#x20;

The total number of times a sales email or call has been logged for a deal. This is updated automatically by HubSpot.

\{{HubSpot Create Date\}}&#x20;

The date the deal was created. This property is set automatically by HubSpot.

\{{HubSpot Team\}}&#x20;

Primary team of the deal owner. This property is set automatically by HubSpot.

\{{Deal Type\}}&#x20;

The type of deal. By default, categorize your deal as either a New Business or Existing Business.

\{{All owner ids\}}&#x20;

The value of all owner referencing properties for this object, both default and custom.

\{{Deal Description\}}&#x20;

Description of the deal.

\{{All team ids\}}&#x20;

The team ids corresponding to all owner referencing properties for this object, both default and custom.

\{{All teams\}}&#x20;

The team ids, including up the team hierarchy, corresponding to all owner referencing properties for this object, both default and custom.

\{{Number of Associated Contacts\}}

The number of contacts associated with this deal. This property is set automatically by HubSpot.

\{{Closed Lost Reason\}}

Reason why this deal was lost.

\{{Closed Won Reason\}}

Reason why this deal was won.

</details>

<details>

<summary>Contacts</summary>

\{{Company size\}}

Contact's company size. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Date of birth\}}

Contact's date of birth. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Days To Close\}}

Count of days elapsed between creation and being closed as a customer. Set automatically.

\


\{{Degree\}}

Contact's degree. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Field of study\}}

Contact's field of study. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{First Conversion Date\}}

Date this contact first submitted a form.

\


\{{First Conversion\}}

First form this contact submitted.

\


\{{First Deal Created Date\}}

Date first deal was created for contact. Set automatically.

\


\{{Gender\}}

Contact's gender. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Graduation date\}}

Contact's graduation date. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Additional email addresses\}}

A set of additional email addresses for a contact.

\


\{{Business units\}}

The business units this record is assigned to.

\


\{{All vids for a contact\}}

A set of all vids, canonical or otherwise, for a contact.

\


\{{First Touch Converting Campaign\}}

Campaign responsible for the first touch creation of this contact.

\


\{{Last Touch Converting Campaign\}}

Campaign responsible for the last touch creation of this contact.

\


\{{Avatar FileManager key\}}

The path in the FileManager CDN for this contact's avatar override image. Automatically set by HubSpot.

\
\
\


\{{Buying Role\}}

Role the contact plays during the sales process. Contacts can have multiple roles, and can share roles with others.

\


\{{All form submissions for a contact\}}

A set of all form submissions for a contact.

\


\{{Merged vids with timestamps of a contact\}}

Merged vids with timestamps of a contact.

\


\{{Calculated Mobile Number in International Format\}}

Mobile number in international format.

\


\{{Calculated Phone Number in International Format\}}

Phone number in international format.

\


\{{Calculated Phone Number Area Code\}}

Area Code of the calculated phone number.

\


\{{Calculated Phone Number Country Code\}}

Country code of the calculated phone number.

\


\{{Calculated Phone Number Region\}}

ISO2 Country code for the derived phone number.

\


\{{Clicked on a LinkedIn Ad\}}

Whether contact has clicked on a LinkedIn Ad.

\


\{{Member email\}}

Email used to send private content information to members.

\


\{{Email Confirmed\}}

Email Confirmation status of user of Content Membership.

\


\{{Time enrolled in registration follow up emails\}}

The time when the contact was first enrolled in the registration follow up email flow.

\


\{{Membership Notes\}}

Notes relating to the contact's content membership.

\


\{{Registered At\}}

Datetime at which this user was set up for Content Membership.

\


\{{Domain to which registration email was sent\}}

Domain to which the registration invitation email for Content Membership was sent to.

\


\{{Time registration email was sent\}}

Datetime at which this user was sent a registration invitation email for Content Membership.

\


\{{Status\}}

Status of the contact's content membership.

\


\{{Conversations visitor email\}}

A Conversations visitor's email address.

\


\{{Count of unengaged contacts\}}

if contact is assigned and unworked, set to 1. if contact is assigned and worked, set to 0.

\


\{{Count of engaged contacts\}}

if contact is assigned and worked, set to 1. if contact is assigned and unworked, set to 0.

\


\{{Created By Conversations\}}

Flag indicating this contact was created by the Conversations API.

\


\{{Created by user ID\}}

The user that created this object. This value is automatically set by HubSpot and may not be modified.

\


\{{Object create date/time\}}

The date and time at which this object was created. This value is automatically set by HubSpot and may not be modified.

\


\{{Ads Consent from Forms\}}

This property captures ads consents from forms and is used by consent manager to create / update associated data privacy consent objects.

\


\{{Date entered 'Customer (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Evangelist (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Marketing Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Opportunity (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Other (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Sales Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Subscriber (Lifecycle Stage Pipeline)'\}}

The date and time when the contact entered the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Customer (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Evangelist (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Marketing Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Opportunity (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Other (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Sales Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Subscriber (Lifecycle Stage Pipeline)'\}}

The date and time when the contact exited the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Recent Document Revisit Date\}}

The last time a shared document (presentation) was accessed by this contact.

\


\{{Invalid email address\}}

The email address associated with this contact is invalid.

\


\{{Email address quarantine reason\}}

The reason why the email address has been quarantined.

\


\{{Email Domain\}}

A contact's email address domain.

\


\{{Email hard bounce reason\}}

The issue that caused a contact to hard bounce from your emails. If this is an error or a temporary issue, you can unbounce this contact from the contact record.

\


\{{Email hard bounce reason\}}

The issue that caused a contact to hard bounce from your emails. If this is an error or a temporary issue, you can unbounce this contact from the contact record.

\


\{{Email Address Quarantined\}}

Indicates that the current email address has been quarantined for anti-abuse reasons and any marketing email sends to it will be blocked. This is automatically set by HubSpot.

\


\{{Email address automated quarantine reason\}}

The automated reason why the email address has been quarantined.

\


\{{Email Address Recipient Fatigue Next Available Sending Time\}}

When this recipient has reached the limit of email sends per time period, this property indicates the next available time to send. This is automatically set by HubSpot.

\


\{{Sends Since Last Engagement\}}

The number of marketing emails that have been sent to the current email address since the last engagement (open or link click). This is automatically set by HubSpot.

\


\{{Marketing email confirmation status\}}

The status of a contact's eligibility to receive marketing email. This is automatically set by HubSpot.

\


\{{Clicked Facebook ad\}}

Whether contact has clicked a Facebook ad.

\


\{{Facebook click id\}}

\


\{{Facebook ID\}}

A contact's facebook id.

\


\{{Last NPS survey comment\}}

Last NPS survey comment that this contact gave.

\


\{{Last NPS survey rating\}}

Last NPS survey rating that this contact gave.

\


\{{Last NPS survey date\}}

The time that this contact last submitted a NPS survey response. This is automatically set by HubSpot.\
\


\{{Should be shown an NPS web survey\}}

Whether or not a contact should be shown an NPS web survey. This is automatically set by HubSpot.

\


\{{ID of first engagement\}}

The object id of the current contact owner's first engagement with the contact.

\


\{{First outreach date\}}

The date of the first outreach (call, email, meeting or other communication) from a sales rep to the contact.

\


\{{First subscription create date\}}

The create date of the first subscription by the contact.

\


\{{Google ad click id\}}

\


\{{googleplus ID\}}

A contact's googleplus id.

\


\{{Contact has an active subscription\}}

The rollup property value is 1 when the contact has an active Subscription or 0 otherwise.

\


\{{IP Timezone\}}

The timezone reported by a contact's IP address. This is automatically set by HubSpot and can be used for segmentation and reporting.

\


\{{Is a contact\}}

Is a contact, has not been deleted and is not a visitor.

\


\{{Contact unworked\}}

Contact has not been assigned or has not been engaged after last owner assignment/re-assignment.

\


\{{last sales activity date old\}}

The date of the last sales activity with the contact. This property is set automatically by HubSpot. Note: This field is only updated for contacts with an owner.

\


\{{Last Engagement Date\}}

The last time a contact engaged with your site or a form, document, meetings link, or tracked email. This doesn't include marketing emails or emails to multiple contacts.

\


\{{Last Engagement Type\}}

The type of the last engagement a contact performed. This doesn't include marketing emails or emails to multiple contacts.

\


\{{Object last modified date/time\}}

Most recent timestamp of any property update for this contact. This includes HubSpot internal properties, which can be visible or hidden. This property is updated automatically.\
\


\{{Latest Disqualified Lead Date\}}

The most recent time at which an associated lead currently in a disqualified stage was moved to that stage.

\


\{{Latest Open Lead Date\}}

The most recent time an associated open lead was moved to a NEW or IN\_PROGRESS state.

\


\{{Latest Qualified Lead Date\}}

The most recent time at which an associated lead currently in a qualified stage was moved to that stage.

\


\{{Last sequence ended date\}}

The last sequence ended date.

\


\{{Last sequence enrolled\}}

The last sequence enrolled.

\


\{{Last sequence enrolled date\}}

The last sequence enrolled date.

\


\{{Last sequence finished date\}}

The last sequence finished date.

\


\{{Last sequence unenrolled date\}}

The last sequence unenrolled date.

\


\{{Latest Source Date\}}

The time of the latest session for a contact.

\


\{{Latest subscription create date\}}

The create date of the latest subscription by the contact.

\


\{{Lead Status\}}

The contact's sales, prospecting or outreach status.

\


\{{Legal basis for processing contact's data\}}

Legal basis for processing contact's data; 'Not applicable' will exempt the contact from GDPR protections.

\


\{{Clicked LinkedIn Ad\}}

\


\{{LinkedIn ID\}}

A contact's LinkedIn id.

\


\{{Marketing contact status source name\}}

The ID of the activity that set the contact as a marketing contact.

\


\{{Marketing contact status source type\}}

The type of the activity that set the contact as a marketing contact.

\


\{{Marketing contact status\}}

The marketing status of a contact.

\


\{{Marketing contact until next update\}}

Specifies if this contact will be set as non-marketing on renewal.

\


\{{Merged Contact IDs\}}

The list of Contact record IDs that have been merged into this Contact. This value is automatically set by HubSpot and may not be modified.

\


\{{Record ID\}}

The unique ID for this record. This value is automatically set by HubSpot and may not be modified.

\


\{{Record Creation Source\}}

Source (PropertySource) that created this object record.

\


\{{Record Creation Source ID\}}

The sourceId -- further detail -- of the source that created this object record.

\


\{{Record Source\}}

How this record was created.

\


\{{Record Creation Source User ID\}}

User ID of the user who initiated creation of this object record.

\


\{{Pinned engagement ID\}}

\


\{{Pipeline\}}

The pipeline with which this contact is currently associated.

\


\{{Likelihood to close\}}

The probability that a contact will become a customer within the next 90 days. This score is based on standard contact properties and behavior.

\


\{{Contact priority\}}

A ranking system of contacts evenly assigned into four tiers. Contacts in tier one are more likely to become customers than contacts in tier four.

\


\{{Read Only Object\}}

Is the object read only.

\


\{{Date of first engagement\}}

The date the current contact owner first engaged with the contact.

\


\{{Description of first engagement\}}

A description of the current contact owner's first engagement with the contact.

\
\


\{{Type of first engagement\}}

The object type of the current contact owner's first engagement with the contact.

\


\{{Recent Sales Email Clicked Date\}}

The last time a tracked sales email was clicked by this user.

\


\{{Recent Sales Email Opened Date\}}

The last time a tracked sales email was opened by this contact. This property does not update for emails that were sent to more than one contact.

\


\{{Calculated Mobile Number with country code\}}

Mobile number with country code.

\


\{{Calculated Phone Number with country code\}}

Phone number with country code.

\


\{{Calculated Mobile Number without country code\}}

Mobile number without country code.

\


\{{Calculated Phone Number without country code\}}

Phone number without country code.

\


\{{Number of sequences actively enrolled\}}

The number of sequences actively enrolled.

\


\{{Number of sequences enrolled\}}

The number of sequences enrolled.

\


\{{Currently in Sequence\}}

A yes/no field that indicates whether the contact is currently in a Sequence.

\


\{{Source Object ID\}}

The ID of the object from which the data was migrated. This is set automatically during portal data migration.

\


\{{Source Portal ID\}}

The ID of the portal from which the data was migrated. This is set automatically during portal data migration.

\


\{{testpurge\}}

Testing purge.

\


\{{testrollback\}}

Testing rollback.

\


\{{Time between contact creation and deal close\}}

\


\{{Time between contact creation and deal creation\}}

\
\


\{{Time in 'Customer (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Evangelist (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Lead (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Marketing Qualified Lead (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Opportunity (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Other (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Sales Qualified Lead (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Subscriber (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the contact in the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Lead response time\}}

Time it took current owner to do first qualifying engagement.

\


\{{Time to move from lead to customer\}}

How long it takes for a contact to move from the HubSpot lead stage to the HubSpot customer stage.

\


\{{Time to move from marketing qualified lead to customer\}}

How long it takes for a contact to move from the HubSpot marketing qualified lead stage to the HubSpot customer stage.

\


\{{Time to move from opportunity to customer\}}

How long it takes for a contact to move from the HubSpot opportunity stage to the HubSpot customer stage.

\


\{{Time to move from sales qualified lead to customer\}}

How long it takes for a contact to move from the HubSpot sales qualified lead stage to the HubSpot customer stage.





\{{Time to move from subscriber to customer\}}

How long it takes for a contact to move from the HubSpot subscriber stage to the HubSpot customer stage.

\


\{{Time Zone\}}

The contact’s time zone. This can be set automatically by HubSpot based on other contact properties. It can also be set manually for each contact.

\


\{{Twitter ID\}}

A contact's twitter id.

\


\{{Unique creation key\}}

Unique property used for idempotent creates.

\


\{{Updated by user ID\}}

The user that last updated this object. This value is automatically set by HubSpot and may not be modified.

\


\{{User IDs of all notification followers\}}

The user IDs of all users that have clicked follow within the object to opt-in to getting follow notifications.

\


\{{User IDs of all notification unfollowers\}}

The user IDs of all object owners that have clicked unfollow within the object to opt-out of getting follow notifications.

\


\{{User IDs of all owners\}}

The user IDs of all owners of this object.

\


\{{Cumulative time in "Customer (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Cumulative time in "Evangelist (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Cumulative time in "Lead (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Cumulative time in "Marketing Qualified Lead (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Cumulative time in "Opportunity (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Cumulative time in "Other (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Cumulative time in "Sales Qualified Lead (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Cumulative time in "Subscriber (Lifecycle Stage Pipeline)"\}}

The cumulative time in seconds spent by the contact in the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Customer (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Evangelist (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Lead (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Marketing Qualified Lead (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Opportunity (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Other (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Sales Qualified Lead (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered "Subscriber (Lifecycle Stage Pipeline)"\}}

The date and time when the contact entered the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited "Customer (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\
\


\{{Date exited "Evangelist (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited "Lead (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited "Marketing Qualified Lead (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited "Opportunity (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited "Other (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited "Sales Qualified Lead (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited "Subscriber (Lifecycle Stage Pipeline)"\}}

The date and time when the contact exited the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Latest time in "Customer (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.

\


\{{Latest time in "Evangelist (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.

\


\{{Latest time in "Lead (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.

\


\{{Latest time in "Marketing Qualified Lead (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.

\


\{{Latest time in "Opportunity (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.\
\
\


\{{Latest time in "Other (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.

\


\{{Latest time in "Sales Qualified Lead (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.

\


\{{Latest time in "Subscriber (Lifecycle Stage Pipeline)"\}}

The total time in seconds spent by the contact in the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline since it last entered this stage.

\


\{{Performed in an import\}}

Object is part of an import.

\


\{{WhatsApp Phone Number\}}

The phone number associated with the contact’s WhatsApp account.

\


\{{Owner Assigned Date\}}

The most recent date a HubSpot Owner was assigned to a contact. This is set automatically by HubSpot and can be used for segmentation and reporting.

\


\{{IP City\}}

The city reported by a contact's IP address. This is automatically set by HubSpot and can be used for segmentation and reporting.

\


\{{IP Country\}}

The country reported by a contact's IP address. This is automatically set by HubSpot and can be used for segmentation and reporting.

\


\{{IP Country Code\}}

The country code reported by a contact's IP address. This is automatically set by HubSpot and can be used for segmentation and reporting.

\


\{{IP Latitude & Longitude\}}

\


\{{IP State/Region\}}

The state or region reported by a contact's IP address. This is automatically set by HubSpot and can be used for segmentation and reporting.

\


\{{IP State Code/Region Code\}}

The state code or region code reported by a contact's IP address. This is automatically set by HubSpot and can be used for segmentation and reporting.

\


\{{IP Zipcode\}}

The zipcode reported by a contact's IP address. This is automatically set by HubSpot and can be used for segmentation and reporting.\
\


\{{Job function\}}

Contact's job function. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Last Modified Date\}}

The date any property on this contact was modified.

\


\{{Marital Status\}}

Contact's marital status. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Military status\}}

Contact's military status. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Number of Associated Deals\}}

Count of deals associated with this contact. Set automatically by HubSpot.

\


\{{Number of Form Submissions\}}

The number of forms this contact has submitted.

\


\{{Number of Unique Forms Submitted\}}

The number of different forms this contact has submitted.

\


\{{Recent Conversion Date\}}

The date this contact last submitted a form.

\


\{{Recent Conversion\}}

The last form this contact submitted.

\


\{{Recent Deal Amount\}}

Amount of last closed won deal associated with a contact. Set automatically.

\


\{{Recent Deal Close Date\}}

Date last deal associated with contact was closed-won. Set automatically.

\


\{{Relationship Status\}}

Contact's relationship status. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{School\}}

Contact's school. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Seniority\}}

Contact's seniority. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\
\


\{{Start date\}}

Contact's start date. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{Total Revenue\}}

Sum of all closed-won deal revenue associated with the contact. Set automatically.

\


\{{Work email\}}

Contact's work email. Required for the Facebook Ads Integration. Automatically synced from the Lead Ads tool.

\


\{{First Name\}}

A contact's first name.

\


\{{First Page Seen\}}

First page the contact visited on your website. Set automatically.

\


\{{Marketing emails delivered\}}

The number of marketing emails delivered for the current email address. This is automatically set by HubSpot.

\


\{{Opted out of email: Marketing Information\}}

Indicates that the current email address has opted out of this email type.

\


\{{Opted out of email: One to One\}}

Indicates that the current email address has opted out of this email type.

\


\{{Opted out of email: Customer Service Communication\}}

Indicates that the current email address has opted out of this email type.

\


\{{Twitter Username\}}

The contact's Twitter handle.

\


\{{Currently in workflow\}}

True when contact is enrolled in a workflow.

\


\{{Follower Count\}}

The number of Twitter followers a contact has.

\


\{{Last Page Seen\}}

Last page the contact visited on your website. Set automatically.

\


\{{Marketing emails opened\}}

The number of marketing emails opened for the current email address. This is automatically set by HubSpot.

\


\{{Last Name\}}

A contact's last name.

\
\


\{{Number of Pageviews\}}

Total number of page views this contact has had on your website. Set automatically.

\


\{{Marketing emails clicked\}}

The number of marketing emails which have had link clicks for the current email address. This is automatically set by HubSpot.

\


\{{Salutation\}}

The title used to address a contact.

\


\{{Twitter Profile Photo\}}

The contact's Twitter profile photo. This is set by HubSpot using the contact's email address.

\


\{{Email\}}

A contact's email address.

\


\{{Number of Sessions\}}

Number of times a contact has come to your website. Set automatically.

\


\{{Marketing emails bounced\}}

The number of marketing emails that bounced for the current email address. This is automatically set by HubSpot.

\


\{{Persona\}}

A contact's persona.

\


\{{Most Recent Social Click\}}

The date of the most recent click on a published social message. This is set automatically by HubSpot for each contact.

\


\{{Number of event completions\}}

Total number of events for this contact. Set automatically.

\


\{{Unsubscribed from all email\}}

Indicates that the current email address has opted out of all email.

\


\{{Twitter Clicks\}}

The number of times a contact clicked on links you shared on Twitter through HubSpot. This is set automatically by HubSpot and can be used for segmentation.

\


\{{Mobile Phone Number\}}

A contact's mobile phone number.

\


\{{Phone Number\}}

A contact's primary phone number.

\


\{{Fax Number\}}

A contact's primary fax number.

\


\{{Time First Seen\}}

First time the contact has been seen. Set automatically.

\


\{{Last marketing email name\}}

The name of the last marketing email sent to the current email address. This is automatically set by HubSpot.

\


\{{Last marketing email send date\}}

The date of the most recent delivery for any marketing email to the current email address. This is automatically set by HubSpot.

\


\{{Facebook Clicks\}}

The number clicks on links shared on Facebook.

\


\{{Street Address\}}

Contact's street address, including apartment or unit number.

\


\{{Date of last meeting booked in meetings tool\}}

The date of the last meeting that has been scheduled by a contact through the meetings tool. If multiple meetings have been scheduled, the date of the last chronological meeting in the timeline is shown.

\


\{{Campaign of last booking in meetings tool\}}

UTM parameter for marketing campaign (e.g. a specific email) responsible for recent meeting booking. Only populated when tracking parameters are included in the meeting link.

\


\{{Medium of last booking in meetings tool\}}

UTM parameter for the channel (e.g. email) responsible for most recent meeting booking. Only populated when tracking parameters are included in the meeting link.

\


\{{Source of last booking in meetings tool\}}

UTM parameter for the site (e.g. Twitter) responsible for most recent meeting booking. Only populated when tracking parameters are included in the meeting link.

\


\{{Time of First Session\}}

First time the contact visited your website. Set automatically.

\


\{{Last marketing email open date\}}

The date of the most recent open for any marketing email to the current email address. This is automatically set by HubSpot.

\


\{{Latest meeting activity\}}

The date of the most recent meeting (past or upcoming) logged for, scheduled with, or booked by this contact.

\


\{{Recent Sales Email Replied Date\}}

The last time a tracked sales email was replied to by this user. This is set automatically by HubSpot based on user actions in the contact record.

\


\{{LinkedIn Clicks\}}

The number clicks on links shared on LinkedIn.

\


\{{Contact owner\}}

The owner of a contact. This can be any HubSpot user or Salesforce integration user, and can be set manually or via Workflows.

\


\{{Last Contacted\}}

The last time a call, chat conversation, LinkedIn message, postal mail, meeting, sales email, SMS, or WhatsApp message was logged for a contact. This is set automatically by HubSpot based on user actions in the contact record.

\


\{{Last Activity Date\}}

The last time a call, chat conversation, LinkedIn message, postal mail, meeting, note, sales email, SMS, or WhatsApp message was logged for a contact. This is set automatically by HubSpot based on user actions in the contact record.

\


\{{Next Activity Date\}}

The date of the next upcoming activity for a contact. This is set automatically by HubSpot based on user actions in the contact record.

\


\{{Number of times contacted\}}

The number of times a call, chat conversation, LinkedIn message, postal mail, meeting, sales email, SMS, or WhatsApp message was logged for a contact record. This is set automatically by HubSpot based on user actions in the contact record.

\


\{{Number of Sales Activities\}}

The number of times a call, chat conversation, LinkedIn message, postal mail, meeting, note, sales email, SMS, task, or WhatsApp message was logged for a contact record. This is set automatically by HubSpot based on user actions in the contact record.

\


\{{HubSpot Owner Email (legacy)\}}

A legacy property used to identify the email address of the owner of the contact. This property is no longer in use.

\


\{{HubSpot Owner Name (legacy)\}}

A legacy property used to identify the name of the owner of the contact. This property is no longer in use.

\


\{{SurveyMonkey Event Last Updated\}}

This field is meaningless on its own, and is solely used for triggering dynamic list updates when SurveyMonkey information is updated.

\


\{{Webinar Event Last Updated\}}

This field is meaningless on its own, and is solely used for triggering dynamic list updates when webinar information is updated.

\


\{{City\}}

A contact's city of residence.

\


\{{Time Last Seen\}}

Timestamp for the most recent webpage view on your website.

\


\{{Last marketing email click date\}}

The date of the most recent link click for any marketing email to the current email address. This is automatically set by HubSpot.

\


\{{Google Plus Clicks\}}

The number clicks on links shared on Google Plus.

\


\{{HubSpot Team\}}

The team of the owner of a contact.

\


\{{LinkedIn Bio\}}

A contact's LinkedIn bio.

\


\{{Twitter Bio\}}

The contact's Twitter bio. This is set by HubSpot using the contact's email address.

\


\{{All owner ids\}}

The value of all owner referencing properties for this object, both default and custom.

\


\{{Time of Last Session\}}

Timestamp for the start of the most recent session for this contact to your website.

\


\{{First marketing email send date\}}

The date of the earliest delivery for any marketing email to the current email address. This is automatically set by HubSpot.

\


\{{Broadcast Clicks\}}

The number of clicks on published social messages. This is set automatically by HubSpot for each contact.

\


\{{State/Region\}}

The contact's state of residence. This might be set via import, form, or integration.

\


\{{All team ids\}}

The team ids corresponding to all owner referencing properties for this object, both default and custom.

\


\{{Original Source\}}

First known source the contact used to find your website. Set automatically, but may be updated manually.

\


\{{First marketing email open date\}}

The date of the earliest open for any marketing email to the current email address. This is automatically set by HubSpot.





\{{Latest Source\}}

The source of the latest session for a contact.

\


\{{Postal Code\}}

The contact's zip code. This might be set via import, form, or integration.

\


\{{Country/Region\}}

The contact's country/region of residence. This might be set via import, form, or integration.

\


\{{All teams\}}

The team ids, including up the team hierarchy, corresponding to all owner referencing properties for this object, both default and custom.

\


\{{Original Source Drill-Down 1\}}

Additional information about the source the contact used to find your website. Set automatically.

\


\{{First marketing email click date\}}

The date of the earliest link click for any marketing email to the current email address. This is automatically set by HubSpot.

\


\{{Latest Source Drill-Down 1\}}

Additional information about the latest source for the last session the contact used to find your website. Set automatically.

\


\{{LinkedIn Connections\}}

How many LinkedIn connections they have.

\


\{{Original Source Drill-Down 2\}}

Additional information about the source the contact used to find your website. Set automatically.

\


\{{Is globally ineligible\}}

Indicates the contact is globally ineligible for email.

\


\{{Preferred language\}}

Set your contact's preferred language for communications. This property can be changed from an import, form, or integration.

\


\{{Latest Source Drill-Down 2\}}

Additional information about the source for the last session the contact used to find your website. Set automatically.

\


\{{Klout Score\}}

A contact's Klout score, a measure of Internet influence.

\


\{{First Referring Site\}}

URL that referred the contact to your website. Set automatically.

\


\{{First marketing email reply date\}}

The date of the earliest reply for any marketing email to the current email address. This is automatically set by HubSpot.

\


\{{Job Title\}}

A contact's job title.

\


\{{Photo\}}

Social Media photo.

\


\{{Last Referring Site\}}

Last URL that referred contact to your website. Set automatically.

\


\{{Last marketing email reply date\}}

The date of the latest reply for any marketing email to the current email address. This is automatically set by HubSpot.

\


\{{Message\}}

A default property to be used for any message or comments a contact may want to leave on a form.

\


\{{Close Date\}}

Date the contact became a customer. Set automatically when a deal or opportunity is marked as closed-won. It can also be set manually or programmatically.

\


\{{Average Pageviews\}}

Average number of pageviews per session for this contact. Set automatically.

\


\{{Marketing emails replied\}}

The number of marketing emails replied to by the current email address. This is automatically set by HubSpot.

\


\{{Event Revenue\}}

Set event revenue on a contact though the Enterprise Events feature. http://help.hubspot.com/articles/KCS\_Article/Reports/How-do-I-create-Events-in-HubSpot

\


\{{Became a Lead Date\}}

The date when a contact's lifecycle stage changed to Lead. This is automatically set by HubSpot for each contact.

\


\{{Became a Marketing Qualified Lead Date\}}

The date when a contact's lifecycle stage changed to MQL. This is automatically set by HubSpot for each contact.

\


\{{Became an Opportunity Date\}}

The date when a contact's lifecycle stage changed to Opportunity. This is automatically set by HubSpot for each contact.

\
\


\{{Lifecycle Stage\}}

The qualification of contacts to sales readiness. It can be set through imports, forms, workflows, and manually on a per contact basis.

\


\{{Became a Sales Qualified Lead Date\}}

The date when a contact's lifecycle stage changed to SQL. This is automatically set by HubSpot for each contact.

\


\{{Create Date\}}

The date that a contact entered the system.

\


\{{Became an Evangelist Date\}}

The date when a contact's lifecycle stage changed to Evangelist. This is automatically set by HubSpot for each contact.

\


\{{Became a Customer Date\}}

The date when a contact's lifecycle stage changed to Customer. This is automatically set by HubSpot for each contact.

\


\{{HubSpot Score\}}

The number that shows qualification of contacts to sales readiness. It can be set in HubSpot's Lead Scoring app.

\


\{{Company Name\}}

Name of the contact's company. This can be set independently from the name property on the contact's associated company.

\


\{{Became a Subscriber Date\}}

The date when a contact's lifecycle stage changed to Subscriber. This is automatically set by HubSpot for each contact.

\
\


\{{Became an Other Lifecycle Date\}}

The date when a contact's lifecycle stage changed to Other. This is automatically set by HubSpot for each contact.

\


\{{Website URL\}}

Associated company website.

\


\{{Number of Employees\}}

The number of company employees.

\


\{{Annual Revenue\}}

Annual company revenue.

\


\{{Industry\}}

The Industry a contact is in.

\


\{{Primary Associated Company ID\}}

HubSpot defines the ID of a contact's primary associated company in HubSpot.

\


\{{Associated Company Last Updated\}}

This field is meaningless on its own, and is solely used for triggering dynamic list updates when a company is updated.

\


\{{Lead Rating\}}

The rating of this contact based on their predictive lead score.

\


\{{Predictive Lead Score\}}

A score calculated by HubSpot that represents a contact's likelihood to.

</details>

<details>

<summary>Companies</summary>

\{{About Us\}}

Short about-company.

\


\{{closedate\_timestamp\_earliest\_value\_a2a17e6e\}}

Calculation context property providing timestamp for rollup property close date calculated as EARLIEST\_VALUE via values of closedate on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Facebook Fans\}}

Number of facebook fans.

\


\{{first\_contact\_createdate\_timestamp\_earliest\_value\_78b50eea\}}

Calculation context property providing timestamp for rollup property first\_contact\_createdate calculated as EARLIEST\_VALUE via values of createdate on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{First Conversion Date\}}

The first conversion date across all contacts associated this company or organization.

\


\{{first\_conversion\_date\_timestamp\_earliest\_value\_61f58f2c\}}

Calculation context property providing timestamp for rollup property first\_conversion\_date calculated as EARLIEST\_VALUE via values of first\_conversion\_date on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{First Conversion\}}

The first form submitted across all contacts associated this company or organization.

\


\{{first\_conversion\_event\_name\_timestamp\_earliest\_value\_68ddae0a\}}

Calculation context property providing timestamp for rollup property first\_conversion\_event\_name calculated as EARLIEST\_VALUE via values of first\_conversion\_event\_name on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{First Deal Created Date\}}

Date the first deal was associated with this company record.

\


\{{Year Founded\}}

The year the company was created. Powered by HubSpot Insights.

\


\{{Additional Domains\}}

Additional domains belonging to this company.

\


\{{Business units\}}

The business units this record is assigned to.

\


\{{Time First Seen\}}

The first activity for any contact associated with this company or organization.

\


\{{hs\_analytics\_first\_timestamp\_timestamp\_earliest\_value\_11e3a63a\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_first\_timestamp calculated as EARLIEST\_VALUE via values of hs\_analytics\_first\_timestamp on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{First Touch Converting Campaign\}}

The campaign responsible for the first touch creation of the first contact associated with this company.

\


\{{hs\_analytics\_first\_touch\_converting\_campaign\_timestamp\_earliest\_value\_4757fe10\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_first\_touch\_converting\_campaign calculated as EARLIEST\_VALUE via values of hs\_analytics\_first\_touch\_converting\_campaign on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Time of First Session\}}

Time of first session across all contacts associated with this company or organization.

\


\{{hs\_analytics\_first\_visit\_timestamp\_timestamp\_earliest\_value\_accc17ae\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_first\_visit\_timestamp calculated as EARLIEST\_VALUE via values of hs\_analytics\_first\_visit\_timestamp on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Time Last Seen\}}

Time last seen across all contacts associated with this company or organization.

\


\{{hs\_analytics\_last\_timestamp\_timestamp\_latest\_value\_4e16365a\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_last\_timestamp calculated as LATEST\_VALUE via values of hs\_analytics\_last\_timestamp on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Last Touch Converting Campaign\}}

The campaign responsible for the last touch creation of the first contact associated with this company.

\
\


\{{hs\_analytics\_last\_touch\_converting\_campaign\_timestamp\_latest\_value\_81a64e30\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_last\_touch\_converting\_campaign calculated as LATEST\_VALUE via values of hs\_analytics\_last\_touch\_converting\_campaign on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Time of Last Session\}}

Time of the last session attributed to any contacts that are associated with this company record.

\


\{{hs\_analytics\_last\_visit\_timestamp\_timestamp\_latest\_value\_999a0fce\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_last\_visit\_timestamp calculated as LATEST\_VALUE via values of hs\_analytics\_last\_visit\_timestamp on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Latest Source\}}

Source of the last session attributed to any contacts that are associated with this company.

\


\{{Latest Source Data 1\}}

Additional source details of the last session attributed to any contacts that are associated with this company.

\


\{{Latest Source Data 2\}}

Additional source details of the last session attributed to any contacts that are associated with this company.

\


\{{Latest Source Timestamp\}}

Timestamp of when latest source occurred.

\


\{{Number of Pageviews\}}

Total number of page views across all contacts associated with this company or organization.

\


\{{hs\_analytics\_num\_page\_views\_cardinality\_sum\_e46e85b0\}}

Calculation context property providing cardinality for rollup property hs\_analytics\_num\_page\_views calculated as SUM via values of hs\_analytics\_num\_page\_views on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Number of Sessions\}}

Total number of sessions across all contacts associated with this company or organization.

\


\{{hs\_analytics\_num\_visits\_cardinality\_sum\_53d952a6\}}

Calculation context property providing cardinality for rollup property hs\_analytics\_num\_visits calculated as SUM via values of hs\_analytics\_num\_visits on object type ObjectTypeId{legacyObjectType=CONTACT}.

\
\


\{{Original Source Type\}}

Original source for the contact with the earliest activity for this company or organization.

\


\{{Original Source Data 1\}}

Additional information about the original source for the contact with the earliest activity for this company or organization.

\


\{{hs\_analytics\_source\_data\_1\_timestamp\_earliest\_value\_9b2f1fa1\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_source\_data\_1 calculated as EARLIEST\_VALUE via values of hs\_analytics\_source\_data\_1 on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Original Source Data 2\}}

Additional information about the original source for the contact with the earliest activity for this company or organization.

\


\{{hs\_analytics\_source\_data\_2\_timestamp\_earliest\_value\_9b2f9400\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_source\_data\_2 calculated as EARLIEST\_VALUE via values of hs\_analytics\_source\_data\_2 on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{hs\_analytics\_source\_timestamp\_earliest\_value\_25a3a52c\}}

Calculation context property providing timestamp for rollup property hs\_analytics\_source calculated as EARLIEST\_VALUE via values of hs\_analytics\_source on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Annual Revenue Currency Code\}}

The currency code associated with the annual revenue amount.

\


\{{Avatar FileManager key\}}

The path in the FileManager CDN for this company's avatar override image. Automatically set by HubSpot.

\


\{{Created by user ID\}}

The user that created this object. This value is automatically set by HubSpot and may not be modified.

\


\{{Object create date/time\}}

The date and time at which this object was created. This value is automatically set by HubSpot and may not be modified.

\


\{{Date entered 'Customer (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Evangelist (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\
\


\{{Date entered 'Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Marketing Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Opportunity (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Other (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Sales Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date entered 'Subscriber (Lifecycle Stage Pipeline)'\}}

The date and time when the company entered the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Customer (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Evangelist (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Marketing Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Opportunity (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Other (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.\
\
\


\{{Date exited 'Sales Qualified Lead (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Date exited 'Subscriber (Lifecycle Stage Pipeline)'\}}

The date and time when the company exited the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Ideal Customer Profile Tier\}}

How well this company matches your Ideal Customer Profile. Tier 1 means a great fit for your products/services, Tier 3 might be acceptable, but low priority.

\


\{{Target Account\}}

Identifies whether this company is being marketed and sold to as part of your account-based strategy.

\


\{{Last Booked Meeting Date\}}

The last date of booked meetings associated with the company.

\


\{{Last Logged Call Date\}}

The last date of logged calls associated with the company.

\


\{{Last Open Task Date\}}

The last due date of open tasks associated with the company.

\


\{{last sales activity date old\}}

The date of the last sales activity with the company in seconds.

\


\{{Last Engagement Date\}}

The last time a contact engaged with your site or a form, document, meetings link, or tracked email. This doesn't include marketing emails or emails to multiple contacts.

\


\{{Last Engagement Type\}}

The type of the last engagement a company performed. This doesn't include marketing emails or emails to multiple contacts.

\


\{{Last Modified Date\}}

Most recent timestamp of any property update for this company. This includes HubSpot internal properties, which can be visible or hidden. This property is updated automatically.

\


\{{Latest create date of active subscriptions\}}

Latest created date of all associated active Subscriptions.

\


\{{Merged Company IDs\}}

The list of Company record IDs that have been merged into this Company. This value is automatically set by HubSpot and may not be modified.

\


\{{Number of blockers\}}

The number of contacts associated with this company with the role of blocker.

\


\{{Number of contacts with a buying role\}}

The number of contacts associated with this company with a buying role.

\


\{{Number of decision makers\}}

The number of contacts associated with this company with the role of decision maker.

\


\{{Number of open deals\}}

The number of open deals associated with this company.

\


\{{Record ID\}}

The unique ID for this record. This value is automatically set by HubSpot and may not be modified.

\


\{{Record Creation Source\}}

Source (PropertySource) that created this object record.

\


\{{Record Creation Source ID\}}

The sourceId -- further detail -- of the source that created this object record.

\


\{{Record Source\}}

How this record was created.

\


\{{Record Creation Source User ID\}}

User ID of the user who initiated creation of this object record.

\


\{{Pinned Engagement ID\}}

The object ID of the current pinned engagement. This value is automatically set by HubSpot and may not be modified.

\


\{{Pipeline\}}

The pipeline with which this company is currently associated.

\


\{{Likelihood to close\}}

The highest probability that a contact associated with this company will become a customer within the next 90 days. This score is based on standard contact properties and behavior.

\


\{{hs\_predictivecontactscore\_v2\_next\_max\_max\_d4e58c1e\}}

Calculation context property providing next\_max for rollup property hs\_predictivecontactscore\_v2 calculated as MAX via values of hs\_predictivecontactscore\_v2 on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Read Only Object\}}

Is the object read only.

\


\{{Source Object ID\}}

The ID of the object from which the data was migrated. This is set automatically during portal data migration.

\


\{{Target Account\}}

The Target Account property is a means to flag high priority companies if you are following an account based strategy.

\


\{{Target Account Probability\}}

The probability a company is marked as a target account.

\


\{{Target Account Recommendation Snooze Time\}}

The date when the target account recommendation is snoozed.

\


\{{Target Account Recommendation State\}}

The state of the target account recommendation.

\


\{{Time in 'Customer (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Customer' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Evangelist (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Evangelist' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Lead (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Marketing Qualified Lead (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Marketing Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Opportunity (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Opportunity' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Other (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Other' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Sales Qualified Lead (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Sales Qualified Lead' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Time in 'Subscriber (Lifecycle Stage Pipeline)'\}}

The total time in seconds spent by the company in the 'Subscriber' stage, 'Lifecycle Stage Pipeline' pipeline.

\


\{{Total open deal value\}}

The total value, in your company's currency, of all open deals associated with this company.

\


\{{Unique creation key\}}

Unique property used for idempotent creates.

\


\{{Updated by user ID\}}

The user that last updated this object. This value is automatically set by HubSpot and may not be modified.

\


\{{User IDs of all notification followers\}}

The user IDs of all users that have clicked follow within the object to opt-in to getting follow notifications.

\


\{{User IDs of all notification unfollowers\}}

The user IDs of all object owners that have clicked unfollow within the object to opt-out of getting follow notifications.

\


\{{User IDs of all owners\}}

The user IDs of all owners of this object.

\


\{{Performed in an import\}}

Object is part of an import.

\


\{{Owner Assigned Date\}}

The timestamp when an owner was assigned to this company.

\


\{{Is Public\}}

Indicates if the company is publicly traded. Powered by HubSpot Insights.

\


\{{Number of Associated Contacts\}}

The number of contacts associated with this company.

\


\{{Number of Associated Deals\}}

The number of deals associated with this company.

\


\{{Number of Form Submissions\}}

The number of forms submission for all contacts associated with this company or organization.

\


\{{num\_conversion\_events\_cardinality\_sum\_d095f14b\}}

Calculation context property providing cardinality for rollup property num\_conversion\_events calculated as SUM via values of num\_conversion\_events on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Recent Conversion Date\}}

The most recent conversion date across all contacts associated this company or organization.

\


\{{recent\_conversion\_date\_timestamp\_latest\_value\_72856da1\}}

Calculation context property providing timestamp for rollup property recent\_conversion\_date calculated as LATEST\_VALUE via values of recent\_conversion\_date on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Recent Conversion\}}

The last form submitted across all contacts associated this company or organization.

\


\{{recent\_conversion\_event\_name\_timestamp\_latest\_value\_66c820bf\}}

Calculation context property providing timestamp for rollup property recent\_conversion\_event\_name calculated as LATEST\_VALUE via values of recent\_conversion\_event\_name on object type ObjectTypeId{legacyObjectType=CONTACT}.

\


\{{Recent Deal Amount\}}

Amount of last closed won deal associated with this company. Set automatically.

\


\{{Recent Deal Close Date\}}

Date of the last "closed won" deal associated with this company record.

\


\{{Time Zone\}}

Time zone where the company or organization is located. Powered by HubSpot Insights.

\


\{{Total Money Raised\}}

The total amount of money raised by the company. Powered by HubSpot Insights.

\


\{{Total Revenue\}}

The total amount of closed won deals.

\


\{{Company name\}}

The name of the company or organization. Powered by HubSpot Insights.

\


\{{HubSpot Owner Email\}}

HubSpot owner email for this company or organization.

\


\{{Twitter Handle\}}

The main twitter account of the company or organization.

\


\{{HubSpot Owner Name\}}

HubSpot owner name for this company or organization.

\


\{{Phone Number\}}

Company primary phone number. Powered by HubSpot Insights.

\


\{{Twitter Bio\}}

The Twitter bio of the company or organization.

\


\{{Twitter Followers\}}

The number of Twitter followers of the company or organization.

\


\{{Street Address\}}

Street address of the company or organization, including unit number. Powered by HubSpot Insights.

\
\


\{{Street Address 2\}}

Additional address of the company or organization. Powered by HubSpot Insights.

\


\{{Facebook Company Page\}}

The URL of the Facebook company page for the company or organization.

\


\{{City\}}

City where the company is located. Powered by HubSpot Insights.

\


\{{LinkedIn Company Page\}}

The URL of the LinkedIn company page for the company or organization.

\


\{{LinkedIn Bio\}}

The LinkedIn bio for the company or organization.

\


\{{State/Region\}}

State or region in which the company or organization is located. Powered by HubSpot Insights.

\


\{{Google Plus Page\}}

The URL of the Google Plus page for the company or organization.

\


\{{Date of last meeting booked in meetings tool\}}

Last Meeting Booked for any contact associated with this Company/Organization.

\


\{{Campaign of last booking in meetings tool\}}

This UTM parameter shows which marketing campaign (e.g. a specific email) referred an associated contact to the meetings tool for their most recent booking. This property is only populated when you add tracking parameters to your meeting link.

\


\{{Medium of last booking in meetings tool\}}

This UTM parameter shows which channel (e.g. email) referred an associated contact to the meetings tool for their most recent booking. This property is only populated when you add tracking parameters to your meeting link.

\


\{{Source of last booking in meetings tool\}}

This UTM parameter shows which site (e.g. Twitter) referred an associated contact to the meetings tool for their most recent booking. This property is only populated when you add tracking parameters to your meeting link.

\


\{{Latest meeting activity\}}

The date of the most recent meeting (past or upcoming) logged for, scheduled with, or booked by a contact associated with this company.

\


\{{Recent Sales Email Replied Date\}}

The last time a tracked sales email was replied to by this company.

\


\{{Company owner\}}

The owner of the company.

\


\{{Last Contacted\}}

The last time a call, chat conversation, LinkedIn message, postal mail, meeting, sales email, SMS, or WhatsApp message was logged for a company. This is set automatically by HubSpot based on user actions in the company record.

\


\{{Last Activity Date\}}

The last time a call, chat conversation, LinkedIn message, postal mail, meeting, note, sales email, SMS, or WhatsApp message was logged for a company. This is set automatically by HubSpot based on user actions in the company record.

\


\{{Next Activity Date\}}

Date of the next upcoming scheduled sales activity for this company record.

\


\{{Number of times contacted\}}

The number of times a call, chat conversation, LinkedIn message, postal mail, meeting, sales email, SMS, or WhatsApp message was logged for a company record. This is set automatically by HubSpot based on user actions in the company record.

\


\{{Number of Sales Activities\}}

The number of times a call, chat conversation, LinkedIn message, postal mail, meeting, note, sales email, SMS, task, or WhatsApp message was logged for a company record. This is set automatically by HubSpot based on user actions in the company record.

\


\{{Postal Code\}}

Postal or zip code of the company or organization. Powered by HubSpot Insights.

\


\{{Country/Region\}}

Country in which the company or organization is located. Powered by HubSpot Insights.

\


\{{HubSpot Team\}}

The team of the owner of the company.

\


\{{All owner ids\}}

The value of all owner referencing properties for this object, both default and custom.

\


\{{Website URL\}}

The main website of the company or organization. This property is used to identify unique companies. Powered by HubSpot Insights.

\


\{{Company Domain Name\}}

The domain name of the company or organization.

\


\{{All team ids\}}

The team ids corresponding to all owner referencing properties for this object, both default and custom.

\


\{{All teams\}}

The team ids, including up the team hierarchy, corresponding to all owner referencing properties for this object, both default and custom.

\


\{{Number of Employees\}}

The total number of employees who work for the company or organization. Powered by HubSpot Insights.

\


\{{Industry\}}

The type of business the company performs. By default, this property has approximately 150 pre-defined options to select from. While these options cannot be deleted as they used by HubSpot Insights, you can add new custom options to meet your needs.

\


\{{Annual Revenue\}}

The actual or estimated annual revenue of the company. Powered by HubSpot Insights.

\


\{{Lifecycle Stage\}}

The qualification of companies to sales readiness throughout the buying journey.

\


\{{Lead Status\}}

The company's sales, prospecting or outreach status.

\


\{{Parent Company\}}

The parent company of this company.

\


\{{Type\}}

The optional classification of this company record - prospect, partner, etc.

\


\{{Description\}}

A short statement about the company's mission and goals. Powered by HubSpot Insights.

\


\{{Number of child companies\}}

The number of child companies of this company.

\


\{{HubSpot Score\}}

The sales and marketing score for the company or organization.

\


\{{Create Date\}}

The date the company or organization was added to the database.

\


\{{Close Date\}}

The date the company or organization was closed as a customer.

\


\{{First Contact Create Date\}}

The date that the first contact from this company entered the system, which could pre-date the company's create date.

\


\{{Days to Close\}}

The number of days between when the company record was created and when they closed as a customer.

\


\{{Web Technologies\}}

The web technologies used by the company or organization. Powered by HubSpot Insights.

</details>

<details>

<summary>Tickets</summary>

\{{Close date\}}

The date the ticket was closed.

\


\{{Created by\}}

VID of contact that created the ticket.

\


\{{Create date\}}

The date the ticket was created.

\


\{{First agent email response date\}}

The date of the first email response from an agent after a ticket was created.

\


\{{Business units\}}

The business units this record is assigned to.

\


\{{All associated contact companies\}}

All associated contact companies.

\


\{{All associated contact emails\}}

All associated contact emails.

\


\{{All associated contact first names\}}

All associated contact first names.

\


\{{All associated contact last names\}}

All associated contact last names.

\


\{{All associated contact mobile phones\}}

All associated contact mobile phones.

\


\{{All associated contact phones\}}

All associated contact phones.

\


\{{All conversation mentions\}}

All mentioned users on the associated conversations.

\


\{{Applied SLA Rule Config ID\}}

Reference to the SLA rule that was applied to this ticket.

\


\{{Assigned Teams\}}

teamIds of the ticket owner(s)’ main team(s), or if ticket owner is blank, then teamId(s) of the team(s) we attempted to assign to.

\
\


\{{Assignment Method\}}

defines how the Object Assignment is done.

\


\{{Auto-generated from thread id\}}

Thread that this ticket was automatically created for using ticket rules.

\


\{{Originating Conversations Message Id\}}

Conversations Message Id of the message that originated this ticket.

\


\{{Conversations originating thread id\}}

Thread that this ticket was originally created for.

\


\{{Created by user ID\}}

The user that created this object. This value is automatically set by HubSpot and may not be modified.

\


\{{HubSpot create date\}}

Internal read-only property representing the date the ticket was created in HubSpot.

\


\{{Custom inbox ID\}}

ID of the custom inbox the ticket is associated with.

\


\{{Date entered 'New (Support Pipeline)'\}}

The date and time when the ticket entered the 'New' stage, 'Support Pipeline' pipeline.

\


\{{Date entered 'Waiting on contact (Support Pipeline)'\}}

The date and time when the ticket entered the 'Waiting on contact' stage, 'Support Pipeline' pipeline.

\


\{{Date entered 'Waiting on us (Support Pipeline)'\}}

The date and time when the ticket entered the 'Waiting on us' stage, 'Support Pipeline' pipeline.

\


\{{Date entered 'Closed (Support Pipeline)'\}}

The date and time when the ticket entered the 'Closed' stage, 'Support Pipeline' pipeline.

\


\{{Date exited 'New (Support Pipeline)'\}}

The date and time when the ticket exited the 'New' stage, 'Support Pipeline' pipeline.

\


\{{Date exited 'Waiting on contact (Support Pipeline)'\}}

The date and time when the ticket exited the 'Waiting on contact' stage, 'Support Pipeline' pipeline.

\


\{{Date exited 'Waiting on us (Support Pipeline)'\}}

The date and time when the ticket exited the 'Waiting on us' stage, 'Support Pipeline' pipeline.

\


\{{Date exited 'Closed (Support Pipeline)'\}}

The date and time when the ticket exited the 'Closed' stage, 'Support Pipeline' pipeline.

\
\


\{{External object ids\}}

Unique ids corresponding to tickets in a system outside of HubSpot.

\


\{{Last CES survey comment\}}

Last CES survey comment that this contact gave for this ticket.

\


\{{Last CES survey rating\}}

Last CES survey rating that this contact gave for this ticket.

\


\{{Last CES survey date\}}

The time that this contact last submitted a CES survey response. This is automatically set by HubSpot.

\


\{{File upload\}}

Files attached to a support form by a contact.

\


\{{First agent response date\}}

The date of the first response from an agent out of all associated conversations.

\


\{{Helpdesk Sort Timestamp\}}

A calculated property to help with sorting in the Helpdesk.

\


\{{In Help Desk\}}

Is this Ticket rendered in the Help Desk.

\


\{{Inbox ID\}}

Inbox the ticket is in.

\


\{{Is Visible in Help desk\}}

Whether the ticket is visible in help desk.

\


\{{Last email activity\}}

The type of the last email activity with the contact associated with the ticket.

\


\{{Last email date\}}

The date of the last email activity with the contact associated with the ticket.

\


\{{Last message from visitor\}}

Whether the last message came from visitor.

\


\{{Last message received date\}}

The date of the last response from the visitor.

\


\{{Last response date\}}

The date of the last response from an agent or bot.\
\


\{{Last activity date\}}

The last time a note, call, email, meeting, or task was logged for a ticket. This is updated automatically by HubSpot.

\


\{{Last contacted date\}}

The last time a call, chat conversation, LinkedIn message, postal mail, meeting, sales email, SMS, or WhatsApp message was logged for a ticket. This is set automatically by HubSpot based on user actions in the ticket record.

\


\{{Last modified date\}}

Most recent timestamp of any property update for this ticket. This includes HubSpot internal properties, which can be visible or hidden. This property is updated automatically.

\


\{{Latest message seen by agent ids\}}

Agents who have seen the newest message across all conversations associated to the ticket.

\


\{{Merged Ticket IDs\}}

The list of Ticket record IDs that have been merged into this Ticket. This value is automatically set by HubSpot and may not be modified.

\


\{{Most relevant SLA status\}}

Most relevant sla status.

\


\{{Most Relevant SLA Type\}}

Most relevant SLA type between Close By, First Response, Next Response.

\


\{{Microsoft Teams message ID for this ticket\}}

Microsoft Teams message ID for this ticket.

\


\{{Next activity date\}}

The date of the next upcoming activity for a ticket. This property is set automatically by HubSpot based on user action. This includes logging a future call, email, or meeting using the Log feature, as well as creating a future task or scheduling a future meeting. This is updated automatically by HubSpot.

\


\{{Number of Associated Companies\}}

Number of companies associated with this ticket.

\


\{{Number of Associated Conversations\}}

Number of conversations associated to the ticket.

\


\{{Number of times contacted\}}

The number of times a call, email, or meeting was logged on the ticket.

\


\{{Record ID\}}

The unique ID for this record. This value is automatically set by HubSpot and may not be modified.

\
\


\{{Record Creation Source\}}

Source (PropertySource) that created this object record.

\


\{{Record Creation Source ID\}}

The sourceId -- further detail -- of the source that created this object record.

\


\{{Record Source\}}

How this record was created.

\


\{{Record Creation Source User ID\}}

User ID of the user who initiated creation of this object record.

\


\{{Originating channel account\}}

First channel account used when conversation was started.

\


\{{Originating email engagement id\}}

Engagement id of the email originating this ticket.

\


\{{Originating channel type\}}

The channel the conversation is in.

\


\{{Pinned Engagement ID\}}

The object ID of the current pinned engagement. This value is automatically set by HubSpot and may not be modified.

\


\{{Pipeline\}}

The pipeline that contains this ticket.

\


\{{Ticket status\}}

The pipeline stage that contains this ticket.

\


\{{Primary Company\}}

Primary company of a ticket.

\


\{{Primary Company ID\}}

Primary company ID of a ticket.

\


\{{Primary Company Name\}}

Primary company name of a ticket.

\


\{{Read Only Object\}}

Is the object read only.

\


\{{Resolution\}}

The action taken to resolve the ticket.

\


\{{Users interaction\}}

Stores a list of users who have viewed the most recent interaction on a ticket.

\
\


\{{Source Object ID\}}

The ID of the object from which the data was migrated. This is set automatically during portal data migration.

\


\{{Ticket Tags\}}

List of tag ids applicable to a ticket. This property is set automatically by HubSpot.

\


\{{Thread IDs To Restore\}}

Thread IDs (from cv-threads) used to implement custom cascading delete/restore.

\


\{{Category\}}

Main reason customer reached out for help.

\


\{{Ticket ID\}}

The unique id for this ticket. This unique id is automatically populated by HubSpot.

\


\{{Priority\}}

The level of attention needed on the ticket.

\


\{{Time in 'New (Support Pipeline)'\}}

The total time in seconds spent by the ticket in the 'New' stage, 'Support Pipeline' pipeline.

\
\


\{{Time in 'Waiting on contact (Support Pipeline)'\}}

The total time in seconds spent by the ticket in the 'Waiting on contact' stage, 'Support Pipeline' pipeline.

\


\{{Time in 'Waiting on us (Support Pipeline)'\}}

The total time in seconds spent by the ticket in the 'Waiting on us' stage, 'Support Pipeline' pipeline.

\


\{{Time in 'Closed (Support Pipeline)'\}}

The total time in seconds spent by the ticket in the 'Closed' stage, 'Support Pipeline' pipeline.

\


\{{Time to Close SLA Due Date\}}

When the ticket falls out of Time to Close SLA.

\


\{{Time to Close SLA Ticket Status\}}

Current Time to Close SLA status of ticket.

\


\{{Time to First Response SLA Due Date\}}

When the ticket falls out of the Time to First Response SLA.

\


\{{Time to First Response SLA Status\}}

Current Time to First Response SLA status.

\


\{{Time to Next Response SLA Due Date\}}

When the ticket falls out of Time to Next Response SLA.\
\


\{{Time to Next Response SLA Status\}}

Current Time to Next Response SLA status.

\


\{{Unique creation key\}}

Unique property used for idempotent creates.

\


\{{Updated by user ID\}}

The user that last updated this object. This value is automatically set by HubSpot and may not be modified.

\


\{{User IDs of all notification followers\}}

The user IDs of all users that have clicked follow within the object to opt-in to getting follow notifications.

\


\{{User IDs of all notification unfollowers\}}

The user IDs of all object owners that have clicked unfollow within the object to opt-out of getting follow notifications.

\


\{{User IDs of all owners\}}

The user IDs of all owners of this object.

\


\{{Performed in an import\}}

Object is part of an import.

\


\{{Owner assigned date\}}

The date an owner was assigned to the ticket.

\


\{{Date of last engagement\}}

The date of the last reply or note.

\


\{{Last customer reply date\}}

The date of the last customer response.

\


\{{NPS follow up\}}

Answer to NPS follow up question.

\


\{{NPS follow up question\}}

Specific version of NPS follow up question that was asked.

\


\{{Conversation NPS score\}}

NPS score received after ticket resolution.

\


\{{Reference to email thread\}}

The id of an email thread with ticket conversation.

\


\{{Time to close\}}

The time between when the ticket was created and closed.

\
\


\{{Time to first agent email reply\}}

The time from the ticket create date to the first agent email reply.

\


\{{Ticket name\}}

Short summary of ticket.

\


\{{Ticket description\}}

Description of the ticket.

\


\{{Source\}}

Channel where ticket was originally submitted.

\


\{{Reference to source-specific object\}}

The id of a connected source object.

\


\{{Tags\}}

Tags associated with your tickets.

\


\{{Recent Sales Email Replied Date\}}

The last time a tracked sales email was replied to for this ticket.

\


\{{Ticket owner\}}

User the ticket is assigned to. Assign additional users to a ticket record by creating a custom user property.

\


\{{Last Contacted (Ticket Note)\}}

The last time a call, chat conversation, LinkedIn message, postal mail, meeting, note, sales email, SMS, or WhatsApp message was logged for a ticket. This is set automatically by HubSpot based on user actions in the ticket record.

\


\{{Last Activity Date (Ticket Note)\}}

The last time a note, call, email, meeting, or task was logged for a ticket. This is set automatically by HubSpot based on user actions in the ticket record.

\


\{{Next Activity Date (Ticket Note)\}}

The date of the next upcoming activity for this ticket.

\


\{{Number of times contacted (Ticket Note)\}}

The number of times a call, email or meeting was logged for this ticket.

\


\{{Number of Sales Activities\}}

The number of times a call, chat conversation, LinkedIn message, postal mail, meeting, note, sales email, SMS, task, or WhatsApp message was logged for a ticket record. This is set automatically by HubSpot based on user actions in the ticket record.

\


\{{HubSpot team\}}

Primary team of the ticket owner. This property is set automatically by HubSpot.

\


\{{All owner ids\}}

The value of all owner referencing properties for this object, both default and custom.

\


\{{All team ids\}}

The team IDs, including up the team hierarchy, corresponding to all owner referencing properties for this object, both default and custom.

\


\{{All teams\}}

The team IDs, including up the team hierarchy, corresponding to all owner referencing properties for this object, both default and custom.

</details>

<details>

<summary>Line Items</summary>

\{{Net price\}}

The amount of a line item.

\


\{{Create Date\}}

The date the line item was created.

\


\{{Description\}}

Full description of product.

\


\{{Unit discount\}}

The discount amount applied.

\


\{{Annual contract value\}}

The annual contract value (ACV) of this product.

\


\{{All teams\}}

The team IDs, including up the team hierarchy, corresponding to all owner referencing properties for this object, both default and custom.

\


\{{Business units\}}

The business units this record is assigned to.

\


\{{All owner ids\}}

The value of all owner referencing properties for this object, both default and custom.

\


\{{All team ids\}}

The team ids corresponding to all owner referencing properties for this object, both default and custom.

\


\{{Allow buyer selected quantity\}}

Whether buyer selected quantity is to be enabled or not for a LineItem.

\


\{{Annual recurring revenue\}}

The annual recurring revenue (ARR) of this product.

\


\{{Billing Period End Date\}}

End date of a fixed billing period.





\{{Billing Period Start Date\}}

Start date of a fixed billing period.

\


\{{Delayed billing start by days\}}

Number of days billing should be delayed by. It allows the customers to start billing sometime in the future.

\


\{{Delayed billing start by months\}}

Number of months billing should be delayed by. It allows the customers to start billing sometime in the future.

\


\{{Start billing terms\}}

The type of billing start delay. It can be a fixed date in the future, relative delay in number of days or months.

\


\{{Unit cost\}}

The amount that sold goods cost the HubSpot customer.

\


\{{Created by user ID\}}

The user that created this object. This value is automatically set by HubSpot and may not be modified.

\


\{{Object create date/time\}}

The date and time at which this object was created. This value is automatically set by HubSpot and may not be modified.

\


\{{Discount Percentage\}}

The discount percentage applied.

\


\{{External LineItem id\}}

The ID of a line item.

\


\{{Image URL\}}

Product images.

\


\{{Last Modified Date\}}

The date any property on this product was modified.

\


\{{Currency\}}

Currency code for the line item.

\


\{{Margin\}}

The margin value of this product.

\


\{{Annual contract value margin\}}

The margin annual contract value of this product.

\


\{{Annual recurring revenue margin\}}

The margin annual recurring revenue of this product.

\


\{{Monthly recurring revenue margin\}}

The margin monthly recurring revenue of this product.

\


\{{Total contract value margin\}}

The margin total contract value of this product.

\


\{{Merged record IDs\}}

The list of record IDs that have been merged into this record. This value is automatically set by HubSpot and may not be modified.

\


\{{Monthly recurring revenue\}}





\{{The monthly recurring revenue (MRR) of this product\}}

\


\{{Record ID\}}

The unique ID for this record. This value is automatically set by HubSpot and may not be modified.

\


\{{Record Creation Source\}}

Source (PropertySource) that created this object record.

\


\{{Record Creation Source ID\}}

The sourceId -- further detail -- of the source that created this object record.

\


\{{Record Source\}}

How this record was created.

\


\{{Record Creation Source User ID\}}

User ID of the user who initiated creation of this object record.

\


\{{Position on quote\}}

The order which the line item appears on the quotes.

\


\{{Net Price after tax\}}

Amount of line item after applying tax.

\


\{{Pre Discount Amount\}}

The pre-discount amount of a line item.

\


\{{Product ID\}}

ID of the product this was copied from.

\


\{{Product Type\}}

The type of product. By default, categorize your product as either Inventory, Non-Inventory or Service.

\


\{{Read Only Object\}}

Is the object read only.\
\
\


\{{Billing end date\}}

Recurring billing end date for a line item.

\


\{{Number of payments\}}

Number of payments for the given period on a Line Item.

\


\{{Term\}}

Product recurring billing duration.

\


\{{Billing start date\}}

Recurring billing start date for a line item.

\


\{{Billing terms\}}

If there are fixed number payments or it goes on until cancelled.

\


\{{SKU\}}

Unique product identifier.

\


\{{Sync amount\}}

The amount set by Ecommerce sync.

\


\{{Tax Amount\}}

Amount of tax calculated based on tax rate for this line item.

\


\{{Tax Rate\}}

Represents tax rate as percent out of 100. Supports up to 4 decimal places.

\


\{{Tax Type\}}

Describes the type of the tax applied on a LI. For example VAT, Tax, GST.

\


\{{Total contract value\}}

The total contract value (TCV) of this product.

\


\{{Term in months\}}

The number of months in the term of this product.

\


\{{Calculated Total Discount\}}

Calculated total Discount for the line item taking in consideration the flat amount and discount percentage.

\


\{{Unique creation key\}}

Unique property used for idempotent creates.

\


\{{Updated by user ID\}}

The user that last updated this object. This value is automatically set by HubSpot and may not be modified.

\


\{{URL\}}

Product url.

\


\{{User IDs of all notification followers\}}

The user IDs of all users that have clicked follow within the object to opt-in to getting follow notifications.

\


\{{User IDs of all notification unfollowers\}}

The user IDs of all object owners that have clicked unfollow within the object to opt-out of getting follow notifications.

\


\{{User IDs of all owners\}}

The user IDs of all owners of this object.

\


\{{Variant id of the product\}}

Variant id of the shopify product.

\


\{{Performed in an import\}}

Object is part of an import.

\


\{{Owner Assigned Date\}}

The most recent date an owner was assigned to this object. This is set automatically by HubSpot and can be used for segmentation and reporting.

\


\{{Owner\}}

The owner of the object.

\


\{{HubSpot Team\}}

The primary team of the owner.

\


\{{Name\}}

Product name.

\


\{{Unit price\}}

Cost of product.

\


\{{Quantity\}}

How many units of a product are in this line item.

\


\{{Billing frequency\}}

How often a line item with recurring billing is billed. It informs the pricing calculation for deals and quotes. Line items with one-time billing aren’t included.

\


\{{Tax\}}

The tax amount applied.

</details>

<details>

<summary>Meetings</summary>

\{{Call and meeting type\}}

The activity type of the engagement.





\{{Business units\}}

The business units this record is assigned to.

\


\{{At-Mentioned Owner Ids\}}

The owners that have been at-mentioned on the engagement.

\


\{{Attached file IDs\}}

The IDs of the files that are attached to the engagement.

\


\{{HubSpot attendee owner IDs\}}

List of HubSpot owner IDs for additional attendees.

\


\{{Body preview\}}

A truncated preview of the engagement body.

\


\{{HTML Body Preview\}}

The HTML representation of the engagement body preview.

\


\{{Body Preview Truncated\}}

Indicates if the engagement body was truncated for the preview.

\


\{{Contact first outreach date\}}

The first outreach date of the associated contact.

\


\{{Activity created by\}}

The user who created the engagement.

\


\{{Created by user ID\}}

The user that created this object. This value is automatically set by HubSpot and may not be modified.

\


\{{Create date\}}

The date that an engagement was created.

\


\{{Engagement Source\}}

The source that created this engagement.

\


\{{Engagement Source ID\}}

The specific ID of the process that created this engagement.

\


\{{Follow up action\}}

What action should be performed during follow up.

\


\{{GDPR deleted\}}

Indicates the body of this engagement has been cleared because of a GDPR delete request.

\


\{{Guest Emails\}}

Guest emails on a meeting booking.\
\


\{{iCalUid\}}

The iCalUid of the synced event.

\


\{{Should include description in reminder\}}

Indicates whether or not the prospect reminders should include the meeting description.

\


\{{Internal Meeting Notes\}}

The internal notes from the meeting.

\


\{{Last modified date\}}

The date any property on this engagement was modified.

\


\{{Meeting description\}}

The text description of the meeting.

\


\{{Meeting calendar event hash\}}

The unique hash for the meeting.

\


\{{Meeting change id\}}

The unique change id for the meeting.

\


\{{Created From Link ID\}}

Created From Link ID.

\


\{{Meeting end time\}}

The date when the meeting ends.

\


\{{External URL\}}

The external URL for the meeting.

\


\{{Meeting location\}}

Where the meeting takes place.

\


\{{Location type\}}

The type of location for the meeting event.

\


\{{Meeting outcome\}}

The outcome of this meeting.

\


\{{Payments session id\}}

The payments session id for the meeting.

\


\{{Pre-meeting prospect reminders\}}

A list of dates when meeting reminders should be sent to prospects.

\


\{{Meeting source\}}

The source where the meeting was booked.

\


\{{Source ID\}}

The source ID of the meeting.

\
\


\{{Meeting start time\}}

The date when the meeting starts.

\


\{{Meeting name\}}

The title of the meeting.

\


\{{Web conference meeting ID\}}

The meeting ID of the web conference.

\


\{{Merged record IDs\}}

The list of record IDs that have been merged into this record. This value is automatically set by HubSpot and may not be modified.

\


\{{Updated by\}}

The user who last updated the engagement.

\


\{{Record ID\}}

The unique ID for this record. This value is automatically set by HubSpot and may not be modified.

\


\{{Record Creation Source\}}

Source (PropertySource) that created this object record.

\


\{{Record Creation Source ID\}}

The sourceId -- further detail -- of the source that created this object record.

\


\{{Record Source\}}

How this record was created.

\


\{{Record Creation Source User ID\}}

User ID of the user who initiated creation of this object record.

\


\{{Outcome canceled count\}}

1 if outcome is canceled otherwise 0.

\


\{{Outcome completed count\}}

1 if outcome is completed otherwise 0.

\


\{{Outcome no show count\}}

1 if outcome is no-show otherwise 0.

\


\{{Outcome rescheduled count\}}

1 if outcome is rescheduled otherwise 0.

\


\{{Outcome scheduled count\}}

1 if outcome is scheduled otherwise 0.\
\


\{{Product name\}}

The name of the product associated with this engagement.

\


\{{Queue Memberships\}}

The list of queues that contain this engagement.

\


\{{Read Only Object\}}

Is the object read only.

\


\{{Roster object coordinates\}}

The ID of the associated roster object if the meeting was booked via a roster.

\


\{{Scheduled tasks\}}

\


\{{Time to book meeting from first contact\}}

The time it took to book a meeting from first outreach date of the associated contact.

\


\{{Activity date\}}

The date that an engagement occurred.

\


\{{Timezone\}}

Timezone of the meeting booking.

\


\{{Unique creation key\}}

Unique property used for idempotent creates.

\


\{{Unique ID\}}

The unique ID of the engagement.

\


\{{Updated by user ID\}}

The user that last updated this object. This value is automatically set by HubSpot and may not be modified.

\


\{{User IDs of all notification followers\}}

The user IDs of all users that have clicked follow within the object to opt-in to getting follow notifications.

\
\


\{{User IDs of all notification unfollowers\}}

The user IDs of all object owners that have clicked unfollow within the object to opt-out of getting follow notifications.

\


\{{User IDs of all owners\}}

The user IDs of all owners of this object.

\


\{{Performed in an import\}}

Object is part of an import.

\
\


\{{Owner Assigned Date\}}

The timestamp when an owner was assigned to this engagement.

\


\{{Activity assigned to\}}

The user that the activity is assigned to in HubSpot. This can be any HubSpot user or Salesforce integration user, and can be set manually or via Workflows.

\


\{{HubSpot Team\}}

The team of the owner of an engagement.

\


\{{All owner ids\}}

The value of all owner referencing properties for this object, both default and custom.

\


\{{All team ids\}}

The team ids corresponding to all owner referencing properties for this object, both default and custom.

\
\


\{{All teams\}}

The team ids, including up the team hierarchy, corresponding to all owner referencing properties for this object, both default and custom.

</details>

<details>

<summary>Portant</summary>

\{{Document Created Time\}}

The creation date of the most recent document output from Portant.

\{{Document Link\}}

The link to the most recent document output from Portant.

\{{Document Status\}}

The status of the most recent document output from Portant.

\{{PDF Link\}}

The link to the most recent document output from Portant.

\{{Signable Document Link\}}

The link to the first signature request link for this document.

\{{Workflow\}}

The name of the workflow that was run to produce the most recent document output from Portant.

</details>

#### Feedback and feature suggestions

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback please feel free to send us an email at contact@portant.co

Thanks,

Blake and James
