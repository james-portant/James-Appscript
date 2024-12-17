# 🟢 Product Updates

**v1.98** - 04/12/24

* Add run from secondary objects as an option for HubSpot workflows
* Add the ability to use the newline character (\n) in formula fields to add formatting in output documents
* Add CC and BCC address fields to signature request config (backend only, please contact support if you require use of this feature)
* Fix issue with indexed images from Google Forms



**v1.97** - 27/11/24

* Add rate limit retry logic for Gmail sending
* Add batch delete option in the workflow list view
* Update default ordering of associated objects from HubSpot to have most recent first
* Update automation logic to prevent automations being started if they were to exceed the user's current document limit
* Fix field level formatting not being applied to labelled associated object fields for HubSpot workflows
* Fix issue with uploading and deleting logos for teams
* Fix documentation link for outgoing webhooks
* Fix modal primary action shortcut for windows
* Fix UI for the attachments modal when using Google Sheets as a template



**v1.96** - 20/11/24

* Add option to the document block in HubSpot workflow to control if PDF/Microsoft File copies should be uploaded to the source object
* Fix bug with associated labels in HubSpot workflows not matching if the display name of the label had been changed



**HubSpot App** - 13/11/24

* Launch a new version of the integrated HubSpot app cards using the new UI Extensions framework: [https://app.hubspot.com/ecosystem/23803058/marketplace/apps/portant-hubspot-google-docs-integration](https://app.hubspot.com/ecosystem/23803058/marketplace/apps/portant-hubspot-google-docs-integration)



**v1.95** - 06/11/24

* Add custom request headers to outgoing webhooks
* Update response status for outgoing webhooks to show HTTP status code
* Fix UI bug with referrals in settings



**v1.94** - 23/10/24

* Add formula fields for Google Sheets templates
* Add TEXTJOIN and TEXTJOINNONEMPTY formulas
* Improve "new workflow" flow and add consistency between the block select modal for new and existing workflows
* Fix bug where name and apperance of a new workflow is not being saved correctly
* Fix tag checking for Google Sheets templates and labeled tags for all source types



**v1.93** - 16/10/24

* Add prefixes to source values for labeled associated objects in HubSpot\
  e.g. `{{Client: Contact Email}}`
* Fix critical automation delay issues and improve overall speed of automations
* Fix bug preventing workflows to be created with a new file in Google Drive
* Fix small UI issues on workflow overview and document block pages



**v1.92** - 03/10/24

* Add AI document builder
* Fix small spacing and text truncation issues in the workflow overview page



**v1.91** - 25/09/24

* Add SUMIF Formula
* Fix various small UI errors



**v1.90** - 18/09/24

* Add PDFs containing fillable forms as a template format
* Add new progress and completion page to HubSpot app modal
* Add "partially signed" status to HubSpot properties. Note: this does require a manual migration if the "document\_status" property already exists within your HubSpot account.
* Add the ability to use templated link values in the signature request redirect URL
* Fix issue with SUM formula for groups of values larger than 1,000



**v1.89** - 04/09/24

* Add signable fields to Google Slides
* Add payment links to Google Slides
* Add export to Microsoft file formats as an output option (Word, Powerpoint, Excel)
  * When using HubSpot as a source these files will be automatically uploaded to selected primary object
* Add nested formulas to formula fields e.g. `{{=IF(N = 1, SUM(1, 2, 3,))}}`
* Add various loading and error states for the HubSpot app modal
* Update the background region that is inserted for signable fields, this will now be transparent
* Update "Remove Portant PDF branding" option to now be toggle-able
* Fix email "to address" validation to allow for apostrophes
* Fix tag replacement for Google Sheets to apply to tab (sheet) names
* Fix text truncation for workflow names



**v1.88** - 21/08/24

* Add Google Sheets as a template
* Fix bug with workflow menu on Firefox not being clickable
* Fix rendering for smaller windows



**v1.87** - 14/08/24

* Add [Developer Facing API](broken-reference) to allow developers to create workflows and automations from their own systems
* Add basic Typeform web hook adapter for forms with text fields
* Update maximum field length for selected HubSpot source fields



**v1.86** - 07/08/24

* Reintroduce Free Tier



**v1.85** - 31/07/24

* Add labeled contacts for "HubSpot to Signature Request" workflows
  * Signature request emails that use `{{Contact ...}}` tags will now correspond to the selected contact in HubSpot
  * Selecting labeled contacts as signature request recipients will now automatically merge data from those contacts by the association labels on contacts configured in HubSpot
* Add subtle indicator to workflow button for new workflows to encourage new users to discover of the automation process
* Add tab support for navigation around the app
* Fix various UI bugs affecting workflow lists
* Fix workflow list not rendering in Copper
* Remove onboarding questions for new users



**v1.84** - 17/07/24

* Add data grouping for arrays of objects in webhook events
* Add shortcut hint for primary action in all modals, Ctrl + Enter on Windows and ⌘ + Enter on Mac
* Add implicit `{{Workflow Runner}}` tag which allows the runner of the workflow to be referenced within the workflow itself. This tag is merged as a formatted email e.g. "John Smith \<john.smith@portant.co>" and can be used directly in email sending fields. This tag can also be used with the `{{=NAMEONLY(Workflow Runner)}` formula to extract just the name e.g. "John Smith".
* Update alias behaviour to always be sent from the workflow owner when an alias is selected. UI has also been improved to convey who an email or signature request will be sent from.
* Update webhook addresses to be shareable across workflows. This **currently** can only be configured by Portant Support, please contact us if you require the same webhook address to be used in multiple workflows.



**v1.83** - 10/07/24

* Add Stripe Connect payment links - Collect payments directly from your documents
* Fix workflow list issues caused by recent pagination changes
* Fix various UI inconsistencies



**v1.82** - 04/07/24

* Add workflow pagination to improve app load times for users with a large amount of workflows
* Add browser tab titles for workflows and other pages within the app
* Add titles to the workflow navigation icons (Source, Workflow, Outputs)
* Add loading modal when removing blocks from a workflow
* Fix various UI inconsistencies and typing errors (thanks to our private investigators 🕵️‍♂️)



**v1.81** - 26/06/24

* Add integration checking for team members to ensure all members are connected to the apps your team uses
* Add unlisted and slug look ups for workflow templates



**v1.80** - 20/06/24

* Update permissions settings to use an explicit refresh button
* Update source field table to use "copy" instead of "insert" for emails and signature requests
* Update Google Sign In to use FedCM
* Remove material icons as they would cause display issues for windows users
* Add support for users to be a part of multiple teams, this feature is not yet public facing



**v1.79.2** - 14/06/24

* Add `{{=IFANY(...)}}` formula to evaluate conditions across a set of data grouped values
* Add new HubSpot onboarding portal
* Fix signature request/team branding modal navigation
* Fix unnecessary warning that is displayed in HubSpot workflows when navigating to outputs page.



**v1.79** - 12/06/24

* Add `{{=LOWER(...)}}` and `{{=UPPER(...)}}` formulas to make text values lower and uppercase respectively
* Add formula fields to email, signature requests and output names
* Add ability to edit "Review and Sign" button text for signature requests
* Update modal UI/UX throughout the app for better consistency
* Update workflow duplicate process to automatically enable auto-create if applicable
* Fix custom team branding inconsistency between Portant Workflow and the signature portal



**v1.78** - 28/05/24

* Add `~` comparison to =IF formula fields to check if target text is contained within the comparison text\* . e.g. `{{=IF("Bar" ~ "FooBarBaz", "Yes", "No")}}` -> `Yes` \*Order of operands is commutative (i.e. `a ~ b` == `b ~ a`)
* Fix false error messaged displayed on outputs page for pending items that are still being created



**v1.77** - 22/05/24

* Add new onboarding flow to help understand how our customers use Portant
* Improve HubSpot integration to only fetch associated objects that are used within the workflow



**v1.76** - 15/05/24

* Add gamification with achievements 🎉
* Add Microsoft .NET webhook adapter (used by a range of SaaS products)
* Add Copper source option to "New Workflow" and "Add Block" modals for all users
* Add placeholder UI for source and template blocks in newly created workflows
* Fix bug with file uploads of completed signable documents for both HubSpot and Copper



**v1.75** - 08/05/24

* Add PDF file upload for HubSpot workflows
* Add warning modal when navigating from HubSpot source with unsaved changes
* Fix minor UI bug on outputs page



**v1.74** - 01/05/24

* Add direct HTML editor to email blocks (BETA)
* Add "Draft" and "Signature Requested" status options to output page filters when applicable to the workflow
* Add prominent loading indicator to HubSpot source field table after making changes from "manage fields" modal
* Fix bug in =IF formula fields for conditions contained quoted strings
* Fix missing custom object fields for duplicated HubSpot workflows
* Fix text entry fields not displaying in the correct position for signable documents
* Experimental: Add extend by page for Google Slides workflows using data grouping. (Please contact support if you would like trial this feature on existing or new workflow)



**v1.73** - 24/04/24

* Add filtering controls to the output page
* Fix missing "In Progress" state on the outputs page
* Fix email editor not showing inserted drive images
* Fix signature request attachments not showing up in some emails
* Fix signature request button to have contrast for custom branding colour in email



**v1.72** - 17/04/24

* Add signable document preview link, this now allows for signing to be completed in any order
* Add "Show in Hubspot" option to control if a workflow should be visible in the HubSpot actions menu
* Improve in-app navigation, Portant will now remember your current position in a workflow when you click back from settings
* Update workflow creation process to always ask for a workflow name. To keep your workflows better labeled
* Improve outputs page navigation and pagination
* Fix multiline text bug in IF formulas



**v1.71** - 03/04/24

* Add [outgoing webhooks](https://docs.portant.co/portant-docs/developer/sending-data-to-webhooks) to send automation event data to app from Portant



**v1.70** - 20/03/24

* Add trust certificates to signable documents/signature requests
* Improve HubSpot associated modal picker to handle large amounts of associated objects
* Improve date and time parsing to handle more formats (e.g. "13:02" from Google Forms can now be converted to "1:02pm" when configured as a "Date" source field)
* Update app flow to allow users to access their workflows after pro trial has expired



**v1.69** - 13/03/24

* Add arithmetic expressions to [formula fields](personalise-documents/tag-formulas/)
* Add decimal place modifier `|` to numeric formula fields
* Add date arithmetic and built in formulas (MINUTES, HOURS, DAYS, WEEKS)



**v1.68** - 06/03/2024

* Add HubSpot associated object picker deselect/select all input
* Add HubSpot override signature request options
* Improve set of default Copper source fields



**v1.67** - 26/02/2024

* Add HubSpot associated object picker



**v1.66** - 19/02/2024

* Add Copper CRM integration



**v1.65** - 12/02/2024

* Improve Google Drive file access for teams workflows



**v1.64** - 29/01/2024

* Add default date and number formatting user settings (applies to formula fields as well)
* Add confirmation modal to be displayed when changing HubSpot primary object&#x20;
* Add update warning to be displayed on login page when backend is down
* Add "ran by" user's name to outputs page items
* Add =ROUND formula field
* Fix preview navigation and review loading issues
* Fix search on teams management page to now be case insensitive
* Fix email editor save state display bug
* Fix automatic navigation when adding a new document before an existing one
* Fix bug that prevents source conditions from being updated or deleted
* Fix OAuth display updates on settings and workflow template pages



**v1.63** - 23/01/2024

* Improve team manager interface with viewer, runner, editor, admin and owner roles
* Add last edited and owner names to team workflow rows in list view
* Add always present side navigation bar



**v1.62** - 08/01/2024

* Add "User" field type for HubSpot users
* Fix trailing slash in custom folder path causing a blank folder to be created
* Improve extend tables (Data Grouping) for Google Slides
* Improve backend error recording for better support



**v1.61** - 03/01/2024

* Add variable amount of seats to teams plans, this is now displayed on the teams settings page
* Fix formula fields that were coming up as invalid in source field table
* Fix logic to strip invalid characters from emails when contained in tags



**v1.60.3** - 20/12/2023

* Add DD.MM.YYYY date formatting option
* Add `=TRUNCATE(text, length)` formula
* Fix PDF file name issue for periods "."



**v1.60** - 16/12/2023

* Update "start automation" flow to prevent timeout errors
* Add new share button UI and flow to help users upgrade to Teams
* Add ability for support staff to capture automation item data to help track down errors
* Begin capturing trust data for signature requests



**v1.59** - 06/12/2023

* Improve frontend data caching
* Add subscription upgrade modal after user has upgraded
* Add new sign up page (initial change for new onboarding flow, coming soon)
* Add email error reporting to the outputs page
* Fix HubSpot status property for "Signature Requested" status



**v1.58** - 23/11/2023

* Update HubSpot Portant properties to include signature request link and pdf link
* Add Portant block to HubSpot workflow automations
* Fix number formatting to not include extra zeros



**v1.57** - 15/11/2023

* Add support for nested associations from HubSpot&#x20;
  * e.g. `Deal -> Deal Month -> Ad Plan:`\
    This will include ‘Ad Plan’ Data when merging on the ‘Deal’
* Change aggregated formula fields that to expect numeric values to treat NaN (Not a Number) fields as zero to continue the aggregation rather than causing the entire field to be blank
