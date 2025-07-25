# Data Sources


## 1. CDPH Lab Results — Influenza Positive Tests
- **Link:** [Influenza Positive Laboratory Tests – Chicago](https://catalog.data.gov/dataset/influenza-positive-laboratory-tests-by-type-and-subtype#:~:text=This%20dataset%20includes%20aggregated%20weekly,Chicago%20residents)
- **Source:** Chicago Department of Public Health (via data.gov)
- **Used:** Weekly influenza-positive lab tests by type/subtype for Chicago residents from 2010–2019.
- **Purpose:** Target variable (ground truth).


## 2. CDC NIS — Vaccination Coverage
- **Link:** [Influenza Vaccination Coverage for All Ages 6 Months and Older](https://data.cdc.gov/Flu-Vaccinations/Influenza-Vaccination-Coverage-for-All-Ages-6-Mont/vh55-3he6/about_data)
- **Source:** CDC National Immunization Survey (NIS)
- **Used:** Monthly vaccination levels for persons older than 6 months.
- **Purpose:** Predictor variable, forward filled to fit weekly intervals.


## 3. Google Search Volume (Flu-related Terms)
- **Link:** [Google Trends](https://trends.google.com/)
- **Source:** Google
- **Used:** Weekly flu-related search interest in Chicago (Tamiflu, fever, Cough, flu symptoms, sore throat).
- **Purpose:** Predictive signal for public concern/flu spread.


## 4. Meteostat — Historical Weather Data
- **Link:** [Chicago O’Hare Weather Station (72530)](https://meteostat.net/en/station/72530?t=2010-10-01/2019-05-01)
- **Source:** Meteostat API — station KORD (Chicago O’Hare)
- **Used:** Daily temperature average and precipitation for 2010–2019.
- **Purpose:** Predictor variables. Created weekly summed precipitation and temperature gradient.


