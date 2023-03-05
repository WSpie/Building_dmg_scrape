The objective is to scrape all the trageted cells with lat, lng and damage states from https://hasar.6subatdepremi.org/ 
# Steps
1. Install necessary libs:
```bash
pip install -r requirements.txt
```

2. Run the entire [Notebook](run.ipynb) 

The processed df will be saved as [.parquet file](Building_dmg_w_geo.parquet).

3. Load processed df by:
```python3
import pandas as pd
df = pd.read_parquet('Building_dmg_w_geo.parquet')
```
