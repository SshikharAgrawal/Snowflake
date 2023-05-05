**Shubham's Review**

Roles are created using create role command. Created a hierarchy between them as per requirements.
From account admin role data warehouse is created.
Switched to admin role.
Given some privileges to admin role and database is created.
Schema is created as mentioned in question.
Employee data table is created according to the schema of csv file.
Integration with aws, file format, and external staging are created.
Variant is created. For loading data internal stage is created and data is loaded into variant table using intert into commands.
Internal stage is created. CSV file is loaded into created table from local by running put command in command prompt.
By using copy command data is loaded into internal and external tables.
Some query commands are runned on above table.
created a parquet file format using put command from command prompt data is loaded.
For getting infer_schema query caommand are runned on parquet stage.
Masking policies are created and applied on columns of tables.
Different privileges are given to pii and developer role.
Query coammnd are runned on tables from differnt roles.


**Kushagra's Review**

Roles are created using create role command. 1.1 . Created a hierarchy between them as per requirements.
From account admin role data warehouse is created.
Switched to admin role.
Given some privileges to admin role and database is created.
Schema is created as mentioned in question.
Employee data table is created according to the schema of csv file.
Variant table, file format are created. Using put command file is loaded into internal stage from local.
Data is loaded into table by using copy command
File format for external stage is created. AWS is integrated with snowflake then data is loaded into external stage from aws s3 bucket.
By using put command data is laoded into internal stage.
Data is inserted into external table and internal table.
File format is created for parquet file. By using put command data is loaded into stage. Infer schema is extracted using select query.
query commands are runned on parquet stage.
Masking policies are created and applied on tables.
Different privileges are given to pii and developer role.Queries are runned on tabled from different roles.
