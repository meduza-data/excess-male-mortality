# excess-male-mortality
Here is a public subset of all the data we used in our analysis on excess male mortality in Russia.
​
We are not publishing here raw and some additional data, to obtain it please write at requests@meduza.io
​
Nevertheless, you can still reproduce excess cases calculation based on aggregated cases data. 
Due to maximum file size limitations on GitHub, aggregated data are available to download using the following link:   
[https://meduza.io/image/misc/excess-male-mortality/parsed_table_full.parquet](https://meduza.io/image/misc/excess-male-mortality/parsed_table_full.parquet)
​
Please consult `meduza-excess-male-mortality-Russia.ipynb` for the particulars of our method. 
In order to use this file you need to copy the file `parsed_table_full.parquet` into `data/out/`:
​
```bash
wget https://meduza.io/image/misc/excess-male-mortality/parsed_table_full.parquet -O data/out/parsed_table_full.parquet
```
