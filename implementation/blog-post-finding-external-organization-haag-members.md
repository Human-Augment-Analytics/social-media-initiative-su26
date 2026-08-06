# Implementation Retrospective: Defining External Organization HAAG members

## Related Procedure
This document evaluates how acquring external organization HAAG member names went by following the current "Haag_Blog_Partnership_Process" created by Neelima. This process was not edited by the Summer 2026 Social media initiative, so it is not included in the GitHub repo. I followed the steps to see if viability. 

## Context and Participants
*   **Investigator:** Jacob McGivern
*   **Target Population:** External computational advisors and faculty affiliates associated with HAAG who maintain affiliations outside of Georgia Tech.

## Objective
To identify, extract, and catalog the names and official institutional email addresses of all HAAG members affiliated with external organizations. This data was required to populate the **Slack Blog Post Pipeline Tracker** so the team could begin pitching cross-university research collaborations to external PR departments.

---

## The Approach

### Implementation Method: Spreadsheet Macro Extraction
Jacob was given a spreadsheet that all HAAG members are listed within called, HAAG_Summer_Enrollment_2026.xlsx. To gather this contact information efficiently , Jacob McGivern wrote a macro to parse the spreadsheet. The macro was designed to filter the enrollment list, isolate researchers and advisors whose registered emails did not end in `@gatech.edu`and put all the emails in a seperate sheet.

### Results and Observations:
*   **Single Success:** The process yielded only **one**  non-Georgia Tech  email address. 
*   **Gmail Domination:** The macro found a dozen `gmail.com`, but they were all attributed to researchers at Georgia Tech. 

*   **Root Cause 1:** Because researchers registered for HAAG using personal emails for long-term access, isolating emails is not reliable.
*   **Root Cause 2** HAAG doesn't have an exhaustive member tracking sheet that accomodates semester turnover accurately.

---

## Pivot

Since I couldn't get external organization members through the spreadsheet, Jacob McGivern declared the blocker to **Riyam**.  
Riyam was able to supply a complete list of external personnel. 

### Riyam's Manual Workflow:

Riyam had a list from the recruitment team of faculty and comp advisors in each project. She checked the emails of each member in the Slack Profile/calendar invites and manually made a list of all non gatech.edu emails and attached their name. 

This manually compiled list was imported into the **Slack Blog Post Pipeline Tracker**.

---

## Effectiveness and Lessons Learned

### What Did Not Work:
*   **Bad Data** The document that was expected to bring results was not profitable. It didn't contain all HAAG members, nor their emails, nor their affiliated organization.


### What Worked:
*   **Sharing Blockers** Sharing blockers with the admins yielded a response quickly. However, it is not sustainable each semester.


---

## Recommendations and Next Steps for Future Cohorts

### 1. Transition to an Internal Personnel Database
Relying on project managers to manually hunt down email addresses through Google and calendar invites is a highly unsustainable, non-scalable process. **Ideally, HAAG admins must maintain an exhaustive personnel record** 

### 2. Update the Onboarding process
A Recruitment Initiative should modify the onboarding enrollment form to include a mandatory field to define if they are part of an external organization and what it is.

### 3. Update the Blog Post Tracker
With so many members on the tracker currently, new additions are not urgent. Jacob would suggest going back after a legitamate HAAG member tracking is made to append new names to the tracker. Afterward, the procedure can be updated to look for names on once per semester basis.

---

## Contributors
*   **Jacob McGivern**  