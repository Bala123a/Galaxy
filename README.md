This respository implements a cloud native preprocessing pipeline for sentinel 1 and sentinel 2 data, speckle filtering, texture extraction, cloud masking and NDVI derivation
Processing of Sentinel datasets
Overview of the project work flow 

1. he project implements an end to end preprocessing and feaqture extract pipeline using snetinel 1 SAR and 2optical data accessed via microsoft planetry computer API
   
- Instalation of Libraries  
- pystac (Data discovery), 
- numpy (numerical operations),
- rioxarry (raster metadata), 
- rasterio(raster I/O), 
- scipy (numerical operations),
- scikit-image (texture extraction),
- matplotlib ( visualization).  

2. Data access via API - AOI, data & time, sentinel collection 1 & 2
3. Sentinel preprocessing  - Scene selection (VV/VH) - SPECKLE FILTERING - GLCM (SAR tecture extraction)
4. Sentinel 2 - Scene selection -  Cloud masking (SCL) - Upscaling 10m to 20m - derive NDVI - visualization

All data can be reproducible

Citation 
Sentinel 1 and sentinel 2 from ESA
Accessed via Microsoft planetary computer 

