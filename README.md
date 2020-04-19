# import_csv_grdf_to_influxdb

Use the [GRDF gazpar energy export](https://monespace.grdf.fr/monespace/particulier/consommation/consommations) to import data into influxdb.  
Useful for initializing the database on influxdb, then a tool like [beufanet/gazpar](https://github.com/beufanet/gazpar) can do the rest of the job daily.