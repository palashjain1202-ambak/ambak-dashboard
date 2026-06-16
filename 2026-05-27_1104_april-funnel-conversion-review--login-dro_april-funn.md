# CoS Report - April Funnel Conversion Review, Login Drop RCA, Capacity Planning & Training AOP - 2026-05-27 11:04

## TL;DR
April M0 login drop fully explained (tenured FBMs on simultaneous leave + PSU ROI hold); recovery underway and now at ~22% heading to 31%. The single most urgent thing: 7 overdue items from last 2 days still need owners to confirm completion.

---

## 1. Context
Monthly institutional ops review covering April funnel conversion deep-dive, RCA on the M0 login drop, E2E capacity planning for June, and AOP-aligned training progress update from Arpit. The funnel data was presented channel-wise with cohort analysis showing where Ambak's strongest conversion happens and where the biggest drop-offs are.

---

## 2. Attendees and Personas

- **Ankita** - Head of Institutional/E2E Operations, Ambak. Focus: funnel conversion, M0 login tracking, capacity planning, DID rollout, FBM productivity.
- **Raghu (Raghuveer Malik)** - Founder and CEO, Ambak. Focus: contingency planning failures, AOP target gaps, cross-pitch opportunity, strategic direction-setting.
- **Rashi** - Co-founder (Operations/Distribution), Ambak. Focus: cross-pitch audit on "logged with another bank" leads, overall distribution quality.
- **Arpit** - Training and L&D Lead, Ambak. Focus: e-learning rollout, escalation training outcomes, June training plan, LPL gamification.
- **Rishabh** - E2E/Operations Manager, Ambak. Focus: Mada partner lead data quality, capacity planning for team allocation.
- **Ankit** - Sales Operations Lead, Ambak. Focus: bank handling approach, calibration sessions, training delivery.
- **Darshan** - Operations/Audit Lead (likely), Ambak. Focus: deal cancel re-audit.
- **Avinash** - Sales Quality/Training (likely), Ambak. Focus: lead audit, cross-pitch quality.

---

## 3. Key Discussion Points

- **Best-performing cohort**: 750+ CIBIL, salaried, 50L+ ticket size achieves 69% QL-to-login, 71% sanction, 81% disbursement on mature pipeline - but this cohort's contribution has dropped from 26% to 13% of total QL volume over the past months.

- **April M0 login drop explained**: Institutional M0 fell from 31% (Feb) to 21% (Mar) to 18% (Apr). Two confirmed causes: (1) three tenured top-performing FBMs (Anita, Rameshwar, Mahesh Singh) went on planned leave simultaneously; (2) PSU ROI confirmation delays held cases from logging for the first 15-16 days of April. No contingency plan existed for either.

- **Recovery underway**: May M0 already at ~22% and trending up. Four active levers - daily first-call tracking, first-call pitch calibration (Q-score improved 49 to 54), auto-dialer (improving connectivity 25-30%), and sales team re-engaged on document collection push. Feb level (31%) expected to be hit or exceeded by month end.

- **Funnel drop-off breakdown on mature cohort**: QL-to-login at ~54-55% vs AOP target of 65-70%. Blockers: 15% not responding (whitelisting not yet live), 28% deal cancel/postpone (audit pending), 16% ineligible post-login (wrong bank selection), 8% lost to competition post-sanction (rate/amount mismatch). Detail channel worse: 24% not responding, 26% deal cancel/postpone.

- **DID phone number whitelisting**: Vendor agreed to supply mobile numbers in 2-3 days. One day to configure in system. Roll-out by next Wednesday (June 3), usable Thursday (June 4). This directly targets the 15-24% not-responding segment.

- **Sanction pool aging (Mumbai/Pune)**: Only 10-15% of the sanction pool disbursing per month. Cases stuck on specific-floor CC/RERA clearances and builder documents. Months outstanding: M5/M6 TAT is now common. Ankita to do partner-level mapping to surface which partners are the bottleneck.

- **Call timestamp bug**: First-call follow-up reports are using call end time (not start time) as the timestamp. Inflating delay metrics significantly. Needs immediate product fix (Roshan) - would auto-improve follow-up scores by 5-7%.

- **Missed call visibility gap**: FBMs don't know when a customer has called back on a system ID unless they're on the system at that moment. Immediate product fix required.

- **Lead data quality (Mada/partner)**: Past 2-3 months of partner data now arrives with only name, phone number, flat type - allotment date and booking date are missing. This causes agents to call stale leads. Root cause unknown; Rishabh to investigate on Monday with partner.

- **Cross-pitch of "logged with another bank" leads**: 17-31% of leads are already logged (mostly SBI). Rashi flagged that agents should be cross-pitching competitive rates. Audit underway (Avinash) to check whether agents are actually pitching and identify training gaps.

- **Training AOP - escalation module**: E-learning module 1 launched on escalations. 63% passing rate. Escalations down from 33 to 11 across four tracked categories (Sangam, BRE, offer share, civil fetch). 94% headcount coverage (158 of 168 nominated across 6 sessions).

- **June training plan**: Communication, art of report, and people management workshops (nomination-based); e-learning in NHT; buddy program; call audits for new joiners; cross-function mock calls (Mumbai vs Pune persona pitch); Learning Premier League gamification on Kahoot.

- **AOP call audit target**: May AOP target is 65-70% call audit score. Escalation training is the confirmed first initiative; new topics to be added. AOP tracking confirmed on-track per plan.

- **Capacity planning for June**: Mumbai 0-to-15-min first follow-up at 62%, target 80% in June. Delhi at 89%. Two Pune hires joining June 8. Ankita sitting with Himang on 27th for complete OP data review; city heads to get June plan on June 1.

---

## 4. Decisions Made

- DID numbers to be configured and rolled out by next week Thursday (June 4) once vendor delivers.
- Planning review to happen on May 27 (Ankita + Himang) with June targets presented to city heads on June 1.
- Auto-dialer to remain live across all channels; will also be routed to inbound leads from Mada while partner data is stale.
- Bulk/cold calling lead data to be handled separately from regular FBM queue going forward - no more mixing bulk data into regular dialer queue.

---

## 5. Action Items

- [ ] [HIGH] Ankita - Review complete May data with Himang today (May 27); present RCA, initiative performance and June targets to city heads by June 1 - 2026-06-01 - Monthly target planning
- [ ] [HIGH] Product (Mohit/Roshan) - Fix call timestamp to use call start time (not end time) in first-call follow-up reports - No date mentioned (immediate) - Reporting accuracy
- [ ] [HIGH] Product team - Implement immediate fix: show missed call notifications to FBMs in real-time on system ID so they can call back without missing customer - No date mentioned (immediate) - Missed call visibility
- [ ] [HIGH] Telecom/Ops - Receive DID mobile numbers from vendor (2-3 days), configure in system within 1 day, roll out by Thursday June 4 - 2026-06-04 - Number whitelisting
- [ ] [HIGH] Rishabh - Meet Mada/partner on Monday to understand lead data quality gap (missing allotment/booking dates in new format); report back with prediction on conversion potential - 2026-06-02 - Lead data quality
- [ ] [HIGH] Darshan - Sit for joint re-audit of deal cancel/postpone cases across cities; validate 28% figure and identify major contribution cities and root causes - No date mentioned - Funnel drop-off audit
- [ ] [LOW] Avinash - Audit "logged with another bank" cases for cross-pitch attempts; check if agents are pitching competitive rates vs SBI and identify pitch training gaps - No date mentioned - Cross-pitch audit
- [ ] [LOW] Arpit/Training team - Launch June plan: communication + art of report + people management workshops (nomination); introduce e-learning in NHT; buddy program; call audits for new joiners; Learning Premier League on Kahoot - 2026-06-30 - June training rollout

---

## 6. Unanswered Questions / Parking Lot

- What is the actual root cause of 28% deal cancel/postpone? Split by city needed (Mumbai/Pune are higher contributors). | Raised by Raghu, Rashi | Darshan + Ankita to close via joint audit.
- Why has partner data quality dropped - missing allotment/booking date for past 2-3 months? Is a new person downloading the data differently? | Raised by Ankita (Avinash flagged) | Rishabh to investigate Monday.
- Are FBMs actively cross-pitching customers already logged with another bank (especially SBI)? What is the pitch success rate? | Raised by Rashi | Avinash to audit and report.
- What is the actual impact of DRE/BRE automation on productivity? Column can be added but how to measure impact systematically? | Raised by Raghu | Unresolved - left for next review.

---

## 7. Risks / Things to Watch

- **AOP FBM productivity target gap**: April actuals at 8.11 vs AOP target of 14. This is a ~42% miss. Core lever (QL-to-login improvement) not yet working at required scale. Risk of carrying this gap into June.
- **Sanction pool aging in Mumbai/Pune**: M5/M6 disbursement timelines becoming the norm for direct allotment cases. Builder CC/RERA delays on specific floors are structural - not within Ambak's control. Revenue recognition is being deferred significantly.
- **Lead data stale quality**: Mada partner data has been missing booking/allotment dates for 2-3 months. 25% of the 61 recent leads had already taken a loan or are self-funded. Calling these wastes capacity and inflates drop-off metrics.
- **No contingency plan for tenured FBM leaves**: April failure mode (multiple tenured FBMs on leave simultaneously) has not yet been formally closed. A process/policy for leave coverage is still being planned.
- **Call recording gaps in May**: Recording issues on May calls have disrupted first-call follow-up and talk-time reports. The bug was fixed but past May data is compromised.
- **QL-to-login gap vs AOP**: Currently at ~22% (M0) vs 31% target. Trajectory is positive but still 9 points below plan. DID rollout and auto-dialer expansion are the key bets - both unproven at scale yet.
- **Training AOP escalation target**: Current passing rate 63% vs 65-70% target. Improvement is real but not yet at target. New topics being added may dilute focus.

---

## 8. Meeting Dynamics and Blind Spots

- **Raghu drove all the tough follow-ups.** Most of the diagnostic probing ("kya contingency plan tha?", "why did we not fix this before?", "are agents cross-pitching?") came from Raghu alone. Other senior participants were mostly in response mode rather than raising independent concerns.

- **Cause-and-effect not always closed.** Multiple funnel drop-off causes were identified (not responding, deal cancel, competition) but very few had confirmed action owners and timelines. There's a risk the meeting generated clarity without generating accountability.

- **Training presenter (Arpit) presented well but the AOP gap wasn't stress-tested.** The 63% passing rate vs 65-70% AOP target was acknowledged but glossed over. No one pushed on what changes to training content or delivery would actually close that gap.

- **Rishabh's Monday update was accepted without a specific outcome defined.** He was asked to "figure out and let us know" on the Mada data. No clarity on what decision would follow his Monday meeting.

- **The FBM productivity miss (8.11 vs 14 AOP) got minimal discussion.** It was mentioned briefly and moved past. This is likely the most significant AOP gap on the board and warranted more time.

**Participation summary:**
- Raghu: ~14 questions
- Ankita: ~6 questions
- Rashi: ~3 questions
- Arpit: ~2 questions
- Rishabh: ~2 questions
- Others (Ankit, Darshan, Avinash): ~1 each

---

## 9. Reminders from Previous Meetings

**A. Overdue (due May 26, not yet reminded)**

- Prabhat - Update QL tracking format (central-allocated vs Lucknow vs unassigned vs self) - Was due: 2026-05-26 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Vijay/Aditya - Send last 12 weeks of QL data (weekly numbers) to Raghu - Was due: 2026-05-26 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Tarun/Hitesh (via Vijay) - Send insurance waterfall update to Raghu by 2 PM - Was due: 2026-05-26 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Rashi - Share comfort level on 76 CR E2E number to Raghu - Was due: 2026-05-26 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Vijay/E2E - Move 20 CR of E2E cases into system - Was due: 2026-05-26 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Akash - Post 2-3 lead IDs from last 3-4 days (Pune-Delhi coordination gaps) - Was due: 2026-05-26 - Source: Ambak WBR / 2026-05-26 - [LOW]
- Vijay - Track daily E2E DRR number in Aditya's self-tracking sheet - Was due: 2026-05-26 - Source: Ambak WBR / 2026-05-26 - [LOW]

**B. Due today or tomorrow**

- Ankit - Share timelines for hacky checklist and bank-wise case handling approach - Due: 2026-05-27 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Raghu/Arvind - Catch up for full update on D2C, ops, institutional and retail - Due: 2026-05-27 - Source: Institutional Review / 2026-05-25 - [HIGH]
- Vikas, Vijay, Aman, Ashish - Hold 30-min sync to align on pay-in changes and adjust May schemes - Due: 2026-05-28 - Source: Retail Review / 2026-05-25 - [HIGH]

**C. Due within the next 7 days**

- Rashi - Create baseline document on extended-timeline problem (property finalisation, registry delays, customer WIP) - Due: 2026-05-31 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Ishaan, Ankit - Hit May commitment of 250-plus logins and 110 number - Due: 2026-05-31 - Source: Institutional Review / 2026-05-25 - [HIGH]
- Neerav - Finalise ABM hire for Ahmedabad; two ABM offers going out - Due: 2026-05-31 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Nagesh - Close Bangalore hiring (city head, 2 ABMs, RMs) - Due: 2026-05-31 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Ankit/Rishab - Ensure 7 Bangalore ready-to-log files are logged this week - Due: 2026-05-31 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Pooja - Double-click on train-the-trainer content, scheduling consistency, assessment reliability - Due: 2026-05-31 - Source: Ambak WBR / 2026-05-26 - [HIGH]
- Ankit, Ishaan - Run joint institutional and E2E review of full funnel - Due: 2026-06-01 - Source: Institutional Review / 2026-05-25 - [HIGH]
- Vijay/Ankit - Ring-fence MAHADA 2600 leads with Aman and banker coordination - Due: 2026-06-01 - Source: Ambak WBR / 2026-05-26 - [HIGH]

**D. Aged items - no due date, created more than 14 days ago**

All items are new (created May 25-26, 2026). No aged items yet. Check back after June 8.

**E. Cross-meeting repeats**

None confirmed across 2+ distinct meeting cycles yet. All items originate from the May 25-26 batch of meetings.

**G. Items updated this meeting (verbal completions or deadline changes)**

No auto-updates triggered. Note: The "Rishabh, E2E team - Complete RCA on QL-to-login" item from the Institutional Review (2026-05-25) appears to have been delivered via this meeting (the presentation IS the RCA). However no explicit verbal confirmation was given so it has not been auto-completed. Recommend Pranav manually mark this done if satisfied with the analysis.

---

Leadership dashboard: https://zippy-dasik-de25fb.netlify.app
