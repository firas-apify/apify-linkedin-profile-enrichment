# LinkedIn Profile Enrichment for B2B Leads

## Idea
Deliver a B2B enrichment actor: input company domains/titles, output LinkedIn profile details plus role fit, seniority, and lead scoring fields for outbound teams.

## Why this is trending/sellable
- `Linkedin-Profile-Scraper` has `2935` users in 30 days and a visible paid model (`$0.01` per result).
- LinkedIn-related actors repeatedly appear in top 30-day usage and paid lists.

## How to implement
1. Inputs: keywords, company filters, job titles, locations, seniority levels.
2. Discovery: search + profile extraction with robust pagination and checkpointing.
3. Enrichment: role normalization, company-size inference, and ideal customer profile scoring.
4. Validation: deduplication, confidence score, and missing-field fill rules.
5. Export: CRM-ready schema (HubSpot/Salesforce friendly field map).
6. Compliance: clear ToS boundaries and user-side consent reminders.

## Monetization
- `PRICE_PER_DATASET_ITEM` with strong data quality positioning.
- Agency bundle: monthly flat plan with higher concurrency and support SLA.
