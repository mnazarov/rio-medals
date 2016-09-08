# rio-medals
A different look at medals from Rio 2016 Olympics: web-scraping and visualization exercise in R.

Published at https://mnazarov.github.io/rio-medals/.

--

Data (scraped from https://www.rio2016.com/) available separately in:
* `allMedals (.json/.rds)`: all medals (2082 rows)
  * `country`, `abbr`: country name and abbreviation
  * `medal`: medal type (gold/silver/bronze)
  * `sport`: sport
  * `athlete`: athlete name
  * `individual`: whether it is an individual medal
  * `medalid`: medal ID (within country), so that medals with the same ID are counted as one 'official' medal

* `allAthletes (.json/.rds)`: all athletes (11544 rows)
  * `country`, `abbr`: country name and abbreviation
  * `code`, `sport` sport code and name
  * `name`, `gender` athlete name and gender
