# Google maps scanner
Since google is very good at proximity and relevance, there isn't a way to scan a given area for places.
This python 'app' generates a grid area given a start and finish Lat and Long range, then searches each given point.
The aim of this is to receive lots of results. There will be duplicates which need popping out before adding to json.

## Requirements
- pipenv
- Google maps apis enables

## Running
- Copy credentials.example.py to credentials.py
- Run ```pipenv shell```
- Run ```python main.py```

After running main.py, maps are generated as html files to app/maps

# TODOs
- next page data
- pop duplicates
