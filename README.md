# Charging_vs_Petrol_Station

# Installation

```bash
conda env create -f environment.yml 
conda activate ORS_stations
pip install -r requirements.txt
```

# Local usage 

```bash
cd openrouteservice-7.1.0
cd docker 
mkdir conf elevation_cache graphs logs
cd logs
mkdir ors tomcat 
cd ..
docker compose up
```
