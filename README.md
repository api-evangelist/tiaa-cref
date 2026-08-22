# TIAA-CREF

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

TIAA (Teachers Insurance and Annuity Association of America, formerly TIAA-CREF) is a Fortune 100 leading provider of financial services for people in the academic, research, medical, cultural, and government fields. With $1.5 trillion in assets under management, TIAA serves over 4.7 million individual customers and more than 12,000 institutional clients. Founded in 1918, TIAA invented the variable annuity in 1952 via the College Retirement Equities Fund (CREF) and is known for its TIAA Traditional fixed annuity and lifetime income solutions. TIAA wholly owns Nuveen Investments, a major institutional asset management firm.

- **Human URL:** [https://www.tiaa.org/public](https://www.tiaa.org/public)

## Description

TIAA serves primarily non-profit organizations, universities, hospitals, and government entities with retirement plans including 403(b), 457(b), and 401(k) plans. Core products include TIAA Traditional (a participating fixed annuity), CREF variable annuity accounts (Stock, Bond Market, Social Choice, Global Equities, Equity Index, Money Market, Inflation-Linked Bond), mutual funds, ETFs managed by Nuveen, and TIAA RetirePlus custom target-date strategies with embedded lifetime income.

## Links

- [TIAA Website](https://www.tiaa.org/public)
- [Plan Sponsors](https://www.tiaa.org/public/plansponsors)
- [Investment Products](https://www.tiaa.org/public/invest/services/wealth-management/investment-products)
- [Lifetime Income Solutions](https://www.tiaa.org/public/plansponsors/lifetime-income-leader)
- [Nuveen Investments](https://www.nuveen.com/)
- [Login](https://auth.tiaa.org/public/authentication/login)
- [About TIAA](https://www.tiaa.org/public/about-tiaa)
- [Wikipedia](https://en.wikipedia.org/wiki/TIAA)

## APIs

TIAA does not currently publish a public developer API. The organization provides financial services through institutional plan agreements, advisor relationships, member portals, and mobile applications.

| API | Description |
|-----|-------------|
| TIAA Retirement Plans | 403(b), 457(b), 401(k), and IRA retirement plan management |
| TIAA Annuities | TIAA Traditional, CREF variable annuities, TIAA MyChoice MYGA |
| Nuveen Investments | Mutual funds, ETFs, closed-end funds, target-date series with lifetime income |
| TIAA Wealth Management | Managed accounts, brokerage, financial advisory, insurance, 529 plans |

## Key Investment Options

| Product | Type | Description |
|---------|------|-------------|
| TIAA Traditional | Fixed Annuity | Guaranteed minimum rate + historical above-floor credits; lifetime income |
| CREF Stock Account | Variable Annuity | Broad US and international equity exposure |
| CREF Social Choice Account | Variable Annuity (ESG) | Equity with ESG screening |
| CREF Inflation-Linked Bond Account | Variable Annuity | TIPS for inflation protection |
| TIAA Secure Income Account (SIA) | Lifetime Income | Embedded in Nuveen target-date funds |
| TIAA RetirePlus | Custom Target-Date | Custom target-date with embedded TIAA lifetime income |

## Artifacts

### JSON Schema

| File | Description |
|------|-------------|
| [tiaa-cref-retirement-account-schema.json](json-schema/tiaa-cref-retirement-account-schema.json) | JSON Schema for TIAA retirement accounts covering plan types, investment allocations, and annuity contract structures |

### JSON Structure

| File | Description |
|------|-------------|
| [tiaa-cref-retirement-account-structure.json](json-structure/tiaa-cref-retirement-account-structure.json) | Structural documentation for TIAA account data models, CREF investment options, and annuity contract structures |

### JSON-LD Context

| File | Description |
|------|-------------|
| [tiaa-cref-context.jsonld](json-ld/tiaa-cref-context.jsonld) | JSON-LD context mapping TIAA-CREF financial vocabulary to schema.org and domain-specific linked data semantics |

### Vocabulary

| File | Description |
|------|-------------|
| [tiaa-cref-vocabulary.yml](vocabulary/tiaa-cref-vocabulary.yml) | Domain vocabulary covering retirement plan types, TIAA/CREF annuity products, Nuveen investment solutions, and income planning concepts |

## Tags

403b, Annuities, Asset Management, Fortune 100, Higher Education, Institutional, Insurance, Investments, Non Profit, Nuveen, Retirement, TIAA
