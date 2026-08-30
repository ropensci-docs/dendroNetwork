# Create dendrochronologial networks

Function to create dendrochronological networks based on the similarity.
The input for this function is a similarity table created with the
sim_table() function. The thresholds are set to the defaults (Visser
2021).

## Usage

``` r
dendro_network(
  sim_table,
  r_threshold = 0.5,
  sgc_threshold = 0.7,
  p_threshold = 1e-04,
  corr_type = "r_hol"
)
```

## Arguments

- sim_table:

  a table of similarities created by the sim_table() function

- r_threshold:

  all correlations equal or above this value are taken into account for
  the creation of edges. If you want all positive correlations included
  set this to 0.

- sgc_threshold:

  all sgc-values equal or above this value are taken into account for
  the creation of edges.

- p_threshold:

  all probabilities of exceedence equal or below this value are taken
  into account for the creation of edges.

- corr_type:

  choose between the correlation based on wuchswerte (r_hol:
  Hollstein 1980) or the correlation without extra transformation (r)

## Value

A simplified network of tree-ring material with the edges defined by the
similarity.

## References

Visser, RM. 2021a Dendrochronological Provenance Patterns. Network
Analysis of Tree-Ring Material Reveals Spatial and Economic Relations of
Roman Timber in the Continental North-Western Provinces. Journal of
Computer Applications in Archaeology 4(1): 230–253. DOI:
https://doi.org/10.5334/jcaa.79.

## Examples

``` r
data(hol_rom)
sim_table_hol <- sim_table(hol_rom)
g_hol <- dendro_network(sim_table_hol)
plot(g_hol)

g_hol_r_low <- dendro_network(sim_table_hol, r_threshold = 0.3,
                                sgc_threshold = 0.6, corr_type = "r")
plot(g_hol_r_low)

```
