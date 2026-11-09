# Sprint 2 Report (October 2026)

**Project:** SproutMe capstone\
**Team:** Seth Aguilar, Warren Christian, Quinnlan McCarthy, Itay Shemesh

SproutMe assigns work continuously through its private Jira project. For this course report, Sprint 2 covers the work documented in the October 2026 progress presentation. The team’s objectives were to complete individual Jira assignments and attend regular client standups.

## YouTube Link

[https://youtu.be/GjuIEtAgSIM]

## What’s New (User Facing)

- The team completed changes to the onboarding flow. Broader onboarding and billing work continued.
- The ad metrics report gained a download button that generates a PDF on the server. The PDF layout was updated to more closely match the product design. The export was in Human Testing at the Jira snapshot.
- The Slack integration implementation was finished and was in Human Testing. The Shopify integration was about halfway complete.
- The author profile page gained blog pagination and support for social and external links. The Competitor Skills section gained Google and Meta account connection flows. The author page was in Human Testing, and the account connection assignment was in progress.
- The presentation also listed a new ROAS Score page. Its testing and deployment status were unconfirmed in the Sprint 2 materials.

## Work Summary (Developer Facing)

The team reported progress and received new assignments during client standups. Jira tickets and designs helped clarify requirements, and progress on current work determined what each person picked up next.

The team worked across onboarding, integrations, reporting, and website features. Seth documented his RPC research and began a system-wide naming refactor. Warren finished the server-side PDF rendering work and connected it to the report’s download button. Quinnlan finished implementing Slack and continued the Shopify integration. Itay used Sanity to manage content for the skills and author pages and added account connection and pagination behavior.

## Unfinished Work

The Jira board showed **19 assigned items** at the Sprint 2 snapshot, with **10 To Do, 3 In Progress, 1 Improvements Needed, and 5 in Human Testing**. Items leave this board after Human Testing, so the snapshot cannot provide a total for completed work. The presentation and board document implementation and testing progress. Production deployment was unverified.

## Completed Issues/User Stories

The team reported the implementation milestones below. The Jira status is included where the board identifies a corresponding ticket.

| Assigned member | Completed work | Status |
| --- | --- | --- |
| Seth Aguilar | Finished changes to the onboarding flow and created a working document to track RPC research. | Reported complete in the team update. A broader onboarding improvement ticket remained in progress. |
| Warren Christian | Finished server-side PDF generation for ad metrics, refined the PDF layout, and added the download button. | PDF export was in Human Testing. |
| Quinnlan McCarthy | Finished implementing the Slack account integration. | Slack integration was in Human Testing. |

## Incomplete Issues/User Stories

| Assigned member | Work remaining at the Sprint 2 snapshot |
| --- | --- |
| Seth Aguilar | Continue RPC research and renaming and work on onboarding billing. Broader onboarding improvements were in progress, self-serve onboarding needed revisions, and navigation changes were in Human Testing. |
| Warren Christian | PDF export and the branded loading screen were in Human Testing. |
| Quinnlan McCarthy | Shopify was about halfway complete, and Slack was in Human Testing. Account-picker polish and account hierarchy work were queued. |
| Itay Shemesh | The Connect Account assignment was in progress, and the dynamic author profile page was in Human Testing. His team update listed feedback, improvements, or a new assignment as the next step. |

## Code Files for Review

**Restricted by the SproutMe NDA.** The team can show the product UI and summarize its work. Private code and internal documentation are restricted.

## Team Contributions

- **Seth Aguilar** finished onboarding flow changes, documented RPC research, and started the system-wide RPC renaming task.
- **Warren Christian** implemented server-side PDF rendering, refined the exported report design, and wired the download button to PDF generation.
- **Quinnlan McCarthy** finished the Slack integration implementation and made progress on Shopify.
- **Itay Shemesh** moved the top three skills and each author’s top six blog posts into Sanity-managed content. He added Google and Meta connections to Competitor Skills, linked back to the skills section, and updated the author and blog pages with pagination. He also added author photo styling and support for social and external links.

## Responsible Use of Generative AI

The team used generative AI extensively during development. Team members verified changes in their local environments before submitting pull requests for human review. CI/CD checks and AI review agents provided additional feedback. The team remained responsible for reviewing suggestions and validating the final changes.

## Retrospective Summary

**What went well**

- Regular client standups helped the team clarify requirements and pick up new assignments as work progressed.
- The team earned more trust and had more freedom to carry out individual assignments.

**What we would improve**

- Individual assignments made it harder for teammates to keep up with work in other product areas.
- The codebase changed quickly, which made it harder to stay current while working on separate tasks.
- The NDA limited the evidence the team could share for course submissions.

**Proposed changes for the next reporting window**

- Use standups to flag changes that may affect another teammate’s work.
- Record implementation, testing, and demo readiness separately in private Jira.
- Choose a small set of verified product screens for the course demo.