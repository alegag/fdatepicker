* Tue Now 05 2019
- Changed the supported format to PHP format

* Fri Nov 01 2019 
- scope data-action to fdatapicker alone, to avoid conflict with other plugins
- Renamed datepicker to fdatepicker
- selectDate accepts a string now too (it will convert to Date internally if so)
- selectDate accepts a csv-string of dates too for ranges or multiple dates
- default language is en
- added option altFieldMultipleDatesSeparator
- added more languages
- Fixed some deprecated jquery calls (blur and focus)
- Increased CSS width a bit to accomodate the slider on firefox
- AMD support added
- Other fixes incorporated from other branches