# Sprint 1 Report (Project start–October 11, 2026)

**Project:** SproutMe capstone  
**Team:** Seth Aguilar, Warren Christian, Quinnlan McCarthy, Itay Shemesh

SproutMe assigns work continuously through its private Jira project rather than in fixed sprints. For this course report, “Sprint 1” means the work assigned from the start of our capstone engagement through October 11, 2026. **[CONFIRM: replace “Project start” with the exact start date before submission.]** Statuses below are a snapshot, not a claim that every change is deployed.

## YouTube link:

## What's New (User Facing)

- An obsolete Profile menu option was removed, so the menu no longer points users toward an unsupported action. The related Jira item is marked Done and its code was merged.
- Business editing and an onboarding-screen change are also marked Done in Jira. We have not independently confirmed their production deployment, so the demo will show only behavior available in the approved environment.
- Other work in this window, including agency team management, loading feedback, integration flows, and a website skill-trial experience, is at different stages of implementation or review. We do not present an open or testing-stage change as a released feature.

## Work Summary (Developer Facing)

The team joined an existing product, learned its application, API, and data flow, and took individual assignments from regular client standups. Each person worked through the relevant design and acceptance criteria, checked changes locally, and used private pull requests for review. Human reviewers, automated CI/CD checks, and AI code-review agents provide additional feedback before merge; the team remains responsible for the result. The main barriers were onboarding into a large existing platform, dependencies across product areas, and limits on what can be shared for a university submission. We therefore distinguish assigned work, Jira completion, merged code, and verified live behavior instead of treating them as interchangeable.

## Unfinished Work

At the October 11 snapshot, 21 team-assigned Jira items were visible: 4 Done, 6 In Progress, 2 Testing, 2 Improvements Needed, and 7 To Do. The 10 active or review-stage items continue in SproutMe's rolling workflow; the 7 To Do items remain queued. We have not verified that every unfinished item has a Jira comment explaining its delay, checked acceptance criteria, or a future sprint assignment. Those details must be completed in the private tracker if the course requires them. A fixed subsequent sprint has not been scheduled by the client.

## Completed Issues/User Stories

The following assignments are marked Done in the private Jira snapshot. Issue links are withheld from this course-facing draft pending client approval.

| Assigned member | Completed assignment | Evidence limit |
| --- | --- | --- |
| Seth Aguilar | Updated business editing and removed an unnecessary onboarding screen in an integration flow. | Jira says Done; production behavior was not independently verified for this report. |
| Warren Christian | Removed an obsolete Profile menu option. | Jira says Done; the related pull request was merged. |
| Itay Shemesh | Completed the parent assignment for a website skill-trial experience. | The parent Jira item says Done; child-task attribution and live delivery need confirmation from Itay. |

## Incomplete Issues/User Stories

These are general descriptions of the work remaining in the private tracker, not a replacement for its acceptance criteria or comments.

| Assigned member | Work in progress, testing, or revision | Queued work |
| --- | --- | --- |
| Seth Aguilar | Agency onboarding revisions, navigation and branding changes, and testing for the business dropdown and team table. | Broader onboarding improvements and self-serve onboarding. |
| Warren Christian | Branded loading feedback and server-rendered report downloads. | None in the October 11 snapshot. |
| Quinnlan McCarthy | Slack connection revisions and Shopify integration work. | Account-picker polish, account hierarchy/navigation, and Google Tag Manager integration. |
| Itay Shemesh | Author detail page. | Connect Account widget. |

Some items may depend on client review, testing, or further requirements. The team should record the specific reason and next action on each affected private Jira item rather than infer one here.

## Code Files for Review

**Restricted by the SproutMe NDA.** 

## Team Contributions

- **Seth Aguilar:** Agency and business onboarding, business editing, team-management UI, and navigation changes.
- **Warren Christian:** Profile-menu cleanup, loading feedback, and report-download work.
- **Quinnlan McCarthy:** Service integrations and account-selection work.
- **Itay Shemesh:** Website skill-trial assignment, author detail page, and a queued account-connection widget.

These summaries describe assigned areas during this reporting window. They do not claim that every listed feature is complete or deployed.

## Responsible Use of Generative AI

The team used generative AI extensively during development. AI output was checked locally before a pull request was opened. Human reviewers and automated checks, including AI code-review agents, then reviewed the proposed changes. AI suggestions can be incorrect or miss product context, so the team resolves review findings and remains accountable for the final code and documentation.

## Retrospective Summary

**What went well**

- Regular client standups gave the team current priorities, feedback, and onboarding help.
- Individual assignments made ownership visible, while private pull requests provided a review trail.
- The team made progress across onboarding, navigation, integrations, website work, and UI feedback.

**What we would improve**

- Work is spread across separate product areas, making it harder to explain one unified outcome.
- We need a more consistent record of what is assigned, merged, tested, and actually available in a demo.
- NDA constraints require an approved way to give the instructor enough evidence without exposing internal systems.

**Changes for the next reporting window**

- Record a short status, acceptance-evidence link, and next action on each active item in private Jira.
- Agree with SproutMe on the exact screens, screenshots, and high-level descriptions permitted in course submissions.
- Confirm each teammate's learning notes and select a small set of verified behaviors for the next demo.
