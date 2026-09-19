# Data

The dataset is not included in this repository. Download it from Kaggle and save it in this folder:

1. Open the dataset page: [Metro Manila Flood Prediction (2016-2020, daily)](https://www.kaggle.com/datasets/denvermagtibay/metro-manila-flood-prediction-20162020-daily)
2. Download the CSV file (a free Kaggle account is required).
3. Save it as `data/flood_prediction.csv`.

Check the license on the Kaggle page before redistributing the file. CSV files in this folder are ignored by git.

## Columns

| Column | Description |
|---|---|
| `Date` | Day of the observation (2016 to 2020) |
| `Location` | Quezon City, Marikina, Manila or Pasig |
| `Rainfall_mm` | Daily rainfall in millimetres |
| `WaterLevel_m` | Water level in metres |
| `SoilMoisture_pct` | Soil moisture in percent |
| `Elevation_m` | Elevation in metres (fixed per city) |
| `FloodOccurrence` | Target: 1 if a flood occurred, 0 otherwise |

7,308 rows in total, no missing values, no duplicate rows. Flood days make up 1.8% of the records (132 of 7,308).
