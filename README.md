# Project Pipeline Dashboard

Interactive dashboard of ENFRA's Energy-as-a-Service development portfolio — upcoming pipeline and closed projects — with demand-response and demand-management product scope by grid region and utility.

## Features

- **Upcoming / Closed toggle** — switches the entire view (KPIs, charts, filters, table)
- **KPI tiles** — project counts, close dates, grid regions, utilities, product scope
- **Charts** — projects by ISO/RTO and product coverage (New Backup Gen DR, BESS DR, Existing Backup Gen DR, Facility DM)
- **Filterable table** — text search, ISO and product filter chips, click-to-sort columns
- **Light / dark theme** toggle

## Usage

Open `index.html` in any browser. The page is fully self-contained — no build step, no dependencies, no network calls.

## Data source

`Upcoming and Active Projects - Consolidated.xlsx` (Upcoming and Closed tabs). A ✓ in the source means the product is in scope; an `x` or blank means not in scope. To update the data, edit the `RAW_UPCOMING` and `RAW_CLOSED` arrays near the top of the `<script>` block in `index.html`.
