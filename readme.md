# HAAG Social Media Initiative

## Group Information

**Team Members:**
* Jacob McGivern (Project Manager)
* Sheena Patel (Project Manager)
* Neelima Pandey (Initiative Lead)

## Problem and Scope
### Problem:
The core problem this initiative addresses is a lack of consistent external outreach. While impactful research, interdisciplinary collaborations, and significant milestones are regularly achieved, this information frequently remains siloed within immediate research groups. Because these achievements are rarely shared externally, there are missed opportunities to engage with key target audiences. Without an external presence, prospective students, potential external collaborators, computational advisors from other universities, and the broader research community are unaware of the opportunities and active work taking place.

### Scope: 
The scope of this semester's Social Media Initiative was to bridge this visibility gap by establishing a consistent, professional presence, primarily on LinkedIn. Our work was to design, test, and document standardized procedures and reusable templates. This ensures that future teams can seamlessly take over the initiative and generate consistent content with minimal onboarding. Some procedures were created by Neelima in the previous semester. Our work would fill in the gaps of documents missing or enhance documents where processes are lacking quality.

Specifically, the initiative's scope was limited to developing four distinct content streams:
* Faces of HAAG: A pipeline for highlighting individual researchers.
* Project Spotlights: A pipeline for showcasing research projects, publications, and technical milestones.
* Blog Posts: An outreach workflow for pitching and collaborating with external organizations and university communications teams to feature people and projects that belong to that external organization.
* Event Promotions: A promotional strategy to demonstrate an active community by highlighting internal lab meetings and external conferences/seminars/presentations/workshops by posting on LinkedIn before and after the event. This also includes sharing the event within HAAG circles for further engagement.

## Intended Outcome
### Faces of HAAG
The intended outcome of Faces of HAAG is to create a tracker, ready for input of previous and future Faces of HAAG publications that track the progress of the workflow. Also, to create a #post-feedback process for reviewing posts before submitting on LinkedIn.
### Project Spotlight
The intended outcome of Project Spotlight is to seperate the Project Spotlight workflow from the Faces of HAAG workflow for specific terminology dedicated to project spotlight. There should also be a tracker that is similar to the Faces of HAAG. Similarly, there should be a #post-feedback process for reviewing posts before submitting on LinkedIn. Lastly, we should attempt following this post-feedback process and draft post process with an actual LinkedIn post.
### Blog Posts
The intended outcome of Blog Posts is to create a tracker that covers the vast and lengthy process. It should be populated with external haag members by trying to utilize the sourcing process already defined. From those members, external contacts at the organization should be defined through the defiend process as well. Lastly, any other improvements to the process can be addressed.
### Event Promotion
#### Internal Events
A Lab meeting tracker with notifications should be made.
#### External Events
A new process document should be defined. This should have a #post-feedback process as well dedicated to Blog posts. Lastly, a tracker for events should be made on Slack with notifications in #general.

## Solutions and Work Completed

### Faces of HAAG
We successfully created and deployed an interactive tracking list in Slack to monitor the progress of the Faces of HAAG pipeline. Additionally, we developed a post-feedback review procedure specifically for Faces of HAAG drafts before publishing on LinkedIn.

### Project Spotlight
We successfully separated the Project Spotlight workflow from the Faces of HAAG pipeline. This has  specific terms highlighting technical research achievements. We built a separate Slack tracker to manage project milestones and drafted a post-feedback procedure. Finally, we did an implementation of an active Project Spotlight post to test and validate the review process.

### Blog Posts
We successfully built a Slack pipeline tracker to manage the long external blog process from identifying members to final social media posts. We executed initial process testing to locate external HAAG members, documenting the failure of this implementation and necessary next steps. Additionally, we created an AI-driven process with a prompt to discover verifiable university media contacts. Lastly, we completely redesigned our outreach email template to compel the reader to collaborate with HAAG on creating an article.

### Event Promotion

#### Internal Events
We successfully built a Weekly Lab Meeting tracker Slack List inside `#haag-admin`. We then integrated this tracker with a scheduled Slack Workflow that automatically triggers every Thursday morning to check for a lab meeting and broadcast the upcoming presentation topic directly into the `#general` channel.

#### External Events
We successfully defined and documented a comprehensive procedure for the External Events promotional workflow to spotlight HAAG members presenting at academic conferences. We established a dedicated Slack tracker to log upcoming presentations with notifications, and  `#post-feedback` review workflow to verify all drafts with presenters and admins before publishing.

## Repository Guide

Use the directory below to access specific files directly:

###  Root Directory
*   **[Final Presentation - Social Media Initiative SU26.pdf](./Final%20Presentation%20-%20Social%20Media%20Initiative%20SU26.pdf)** — The final presentation slide deck in PDF format.
*   **[Final Presentation - Social Media Initiative SU26.ppt](./Final%20Presentation%20-%20Social%20Media%20Initiative%20SU26.ppt)** — The PowerPoint version of our final presentation slides.
*   **[WeeklyReportConsolidation.md](./WeeklyReportConsolidation.md)** — Consolidated weekly progress updates of each team member in Summer 2026.

---

###  Procedures Folder (`/procedures/`)
This folder contains our standardized, step-by-step Standard Operating Procedures (SOPs) and supportive screenshots to ensure frictionless repeatability.

####  Procedure Templates (.md)
*   **[ProceduresFacesOfHAAG.md](./procedures/ProceduresFacesOfHAAG.md)** — Standardized pipeline for "Faces of HAAG" profile posts.
*   **[ProcedureProjectSpotlight.md](./procedures/ProcedureProjectSpotlight.md)** — Standardized pipeline for drafting "Project Spotlight" posts.
*   **[PostFeedbackforFacesofHAAG.md](./procedures/PostFeedbackforFacesofHAAG.md)** — Review and  process for "Faces of HAAG" drafts.
*   **[PostFeedbackforProject Spotlight.md](./procedures/PostFeedbackforProject%20Spotlight.md)** — Review process for "Project Spotlight" drafts.
*   **[blog-post-hook-email.md](./procedures/blog-post-hook-email.md)** — The new outreach email hook designed to pitch external editors.
*   **[blog-post-tracking.md](./procedures/blog-post-tracking.md)** — Standardized pipeline instructions for tracking external blog posts from defining external HAAG members to publication.
*   **[events-promotion-external-process.md](./procedures/events-promotion-external-process.md)** — Procedure for promoting HAAG members presenting at external academic conferences.
*   **[events-promotion-post-feedback-procedure.md](./procedures/events-promotion-post-feedback-procedure.md)** — Review workflow for external event promotional drafts.
*   **[events-promotion-internal-tracking.md](./procedures/events-promotion-internal-tracking.md)** — Procedure for utilizing the Slack Tracker for Internal Lab Meetings.
*   **[events-promotion-external-tracking.md](./procedures/events-promotion-external-tracking.md)** — Procedure for utilizing the Slack Tracker for External Events.




####  Tracker & Workflow Screenshots (.png)
*   **[blog_post_tracker_screenshot.png](./procedures/blog_post_tracker_screenshot.png)** — Screenshot of slack tracker used for  blog tracking.
*   **[lab_meeting_tracker_screenshot.png](./procedures/lab_meeting_tracker_screenshot.png)** — Screenshot of the interactive weekly lab meeting list setup inside `#haag-admin`.
*   **[slack_workflow_screenshot.png](./procedures/slack_workflow_screenshot.png)** — Screenshot of slack notification used for lab meetings.
*   **[external_events_tracker_screenshot.png](./procedures/external_events_tracker_screenshot.png)** Screenshot of slack tracker used for external events tracking.

---

###  Implementation Folder (`/implementation/`)
This folder contains our post-mortems, implementation retrospectives, programmatic AI tools, and evidence collected during pilot runs.

*   **[blog-post-finding-external-organization-haag-members.md](./implementation/blog-post-finding-external-organization-haag-members.md)** — Retrospective detailing the failure of finding how to find external organization haag members using the original defined proces.
*   **[blog-post-external-organization-media-contacts.md](./implementation/blog-post-external-organization-media-contacts.md)** — Retrospective detailing how finding the external organization contacts can be improved.
*   **[blog-post-media-contacts-prompt.md](./implementation/blog-post-media-contacts-prompt.md)** — The prompt used to instantly generate 5 verified, high-yield media contacts for any university using AI.
*   **[ImplementationPostFeedbackProcess(ProjectSpotlight Pilot).md](./implementation/ImplementationPostFeedbackProcess(ProjectSpotlight%20Pilot).md)** — Evaluation and observations gathered during the run of our threaded `#post-feedback` Slack review pipeline from a project spotlight.

## Individual Contributions
* **Sheena Patel:** Created and refined the end-to-end procedures for the Faces of HAAG and Project Spotlight streams and established the `#post-feedback` verification workflow from scratch. Implemented a Project Spotlight Post and documented how the implementation went.

* **Jacob McGivern:** Improved the procedure for Blog Posts through finding errors in the HAAG member sourcing section. Added those external organization members in the project tracker. Created a new procedure part for finding media personnel at external organizations through using AI/LLMs. Redesigned the pitch for contacting those contacts.
Created a new procedure for External Event Promotions. Designed the Slack Pipeline Tracker for the new procedure pipeline, defined a #post-feedback procedure process for post verification in the external events pipeline.
Created a new Lab Meeting tracker with notifications to alert #general of meetings each Thursday.

* **Neelima Pandey (Lead):** Advisor of work to be completed and guided edits along the way. Provided starting draft for Project Spotlight and procedures previously defined. 

## Presentation Feedback and Reflection
During our final presentation, we received valuable feedback from the HAAG community that helped clarify the future direction of this initiative:

* **Feedback from Oral Presentation:** Following the presentation, we received one question.
Q: How do you validate the outreach increased based on these content streams?
A: The growth of the LinkedIn Group and likes/comments can be analyzed in the future. Being the second semester of the initiative, we just need better procedures in place (this semester’s work). Then, more posts can be created in each content stream. Finally, we can analyze how they’re doing and the growth from the initiative as a whole and each stream individually. 

* **What the Group Learned:** The group learned that this initiative is vast and requires better bookkeeping to keep up with all of the streams. If posts occur one at a time, by a single coordinator, information will be slow to process and possibly lost. The trackers were a necessity and the procedures needed improvement to save time (Blog Posts).
We also learned the initiative team needs a dedicated HAAG Admin (Social media coordinator) as a consistent review and worker across all channels along side of any additional PMs that may join in future semesters. The workload is much too large for 1 or 2 people to focus on creating content.

* **Possible Improvements:**
[1] There needs to be a procedure in place to entice HAAG members to want to be spotlighted and apart of the social media process for their own benefit. 
[2] The social media initiative needs more members to handle each stream as well as an overall coordinator overseeing the operations when Bree or other admins cannot review posts.
[3] Evaluate the 48 hour feedback window. This may be too small, too large, or just not appropriate to expect Bree or other Admins as part of the #post-feedback process.

* **Future Next Steps:** 
[*1*] MOST IMPORTANTLY: Start doing more posts. The processes have now been created, its time to build a repetoire of content to be posted to put these procedures to the test.
[2] Once more posts are being populated consistently, start including LinkedIn Analytics and maybe A/B tests for future improvements.

