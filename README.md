# WFG Borrower Email Campaigns — what this is and how to use it

**36 emails, English + Spanish (72 total)**, all on the new premium template (the one you liked at 12:18), with custom on-brand images, a progress tracker on the milestone emails, and working CTA links.

## Start here
1. Open **campaign-index.html** to see every email (EN + ES thumbnails, grouped by campaign).
2. Read **COMPLIANCE-NOTES.md** for what is covered (everything is in good shape).

## What is in this folder
| Folder/file | What it is |
|---|---|
| `campaign-index.html` | Self-contained gallery of all 58 emails. Open this first. |
| `html/` | 58 production-ready `.html` emails (id-key.en.html / .es.html). |
| `images/` | 16 optimized images (`wfg-email-01.jpg` ... `16.jpg`). |
| `previews/` | Full-length PNG of each email. |
| `COMPLIANCE-NOTES.md` | Compliance review + flags. |
| `source/` | `campaign-matrix.json` (the plan) + `copy.json` (all subjects + copy, EN/ES). |

## The campaigns
- **A. Lead Nurture (7)** new leads, Day 1 to Day 90, tapering.
- **B. Credit Follow-up (7)** not-yet-qualified, Day 1 to Day 210, slowing down. Education only, no credit-repair claims.
- **C. In-Process Milestones (11)** pre-approval through closed + the funding / final-numbers email, with a 6-step progress tracker.
- **E. Homeowner Onboarding (4)** review request, first-payment explainer, homestead exemption, license reminder.
- **F. Client for Life Savings (2)** property-tax protest, insurance re-shop.
- **D. Retention & Referral (5)** settling in, 1-year anniversary, refi watch, referral, seasonal.

## Going live
1. **Images: DONE.** Hosted on a CDN (`cdn.jsdelivr.net/gh/franklinwarens-bot/wfg-email-assets`). Every email renders live right now, no WordPress needed. To move them onto warensfinancial.com later, just say so and I will repoint the templates.
2. **Pick a sender.** FollowUpBoss cannot faithfully send this hand-coded HTML, so these run through a dedicated HTML email sender triggered off your CRM/LOS stages. See CAMPAIGN-PLAYBOOK.md for how each milestone fires automatically.

## Notes
- CTA "Talk to an advisor / Hablar con un asesor" points to **warensfinancial.com/contact-us/** for now. Swap to the booking page when it is built.
- Subject lines (EN + ES) are in the gallery and in `source/copy.json`.
- The docs-needed email (C5) has a checklist your LO can edit per file.
- Your NMLS **#1249423** now appears in every signature.
