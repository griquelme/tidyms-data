TidyMS Data
===========

This repository contains example data for the [tidyms
package](https://github.com/griquelme/tidyms). It doesn't try to be a data
repository, and only contains some example data sets to generate examples
or for testing purposes.


datasets format
---------------

Each dataset is in its own directory and the name is obtained from the directory
name. Three files are used to load the data:

1. sample.csv: Sample metadata information
2. features.csv: Feature metadata information
3. data.csv: data matrix.

These three csv files are used to build a DataContainer instance with the data.
Also a file called description.txt may be added to briefly describe the data.
