# Hypothesis & Success Metrics

> **Module 3 · ★ Deliverable 3.** Repo file `03-analytics/hypothesis-and-metrics.md` — part of your submission.
> Do the lab in the **Module 3 · Exercise Guide** (linked from the Module 3 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It feeds the **Problem, Value & Hypothesis** slide of your Module 6 final deck.

## Finalized product hypothesis

> Based on [qual + quant evidence], I believe that [solving X] for [persona] will result in [outcome], as measured by a [X%] change in [success metric]. I will protect [guardrail metric] and make a go/no-go decision after [decision window].

## Success metrics

| Metric | Type | Target | Why it matters |
|---|---|---|---|
| _North-star_ | | _____ | _____ |
| _Leading indicator_ | | _____ | _____ |
| _Guardrail_ | | _____ | _____ |


# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** A passionate film enthusiast who actively seeks high-quality, diverse, and meaningful cinema experiences beyond mainstream recommendations.
- **Goal , what this user is ultimately trying to achieve:** Discover exceptional films efficiently through trusted guidance, curation, and recommendations that expand their tastes.
- **Friction / moment of misery , the specific pain blocking their goal:** Cannot confidently choose a meaningful film because StreamLine's recommendations feel repetitive and untrustworthy.
- **Current workaround , the external tool or manual process they rely on (M2):** - Letterboxd for curated lists and community recommendations.

- IMDb for ratings, reviews, and discovery.

- Rotten Tomatoes for critic consensus and quality validation.

- MUBI or Criterion Channel to explore expert-curated film collections and editorial selections.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** We must solve increasing churn and declining relevance as a content discovery destination by addressing the needs of cinephiles who are forced to leave StreamLine to find curated recommendations and meaningful film discovery experiences.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** For Cinephiles and discovery-driven viewers who value quality, curation, and expert recommendations over catalog size., we will Provide a premium curated cinema experience inside StreamLine through expert collections, human editorial selections, hard-to-discover films, or contextual recommendations that help users confidently discover great content. because Because subscriber churn is increasing, specialized competitors are gaining credibility as discovery leaders, and StreamLine risks losing its most engaged viewers if it cannot reestablish itself as a trusted destination for film discovery..

## Read your data snapshots
- **Does the funnel data confirm your M2 friction point, or does it tell a different story? Note where the numbers align with the qualitative pain you found and where they diverge.:** The funnel largely confirms our friction point. Users are still reaching browsing and title-detail stages, but fewer are converting discovery into viewing. The decline in search-to-play conversion (-7 pts), session length (-23%), and 30+ minute sessions (-8 pts) suggests the core problem is not content access, but confidence in choosing what to watch. This aligns closely with our qualitative finding that users experience choice overload and increasingly rely on external sources for trusted discovery. The data suggests StreamLine has a discovery problem more than an acquisition problem: users are entering the funnel, but they are not finding enough reasons to commit to watching.
- **Do the retention patterns align with the workaround your M2 persona used to find content? Note what the Mo. 0→1 drop suggests about the onboarding experience your persona described as frustrating.:** Yes, the retention patterns support our persona's workaround. The weak Month 1 retention in Full Library cohorts suggests users fail to experience discovery value early enough and continue relying on external platforms for guidance. Spotlight's 12–15 point retention improvement indicates that human-led curation addresses this pain point, but the persistent Month 0→1 drop shows StreamLine still struggles to prove its discovery value during the user's first month.
- **Does the LTV gap and the content mix (61% trending for Wanderers) confirm the moment of misery your persona described? Note which segment your persona is in and whether the data confirms their pain.:** Yes. The data strongly supports our persona's pain point. Wanderers, the segment that most closely reflects users struggling to discover meaningful content, have the lowest LTV ($8.40), the fewest sessions (1.1/week), and consume mostly trending content (61%) rather than curated experiences. Their 22-point churn improvement when exposed to Spotlight suggests that trusted curation directly addresses the frustration of not being able to confidently find a worthwhile film, validating our identified moment of misery.
- **Does the low adoption confirm your persona is burdened by tools they don’t use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** _(not filled in)_
- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** _(not filled in)_
- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona’s friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** _(not filled in)_

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** After repeatedly encountering generic trending recommendations and spending too long browsing without confidence, they abandon StreamLine and turn to trusted sources such as Letterboxd, IMDb, Rotten Tomatoes, or MUBI to decide what to watch.
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** Wanderers, the segment that most closely reflects users struggling to discover meaningful content, have the lowest LTV ($8.40), the fewest sessions (1.1/week), and consume mostly trending content (61%) rather than curated experiences.
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** A discovery-driven viewer overwhelmed by StreamLine's trend-heavy catalog who leaves the platform to seek trusted film recommendations elsewhere before deciding what to watch.
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Reduce decision paralysis caused by repetitive, trend-heavy recommendations that force users to seek trusted film discovery elsewhere.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Transform discovery-driven users from low-engagement Wanderers who leave StreamLine to find recommendations elsewhere into loyal, high-retention viewers who rely on Spotlight as their primary destination for film discovery.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** Increase the percentage of discovery sessions that result in a title being played, indicating that users can confidently find something worth watching without leaving StreamLine.
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Maintain or improve the 30+ minute session rate among non-Spotlight users while increasing discovery-to-play conversion for Spotlight users.
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** Evaluate Spotlight after 90 days and one complete Month 0 → Month 1 retention cycle before deciding to scale, pivot, or stop. Increase Discovery-to-Play Conversion by at least 15% and Month 1 retention by at least 10 percentage points without reducing 30+ minute session rates.
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on evidence that users struggle to find meaningful content, spend more time browsing than watching, and increasingly rely on external discovery platforms, I believe that providing trusted human-led curation for discovery-driven film lovers will increase confident content selection and reduce churn risk, as measured by a 15% increase in Discovery-to-Play Conversion Rate. I will protect the 30+ Minute Session Rate and make a go/no-go decision after 90 days and one full Month 1 retention cycle.
