This repository contains the data used/related to the [MitreAttackGraphQL project](https://github.com/rivantsov/MitreAttackGraphQL) 

SourceJsonZips folder contains a zip file with 3 Json files with attack data, downloaded from repo: 

https://github.com/mitre-attack/attack-stix-data

use this file if you want to import raw data into database, using the import command line app in the MitreAttackGraphQL project. 


The SqlDbBackup folder contains a backup of the SQL database with already imported Mitre data. Use this file if you want to skip the import process. Just unzip the file and restore the database from the .bak file using the SQL Management Studio.  
