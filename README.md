# Configuration Language

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

Configuration languages are formats and DSLs used to express the desired state of software systems, infrastructure, applications, and APIs. Configuration languages span a spectrum from simple text-based formats (INI, JSON, YAML, TOML) to typed and templated formats (HCL, Cue, Dhall, Pkl, Jsonnet, KDL) that support imports, schemas, and validation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/configuration-language/refs/heads/main/apis.yml)

## Tags

- Configuration, DSL, Infrastructure as Code, Schemas, Serialization, Templating, YAML

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### YAML
YAML 1.2 is widely used for configuration in Kubernetes, OpenAPI, GitHub Actions, Ansible, and many other ecosystems.

**Human URL:** [https://yaml.org/](https://yaml.org/)

### JSON
RFC 8259 / ECMA-404. Heavily used in Node.js (package.json), VS Code settings, and as the foundation for JSON Schema.

**Human URL:** [https://www.json.org/](https://www.json.org/)

### TOML
Tom's Obvious, Minimal Language. Used by Cargo for Rust projects, Python pyproject.toml, and Hugo site config.

**Human URL:** [https://toml.io/](https://toml.io/)

### HCL
HashiCorp Configuration Language. Underpins Terraform, Packer, Vault, Consul, and Nomad.

**Human URL:** [https://github.com/hashicorp/hcl](https://github.com/hashicorp/hcl)

### Cue
Open source data validation language with a powerful type system and unification semantics.

**Human URL:** [https://cuelang.org/](https://cuelang.org/)

### Dhall
Programmable configuration language that adds types and functions to JSON and YAML. Total expressions, content-addressed imports.

**Human URL:** [https://dhall-lang.org/](https://dhall-lang.org/)

### Pkl
Apple's open source configuration language with a focus on type safety, composition, and runtime templating.

**Human URL:** [https://pkl-lang.org/](https://pkl-lang.org/)

### Jsonnet
Data templating language designed for elegant generation of JSON and YAML. Used in Kubernetes manifests, Grafana dashboards, and Bazel.

**Human URL:** [https://jsonnet.org/](https://jsonnet.org/)

### KDL
A node-oriented document language combining the readability of YAML and TOML with a tree-shaped grammar.

**Human URL:** [https://kdl.dev/](https://kdl.dev/)

## Common Properties

- [Wikipedia: Configuration file](https://en.wikipedia.org/wiki/Configuration_file)
- [Linux kernel configuration guide](https://docs.kernel.org/admin-guide/configuration.html)
- [Awesome Go configuration libs](https://github.com/avelino/awesome-go#configuration)
- [JSON Schema](https://json-schema.org/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
