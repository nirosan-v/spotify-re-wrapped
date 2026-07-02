# Spotify Listening Analysis

Built a Power BI dashboard using my Spotify listening history to analyse over 8 years of music habits beyond Spotify Wrapped.

The dashboard explores listening behaviour through interactive visualisations, uncovering trends across artists, tracks and years. It also shows data cleaning, transformation and visualisation techniques in Power Query and Power BI.

## Tech Stack

- Power BI
- Power Query
- DAX
- Excel
- JSON

## Workflow

```text
Spotify Extended Streaming History
                ↓
Import JSON Files into Power BI
                ↓
Clean, Merge & Transform Data (Power Query)
                ↓
Create DAX Measures
                ↓
Build Interactive Dashboard
                ↓
Generate Insights
```

## Dashboard

![Spotify Dashboard](/spotify-re-wrapped-dashboard.png)

## Key Insights

- Analysed over 8 years of Spotify listening history.
- Compared listening hours against play count to better represent listening habits.
- Identified trends across years, weekdays and hours of the day.
- Built an interactive dashboard to explore artists, tracks and listening behaviour.

## Repository Contents

- `Spotify Listening Analysis.pbix` — Complete Power BI report including the data model, Power Query transformations and DAX measures.
- `images/` — Dashboard screenshots used in this project.

> **Note:** The original dataset is not included as it contains personal listening history. You can request your own Spotify Extended Streaming History directly from Spotify.

## Future Improvements

- Spotify API integration for more data rich analysis.
- A weighted scoring model to track artist changes over time.
- Publish an interactive web version.
