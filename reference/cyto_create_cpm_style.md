# Create CPM style in Cytoscape

Function to create a style in Cytoscape to visualise the communities in
a network using clique percolation method (CPM: Palla et al., 2005). See
also: find_all_cpm_com() Each node is filled with the colour of the
community. If a node is part of several communities a pie chart is used
to show the various community colours. The function uses a graph as
input and the number of cliques (default = 3). The style can be
specified or automatically named based on the name of the network an the
number of cliques. Before starting this function, Cytoscape must be up
and running!

## Usage

``` r
cyto_create_cpm_style(graph_input, k = 3, com_k = NULL, style_name = "auto")
```

## Arguments

- graph_input:

  the graph with the CPM communities

- k:

  clique size for the visualisation. This should be an integer with the
  value 3 or higher

- com_k:

  data_frame with the communities for the specific clique size (two
  columns: node and com_name). This is the result of
  clique_community_names_par() or clique_community_names()

- style_name:

  name of the output style in Cytoscape. If set to "auto", the style is
  derived from the name of the network and value for k

## Value

The style applied in Cytoscape, no objects in R as return.

## Examples

``` r
if (FALSE) { # \dontrun{
data(hol_rom)
sim_table_hol <- sim_table(hol_rom)
g_hol <- dendro_network(sim_table_hol)
hol_com_cpm_k3 <- clique_community_names(g_hol, k = 3)
cyto_create_graph(g_hol)
cyto_create_cpm_style(g_hol, k = 3, com_k = hol_com_cpm_k3)
} # }
```
