---
title:  "A Remote Sensing Method to Monitor Water, Aquatic Vegetation, and Invasive Water Hyacinth at National Extents"
authors:
  - Geethen Singh
  - Chevonne Reynolds
  - Marcus Byrne
  - Benjamin Rosman

author_notes: []

publication: "*Remote Sensing*"

date: 2020-12-01T00:00:00Z
publishDate: 2022-10-05T00:00:00Z

# conf = 1, journal = 2, preprint = 3, report = 4, book = 5, book chapter = 6, thesis = 7, patent = 9
# workshop = 9, symposium = 10, extended abstract =11
publication_types:
- "2"

abstract: "Diverse freshwater biological communities are threatened by invasive aquatic alien plant (IAAP) invasions and
  consequently, cost countries millions to manage. The effective management of these IAAP invasions necessitates their 
  frequent and reliable monitoring across a broad extent and over a long-term. Here, we introduce and apply a monitoring approach 
  that meet these criteria and is based on a three-stage hierarchical classification to firstly detect water, then aquatic 
  vegetation and finally water hyacinth (Pontederia crassipes, previously Eichhornia crassipes), the most damaging IAAP 
  species within many regions of the world. Our approach circumvents many challenges that restricted previous satellite-based 
  water hyacinth monitoring attempts to smaller study areas. The method is executable on Google Earth Engine (GEE) extemporaneously
  and utilizes free, medium resolution (10–30 m) multispectral Earth Observation (EO) data from either Landsat-8 or Sentinel-2.
  The automated workflow employs a novel simple thresholding approach to obtain reliable boundaries for open-water, which 
  are then used to limit the area for aquatic vegetation detection. Subsequently, a random forest modelling approach is used
  to discriminate water hyacinth from other detected aquatic vegetation using the eight most important variables. 
  This study represents the first national scale EO-derived water hyacinth distribution map. Based on our model, it is estimated
  that this pervasive IAAP covered 417.74 km2 across South Africa in 2013. Additionally, we show encouraging results
  for utilizing the automatically derived aquatic vegetation masks to fit and evaluate a convolutional neural network-based 
  semantic segmentation model, removing the need for detection of surface water extents that may not always be available at the 
  required spatio-temporal resolution or accuracy. The water hyacinth species discrimination has a 0.80, or greater, overall 
  accuracy (0.93), F1-score (0.87) and Matthews correlation coefficient (0.80) based on 98 widely distributed field sites across 
  South Africa. The results suggest that the introduced workflow is suitable for monitoring changes in the extent of open water, 
  aquatic vegetation, and water hyacinth for individual waterbodies or across national extents."

featured: true
tags:
  - Remote Sensing
  - Machine Learning


image:
focal_point: ''
preview_only: false

slides: null
url_code: "https://code.earthengine.google.com/?accept_repo=users/geethensingh/Singh_etal_2020"

---
