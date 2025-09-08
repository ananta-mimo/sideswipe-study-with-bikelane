
# Evaluating the Impact of Adding Bike Lanes on Sideswipe Crash Occurrences

This project analyzes the effect of adding bike lanes on sideswipe crash occurrences at intersections. The goal is to evaluate whether the presence of bike lanes reduces conflicts and improves safety for bicyclists, especially at signalized intersections or areas with high crash frequency.

## 🚦 Project Objectives

- Identify and extract intersections from OpenStreetMap for a study area (e.g., Tampa)
- Collect and preprocess crash data with a focus on sideswipe crashes
- Integrate aerial imagery and roadway design data where available
- Compare crash patterns before and after bike lane implementation
- Generate summary statistics, visualizations, and geospatial outputs



## 📁 Project Structure 
``````
sideswipe-study-with-bikelane/
│
├── data/ # Input data files (crashes, OSM, etc.)
├── notebooks/ # Jupyter notebooks for analysis
├── scripts/ # Python scripts for automation
├── output/ # Figures, charts, and results
├── venv/ # Virtual environment (excluded via .gitignore)
├── README.md # Project overview (this file)
├── requirements.txt # Python dependencies
└── .gitignore # Ignored files and folders

``````
### 1. Clone the Repository
```bash
git clone https://github.com/ananta-mimo/sideswipe-study-with-bikelane.git
cd sideswipe-study-with-bikelane

## 2. Setup the environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt

## Sample Tools & Libraries Used
osmnx: to extract intersection nodes and street networks

pandas, geopandas: for tabular and spatial data processing

matplotlib, seaborn: for data visualization

folium: for interactive maps

scikit-learn: for any modeling or statistical comparison

`````
### Author
Ananta Sinha

Transportation AI Researcher | PhD |
GitHub Profile: ananta-mimo "
