# Data Dictionary

## Dataset Overview
The EV sales dataset contains historical data about electric vehicle adoption and its environmental impact globally.

## Fields Description

### Time-based Identifiers
- **Year**: Calendar year of the data point
  - Type: Integer
  - Range: 2010-2023
  - Example: 2020

### Vehicle Numbers
- **EV Sales**
  - Description: Number of new electric vehicles sold in the given year
  - Unit: Vehicles
  - Type: Integer
  - Example: 3,000,000

- **EV Stock**
  - Description: Total number of electric vehicles in use
  - Unit: Vehicles
  - Type: Integer
  - Example: 10,000,000

### Market Share Metrics
- **EV Sales Share**
  - Description: Percentage of total vehicle sales that are EVs
  - Unit: Percentage (%)
  - Type: Float
  - Range: 0-100
  - Example: 4.6

- **EV Stock Share**
  - Description: Percentage of total vehicle fleet that are EVs
  - Unit: Percentage (%)
  - Type: Float
  - Range: 0-100
  - Example: 1.2

### Environmental Impact
- **Electricity Demand**
  - Description: Total electricity consumption by EV fleet
  - Unit: TWh
  - Type: Float
  - Example: 80.0

- **Oil Displacement Mbd**
  - Description: Amount of oil consumption avoided due to EVs
  - Unit: Million barrels per day
  - Type: Float
  - Example: 0.5

- **Oil Displacement, million lge**
  - Description: Oil displacement in million liters of gasoline equivalent
  - Unit: Million lge
  - Type: Float
  - Example: 29000.0

## Data Quality Notes
- No missing values in key metrics
- Consistent units across years
- Numerical precision: 1 decimal place for percentages and energy metrics
