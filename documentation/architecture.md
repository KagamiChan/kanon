# Project kanon::architecture

## Description
kanon is an application to display personal Valve Dota2 gaming history data. It retrieves data via REST API, stores them locally and displays through web pages. It is similar to dotabuff or dotamax but only concentrates on only one player.

## Backend
Language: Python
Framework: flask
ORM: peewee
Database: sqlite
REST client: requests

### Main functionalities
- Request data from REST API
- Parse data and store necessary information in database
- Update data regularly and when requested
- Generate web content

### data object
- Player: myself, friends and competitors
- Game
- Dota2 heroes
- Hero skills
- Dota2 stuffs

## Frontend
Framework: foundation
Data visualization: d3, TBD.
