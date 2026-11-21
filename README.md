# NZ Post Codes with Latitude/Longitude

An Excel dataset of New Zealand post codes, one row per locality, with coordinates for mapping and geospatial joins
(for example in Power BI or other dashboards).

**File:** `newzealand_postcodes.xlsx` (sheet `Sheet1`, about 2,700 rows)

| Column | Example |
|---|---|
| Postcode | `0110` (text, keeps the leading zero) |
| Locality | `Abbey Caves` |
| Long | `174.327` |
| Lat | `-35.749` |
| Territory | `Whangarei` |
| Region | `Northland` |
| Island | `North Island` |

## Source and licensing

The data was taken from <https://www.matthewproctor.com/newzealand_postcodes> in 2025 for a Power BI dashboard.
It belongs to its original source: check that site's terms before reusing it. The MIT licence in this repository
covers only this repository's own text, not the underlying data.

Tip: when loading the file, keep Postcode as text so codes such as `0110` don't lose their leading zero.
