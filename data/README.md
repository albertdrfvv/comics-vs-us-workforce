# Data

The raw files are not stored in this repository. IPUMS data may not be redistributed, and the Fandom scrapes are large, so `data/*.csv` is git ignored.

To run the notebook locally, place these four files in this folder:

| File | Source | Size |
|---|---|---|
| `marvel_characters_raw.csv` | Marvel Database (Fandom wiki), Earth 616, API scrape of 29 Sep 2026 | 37,204 rows x 25 columns |
| `dc_characters_raw.csv` | DC Database (Fandom wiki), Earth Two, Earth One, New Earth and Prime Earth, API scrape of 29 Sep 2026 | 14,671 rows x 26 columns |
| `us_jobs_by_sex_ipums_1940_2023.csv` | IPUMS USA Abacus, tabulated by occupation (OCC1950) and sex | 5,772 rows x 12 columns |
| `FRED_LNS11300002_women_lfpr.csv` | FRED series [LNS11300002](https://fred.stlouisfed.org/series/LNS11300002) | 944 rows x 2 columns |

The team keeps copies in its shared Google Drive folder. Ask a teammate for access, or rebuild the files from the sources above.

Licenses: Fandom content is CC BY-SA 3.0, IPUMS USA is free for academic use under the IPUMS terms, and FRED/BLS data is public domain.
