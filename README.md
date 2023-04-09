# Optimize your '23 Roskilde Festival music experience  

<center>

Find new music to love, and plan your must-see concerts|
:-:
![screencast](img/google_sheet_demo.gif)

Add fave concerts to your calendar|See relevant event details
:-:|:-:
![Alt text](img/cal_event_overview.png)|![Alt text](img/cal_event_details.png)

</center>

<details>
<summary>

## Isn't there like.. an app for this?

</summary>

Probably! Also, the website helps a bit, but I've been desiring the following functionality: 

- Rather than just ❤️ the artists I like, I want it more granular, and be able to add comments on *why* I (dis)liked an artist
- I'm going together with my GF and we'd like to easily see what's important for each other
- Find artists' mustic on Spotify without too many clicks
- See the relevant information at the right time (TODO feature to create .ical of most important events + notification of when favorite artists are going to play?)

</details>

## Get started

1. Make a copy of [this google sheet](https://docs.google.com/spreadsheets/d/1uu3_S_e2zR5O2cTbknIUh4bG1GymBtdwieFwZynTPRY/edit#gid=555358856), and clear values in column `E`, `F`, and `O`.
2. Listen to all the amazing (and not-so-amazing 💩) music.
3. Edit the `SHEET_ID` parameter in `transform.ipynb` to source your spreadsheet, and run the code.
4. Load the calendar-file into your prefered calendar.

<details>
<summary>

## Under the hood

</summary>


1. `roskilde.ipynb` scrapes selected programme information from the roskilde website
2. scraped data is written to `output.csv`
3. `is_everything_synced.ipynb` compares roskilde-website, `output.csv`, and the google sheet, and makes it easy to add new artists to the google sheet with some crazy cmd+c cmd+v action

### installation

```shell
git clone https://github.com/djmikeale/RF23.git
cd RF23
python3 -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
source venv/bin/activate
```
</details>
