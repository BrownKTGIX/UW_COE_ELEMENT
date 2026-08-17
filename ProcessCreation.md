# Mapping Processes to Segments

A quick exercise to determine what key stages are in your process, and how you determine when people reach that stage.

## 1. What are key milestones in your admissions process where you want to take some action with an applicant or student?

Here is a sample of communications or actions you may want to do during an admissions process:

* Send a reminder email to those who have started but not submitted an application

* Notify accepted students of upcoming onboarding events

* Assign applications to your reviewer pool

* Remind applicants of Enrollment Confirmation Deposit deadlines

## 2. Based on the action you want to take, how do you identify when people are ready for the step?

Given the examples above, we can consider:

 | Stage | Slate Identifier | Category to Map to | Segment |
 | --- | --- | --- | --- |
 | Started but not submitted | "Application by Population Status"= Awaiting Submission (Plus appropriate term/program code filters) | [PROGRAM] Application Status | Application Status IS Awaiting submission |
| Upcoming Onboarding | "SDB Status - Most Recent"= Enrollment Packet (Or Registered, depending on timing) | [PROGRAM] Enrollment Status | Enrollment Status in Deposited, Registered | 
| Assign Applications | "Admission Review Bin" or "Application by Population Status" = Awaiting Review | [PROGRAM] Application Status | Application Status IS Awaiting Review
| ECD Deadlines | Slate "SDB Status - Most Recent"= Offered-Synced | [PROGRAM] Enrollment Status | [PROGRAM] Enrollment Status IS No Deposit


## 3. Build Segments 

With the process mapped, you can now build segments, which allows you to undertake a number of other tasks like send out appointment invites (or assign appointment invitations to your team), send emails, or other actions, and in many cases once the process is mapped, you can trigger all of the processes with just a file upload if you wish.
