This file summarizes the major and interesting changes for each release. For a
detailed list of changes, please see the git history.

2026.09.09
----------

* Parse intended usage and add an `Intended Usage` column to the CSV files
* reference RFC Errata 9028 in `application/tzif-leap`
* obsolete `application/vnd.edulith.edux+json`
* update `application/v3c` to RFC10034
* add `application/vnd.fiduswriter+zip`
* add `application/vnd.prml+yaml`
* scripts/generate_iana_csv.py: fix returning failure in
  `add_additional_information`

2026.08.21
----------

* Rename `unique` to `primary`. The CSV column is called
  `Primary File Extensions` now.

2026.08.19
----------

* Initial release
