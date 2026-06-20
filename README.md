# Coconut (coconut)

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
