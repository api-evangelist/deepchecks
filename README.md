# Deepchecks (deepchecks)

Deepchecks is an ML and LLM testing, evaluation, and monitoring platform. Its cloud LLM Evaluation product exposes a REST API for logging LLM interactions, managing applications and versions, retrieving annotations, and configuring evaluation properties, while its open-source Python packages provide continuous validation of tabular, computer-vision, and LLM data and models.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/deepchecks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/deepchecks/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Evaluation
- Testing
- Monitoring

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Deepchecks LLM Interactions / Logging API

Logs raw LLM interactions (input, output, context, history, and metadata) to a specific application version for evaluation, retrieves enriched interactions by filter, downloads interactions, deletes interactions, and checks interaction completion status.

- **Human URL:** [https://llmdocs.deepchecks.com/reference](https://llmdocs.deepchecks.com/reference)
- **Base URL:** `https://app.llm.deepchecks.com/api/v1`

#### Tags

- Interactions
- Logging
- LLM
- Evaluation

#### Properties

- [Documentation](https://llmdocs.deepchecks.com/docs/deepchecks-sdk)
- [API Reference](https://llmdocs.deepchecks.com/reference)
- [OpenAPI](openapi/deepchecks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepchecks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepchecks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/deepchecks)

### Deepchecks Applications / Versions API

Creates and lists evaluation applications and their versions, the organizational units that scope interactions, properties, and evaluation runs in the Deepchecks LLM Evaluation platform.

- **Human URL:** [https://llmdocs.deepchecks.com/reference](https://llmdocs.deepchecks.com/reference)
- **Base URL:** `https://app.llm.deepchecks.com/api/v1`

#### Tags

- Applications
- Versions
- Configuration

#### Properties

- [Documentation](https://llmdocs.deepchecks.com/docs/deepchecks-sdk)
- [API Reference](https://llmdocs.deepchecks.com/reference)
- [OpenAPI](openapi/deepchecks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepchecks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepchecks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/deepchecks)

### Deepchecks Annotations API

Reads automatic and manual annotations (good / bad / unknown labels and reasons) attached to logged interactions, returned alongside interactions when downloading enriched evaluation data.

- **Human URL:** [https://llmdocs.deepchecks.com/reference](https://llmdocs.deepchecks.com/reference)
- **Base URL:** `https://app.llm.deepchecks.com/api/v1`

#### Tags

- Annotations
- Labels
- Evaluation

#### Properties

- [Documentation](https://llmdocs.deepchecks.com/docs/deepchecks-sdk)
- [API Reference](https://llmdocs.deepchecks.com/reference)
- [OpenAPI](openapi/deepchecks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepchecks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepchecks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/deepchecks)

### Deepchecks Properties API

Configures LLM property definitions and display names per application, governing the built-in and custom properties (relevance, grounded-in-context, toxicity, PII, and more) that Deepchecks computes over logged interactions.

- **Human URL:** [https://llmdocs.deepchecks.com/reference](https://llmdocs.deepchecks.com/reference)
- **Base URL:** `https://app.llm.deepchecks.com/api/v1`

#### Tags

- Properties
- Metrics
- Custom Properties

#### Properties

- [Documentation](https://llmdocs.deepchecks.com/docs/deepchecks-sdk)
- [API Reference](https://llmdocs.deepchecks.com/reference)
- [OpenAPI](openapi/deepchecks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepchecks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepchecks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/deepchecks)

### Deepchecks Open-Source Testing

The AGPL-3.0 licensed open-source Python package for continuous validation of tabular, computer-vision, and LLM/NLP data and models. Distributed via PyPI (pip install deepchecks); a Python library rather than a hosted HTTP API.

- **Human URL:** [https://github.com/deepchecks/deepchecks](https://github.com/deepchecks/deepchecks)
- **Base URL:** `https://github.com/deepchecks/deepchecks`

#### Tags

- Open Source
- Testing
- Validation
- Python

#### Properties

- [Documentation](https://docs.deepchecks.com/stable/getting-started/welcome.html)
- [GitHub](https://github.com/deepchecks/deepchecks)

## Common Properties

- [GitHub Organization](https://github.com/deepchecks)
- [LinkedIn](https://www.linkedin.com/company/deepchecks)
- [Website](https://www.deepchecks.com)
- [Documentation](https://llmdocs.deepchecks.com)
- [Plans](plans/deepchecks-plans-pricing.yml)
- [Rate Limits](rate-limits/deepchecks-rate-limits.yml)
- [Fin Ops](finops/deepchecks-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
