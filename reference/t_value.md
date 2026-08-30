# Students' t value

Function to determine the Students' t-value using the correlation and
the number of compare values (tree-rings)

## Usage

``` r
t_value(r, n)
```

## Arguments

- r:

  correlation value.

- n:

  number of overlapping tree-rings/compared values.

## Value

Students' t value as a numeric.

## Examples

``` r
t_value(0.5, 100)
#> [1] 5.744563
```
