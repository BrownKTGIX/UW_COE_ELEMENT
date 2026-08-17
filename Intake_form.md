# Build an Intake Form

Relevant Element Modules:

Data Sources:https://help.element451.com/en/collections/3846538-data-sources

Field Management: https://help.element451.com/en/collections/3846539-field-management

Create Forms: https://help.element451.com/en/articles/9001082-creating-managing-forms

Campaigns: https://help.element451.com/en/collections/124581-campaigns

Workflows: https://help.element451.com/en/collections/124560-workflows-rules

## What do I use an intake form for?

Intake forms are a great way to capture engagement and quickly and professionally communicate with them.

In this example we will build an intake form, make sure the data is structured correctly, put users into segments, and enroll the person to get an immediate, customized email response.

You can further develop these leads by using workflows to enroll them into other email campaigns.

## Step 1: Determine what information to collect and determine if new Data Sources are needed.

Most common form fields are likely already mapped to Data Sources.  If you need a new Data Source, please check out the Data Source article.

> [!WARNING]
> Most form field choices, if used in multiple forms, will overwrite with the latest submission.

For example, ![Data Sources](/Assets/COE%20How%20did%20you%20hear.png)If you use the  '[COE] How did you hear about us' field on multiple forms, the most recent submission will overwrite any previous submissions.

## Step 2: Create a new form

Decide what form fields you need to populate. Please read <a href="/Forms/Create Forms">Create Forms</a> for tips to make sure your form functions correctly in the UW instance.

> [!NOTE] 
> Recommended practice: Consider a balance between amount of information you need at this stage, and ease of completing the form.  Shorter initial forms will get more engagement.

![Form Fields](/Assets/Formfields.png)

## Step 3: Create a Segment

Segments are how you sort and filter users. In order take any actions like sending an email or automation steps, you must create a segment that will be the target of any actions.

>[!TIP]
> Label one-time use segments with a specific label, so you can easily find and delete them later.  For example you may want to send a follow-up to people who attended a specific one time event. Consider deleting segments if they're no longer needed.

You can make segments based on actions that users take within Element:
* Registered for or attended an event
* Did not show for an appointment
* Submitted your RFI form

You can also make segments based on data that you have imported:
* Started but not submitted applications
* A list of leads
* Leads from digital advertising
* People who have not accepted their admissions offer

For imported people you will need to identify them somehow by identifying a field to serve as a filter.  While you can also create audiences from imports directly, it is probably not best practice for those whom you want to communicate with again later, as it will be more challenging to combine them with other groups.

>[!NOTE]
> The logic filters are not traditional Boolean.  'In' denotes any of a number of choices, while 'Is' means only a single choice.  If you want to include or exclude multiple options (for example, if you have multiple checkbox selections that a user can enter), you should use "in"/"not in"

>[!WARNING]
>Be very careful with the 'does not exist' filter.  You are very likely to get every almost every lead in Element in a segment this way.
>
>
  





