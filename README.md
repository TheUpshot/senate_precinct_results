Senate Precinct Results
=======================

This repository contains a snapshot of precinct-level results from 2014 general election in the following states with Senate races:

* Alaska
* Arkansas
* Georgia
* Kentucky
* Louisiana
* Minnesota
* North Carolina
* Virginia

The data was used for [The Upshot's Live Senate Model](http://elections.nytimes.com/2014/senate-model) on election night.

These results were scraped from official state websites by The New York Times on November 5, 2014. However, as snapshots, these files may not match data currently published on those sites. Use at your own risk. This is government data, so there is no claim of copyright or license for its use.

Each state-specific JSON file contains the name of the precinct, the county, candidate totals and a status representing completeness of the data for that precinct. Example:

```
    {
        "Mitch McCONNELL": 343,
        "Alison Lundergan GRIMES": 147,
        "David M. PATTERSON": 13,
        "precinct_name": "AB",
        "county_name": "Adair",
        "status": "INCOMPLETE"
    }
```

