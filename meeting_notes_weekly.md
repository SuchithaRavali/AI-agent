# Project Beacon: Weekly Team Meeting Notes (September 2026)

Attendees (core): Dana (PM, report author), Priya (Design/Research), Marcus (Engineering lead), Lena (Customer Support lead), Tom (Finance partner, joins as needed)

---

## Week ending Sep 4

**Progress**
- Onboarding checklist redesign: usability testing with 8 customers completed. Feedback largely positive; 2 users confused by the "connect your data" step.
- Marcus: new welcome-email sequence is built and in QA.
- Lena: support tickets tagged "onboarding" remain the biggest category.

**Decisions**
- Keep the 5-step onboarding flow (not the 7-step variant).

**Blockers**
- Waiting on legal for updated in-app consent copy.

**Action items**
- Priya: revise "connect your data" step copy by Sep 9.
- Dana: chase legal for consent copy.

---

## Week ending Sep 11

**Progress**
- Revised "connect your data" step shipped to the 10% pilot group.
- SSO integration with the identity provider is about 60% done, per Marcus.
- Pilot group completion looks better than control, but sample is small.

**Decisions**
- Launch date confirmed: **Nov 15**. Team agreed this is achievable if SSO lands by mid-October.

**Blockers**
- Legal consent copy still outstanding (now 2 weeks).

**Action items**
- Marcus: SSO to staging by Oct 2.
- Lena: summarize top 5 pilot support themes by Sep 18.

---

## Week ending Sep 18

**Progress**
- Pilot expanded to 25% of new customers.
- Ticket volume spiked this week. Lena traced most of it to an SSO login bug affecting pilot users; Marcus pushed a fix on Thursday.
- Legal consent copy approved.

**Decisions**
- Expand pilot to 50% only after ticket volume normalizes.

**Blockers**
- SSO bug exposed edge cases the team had not tested for. Marcus thinks more QA time is needed.

**Other / side notes**
- Priya mentioned that if we hold to a December launch, we will probably need around $18k extra for translating the onboarding flows into Spanish and French. Dana: "We'll sort that out later."
- Side note from Tom: the MailPilot email-delivery contract runs out at the end of October. Nobody has looked at renewal terms yet.

**Action items**
- Marcus: add SSO edge-case test suite by Sep 25.
- Lena: keep daily ticket tracking until volume drops.

---

## Week ending Sep 25

**Progress**
- Pilot at 50% of new customers. Completion rate improved to 78%, which is above our 75% interim goal. Team happy with the trend.
- Ticket volume back down after the SSO fix.
- Edge-case test suite complete; QA found 3 further SSO issues, 2 fixed.

**Decisions**
- Launch date moved to **Dec 1** to allow for extra SSO QA and a regression pass. Marcus and Dana aligned on this; leadership not yet informed.

**Blockers**
- 1 SSO issue still open (token refresh on mobile browsers).

**Action items**
- Marcus: close token refresh issue by Oct 9.
- Dana: draft the monthly status report for leadership.
- Priya: finalize Spanish/French string list so we can get a translation quote.
