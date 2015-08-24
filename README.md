# Example Binder using remote storage

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/binder-project/example-remote-storage)

A Binder-compatible repo that shows accessing data from remote sources.

The notebooks use `boto` and `requests` to load both images and tables from S3 and Google Storage. The image loading makes use of `PIL` and the table loading makes use of `pandas`. In both cases the data have been made publicly available. 
