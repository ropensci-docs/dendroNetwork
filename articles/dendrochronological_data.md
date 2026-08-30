# dendrochronological data

``` r

library(dendroNetwork)
```

## Dendrochronological data (or tree-ring data)

The package dendroNetwork is based on using dendrochronological (or
tree-ring) data. This data is the input for creating networks and uses
the same data format as used in dplR (Bunn 2008). The base format is
rwl-format as described here:
<https://www.ncei.noaa.gov/pub/data/paleo/treering/treeinfo.txt>. This
data can be imported into R using `dplR::read.tucson("filename.rwl")` .
The resulting dataframe has the series in columns and the years as rows,
as shown below for a selection of data from one of the sample data sets
in `dendroNetwork::hol_rom[400:410,1:4]` :

|      | HOL_AAHOH | HOL_ALT2H | HOL_BDN2H | HOL_BENGH |
|:-----|----------:|----------:|----------:|----------:|
| -103 |      0.96 |        NA |      1.15 |        NA |
| -102 |      0.80 |        NA |      0.95 |        NA |
| -101 |      0.76 |        NA |      0.89 |        NA |
| -100 |      0.69 |        NA |      0.76 |        NA |
| -99  |      0.91 |        NA |      0.74 |        NA |
| -98  |      0.94 |        NA |      0.79 |        NA |
| -97  |      0.90 |        NA |      0.72 |        NA |
| -96  |      0.68 |        NA |      0.96 |        NA |
| -95  |      0.68 |        NA |      0.70 |        NA |
| -94  |      0.69 |        NA |      0.62 |        NA |
| -93  |      0.86 |        NA |      0.77 |        NA |

The row names are the years to which the tree rings are dated, in this
case the years -103 to -93, in other words 102 to 92 BCE (the year 0
does not exist, only mathematically). The column headers are the
identification or names of the tree-ring series. The values represent
the width of a tree ring in millimeters. While dendroNetwork is written
based on measurements of tree-ring widths, other time series with a
similar rwl-format can also be used as input.

The packages comes with two sample data sets to try the package.

### hol_rom: Roman tree-ring site chronologies from Hollstein

These are dendrochronological site chronologies published by Ernst
Hollstein in the 1970s and 1980s (Hollstein 1972; Hollstein 1980). These
52 (pre) Roman site chronologies date between 502 BC and AD 550. This
selection of (pre)Roman site-chronologies was also used in an earlier
study.

### RING_Visser_2021: Roman tree-ring site chronologies

Dendrochronological site chronologies published earlier (Visser, n.d.,
2021). These (pre) Roman site chronologies date between 520 BC and AD
663 and are based on the material from RING (full references to the
source data can be found in the [supplementary
data](https://github.com/RonaldVisser/ProvenanceNetworks/blob/master/SupplementaryTables/Supplementary_table_1a_DOI_data.csv)
(Visser 2021).

The series are named based on their location, species and type of
standardisation For example: ABC_Q1M or ABC_Q1C consist of the same
material from the site ABC (Abcoude), species Q(uercus), chronology 1
and standardisation C(ofecha) and M(eans). See Visser(2021) for more
explanation.

## References

Bunn, Andrew G. 2008. “A Dendrochronology Program Library in r (dplR).”
*Dendrochronologia* 26 (2): 115124.
https://doi.org/<https://doi.org/10.1016/j.dendro.2008.01.002>.

Hollstein, E. 1980. *Mitteleuropäische Eichenchronologie. Trierer
Dendrochronologische Forschungen Zur Archäologie Und Kunstgeschichte.*
Trierer Grabungen Und Forschungen 11. Verlag Philipp von Zabern.

Hollstein, Ernst. 1972. “Dendrochronologische Datierung von Hölzern Aus
Wederath (Belginum).” *Trierer Zeitschrift* 35: 123–25.

Visser, Ronald M. 2021. “Dendrochronological Provenance Patterns.
Network Analysis of Tree-Ring Material Reveals Spatial and Economic
Relations of Roman Timber in the Continental North-Western Provinces.”
*Journal of Computer Applications in Archaeology* 4 (1): 230–53.
<https://doi.org/10.5334/jcaa.79>.

Visser, Ronald M. n.d. *Dendrochronological Provenance Patterns. Code
and Data of Network Analysis of Tree-Ring Material*.
<https://doi.org/10.5281/zenodo.10200361>.
