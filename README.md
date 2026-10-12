# Spotify Music Trends — Exploratory Data Analysis (EDA)

## Project Overview
This project explores Spotify track data to understand music popularity and identify patterns associated with track performance. Using Python, the analysis examines artist popularity, follower counts, track duration, explicit content, album types, and release trends.

## Objectives
- Analyze track and artist popularity distributions.
- Investigate relationships between artist popularity, followers, and track success.
- Compare popularity across explicit and non-explicit tracks.
- Explore track duration and album type patterns.
- Examine release trends over time.
- Study correlations between track features and popularity.

## Dataset Overview
- **Original records:** 8,582 tracks
- **Cleaned working dataset:** 5,221 tracks
- **Features:** 15
- **Key attributes:** Track popularity, artist popularity, artist followers, track duration, album type, explicit labeling, and release date.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings

### Artist Popularity
Artist popularity has the strongest observed correlation with track popularity (**r = 0.47**).

### Artist Followers
Artist follower count has a positive correlation with track popularity (**r = 0.23**), although a larger audience does not guarantee success.

### Explicit Content
Explicit tracks have a higher average popularity (**57.82**) than non-explicit tracks (**50.53**). This association does not prove causation.

### Track Duration
The average track duration is approximately **3.56 minutes**. Duration has a weak correlation with popularity (**r = 0.11**).

### Album Type
Albums have the highest average track popularity (**55.66**), followed by singles (**46.36**) and compilations (**40.51**).

### Album Size
Album track count has almost no correlation with track popularity (**r = -0.053**).

### Release Trends
Track releases increased substantially after 2010, with the dataset showing a peak in 2024–2025. Newer releases are not automatically more popular.

## Conclusion
The analysis suggests that artist popularity and audience reach are more closely associated with Spotify track popularity than track duration or album size. The project demonstrates practical skills in data cleaning, exploratory analysis, correlation analysis, and data visualization.

## Project Files
- `EDA Project.ipynb` — Jupyter Notebook containing the analysis and visualizations.
