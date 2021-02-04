# Download irods files

This is a PBS script to download large number of files from the Cyverse datastore using irods

## Quick guide

First edit the config.sh file and add:

- LIST= give the path to a text file containing the list of files to download on the datastore

- NB_SPLITS= the number of files each nodes will download in parallel. Irods is pretty slow, I recommend choosing a number between 5 and 20.

- OUT_DIR= output directory where the files will be downloaded

- MAIL_USER = your email

## Run the pipeline

to run the pipeline use the command

```
./run.sh
```

