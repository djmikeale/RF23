# Scraping and transforming the Roskilde Festival 2023 programme.

## Goals

- Easily find new music to love
- Make sure you don't miss your most loved artists
- Make sure you miss the music you don't like 💩

## Get started
Make a copy of [this google sheet](https://docs.google.com/spreadsheets/d/1uu3_S_e2zR5O2cTbknIUh4bG1GymBtdwieFwZynTPRY/edit#gid=555358856), and clear values in column `E`, `F`, and `O`.
## Under the hood

1. `roskilde.ipynb` scrapes selected programme information from the roskilde website
2. scraped data is written to `output.csv`
3. new data is manually copied into google sheets, and some vlookup and cmd+c cmd+v action makes things work well enough for the purpose
4. enjoying and rating some exciting music! 

![screencast](google_sheet_demo.gif)
