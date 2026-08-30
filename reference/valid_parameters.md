# Get all valid API parameters for a given FEMA data set

Get all valid API parameters for a given FEMA data set

## Usage

``` r
valid_parameters(data_set = NULL)
```

## Arguments

- data_set:

  A character string indicating the data set to return valid parameters
  for

## Value

Returns a tibble of parameter names that can be used to filter an API
call for a given open FEMA data set

## Examples

``` r
if (FALSE) { # \dontrun{
valid_parameters("fimaNfipPolicies")
} # }
```
