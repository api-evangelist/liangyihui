# liangyihui

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
