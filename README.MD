# HEPA Project partner agent locator

### Tutorial (Uncertified Device)

1. Download CSV report from Eric's dashboard
https://dashboards.corp.google.com/edit/_b65d615f_af0c_4539_87c0_aed74ee1d9bc

2. Prepare a csv file contain all projects owned by partner, here's example 
https://docs.google.com/spreadsheets/d/1wcY9cuDRozHZvvm0l5UCGF4EEitDOfIqRnmLgQ8EsPs/edit?usp=sharing

3. Download above 2 files to this project root directory, then run the command
```
python generateUncertifiedDeviceReport.py <uncertified device csv> <agent list of partners>
```

4. You will see an output file named 
`output_YYYY_MM_DD.csv`

5. import this csv to google spread sheet
