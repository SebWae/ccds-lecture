# ccds-lecture documentation!

## Description

An example for using CCDS in a DS project

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `gsutil rsync` to recursively sync files in `data/` up to `gs://ccds-swae/data/`.
* `make sync_data_down` will use `gsutil rsync` to recursively sync files in `gs://ccds-swae/data/` to `data/`.

