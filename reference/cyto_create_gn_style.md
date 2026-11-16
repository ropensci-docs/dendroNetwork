# Create Girvan-Newman communities style in Cytoscape

Function to create a style in Cytoscape to visualise the communities in
a network using the Girvan-Newman method for community detection. Each
node is filled with a separate colour for each community. Before
starting this function, Cytoscape must be up and running!

## Usage

``` r
cyto_create_gn_style(graph_input, gn_coms = NULL, style_name = "auto")
```

## Arguments

- graph_input:

  the graph with the CPM communities

- gn_coms:

  GN communities in graph_input. This is the result of gn_names(). If
  this is not given this will be calculated in the function

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
g_hol_gn <- gn_names(g_hol)
cyto_create_graph(g_hol)
cyto_create_gn_style(g_hol, gn_coms = g_hol_gn)
} # }
```
