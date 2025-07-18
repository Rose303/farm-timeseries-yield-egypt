# Farm Time Series Dataset for Crop Yield Modeling (Egypt)

This repository contains a farm-level time series dataset collected from Egyptian agricultural regions. The data captures climatic and vegetation indices across multiple farms and is designed to support machine learning and deep learning research in precision agriculture and yield forecasting.

> 📌 This dataset was created using ground-truth data generously provided by **Lemon Tree Labs**. Their contribution enabled the farm-level alignment of satellite and weather observations, making this time series dataset possible.  
> 🌐 [https://lemontree-labs.com](www.lemontree-labs.com)  
> ✉️ Contact: info@lemontree-labs.com

---

## 📦 Dataset Summary

- **Scope**: Time series data from individual farms  
- **Region**: Egypt, across different villages  
- **Crop Year**: 2024  
- **Granularity**: Farm-level observations per day  
- **Purpose**: Designed for crop yield prediction modeling, especially for soybean fields  

---

## 📁 Data Columns

| Column | Description |
|--------|-------------|
| `date` | Observation date (daily granularity) |
| `farm_id` | Unique identifier for each farm |
| `stats.average_msavi` | Mean MSAVI (Modified Soil-Adjusted Vegetation Index) |
| `stats.average_ndmi` | Mean NDMI (Normalized Difference Moisture Index) |
| `stats.average_ndvi` | Mean NDVI (Normalized Difference Vegetation Index) |
| `stats.max_msavi` | Maximum MSAVI recorded for the day |
| `stats.max_ndmi` | Maximum NDMI value |
| `stats.max_ndvi` | Maximum NDVI value |
| `stats.min_msavi` | Minimum MSAVI value |
| `stats.min_ndmi` | Minimum NDMI value |
| `stats.min_ndvi` | Minimum NDVI value |
| `stats.q1_msavi` | First quartile of MSAVI distribution |
| `stats.q1_ndmi` | First quartile of NDMI |
| `stats.q1_ndvi` | First quartile of NDVI |
| `stats.std_msavi` | Standard deviation of MSAVI |
| `stats.std_ndmi` | Standard deviation of NDMI |
| `stats.std_ndvi` | Standard deviation of NDVI |
| `Max Deg.C` | Maximum daily temperature (°C) |
| `Min Deg.C` | Minimum daily temperature (°C) |
| `Wind Speed (m/s)` | Daily average wind speed |
| `Humidity (%)` | Average relative humidity (%) |
| `Precipitation (mm)` | Daily precipitation (mm) |
| `Evapotranspiration (mm)` | Estimated evapotranspiration (mm) |
| `Global radiation (W/m²)` | Solar radiation in watts per square meter |
| `Yield_2024` | Reported yield in kilograms per hectare for the 2024 season |

---

## 🔍 Usage

This dataset is ideal for:
- Time series models for yield prediction  
- In-season crop monitoring  
- Climate impact analysis  
- Feature importance & explainability studies 
 

---

## 📜 License

This dataset is released for academic and non-commercial research use only.  
Please cite or credit **Lemon Tree Labs** when using this dataset in research, as they provided the essential ground-truth farm data used to build this time series version.
