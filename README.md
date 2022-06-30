# Hepatitis of unknown origin in children

## Contents

This repository contains data extracted from the [ECDC-WHO/Europe surveillance bulletin](https://www.ecdc.europa.eu/en/hepatitis/joint-weekly-hepatitis-unknown-origin-children-surveillance-bulletin) bulletins starting from the week of September 27, 2021. 

## Getting the data

**Direct download (CSV)**: https://raw.githubusercontent.com/fbranda/hepatitis/main/timeseries-country-cases.csv

**Python** (requires `pandas`):
```python
import pandas as pd
df = pd.read_csv("https://raw.githubusercontent.com/fbranda/hepatitis/main/timeseries-country-cases.csv")
```

**R** (requires `httr`):
```r
library(httr)
df <- read.csv(text=content(GET("https://raw.githubusercontent.com/fbranda/hepatitis/main/timeseries-country-cases.csv")))
```

## License and attribution

This repository and data exports are published under the CC BY 4.0 license.




