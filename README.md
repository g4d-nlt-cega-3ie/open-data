# Geo4Dev — Open Data

The community contribution hub for **[Geo4Dev](https://geo4dev.nltgis.ai)** — an open library of
geospatial datasets, publications, and training resources that connect satellite and
remote-sensing data to development economics, impact evaluation, and public policy.

🌍 **Website:** https://geo4dev.nltgis.ai
📚 **Browse the library:** https://geo4dev.nltgis.ai/library
🗺️ **Explore the map:** https://geo4dev.nltgis.ai/map

This repository is where the research community proposes new entries, improves existing
records, and discusses the platform. It is open by design: everything is public, reviewable,
and version-controlled.

---

## Who runs Geo4Dev

Geo4Dev is a collaboration of three organizations working at the intersection of geospatial
science and global development:

- **[New Light Technologies (NLT)](https://newlighttechnologies.com)** — a Washington, DC–based
  integrated consulting firm spanning geospatial and remote sensing, data science and AI,
  software engineering, cloud, and cybersecurity. NLT builds and maintains the platform.
- **[Center for Effective Global Action (CEGA)](https://cega.berkeley.edu)** — a research
  network at UC Berkeley generating rigorous evidence on global poverty and development,
  including its Data Science for Development portfolio.
- **[International Initiative for Impact Evaluation (3ie)](https://www.3ieimpact.org)** —
  a global organization advancing evidence-informed development and home of the Development
  Evidence Portal.

---

## Ways to contribute

### 1. Add a publication or dataset

Pick whichever path is easiest for you:

- **Link an existing resource.** Open a *submission* issue with the link and core details
  (title, authors, location, short description). A maintainer catalogs it with attribution.
- **Register & submit.** For new or unpublished material, go through a short submission and
  review so the entry is described consistently and is easy to discover.
- **Open a pull request.** Comfortable with Git? Add a record to the catalog data and open a PR.

### 2. Improve the platform

The website itself is open source. Bug fixes, interface refinements, and new functionality
(map, search, catalog views) are all welcome.

➡️ **Site repository:** https://github.com/g4d-nlt-cega-3ie/geo4dev-site
Fork it, make your change, and open a pull request.

### 3. Discuss & review

Use **[Discussions](../../discussions)** to propose ideas, ask questions, and help review
community submissions. Good proposals often start as a conversation.

---

## Catalog data format

Each catalog entry is a structured record with fields such as:

| Field | Description |
| --- | --- |
| `title` | Resource title |
| `description` | Short summary |
| `content_type` | Publication, Dataset, Training Material, etc. |
| `category` / `subcategory` | Topic taxonomy |
| `author` / `publishing_org` | Attribution |
| `country` / `region_city` | Geographic scope |
| `lat` / `lng` | Coordinates (optional; enables the map) |
| `tags` | Keywords |
| `stable_link` / `source_url` | Where the resource lives |
| `license` | Usage terms |

When adding an entry, fill in as much as you can. Coordinates are optional but let your
contribution appear on the [map](https://geo4dev.nltgis.ai/map).

---

## Submission review

1. You open an issue or pull request.
2. A maintainer reviews for completeness, attribution, and fit.
3. On merge, the entry is published to the live library — usually within one release cycle.

See **[release notes](https://geo4dev.nltgis.ai/releases)** for what has shipped, and turn on
**[email alerts](https://geo4dev.nltgis.ai/contact)** to follow new additions.

---

## Licensing & attribution

Datasets and publications remain under **their respective original licenses** — always check
and preserve the source license and attribution. By contributing a record you confirm you have
the right to share the information and link provided.

---

## Questions?

Open a thread in [Discussions](../../discussions) or reach the team via the
[Geo4Dev site](https://geo4dev.nltgis.ai/contact).

*Geo4Dev is powered and maintained by [New Light Technologies](https://newlighttechnologies.com).*
