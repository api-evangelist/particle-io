# Particle (particle-io)

Particle is an end-to-end IoT platform combining cellular and Wi-Fi connectivity, hardware modules (Photon, Boron, Tracker, B-SoM, M-SoM), firmware, and a Device Cloud. The Particle Device Cloud exposes a REST API for fleet management, device control, cloud functions and variables, webhooks and integrations, OTA firmware updates, SIM management, and customer and product administration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/particle-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/particle-io/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Cellular
- Cloud Functions
- Connectivity
- Device Management
- Edge
- Firmware
- Fleet Management
- IoT
- OTA
- Webhooks
- Wi-Fi

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Particle Device Cloud API

The Particle Device Cloud REST API is the primary interface to the Particle platform. Use it to claim and manage devices, list and call cloud functions, read cloud variables, subscribe to events, manage webhooks and integrations, administer products and fleets, manage SIM cards, and orchestrate OTA firmware updates.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/api/](https://docs.particle.io/reference/cloud-apis/api/)
- **Base URL:** `https://api.particle.io`

#### Tags

- Cloud Functions
- Devices
- Events
- Fleet Management
- Integrations
- Variables
- Webhooks

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/api/)
- [Authentication](https://docs.particle.io/reference/cloud-apis/access-tokens/)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle OAuth 2.0 API

OAuth 2.0 endpoints for creating, listing, and deleting access tokens used to authenticate against the Particle Device Cloud API.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/access-tokens/](https://docs.particle.io/reference/cloud-apis/access-tokens/)
- **Base URL:** `https://api.particle.io`

#### Tags

- Access Tokens
- Authentication
- OAuth2

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/access-tokens/)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Devices API

List, claim, rename, and inspect Particle devices, request remote diagnostics and vitals, and control device signal LEDs.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/api/#devices](https://docs.particle.io/reference/cloud-apis/api/#devices)
- **Base URL:** `https://api.particle.io`

#### Tags

- Devices
- Diagnostics
- Vitals

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/api/#devices)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Functions and Variables API

Invoke cloud-callable firmware functions and read cloud-exposed variables on Particle devices.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/api/#functions](https://docs.particle.io/reference/cloud-apis/api/#functions)
- **Base URL:** `https://api.particle.io`

#### Tags

- Cloud Functions
- Devices
- Variables

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/api/#functions)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Events API

Publish events from the cloud to devices and subscribe to a Server-Sent Events stream of device, product, or public events.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/api/#events](https://docs.particle.io/reference/cloud-apis/api/#events)
- **Base URL:** `https://api.particle.io`

#### Tags

- Events
- Pub Sub
- SSE

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/api/#events)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Webhooks and Integrations API

Create and manage webhooks and integrations that forward device events to external services such as Azure IoT Hub, Google Cloud Pub/Sub, and arbitrary HTTP endpoints.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/api/#integrations-webhooks](https://docs.particle.io/reference/cloud-apis/api/#integrations-webhooks)
- **Base URL:** `https://api.particle.io`

#### Tags

- Integrations
- Webhooks

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/api/#integrations-webhooks)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Products API

Manage product fleets including importing and listing devices, configuring OAuth clients, and orchestrating OTA firmware releases across product devices.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/api/#products](https://docs.particle.io/reference/cloud-apis/api/#products)
- **Base URL:** `https://api.particle.io`

#### Tags

- Fleet Management
- OTA
- Products

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/api/#products)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle SIM Cards API

List, activate, deactivate, and inspect Particle cellular SIM cards including data usage and network status.

- **Human URL:** [https://docs.particle.io/reference/cloud-apis/api/#sim-cards](https://docs.particle.io/reference/cloud-apis/api/#sim-cards)
- **Base URL:** `https://api.particle.io`

#### Tags

- Cellular
- SIM

#### Properties

- [Documentation](https://docs.particle.io/reference/cloud-apis/api/#sim-cards)
- [Postman Collection](collections/particle-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.particle.io/)
- [Developer](https://docs.particle.io/)
- [Documentation](https://docs.particle.io/reference/cloud-apis/api/)
- [SDK](https://github.com/particle-iot/particle-api-js)
- [C L I](https://docs.particle.io/reference/developer-tools/cli/)
- [Git Hub](https://github.com/particle-iot)
- [Blog](https://blog.particle.io/)
- [Pricing](https://www.particle.io/pricing/)
- [Status Page](https://status.particle.io/)
- [Support](https://support.particle.io/)
- [Community](https://community.particle.io/)
- [Privacy Policy](https://www.particle.io/legal/)
- [Terms of Service](https://www.particle.io/legal/)
- [LinkedIn](https://www.linkedin.com/company/particle-)
- [Changelog](https://docs.particle.io/reference/changelog/)
- [Integrations](https://docs.particle.io/reference/cloud-apis/api/#integrations-webhooks)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
