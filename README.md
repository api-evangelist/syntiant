# Syntiant

Syntiant Corp is an Irvine, California edge-AI semiconductor company founded in 2017. It designs
ultra-low-power Neural Decision Processors (NDP100/101, NDP102, NDP115, NDP120, NDP200, NDP250) and
the deep-learning models and tooling that run on them, putting always-on speech, audio, sensor and
vision inference into battery-powered devices without a cloud connection. In December 2024 Syntiant
completed the USD 150 million acquisition of Knowles Corporation's Consumer MEMS Microphones
business, taking the company from roughly 70 to nearly 1,700 employees.

- https://www.syntiant.com/
- https://github.com/syntiant

## API surface

Syntiant is a silicon, module and embedded-software supplier, not an API provider. As of 2026-08-02
enrichment found **no public web API**: no OpenAPI/Swagger/GraphQL/AsyncAPI contract, no developer
portal, no MCP server, no A2A agent card, no webhook or event surface, and no first-party client
libraries on npm, PyPI, crates.io or any other public registry. The Syntiant SDK and Training
Development Kit (TDK) are embedded toolchains delivered to customers under agreement through a
private GitLab.

`www.syntiant.com` sits behind a SiteGround bot wall that answers automated requests with HTTP 202
and a captcha meta-refresh shell, so no path on the site can be confirmed by probe. See
`well-known/syntiant-well-known.yml` for the recorded negative result.
