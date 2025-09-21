<img width="720" height="540" alt="vlcsnap-2025-09-18-23h10m18s024" src="https://github.com/user-attachments/assets/8db3171a-d9f0-4f15-97a1-f6574006a7de" />
<img width="720" height="540" alt="vlcsnap-2025-09-18-23h09m47s124" src="https://github.com/user-attachments/assets/bd91e8d8-630b-4c81-818f-70eb30acf5d6" />
<img width="720" height="540" alt="vlcsnap-2025-09-18-23h09m41s225" src="https://github.com/user-attachments/assets/dc73b773-9e8d-4847-b599-8a11e7c7c994" />
<img width="720" height="480" alt="AirQuality_ScenePreview" src="https://github.com/user-attachments/assets/6add74bc-54a0-49ad-85f9-bbdcf0a856d5" />


Recreation of Weatherscan Local Made in Viz Artist 2.8


>[!WARNING]
> This Viz design **must** be run on an IntelliStar 2 Jr.

>You need Vizrt/i2 Experience to properly configure this for your location.


# Important

- Make sure to add a Long Lat Value to all 3 PrimaryLatitudeLongitudes in MachineProductConfig Since Regional Maps Can use a different Center Point if needed. Verify in RegionalDoppler_DftCFg and RegionalSat_DftCfg Etc to see which PrimaryLatitudeLongitude its looking for. Local Dopplar uses the the 1st PrimaryLatitudeLongitude

- Customize the LocalRadarCity Values in MachineProductCfg to fit correctly with the Local Radar map width. or Change the Map width in LocalRadar_DftCfg to your prefrence

- Enter 8 locations for NearbyLocations in MachineProductCfg

- Their might be a longitude offset in the GeoreferenceMap Containeer for Today,Tonight,Tomorrow and Now Map in the scene on viz. SO adjust That according to your location. The Offset was there for my location.

- XL BaseMap Scaling May have to be adjusted for your Area Especially if your not in the SE. i was able to perfect align the south East but for areas like The NE,MidWest ,NW and SW the county lines and border lines becomes slightly misaligned. This is due to XL map Not being CMR instead were using the raw Tiff itself. This could be easily adjusted on viz to align to your coordinates perfectly. Turn on the Border Lines that were previously used for the old maps as reference to align.

# Flavors

- Flavor: wxscanXL
- Duration: 9419

  
# Products

- Local Forecast
- Health

# To Do

- Import The rest of the worded XL Icons(Snow Varients)



