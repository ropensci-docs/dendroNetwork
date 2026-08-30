# Clique Percolation Method (with node names)

Function to determine communities in a network using clique percolation
method (Palla et al., 2005). Communities are created based on cliques.
Cliques are subsets of a network that can be considered complete
(sub)networks. The size of the cliques to be used to community detection
is part of the input of the function.

## Usage

``` r
clique_community_names(g, k = 3)
```

## Arguments

- g:

  network object (igraph)

- k:

  clique size to be used. The default is set to smallest possible size
  (3)

## Value

a dataframe with node names and community name. The community is named
as CPM_Kk_number_of_community with k replaced by the value of k.

## References

Palla, G., Derényi, I., Farkas, I., & Vicsek, T. (2005). Uncovering the
overlapping community structure of complex networks in nature and
society. Nature, 435(7043), 814-818.

Code adapted from source:
https://github.com/angelosalatino/CliquePercolationMethod-R/blob/master/clique.community.R

## Author

Angelo Salatino

Ronald Visser

## Examples

``` r
hol_sim <- sim_table(hol_rom)
g_hol <- dendro_network(hol_sim)
clique_community_names(g_hol, k = 3)
#>          node com_name
#> 1   HOL_LKBBH CPM_K3_1
#> 2   HOL_MBRUH CPM_K3_1
#> 3   HOL_MBUFH CPM_K3_1
#> 4   HOL_MRBRH CPM_K3_1
#> 5   HOL_TRRBH CPM_K3_1
#> 6   HOL_TRRSH CPM_K3_1
#> 7 HOL_TRMB32H CPM_K3_2
#> 8   HOL_WEDEH CPM_K3_2
#> 9   HOL_WEDWH CPM_K3_2
```
