# Federal Housing Finance Agency (FHFA) (fhfa)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Federal Housing Finance Agency (FHFA) is an independent federal regulator established in 2008 that supervises Fannie Mae, Freddie Mac, and the Federal Home Loan Bank System. FHFA provides publicly accessible data APIs and datasets covering house price indexes (FHFA HPI), mortgage market surveys, conforming loan limits, National Mortgage Database (NMDB) aggregate statistics, Public Use Databases (PUDB) for Fannie Mae and Freddie Mac, Uniform Appraisal Dataset (UAD) statistics, and GSE performance and duty-to-serve data. Data is available in CSV, JSON, XML, and Excel formats with open public access under FHFA's API Terms of Service.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fhfa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fhfa/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Housing Finance
- House Price Index
- Mortgage
- Government
- GSE
- Fannie Mae
- Freddie Mac
- Federal

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### FHFA House Price Index (HPI) API

The FHFA House Price Index (HPI) is a comprehensive, publicly available dataset measuring changes in single-family home values across all 50 states and over 400 American cities, with data extending back to the mid-1970s. The HPI uses a weighted repeat-sales methodology based on tens of millions of home sales and is available in CSV, JSON, and XML formats at monthly and quarterly intervals. Datasets include purchase-only indexes, all-transaction indexes incorporating appraisal data, expanded-data indexes adding FHA and county recorder data, and volatility parameters. Data is free and publicly accessible with attribution required under FHFA API Terms of Service.

- **Human URL:** [https://www.fhfa.gov/data/hpi](https://www.fhfa.gov/data/hpi)

#### Tags

- House Price Index
- Housing
- CSV
- JSON
- XML

#### Properties

- [Documentation](https://www.fhfa.gov/data/hpi)
- [Datasets](https://www.fhfa.gov/data/hpi/datasets)
- [Data Download C S V](https://www.fhfa.gov/hpi/download/monthly/hpi_master.csv)
- [Data Download X M L](https://www.fhfa.gov/hpi/download/monthly/hpi_master.xml)
- [Data Dictionary](https://www.fhfa.gov/sites/default/files/2023-09/HPI_dictionary.xls)
- [Summary Tables](https://www.fhfa.gov/data/hpi/summary-tables)
- [Calculator](https://www.fhfa.gov/hpi-calculator)

### FHFA National Mortgage Database (NMDB) API

The National Mortgage Database (NMDB) is a nationally representative, longitudinal database of residential mortgages providing aggregate statistics on outstanding residential mortgages and mortgage originations. Data covers loan characteristics, borrower demographics, and geographic distributions. NMDB aggregate statistics and National Survey of Mortgage Originations (NSMO) data are downloadable as CSV files with interactive Tableau dashboards for visualization.

- **Human URL:** [https://www.fhfa.gov/data/nmdb](https://www.fhfa.gov/data/nmdb)

#### Tags

- Mortgage
- National Mortgage Database
- Statistics
- CSV

#### Properties

- [Documentation](https://www.fhfa.gov/data/nmdb)
- [Related Dataset](https://www.fhfa.gov/data/nsmo)
- [Dashboard](https://www.fhfa.gov/data/dashboard/nmdb-outstanding-residential-mortgage-statistics)

### FHFA Enterprise Public Use Database (PUDB) API

The FHFA Enterprise Public Use Database (PUDB) provides loan-level data on single-family and multifamily mortgages acquired by Fannie Mae and Freddie Mac, as well as data on Federal Home Loan Bank member institutions. Files include National File A, B, and C for single-family mortgages and property-level and unit-class-level files for multifamily. Data is downloadable as zipped CSV files with accompanying data dictionaries.

- **Human URL:** [https://www.fhfa.gov/data/pudb](https://www.fhfa.gov/data/pudb)

#### Tags

- Fannie Mae
- Freddie Mac
- GSE
- Mortgage
- Public Use Database
- CSV

#### Properties

- [Documentation](https://www.fhfa.gov/data/pudb)
- [Overview](https://www.fhfa.gov/data/public-use-database)

### FHFA Conforming Loan Limits API

FHFA publishes annual conforming loan limit (CLL) values establishing the maximum mortgage amounts that Fannie Mae and Freddie Mac may purchase. Data is available at the county level for all U.S. states and territories, downloadable in XLSX, CSV, and PDF formats. Limits are adjusted annually per the Housing and Economic Recovery Act (HERA) formula, with higher limits for designated high-cost areas.

- **Human URL:** [https://www.fhfa.gov/data/conforming-loan-limit](https://www.fhfa.gov/data/conforming-loan-limit)

#### Tags

- Conforming Loan Limits
- Fannie Mae
- Freddie Mac
- Mortgage
- CSV

#### Properties

- [Documentation](https://www.fhfa.gov/data/conforming-loan-limit)

### FHFA Uniform Appraisal Dataset (UAD) Aggregate Statistics API

The FHFA Uniform Appraisal Dataset (UAD) Aggregate Statistics provide data on residential appraisals submitted to Fannie Mae and Freddie Mac, covering appraisal values, property characteristics, and geographic distributions. An Appraisal-Level Public Use File (PUF) with anonymized individual appraisal records is also available for research.

- **Human URL:** [https://www.fhfa.gov/data/uad](https://www.fhfa.gov/data/uad)

#### Tags

- Appraisal
- UAD
- Housing
- Statistics

#### Properties

- [Documentation](https://www.fhfa.gov/data/uad)
- [Public Use File](https://www.fhfa.gov/data/uad/puf)
- [Dashboard](https://www.fhfa.gov/data/dashboard)

## Common Properties

- [Website](https://www.fhfa.gov)
- [Documentation](https://www.fhfa.gov/data/developer-information)
- [Terms of Service](https://www.fhfa.gov/about/fhfa-policies/api-terms-of-service)
- [Datasets](https://www.fhfa.gov/data/datasets)
- [Blog](https://www.fhfa.gov/news)
- [LinkedIn](https://www.linkedin.com/company/fhfa)
- [X (Twitter)](https://x.com/FHFA)
- [Git Hub Org](https://github.com/fhfa)
- [Plans](plans/fhfa-plans-pricing.yml)
- [Rate Limits](rate-limits/fhfa-rate-limits.yml)
- [Fin Ops](finops/fhfa-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
