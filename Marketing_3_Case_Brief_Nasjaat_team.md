# Marketing 3 — Nasjaat, Anastasia, Tapiwa

**Business context:** Local grocery loyalty programme with a limited personalised-offer budget.

**Business problem:** Select eligible loyalty customers for a personalised offer campaign while limiting unnecessary contact and campaign cost.

**Stakeholder and decision:** The campaign manager must select up to 12% of eligible customer-campaign opportunities for an offer.

**Proposed success criteria (exercise assumptions, to review):** Compare against an all-nonconverter baseline; justify a threshold under a 12% contact-capacity limit; discuss precision, recall and illustrative contribution. The dataset cannot prove incremental uplift.

**Observation unit:** One customer-campaign opportunity. **Business key:** customer_id + campaign_id. **Target:** conversion_flag. **Prediction moment:** Before sending the campaign.

**Data challenges:** Push/push categories; discount represented as both fraction and percent; exact duplicate rows; negative campaign cost; missing average basket; overlapping historical purchase features. clicks_after_campaign and purchase_revenue_after_campaign_eur are post-campaign fields and must NOT be predictors. Consider justified features such as customer activity or potential value; explain whether combining variables improves the business decision.

**Your task:** Use the same 90-minute CRISP-DM Phases 3–6 group assignment as the other teams. Critique the supplied Business Understanding, document three preparation decisions, compare a baseline and model, evaluate against business goals and propose a monitored deployment workflow.
