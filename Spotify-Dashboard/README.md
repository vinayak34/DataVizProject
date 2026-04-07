# Spotify Advanced Analytics Dashboard
## Project Overview
This dashboard analyzes the "Most Streamed Spotify Songs of 2023" using advanced Power BI techniques. The project focuses not only on standard metric reporting but also on data enrichment via Python, custom UI design, and the use of declarative visualization (Deneb) to push the limits of Power BI's standard visual library.
## Technical Workflow
1. **Data Enrichment (ChatGPT & Python)**: Used ChatGPT to write Python code that utilizes the Spotify Web API to fetch album cover image URLs for every track in the Kaggle dataset [].
2. **UI/UX Design**: Created a professional Glassmorphism background using PowerPoint gradients and rounded shapes to provide a modern, sleek aesthetic [].
3.** Data Modelling**: Implemented a star schema with a custom calendar table generated via the Bravo external tool [].
4. **Advanced Visuals**: Integrated HTML and Deneb visuals to achieve designs (like rounded image corners and heatmaps) that are impossible with out-of-the-box Power BI visuals [].
## Key Dashboard Features
### 1. Dynamic KPIs & Analytics
- **Top Song Insights**: Displays the most streamed track name, artist, and release date [].
- **Performance vs. Average**: A DAX-powered metric that compares the top song’s streams against the yearly average with conditional up/down arrows [].
- **Song Characteristics**: Tracks quantifiers for acousticness, danceability, energy, and valence [].
### 2. Custom Visualization Stack
- **HTML Cover Art**: Used a custom HTML visual with CSS to display album covers with rounded corners and specific aspect ratios [].
- **Deneb Unit Chart**: A custom-coded circular progress gauge to visualize the average Energy % of songs, styled with Spotify-branded gradients [].
- **Deneb Heatmap**: A sophisticated monthly release frequency heatmap with integrated bar charts, providing a 2D view of when tracks were released [].
## Repository Structure
- **/Data**: Original Kaggle CSV and the Python-enriched version.
- **/Scripts**: Python code used for Spotify API data fetching.
- **/Dashboard**: The .pbix Power BI file.
- **/Assets**: PowerPoint background templates and custom icons.
