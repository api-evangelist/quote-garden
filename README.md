# Quote Garden (quote-garden)

Quote Garden is a free, open-source REST API that serves more than 75,000 famous quotes. Built by Prathamesh More in Node.js + Express + MongoDB, it exposes a small read-only HTTP surface for fetching random quotes, paginated quote listings filterable by author, genre, and full-text query, plus master lists of all authors and genres. No authentication, no cost, MIT-licensed.

**APIs.yml:** [apis.yml](apis.yml)

## Type

- **x-type:** opensource
- **x-tier:** 3 (opensource-thin)
- **x-source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Personality
- **License:** MIT
- **Language:** JavaScript (Node.js + Express + MongoDB)

## API

- **Quote Garden REST API** — `GET /api/v3/quotes/random`, `GET /api/v3/quotes`, `GET /api/v3/genres`, `GET /api/v3/authors`
  - Base URL: `https://quote-garden.onrender.com/api/v3`
  - Legacy: `https://quote-garden.herokuapp.com/api/v3`
  - [GitHub README](https://github.com/pprathameshmore/QuoteGarden#readme)

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/quote-garden-openapi.yml](openapi/quote-garden-openapi.yml) |
| JSON Schema | [json-schema/quote-garden-quote-schema.json](json-schema/quote-garden-quote-schema.json) |
| JSON Schema | [json-schema/quote-garden-response-envelope-schema.json](json-schema/quote-garden-response-envelope-schema.json) |
| JSON Structure | [json-structure/quote-garden-quote-structure.json](json-structure/quote-garden-quote-structure.json) |
| JSON Structure | [json-structure/quote-garden-response-envelope-structure.json](json-structure/quote-garden-response-envelope-structure.json) |
| JSON-LD | [json-ld/quote-garden-context.jsonld](json-ld/quote-garden-context.jsonld) |
| Example | [examples/quote-garden-get-random-quote-example.json](examples/quote-garden-get-random-quote-example.json) |
| Example | [examples/quote-garden-list-quotes-example.json](examples/quote-garden-list-quotes-example.json) |
| Example | [examples/quote-garden-list-genres-example.json](examples/quote-garden-list-genres-example.json) |
| Example | [examples/quote-garden-list-authors-example.json](examples/quote-garden-list-authors-example.json) |
| Example | [examples/quote-garden-quote-example.json](examples/quote-garden-quote-example.json) |
| Example | [examples/quote-garden-response-envelope-example.json](examples/quote-garden-response-envelope-example.json) |
| Spectral Rules | [rules/quote-garden-rules.yml](rules/quote-garden-rules.yml) |
| Naftiko Capability | [capabilities/quote-discovery.yaml](capabilities/quote-discovery.yaml) |
| Vocabulary | [vocabulary/quote-garden-vocabulary.yml](vocabulary/quote-garden-vocabulary.yml) |

## Tags

Quotes, Inspiration, Open Source, Free API, Node.js, MongoDB, Express, Personality, Public APIs

## Notes

- Read-only API. All four endpoints are `GET`; no auth required; CORS-enabled.
- Response envelope: `{ statusCode, message, pagination, totalQuotes, data }`.
- Pagination block returns nulls on non-paginated endpoints (`/genres`, `/authors`).
- An official npm wrapper exists at [QuoteGardenNPM](https://github.com/pprathameshmore/QuoteGardenNPM) (`quotegarden` package).
- Originally created to power the [Achieve Chrome Extension](https://github.com/pprathameshmore/Achieve-Chrome-Extension); now consumed by Chrome extensions, Android/iOS apps, Twitter bots, and educational projects.

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers

- **Kin Lane** — kin@apievangelist.com
