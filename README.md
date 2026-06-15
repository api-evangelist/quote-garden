# Quote Garden (quote-garden)

Quote Garden is a free, open-source REST API that serves more than 75,000 famous quotes. Built by Prathamesh More (pprathameshmore) in Node.js + Express + MongoDB, it exposes a small read-only HTTP surface for fetching random quotes, paginated quote lists filterable by author, genre, and full-text query, plus master lists of all authors and genres. There is no authentication and no cost to use; the canonical reference implementation is hosted on Render at https://quote-garden.onrender.com/api/v3 and was previously deployed on Heroku at quote-garden.herokuapp.com. The project also ships an official npm client wrapper (`@pprathameshmore/quotegardennpm`) and is widely embedded in third-party chrome extensions, mobile apps, and Twitter bots that need a lightweight inspirational-quote source.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Quotes
- Inspiration
- Open Source
- Free API
- Node.js
- MongoDB
- Express
- Personality
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Quote Garden REST API

Read-only REST API exposing a database of 75,000+ famous quotes. Returns JSON with a consistent envelope (statusCode, message, pagination, totalQuotes, data). Supports filtering by author, genre, and full-text query, plus pagination via page/limit query parameters. The v3 API is the only supported version; older versions (v1/v2) are deprecated.

- **Human URL:** [https://pprathameshmore.github.io/QuoteGarden/](https://pprathameshmore.github.io/QuoteGarden/)
- **Base URL:** `https://quote-garden.onrender.com/api/v3`

#### Tags

- Quotes
- REST
- Open Source
- Free API

#### Properties

- [Documentation](https://github.com/pprathameshmore/QuoteGarden#readme)
- [API Reference](https://github.com/pprathameshmore/QuoteGarden#api-documentation)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/openapi/quote-garden-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/json-schema/quote-garden-quote-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/json-schema/quote-garden-response-envelope-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/json-structure/quote-garden-quote-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/json-structure/quote-garden-response-envelope-structure.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/json-ld/quote-garden-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/examples/quote-garden-get-random-quote-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/examples/quote-garden-list-quotes-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/examples/quote-garden-list-genres-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/examples/quote-garden-list-authors-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/examples/quote-garden-quote-example.json)
- [Example](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/examples/quote-garden-response-envelope-example.json)
- [SDK](https://github.com/pprathameshmore/QuoteGardenNPM)
- [SDK](https://www.npmjs.com/package/quotegarden)
- [Postman Collection](collections/quote-garden.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quote-garden.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://pprathameshmore.github.io/QuoteGarden/)
- [Portal](https://pprathameshmore.github.io/QuoteGarden/)
- [GitHub Repository](https://github.com/pprathameshmore/QuoteGarden)
- [GitHub Organization](https://github.com/pprathameshmore)
- [Source Code](https://github.com/pprathameshmore/QuoteGarden)
- [License](https://opensource.org/licenses/MIT)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/rules/quote-garden-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/quote-garden/refs/heads/main/vocabulary/quote-garden-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
