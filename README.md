# Koobz

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
