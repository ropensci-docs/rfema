# Get data fields and descriptions for a given FEMA data set

Get data fields and descriptions for a given FEMA data set

## Usage

``` r
fema_data_fields(data_set)
```

## Arguments

- data_set:

  a character string indicating the data set of interest

## Value

Returns a tibble consisting of the data fields name, along with
information about each data field including the data type, a description
of the data field, and whether the data field is "searchable" (i.e. can
it be used to filter the returned data in an API query)

## Examples

``` r
if (FALSE) { # \dontrun{
fema_data_fields("FimaNfipClaims")
} # }
if (FALSE) { # \dontrun{
fema_data_fields("FimaNfipPolicies")
} # }
```
