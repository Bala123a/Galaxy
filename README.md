This respository implements a cloud native preprocessing pipeline for sentinel 1 and sentinel 2 data, speckle filtering, texture extraction, cloud masking and NDVI derivation
Processing of Sentinel datasets
Overview of the project work flow 

1. The project implements an end to end preprocessing and feature extract pipeline using snetinel 1 SAR and 2 optical data accessed via microsoft planetry computer API
   
 Instalation of Libraries  
- pystac (Data discovery), 
- numpy (numerical operations),
- rioxarry (raster metadata), 
- rasterio(raster I/O), 
- scipy (numerical operations),
- scikit-image (texture extraction),
- matplotlib ( visualization).  

2. Data access via API - AOI, date & time, sentinel scene collection 1 & 2

4. Sentinel preprocessing  - Scene selection (VV/VH) - SPECKLE FILTERING

<img width="640" height="453" alt="SAR preprocessing" src="https://github.com/user-attachments/assets/318651f5-7db8-414e-bcc0-73768a707649" />

GLCM (SAR tecture extraction)

<img width="1389" height="491" alt="glcm sar" src="https://github.com/user-attachments/assets/35501bd4-6b42-4f13-b9fc-325d87da733e" />
<img width="1389" height="491" alt="SAR GLCM" src="https://github.com/user-attachments/assets/3f23d102-10ef-48d0-becc-89474b7ca07c" />


4. Sentinel 2 - Scene selection -  Cloud masking (SCL) - visualization

<img width="484" height="457" alt="Cloud masking after" src="https://github.com/user-attachments/assets/7fd83f6f-8df4-4e9c-a6bc-9b1744277f6c" />
<img width="484" height="457" alt="Cloud masking" src="https://github.com/user-attachments/assets/1be71501-0d4f-4e74-adc5-e09493a11e45" />




 5. NDVI
 
<img width="489" height="496" alt="download" src="https://github.com/user-attachments/assets/07dc1b71-24e5-42dc-b1c7-8bdb1a089969" />


All data can be reproducible




Citation 

Sentinel 1 and sentinel 2 from ESA
Accessed via Microsoft planetary computer 


