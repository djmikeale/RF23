# Optimize your '23 Roskilde Festival music experience  

![screencast](google_sheet_demo.gif)

## Goals

- Easily find new music to love
- Make sure you don't miss your most loved artists
- Make sure you miss the music you don't like 💩

<details>
<summary>

## Isn't this overkill?

</summary>

The festival apps and the website helps a bit, but I've been desiring the following functionality: 

- Rather than just ❤️ the artists I like, I want it more granular, and be able to add comments on *why* I (dis)liked an artist
- I'm going together with my GF and we'd like to easily see what's important for each other
- Find artists' mustic on Spotify without too many clicks
- See the relevant information at the right time (TODO feature to create .ical of most important events + notification of when favorite artists are going to play?)

</details>

## Get started
Make a copy of [this google sheet](https://docs.google.com/spreadsheets/d/1uu3_S_e2zR5O2cTbknIUh4bG1GymBtdwieFwZynTPRY/edit#gid=555358856), and clear values in column `E`, `F`, and `O`.

<details>
<summary>

## Under the hood

</summary>


1. `roskilde.ipynb` scrapes selected programme information from the roskilde website
2. scraped data is written to `output.csv`
3. new data is manually copied into google sheets, and some vlookup and cmd+c cmd+v action makes things work well enough for the purpose
4. enjoying and rating some exciting music! 

</details>
