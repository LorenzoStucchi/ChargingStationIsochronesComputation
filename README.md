# Charging Stations Isochrones Computation

# Installation

```bash
conda env create -f environment.yml 
conda activate ORS_stations
pip install -r requirements.txt
wget https://gist.githubusercontent.com/perrygeo/5667173/raw/763e1e50208e8c853f46e57cd07bb07b424fed10/zonal_stats.py
```

# Local usage 

```bash
wget https://github.com/GIScience/openrouteservice/archive/refs/tags/v7.1.0.zip
unzip v7.1.0.zip

cd openrouteservice-7.1.0
cd docker 
mkdir conf elevation_cache graphs logs
cd logs
mkdir ors tomcat 
cd ..
docker compose up
```
