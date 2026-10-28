# Global Olympic Sports Performance Analysis

A Tableau project that explores Olympic athlete-event data using charts, a dashboard and a story. A small Flask website is included for web integration.

## Objective
To understand medal distribution, participation by country (NOC code) and participation by sport using data visualisation.

## Dataset
- File: athlete_events.csv (Kaggle: 120 Years of Olympic History)
- 271,116 rows and 15 fields
- Each row is one athlete in one event
- Medal values: Gold, Silver, Bronze and NA (NA means no medal)

## Visualizations
| Chart | What it shows | Result |
|---|---|---|
| Medal Analysis | Gold, Silver and Bronze counts (NA removed) | Gold 13,372, Bronze 13,295, Silver 13,116 |
| Olympic Participation by Country | Top 10 NOC codes | USA 18,853, FRA 12,758, GBR 12,256 |
| Sports Participation | Top 10 sports | Athletics 38,624, Gymnastics 26,707, Swimming 23,195 |

## Dashboard and Story
- The three charts are combined into one dashboard.
- The dashboard is shown as a Tableau story with a caption.

## Web Integration (Flask)
- app.py runs a small Flask website.
- templates/index.html is the webpage with the project description.
- Run it with: python app.py
- Open it at: http://127.0.0.1:5000
- The site runs locally on my computer.

## Tools Used
Tableau, Tableau Public, Python (Flask), VS Code, GitHub

## Repository Files
- olympic_tableau.twbx : Tableau packaged workbook
- dashboard_screenshot.png : dashboard screenshot
- story_screenshot.png : story screenshot
- app.py : Flask application
- templates/index.html : website page
- Project Documentation : project report
- Web integration output.pdf : Flask website running locally

## Notes
- Counts show participation records, not unique athletes.
- NOC is a country code (like USA, GBR), not a country name.
- Only the top 10 countries and sports are shown to keep the charts readable.

## Future Improvements
- Show country names instead of NOC codes
- Add Year and Season filters
- Add medals per country
