# Project Brief

## Engagement Details

| Field | Detail |
|---|---|
| Project ID | MTL-DA-003 |
| Project Title | Energy Demand, Tariff & Customer Consumption Intelligence |
| Client | Confidential Regional Energy Network & Retail Partner |
| Sector | Energy / Utilities |
| Duration | 8 weeks |
| Recommended Team Size | 5–6 |
| Primary Sponsor | Director of Customer Energy & Flexibility |
| Senior Stakeholders | Head of Network Planning, Head of Retail Pricing, Customer Insights Lead, Operations Planning Lead, Data & Analytics Lead |

## 1. Client Situation

The client operates within a regional electricity market and is exploring how household smart-meter data can support better demand forecasting, tariff design, customer segmentation and flexibility planning.

Current management reporting focuses mainly on aggregate consumption and historic billing outcomes. This gives leadership limited visibility of how demand changes by time of day, season, customer group and tariff treatment.

The organisation is especially interested in whether customers respond to time-varying price signals and whether demand can be shifted away from periods of system stress.

## 2. Business Problem

The client does not currently have a governed analytical view that brings together:

- household consumption patterns;
- half-hourly demand;
- peak demand periods;
- tariff treatment;
- seasonal behaviour;
- customer-level differences;
- potential demand-shifting behaviour.

The project team has been commissioned to build a reproducible analytical solution that supports operational and commercial decision-making.

## 3. Project Objectives

### A. Establish a trusted analytical foundation
Profile and validate the smart-meter source data, including scale, completeness, time coverage and customer-level consistency.

### B. Build a reusable time-series analytical layer
Create reproducible structures that support household, daily, weekly, monthly and half-hourly analysis.

### C. Define demand and customer KPIs
Develop clear metrics for consumption, peak demand, load profile, tariff response and customer behaviour.

### D. Understand demand patterns
Identify material differences by time period, customer cohort, tariff treatment and season.

### E. Assess tariff responsiveness
Evaluate whether customers exposed to dynamic tariffs appear to change consumption behaviour relative to appropriate comparison groups.

### F. Support demand-flexibility decisions
Provide management with clear evidence on where demand-shifting or targeted customer programmes may be worth further investigation.

## 4. Key Business Questions

1. What are the dominant daily and seasonal household demand patterns?
2. When do peak demand periods occur and how persistent are they?
3. How different are customer load profiles across the population?
4. Which customer segments contribute disproportionately to peak demand?
5. How does consumption differ between standard-tariff and dynamic-tariff customers?
6. Do high or low price signals correspond with changes in consumption?
7. Which households appear most responsive to tariff signals?
8. What indicators should management monitor routinely?
9. Where could data-quality issues distort operational conclusions?
10. What additional data would materially improve demand forecasting or customer targeting?

## 5. Expected Analytical Work

Teams are expected to:

- profile the raw files;
- design an efficient ingestion process;
- avoid loading the full dataset into memory unnecessarily;
- create time-aware transformations;
- establish customer-level and interval-level grain;
- build reusable consumption measures;
- compare tariff and non-tariff cohorts;
- investigate peak demand and seasonality;
- perform customer segmentation where justified;
- quantify uncertainty and limitations;
- build a management-facing decision-support product;
- provide a technical handover.

## 6. Constraints

- the source data is historical;
- the data must not be presented as current confidential customer data;
- raw source files must remain unchanged;
- the dataset is too large for naive spreadsheet-based processing;
- analytical transformations must be reproducible;
- observational differences must not automatically be described as causal tariff effects;
- recommendations must acknowledge sample and trial-design limitations;
- teams must not identify individual households.

## 7. Success Criteria

The project will be successful where the team can demonstrate:

- reliable large-scale data ingestion;
- correct treatment of time and customer grain;
- reproducible transformations;
- defensible KPIs;
- meaningful demand-pattern analysis;
- responsible tariff-response interpretation;
- efficient analytical workflows;
- a useful management dashboard/product;
- clear technical handover;
- visible individual contribution evidence.

## 8. Final Review

The team will present to a Mettelo review panel acting as the client's stakeholder group.

The panel may challenge:

- ingestion design;
- aggregation logic;
- tariff comparisons;
- peak definitions;
- customer segmentation;
- performance and scalability;
- assumptions;
- causal interpretation;
- recommendations;
- limitations.
