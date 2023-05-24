# Snowflake Assignment

The worksheet.sql file contains the following SQL statements:

- **CREATE ROLE:** Creates three roles, Admin, Developer, and PII.
- **GRANT ROLE:** Grants roles to other roles.
- **CREATE WAREHOUSE:** Creates a new warehouse assignment_wh.
- **GRANT:** Grants privileges to roles.
- **USE:** Switches the context to a specific database, schema, or warehouse.
- **CREATE DATABASE:** Creates a new database assignment_db.
- **CREATE SCHEMA:** Creates a new schema my_schema under assignment_db.
- **CREATE TABLE:** Creates a new table employees under my_schema.
- **PUT:** Uploads data from a local file to a Snowflake stage.
- **LIST:** Lists the contents of a Snowflake stage.
- **COPY INTO:** Copies data from a Snowflake stage to a Snowflake table.
- **SELECT:** Retrieves data from a Snowflake table.
- **CREATE STORAGE INTEGRATION:** Creates a new storage integration s3_int.
- **CREATE STAGE:** Creates a new stage external_stage using the s3_int integration.
- **CREATE TABLE:** Creates a new table employees_variant using the data in external_stage.
- **CREATE FILE FORMAT:** Creates a new file format parquet_ff.
- **CREATE STAGE:** Creates a new stage parquet_stage using the s3_int integration and the parquet_ff file format.
- **SELECT:** Retrieves data from a parquet file in the parquet_stage.
- **CREATE MASKING POLICY:** Creates a new masking policy pii_mask.
- **ALTER TABLE:** Modifies the email column of the employees table to use the pii_mask masking policy.
- **GRANT:** Grants privileges to roles.
