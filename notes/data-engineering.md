# Data Engineering Notes

## Data Collection
I used the NBA API to collect real player game data.

## Data Cleaning
- Fixed missing values
- Standardized column names
- Removed duplicates

## Feature Engineering
This made the biggest difference in performance:
- Rolling averages (last 5–10 games)
- Home vs away games
- Rest days between games
- Player trends

## Key Takeaway
Raw data is messy — turning it into useful features is where the real work happens.
