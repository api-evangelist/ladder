# Ladder

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ladder (Ladder Financial Inc., operating as Ladder Insurance Services, LLC) is a digital life insurance company founded in 2015 that sells flexible term life insurance fully online — a few health questions, no medical exam for policies up to $3M, 10-to-30 year terms, and "laddering" that lets a policyholder raise or lower coverage as circumstances change. Policies are underwritten by partner carriers (Amica Life, Fidelity Security Life, and S.USA Life / Prosperity Life Group).

Alongside the direct-to-consumer product, Ladder runs an embedded insurance distribution business. The [Ladder API](https://www.ladderlife.com/api) lets fintech, lending, investing, benefits, and health-and-wellness platforms embed quoting and a full term-life application into their own site or app in roughly ten lines of JavaScript, across five surfaces:

- **Embeddable API** — the full white-labeled application flow, mounted into a container element
- **Quoter API** — price estimates rendered in the partner's UI
- **Connector** — pre-fills known applicant data and deep-links into Ladder's application
- **Calculator** — coverage-needs sizing questionnaire
- **Account Manager** — in-app servicing of existing Ladder policies

Access is granted by partner request; reference documentation is not public, and Ladder publishes no OpenAPI definition. Ladder does publish an RFC 9116 `security.txt` and a full responsible-disclosure policy.

Backed by: canaan-partners, general-catalyst, lightspeed-venture-partners
