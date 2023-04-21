# Steam game searching

Final project for Umich SI 507 course

## Requirements

The project is created with Python 3.10.4 with following required Python packages:

- requests
- flask
- beautifulsoup4
- sqlite3

## Run the code

run the python file main.py directly. Then there is a link http://127.0.0.1:5000/ to interact with the program.

## Data Processing and Data Structure

Steam game data is from steampowered website (json file)
The json file will be got after getting access to the data, cache is used in this project.
data structure mainly represented by html files.
index.html is the interface.
detail.html and extension_info.html in templates folder will use the data stored in sqlite3 database.
cache.json is used in constructing detail.html and extension_info.html.
