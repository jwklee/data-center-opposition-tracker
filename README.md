# Data Center Opposition Tracker

A record of organized opposition to data center installation in the
United States, from 2020 through 2026-05-31. Movements are filed at the local
(county or municipal), state, or national level in one schema.

Two pages:

- **[Tracker](https://github.com/jwklee/data-center-opposition-tracker/blob/main/tracker.html)** —
  an interactive map and filterable table. Every popup links to a primary news source.
- **[Profile](https://github.com/jwklee/data-center-opposition-tracker/blob/main/profile.html)** —
  three figures: how the count of new movements has grown year by year, and how
  opposition counties compare to the rest of the country on per-capita income and
  2024 presidential vote.

## Methods

Every entry has at least one working source URL, visible in the marker popup and in
the table's Sources column. Entries are compiled from news coverage and official
records, not scraped or auto-generated. Each claim is checked against the underlying
article before it enters the dataset.

The dataset uses a controlled vocabulary for each movement's geographic level
(`local`, `state`, `national`), status (`active`, `won`, `lost`,
`ongoing-legislation`, `unknown`), and the event types in its timeline
(`regulation_proposed`, `regulation_passed`, `regulation_failed`, `project_blocked`,
`project_delayed`, `project_approved`, `public_action`, `legal_action`,
`electoral_action`, `start`, `other`). The Tracker page defines each one inline.

## Data

CSV source data underlying the tracker is **available upon request**; contact
[to.jaewook.lee@gmail.com](mailto:to.jaewook.lee@gmail.com). Research collaborations
are welcome.

## Contribute a movement

If you know of a local, state, or national data center opposition movement that
isn't here, or a correction or additional source for one that is, please email
[to.jaewook.lee@gmail.com](mailto:to.jaewook.lee@gmail.com?subject=Data%20Center%20Opposition%20Tracker%20submission).

Useful details for a new entry: where it is (county and state), when the opposition
began, any key dates (hearings, votes, bills, protests), who is involved, and one
or more links to news articles or official records.

## How to cite

```bibtex
@misc{lee2026dctracker,
  author       = {Lee, Jaewook},
  title        = {Data Center Opposition Tracker: Organized Opposition to
                  Data Center Installation Across the United States},
  year         = {2026},
  version      = {1.0},
  howpublished = {\url{https://github.com/jwklee/data-center-opposition-tracker/}},
  note         = {Data through 2026-05-31.
                  Contact: to.jaewook.lee@gmail.com}
}
```

## License

Page content is CC-BY-4.0; please cite as above when reusing figures or text. CSV
data terms depend on the use; contact above.

## Repository structure

```
docs/
  index.html        landing page
  tracker.html      interactive map + table
  profile.html      summary figures
README.md           this file
LICENSE             CC-BY-4.0
```
