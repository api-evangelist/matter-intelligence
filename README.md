# Matter Intelligence

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

Matter Intelligence is a California-based remote sensing and physical-AI company founded in 2024 by
former NASA Jet Propulsion Laboratory engineers Vishnu Sridhar and Thomas Chrien with former Caltech
scientist Nathan Stein. It builds ultraspectral imaging sensors that capture roughly 2,000 spectral
bands from deep ultraviolet through thermal infrared — enough to read the molecular chemistry of a
surface rather than only its color — and pairs them with Large Geospatial Models. Its first satellite,
EARTH-1, is intended to deliver sub-meter hyperspectral and thermal imaging. The company emerged from
stealth in October 2024 with a $12M seed round led by Lowercarbon Capital (Toyota Ventures, Pear VC,
E2MC and Mark Cuban participating).

- Website: https://www.matter.com/
- GitHub: https://github.com/matter-intelligence (0 public repositories)
- Early access: https://matterintelligence.typeform.com/earlyaccess

## No API surface (checked 2026-08-25)

Matter Intelligence publishes no API, developer portal, documentation, SDK or machine-readable
contract. Probed on 2026-08-25:

- `api.`, `docs.`, `developer.`, `developers.`, `app.`, `console.`, `platform.`, `data.`, `mcp.`,
  `status.` and `blog.` .matter.com — all NXDOMAIN.
- `www.matter.com` `/openapi.json`, `/openapi.yaml`, `/swagger.json`, `/v1/openapi.json`, `/api-docs`,
  `/docs`, `/redoc`, `/graphql`, `/llms.txt` — all HTTP 404.
- Every `/.well-known/` path (security.txt, api-catalog, agent-card.json, agent.json, ai-plugin.json,
  openid-configuration, oauth-authorization-server, oauth-protected-resource) — all HTTP 404. Recorded
  in `well-known/matter-intelligence-well-known.yml`.
- No packages on npm or PyPI; no MCP server; no A2A agent card.

The earlier stub listed https://www.nasdaqprivatemarket.com/ as this company's website. That was the
secondary-market venue it was harvested from, not Matter Intelligence's site; it has been corrected to
https://www.matter.com/.

## Artifacts in this repo

| Path | Type | Method |
|---|---|---|
| `security/matter-intelligence-domain-security.yml` | DomainSecurity | probed |
| `well-known/matter-intelligence-well-known.yml` | (absence recorded — no pointer) | probed |
| `plans/matter-intelligence-plans-pricing.yml` | Plans (plan_count: 0) | searched |
| `llms/matter-intelligence-llms.txt` | LLMsTxt | generated |
