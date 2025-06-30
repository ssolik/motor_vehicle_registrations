# Motor Vehicle Registrations				
This project analyzed motor vehicle registrations data to uncover trends and insights to inform policy decisions and improve transportation planning. The analysis included data preprocessing, exploratory data analysis (EDA), and visualization of key metrics such as registration trends over time, economic drivers, and regional variations.

[Jupyter Notebook: nbviewer](https://nbviewer.org/github/ssolik/motor_vehicle_registrations/blob/main/motor_vehicle_registrations.ipynb?flush_cache=true)

![Jupyter Notebook: local](motor_vehicle_registrations.ipynb)

## Key Findings
- Motor vehicle registrations have shown a steady increase over the years, with notable spikes during economic recovery periods.
- U.S. motorization is mature; total growth now comes more from population than from additional vehicles per household.
- Regional variations in registration trends highlight the impact of local economic conditions and population growth.
- State-level divergence persists: sparse, rural states continue to build oversized fleets relative to population, while coastal metros stay flat.
- Correlation analysis indicates a weak negative correlation between per-capita income and vehicle registrations, suggesting that economic factors may play a counterintuitive role in vehicle ownership.

### National Growth
- Raw registrations rose every year from 2000 through 2023.
- Average annual growth ≈ 1.8 million vehicles; 2023 closed at a little over 286 million registrations.

### Registration Trends
- Per-capita registrations have been essentially flat since 2013, with a slight dip in 2020 likely due to the pandemic.
- 2023 registrations are at 860 vehicles per 1,000 residents, which is roughly equivalent to the 2010 level.
- Registrations peaked in 2013 at 880 vehicles per 1,000 residents.

### State Comparisons: Registrations per 1000 Residents
- Upper-Midwest states (Montana, Wyoming, North Dakota, South Dakota) top the chart, all exceeding 1,100 vehicles per 1,000 residents—i.e., more vehicles than people.
- The lowest rates cluster on the coasts and New York (≈ 540).
- Pennsylvania growth has been essentially flat and registration rate has been consistently roughly equivelent to the national average.
- Florida and California have flattened after significant declines between 2010 and 2013.

## Project Technical Details
### Tech Stack & Methodology

- **Python:**
  - Exploratory Data Analysis (EDA)
  - Data Visualization
  - Statistical Analysis

- **Pandas:**
  - Data Manipulation
  - Data Cleaning
  - Data Aggregation

- **Matplotlib & Seaborn:**
  - Data Visualization
  - Graphical Representation of Trends

- **Jupyter Notebook:**
  - Interactive Data Analysis
  - Documentation of Analysis Steps

### Dataset
- The project utilized the following CSV files:
  - Annual Motor Vehicle Registration Data (Motor_Vehicle_Registrations_2000-2023_MV-1.csv)
  - Annual State Resident Population Data (historical_state_population_by_year.csv)
  - Annual Per-Capita Personal Income by State (SASUMMARY__ALL_AREAS_1998_2024.csv)