# Experimentation Plan (Module 5)

## Get your documents ready
- **From M3, your hypothesis sentence:** Based on Wanderers, the segment that most closely reflects users struggling to discover meaningful content, have the lowest LTV ($8.40), the fewest sessions (1.1/week), and consume mostly trending content (61%) rather than curated experiences., we believe that solving Reduce decision paralysis caused by repetitive, trend-heavy recommendations that force users to seek trusted film discovery elsewhere. for A discovery-driven viewer overwhelmed by StreamLine's trend-heavy catalog who leaves the platform to seek trusted film recommendations elsewhere before deciding what to watch. will result in Transform discovery-driven users from low-engagement Wanderers who leave StreamLine to find recommendations elsewhere into loyal, high-retention viewers who rely on Spotlight as their primary destination for film discovery., as measured by Increase the percentage of discovery sessions that result in a title being played, indicating that users can confidently find something worth watching without leaving StreamLine.. We will protect Maintain or improve the 30+ minute session rate among non-Spotlight users while increasing discovery-to-play conversion for Spotlight users. and make a go/no-go decision after Evaluate Spotlight after 90 days and one complete Month 0 → Month 1 retention cycle before deciding to scale, pivot, or stop. Increase Discovery-to-Play Conversion by at least 15% and Month 1 retention by at least 10 percentage points without reducing 30+ minute session rates..
- **From M3, your primary success metric & guardrail metric:** Success metric: Increase the percentage of discovery sessions that result in a title being played, indicating that users can confidently find something worth watching without leaving StreamLine.

Guardrail metric: Maintain or improve the 30+ minute session rate among non-Spotlight users while increasing discovery-to-play conversion for Spotlight users.
- **From M4, the feature you scoped in your PRD this is what you're testing:** “Why You’ll Love This” Label

## Define your experiment parameters
- **Feature under test pull from your M4 PRD:** “Why You’ll Love This” Label
- **Persona pull your M2 persona:** A discovery-driven viewer overwhelmed by StreamLine's trend-heavy catalog who leaves the platform to seek trusted film recommendations elsewhere before deciding what to watch.
- **Expected outcome the behaviour change you expect, from your M3 hypothesis:** Transform discovery-driven users from low-engagement Wanderers who leave StreamLine to find recommendations elsewhere into loyal, high-retention viewers who rely on Spotlight as their primary destination for film discovery.
- **Primary success metric the one number that defines success, from M3:** Increase the percentage of discovery sessions that result in a title being played, indicating that users can confidently find something worth watching without leaving StreamLine.
- **Baseline rate today's rate of your primary metric, from your M3 data:** 30+ Minute Session Rate = 11%
- **Guardrail metric & boundary what must not break, and how far it can move before you investigate:** Maintain or improve the 30+ minute session rate among non-Spotlight users while increasing discovery-to-play conversion for Spotlight users.
- **Minimum Detectable Effect (MDE) the smallest improvement worth shipping, your floor:** +2 pts in Discovery-to-Play Conversion Rate (from 34% to 36%)
- **Sample size per arm use the calculator in the builder, baseline + MDE:** 4144
- **Traffic split & test duration 50/50 standard · cover ≥ 2 weekly cycles:** 50/50
- **Significance threshold p < 0.05 is standard, explain any deviation:** p < 0.05 (95% confidence level)

## Define your control and variant
- **Control (A) the current experience, reference your M2 moment of misery and M3 funnel/workflow data:** Based on Wanderers, the segment that most closely reflects users struggling to discover meaningful content, have the lowest LTV ($8.40), the fewest sessions (1.1/week), and consume mostly trending content (61%) rather than curated experiences., we believe that solving Reduce decision paralysis caused by repetitive, trend-heavy recommendations that force users to seek trusted film discovery elsewhere. for A discovery-driven viewer overwhelmed by StreamLine's trend-heavy catalog who leaves the platform to seek trusted film recommendations elsewhere before deciding what to watch. will result in Transform discovery-driven users from low-engagement Wanderers who leave StreamLine to find recommendations elsewhere into loyal, high-retention viewers who rely on Spotlight as their primary destination for film discovery., as measured by Increase the percentage of discovery sessions that result in a title being played, indicating that users can confidently find something worth watching without leaving StreamLine.. We will protect Maintain or improve the 30+ minute session rate among non-Spotlight users while increasing discovery-to-play conversion for Spotlight users. and make a go/no-go decision after Evaluate Spotlight after 90 days and one complete Month 0 → Month 1 retention cycle before deciding to scale, pivot, or stop. Increase Discovery-to-Play Conversion by at least 15% and Month 1 retention by at least 10 percentage points without reducing 30+ minute session rates..
- **Variant (B) your single change, copy the relevant screens & functional requirements from your M4 PRD:** Screen descriptions: 
1. Spotlight Entry: Dedicated Spotlight landing page; Curated Rail; Hidden Gem Badges; Spotlight branding and editor highlights
2. Film Discovery Detail (Core Feature): Film card/detail view; "Why You'll Love This" explanation; Editorial recommendation note; Hidden Gem indicator; Play CTA
3. Watching Confirmation: Playback started confirmation; Success message; Related Spotlight recommendations; "Continue Exploring Spotlight" CTA

Functional Requirements: 
The system must display a Spotlight Curated Rail containing at least 10 hand-picked film titles.
The system must allow users to access Spotlight from the homepage in one click.
The system must display a "Why You'll Love This" recommendation reason for every Spotlight title.
The system must display a Hidden Gem Badge for eligible low-viewcount, high-rated films.
The system must allow users to open a title detail page directly from Spotlight.
The system must provide an editorial recommendation note for every Spotlight title.
The system must allow users to start playback from the title detail page.
The system must track whether a Spotlight discovery session results in a title being played.
- **Isolation check, what has NOT changed? list everything identical between arms (app version, recommendation engine, notifications, onboarding). If something changed inadvertently, your test is compromised.:** .

## Formalize your hypothesis & shipping criteria
- **Your hypothesis (filled in):** I believe that “Why You’ll Love This” Label for a discovery-driven viewer overwhelmed by StreamLine's trend-heavy catalog who leaves the platform to seek trusted film recommendations elsewhere before deciding what to watch, will result in transform discovery-driven users from low-engagement Wanderers who leave StreamLine to find recommendations elsewhere into loyal, high-retention viewers who rely on Spotlight as their primary destination for film discovery,
as measured by a 11% change in Increase the percentage of discovery sessions that result in a title being played, indicating that users can confidently find something worth watching without leaving StreamLine within 14 days (≥ 2 weekly viewing cycles).
We will protect to maintain or improve the 30+ minute session rate among non-Spotlight users while increasing discovery-to-play conversion for Spotlight users. throughout the test.
- **Your shipping criteria (filled in):** We will SHIP if the increase the percentage of discovery sessions that result in a title being played, indicating that users can confidently find something worth watching without leaving StreamLine improves by ≥ +2 pts at p < 0.05
and maintain or improve the 30+ minute session rate among non-Spotlight users while increasing discovery-to-play conversion for Spotlight users, does not reach The 30+ Minute Session Rate among non-Spotlight users must not decrease by more than 2 percentage points from baseline after 14 days (≥ 2 weekly viewing cycles).

We will ITERATE if direction is positive but lift is below the MDE.

We will KILL if the primary metric shows no improvement or moves negatively.

The read date is fixed at the end of 14 days (≥ 2 weekly viewing cycles), no results reviewed before this date.
- **Hardest parameter to define, and did it change your hypothesis? quick debrief:** The hardest parameter to define was the MDE (+2 pts in Discovery-to-Play Conversion), because it forced me to balance statistical realism with business impact. It did not change my hypothesis, but it made me narrow the success criteria from broad outcomes like retention and churn to a measurable short-term behavioral change: helping users confidently move from discovery to playback.
