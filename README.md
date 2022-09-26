# uggp-api

GeoInfomation of UNESCO Global Geopark

## 🗄️ Meta data

Geopark network

- GeoLAC
  - Country_ISO3c-Geopark_Name
    - geopark
      - boundary.shp
      - boundary.json
    - geosite
      - geosite.shp
      - geosite.json
    - georoute
      - georoute.shp
      - georoute.json
- EGN
- APGN
- Other

### 📁Country_ISO3c-Geopark_Name

Country code ISO3c
Geopark name without acent only in alphabeta ingles [a-z]

#### geopark

Contains boundary of geopark

boundary shapefile/json table
link to 📓notion 

|     name   |       area     |
|------------|----------------|
|geopark_name|area_size_in_km2|


#### geosite

contains geosites of the geopark
detail table in notion

|   geopark  |    name    |     type    |          level       |
|------------|------------|-------------|----------------------|
|geopark_name|geosite_name|geosite_type*|national/international|

#### georoute

contains the georoute of geopark
more infomation at notion

|   geopark  |     name    |          geosite          |
|------------|-------------|---------------------------|
|geopark_name|georoute_name|geosite_name_along_georoute|