# liangyihui

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

liangyihui operates the web property at [liangyihui.net](https://www.liangyihui.net) and was surfaced as a portfolio company of the venture firm Qiming.

## Public API program: none found

As of the 2026-07-19 enrichment pass, liangyihui publishes **no public developer program**. Searched and not found: developer portal, API documentation or reference, OpenAPI / Swagger / AsyncAPI / GraphQL definition, Postman collection, MCP server, changelog, status page, pricing, terms of service, privacy policy, `security.txt`, vulnerability-disclosure program, trust center, CLI, sandbox credentials, and first-party SDK packages on npm, PyPI, Maven Central, NuGet, pkg.go.dev, RubyGems, Packagist and crates.io.

Two findings shaped this pass:

- **The site host soft-404s.** `www.liangyihui.net` returns HTTP 200 for *every* path, but the body is byte-identical to its obfuscated JavaScript bot-shield challenge (Tengine / kunlunpi CDN). A 200 from this host is not evidence a document exists — verified by checksum against a control path. Only `/robots.txt` returns a real document. The apex `liangyihui.net` does not respond.
- **A private API host exists.** `api.liangyihui.net` is live, serves a Tomcat `Welcome to LYH!` root, and returns genuine 404s. It appears to back the company's own clients; nothing about it is publicly documented.

No API artifacts have been fabricated.

## Artifacts

| Artifact | File |
|---|---|
| Domain security (probed) | `security/liangyihui-domain-security.yml` |
| Well-known probe (no documents) | `well-known/liangyihui-well-known.yml` |
| llms.txt (generated) | `llms/liangyihui-llms.txt` |
