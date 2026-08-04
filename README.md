# Underwriting Standards

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

A curated collection of data standards, APIs, and specifications used in insurance underwriting. This covers the landscape of industry-wide data interchange formats, protocol standards, and API ecosystems that enable carriers, MGAs, brokers, and InsurTech platforms to exchange underwriting data programmatically.

Key standards include ACORD (Property & Casualty, Life, Reinsurance), LIMRA LDEx (employee benefits), and emerging OpenInsurance initiatives.

## Standards

### ACORD Next-Generation Digital Standards (NGDS)

ACORD provides the insurance industry's primary data standards. The NGDS are JSON/YAML-based transaction-centric standards for RESTful APIs and microservices, covering Policy, Claims, Party, Product, and Reinsurance entities.

- **Website:** https://www.acord.org/
- **NGDS Documentation:** https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards

### LIMRA LDEx Data Exchange Standards

Free, collaboratively developed standards for exchanging employee workplace benefits data between carriers and benefits administration platforms. LDEx provides REST API endpoints compliant with OpenAPI 3.1.

- **Website:** https://www.limra.com/
- **Documentation:** https://www.limra.com/en/solutions-and-services/data-exchange-standards/ldex-overview/

## Artifacts

### JSON Schema

| File | Description |
|------|-------------|
| [json-schema/underwriting-standards-submission-schema.json](json-schema/underwriting-standards-submission-schema.json) | Schema for an insurance underwriting submission including risk, coverages, quotes, and documents |

### JSON Structure

| File | Description |
|------|-------------|
| [json-structure/underwriting-standards-submission-structure.json](json-structure/underwriting-standards-submission-structure.json) | Field-level documentation for the Underwriting Submission entity |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/underwriting-standards-context.jsonld](json-ld/underwriting-standards-context.jsonld) | JSON-LD context mapping underwriting terms to schema.org and FIBO ontology vocabulary |

### Examples

| File | Description |
|------|-------------|
| [examples/underwriting-standards-submission-example.json](examples/underwriting-standards-submission-example.json) | Example cyber liability underwriting submission following ACORD data standards |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/underwriting-standards-vocabulary.yml](vocabulary/underwriting-standards-vocabulary.yml) | Domain vocabulary covering underwriting process, risk assessment, coverage concepts, data standards, and InsurTech |

## Related Resources

- [ACORD Data Standards](https://www.acord.org/standards-architecture/acord-data-standards)
- [LIMRA LDEx Standards](https://www.limra.com/en/solutions-and-services/data-exchange-standards/)
- [ACORD Reference Architecture](https://www.acord.org/standards-architecture/reference-architecture)
- [Open Insurance Initiative](https://openinsurance.io/)
