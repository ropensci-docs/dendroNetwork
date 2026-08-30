# Create networks in Cytoscape

Function to create a network in cytoscape (https://cytoscape.org/)
Cytoscape must be running before executing this function.

## Usage

``` r
cyto_create_graph(
  graph_input,
  network_name = substitute(graph_input),
  collection_name = "default",
  style_name = "default",
  CPM_table = NULL,
  GN_table = NULL
)
```

## Arguments

- graph_input:

  igraph network used to create network in Cytoscape

- network_name:

  name of the network in Cytoscape, defaults to the name of variable
  that is the network in R

- collection_name:

  name of the collection in Cytoscape (default = default)

- style_name:

  name of the style in Cytoscape (default = default)

- CPM_table:

  table with the name of the nodes in the first column and the
  CPM-communities in other columns. This is the result of
  find_all_cpm_com()

- GN_table:

  two column table with the name of the nodes in the first column and
  the Girvan-Newman-communities in other columns

## Value

a graph in Cytoscape

## Examples

``` r
if (FALSE) { # \dontrun{
data(hol_rom)
sim_table_hol <- sim_table(hol_rom)
g_hol <- dendro_network(sim_table_hol)
hol_com_cpm_all <- find_all_cpm_com(g_hol)
g_hol_gn <- gn_names(g_hol)
cyto_create_graph(g_hol, CPM_table = hol_com_cpm_all, GN_table = g_hol_gn)
} # }
```
