You will now build a Dataflow pipeline with a TextIO source and a BigQueryIO destination to ingest data into BigQuery. More specifically, you will:

Ingest the files from Cloud Storage.
Convert the lines read to dictionary objects.
Transform the data which contains the year to a format BigQuery understands as a date.
Output the rows to BigQuery.

Get the source code from here.

gsutil -m cp -R gs://spls/gsp290/dataflow-python-examples .
