# 🌿 MODIS NDVI Animated GIF Generator using Google Earth Engine

This project uses **Google Earth Engine** to generate an animated GIF of **Normalized Difference Vegetation Index (NDVI)** using **MODIS MOD13Q1** satellite imagery.

>  Developed by [Suman Bhowmick](https://github.com/Suman1801)

---

##  Description

This script processes 16-day NDVI composites to visualize vegetation changes over time in a selected region of interest. The output is an animated GIF showing temporal NDVI dynamics.

---

##  Dataset Used

- **Product**: MODIS MOD13Q1 (NDVI)
- **Spatial Resolution**: 250 meters
- **Temporal Resolution**: 16-day composites
- **Bands Used**: NDVI

---

##  Script Features

- Imports MOD13Q1 collection
- Filters by date and region
- Masks clouds and invalid pixels
- Adds NDVI scaling
- Creates NDVI time-series as an animated GIF
- Optionally exports the GIF to Google Drive

---

##  Parameters You Can Modify

- `startDate` and `endDate`
- `region` (geometry)
- `NDVI palette`
- `GIF export size and FPS`

---

## ▶️ Run the Script

Click the link below to run this script directly in the Earth Engine Code Editor:

🔗 [Open in Google Earth Engine](https://code.earthengine.google.com/?scriptPath=users/sumanbhowmick768/V:31%20-%20MODIS%20NDVI%20Animated%20GIF)

