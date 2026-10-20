# Data Description

This document describes the final dataset (`eda_todo.csv`) used for exploratory data analysis and machine learning models. 

| Variable | Type | Description |
| :--- | :--- | :--- |
| `doFeesApply` | Categorical (Boolean) | Indicates whether the activity requires an entrance or participation fee. Values are `True` or `False`. |
| `isReservationRequired` | Categorical (Boolean) | Indicates whether a reservation is needed in advance. Values are `True` or `False`. |
| `arePetsPermitted` | Categorical (Boolean) | Indicates whether pets are allowed on the activity. Values are `True` or `False`. |
| `tags` | Continuous (Discrete Count) | The number of descriptive tags associated with the activity (e.g., "Hiking", "Wildlife"). Unit: count (integer, min 0). |
| `topics` | Continuous (Discrete Count) | The number of thematic topics associated with the activity. Unit: count (integer, min 0). |
| `timeOfDay` | Multi-label Categorical (List of Strings) | The recommended time of day for the activity (e.g., `['Day']`). Stored as a string-formatted list. Possible values: `'Day'`, `'Night'`, `'Dawn'`, `'Dusk'`. An empty list `[]` indicates unspecified. |
| `season` | Multi-label Categorical (List of Strings) | The recommended seasons for the activity (e.g., `['Spring']`). Stored as a string-formatted list. Possible values: `'Winter'`, `'Spring'`, `'Summer'`, `'Fall'`. An empty list `[]` indicates unspecified. |
| `regions` | Multi-label Categorical (List of Strings) | The geographic regions of the related national parks (e.g., `['Northeast']`). Mapped from park states based on the four U.S. Census Bureau geographic regions plus U.S. territories. Stored as a string-formatted list. Possible values: `'Northeast'`, `'Midwest'`, `'South'`, `'West'`, `'Territories'`. |
| `park_categories` | Multi-label Categorical (List of Strings) | The generalized types of national parks where the activity occurs, categorized from park designations (e.g., `['National_Park']`). Stored as a string-formatted list. Possible values: `'National_Park'`, `'Historical_Site'`, `'National_Monument'`, `'Recreation_Area'`, `'Other_Protected_Area'`. |
