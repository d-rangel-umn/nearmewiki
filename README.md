# NearMeWiki

**Explore nearby places through maps, useful profiles, and browsable catalogs.**

NearMeWiki is a local discovery prototype that brings business information into a map-first interface. Search for a place or an offering, explore catalog sections, and open a profile with practical details and source links.

This repository presents the product and its architecture through actual captures of the running application. Featured screenshots showcase Andale Taqueria & Mercado with explicit owner permission. The core implementation and research pipeline are maintained privately.

![NearMeWiki map and local search](media/map-andale.png)

## Product tour

| Experience | What it helps people do |
| --- | --- |
| Map and search | Find places and offerings in a geographic context with live vector map tiles. |
| Business profiles | Read an overview, browse an extensive catalog, and access hours, directions, website, and phone actions. |
| Discover | Browse offerings across businesses through categorized catalog sections. |
| Source disclosure | Inspect verified source links and provenance associated with a profile. |
| Research pipeline | Transform official business websites into structured, searchable profiles with validation. |

Read the [feature tour](docs/feature-tour.md), explore the [architecture](docs/architecture.md), or inspect a [sample data format](examples/fictional-business.json).

## Desktop experience

![NearMeWiki profile overview](media/profile-desktop-overview.png)

## Responsive mobile experience

<p align="center">
  <img src="media/profile-mobile-overview.png" alt="Mobile profile overview" width="360" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="media/profile-mobile-catalog.png" alt="Mobile catalog with expanded offering" width="360" />
</p>

See the [capture notes](docs/capture-notes.md) for provenance, viewport dimensions, and coverage details.

## Engineering approach

- **Frontend:** Flutter web application delivering responsive map navigation, custom vector tile styling, and modal profile sheets.
- **Backend:** Python/FastAPI service serving high-performance geospatial search and structured catalog data from PostgreSQL/PostGIS.
- **AI Research Pipeline:** Converts official business websites into structured, searchable profiles with source citations, confidence scoring, and schema validation.
- **Content Governance:** Ephemeral text processing, strict separation of factual data from protected media, and explicit rights verification before publication.

## Status and scope

NearMeWiki is an active prototype. This presentation repository documents the architecture and UX flows; it does not offer a public API, hosted demo, or runnable multi-container stack.

The public material intentionally stops at product behavior and high-level architecture. Internal prompts, retrieval heuristics, evaluation benchmarks, and proprietary operational configs remain in private repositories.
