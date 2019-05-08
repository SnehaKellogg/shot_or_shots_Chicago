# shot_or_shots_Chicago
This project is an attempt to study the relation of flushots and crime in Chicago city with the demographics of the city divided by communities - as catgorized in the census by ACS.

The summary of whole process is in the pdf file here. https://github.com/SnehaKellogg/shot_or_shots_Chicago/blob/master/ETL%20Project%20Report.pdf 

The data was huge and so we could not upload it on the github.

The extraction sources and process of cleaning the data is coded in https://github.com/SnehaKellogg/shot_or_shots_Chicago/blob/master/ETL_Extract_Transform.ipynb
and https://github.com/SnehaKellogg/shot_or_shots_Chicago/blob/master/crimedata_cleaning.ipynb

The loading to mysql via sqlalchemy is here:
https://github.com/SnehaKellogg/shot_or_shots_Chicago/blob/master/sqlconnection.ipynb

Finally, the sql commands (they were much faster!) we used are available here:
https://github.com/SnehaKellogg/shot_or_shots_Chicago/blob/master/ETLtables.sql
