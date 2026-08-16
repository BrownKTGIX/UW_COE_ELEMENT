# Element451@ UW Basics

This article will take you through a basic process in Element and help you determine next steps.

Before you do anything consider a few basic points about Element

## The Database

Element is a database system, but it's essentially a single large database in the UW implementation. Each 'Field' is like a column in a spreadsheet.  

This means that each time you change or input data into a field, it will overwrite what's previously there.  

>[!WARNING]
>Only use System fields for data you do not expect to change. (Like name, address, email, etc.)

System Fields are those which do not have a department identifier on them like [COE]

When building forms, consider if the data you are collecting is unique to your program.  If so, you should make a new custom field for the data.

## Segments are what drives everything

Segments will be how you sort people for workflows or any type of action.  Segments are based on data that you have collected about the student, so **make sure you are using your department's custom fields as a primary filter.**

You will use segments to drive action, so common segments might be:

* People who have started but not submitted an application
* Leads you collected at an event
* People who have attended an info session

Using additional information to created multiple filters will allow you very narrow scoped segments, if you have the right data available, like:

* People who have started an application in the past 30 days and live in the local area (Zip Code)
* Students who have not yet accepted their admissions offer and are not international students (Phone or Zip Code)

## Work backwards to build your forms.

Start with the action you'd like to take, like **sending an email** or **assigning a follow-up phone call to your team**, then work backwards to determine how to build your automation and form.

Example: assign a phone call automatically to your team to everyone who has not accepted your admissions offer.

- [ ] Goal: Create a balanced assignment list of phone calls for your admissions team of 3 people.
- [ ] Create an automation (Workflow) to automatically distribute tasks
- [ ] Create a Task 
- [ ] Create a Task Template (Implementation Captain role)
- [ ] Create the target segment (Students who have not accepted your offer)
- [ ] Import or Filter data to create the segment (Slate or SDB Status import)
- [ ] If collecting data on a form, create the form
- [ ] Identify form fields to use on the form, or create custom fields if necessary

## Consider how you would like to evaluate your leads in a review cycle.

When you get to the end of a cycle, if you are interested in looking at where you gained the most leads, consider how you might track different events.  

If you use the same lead form everywhere you go, it might be simpler but you do not have additional data to track.

Consider making a copy of your lead form for unique events, and using the copy to help you sort out where leads came from, or use a hidden field with the event information.

>[!TIP]
>If you make a copy of your lead form for different events, you can make a simple workflow to just enroll those leads into other workflows, like a drip campaign.  This way you can give everyone the same experience.

