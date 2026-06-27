# WFG Email Campaign Playbook — when each email sends

Every email exists in English and Spanish. Send the language that matches the contact's preference.

## A. Lead Nurture  (trigger: new lead created, has NOT applied)
Stop this series the moment they apply (they move to series C). Drip cadence:

| Email | Sends | 
|---|---|
| A1 Welcome | Day 1 (immediately) |
| A2 How it works | Day 3 |
| A3 Less down than you think | Day 7 |
| A4 A loan for your situation | Day 14 |
| A5 Still thinking it over | Day 24 |
| A6 Smartest first step | Day 45 |
| A7 Here when you are ready | Day 90 |

## B. Credit Follow-up  (trigger: lead marked "credit not ready" / not yet qualified)
This is the new campaign you asked for. Tapers over ~7 months. Stop if they re-engage or qualify.

| Email | Sends |
|---|---|
| B1 Plan starts now | Day 1 |
| B2 Small habits | Day 14 |
| B3 Keep momentum | Day 30 |
| B4 What changes when ready | Day 60 |
| B5 Re-check your numbers | Day 90 |
| B6 Still in your corner | Day 150 |
| B7 One call away | Day 210 |

> Reminder: if a borrower was formally **declined**, the legal Adverse Action Notice is separate (handled in your LOS). These are nurture only. See COMPLIANCE-NOTES.

## C. In-Process Milestones  (trigger: loan status change in your LOS/CRM)
Event-driven, not time-driven. Each carries the 6-step progress tracker.

| Email | Fires when status = |
|---|---|
| C1 Pre-approved | Pre-approval / pre-qualification issued |
| C2 Application received | Application submitted |
| C3 In processing | Moved to Processing |
| C4 Appraisal ordered | Appraisal ordered |
| C5 Documents needed | Conditions / docs requested (LO edits checklist) |
| C6 Underwriting | Submitted to underwriting |
| C7 Clear to Close | CTC issued |
| CF1 Final numbers & closing instructions | Final numbers balanced with title; processor sends (merge fields + wire-fraud banner) |
| C8 Closing scheduled | Closing date set (has wire-fraud banner) |
| C9 Closed / Welcome home | Loan funded / closed |
| C10 Thank you + referral | 7 days after closing |

## E. Homeowner Onboarding  (trigger: after closing)
| Email | Sends |
|---|---|
| E1 Review request | ~7 days after closing |
| E2 First-payment + autopay explainer | ~10 days after closing (merge field for exact date) |
| E3 Homestead exemption | ~21 days after closing (Texas) |
| E4 Driver license reminder | ~30 days after closing |

## F. Client for Life — Savings  (recurring, money-savers)
| Email | Sends |
|---|---|
| F1 Property-tax protest | Seasonal, early year before the ~May 15 Texas deadline |
| F2 Re-shop homeowners insurance | At each home anniversary |

## D. Retention & Referral  (trigger: past client)
| Email | Sends |
|---|---|
| D1 Settling in | 30 days after closing |
| D2 One-year anniversary | 365 days after closing |
| D3 Rate watch / refi | Ad hoc, or quarterly to past clients |
| D4 Refer a friend | Ad hoc, suggested ~60-90 days post close |
| D5 Seasonal greeting | Holidays / season changes |

## Sending notes
- FollowUpBoss editor cannot hold raw HTML. Run these through a dedicated HTML sender triggered off your CRM/LOS stages.
- A-series and B-series are time drips. C-series are status-triggered. D-series are date or ad hoc.
- Always send only ONE language per contact based on their preference.
