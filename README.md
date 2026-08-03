# Advanced Micro Devices (advanced-micro-devices)

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

Advanced Micro Devices (AMD) is a global semiconductor company that develops high-performance computing, graphics, and visualization technologies for data centers, gaming, and embedded markets. AMD provides the ROCm open software platform for GPU computing, HIP programming interface, and the AMD Developer Cloud for AI workloads using AMD Instinct GPUs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/advanced-micro-devices/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/advanced-micro-devices/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- Cloud Computing
- GPU
- HPC
- Machine Learning
- Semiconductor

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### AMD Developer Cloud API

The AMD Developer Cloud API provides access to AMD Instinct GPU instances for AI inference, training, and HPC workloads. Supports managing compute instances, deploying AI models, monitoring GPU utilization, and integrating with ROCm-compatible frameworks including PyTorch, TensorFlow, and vLLM.

- **Human URL:** [https://developer.amd.com](https://developer.amd.com)
- **Base URL:** `https://api.developer.amd.com/v1`

#### Tags

- AI
- Cloud Computing
- GPU
- HPC
- Instinct

#### Properties

- [Documentation](https://developer.amd.com)
- [OpenAPI](openapi/amd-developer-cloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amd-developer-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amd-developer-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [JSON-LD](json-ld/amd-developer-cloud-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/amd-spectral-rules.yml)
- [Vocabulary](vocabulary/advanced-micro-devices-vocabulary.yaml)

### AMD ROCm API

The AMD ROCm (Radeon Open Compute) platform provides the runtime and library APIs for GPU-accelerated computing on AMD hardware. Includes HIP (Heterogeneous-compute Interface for Portability), math libraries (rocBLAS, rocFFT, rocRAND), and communication libraries (RCCL) for high-performance computing and AI workloads.

- **Human URL:** [https://rocm.docs.amd.com](https://rocm.docs.amd.com)
- **Base URL:** `https://rocm.docs.amd.com/en/latest`

#### Tags

- GPU
- HPC
- Machine Learning
- ROCm
- SDK

#### Properties

- [Documentation](https://rocm.docs.amd.com)
- [OpenAPI](openapi/amd-rocm-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amd-rocm-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amd-rocm-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [JSON-LD](json-ld/amd-rocm-management-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/amd-spectral-rules.yml)
- [Vocabulary](vocabulary/advanced-micro-devices-vocabulary.yaml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/amd)
- [Website](https://www.amd.com)
- [Portal](https://developer.amd.com)
- [Documentation](https://rocm.docs.amd.com)
- [Getting Started](https://developer.amd.com/resources/rocm-resources/)
- [Support](https://developer.amd.com/support/)
- [Blog](https://www.amd.com/en/corporate/blog.html)
- [Terms of Service](https://www.amd.com/en/legal/terms-and-conditions.html)
- [Privacy Policy](https://www.amd.com/en/legal/privacy.html)
- [GitHub Organization](https://github.com/ROCm)
- [Academy](https://academy.amd.com)
- [Sign Up](https://developer.amd.com/amd-developer-cloud/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
