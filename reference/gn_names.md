# Community detection using the Girvan-Newman algorithm

Function to determine the communities in a network using the
Girvan-Newman algorithm. This function uses the
cluster_edge_betweenness() function from the iGraph package, but creates
a more user-friendly output that includes the names of the nodes.

## Usage

``` r
gn_names(g)
```

## Arguments

- g:

  input graph or network that is used for community detection

## Value

the names of the nodes in the various communities

## Details

The GN-algorithm uses the edge betweenness to determine communities.
Edge betweenness is the number of shortest paths between pairs of nodes
running over that edge. The higher the edge betweenness, the more
communities an edge connects. Therefore these are removed in this
algorithm to detect communities.

## References

Girvan, M and Newman, MEJ. 2002 Community structure in social and
biological networks. Proceedings of the National Academy of Sciences of
the United States of America 99(12): 7821–7826. DOI:
https://doi.org/10.1073/pnas.122653799.

Newman, MEJ and Girvan, M. 2004 Finding and evaluating community
structure in networks. Physical Review E 69(2): 026113. DOI:
https://doi.org/10.1103/PhysRevE.69.026113.

## Examples

``` r
hol_sim <- sim_table(hol_rom)
g_hol <- dendro_network(hol_sim)
gn_names(g_hol)
#>           node com_name
#> 1    HOL_AAHOH     GN_1
#> 2    HOL_KMBQH     GN_1
#> 3    HOL_GKZBH     GN_2
#> 4    HOL_KORHH     GN_2
#> 5    HOL_LKBBH     GN_2
#> 6    HOL_KBMBH     GN_3
#> 7    HOL_LKSBH     GN_3
#> 8    HOL_MBRUH     GN_3
#> 9    HOL_MBUFH     GN_3
#> 10   HOL_MRBRH     GN_3
#> 11   HOL_PALZH     GN_3
#> 12  HOL_TMB11H     GN_3
#> 13   HOL_TRRBH     GN_3
#> 14   HOL_TRRSH     GN_3
#> 15   HOL_KORBH     GN_4
#> 16  HOL_MB253H     GN_4
#> 17 HOL_TRMB32H     GN_4
#> 18   HOL_WEDEH     GN_4
#> 19   HOL_WEDWH     GN_4
```
