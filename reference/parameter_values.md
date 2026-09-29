# Returns examples of data field values along with a description of the data field

Returns examples of data field values along with a description of the
data field

## Usage

``` r
parameter_values(data_set = NULL, data_field = NULL, message = TRUE)
```

## Arguments

- data_set:

  a character vector specifying the data set

- data_field:

  a character vector specifying the data field

- message:

  a logical value that is TRUE by default. When TRUE, the function will
  return information as a console message. When set to FALSE, the
  function will return the same information as a tibble.

## Value

returns a consoles message providing a description of the data field and
several example values of the data field within the data set.

## Examples

``` r
if (FALSE) { # \dontrun{
parameter_values(
  data_set = "fimaNfipClaims",
  data_field = "totalBuildingInsuranceCoverage"
)
} # }
```
