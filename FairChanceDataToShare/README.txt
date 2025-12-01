README: Fair Chance Hiring Policy Indices


Contents

* PositiveIndex.csv
* NegativeIndex.csv
* IndeedFairChance_August2024.csv
* IndeedFairChance_October2024.csv
* FairChancePolicyIndexMetadata.csv
* FairChanceEmploymentMetricsMetadata.csv


Positive Policy Indices

We focus on five key policies commonly considered beneficial for job-seekers with records:
* Ban-the-box laws
* Laws that reduce barriers to occupational licensing
* Record-clearing laws
* Certificates of rehabilitation
* Business liability protections
For each policy type, we collect data and create a metric, with 1 representing the strongest policy and 0 representing the weakest. We then calculate the Positive Policy Index as the average of these five policy metrics.


Negative Policy Indices

We also capture and quantify the impact of various legal and regulatory barriers that can restrict a person’s ability to find employment. For each state, we compute the Negative Policy Index, the primary measure of punitive employment policies.
This index combines two underlying measures:
1. Negative Policy Count – the total number of employment-related restrictions in a state.
2. Average Negative Policy Strength – the typical severity of those restrictions.
By multiplying these two measures, the Negative Policy Index captures both the prevalence and intensity of restrictive policies, offering a comprehensive assessment of how state-level policies impact employment opportunities for individuals with criminal records.


Fair Chance Employment Data

In addition to state policy indicators, we include empirical data describing the actual availability of fair-chance job opportunities in the labor market.
Two files, IndeedFairChance_August2024.csv and IndeedFairChance_October2024.csv, contain state-level and industry-level counts of job postings scraped from Indeed.com:
* total_jobs — the total number of job postings in a given state × industry category.
* fair_chance_jobs — the subset of postings labeled by Indeed as “Fair Chance” (under the Encouraged to Apply filter).
* state — U.S. state where postings were aggregated.
* industry — the industry category assigned by Indeed (e.g., retail, food service).
These datasets provide a view of fair-chance employment opportunities as they appear in real time on a major job platform. They can be used to measure:
* the prevalence of fair-chance jobs by state,
* sectoral differences in fair-chance hiring,
* and changes in opportunities across different collection periods (e.g., August vs. October 2024).


Metadata

Further details on the data acquisition and processing procedures for the policy indices are available in the FairChancePolicyIndexMetadata.csv file.
Parallel documentation for the Indeed employment data is provided in the FairChanceEmploymentMetricsMetadata.csv file.


Acknowledgements

QSIDE has partnered with the Responsible Business Initiative for Justice (RBIJ) and Jobs for the Future (JFF) to build a robust research framework identifying effective practices for hiring people with criminal records.
This work is made possible through this partnership and is supported by The Justice and Mobility Fund, a collaboration launched by The Ford Foundation and Blue Meridian Partners, with support from The Charles and Lynn Schusterman Family Philanthropies.
We express our gratitude to our community partners, the Responsible Business Initiative for Justice and Jobs for the Future. Their insights, wisdom, and partnership have proved invaluable in this work.


Suggested Citation

Bliven, J., Johnson, A., Stanley, Z. C., Topaz, C. M., Chalfin, A., Higdon, J., & Bass, T. (2025). Quantifying Fair Chance Policy Implementation and Employer Engagement. The Prison Journal, 105(4), 446–471. [https://doi.org/10.1177/00328855251355496](https://doi.org/10.1177/00328855251355496) (Original work published 2025)
