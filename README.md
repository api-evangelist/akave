# Akave

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

Akave is a decentralized, S3-compatible object storage company. Akave Cloud and the Akave O3 gateway expose an S3-compatible API usable with AWS SDKs and CLI tools, backed by the Akave (Oasis) protocol with encryption, erasure coding and on-chain data integrity. Akave also publishes Akavelink, a self-hostable REST API for buckets and files, the Akave CLI and Go/Python SDKs over a gRPC node API, and an MCP server (akave-mcp-js) for AI agents.

**Areas:** Company · Object Storage · S3 Compatible · Decentralized Storage · Cloud Storage · gRPC · MCP

## Akave on APIs.io

Everything profiled for Akave is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/akave/](https://apis.io/providers/akave/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Akave O3 S3-Compatible API](https://apis.io/apis/akave/akave-o3/) — S3-compatible object storage API for Akave decentralized storage; works with AWS SDKs, AWS CLI and Terraform. Credentials and a per-credential endpoint URL…
- [Akave IPC Node gRPC API](https://apis.io/apis/akave/ipc-node-api/) — gRPC services IPCNodeAPI and IPCArchivalAPI (package ipcnodeapi) used by the Akave Go SDK and CLI to talk to Akave nodes; published as a .proto in the…
- [Akave Buckets API](https://apis.io/apis/akave/akave-buckets-api/) — The Buckets API from Akave — 5 operation(s) for buckets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [akave-mcp-js](https://apis.io/servers/akave/akave-mcp-js/)

#### JSON Schema (6)

The data models the API reads and writes.

- [DeleteBucketsMybucketResponse](https://apis.io/schemas/akave/akave-delete-buckets-mybucket-response/)
- [GetBucketsMybucketFilesMyfileTxtDownloadResponse](https://apis.io/schemas/akave/akave-get-buckets-mybucket-files-myfile-txt-download-response/)
- [GetBucketsMybucketFilesMyfileTxtResponse](https://apis.io/schemas/akave/akave-get-buckets-mybucket-files-myfile-txt-response/)
- [GetBucketsMybucketFilesResponse](https://apis.io/schemas/akave/akave-get-buckets-mybucket-files-response/)
- [GetBucketsMybucketResponse](https://apis.io/schemas/akave/akave-get-buckets-mybucket-response/)
- [GetBucketsResponse](https://apis.io/schemas/akave/akave-get-buckets-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Akave Context](https://apis.io/jsonld/akave/akave-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Akave API Rules](https://apis.io/rules/akave/akave-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Akave Domain Security](https://apis.io/security/akave/akave-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://akave.com)
- [Documentation](https://docs.akave.xyz/)
- [Getting started](https://docs.akave.xyz/akave-o3/introduction/setup/)
- [Pricing](https://akave.com/akave-cloud-pricing)
- [Blog](https://akave.com/blog)
- [Terms of service](https://akave.com/terms-of-service)
- [Privacy policy](https://akave.com/privacy-policy)
- [GitHub](https://github.com/akave-ai)

## API Evangelist rating

**Kin Score 31.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 22.6 |
| Contract governance | 19.7 |
| Operational transparency | 5.3 |
| Developer ergonomics | 33.3 |
| Access clarity | 44.7 |

**Agent readiness 21.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 18.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/akave/](https://apis.io/providers/akave/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Akave: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/akave/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
