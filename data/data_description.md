# Data Description

This document describes the final dataset (`eda_todo.csv`) used for exploratory data analysis and machine learning. 

| Variable | Type | Description |
| :--- | :--- | :--- |
| `doFeesApply` | Categorical (Boolean) | Indicates whether the activity requires an entrance or participation fee. Values are `true` or `false`. |
| `isReservationRequired` | Categorical (Boolean) | Indicates whether a reservation is needed in advance. Values are `true` or `false`. |
| `arePetsPermitted` | Categorical (Boolean) | Indicates whether pets are allowed on the activity. Values are `true` or `false`. |
| `tags` | Continuous (Discrete Count) | The number of descriptive tags associated with the activity (e.g., "Hiking", "Wildlife"). Unit: count (integer, min 0). |
| `topics` | Continuous (Discrete Count) | The number of thematic topics associated with the activity. Unit: count (integer, min 0). |
| `timeOfDay` | Multi-label Categorical | The recommended time of day for the activity. Format is a list of strings. Possible values: `'Day'`, `'Night'`, `'Dawn'`, `'Dusk'`. An empty list `[]` indicates unspecified. |
| `season` | Multi-label Categorical | The recommended seasons for the activity. Format is a list of strings. Possible values: `'Winter'`, `'Spring'`, `'Summer'`, `'Fall'`. An empty list `[]` indicates year-round or unspecified. |
| `states` | Multi-label Categorical | The geographic regions of the related national parks extracted from `relatedParks`. *Note: Though named 'states', this column contains US regions.* Possible values: `'Northeast'`, `'Midwest'`, `'South'`, `'West'`, `'Territories'`. |
| `park_categories` | Multi-label Categorical | The generalized types of national parks where the activity occurs (categorized from park designations). Possible values: `'National_Park'`, `'Historical_Site'`, `'National_Monument'`, `'Recreation_Area'`, `'Other_Protected_Area'`. |
