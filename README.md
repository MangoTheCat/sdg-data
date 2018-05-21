# SDG Data Repository

[![Build Status](https://travis-ci.org/mangothecat/sdg-data.svg?branch=develop)](https://travis-ci.org/mangothecat/sdg-data)

This repository holds the UK data for SDGs. The data is served

Routes:

```
data/<format>/<id>.<ext>

data/csv/1-2-1.csv
data/json/1-2-1.json

data/<format>/all.<ext>

meta/json/<id>.json
meta/json/all.json

headline/<format>/<id>.<ext>

headline/json/all.json
```


Scripts:

`build_data.py`: Builds main data, headline, and edges output in csv, and json.

`build_meta.py`: Builds the output metadata in json

