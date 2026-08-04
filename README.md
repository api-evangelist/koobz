# Koobz

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

Koobz is a Ventura, California additive-manufacturing company rebuilding the footwear supply chain
around on-demand 3D printing. Its factory prints circular-ready, mono-material foamed-TPU shoes to
order, so brands carry zero inventory and face no minimum order quantities: a consumer buys on the
brand's own storefront, the order and personalization specs sync to the Koobz factory, and the shoe
is printed in Ventura and dropshipped to the customer in days.

Koobz markets 10x faster concept-to-market cycles (4-6 weeks, no tooling), foot-scanning and
cushioning personalization, and the KoobzWeave upper pattern engine. Its mono-material architecture
is positioned for Extended Producer Responsibility regimes such as California SB 707. The company
has raised $7.2M and is backed by Uncork Capital.

## API status

Koobz describes its factory as API-driven and its order intake as an "API sync" from brand
storefronts, but publishes **no public API surface** as of 2026-07-19: no developer portal, API
reference, OpenAPI/AsyncAPI definition, SDK, CLI, MCP server, sandbox, or first-party package on
npm, PyPI, RubyGems, Packagist or crates.io. Integration runs through the partner channel at
<https://koo.bz/contact>. This profile therefore carries identity and probe artifacts only.

## Artifacts

| Artifact | File |
|---|---|
| Well-known discovery probe | `well-known/koobz-well-known.yml` |
| Domain security posture | `security/koobz-domain-security.yml` |
| llms.txt | `llms/koobz-llms.txt` |

Backed by: uncork-capital
