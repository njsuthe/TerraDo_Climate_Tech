# TerraDo Climate Tech Fellowship - Lab Work

This repository contains Jupyter notebook implementations of lab work originally conducted in Hex notebooks as part of the Terra.Do Climate Tech fellowship program. These `.ipynb` files serve as proof of coding practice and demonstrate various climate tech data analysis techniques.

## Overview

These notebooks were converted from their original Hex YAML format to standard Jupyter notebooks with matplotlib visualizations, making them accessible for use in any Jupyter environment. Each notebook focuses on different aspects of climate technology and renewable energy analysis.

## Notebook Contents

### 1. electricity_demand_generation.ipynb
**EIA API data analysis for electricity generation and demand**

- Fetches electricity generation and demand data from the U.S. Energy Information Administration (EIA) API
- Analyzes grid mix by fuel type (coal, natural gas, solar, hydro, nuclear, etc.)
- Compares local vs. imported electricity generation
- Includes interactive visualizations of electricity generation trends over time
- Covers balancing authority (BA) concepts and grid interconnection analysis

### 2. rooftop_solar_model.ipynb
**PV system modeling using pvlib and NREL weather data**

- Models residential rooftop solar (photovoltaic) systems using the pvlib Python library
- Fetches historical solar weather data from NREL's Physical Solar Model (PSM)
- Simulates electricity generation based on home characteristics, panel orientation, and weather conditions
- Includes System Advisor Model (SAM) integration for detailed PV panel and inverter modeling
- Provides weekly and detailed hourly generation analysis

### 3. home_energy_usage_model.ipynb
**HVAC energy consumption simulation**

- Implements a "baby energy model" for residential HVAC system energy usage
- Models home envelope characteristics (insulation, air tightness, window area)
- Simulates heating and cooling energy consumption based on weather data
- Analyzes energy balance components: conduction, air changes, solar gain, and HVAC operation
- Includes monthly energy balance analysis and seasonal temperature comparisons

### 4. iot_data_logging.ipynb
**IoT sensor data visualization and analysis**

- Fetches and analyzes sensor data from a fleet of IoT devices deployed in Las Vegas, NV
- Processes environmental measurements: CO2, temperature, humidity, particulate matter, and battery status
- Aggregates data hourly using median values for robust analysis
- Compares indoor vs. outdoor environmental conditions
- Includes comprehensive data visualization for all sensor types

## Technical Details

- **Original Format**: Hex notebooks (YAML format)
- **Converted Format**: Jupyter notebooks (.ipynb)
- **Visualization**: Matplotlib charts (replacing Hex's interactive charts)
- **Data Sources**: EIA API, NREL PSM, Supabase database
- **Libraries Used**: pandas, matplotlib, pvlib, requests, sqlalchemy

## Usage

Each notebook is self-contained and includes:
- Detailed explanations of concepts and terminology
- Code comments and educational content
- Data fetching and processing functions
- Visualization code with matplotlib
- Analysis and insights sections

## Requirements

To run these notebooks, you'll need:
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Required packages: pandas, matplotlib, numpy, pvlib, requests, sqlalchemy
- API keys for EIA, NREL, and Supabase (as specified in each notebook)

## Educational Context

These notebooks were created as part of the Terra.Do Climate Tech fellowship program, demonstrating practical applications of data science and programming in climate technology. They showcase:

- API integration for climate and energy data
- Time series analysis and visualization
- Energy system modeling
- IoT data processing and analysis
- Environmental data interpretation

## Repository Structure

```
TerraDo_Climate_Tech/
├── README.md
├── electricity_demand_generation.ipynb
├── rooftop_solar_model.ipynb
├── home_energy_usage_model.ipynb
└── iot_data_logging.ipynb
```

---

*This repository serves as a portfolio of climate tech data analysis work completed during the Terra.Do Climate Tech fellowship program.*
