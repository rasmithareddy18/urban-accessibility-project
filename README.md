
# Urban Inequality Map of Hyderabad

This project visualizes urban inequality across Hyderabad using geospatial data from the GHMC (Greater Hyderabad Municipal Corporation) and ward-level census indicators.

## 📂 Project Structure

```
hyderabad_urban_inequality/
├── data/
│   ├── ghmc-wards.kml
│   └── hyd_census_ward_data.csv
├── Urban Inequality Map of Hyderabad.ipynb
└── README.md
```

## 🔍 What It Does

- Loads GHMC ward boundaries (from KML)
- Loads ward-level census data (e.g., Scheduled Caste %, literacy rate)
- Merges spatial + tabular data
- Visualizes inequality indicators using choropleth maps

## 📊 Data Sources

- GHMC Wards: [Datameet GHMC KML Data](https://github.com/datameet/Municipal_Spatial_Data/tree/master/Hyderabad)
- Census Data: Custom dataset (ward-level summary from Census 2011)

## 📈 Key Insights

- Geographic variation in Scheduled Caste population
- Platform for future analysis of literacy, slums, healthcare access

## ✅ Next Steps

- Add OpenStreetMap POI data (e.g., hospitals, schools)
- Conduct spatial accessibility analysis
- Improve ward-Census matching

## 🛠️ Tools Used

- Python (Pandas, GeoPandas, Matplotlib)
- Jupyter Notebook
- OpenStreetMap (upcoming)
