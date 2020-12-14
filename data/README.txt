This data readme.txt file was generated on 20201214 by Annika Rockenberger

-------------------
GENERAL INFORMATION
-------------------

Title of Dataset: List of letters and other correspondence registered in [HANSKE](https://www.nb.no/hanske/), the manuscript catalogue at the National Library of Norway.

Author Information: Annika Rockenberger, University of Oslo Library, annika.rockenberger[at]ub.uio.no

Date of data collection: 20181025

Geographic location of data collection: Oslo, Norway

The data was extracted from the catalogue by the maintainer of the database HANSKE is built upon. The goal was to extract all items that are letters or correspondence (incl. telegrams, postcards, etc.) from the private archives at the National Library.



--------------------------
SHARING/ACCESS INFORMATION
--------------------------

Licenses/restrictions placed on the data, or limitations of reuse: Creative-Commons-License CC0


--------------------
DATA & FILE OVERVIEW
--------------------

File list (filenames, directory structure (for zipped files) and brief description of all data files):

- NorKorr_hanske_signatur_brev.tsv (20181025 as Google Spreadsheet, converted to .tsv on 20201214)
- NorKorr_HANSKE_collett.tsv (20181025 as Google Spreadsheet, converted to .tsv on 20201214)
  -  248 rows, 2 columns
  - contains 229 items catalogued as letters to/from Camilla Collett in the private archives at the National Library
- HANSKE_NorKorr_collett_network.tsv (20181026 as Google Spreadsheet, converted to .tsv on 20201214)
  - based on NorKorr_HANSKE_collett.tsv, extracted sender/receiver names from list of letters in archival holdings for network analysis.
  - 236 rows, 2 columns (header: column 1 "Source", column 2 "Target")
  - 235 name pairs
- NorKorr_HANSKE_collett_data.csv (20181026 as .csv)
  - based on NorKorr_HANSKE_collett.tsv, extracted sender/receiver names, date of letter, URN if digitized
  - 236 rows, 5 columns (header: column 1 "Number", column 2 "Source", column 2
  3 "Target", column 4 "data", column 5 "URN")
  - 235 data rows
  - date format YYYY.MM.DD where full date is given, YYYY.MM. where only month and year is known, YYYY where only year is known; time span YYYY.MMM.DD-YYYY.MM.DD.
- README.txt
