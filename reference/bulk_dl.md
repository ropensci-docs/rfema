# Bulk download full open FEMA data sets as .csv files

Deprecated function for downloading full open FEMA data sets as .csv
files.

## Usage

``` r
bulk_dl(data_set, output_dir = NULL, file_name = NULL, size_warning = TRUE)
```

## Arguments

- data_set:

  A character string indicating the name of the data set to download

- output_dir:

  An optional character string indicating the directory (defaults to
  working directory)

- file_name:

  An optional character string indicating the file name (defaults to
  data set name with time stamp)

- size_warning:

  A logical indicating whether to issue a warning before proceeding with
  downloading a large file (default is TRUE)

## Value

Returns a downloaded csv file of the data set to the specified output
directory.

## Examples

``` r
if (FALSE) { # \dontrun{
bulk_dl("femaregions") # download the file
} # }
if (FALSE) { # \dontrun{
file.remove("FemaRegions.csv") # clean up directory after file downloads
} # }
```
