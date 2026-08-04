# Coconut (coconut)

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

Coconut is a cloud video and audio encoding/transcoding service. The Coconut API v2 lets developers submit a single asynchronous job that transcodes source media into multiple formats, packages adaptive HLS/MPEG-DASH streams, and generates thumbnails and GIF animations, delivering results to cloud storage and reporting progress through webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coconut/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coconut/refs/heads/main/apis.yml)

## Tags

- Video
- Audio
- Encoding
- Transcoding
- Media

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Coconut Jobs API

Create an asynchronous encoding job with a single request - specify an input source, storage destination, output formats (MP4, WebM, HLS, MPEG-DASH, thumbnails, GIF), and a webhook notification - then retrieve the job and its status and progress.

- **Human URL:** [https://docs.coconut.co/jobs/api](https://docs.coconut.co/jobs/api)
- **Base URL:** `https://api.coconut.co/v2`

#### Tags

- Jobs
- Encoding
- Transcoding

#### Properties

- [Documentation](https://docs.coconut.co/jobs/api)
- [API Reference](https://docs.coconut.co/jobs/api)
- [OpenAPI](openapi/coconut-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coconut.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coconut.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coconut Metadata API

Retrieve technical metadata (codec, stream, and format details) for the input source and output files of a completed job, for all keys or a specific output key.

- **Human URL:** [https://docs.coconut.co/metadata/api](https://docs.coconut.co/metadata/api)
- **Base URL:** `https://api.coconut.co/v2`

#### Tags

- Metadata
- Streams
- Probe

#### Properties

- [Documentation](https://docs.coconut.co/metadata/api)
- [API Reference](https://docs.coconut.co/metadata/api)
- [OpenAPI](openapi/coconut-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coconut.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coconut.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coconut Webhooks API

Configured per job via the notification object, Coconut POSTs JSON event payloads (input.transferred, output.completed, output.failed, job.completed, job.failed) to a caller-supplied URL, optionally including per-event and metadata detail.

- **Human URL:** [https://docs.coconut.co/jobs/notification](https://docs.coconut.co/jobs/notification)
- **Base URL:** `https://api.coconut.co/v2`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://docs.coconut.co/jobs/notification)
- [API Reference](https://docs.coconut.co/jobs/notification)
- [OpenAPI](openapi/coconut-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coconut.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coconut.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/opencoconut)
- [LinkedIn](https://www.linkedin.com/company/coconut-co)
- [Website](https://www.coconut.co)
- [Documentation](https://docs.coconut.co)
- [Plans](plans/coconut-plans-pricing.yml)
- [Rate Limits](rate-limits/coconut-rate-limits.yml)
- [Fin Ops](finops/coconut-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
