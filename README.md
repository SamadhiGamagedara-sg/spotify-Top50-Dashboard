#Spotify Global Top 50 Dashboard

Chart Trends & Song Performance (May 2023 – Nov 2024)

An interactive Power BI dashboard exploring 18 months of daily Spotify Global Top 50 chart data — tracking which songs and artists dominated, how popularity shifted over time, and what separates a song that charts often from one that charts high.

Show Image

What's inside

The dashboard has three pages, each built around a different question:

🏠 Home

A landing page introducing the dataset and navigation.

📊 Overview

The big picture — KPI cards, top artists and songs by days charted, album type split, explicit content share, and an average-popularity trend across the full 18-month window.

🎵 Songs

A song-level deep dive. Pick any song from the slicer and the whole page updates: cover art, release year, best rank, average popularity, and a day-by-day position trend showing exactly how that song moved up and down the chart over time.

Show Image

Key insights


794 unique songs and 343 artists cycled through the Global Top 50 across the period.
"I Wanna Be Yours" (Arctic Monkeys) is the longest-charting song at 548 days — but never cracked the top 10, peaking at #11.
"Cruel Summer" (Taylor Swift) is the rare song that charts both often (517 days) and high (peaked at #2, averaging position ~16) — the strongest combination in the dataset.
Taylor Swift dominates total days charted by a wide margin, well ahead of every other artist.
40.2% of all chart entries were explicit tracks.
Albums outnumber singles roughly 62% to 38% among charting tracks.


Data

Source: daily Spotify Global Top 50 snapshots, spotify-top-50-world.csv — one row per song per day it appeared in the chart, covering 2023-05-18 to 2024-11-27 (27,800 rows).

Fields include song, artist, chart position, popularity score, duration, album type, explicit flag, release date, and album cover art URL.

Tools


Power BI Desktop — data modeling, DAX measures, and all visuals
DAX — 20+ custom measures covering totals, averages, rankings, and explicit content share
Figma — custom UI mockups and layout design used as visual references for the dashboard
Canva — supporting graphics and the intro/title design
