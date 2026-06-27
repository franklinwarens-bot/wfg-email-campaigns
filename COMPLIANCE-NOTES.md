# WFG Borrower Emails — Compliance Notes

Practical, not preachy. What is already covered, and the few things worth your call.

## Already built in (every email)
- **Not a commitment to lend** disclaimer, subject to credit approval, income/asset verification, and appraisal.
- **Rates/programs/terms subject to change**, may not be available in all states.
- **Company NMLS #2532048** + **Equal Housing Lender** in the footer.
- **Confidentiality notice.**
- **Wire fraud advisory** in every footer, plus a prominent red wire-fraud banner on the Closing Scheduled email.
- **Opt-out (reply STOP / BAJA)** on all marketing emails (Lead Nurture, Credit, Retention, Referral). Transactional milestone updates (pre-approval through closed) intentionally omit opt-out since they are service messages on an active loan.
- **No guarantees** of approval, rates, or savings anywhere. Softeners used throughout ("may qualify", "could", "many buyers").
- **Credit campaign**: framed as general education only. No credit-repair claims, no promises of specific score increases. WFG never positioned as a credit-repair company.
- **Pre-approval email** explicitly states it is not a final commitment and is subject to conditions.

## Worth your call (the "might be missing" flags)

| # | Item | Status / recommendation |
|---|------|------------------------|
| 1 | **Individual LO NMLS** | DONE. **Franklin Warens NMLS #1249423** now appears in every signature, alongside Company NMLS #2532048. Verified against public loan-officer listings. |
| 2 | **ECOA / Adverse Action** | The Credit follow-up series is marketing/nurture, NOT an adverse-action notice. If a borrower is formally declined, federal law still requires a separate Adverse Action Notice (usually via your LOS). These emails do not replace or trigger that. No change needed, just be aware. |
| 3 | **Functional unsubscribe (CAN-SPAM)** | "Reply STOP/BAJA" is acceptable if honored. When you pick the sending platform, wire its native one-click unsubscribe link into the marketing emails too. Easy add later. |
| 4 | **Equal Housing logo** | Text is present. The little EHO house logo image is a nice-to-have once images are hosted. Optional. |
| 5 | **Rate/payment specifics** | These templates deliberately contain NO specific rate or payment numbers. The moment you add a rate or a monthly-payment example, Reg Z trigger-term disclosures kick in. Keep specifics out of these, or tell me and I will add the required disclosure block. |
| 6 | **Secure document link (C5)** | The docs-needed email tells clients to use a secure portal and not to text sensitive info. Make sure a real secure upload link exists to drop in. |

Bottom line: this set is in good shape for a mortgage brokerage and is not over-lawyered.

## New post-close emails (added)
- **Funding / final-numbers email (CF1)** intentionally does NOT contain live wire instructions. It tells the borrower to call the title company at a verified number. This is the safest design and cuts wire-fraud liability. The processor fills the merge fields: `{{cash_to_close}}`, `{{title_company}}`, `{{title_address}}`, `{{title_phone}}`, `{{closing_date_time}}`.
- **Homestead exemption (E3)** and **property-tax protest (F1)** are written for **Texas**. Florida and other states differ. Use only where accurate, or ask me for state variants.
- **First-payment email (E2)** teaches the skip-a-month rule and uses a `{{first_payment_date}}` merge field, so the exact date is always correct.
