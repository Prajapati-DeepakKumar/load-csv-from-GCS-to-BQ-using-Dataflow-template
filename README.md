# **Load csv files from GCS bucket to BQ tables using existing Dataflow template**

While creating a dataflow with template *CSV files on Cloud Storage CSV to BigQuery*,
we need to specify the Cloud Storage path to the JSON file that defines your BigQuery schema.

Use the file 'bq_schema.json' to define the structure of your table and load it into the appropriate storage bucket.
