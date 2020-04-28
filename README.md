# lqs
Text-based sql client

## Idea
The main inspiration was `tig` - super druper console app for git. I'd like to have something similar for sql.

## Vision

* connect to db by arguments || save connection and load on 1st screen by choice || load connection by argument
* db drivers: support drivers for db type. Starting from mysql, in future sqlite, postgresql, redis, csv*
* browser: table list with regexp filter and main screen of content, search as WHERE, LIMIT
* inline editor: edit value, delete/insert row, push to db with one call
* query editor: execute script, result preview
* use "tabs", fzf search for quick jump/navigation
* color themes
* ViM keys

`* - csv could be as table. Possibility to load directory of csv`
