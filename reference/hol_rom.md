# Roman tree-ring site chronologies from Hollstein

Dendrochronological site chronologies published by Hollstein (1972,
1980). These 52 (pre) Roman site chronologies date between 502 BC and AD
550. This selection of (pre)Roman site-chronologies are also used by
Visser (2021) and made available as Visser (2022).

## Usage

``` r
data(hol_rom)
```

## Format

An object of class `"rwl"`.

## References

Hollstein, E. 1972 Dendrochronologische Datierung von Hölzern aus
Wederath (Belginum). Trierer Zeitschrift 35: 123–125.

Hollstein, E. 1980. Mitteleuropäische Eichenchronologie. Trierer
Dendrochronologische Forschungen zur Archäologie und Kunstgeschichte.
Trierer Grabungen und Forschungen 11. Mainz am Rhein: Verlag Philipp von
Zabern.

Visser, RM. 2021 Dendrochronological Provenance Patterns. Network
Analysis of Tree-Ring Material Reveals Spatial and Economic Relations of
Roman Timber in the Continental North-Western Provinces. Journal of
Computer Applications in Archaeology 4(1): 230–253. DOI:
https://doi.org/10.5334/jcaa.79.

Visser, RM. 2022 Dendrochronological Provenance Patterns. Code and Data
of Network Analysis of Tree-Ring Material. DOI:
https://doi.org/10.5281/zenodo.7157744.

## Examples

``` r
data(hol_rom)
sim_table(hol_rom, last_digit_radius = TRUE)
#>        series_a radius_a   series_b radius_b overlap            r        r_hol
#> 3      HOL_AAHO        H   HOL_BDN2        H      60  0.188406859  0.445023059
#> 7      HOL_AAHO        H   HOL_BRBR        H      87 -0.092025539  0.243008720
#> 11     HOL_AAHO        H   HOL_GKZB        H      77  0.137326483  0.278197844
#> 13     HOL_AAHO        H   HOL_IRRB        H     187  0.493596957  0.393506269
#> 15     HOL_AAHO        H   HOL_KBMB        H     173  0.295691657  0.414522592
#> 18     HOL_AAHO        H   HOL_KMBQ        H     122  0.321154212  0.591621699
#> 20     HOL_AAHO        H   HOL_KORH        H      85  0.050560394  0.288676503
#> 22     HOL_AAHO        H   HOL_LATE        H     103  0.298520123  0.201482556
#> 23     HOL_AAHO        H   HOL_LKBB        H      87  0.024049799  0.327189504
#> 24     HOL_AAHO        H   HOL_LKSB        H     118  0.302268769  0.498699727
#> 25     HOL_AAHO        H   HOL_LKSH        H     134  0.371330048  0.244677604
#> 29     HOL_AAHO        H   HOL_MBRU        H      87  0.065309029  0.459845937
#> 30     HOL_AAHO        H   HOL_MBUF        H     124  0.449018896  0.491842675
#> 32     HOL_AAHO        H   HOL_MRBR        H     138  0.303797212  0.559263260
#> 34     HOL_AAHO        H   HOL_PALZ        H     158  0.306343579  0.421020482
#> 35     HOL_AAHO        H   HOL_SQUS        H     157  0.347714888  0.364675149
#> 39     HOL_AAHO        H  HOL_TMB11        H      87  0.441421672  0.414098997
#> 45     HOL_AAHO        H   HOL_TRPB        H      68  0.356284712  0.490183811
#> 46     HOL_AAHO        H   HOL_TRRB        H     101  0.158422177  0.533836233
#> 47     HOL_AAHO        H   HOL_TRRS        H     187  0.332296592  0.458285337
#> 49     HOL_AAHO        H   HOL_UNLU        H     187 -0.031712669  0.064022899
#> 105    HOL_BDN2        H   HOL_AAHO        H      60  0.188406859  0.445023059
#> 117    HOL_BDN2        H   HOL_IRRB        H      60  0.581057202  0.596238067
#> 122    HOL_BDN2        H   HOL_KMBQ        H      54  0.138911744  0.213496197
#> 125    HOL_BDN2        H   HOL_LAGE        H      58  0.433764001  0.341440542
#> 126    HOL_BDN2        H   HOL_LATE        H     326  0.475777446  0.081137615
#> 130    HOL_BDN2        H   HOL_MANC        H     226  0.121782161  0.215989030
#> 138    HOL_BDN2        H   HOL_PALZ        H     146  0.127156008  0.409393249
#> 139    HOL_BDN2        H   HOL_SQUS        H      60  0.218914148  0.092752129
#> 142    HOL_BDN2        H   HOL_TITE        H      84  0.283233492  0.338320042
#> 150    HOL_BDN2        H   HOL_TRRB        H     276  0.252126581  0.518011876
#> 151    HOL_BDN2        H   HOL_TRRS        H      60  0.435542796  0.176853289
#> 153    HOL_BDN2        H   HOL_UNLU        H      91  0.064324801  0.242647987
#> 161    HOL_BENG        H   HOL_BERL        H      59  0.303932199  0.185960846
#> 164    HOL_BENG        H   HOL_BROI        H      69  0.489170203  0.271041933
#> 173    HOL_BENG        H   HOL_KKNA        H      69  0.282119113  0.225799744
#> 175    HOL_BENG        H   HOL_KORB        H      63  0.665527356  0.315735142
#> 212    HOL_BERL        H   HOL_BENG        H      59  0.303932199  0.185960846
#> 216    HOL_BERL        H   HOL_BROI        H     220  0.719781537  0.176768041
#> 218    HOL_BERL        H   HOL_ERP1        H      93  0.450376684  0.050316658
#> 225    HOL_BERL        H   HOL_KKNA        H     228  0.648796646  0.304733827
#> 227    HOL_BERL        H   HOL_KORB        H      53  0.606828824  0.179090988
#> 241    HOL_BERL        H   HOL_OB2B        H     150  0.491688025  0.148084800
#> 267    HOL_BICK        H   HOL_BRBR        H      54  0.470995986  0.250731594
#> 271    HOL_BICK        H   HOL_GKZB        H      59  0.038772914  0.445440499
#> 272    HOL_BICK        H   HOL_GUST        H      77  0.391801212  0.397332816
#> 274    HOL_BICK        H   HOL_K9SA        H      77 -0.079101900  0.095084116
#> 275    HOL_BICK        H   HOL_KBMB        H      77  0.205125340  0.295696702
#> 283    HOL_BICK        H   HOL_LKBB        H      77  0.490403004  0.337521326
#> 284    HOL_BICK        H   HOL_LKSB        H      70  0.184627117  0.183442546
#> 285    HOL_BICK        H   HOL_LKSH        H      66  0.159042134  0.144177426
#> 287    HOL_BICK        H  HOL_MB253        H      77  0.367288301  0.303391543
#> 291    HOL_BICK        H   HOL_MIWA        H      53  0.026932105  0.104871658
#> 296    HOL_BICK        H   HOL_TATE        H      77  0.133636892  0.326688577
#> 300    HOL_BICK        H  HOL_TMB12        H      77  0.325425741  0.335678517
#> 301    HOL_BICK        H  HOL_TMB21        H      69  0.308309538  0.249050794
#> 302    HOL_BICK        H  HOL_TMB22        H      77  0.335960060  0.179517522
#> 307    HOL_BICK        H   HOL_TRRS        H      66  0.099903053  0.211226084
#> 308    HOL_BICK        H   HOL_TWML        H      77  0.330742957  0.319830826
#> 310    HOL_BICK        H   HOL_WEDE        H      77  0.334837187  0.220952568
#> 311    HOL_BICK        H   HOL_WEDG        H      64  0.327289636 -0.116183942
#> 312    HOL_BICK        H   HOL_WEDW        H      77  0.308287116  0.173699858
#> 313    HOL_BRBR        H   HOL_AAHO        H      87 -0.092025539  0.243008720
#> 318    HOL_BRBR        H   HOL_BICK        H      54  0.470995986  0.250731594
#> 323    HOL_BRBR        H   HOL_GKZB        H     143  0.304436243  0.316285251
#> 324    HOL_BRBR        H   HOL_GUST        H      54  0.556559087  0.201123572
#> 325    HOL_BRBR        H   HOL_IRRB        H     102  0.123024561  0.115560935
#> 326    HOL_BRBR        H   HOL_K9SA        H      89 -0.032851634  0.195837658
#> 327    HOL_BRBR        H   HOL_KBMB        H     153 -0.047533196  0.223174924
#> 332    HOL_BRBR        H   HOL_KORH        H      85  0.392176452  0.198172039
#> 335    HOL_BRBR        H   HOL_LKBB        H     153  0.514217918  0.411207086
#> 336    HOL_BRBR        H   HOL_LKSB        H     153  0.557418690  0.327587355
#> 337    HOL_BRBR        H   HOL_LKSH        H     153  0.540711818  0.230863880
#> 339    HOL_BRBR        H  HOL_MB253        H      54  0.324974883  0.109715802
#> 341    HOL_BRBR        H   HOL_MBRU        H     100  0.287621312  0.273093775
#> 342    HOL_BRBR        H   HOL_MBUF        H      55  0.378409478  0.394466702
#> 344    HOL_BRBR        H   HOL_MRBR        H      73  0.299089892  0.276143408
#> 346    HOL_BRBR        H   HOL_PALZ        H      58  0.381600162  0.076475951
#> 347    HOL_BRBR        H   HOL_SQUS        H      57  0.238618861  0.204771374
#> 348    HOL_BRBR        H   HOL_TATE        H      60  0.230664609  0.189656344
#> 351    HOL_BRBR        H  HOL_TMB11        H      95  0.094108502  0.296739269
#> 352    HOL_BRBR        H  HOL_TMB12        H      54  0.127818031  0.254408087
#> 353    HOL_BRBR        H  HOL_TMB21        H      54  0.141560682  0.182896209
#> 354    HOL_BRBR        H  HOL_TMB22        H      54  0.621466404  0.184390902
#> 359    HOL_BRBR        H   HOL_TRRS        H     153 -0.037596570  0.314223987
#> 360    HOL_BRBR        H   HOL_TWML        H      98  0.488033063  0.189688375
#> 361    HOL_BRBR        H   HOL_UNLU        H      90  0.234093805  0.107941312
#> 362    HOL_BRBR        H   HOL_WEDE        H      64  0.274358628  0.258833452
#> 364    HOL_BRBR        H   HOL_WEDW        H      64  0.225918357  0.241293227
#> 368    HOL_BROI        H   HOL_BENG        H      69  0.489170203  0.271041933
#> 369    HOL_BROI        H   HOL_BERL        H     220  0.719781537  0.176768041
#> 374    HOL_BROI        H   HOL_ERP1        H      93  0.483247297 -0.112654333
#> 381    HOL_BROI        H   HOL_KKNA        H     231  0.729106542  0.309125970
#> 383    HOL_BROI        H   HOL_KORB        H      70  0.734831416  0.432936730
#> 397    HOL_BROI        H   HOL_OB2B        H     103  0.272484254  0.011041913
#> 430    HOL_DHRO        H   HOL_K9SA        H      93 -0.026333217  0.435453467
#> 431    HOL_DHRO        H   HOL_KBMB        H      85  0.370625080  0.493546818
#> 435    HOL_DHRO        H   HOL_KORB        H      86  0.079789205  0.255727290
#> 439    HOL_DHRO        H   HOL_LKBB        H      65  0.557982768  0.539011875
#> 443    HOL_DHRO        H  HOL_MB253        H     116 -0.084985667  0.528471099
#> 444    HOL_DHRO        H  HOL_MB259        H      59  0.288547531  0.451881863
#> 447    HOL_DHRO        H   HOL_MIWA        H     110  0.568889048  0.443083941
#> 452    HOL_DHRO        H   HOL_TATE        H     116  0.245609153  0.418843672
#> 456    HOL_DHRO        H  HOL_TMB12        H     116  0.706576038  0.599445863
#> 460    HOL_DHRO        H HOL_TRMB32        H      52  0.189234193  0.513346278
#> 464    HOL_DHRO        H   HOL_TWML        H     113  0.301798507  0.323127643
#> 466    HOL_DHRO        H   HOL_WEDE        H     116  0.386904490  0.516880163
#> 467    HOL_DHRO        H   HOL_WEDG        H      75  0.620845102  0.583970783
#> 468    HOL_DHRO        H   HOL_WEDW        H     116  0.394374162  0.519431179
#> 473    HOL_ERP1        H   HOL_BERL        H      93  0.450376684  0.050316658
#> 476    HOL_ERP1        H   HOL_BROI        H      93  0.483247297 -0.112654333
#> 485    HOL_ERP1        H   HOL_KKNA        H      93  0.153494282 -0.025617359
#> 501    HOL_ERP1        H   HOL_OB2B        H      92  0.527554510  0.214297986
#> 521    HOL_GKZB        H   HOL_AAHO        H      77  0.137326483  0.278197844
#> 526    HOL_GKZB        H   HOL_BICK        H      59  0.038772914  0.445440499
#> 527    HOL_GKZB        H   HOL_BRBR        H     143  0.304436243  0.316285251
#> 532    HOL_GKZB        H   HOL_GUST        H      59  0.056879061  0.468344028
#> 533    HOL_GKZB        H   HOL_IRRB        H      92  0.045835787  0.316290805
#> 534    HOL_GKZB        H   HOL_K9SA        H      94 -0.013513101 -0.037757006
#> 535    HOL_GKZB        H   HOL_KBMB        H     148  0.004404887  0.305523062
#> 540    HOL_GKZB        H   HOL_KORH        H      75  0.015126348  0.539912486
#> 543    HOL_GKZB        H   HOL_LKBB        H     148  0.592894958  0.385617958
#> 544    HOL_GKZB        H   HOL_LKSB        H     148  0.595772324  0.369116446
#> 545    HOL_GKZB        H   HOL_LKSH        H     148  0.280937674  0.170810453
#> 547    HOL_GKZB        H  HOL_MB253        H      59  0.093307054  0.171147887
#> 549    HOL_GKZB        H   HOL_MBRU        H      90  0.307503904  0.507064623
#> 552    HOL_GKZB        H   HOL_MRBR        H      63  0.308367588  0.495787214
#> 556    HOL_GKZB        H   HOL_TATE        H      65  0.328003333  0.223500616
#> 559    HOL_GKZB        H  HOL_TMB11        H      85  0.000173664  0.340106128
#> 560    HOL_GKZB        H  HOL_TMB12        H      59  0.206204548  0.164828147
#> 561    HOL_GKZB        H  HOL_TMB21        H      59 -0.063652080  0.237617788
#> 562    HOL_GKZB        H  HOL_TMB22        H      59 -0.109329770  0.077309696
#> 567    HOL_GKZB        H   HOL_TRRS        H     148 -0.188090442  0.259036387
#> 568    HOL_GKZB        H   HOL_TWML        H     103  0.183764564  0.242532939
#> 569    HOL_GKZB        H   HOL_UNLU        H      80  0.086962224  0.054221366
#> 570    HOL_GKZB        H   HOL_WEDE        H      69  0.156149106  0.240202586
#> 572    HOL_GKZB        H   HOL_WEDW        H      69  0.123656717  0.218464883
#> 578    HOL_GUST        H   HOL_BICK        H      77  0.391801212  0.397332816
#> 579    HOL_GUST        H   HOL_BRBR        H      54  0.556559087  0.201123572
#> 583    HOL_GUST        H   HOL_GKZB        H      59  0.056879061  0.468344028
#> 586    HOL_GUST        H   HOL_K9SA        H      88  0.145345889  0.229675843
#> 587    HOL_GUST        H   HOL_KBMB        H      88  0.245883024  0.369449586
#> 595    HOL_GUST        H   HOL_LKBB        H      88  0.421581798  0.396463781
#> 596    HOL_GUST        H   HOL_LKSB        H      70  0.387944916  0.277987333
#> 597    HOL_GUST        H   HOL_LKSH        H      66  0.228060287  0.205141873
#> 599    HOL_GUST        H  HOL_MB253        H      88  0.195674878  0.552690080
#> 603    HOL_GUST        H   HOL_MIWA        H      64  0.486231851  0.211205939
#> 608    HOL_GUST        H   HOL_TATE        H      88  0.310066749  0.305284742
#> 612    HOL_GUST        H  HOL_TMB12        H      88  0.424427059  0.472487999
#> 613    HOL_GUST        H  HOL_TMB21        H      69  0.125643831  0.308952578
#> 614    HOL_GUST        H  HOL_TMB22        H      82  0.679291680  0.287488012
#> 619    HOL_GUST        H   HOL_TRRS        H      66 -0.185446513  0.338579482
#> 620    HOL_GUST        H   HOL_TWML        H      88  0.492230094  0.303859893
#> 622    HOL_GUST        H   HOL_WEDE        H      88  0.181442734  0.147711923
#> 623    HOL_GUST        H   HOL_WEDG        H      75  0.114871224  0.251548967
#> 624    HOL_GUST        H   HOL_WEDW        H      88  0.112537983  0.078855364
#> 625    HOL_IRRB        H   HOL_AAHO        H     187  0.493596957  0.393506269
#> 627    HOL_IRRB        H   HOL_BDN2        H      60  0.581057202  0.596238067
#> 631    HOL_IRRB        H   HOL_BRBR        H     102  0.123024561  0.115560935
#> 635    HOL_IRRB        H   HOL_GKZB        H      92  0.045835787  0.316290805
#> 639    HOL_IRRB        H   HOL_KBMB        H     188  0.494193558  0.311285485
#> 642    HOL_IRRB        H   HOL_KMBQ        H     122  0.146320981  0.216230639
#> 644    HOL_IRRB        H   HOL_KORH        H      85  0.365580108  0.304804599
#> 646    HOL_IRRB        H   HOL_LATE        H     103  0.515759161  0.196970711
#> 647    HOL_IRRB        H   HOL_LKBB        H     102 -0.169554109  0.246260872
#> 648    HOL_IRRB        H   HOL_LKSB        H     133  0.321052266  0.381384769
#> 649    HOL_IRRB        H   HOL_LKSH        H     149  0.229178936  0.196534990
#> 653    HOL_IRRB        H   HOL_MBRU        H     100  0.037921169  0.242702611
#> 654    HOL_IRRB        H   HOL_MBUF        H     124  0.494744518  0.407919753
#> 656    HOL_IRRB        H   HOL_MRBR        H     138  0.245032881  0.351267297
#> 658    HOL_IRRB        H   HOL_PALZ        H     158  0.589586869  0.408641950
#> 659    HOL_IRRB        H   HOL_SQUS        H     157  0.299853050  0.200795430
#> 663    HOL_IRRB        H  HOL_TMB11        H      95  0.738107843  0.490500528
#> 669    HOL_IRRB        H   HOL_TRPB        H      68  0.331075012  0.425255566
#> 670    HOL_IRRB        H   HOL_TRRB        H     101  0.112710306  0.501053287
#> 671    HOL_IRRB        H   HOL_TRRS        H     202  0.397034405  0.303430429
#> 673    HOL_IRRB        H   HOL_UNLU        H     190  0.141304936  0.152727979
#> 682    HOL_K9SA        H   HOL_BICK        H      77 -0.079101900  0.095084116
#> 683    HOL_K9SA        H   HOL_BRBR        H      89 -0.032851634  0.195837658
#> 685    HOL_K9SA        H   HOL_DHRO        H      93 -0.026333217  0.435453467
#> 687    HOL_K9SA        H   HOL_GKZB        H      94 -0.013513101 -0.037757006
#> 688    HOL_K9SA        H   HOL_GUST        H      88  0.145345889  0.229675843
#> 691    HOL_K9SA        H   HOL_KBMB        H     163  0.273394303  0.333400041
#> 695    HOL_K9SA        H   HOL_KORB        H      63  0.500830859  0.457236393
#> 699    HOL_K9SA        H   HOL_LKBB        H     143  0.287785970  0.242627666
#> 700    HOL_K9SA        H   HOL_LKSB        H     105  0.147632386  0.345038961
#> 701    HOL_K9SA        H   HOL_LKSH        H     101  0.138410746  0.123241013
#> 703    HOL_K9SA        H  HOL_MB253        H     136  0.379300156  0.463258821
#> 707    HOL_K9SA        H   HOL_MIWA        H     112  0.243103119  0.350195331
#> 712    HOL_K9SA        H   HOL_TATE        H     142  0.253814714  0.368958631
#> 716    HOL_K9SA        H  HOL_TMB12        H     136  0.195051113  0.532215394
#> 717    HOL_K9SA        H  HOL_TMB21        H      69  0.225576266  0.360786854
#> 718    HOL_K9SA        H  HOL_TMB22        H      82  0.285254051  0.510479488
#> 723    HOL_K9SA        H   HOL_TRRS        H     101  0.353085800  0.463439523
#> 724    HOL_K9SA        H   HOL_TWML        H     171  0.158939070  0.428712893
#> 726    HOL_K9SA        H   HOL_WEDE        H     146  0.216597331  0.403352862
#> 727    HOL_K9SA        H   HOL_WEDG        H     105  0.002461062  0.347195026
#> 728    HOL_K9SA        H   HOL_WEDW        H     146  0.194764476  0.380558863
#> 729    HOL_KBMB        H   HOL_AAHO        H     173  0.295691657  0.414522592
#> 734    HOL_KBMB        H   HOL_BICK        H      77  0.205125340  0.295696702
#> 735    HOL_KBMB        H   HOL_BRBR        H     153 -0.047533196  0.223174924
#> 737    HOL_KBMB        H   HOL_DHRO        H      85  0.370625080  0.493546818
#> 739    HOL_KBMB        H   HOL_GKZB        H     148  0.004404887  0.305523062
#> 740    HOL_KBMB        H   HOL_GUST        H      88  0.245883024  0.369449586
#> 741    HOL_KBMB        H   HOL_IRRB        H     188  0.494193558  0.311285485
#> 742    HOL_KBMB        H   HOL_K9SA        H     163  0.273394303  0.333400041
#> 746    HOL_KBMB        H   HOL_KMBQ        H     114  0.189622283  0.376163878
#> 747    HOL_KBMB        H   HOL_KORB        H      55  0.364831685  0.324685610
#> 748    HOL_KBMB        H   HOL_KORH        H      85  0.534915200  0.425992683
#> 750    HOL_KBMB        H   HOL_LATE        H      89  0.567261269  0.193522570
#> 751    HOL_KBMB        H   HOL_LKBB        H     207  0.048507830  0.563968508
#> 752    HOL_KBMB        H   HOL_LKSB        H     200  0.205888404  0.515339850
#> 753    HOL_KBMB        H   HOL_LKSH        H     212  0.192053825  0.465966207
#> 755    HOL_KBMB        H  HOL_MB253        H     128  0.158392623  0.455974350
#> 757    HOL_KBMB        H   HOL_MBRU        H     100  0.534248981  0.593245634
#> 758    HOL_KBMB        H   HOL_MBUF        H     124  0.723346282  0.636849856
#> 759    HOL_KBMB        H   HOL_MIWA        H     104  0.321364232  0.354941977
#> 760    HOL_KBMB        H   HOL_MRBR        H     138  0.604376406  0.574695819
#> 762    HOL_KBMB        H   HOL_PALZ        H     144  0.683684975  0.487853519
#> 763    HOL_KBMB        H   HOL_SQUS        H     143  0.482221485  0.406060391
#> 764    HOL_KBMB        H   HOL_TATE        H     134  0.263513287  0.416086104
#> 767    HOL_KBMB        H  HOL_TMB11        H      95  0.179775977  0.369039404
#> 768    HOL_KBMB        H  HOL_TMB12        H     128  0.342397513  0.599927998
#> 769    HOL_KBMB        H  HOL_TMB21        H      69  0.472208117  0.657292845
#> 770    HOL_KBMB        H  HOL_TMB22        H      82  0.310896703  0.500502472
#> 773    HOL_KBMB        H   HOL_TRPB        H      68  0.410963063  0.372995637
#> 774    HOL_KBMB        H   HOL_TRRB        H      87  0.107651532  0.669123266
#> 775    HOL_KBMB        H   HOL_TRRS        H     251  0.389238024  0.574039069
#> 776    HOL_KBMB        H   HOL_TWML        H     172  0.015844598  0.232887482
#> 777    HOL_KBMB        H   HOL_UNLU        H     176  0.360137445  0.271504589
#> 778    HOL_KBMB        H   HOL_WEDE        H     138  0.452358388  0.500901295
#> 779    HOL_KBMB        H   HOL_WEDG        H     105  0.186686657  0.322246064
#> 780    HOL_KBMB        H   HOL_WEDW        H     138  0.430539452  0.438924058
#> 799    HOL_KDGB        H   HOL_KORB        H      83  0.215007343  0.478031417
#> 816    HOL_KDGB        H   HOL_TATE        H      55  0.354746879  0.492059867
#> 817    HOL_KDGB        H   HOL_TATT        H      63 -0.087559381  0.126638336
#> 824    HOL_KDGB        H HOL_TRMB32        H      83  0.174967773  0.450074872
#> 836    HOL_KKNA        H   HOL_BENG        H      69  0.282119113  0.225799744
#> 837    HOL_KKNA        H   HOL_BERL        H     228  0.648796646  0.304733827
#> 840    HOL_KKNA        H   HOL_BROI        H     231  0.729106542  0.309125970
#> 842    HOL_KKNA        H   HOL_ERP1        H      93  0.153494282 -0.025617359
#> 851    HOL_KKNA        H   HOL_KORB        H      64  0.345782321  0.440776458
#> 865    HOL_KKNA        H   HOL_OB2B        H     111  0.306094959  0.042447049
#> 885    HOL_KMBQ        H   HOL_AAHO        H     122  0.321154212  0.591621699
#> 887    HOL_KMBQ        H   HOL_BDN2        H      54  0.138911744  0.213496197
#> 897    HOL_KMBQ        H   HOL_IRRB        H     122  0.146320981  0.216230639
#> 899    HOL_KMBQ        H   HOL_KBMB        H     114  0.189622283  0.376163878
#> 906    HOL_KMBQ        H   HOL_LATE        H      97  0.024111124  0.131747119
#> 908    HOL_KMBQ        H   HOL_LKSB        H      59  0.054764538  0.377749389
#> 909    HOL_KMBQ        H   HOL_LKSH        H      75  0.441272425  0.429744097
#> 914    HOL_KMBQ        H   HOL_MBUF        H      97  0.250720480  0.497686600
#> 916    HOL_KMBQ        H   HOL_MRBR        H      93 -0.033149179  0.435916706
#> 918    HOL_KMBQ        H   HOL_PALZ        H     122  0.213031530  0.332566165
#> 919    HOL_KMBQ        H   HOL_SQUS        H     122  0.112188530  0.250932006
#> 929    HOL_KMBQ        H   HOL_TRPB        H      68 -0.026148714  0.388887146
#> 930    HOL_KMBQ        H   HOL_TRRB        H      95  0.269473726  0.309999844
#> 931    HOL_KMBQ        H   HOL_TRRS        H     122  0.128799278  0.389133386
#> 933    HOL_KMBQ        H   HOL_UNLU        H     122  0.217656631  0.180615553
#> 940    HOL_KORB        H   HOL_BENG        H      63  0.665527356  0.315735142
#> 941    HOL_KORB        H   HOL_BERL        H      53  0.606828824  0.179090988
#> 944    HOL_KORB        H   HOL_BROI        H      70  0.734831416  0.432936730
#> 945    HOL_KORB        H   HOL_DHRO        H      86  0.079789205  0.255727290
#> 950    HOL_KORB        H   HOL_K9SA        H      63  0.500830859  0.457236393
#> 951    HOL_KORB        H   HOL_KBMB        H      55  0.364831685  0.324685610
#> 952    HOL_KORB        H   HOL_KDGB        H      83  0.215007343  0.478031417
#> 953    HOL_KORB        H   HOL_KKNA        H      64  0.345782321  0.440776458
#> 963    HOL_KORB        H  HOL_MB253        H     105  0.592835617  0.610646450
#> 964    HOL_KORB        H  HOL_MB259        H      84  0.490329050  0.413909575
#> 967    HOL_KORB        H   HOL_MIWA        H      80  0.101212307  0.284768032
#> 972    HOL_KORB        H   HOL_TATE        H     138  0.440587868  0.510714524
#> 973    HOL_KORB        H   HOL_TATT        H      85  0.046435228  0.042769777
#> 976    HOL_KORB        H  HOL_TMB12        H      97  0.060272067  0.476987801
#> 980    HOL_KORB        H HOL_TRMB32        H     133  0.454742390  0.496032610
#> 984    HOL_KORB        H   HOL_TWML        H      83  0.171363922  0.387056412
#> 986    HOL_KORB        H   HOL_WEDE        H     124  0.253383305  0.405401632
#> 988    HOL_KORB        H   HOL_WEDW        H     124  0.225610729  0.415516720
#> 989    HOL_KORH        H   HOL_AAHO        H      85  0.050560394  0.288676503
#> 995    HOL_KORH        H   HOL_BRBR        H      85  0.392176452  0.198172039
#> 999    HOL_KORH        H   HOL_GKZB        H      75  0.015126348  0.539912486
#> 1001   HOL_KORH        H   HOL_IRRB        H      85  0.365580108  0.304804599
#> 1003   HOL_KORH        H   HOL_KBMB        H      85  0.534915200  0.425992683
#> 1011   HOL_KORH        H   HOL_LKBB        H      85  0.176961734  0.577187570
#> 1012   HOL_KORH        H   HOL_LKSB        H      85  0.293937953  0.546311524
#> 1013   HOL_KORH        H   HOL_LKSH        H      85  0.270758454  0.313355332
#> 1017   HOL_KORH        H   HOL_MBRU        H      85  0.310680627  0.536081723
#> 1018   HOL_KORH        H   HOL_MBUF        H      55  0.284118102  0.084468501
#> 1020   HOL_KORH        H   HOL_MRBR        H      73  0.403900225  0.487490594
#> 1022   HOL_KORH        H   HOL_PALZ        H      58  0.436837722  0.200495727
#> 1023   HOL_KORH        H   HOL_SQUS        H      57  0.477601912  0.331567296
#> 1027   HOL_KORH        H  HOL_TMB11        H      85  0.447164075  0.480030045
#> 1035   HOL_KORH        H   HOL_TRRS        H      85  0.642772074  0.480783259
#> 1037   HOL_KORH        H   HOL_UNLU        H      85  0.120928149 -0.087497523
#> 1043   HOL_LAGE        H   HOL_BDN2        H      58  0.433764001  0.341440542
#> 1062   HOL_LAGE        H   HOL_LATE        H      58  0.045105122  0.117701098
#> 1066   HOL_LAGE        H   HOL_MANC        H      58  0.147704300  0.265611390
#> 1078   HOL_LAGE        H   HOL_TITE        H      58  0.181761277  0.392027733
#> 1086   HOL_LAGE        H   HOL_TRRB        H      58  0.422119379  0.394990644
#> 1093   HOL_LATE        H   HOL_AAHO        H     103  0.298520123  0.201482556
#> 1095   HOL_LATE        H   HOL_BDN2        H     326  0.475777446  0.081137615
#> 1105   HOL_LATE        H   HOL_IRRB        H     103  0.515759161  0.196970711
#> 1107   HOL_LATE        H   HOL_KBMB        H      89  0.567261269  0.193522570
#> 1110   HOL_LATE        H   HOL_KMBQ        H      97  0.024111124  0.131747119
#> 1113   HOL_LATE        H   HOL_LAGE        H      58  0.045105122  0.117701098
#> 1117   HOL_LATE        H   HOL_LKSH        H      50 -0.230459549           NA
#> 1118   HOL_LATE        H   HOL_MANC        H     226 -0.059788543 -0.002400243
#> 1122   HOL_LATE        H   HOL_MBUF        H      72  0.171757641  0.133946819
#> 1124   HOL_LATE        H   HOL_MRBR        H      68  0.441573630  0.083108235
#> 1126   HOL_LATE        H   HOL_PALZ        H     189  0.431646461  0.033203004
#> 1127   HOL_LATE        H   HOL_SQUS        H     103  0.257036312  0.104705526
#> 1130   HOL_LATE        H   HOL_TITE        H      84  0.097782027  0.008943228
#> 1137   HOL_LATE        H   HOL_TRPB        H      68  0.259949997 -0.011459399
#> 1138   HOL_LATE        H   HOL_TRRB        H     317  0.019928936  0.061802157
#> 1139   HOL_LATE        H   HOL_TRRS        H     103  0.239689088  0.032238120
#> 1141   HOL_LATE        H   HOL_UNLU        H     134 -0.033085444 -0.025515608
#> 1145   HOL_LKBB        H   HOL_AAHO        H      87  0.024049799  0.327189504
#> 1150   HOL_LKBB        H   HOL_BICK        H      77  0.490403004  0.337521326
#> 1151   HOL_LKBB        H   HOL_BRBR        H     153  0.514217918  0.411207086
#> 1153   HOL_LKBB        H   HOL_DHRO        H      65  0.557982768  0.539011875
#> 1155   HOL_LKBB        H   HOL_GKZB        H     148  0.592894958  0.385617958
#> 1156   HOL_LKBB        H   HOL_GUST        H      88  0.421581798  0.396463781
#> 1157   HOL_LKBB        H   HOL_IRRB        H     102 -0.169554109  0.246260872
#> 1158   HOL_LKBB        H   HOL_K9SA        H     143  0.287785970  0.242627666
#> 1159   HOL_LKBB        H   HOL_KBMB        H     207  0.048507830  0.563968508
#> 1164   HOL_LKBB        H   HOL_KORH        H      85  0.176961734  0.577187570
#> 1168   HOL_LKBB        H   HOL_LKSB        H     169  0.653855370  0.658100556
#> 1169   HOL_LKBB        H   HOL_LKSH        H     165  0.342351849  0.538476927
#> 1171   HOL_LKBB        H  HOL_MB253        H     108  0.154307891  0.428379162
#> 1173   HOL_LKBB        H   HOL_MBRU        H     100  0.649670541  0.682432783
#> 1174   HOL_LKBB        H   HOL_MBUF        H      55  0.689133115  0.585865836
#> 1175   HOL_LKBB        H   HOL_MIWA        H      84  0.427418323  0.423513508
#> 1176   HOL_LKBB        H   HOL_MRBR        H      73  0.686515436  0.643945809
#> 1178   HOL_LKBB        H   HOL_PALZ        H      58  0.334509555  0.362400744
#> 1179   HOL_LKBB        H   HOL_SQUS        H      57  0.351425985  0.415145689
#> 1180   HOL_LKBB        H   HOL_TATE        H     114  0.403610102  0.461347418
#> 1183   HOL_LKBB        H  HOL_TMB11        H      95 -0.126528737  0.456570740
#> 1184   HOL_LKBB        H  HOL_TMB12        H     108  0.544759440  0.603884425
#> 1185   HOL_LKBB        H  HOL_TMB21        H      69  0.356994329  0.436806035
#> 1186   HOL_LKBB        H  HOL_TMB22        H      82  0.372160586  0.421610342
#> 1191   HOL_LKBB        H   HOL_TRRS        H     165 -0.089227628  0.513661005
#> 1192   HOL_LKBB        H   HOL_TWML        H     152  0.566824381  0.312159966
#> 1193   HOL_LKBB        H   HOL_UNLU        H      90  0.114272999  0.144795007
#> 1194   HOL_LKBB        H   HOL_WEDE        H     118  0.347653246  0.485822075
#> 1195   HOL_LKBB        H   HOL_WEDG        H      95  0.341031432  0.407961750
#> 1196   HOL_LKBB        H   HOL_WEDW        H     118  0.265138039  0.467384322
#> 1197   HOL_LKSB        H   HOL_AAHO        H     118  0.302268769  0.498699727
#> 1202   HOL_LKSB        H   HOL_BICK        H      70  0.184627117  0.183442546
#> 1203   HOL_LKSB        H   HOL_BRBR        H     153  0.557418690  0.327587355
#> 1207   HOL_LKSB        H   HOL_GKZB        H     148  0.595772324  0.369116446
#> 1208   HOL_LKSB        H   HOL_GUST        H      70  0.387944916  0.277987333
#> 1209   HOL_LKSB        H   HOL_IRRB        H     133  0.321052266  0.381384769
#> 1210   HOL_LKSB        H   HOL_K9SA        H     105  0.147632386  0.345038961
#> 1211   HOL_LKSB        H   HOL_KBMB        H     200  0.205888404  0.515339850
#> 1214   HOL_LKSB        H   HOL_KMBQ        H      59  0.054764538  0.377749389
#> 1216   HOL_LKSB        H   HOL_KORH        H      85  0.293937953  0.546311524
#> 1219   HOL_LKSB        H   HOL_LKBB        H     169  0.653855370  0.658100556
#> 1221   HOL_LKSB        H   HOL_LKSH        H     196  0.541084026  0.513610375
#> 1223   HOL_LKSB        H  HOL_MB253        H      70 -0.141961669  0.387233649
#> 1225   HOL_LKSB        H   HOL_MBRU        H     100  0.319163518  0.547674147
#> 1226   HOL_LKSB        H   HOL_MBUF        H      86  0.162226127  0.397582782
#> 1228   HOL_LKSB        H   HOL_MRBR        H     104  0.411365673  0.630874957
#> 1230   HOL_LKSB        H   HOL_PALZ        H      89  0.114105772  0.315740262
#> 1231   HOL_LKSB        H   HOL_SQUS        H      88  0.103289823  0.327399632
#> 1232   HOL_LKSB        H   HOL_TATE        H      76  0.395525047  0.378277671
#> 1235   HOL_LKSB        H  HOL_TMB11        H      95  0.223933278  0.452640907
#> 1236   HOL_LKSB        H  HOL_TMB12        H      70  0.225414032  0.489700927
#> 1237   HOL_LKSB        H  HOL_TMB21        H      69  0.223427090  0.528989194
#> 1238   HOL_LKSB        H  HOL_TMB22        H      70  0.492548432  0.334379418
#> 1243   HOL_LKSB        H   HOL_TRRS        H     196 -0.053779651  0.461660810
#> 1244   HOL_LKSB        H   HOL_TWML        H     114  0.509604090  0.371210304
#> 1245   HOL_LKSB        H   HOL_UNLU        H     121  0.114516712  0.150898944
#> 1246   HOL_LKSB        H   HOL_WEDE        H      80  0.264211526  0.426866051
#> 1247   HOL_LKSB        H   HOL_WEDG        H      57  0.037667612  0.173995168
#> 1248   HOL_LKSB        H   HOL_WEDW        H      80  0.168797282  0.389698539
#> 1249   HOL_LKSH        H   HOL_AAHO        H     134  0.371330048  0.244677604
#> 1254   HOL_LKSH        H   HOL_BICK        H      66  0.159042134  0.144177426
#> 1255   HOL_LKSH        H   HOL_BRBR        H     153  0.540711818  0.230863880
#> 1259   HOL_LKSH        H   HOL_GKZB        H     148  0.280937674  0.170810453
#> 1260   HOL_LKSH        H   HOL_GUST        H      66  0.228060287  0.205141873
#> 1261   HOL_LKSH        H   HOL_IRRB        H     149  0.229178936  0.196534990
#> 1262   HOL_LKSH        H   HOL_K9SA        H     101  0.138410746  0.123241013
#> 1263   HOL_LKSH        H   HOL_KBMB        H     212  0.192053825  0.465966207
#> 1266   HOL_LKSH        H   HOL_KMBQ        H      75  0.441272425  0.429744097
#> 1268   HOL_LKSH        H   HOL_KORH        H      85  0.270758454  0.313355332
#> 1270   HOL_LKSH        H   HOL_LATE        H      50 -0.230459549           NA
#> 1271   HOL_LKSH        H   HOL_LKBB        H     165  0.342351849  0.538476927
#> 1272   HOL_LKSH        H   HOL_LKSB        H     196  0.541084026  0.513610375
#> 1275   HOL_LKSH        H  HOL_MB253        H      66  0.214533319  0.170299957
#> 1277   HOL_LKSH        H   HOL_MBRU        H     100 -0.008618018  0.453316447
#> 1278   HOL_LKSH        H   HOL_MBUF        H     102  0.475212621  0.321238812
#> 1280   HOL_LKSH        H   HOL_MRBR        H     120  0.003288783  0.407830073
#> 1282   HOL_LKSH        H   HOL_PALZ        H     105  0.035599017  0.308005630
#> 1283   HOL_LKSH        H   HOL_SQUS        H     104  0.260830951  0.258130680
#> 1284   HOL_LKSH        H   HOL_TATE        H      72  0.241429031  0.408594403
#> 1287   HOL_LKSH        H  HOL_TMB11        H      95  0.345407296  0.281689900
#> 1288   HOL_LKSH        H  HOL_TMB12        H      66  0.402407134  0.466653142
#> 1289   HOL_LKSH        H  HOL_TMB21        H      66  0.377395037  0.500255379
#> 1290   HOL_LKSH        H  HOL_TMB22        H      66  0.366729580  0.295082417
#> 1295   HOL_LKSH        H   HOL_TRRS        H     212  0.088249244  0.415316109
#> 1296   HOL_LKSH        H   HOL_TWML        H     110  0.420838212  0.200631160
#> 1297   HOL_LKSH        H   HOL_UNLU        H     137  0.320611330  0.141760093
#> 1298   HOL_LKSH        H   HOL_WEDE        H      76  0.218206049  0.284314989
#> 1299   HOL_LKSH        H   HOL_WEDG        H      53  0.170916909  0.297401147
#> 1300   HOL_LKSH        H   HOL_WEDW        H      76  0.196719235  0.282650191
#> 1303   HOL_MANC        H   HOL_BDN2        H     226  0.121782161  0.215989030
#> 1321   HOL_MANC        H   HOL_LAGE        H      58  0.147704300  0.265611390
#> 1322   HOL_MANC        H   HOL_LATE        H     226 -0.059788543 -0.002400243
#> 1334   HOL_MANC        H   HOL_PALZ        H      87  0.316267215  0.430411956
#> 1338   HOL_MANC        H   HOL_TITE        H      84  0.070299770  0.175630806
#> 1346   HOL_MANC        H   HOL_TRRB        H     217  0.191327279  0.336500430
#> 1358  HOL_MB253        H   HOL_BICK        H      77  0.367288301  0.303391543
#> 1359  HOL_MB253        H   HOL_BRBR        H      54  0.324974883  0.109715802
#> 1361  HOL_MB253        H   HOL_DHRO        H     116 -0.084985667  0.528471099
#> 1363  HOL_MB253        H   HOL_GKZB        H      59  0.093307054  0.171147887
#> 1364  HOL_MB253        H   HOL_GUST        H      88  0.195674878  0.552690080
#> 1366  HOL_MB253        H   HOL_K9SA        H     136  0.379300156  0.463258821
#> 1367  HOL_MB253        H   HOL_KBMB        H     128  0.158392623  0.455974350
#> 1371  HOL_MB253        H   HOL_KORB        H     105  0.592835617  0.610646450
#> 1375  HOL_MB253        H   HOL_LKBB        H     108  0.154307891  0.428379162
#> 1376  HOL_MB253        H   HOL_LKSB        H      70 -0.141961669  0.387233649
#> 1377  HOL_MB253        H   HOL_LKSH        H      66  0.214533319  0.170299957
#> 1380  HOL_MB253        H  HOL_MB259        H      78  0.159776650  0.469755979
#> 1383  HOL_MB253        H   HOL_MIWA        H     129 -0.322827810  0.332488757
#> 1388  HOL_MB253        H   HOL_TATE        H     178  0.106930926  0.551991160
#> 1392  HOL_MB253        H  HOL_TMB12        H     170 -0.233782014  0.649386617
#> 1393  HOL_MB253        H  HOL_TMB21        H      69  0.403444986  0.545565464
#> 1394  HOL_MB253        H  HOL_TMB22        H      82  0.136354296  0.416613457
#> 1396  HOL_MB253        H HOL_TRMB32        H      71  0.517839579  0.675646409
#> 1399  HOL_MB253        H   HOL_TRRS        H      66  0.643374022  0.556914738
#> 1400  HOL_MB253        H   HOL_TWML        H     156 -0.146541730  0.365020421
#> 1402  HOL_MB253        H   HOL_WEDE        H     178  0.459390150  0.530474537
#> 1403  HOL_MB253        H   HOL_WEDG        H     105  0.270299737  0.374831539
#> 1404  HOL_MB253        H   HOL_WEDW        H     178  0.475733073  0.497914415
#> 1413  HOL_MB259        H   HOL_DHRO        H      59  0.288547531  0.451881863
#> 1423  HOL_MB259        H   HOL_KORB        H      84  0.490329050  0.413909575
#> 1431  HOL_MB259        H  HOL_MB253        H      78  0.159776650  0.469755979
#> 1435  HOL_MB259        H   HOL_MIWA        H      53  0.590943015  0.509241731
#> 1440  HOL_MB259        H   HOL_TATE        H      84  0.183574774  0.397481879
#> 1441  HOL_MB259        H   HOL_TATT        H      50  0.263201374           NA
#> 1444  HOL_MB259        H  HOL_TMB12        H      70  0.270162719  0.572080219
#> 1448  HOL_MB259        H HOL_TRMB32        H      77  0.529496800  0.459110314
#> 1452  HOL_MB259        H   HOL_TWML        H      56  0.024214611  0.517503480
#> 1454  HOL_MB259        H   HOL_WEDE        H      84  0.151884006  0.569579263
#> 1456  HOL_MB259        H   HOL_WEDW        H      84  0.162768833  0.557212425
#> 1457   HOL_MBRU        H   HOL_AAHO        H      87  0.065309029  0.459845937
#> 1463   HOL_MBRU        H   HOL_BRBR        H     100  0.287621312  0.273093775
#> 1467   HOL_MBRU        H   HOL_GKZB        H      90  0.307503904  0.507064623
#> 1469   HOL_MBRU        H   HOL_IRRB        H     100  0.037921169  0.242702611
#> 1471   HOL_MBRU        H   HOL_KBMB        H     100  0.534248981  0.593245634
#> 1476   HOL_MBRU        H   HOL_KORH        H      85  0.310680627  0.536081723
#> 1479   HOL_MBRU        H   HOL_LKBB        H     100  0.649670541  0.682432783
#> 1480   HOL_MBRU        H   HOL_LKSB        H     100  0.319163518  0.547674147
#> 1481   HOL_MBRU        H   HOL_LKSH        H     100 -0.008618018  0.453316447
#> 1486   HOL_MBRU        H   HOL_MBUF        H      55  0.640299285  0.567773194
#> 1488   HOL_MBRU        H   HOL_MRBR        H      73  0.775861707  0.801452796
#> 1490   HOL_MBRU        H   HOL_PALZ        H      58  0.506117270  0.368504172
#> 1491   HOL_MBRU        H   HOL_SQUS        H      57  0.391808284  0.458484738
#> 1495   HOL_MBRU        H  HOL_TMB11        H      95  0.124080604  0.528106736
#> 1503   HOL_MBRU        H   HOL_TRRS        H     100  0.460348649  0.584573346
#> 1505   HOL_MBRU        H   HOL_UNLU        H      90  0.176705007  0.138971604
#> 1509   HOL_MBUF        H   HOL_AAHO        H     124  0.449018896  0.491842675
#> 1515   HOL_MBUF        H   HOL_BRBR        H      55  0.378409478  0.394466702
#> 1521   HOL_MBUF        H   HOL_IRRB        H     124  0.494744518  0.407919753
#> 1523   HOL_MBUF        H   HOL_KBMB        H     124  0.723346282  0.636849856
#> 1526   HOL_MBUF        H   HOL_KMBQ        H      97  0.250720480  0.497686600
#> 1528   HOL_MBUF        H   HOL_KORH        H      55  0.284118102  0.084468501
#> 1530   HOL_MBUF        H   HOL_LATE        H      72  0.171757641  0.133946819
#> 1531   HOL_MBUF        H   HOL_LKBB        H      55  0.689133115  0.585865836
#> 1532   HOL_MBUF        H   HOL_LKSB        H      86  0.162226127  0.397582782
#> 1533   HOL_MBUF        H   HOL_LKSH        H     102  0.475212621  0.321238812
#> 1537   HOL_MBUF        H   HOL_MBRU        H      55  0.640299285  0.567773194
#> 1540   HOL_MBUF        H   HOL_MRBR        H     120  0.646291133  0.624179143
#> 1542   HOL_MBUF        H   HOL_PALZ        H     124  0.608691700  0.714996995
#> 1543   HOL_MBUF        H   HOL_SQUS        H     124  0.451006541  0.510205405
#> 1547   HOL_MBUF        H  HOL_TMB11        H      55  0.097614000  0.260539250
#> 1553   HOL_MBUF        H   HOL_TRPB        H      64  0.616201031  0.552756931
#> 1554   HOL_MBUF        H   HOL_TRRB        H      70  0.383379749  0.716668333
#> 1555   HOL_MBUF        H   HOL_TRRS        H     124  0.446763833  0.670593303
#> 1557   HOL_MBUF        H   HOL_UNLU        H     124  0.305811681  0.240252770
#> 1566   HOL_MIWA        H   HOL_BICK        H      53  0.026932105  0.104871658
#> 1569   HOL_MIWA        H   HOL_DHRO        H     110  0.568889048  0.443083941
#> 1572   HOL_MIWA        H   HOL_GUST        H      64  0.486231851  0.211205939
#> 1574   HOL_MIWA        H   HOL_K9SA        H     112  0.243103119  0.350195331
#> 1575   HOL_MIWA        H   HOL_KBMB        H     104  0.321364232  0.354941977
#> 1579   HOL_MIWA        H   HOL_KORB        H      80  0.101212307  0.284768032
#> 1583   HOL_MIWA        H   HOL_LKBB        H      84  0.427418323  0.423513508
#> 1587   HOL_MIWA        H  HOL_MB253        H     129 -0.322827810  0.332488757
#> 1588   HOL_MIWA        H  HOL_MB259        H      53  0.590943015  0.509241731
#> 1596   HOL_MIWA        H   HOL_TATE        H     129  0.412145116  0.320113481
#> 1600   HOL_MIWA        H  HOL_TMB12        H     129  0.708490105  0.429404283
#> 1602   HOL_MIWA        H  HOL_TMB22        H      58  0.378996713  0.229551518
#> 1608   HOL_MIWA        H   HOL_TWML        H     129  0.281844726  0.221487629
#> 1610   HOL_MIWA        H   HOL_WEDE        H     129  0.070142752  0.495090767
#> 1611   HOL_MIWA        H   HOL_WEDG        H      94  0.016502954  0.460010471
#> 1612   HOL_MIWA        H   HOL_WEDW        H     129  0.030091643  0.477594560
#> 1613   HOL_MRBR        H   HOL_AAHO        H     138  0.303797212  0.559263260
#> 1619   HOL_MRBR        H   HOL_BRBR        H      73  0.299089892  0.276143408
#> 1623   HOL_MRBR        H   HOL_GKZB        H      63  0.308367588  0.495787214
#> 1625   HOL_MRBR        H   HOL_IRRB        H     138  0.245032881  0.351267297
#> 1627   HOL_MRBR        H   HOL_KBMB        H     138  0.604376406  0.574695819
#> 1630   HOL_MRBR        H   HOL_KMBQ        H      93 -0.033149179  0.435916706
#> 1632   HOL_MRBR        H   HOL_KORH        H      73  0.403900225  0.487490594
#> 1634   HOL_MRBR        H   HOL_LATE        H      68  0.441573630  0.083108235
#> 1635   HOL_MRBR        H   HOL_LKBB        H      73  0.686515436  0.643945809
#> 1636   HOL_MRBR        H   HOL_LKSB        H     104  0.411365673  0.630874957
#> 1637   HOL_MRBR        H   HOL_LKSH        H     120  0.003288783  0.407830073
#> 1641   HOL_MRBR        H   HOL_MBRU        H      73  0.775861707  0.801452796
#> 1642   HOL_MRBR        H   HOL_MBUF        H     120  0.646291133  0.624179143
#> 1646   HOL_MRBR        H   HOL_PALZ        H     123  0.539047700  0.536001850
#> 1647   HOL_MRBR        H   HOL_SQUS        H     122  0.406418426  0.443851725
#> 1651   HOL_MRBR        H  HOL_TMB11        H      73  0.095326145  0.547150742
#> 1657   HOL_MRBR        H   HOL_TRPB        H      60  0.694007691  0.544136181
#> 1658   HOL_MRBR        H   HOL_TRRB        H      66  0.153066164  0.733701800
#> 1659   HOL_MRBR        H   HOL_TRRS        H     138  0.377208429  0.624626688
#> 1661   HOL_MRBR        H   HOL_UNLU        H     138 -0.110182054  0.109825237
#> 1669   HOL_OB2B        H   HOL_BERL        H     150  0.491688025  0.148084800
#> 1672   HOL_OB2B        H   HOL_BROI        H     103  0.272484254  0.011041913
#> 1674   HOL_OB2B        H   HOL_ERP1        H      92  0.527554510  0.214297986
#> 1681   HOL_OB2B        H   HOL_KKNA        H     111  0.306094959  0.042447049
#> 1717   HOL_PALZ        H   HOL_AAHO        H     158  0.306343579  0.421020482
#> 1719   HOL_PALZ        H   HOL_BDN2        H     146  0.127156008  0.409393249
#> 1723   HOL_PALZ        H   HOL_BRBR        H      58  0.381600162  0.076475951
#> 1729   HOL_PALZ        H   HOL_IRRB        H     158  0.589586869  0.408641950
#> 1731   HOL_PALZ        H   HOL_KBMB        H     144  0.683684975  0.487853519
#> 1734   HOL_PALZ        H   HOL_KMBQ        H     122  0.213031530  0.332566165
#> 1736   HOL_PALZ        H   HOL_KORH        H      58  0.436837722  0.200495727
#> 1738   HOL_PALZ        H   HOL_LATE        H     189  0.431646461  0.033203004
#> 1739   HOL_PALZ        H   HOL_LKBB        H      58  0.334509555  0.362400744
#> 1740   HOL_PALZ        H   HOL_LKSB        H      89  0.114105772  0.315740262
#> 1741   HOL_PALZ        H   HOL_LKSH        H     105  0.035599017  0.308005630
#> 1742   HOL_PALZ        H   HOL_MANC        H      87  0.316267215  0.430411956
#> 1745   HOL_PALZ        H   HOL_MBRU        H      58  0.506117270  0.368504172
#> 1746   HOL_PALZ        H   HOL_MBUF        H     124  0.608691700  0.714996995
#> 1748   HOL_PALZ        H   HOL_MRBR        H     123  0.539047700  0.536001850
#> 1751   HOL_PALZ        H   HOL_SQUS        H     157  0.396758872  0.432349683
#> 1754   HOL_PALZ        H   HOL_TITE        H      70  0.365011577  0.429235533
#> 1755   HOL_PALZ        H  HOL_TMB11        H      58  0.036518273  0.216776370
#> 1761   HOL_PALZ        H   HOL_TRPB        H      68  0.372446788  0.529021190
#> 1762   HOL_PALZ        H   HOL_TRRB        H     187  0.195043502  0.768677386
#> 1763   HOL_PALZ        H   HOL_TRRS        H     158  0.416785660  0.624806906
#> 1765   HOL_PALZ        H   HOL_UNLU        H     189  0.256579127  0.216520771
#> 1769   HOL_SQUS        H   HOL_AAHO        H     157  0.347714888  0.364675149
#> 1771   HOL_SQUS        H   HOL_BDN2        H      60  0.218914148  0.092752129
#> 1775   HOL_SQUS        H   HOL_BRBR        H      57  0.238618861  0.204771374
#> 1781   HOL_SQUS        H   HOL_IRRB        H     157  0.299853050  0.200795430
#> 1783   HOL_SQUS        H   HOL_KBMB        H     143  0.482221485  0.406060391
#> 1786   HOL_SQUS        H   HOL_KMBQ        H     122  0.112188530  0.250932006
#> 1788   HOL_SQUS        H   HOL_KORH        H      57  0.477601912  0.331567296
#> 1790   HOL_SQUS        H   HOL_LATE        H     103  0.257036312  0.104705526
#> 1791   HOL_SQUS        H   HOL_LKBB        H      57  0.351425985  0.415145689
#> 1792   HOL_SQUS        H   HOL_LKSB        H      88  0.103289823  0.327399632
#> 1793   HOL_SQUS        H   HOL_LKSH        H     104  0.260830951  0.258130680
#> 1797   HOL_SQUS        H   HOL_MBRU        H      57  0.391808284  0.458484738
#> 1798   HOL_SQUS        H   HOL_MBUF        H     124  0.451006541  0.510205405
#> 1800   HOL_SQUS        H   HOL_MRBR        H     122  0.406418426  0.443851725
#> 1802   HOL_SQUS        H   HOL_PALZ        H     157  0.396758872  0.432349683
#> 1807   HOL_SQUS        H  HOL_TMB11        H      57  0.034766025  0.251901720
#> 1813   HOL_SQUS        H   HOL_TRPB        H      68  0.417077201  0.301546782
#> 1814   HOL_SQUS        H   HOL_TRRB        H     101  0.131502723  0.444094893
#> 1815   HOL_SQUS        H   HOL_TRRS        H     157  0.494324809  0.529997977
#> 1817   HOL_SQUS        H   HOL_UNLU        H     157  0.135298979  0.030077818
#> 1826   HOL_TATE        H   HOL_BICK        H      77  0.133636892  0.326688577
#> 1827   HOL_TATE        H   HOL_BRBR        H      60  0.230664609  0.189656344
#> 1829   HOL_TATE        H   HOL_DHRO        H     116  0.245609153  0.418843672
#> 1831   HOL_TATE        H   HOL_GKZB        H      65  0.328003333  0.223500616
#> 1832   HOL_TATE        H   HOL_GUST        H      88  0.310066749  0.305284742
#> 1834   HOL_TATE        H   HOL_K9SA        H     142  0.253814714  0.368958631
#> 1835   HOL_TATE        H   HOL_KBMB        H     134  0.263513287  0.416086104
#> 1836   HOL_TATE        H   HOL_KDGB        H      55  0.354746879  0.492059867
#> 1839   HOL_TATE        H   HOL_KORB        H     138  0.440587868  0.510714524
#> 1843   HOL_TATE        H   HOL_LKBB        H     114  0.403610102  0.461347418
#> 1844   HOL_TATE        H   HOL_LKSB        H      76  0.395525047  0.378277671
#> 1845   HOL_TATE        H   HOL_LKSH        H      72  0.241429031  0.408594403
#> 1847   HOL_TATE        H  HOL_MB253        H     178  0.106930926  0.551991160
#> 1848   HOL_TATE        H  HOL_MB259        H      84  0.183574774  0.397481879
#> 1851   HOL_TATE        H   HOL_MIWA        H     129  0.412145116  0.320113481
#> 1857   HOL_TATE        H   HOL_TATT        H      77  0.179829565  0.081321651
#> 1860   HOL_TATE        H  HOL_TMB12        H     170  0.619914326  0.703885253
#> 1861   HOL_TATE        H  HOL_TMB21        H      69  0.128988583  0.640045352
#> 1862   HOL_TATE        H  HOL_TMB22        H      82  0.439051629  0.542447674
#> 1864   HOL_TATE        H HOL_TRMB32        H     104  0.131743114  0.419491509
#> 1867   HOL_TATE        H   HOL_TRRS        H      72  0.158143461  0.432379215
#> 1868   HOL_TATE        H   HOL_TWML        H     162  0.407060207  0.361545478
#> 1870   HOL_TATE        H   HOL_WEDE        H     203  0.167580256  0.488892214
#> 1871   HOL_TATE        H   HOL_WEDG        H     105  0.136123890  0.346128904
#> 1872   HOL_TATE        H   HOL_WEDW        H     203  0.077051683  0.479001680
#> 1888   HOL_TATT        H   HOL_KDGB        H      63 -0.087559381  0.126638336
#> 1891   HOL_TATT        H   HOL_KORB        H      85  0.046435228  0.042769777
#> 1900   HOL_TATT        H  HOL_MB259        H      50  0.263201374           NA
#> 1908   HOL_TATT        H   HOL_TATE        H      77  0.179829565  0.081321651
#> 1916   HOL_TATT        H HOL_TRMB32        H      85  0.199403579  0.115082789
#> 1922   HOL_TATT        H   HOL_WEDE        H      63 -0.146651421  0.187191262
#> 1924   HOL_TATT        H   HOL_WEDW        H      63 -0.184679599  0.145794377
#> 1927   HOL_TITE        H   HOL_BDN2        H      84  0.283233492  0.338320042
#> 1945   HOL_TITE        H   HOL_LAGE        H      58  0.181761277  0.392027733
#> 1946   HOL_TITE        H   HOL_LATE        H      84  0.097782027  0.008943228
#> 1950   HOL_TITE        H   HOL_MANC        H      84  0.070299770  0.175630806
#> 1958   HOL_TITE        H   HOL_PALZ        H      70  0.365011577  0.429235533
#> 1970   HOL_TITE        H   HOL_TRRB        H      84  0.492660184  0.478859809
#> 1977  HOL_TMB11        H   HOL_AAHO        H      87  0.441421672  0.414098997
#> 1983  HOL_TMB11        H   HOL_BRBR        H      95  0.094108502  0.296739269
#> 1987  HOL_TMB11        H   HOL_GKZB        H      85  0.000173664  0.340106128
#> 1989  HOL_TMB11        H   HOL_IRRB        H      95  0.738107843  0.490500528
#> 1991  HOL_TMB11        H   HOL_KBMB        H      95  0.179775977  0.369039404
#> 1996  HOL_TMB11        H   HOL_KORH        H      85  0.447164075  0.480030045
#> 1999  HOL_TMB11        H   HOL_LKBB        H      95 -0.126528737  0.456570740
#> 2000  HOL_TMB11        H   HOL_LKSB        H      95  0.223933278  0.452640907
#> 2001  HOL_TMB11        H   HOL_LKSH        H      95  0.345407296  0.281689900
#> 2005  HOL_TMB11        H   HOL_MBRU        H      95  0.124080604  0.528106736
#> 2006  HOL_TMB11        H   HOL_MBUF        H      55  0.097614000  0.260539250
#> 2008  HOL_TMB11        H   HOL_MRBR        H      73  0.095326145  0.547150742
#> 2010  HOL_TMB11        H   HOL_PALZ        H      58  0.036518273  0.216776370
#> 2011  HOL_TMB11        H   HOL_SQUS        H      57  0.034766025  0.251901720
#> 2023  HOL_TMB11        H   HOL_TRRS        H      95  0.292290683  0.528807145
#> 2025  HOL_TMB11        H   HOL_UNLU        H      90  0.183344788  0.089926560
#> 2034  HOL_TMB12        H   HOL_BICK        H      77  0.325425741  0.335678517
#> 2035  HOL_TMB12        H   HOL_BRBR        H      54  0.127818031  0.254408087
#> 2037  HOL_TMB12        H   HOL_DHRO        H     116  0.706576038  0.599445863
#> 2039  HOL_TMB12        H   HOL_GKZB        H      59  0.206204548  0.164828147
#> 2040  HOL_TMB12        H   HOL_GUST        H      88  0.424427059  0.472487999
#> 2042  HOL_TMB12        H   HOL_K9SA        H     136  0.195051113  0.532215394
#> 2043  HOL_TMB12        H   HOL_KBMB        H     128  0.342397513  0.599927998
#> 2047  HOL_TMB12        H   HOL_KORB        H      97  0.060272067  0.476987801
#> 2051  HOL_TMB12        H   HOL_LKBB        H     108  0.544759440  0.603884425
#> 2052  HOL_TMB12        H   HOL_LKSB        H      70  0.225414032  0.489700927
#> 2053  HOL_TMB12        H   HOL_LKSH        H      66  0.402407134  0.466653142
#> 2055  HOL_TMB12        H  HOL_MB253        H     170 -0.233782014  0.649386617
#> 2056  HOL_TMB12        H  HOL_MB259        H      70  0.270162719  0.572080219
#> 2059  HOL_TMB12        H   HOL_MIWA        H     129  0.708490105  0.429404283
#> 2064  HOL_TMB12        H   HOL_TATE        H     170  0.619914326  0.703885253
#> 2069  HOL_TMB12        H  HOL_TMB21        H      69  0.588313679  0.715455439
#> 2070  HOL_TMB12        H  HOL_TMB22        H      82  0.604236100  0.711063906
#> 2072  HOL_TMB12        H HOL_TRMB32        H      63  0.209259651  0.513574696
#> 2075  HOL_TMB12        H   HOL_TRRS        H      66  0.527584405  0.665662485
#> 2076  HOL_TMB12        H   HOL_TWML        H     156  0.568477076  0.490006450
#> 2078  HOL_TMB12        H   HOL_WEDE        H     170  0.194899198  0.655967645
#> 2079  HOL_TMB12        H   HOL_WEDG        H     105  0.202818770  0.466712045
#> 2080  HOL_TMB12        H   HOL_WEDW        H     170  0.131540176  0.624961700
#> 2086  HOL_TMB21        H   HOL_BICK        H      69  0.308309538  0.249050794
#> 2087  HOL_TMB21        H   HOL_BRBR        H      54  0.141560682  0.182896209
#> 2091  HOL_TMB21        H   HOL_GKZB        H      59 -0.063652080  0.237617788
#> 2092  HOL_TMB21        H   HOL_GUST        H      69  0.125643831  0.308952578
#> 2094  HOL_TMB21        H   HOL_K9SA        H      69  0.225576266  0.360786854
#> 2095  HOL_TMB21        H   HOL_KBMB        H      69  0.472208117  0.657292845
#> 2103  HOL_TMB21        H   HOL_LKBB        H      69  0.356994329  0.436806035
#> 2104  HOL_TMB21        H   HOL_LKSB        H      69  0.223427090  0.528989194
#> 2105  HOL_TMB21        H   HOL_LKSH        H      66  0.377395037  0.500255379
#> 2107  HOL_TMB21        H  HOL_MB253        H      69  0.403444986  0.545565464
#> 2116  HOL_TMB21        H   HOL_TATE        H      69  0.128988583  0.640045352
#> 2120  HOL_TMB21        H  HOL_TMB12        H      69  0.588313679  0.715455439
#> 2122  HOL_TMB21        H  HOL_TMB22        H      69  0.243994066  0.343968275
#> 2127  HOL_TMB21        H   HOL_TRRS        H      66  0.352614484  0.407635316
#> 2128  HOL_TMB21        H   HOL_TWML        H      69  0.368805637  0.381544691
#> 2130  HOL_TMB21        H   HOL_WEDE        H      69  0.539984432  0.506665865
#> 2131  HOL_TMB21        H   HOL_WEDG        H      56  0.344013864  0.275313942
#> 2132  HOL_TMB21        H   HOL_WEDW        H      69  0.523178137  0.438412294
#> 2138  HOL_TMB22        H   HOL_BICK        H      77  0.335960060  0.179517522
#> 2139  HOL_TMB22        H   HOL_BRBR        H      54  0.621466404  0.184390902
#> 2143  HOL_TMB22        H   HOL_GKZB        H      59 -0.109329770  0.077309696
#> 2144  HOL_TMB22        H   HOL_GUST        H      82  0.679291680  0.287488012
#> 2146  HOL_TMB22        H   HOL_K9SA        H      82  0.285254051  0.510479488
#> 2147  HOL_TMB22        H   HOL_KBMB        H      82  0.310896703  0.500502472
#> 2155  HOL_TMB22        H   HOL_LKBB        H      82  0.372160586  0.421610342
#> 2156  HOL_TMB22        H   HOL_LKSB        H      70  0.492548432  0.334379418
#> 2157  HOL_TMB22        H   HOL_LKSH        H      66  0.366729580  0.295082417
#> 2159  HOL_TMB22        H  HOL_MB253        H      82  0.136354296  0.416613457
#> 2163  HOL_TMB22        H   HOL_MIWA        H      58  0.378996713  0.229551518
#> 2168  HOL_TMB22        H   HOL_TATE        H      82  0.439051629  0.542447674
#> 2172  HOL_TMB22        H  HOL_TMB12        H      82  0.604236100  0.711063906
#> 2173  HOL_TMB22        H  HOL_TMB21        H      69  0.243994066  0.343968275
#> 2179  HOL_TMB22        H   HOL_TRRS        H      66 -0.140631520  0.640876355
#> 2180  HOL_TMB22        H   HOL_TWML        H      82  0.578858208  0.333909100
#> 2182  HOL_TMB22        H   HOL_WEDE        H      82  0.401701601  0.611292452
#> 2183  HOL_TMB22        H   HOL_WEDG        H      69  0.235451889  0.288916576
#> 2184  HOL_TMB22        H   HOL_WEDW        H      82  0.332048025  0.553712120
#> 2245 HOL_TRMB32        H   HOL_DHRO        H      52  0.189234193  0.513346278
#> 2252 HOL_TRMB32        H   HOL_KDGB        H      83  0.174967773  0.450074872
#> 2255 HOL_TRMB32        H   HOL_KORB        H     133  0.454742390  0.496032610
#> 2263 HOL_TRMB32        H  HOL_MB253        H      71  0.517839579  0.675646409
#> 2264 HOL_TRMB32        H  HOL_MB259        H      77  0.529496800  0.459110314
#> 2272 HOL_TRMB32        H   HOL_TATE        H     104  0.131743114  0.419491509
#> 2273 HOL_TRMB32        H   HOL_TATT        H      85  0.199403579  0.115082789
#> 2276 HOL_TRMB32        H  HOL_TMB12        H      63  0.209259651  0.513574696
#> 2286 HOL_TRMB32        H   HOL_WEDE        H      90  0.131217727  0.568821850
#> 2288 HOL_TRMB32        H   HOL_WEDW        H      90  0.129635676  0.560523192
#> 2289   HOL_TRPB        H   HOL_AAHO        H      68  0.356284712  0.490183811
#> 2301   HOL_TRPB        H   HOL_IRRB        H      68  0.331075012  0.425255566
#> 2303   HOL_TRPB        H   HOL_KBMB        H      68  0.410963063  0.372995637
#> 2306   HOL_TRPB        H   HOL_KMBQ        H      68 -0.026148714  0.388887146
#> 2310   HOL_TRPB        H   HOL_LATE        H      68  0.259949997 -0.011459399
#> 2318   HOL_TRPB        H   HOL_MBUF        H      64  0.616201031  0.552756931
#> 2320   HOL_TRPB        H   HOL_MRBR        H      60  0.694007691  0.544136181
#> 2322   HOL_TRPB        H   HOL_PALZ        H      68  0.372446788  0.529021190
#> 2323   HOL_TRPB        H   HOL_SQUS        H      68  0.417077201  0.301546782
#> 2334   HOL_TRPB        H   HOL_TRRB        H      68  0.079866946  0.506071379
#> 2335   HOL_TRPB        H   HOL_TRRS        H      68  0.233784624  0.462847802
#> 2337   HOL_TRPB        H   HOL_UNLU        H      68 -0.287785101  0.044421369
#> 2341   HOL_TRRB        H   HOL_AAHO        H     101  0.158422177  0.533836233
#> 2343   HOL_TRRB        H   HOL_BDN2        H     276  0.252126581  0.518011876
#> 2353   HOL_TRRB        H   HOL_IRRB        H     101  0.112710306  0.501053287
#> 2355   HOL_TRRB        H   HOL_KBMB        H      87  0.107651532  0.669123266
#> 2358   HOL_TRRB        H   HOL_KMBQ        H      95  0.269473726  0.309999844
#> 2361   HOL_TRRB        H   HOL_LAGE        H      58  0.422119379  0.394990644
#> 2362   HOL_TRRB        H   HOL_LATE        H     317  0.019928936  0.061802157
#> 2366   HOL_TRRB        H   HOL_MANC        H     217  0.191327279  0.336500430
#> 2370   HOL_TRRB        H   HOL_MBUF        H      70  0.383379749  0.716668333
#> 2372   HOL_TRRB        H   HOL_MRBR        H      66  0.153066164  0.733701800
#> 2374   HOL_TRRB        H   HOL_PALZ        H     187  0.195043502  0.768677386
#> 2375   HOL_TRRB        H   HOL_SQUS        H     101  0.131502723  0.444094893
#> 2378   HOL_TRRB        H   HOL_TITE        H      84  0.492660184  0.478859809
#> 2385   HOL_TRRB        H   HOL_TRPB        H      68  0.079866946  0.506071379
#> 2387   HOL_TRRB        H   HOL_TRRS        H     101  0.147773875  0.638429609
#> 2389   HOL_TRRB        H   HOL_UNLU        H     132  0.148901656  0.168033940
#> 2393   HOL_TRRS        H   HOL_AAHO        H     187  0.332296592  0.458285337
#> 2395   HOL_TRRS        H   HOL_BDN2        H      60  0.435542796  0.176853289
#> 2398   HOL_TRRS        H   HOL_BICK        H      66  0.099903053  0.211226084
#> 2399   HOL_TRRS        H   HOL_BRBR        H     153 -0.037596570  0.314223987
#> 2403   HOL_TRRS        H   HOL_GKZB        H     148 -0.188090442  0.259036387
#> 2404   HOL_TRRS        H   HOL_GUST        H      66 -0.185446513  0.338579482
#> 2405   HOL_TRRS        H   HOL_IRRB        H     202  0.397034405  0.303430429
#> 2406   HOL_TRRS        H   HOL_K9SA        H     101  0.353085800  0.463439523
#> 2407   HOL_TRRS        H   HOL_KBMB        H     251  0.389238024  0.574039069
#> 2410   HOL_TRRS        H   HOL_KMBQ        H     122  0.128799278  0.389133386
#> 2412   HOL_TRRS        H   HOL_KORH        H      85  0.642772074  0.480783259
#> 2414   HOL_TRRS        H   HOL_LATE        H     103  0.239689088  0.032238120
#> 2415   HOL_TRRS        H   HOL_LKBB        H     165 -0.089227628  0.513661005
#> 2416   HOL_TRRS        H   HOL_LKSB        H     196 -0.053779651  0.461660810
#> 2417   HOL_TRRS        H   HOL_LKSH        H     212  0.088249244  0.415316109
#> 2419   HOL_TRRS        H  HOL_MB253        H      66  0.643374022  0.556914738
#> 2421   HOL_TRRS        H   HOL_MBRU        H     100  0.460348649  0.584573346
#> 2422   HOL_TRRS        H   HOL_MBUF        H     124  0.446763833  0.670593303
#> 2424   HOL_TRRS        H   HOL_MRBR        H     138  0.377208429  0.624626688
#> 2426   HOL_TRRS        H   HOL_PALZ        H     158  0.416785660  0.624806906
#> 2427   HOL_TRRS        H   HOL_SQUS        H     157  0.494324809  0.529997977
#> 2428   HOL_TRRS        H   HOL_TATE        H      72  0.158143461  0.432379215
#> 2431   HOL_TRRS        H  HOL_TMB11        H      95  0.292290683  0.528807145
#> 2432   HOL_TRRS        H  HOL_TMB12        H      66  0.527584405  0.665662485
#> 2433   HOL_TRRS        H  HOL_TMB21        H      66  0.352614484  0.407635316
#> 2434   HOL_TRRS        H  HOL_TMB22        H      66 -0.140631520  0.640876355
#> 2437   HOL_TRRS        H   HOL_TRPB        H      68  0.233784624  0.462847802
#> 2438   HOL_TRRS        H   HOL_TRRB        H     101  0.147773875  0.638429609
#> 2440   HOL_TRRS        H   HOL_TWML        H     110 -0.105790202  0.444866315
#> 2441   HOL_TRRS        H   HOL_UNLU        H     190  0.188200834  0.214330284
#> 2442   HOL_TRRS        H   HOL_WEDE        H      76  0.402791132  0.435415383
#> 2443   HOL_TRRS        H   HOL_WEDG        H      53  0.474964442  0.258843606
#> 2444   HOL_TRRS        H   HOL_WEDW        H      76  0.427268723  0.359800846
#> 2450   HOL_TWML        H   HOL_BICK        H      77  0.330742957  0.319830826
#> 2451   HOL_TWML        H   HOL_BRBR        H      98  0.488033063  0.189688375
#> 2453   HOL_TWML        H   HOL_DHRO        H     113  0.301798507  0.323127643
#> 2455   HOL_TWML        H   HOL_GKZB        H     103  0.183764564  0.242532939
#> 2456   HOL_TWML        H   HOL_GUST        H      88  0.492230094  0.303859893
#> 2458   HOL_TWML        H   HOL_K9SA        H     171  0.158939070  0.428712893
#> 2459   HOL_TWML        H   HOL_KBMB        H     172  0.015844598  0.232887482
#> 2463   HOL_TWML        H   HOL_KORB        H      83  0.171363922  0.387056412
#> 2467   HOL_TWML        H   HOL_LKBB        H     152  0.566824381  0.312159966
#> 2468   HOL_TWML        H   HOL_LKSB        H     114  0.509604090  0.371210304
#> 2469   HOL_TWML        H   HOL_LKSH        H     110  0.420838212  0.200631160
#> 2471   HOL_TWML        H  HOL_MB253        H     156 -0.146541730  0.365020421
#> 2472   HOL_TWML        H  HOL_MB259        H      56  0.024214611  0.517503480
#> 2475   HOL_TWML        H   HOL_MIWA        H     129  0.281844726  0.221487629
#> 2480   HOL_TWML        H   HOL_TATE        H     162  0.407060207  0.361545478
#> 2484   HOL_TWML        H  HOL_TMB12        H     156  0.568477076  0.490006450
#> 2485   HOL_TWML        H  HOL_TMB21        H      69  0.368805637  0.381544691
#> 2486   HOL_TWML        H  HOL_TMB22        H      82  0.578858208  0.333909100
#> 2491   HOL_TWML        H   HOL_TRRS        H     110 -0.105790202  0.444866315
#> 2494   HOL_TWML        H   HOL_WEDE        H     166  0.197003573  0.334921921
#> 2495   HOL_TWML        H   HOL_WEDG        H     105  0.226324375  0.131401013
#> 2496   HOL_TWML        H   HOL_WEDW        H     166  0.113962643  0.284310730
#> 2497   HOL_UNLU        H   HOL_AAHO        H     187 -0.031712669  0.064022899
#> 2499   HOL_UNLU        H   HOL_BDN2        H      91  0.064324801  0.242647987
#> 2503   HOL_UNLU        H   HOL_BRBR        H      90  0.234093805  0.107941312
#> 2507   HOL_UNLU        H   HOL_GKZB        H      80  0.086962224  0.054221366
#> 2509   HOL_UNLU        H   HOL_IRRB        H     190  0.141304936  0.152727979
#> 2511   HOL_UNLU        H   HOL_KBMB        H     176  0.360137445  0.271504589
#> 2514   HOL_UNLU        H   HOL_KMBQ        H     122  0.217656631  0.180615553
#> 2516   HOL_UNLU        H   HOL_KORH        H      85  0.120928149 -0.087497523
#> 2518   HOL_UNLU        H   HOL_LATE        H     134 -0.033085444 -0.025515608
#> 2519   HOL_UNLU        H   HOL_LKBB        H      90  0.114272999  0.144795007
#> 2520   HOL_UNLU        H   HOL_LKSB        H     121  0.114516712  0.150898944
#> 2521   HOL_UNLU        H   HOL_LKSH        H     137  0.320611330  0.141760093
#> 2525   HOL_UNLU        H   HOL_MBRU        H      90  0.176705007  0.138971604
#> 2526   HOL_UNLU        H   HOL_MBUF        H     124  0.305811681  0.240252770
#> 2528   HOL_UNLU        H   HOL_MRBR        H     138 -0.110182054  0.109825237
#> 2530   HOL_UNLU        H   HOL_PALZ        H     189  0.256579127  0.216520771
#> 2531   HOL_UNLU        H   HOL_SQUS        H     157  0.135298979  0.030077818
#> 2535   HOL_UNLU        H  HOL_TMB11        H      90  0.183344788  0.089926560
#> 2541   HOL_UNLU        H   HOL_TRPB        H      68 -0.287785101  0.044421369
#> 2542   HOL_UNLU        H   HOL_TRRB        H     132  0.148901656  0.168033940
#> 2543   HOL_UNLU        H   HOL_TRRS        H     190  0.188200834  0.214330284
#> 2554   HOL_WEDE        H   HOL_BICK        H      77  0.334837187  0.220952568
#> 2555   HOL_WEDE        H   HOL_BRBR        H      64  0.274358628  0.258833452
#> 2557   HOL_WEDE        H   HOL_DHRO        H     116  0.386904490  0.516880163
#> 2559   HOL_WEDE        H   HOL_GKZB        H      69  0.156149106  0.240202586
#> 2560   HOL_WEDE        H   HOL_GUST        H      88  0.181442734  0.147711923
#> 2562   HOL_WEDE        H   HOL_K9SA        H     146  0.216597331  0.403352862
#> 2563   HOL_WEDE        H   HOL_KBMB        H     138  0.452358388  0.500901295
#> 2567   HOL_WEDE        H   HOL_KORB        H     124  0.253383305  0.405401632
#> 2571   HOL_WEDE        H   HOL_LKBB        H     118  0.347653246  0.485822075
#> 2572   HOL_WEDE        H   HOL_LKSB        H      80  0.264211526  0.426866051
#> 2573   HOL_WEDE        H   HOL_LKSH        H      76  0.218206049  0.284314989
#> 2575   HOL_WEDE        H  HOL_MB253        H     178  0.459390150  0.530474537
#> 2576   HOL_WEDE        H  HOL_MB259        H      84  0.151884006  0.569579263
#> 2579   HOL_WEDE        H   HOL_MIWA        H     129  0.070142752  0.495090767
#> 2584   HOL_WEDE        H   HOL_TATE        H     203  0.167580256  0.488892214
#> 2585   HOL_WEDE        H   HOL_TATT        H      63 -0.146651421  0.187191262
#> 2588   HOL_WEDE        H  HOL_TMB12        H     170  0.194899198  0.655967645
#> 2589   HOL_WEDE        H  HOL_TMB21        H      69  0.539984432  0.506665865
#> 2590   HOL_WEDE        H  HOL_TMB22        H      82  0.401701601  0.611292452
#> 2592   HOL_WEDE        H HOL_TRMB32        H      90  0.131217727  0.568821850
#> 2595   HOL_WEDE        H   HOL_TRRS        H      76  0.402791132  0.435415383
#> 2596   HOL_WEDE        H   HOL_TWML        H     166  0.197003573  0.334921921
#> 2599   HOL_WEDE        H   HOL_WEDG        H     105  0.523920912  0.440305026
#> 2600   HOL_WEDE        H   HOL_WEDW        H     207  0.978905719  0.968930120
#> 2606   HOL_WEDG        H   HOL_BICK        H      64  0.327289636 -0.116183942
#> 2609   HOL_WEDG        H   HOL_DHRO        H      75  0.620845102  0.583970783
#> 2612   HOL_WEDG        H   HOL_GUST        H      75  0.114871224  0.251548967
#> 2614   HOL_WEDG        H   HOL_K9SA        H     105  0.002461062  0.347195026
#> 2615   HOL_WEDG        H   HOL_KBMB        H     105  0.186686657  0.322246064
#> 2623   HOL_WEDG        H   HOL_LKBB        H      95  0.341031432  0.407961750
#> 2624   HOL_WEDG        H   HOL_LKSB        H      57  0.037667612  0.173995168
#> 2625   HOL_WEDG        H   HOL_LKSH        H      53  0.170916909  0.297401147
#> 2627   HOL_WEDG        H  HOL_MB253        H     105  0.270299737  0.374831539
#> 2631   HOL_WEDG        H   HOL_MIWA        H      94  0.016502954  0.460010471
#> 2636   HOL_WEDG        H   HOL_TATE        H     105  0.136123890  0.346128904
#> 2640   HOL_WEDG        H  HOL_TMB12        H     105  0.202818770  0.466712045
#> 2641   HOL_WEDG        H  HOL_TMB21        H      56  0.344013864  0.275313942
#> 2642   HOL_WEDG        H  HOL_TMB22        H      69  0.235451889  0.288916576
#> 2647   HOL_WEDG        H   HOL_TRRS        H      53  0.474964442  0.258843606
#> 2648   HOL_WEDG        H   HOL_TWML        H     105  0.226324375  0.131401013
#> 2650   HOL_WEDG        H   HOL_WEDE        H     105  0.523920912  0.440305026
#> 2652   HOL_WEDG        H   HOL_WEDW        H     105  0.534250550  0.458507159
#> 2658   HOL_WEDW        H   HOL_BICK        H      77  0.308287116  0.173699858
#> 2659   HOL_WEDW        H   HOL_BRBR        H      64  0.225918357  0.241293227
#> 2661   HOL_WEDW        H   HOL_DHRO        H     116  0.394374162  0.519431179
#> 2663   HOL_WEDW        H   HOL_GKZB        H      69  0.123656717  0.218464883
#> 2664   HOL_WEDW        H   HOL_GUST        H      88  0.112537983  0.078855364
#> 2666   HOL_WEDW        H   HOL_K9SA        H     146  0.194764476  0.380558863
#> 2667   HOL_WEDW        H   HOL_KBMB        H     138  0.430539452  0.438924058
#> 2671   HOL_WEDW        H   HOL_KORB        H     124  0.225610729  0.415516720
#> 2675   HOL_WEDW        H   HOL_LKBB        H     118  0.265138039  0.467384322
#> 2676   HOL_WEDW        H   HOL_LKSB        H      80  0.168797282  0.389698539
#> 2677   HOL_WEDW        H   HOL_LKSH        H      76  0.196719235  0.282650191
#> 2679   HOL_WEDW        H  HOL_MB253        H     178  0.475733073  0.497914415
#> 2680   HOL_WEDW        H  HOL_MB259        H      84  0.162768833  0.557212425
#> 2683   HOL_WEDW        H   HOL_MIWA        H     129  0.030091643  0.477594560
#> 2688   HOL_WEDW        H   HOL_TATE        H     203  0.077051683  0.479001680
#> 2689   HOL_WEDW        H   HOL_TATT        H      63 -0.184679599  0.145794377
#> 2692   HOL_WEDW        H  HOL_TMB12        H     170  0.131540176  0.624961700
#> 2693   HOL_WEDW        H  HOL_TMB21        H      69  0.523178137  0.438412294
#> 2694   HOL_WEDW        H  HOL_TMB22        H      82  0.332048025  0.553712120
#> 2696   HOL_WEDW        H HOL_TRMB32        H      90  0.129635676  0.560523192
#> 2699   HOL_WEDW        H   HOL_TRRS        H      76  0.427268723  0.359800846
#> 2700   HOL_WEDW        H   HOL_TWML        H     166  0.113962643  0.284310730
#> 2702   HOL_WEDW        H   HOL_WEDE        H     207  0.978905719  0.968930120
#> 2703   HOL_WEDW        H   HOL_WEDG        H     105  0.534250550  0.458507159
#>                 t       t_hol       sgc       ssgc            p
#> 3     1.473570629  3.78461454 0.6610169 0.03389831 1.337634e-02
#> 7    -0.857046488  2.30966394 0.5697674 0.04651163 1.956677e-01
#> 11    1.208635328  2.50828143 0.5657895 0.05263158 2.513491e-01
#> 13    7.740412083  5.82196912 0.5913978 0.04838710 1.266685e-02
#> 15    4.059485995  5.95643279 0.6046512 0.04651163 6.051564e-03
#> 18    3.730301947  8.03865634 0.7520661 0.06611570 2.931915e-08
#> 20    0.463987099  2.74691328 0.5476190 0.03571429 3.827331e-01
#> 22    3.158942695  2.06726998 0.5392157 0.03921569 4.282919e-01
#> 23    0.223093191  3.19224325 0.5581395 0.03488372 2.808875e-01
#> 24    3.429981790  6.19671953 0.6239316 0.03418803 7.339134e-03
#> 25    4.612151513  2.89925600 0.5338346 0.03759398 4.351561e-01
#> 29    0.606946798  4.77429753 0.6162791 0.05813953 3.103252e-02
#> 30    5.573291986  6.23943859 0.7073171 0.03252033 4.255128e-06
#> 32    3.732253762  7.86749352 0.6642336 0.05839416 1.207446e-04
#> 34    4.032345115  5.79740652 0.6369427 0.03184713 5.996479e-04
#> 35    4.631992406  4.87595238 0.6089744 0.05128205 6.485308e-03
#> 39    4.562105380  4.19432051 0.6279070 0.04651163 1.767673e-02
#> 45    3.121132771  4.56882160 0.6417910 0.04477612 2.027500e-02
#> 46    1.604484047  6.28155102 0.7000000 0.04000000 6.334248e-05
#> 47    4.804963625  7.01318469 0.6559140 0.05376344 2.111459e-05
#> 49   -0.432720785  0.87259576 0.5322581 0.04301075 3.789229e-01
#> 105   1.473570629  3.78461454 0.6610169 0.03389831 1.337634e-02
#> 117   5.483953185  5.65616643 0.6949153 0.01694915 2.750348e-03
#> 122   1.021193475  1.57587655 0.6226415 0.01886792 7.414990e-02
#> 125   3.634572700  2.71847842 0.6491228 0.05263158 2.434092e-02
#> 126   9.751630705  1.46530832 0.4830769 0.03692308 1.458251e+00
#> 130   1.840431010  3.31077605 0.5377778 0.02666667 2.570743e-01
#> 138   1.543691654  5.38463941 0.6275862 0.01379310 2.121439e-03
#> 139   1.723311918  0.70943739 0.5084746 0.05084746 8.964170e-01
#> 142   2.690555518  3.25559723 0.5542169 0.02409639 3.232122e-01
#> 150   4.320627392 10.02441978 0.6327273 0.05090909 1.072251e-05
#> 151   3.716492486  1.36844501 0.5254237 0.03389831 6.961175e-01
#> 153   0.611505061  2.35965627 0.6000000 0.00000000 5.777957e-02
#> 161   2.429614840  1.42889764 0.6379310 0.01724138 3.564949e-02
#> 164   4.624919424  2.30485004 0.5441176 0.08823529 4.668543e-01
#> 173   2.424915353  1.89724941 0.6911765 0.02941176 1.616222e-03
#> 175   7.021106644  2.59891146 0.6451613 0.00000000 2.225412e-02
#> 212   2.429614840  1.42889764 0.6379310 0.01724138 3.564949e-02
#> 216  15.343970174  2.65170649 0.5388128 0.08219178 2.506576e-01
#> 218   4.838345011  0.48059910 0.4456522 0.08695652 1.702853e+00
#> 225  12.845725876  4.80992577 0.6255507 0.06167401 1.548107e-04
#> 227   5.505442498  1.29998293 0.5192308 0.00000000 7.815113e-01
#> 241   6.892528861  1.82161324 0.4765101 0.10067114 1.433668e+00
#> 267   3.887048085  1.86771223 0.4716981 0.05660377 1.319720e+00
#> 271   0.295507924  3.75623663 0.6034483 0.10344828 1.151002e-01
#> 272   3.712454943  3.74969864 0.6052632 0.01315789 6.645742e-02
#> 274  -0.691761992  0.82720045 0.6052632 0.01315789 6.645742e-02
#> 275   1.827093086  2.68068371 0.6315789 0.00000000 2.178146e-02
#> 283   4.905628195  3.10524264 0.6052632 0.02631579 6.645742e-02
#> 284   1.560454341  1.53881908 0.5072464 0.04347826 9.041775e-01
#> 285   1.298769679  1.16559774 0.5384615 0.00000000 5.351435e-01
#> 287   3.442555185  2.75741594 0.6447368 0.02631579 1.161689e-02
#> 291   0.194280644  0.75308613 0.5769231 0.00000000 2.672575e-01
#> 296   1.175563790  2.99345060 0.5921053 0.01315789 1.082937e-01
#> 300   3.000309909  3.08612890 0.5921053 0.02631579 1.082937e-01
#> 301   2.672577261  2.10489289 0.5441176 0.02941176 4.668543e-01
#> 302   3.109571940  1.58034033 0.5921053 0.02631579 1.082937e-01
#> 307   0.809493917  1.72881554 0.6000000 0.00000000 1.068637e-01
#> 308   3.055299845  2.92336703 0.6842105 0.02631579 1.318969e-03
#> 310   3.097864025  1.96199700 0.5789474 0.00000000 1.686686e-01
#> 311   2.749195457 -0.92107103 0.5396825 0.03174603 5.287333e-01
#> 312   2.825190294  1.52750505 0.5657895 0.00000000 2.513491e-01
#> 313  -0.857046488  2.30966394 0.5697674 0.04651163 1.956677e-01
#> 318   3.887048085  1.86771223 0.4716981 0.05660377 1.319720e+00
#> 323   3.808558446  3.95891351 0.5492958 0.07042254 2.400532e-01
#> 324   4.876952521  1.48057699 0.4339623 0.07547170 1.663711e+00
#> 325   1.245845442  1.16340370 0.5148515 0.02970297 7.653131e-01
#> 326  -0.308342079  1.86272118 0.5681818 0.04545455 2.008251e-01
#> 327  -0.586691758  2.81337721 0.5460526 0.04605263 2.561450e-01
#> 332   3.907376443  1.84196442 0.5833333 0.01190476 1.266305e-01
#> 335   7.391865616  5.54335130 0.6118421 0.03289474 5.819817e-03
#> 336   8.277593492  4.26055439 0.6250000 0.04605263 2.054719e-03
#> 337   7.924727054  2.91566650 0.5723684 0.04605263 7.435291e-02
#> 339   2.501634983  0.79597722 0.4905660 0.07547170 1.109254e+00
#> 341   2.988058682  2.81031788 0.5757576 0.03030303 1.316680e-01
#> 342   3.004122017  3.12518114 0.5740741 0.03703704 2.763029e-01
#> 344   2.659605495  2.42096130 0.5694444 0.04166667 2.385928e-01
#> 346   3.116880179  0.57397454 0.4912281 0.01754386 1.105374e+00
#> 347   1.838776227  1.55150174 0.6250000 0.01785714 6.136883e-02
#> 348   1.820871338  1.47107898 0.5254237 0.06779661 6.961175e-01
#> 351   0.916483180  2.99662212 0.6063830 0.03191489 3.912760e-02
#> 352   0.938224974  1.89697919 0.5660377 0.03773585 3.362888e-01
#> 353   1.041061243  1.34151163 0.4716981 0.07547170 1.319720e+00
#> 354   5.774965560  1.35285919 0.4905660 0.09433962 1.109254e+00
#> 359  -0.463849589  4.06726031 0.6118421 0.04605263 5.819817e-03
#> 360   5.506908557  1.89292623 0.6288660 0.06185567 1.113716e-02
#> 361   2.271553900  1.01853026 0.4382022 0.03370787 1.756385e+00
#> 362   2.264550695  2.10995993 0.6190476 0.04761905 5.878172e-02
#> 364   1.840761985  1.95779314 0.6031746 0.04761905 1.014538e-01
#> 368   4.624919424  2.30485004 0.5441176 0.08823529 4.668543e-01
#> 369  15.343970174  2.65170649 0.5388128 0.08219178 2.506576e-01
#> 374   5.294380935 -1.08153866 0.4130435 0.04347826 1.904707e+00
#> 381  16.156406698  4.91884435 0.5826087 0.06086957 1.222280e-02
#> 383   8.999587148  3.96049640 0.5797101 0.07246377 1.854219e-01
#> 397   2.860184764  0.11097661 0.5098039 0.04901961 8.430220e-01
#> 430  -0.252666963  4.61442952 0.6630435 0.03260870 1.761702e-03
#> 431   3.657298386  5.16997366 0.6547619 0.04761905 4.556350e-03
#> 435   0.737972961  2.42439291 0.5647059 0.03529412 2.328234e-01
#> 439   5.379102857  5.07928700 0.5468750 0.07812500 4.532547e-01
#> 443  -0.914678896  6.64646762 0.6000000 0.05217391 3.197196e-02
#> 444   2.295134768  3.82436744 0.6896552 0.05172414 3.867869e-03
#> 447   7.221878507  5.13638087 0.5963303 0.06422018 4.427951e-02
#> 452   2.717092141  4.92482298 0.5565217 0.03478261 2.254143e-01
#> 456  10.707725167  7.99626189 0.5565217 0.09565217 2.254143e-01
#> 460   1.376268897  4.22976500 0.6666667 0.05882353 1.729028e-02
#> 464   3.350146719  3.59733880 0.6339286 0.06250000 4.586392e-03
#> 466   4.499511282  6.44672611 0.6521739 0.04347826 1.099416e-03
#> 467   6.812711955  6.14634665 0.5945946 0.04054054 1.036380e-01
#> 468   4.602200268  6.49026050 0.6434783 0.04347826 2.089089e-03
#> 473   4.838345011  0.48059910 0.4456522 0.08695652 1.702853e+00
#> 476   5.294380935 -1.08153866 0.4130435 0.04347826 1.904707e+00
#> 485   1.489921700 -0.24445426 0.4673913 0.05434783 1.468385e+00
#> 501   5.923983276  2.08136273 0.4725275 0.05494505 1.399821e+00
#> 521   1.208635328  2.50828143 0.5657895 0.05263158 2.513491e-01
#> 526   0.295507924  3.75623663 0.6034483 0.10344828 1.151002e-01
#> 527   3.808558446  3.95891351 0.5492958 0.07042254 2.400532e-01
#> 532   0.433880442  4.00196380 0.5344828 0.12068966 5.994263e-01
#> 533   0.437705578  3.16297812 0.6593407 0.02197802 2.365577e-03
#> 534  -0.130327531 -0.36241090 0.4946237 0.05376344 1.082589e+00
#> 535   0.053406940  3.87703068 0.5918367 0.06802721 2.595246e-02
#> 540   0.130136657  5.48045426 0.7567568 0.01351351 9.989052e-06
#> 543   8.926672777  5.05001502 0.6054422 0.05442177 1.056287e-02
#> 544   8.993743674  4.79893676 0.6190476 0.06802721 3.892417e-03
#> 545   3.549125713  2.09469438 0.5102041 0.06802721 8.045709e-01
#> 547   0.713719034  1.31148877 0.5344828 0.12068966 5.994263e-01
#> 549   3.048705508  5.51878806 0.6516854 0.03370787 4.209845e-03
#> 552   2.552478026  4.45880423 0.6612903 0.06451613 1.108517e-02
#> 556   2.777698486  1.82002078 0.5312500 0.10937500 6.170751e-01
#> 559   0.001591657  3.29493506 0.5595238 0.03571429 2.752335e-01
#> 560   1.604898066  1.26168213 0.5862069 0.12068966 1.891613e-01
#> 561  -0.485744818  1.84687170 0.5689655 0.13793103 2.935106e-01
#> 562  -0.837652001  0.58542752 0.5000000 0.13793103 1.000000e+00
#> 567  -2.321917665  3.24055667 0.5986395 0.06802721 1.676234e-02
#> 568   1.888084658  2.51243934 0.6274510 0.07843137 1.004189e-02
#> 569   0.775876473  0.47957563 0.4683544 0.03797468 1.426255e+00
#> 570   1.303629490  2.02544221 0.6029412 0.08823529 8.955507e-02
#> 572   1.027586074  1.83247594 0.5882353 0.08823529 1.456101e-01
#> 578   3.712454943  3.74969864 0.6052632 0.01315789 6.645742e-02
#> 579   4.876952521  1.48057699 0.4339623 0.07547170 1.663711e+00
#> 583   0.433880442  4.00196380 0.5344828 0.12068966 5.994263e-01
#> 586   1.370246981  2.18842902 0.5287356 0.03448276 5.919197e-01
#> 587   2.366084114  3.68698591 0.5862069 0.02298851 1.077982e-01
#> 595   4.336452319  4.00484984 0.5517241 0.04597701 3.345943e-01
#> 596   3.496336630  2.38640296 0.5362319 0.05797101 5.472212e-01
#> 597   1.888447034  1.67679668 0.4461538 0.01538462 1.614739e+00
#> 599   1.861111225  6.15012923 0.6781609 0.05747126 8.887985e-04
#> 603   4.416587185  1.70141854 0.5555556 0.03174603 3.778216e-01
#> 608   3.042037561  2.97302305 0.5287356 0.03448276 5.919197e-01
#> 612   4.372123277  4.97162031 0.5287356 0.05747126 5.919197e-01
#> 613   1.044361703  2.65896942 0.5000000 0.04411765 1.000000e+00
#> 614   8.330683272  2.68470795 0.5925926 0.03703704 9.558070e-02
#> 619  -1.521509137  2.87865561 0.5384615 0.01538462 5.351435e-01
#> 620   5.274440684  2.95773197 0.5057471 0.04597701 9.146214e-01
#> 622   1.720950333  1.38501707 0.5057471 0.02298851 9.146214e-01
#> 623   0.994744452  2.22064098 0.5675676 0.05405405 2.450420e-01
#> 624   1.056395260  0.73355882 0.5172414 0.02298851 7.477302e-01
#> 625   7.740412083  5.82196912 0.5913978 0.04838710 1.266685e-02
#> 627   5.483953185  5.65616643 0.6949153 0.01694915 2.750348e-03
#> 631   1.245845442  1.16340370 0.5148515 0.02970297 7.653131e-01
#> 635   0.437705578  3.16297812 0.6593407 0.02197802 2.365577e-03
#> 639   7.773601527  4.46732036 0.6042781 0.04278075 4.345023e-03
#> 642   1.627042373  2.42608350 0.6198347 0.06611570 8.379987e-03
#> 644   3.599773806  2.91564321 0.6428571 0.02380952 8.828761e-03
#> 646   6.079967095  2.01908631 0.5490196 0.04901961 3.221020e-01
#> 647  -1.729032576  2.54085805 0.6633663 0.01980198 1.024820e-03
#> 648   3.894794371  4.72205843 0.6590909 0.03787879 2.565504e-04
#> 649   2.864317891  2.43025790 0.5405405 0.04054054 3.239398e-01
#> 653   0.377582455  2.47668430 0.6060606 0.04040404 3.480848e-02
#> 654   6.313854145  4.93486656 0.6422764 0.04065041 1.600346e-03
#> 656   2.958218315  4.37525776 0.6569343 0.06569343 2.390279e-04
#> 658   9.146287992  5.59216119 0.6114650 0.03184713 5.217262e-03
#> 659   3.925807862  2.55185611 0.5384615 0.05128205 3.366684e-01
#> 663  10.606794165  5.42803973 0.7127660 0.04255319 3.696329e-05
#> 669   2.871929864  3.81714110 0.6119403 0.04477612 6.687076e-02
#> 670   1.134331145  5.76071481 0.6700000 0.06000000 6.738585e-04
#> 671   6.133047854  4.50347702 0.6169154 0.04477612 9.160235e-04
#> 673   1.962311295  2.11895961 0.5343915 0.03703704 3.443471e-01
#> 682  -0.691761992  0.82720045 0.6052632 0.01315789 6.645742e-02
#> 683  -0.308342079  1.86272118 0.5681818 0.04545455 2.008251e-01
#> 685  -0.252666963  4.61442952 0.6630435 0.03260870 1.761702e-03
#> 687  -0.130327531 -0.36241090 0.4946237 0.05376344 1.082589e+00
#> 688   1.370246981  2.18842902 0.5287356 0.03448276 5.919197e-01
#> 691   3.617563123  4.48709964 0.5740741 0.03086420 5.934644e-02
#> 695   4.556141312  4.01546036 0.6612903 0.03225806 1.108517e-02
#> 699   3.580854565  2.96978254 0.5915493 0.04225352 2.911902e-02
#> 700   1.522241086  3.73088261 0.6057692 0.04807692 3.098405e-02
#> 701   1.397559087  1.23565226 0.5400000 0.03000000 4.237108e-01
#> 703   4.762990275  6.05108234 0.6222222 0.03703704 4.508698e-03
#> 707   2.640462989  3.92118181 0.5945946 0.04504505 4.623607e-02
#> 712   3.115920222  4.69696814 0.6028369 0.02127660 1.459642e-02
#> 716   2.310669995  7.27707678 0.6074074 0.06666667 1.256300e-02
#> 717   1.909362385  3.16643228 0.5441176 0.04411765 4.668543e-01
#> 718   2.678576088  5.30982767 0.7160494 0.03703704 1.007042e-04
#> 723   3.773933482  5.20372019 0.6200000 0.01000000 1.639507e-02
#> 724   2.098993510  6.16893514 0.6411765 0.03529412 2.319277e-04
#> 726   2.671598235  5.28961625 0.6413793 0.02068966 6.619685e-04
#> 727   0.025098086  3.75738021 0.5769231 0.03846154 1.166645e-01
#> 728   2.391063634  4.93827875 0.6275862 0.02068966 2.121439e-03
#> 729   4.059485995  5.95643279 0.6046512 0.04651163 6.051564e-03
#> 734   1.827093086  2.68068371 0.6315789 0.00000000 2.178146e-02
#> 735  -0.586691758  2.81337721 0.5460526 0.04605263 2.561450e-01
#> 737   3.657298386  5.16997366 0.6547619 0.04761905 4.556350e-03
#> 739   0.053406940  3.87703068 0.5918367 0.06802721 2.595246e-02
#> 740   2.366084114  3.68698591 0.5862069 0.02298851 1.077982e-01
#> 741   7.773601527  4.46732036 0.6042781 0.04278075 4.345023e-03
#> 742   3.617563123  4.48709964 0.5740741 0.03086420 5.934644e-02
#> 746   2.052959125  4.29650938 0.6017699 0.05309735 3.049061e-02
#> 747   2.879422987  2.49914563 0.5925926 0.03703704 1.735682e-01
#> 748   5.802515582  4.28966940 0.6071429 0.02380952 4.953461e-02
#> 750   6.461612115  1.83983900 0.5340909 0.02272727 5.224313e-01
#> 751   0.697038886  9.77819860 0.6796117 0.03398058 2.525176e-07
#> 752   2.968001365  8.46160296 0.6582915 0.03015075 7.971363e-06
#> 753   2.842660812  7.63163726 0.6303318 0.02843602 1.528725e-04
#> 755   1.807815698  5.75094395 0.6614173 0.03149606 2.745910e-04
#> 757   6.288346597  7.29524881 0.6767677 0.05050505 4.354152e-04
#> 758  11.618345264  9.12366726 0.7235772 0.02439024 7.079026e-07
#> 759   3.444185260  3.83440260 0.6310680 0.03883495 7.805044e-03
#> 760   8.879194304  8.18953660 0.6861314 0.05109489 1.317224e-05
#> 762  11.202984249  6.65972704 0.6293706 0.02797203 1.974140e-03
#> 763   6.559370513  5.27627051 0.6267606 0.04225352 2.518974e-03
#> 764   3.150329454  5.25715694 0.6090226 0.01503759 1.191611e-02
#> 767   1.771860672  3.82917418 0.5851064 0.05319149 9.888691e-02
#> 768   4.106862565  8.41715072 0.6535433 0.06299213 5.387921e-04
#> 769   4.417453099  7.13896237 0.6029412 0.02941176 8.955507e-02
#> 770   2.943962182  5.17090062 0.6419753 0.02469136 1.060184e-02
#> 773   3.689870330  3.26592239 0.6268657 0.01492537 3.781258e-02
#> 774   1.004154697  8.30115022 0.7674419 0.04651163 7.038165e-07
#> 775   6.681299456 11.06237782 0.6720000 0.03200000 5.354511e-08
#> 776   0.207221017  3.12233393 0.5438596 0.04093567 2.513491e-01
#> 777   5.106843594  3.72116924 0.6228571 0.04000000 1.152045e-03
#> 778   5.936873740  6.74920035 0.7153285 0.01459854 4.638074e-07
#> 779   1.937907171  3.45472966 0.6730769 0.01923077 4.154176e-04
#> 780   5.583306851  5.69677517 0.7153285 0.01459854 4.638074e-07
#> 799   1.993599753  4.89818219 0.6341463 0.01219512 1.511993e-02
#> 816   2.788183335  4.11487352 0.6666667 0.00000000 1.430588e-02
#> 817  -0.692101411  0.99710476 0.5161290 0.06451613 7.994954e-01
#> 824   1.609224207  4.53607556 0.6219512 0.03658537 2.720035e-02
#> 836   2.424915353  1.89724941 0.6911765 0.02941176 1.616222e-03
#> 837  12.845725876  4.80992577 0.6255507 0.06167401 1.548107e-04
#> 840  16.156406698  4.91884435 0.5826087 0.06086957 1.222280e-02
#> 842   1.489921700 -0.24445426 0.4673913 0.05434783 1.468385e+00
#> 851   2.924990856  3.86654627 0.6190476 0.01587302 5.878172e-02
#> 865   3.372213963  0.44355997 0.4909091 0.04545455 1.151233e+00
#> 885   3.730301947  8.03865634 0.7520661 0.06611570 2.931915e-08
#> 887   1.021193475  1.57587655 0.6226415 0.01886792 7.414990e-02
#> 897   1.627042373  2.42608350 0.6198347 0.06611570 8.379987e-03
#> 899   2.052959125  4.29650938 0.6017699 0.05309735 3.049061e-02
#> 906   0.236308507  1.29540364 0.5104167 0.04166667 8.382565e-01
#> 908   0.417701143  3.08016101 0.5689655 0.08620690 2.935106e-01
#> 909   4.230089507  4.06637381 0.6216216 0.05405405 3.639761e-02
#> 914   2.537601166  5.59267905 0.6770833 0.05208333 5.202443e-04
#> 916  -0.318130597  4.62048927 0.6195652 0.07608696 2.181012e-02
#> 918   2.398401357  3.86295977 0.5537190 0.04958678 2.372779e-01
#> 919   1.241914109  2.83967873 0.5702479 0.07438017 1.222364e-01
#> 929  -0.214109657  3.42926753 0.5522388 0.04477612 3.924481e-01
#> 930   2.713004881  3.14443581 0.6276596 0.06382979 1.330829e-02
#> 931   1.428692088  4.62747357 0.6611570 0.04958678 3.919366e-04
#> 933   2.453033421  2.01162795 0.5123967 0.04958678 7.850629e-01
#> 940   7.021106644  2.59891146 0.6451613 0.00000000 2.225412e-02
#> 941   5.505442498  1.29998293 0.5192308 0.00000000 7.815113e-01
#> 944   8.999587148  3.96049640 0.5797101 0.07246377 1.854219e-01
#> 945   0.737972961  2.42439291 0.5647059 0.03529412 2.328234e-01
#> 950   4.556141312  4.01546036 0.6612903 0.03225806 1.108517e-02
#> 951   2.879422987  2.49914563 0.5925926 0.03703704 1.735682e-01
#> 952   1.993599753  4.89818219 0.6341463 0.01219512 1.511993e-02
#> 953   2.924990856  3.86654627 0.6190476 0.01587302 5.878172e-02
#> 963   7.507244970  7.82593561 0.7019231 0.02884615 3.814478e-05
#> 964   5.125552038  4.11736405 0.6867470 0.02409639 6.672544e-04
#> 967   0.904238057  2.62363077 0.5949367 0.05063291 9.148192e-02
#> 972   5.744563064  6.92748028 0.6861314 0.00729927 1.317224e-05
#> 973   0.426045466  0.39000809 0.5595238 0.05952381 2.752335e-01
#> 976   0.591618811  5.28962289 0.6354167 0.07291667 7.963489e-03
#> 980   5.866221945  6.53843979 0.7045455 0.02272727 2.600383e-06
#> 984   1.575064993  3.77797831 0.6585366 0.04878049 4.088913e-03
#> 986   2.904957292  4.89838960 0.5934959 0.02439024 3.809416e-02
#> 988   2.568362760  5.04574004 0.6016260 0.01626016 2.418522e-02
#> 989   0.463987099  2.74691328 0.5476190 0.03571429 3.827331e-01
#> 995   3.907376443  1.84196442 0.5833333 0.01190476 1.266305e-01
#> 999   0.130136657  5.48045426 0.7567568 0.01351351 9.989052e-06
#> 1001  3.599773806  2.91564321 0.6428571 0.02380952 8.828761e-03
#> 1003  5.802515582  4.28966940 0.6071429 0.02380952 4.953461e-02
#> 1011  1.647888495  6.43932685 0.7142857 0.00000000 8.568298e-05
#> 1012  2.818494220  5.94226530 0.6785714 0.01190476 1.063115e-03
#> 1013  2.577831128  3.00620774 0.5476190 0.02380952 3.827331e-01
#> 1017  2.995678023  5.78551661 0.6190476 0.02380952 2.909633e-02
#> 1018  2.177572438  0.61714555 0.5740741 0.03703704 2.763029e-01
#> 1020  3.746387909  4.70454233 0.6111111 0.05555556 5.934644e-02
#> 1022  3.666375331  1.53146978 0.5438596 0.01754386 5.078006e-01
#> 1023  4.067996388  2.60640936 0.5357143 0.01785714 5.929801e-01
#> 1027  4.581941423  4.98520562 0.6547619 0.01190476 4.556350e-03
#> 1035  7.690158418  4.99537725 0.6666667 0.03571429 2.250227e-03
#> 1037  1.116518626 -0.80020938 0.4880952 0.02380952 1.172741e+00
#> 1043  3.634572700  2.71847842 0.6491228 0.05263158 2.434092e-02
#> 1062  0.340883142  0.88695956 0.4912281 0.08771930 1.105374e+00
#> 1066  1.127510026  2.06170989 0.5789474 0.05263158 2.332302e-01
#> 1078  1.395513050  3.18892993 0.6140351 0.07017544 8.508907e-02
#> 1086  3.515488051  3.21746721 0.7017544 0.07017544 2.315807e-03
#> 1093  3.158942695  2.06726998 0.5392157 0.03921569 4.282919e-01
#> 1095  9.751630705  1.46530832 0.4830769 0.03692308 1.458251e+00
#> 1105  6.079967095  2.01908631 0.5490196 0.04901961 3.221020e-01
#> 1107  6.461612115  1.83983900 0.5340909 0.02272727 5.224313e-01
#> 1110  0.236308507  1.29540364 0.5104167 0.04166667 8.382565e-01
#> 1113  0.340883142  0.88695956 0.4912281 0.08771930 1.105374e+00
#> 1117 -1.657842814          NA        NA         NA           NA
#> 1118 -0.898435381 -0.03592364 0.4666667 0.02666667 1.682689e+00
#> 1122  1.469087374  1.13087030 0.4788732 0.01408451 1.278185e+00
#> 1124  4.028460944  0.67751835 0.5223881 0.02985075 7.139858e-01
#> 1126  6.561149486  0.45429473 0.4680851 0.02127660 1.618529e+00
#> 1127  2.686190824  1.05809357 0.4705882 0.05882353 1.447547e+00
#> 1130  0.895126238  0.08098762 0.5180723 0.03614458 7.419344e-01
#> 1137  2.203535398 -0.09310271 0.4925373 0.02985075 1.097235e+00
#> 1138  0.354334887  1.09898027 0.5000000 0.05379747 1.000000e+00
#> 1139  2.493425221  0.32415759 0.5098039 0.03921569 8.430220e-01
#> 1141 -0.381768966 -0.29324749 0.4436090 0.02255639 1.806627e+00
#> 1145  0.223093191  3.19224325 0.5581395 0.03488372 2.808875e-01
#> 1150  4.905628195  3.10524264 0.6052632 0.02631579 6.645742e-02
#> 1151  7.391865616  5.54335130 0.6118421 0.03289474 5.819817e-03
#> 1153  5.379102857  5.07928700 0.5468750 0.07812500 4.532547e-01
#> 1155  8.926672777  5.05001502 0.6054422 0.05442177 1.056287e-02
#> 1156  4.336452319  4.00484984 0.5517241 0.04597701 3.345943e-01
#> 1157 -1.729032576  2.54085805 0.6633663 0.01980198 1.024820e-03
#> 1158  3.580854565  2.96978254 0.5915493 0.04225352 2.911902e-02
#> 1159  0.697038886  9.77819860 0.6796117 0.03398058 2.525176e-07
#> 1164  1.647888495  6.43932685 0.7142857 0.00000000 8.568298e-05
#> 1168 11.201050942 11.29525042 0.6785714 0.04166667 3.672575e-06
#> 1169  4.666213626  8.15865744 0.6402439 0.03048780 3.281542e-04
#> 1171  1.615522662  4.88096273 0.5514019 0.04672897 2.875960e-01
#> 1173  8.503032374  9.24243121 0.7272727 0.02020202 6.106436e-06
#> 1174  6.988449497  5.26298772 0.7592593 0.03703704 1.387885e-04
#> 1175  4.307227640  4.23349284 0.6144578 0.04819277 3.702204e-02
#> 1176  8.011490353  7.09213013 0.7361111 0.05555556 6.151089e-05
#> 1178  2.679872913  2.90975724 0.5614035 0.01754386 3.538369e-01
#> 1179  2.809001552  3.38421116 0.6785714 0.01785714 7.526315e-03
#> 1180  4.689352372  5.50308212 0.6283186 0.04424779 6.370212e-03
#> 1183 -1.236680898  4.94894070 0.6914894 0.02127660 2.047226e-04
#> 1184  6.719636026  7.80026337 0.6448598 0.07476636 2.727553e-03
#> 1185  3.151514830  3.97464150 0.5441176 0.05882353 4.668543e-01
#> 1186  3.608661344  4.15868191 0.5925926 0.06172840 9.558070e-02
#> 1191 -1.147247245  7.64339918 0.6463415 0.03048780 1.781293e-04
#> 1192  8.454634421  4.02425708 0.5894040 0.05298013 2.800411e-02
#> 1193  1.085157762  1.37276420 0.4606742 0.02247191 1.541912e+00
#> 1194  4.010614194  5.98640539 0.6666667 0.04273504 3.114910e-04
#> 1195  3.517276474  4.30914005 0.6489362 0.05319149 3.877252e-03
#> 1196  2.974357247  5.69408865 0.6666667 0.03418803 3.114910e-04
#> 1197  3.429981790  6.19671953 0.6239316 0.03418803 7.339134e-03
#> 1202  1.560454341  1.53881908 0.5072464 0.04347826 9.041775e-01
#> 1203  8.277593492  4.26055439 0.6250000 0.04605263 2.054719e-03
#> 1207  8.993743674  4.79893676 0.6190476 0.06802721 3.892417e-03
#> 1208  3.496336630  2.38640296 0.5362319 0.05797101 5.472212e-01
#> 1209  3.894794371  4.72205843 0.6590909 0.03787879 2.565504e-04
#> 1210  1.522241086  3.73088261 0.6057692 0.04807692 3.098405e-02
#> 1211  2.968001365  8.46160296 0.6582915 0.03015075 7.971363e-06
#> 1214  0.417701143  3.08016101 0.5689655 0.08620690 2.935106e-01
#> 1216  2.818494220  5.94226530 0.6785714 0.01190476 1.063115e-03
#> 1219 11.201050942 11.29525042 0.6785714 0.04166667 3.672575e-06
#> 1221  8.984672928  8.33749245 0.6358974 0.03589744 1.474004e-04
#> 1223 -1.191287359  3.46342098 0.5652174 0.02898551 2.785987e-01
#> 1225  3.350889564  6.47992246 0.6262626 0.04040404 1.198470e-02
#> 1226  1.515728926  3.97127308 0.6588235 0.03529412 3.405348e-03
#> 1228  4.580407245  8.21194982 0.7378641 0.05825243 1.378326e-06
#> 1230  1.077444236  3.10380205 0.5454545 0.02272727 3.937686e-01
#> 1231  0.968604101  3.21327589 0.5517241 0.02298851 3.345943e-01
#> 1232  3.729465972  3.51528040 0.5600000 0.05333333 2.986976e-01
#> 1235  2.227686956  4.89530743 0.6382979 0.04255319 7.325016e-03
#> 1236  1.921893219  4.63151898 0.5362319 0.05797101 5.472212e-01
#> 1237  1.890210280  5.10230667 0.6029412 0.07352941 8.955507e-02
#> 1238  4.701235105  2.92577521 0.5797101 0.07246377 1.854219e-01
#> 1243 -0.752080348  7.24890778 0.6153846 0.03589744 1.270697e-03
#> 1244  6.296035594  4.23081749 0.5486726 0.05309735 3.007656e-01
#> 1245  1.262775114  1.66518080 0.5250000 0.04166667 5.838824e-01
#> 1246  2.434887735  4.16887860 0.5949367 0.03797468 9.148192e-02
#> 1247  0.282078779  1.31037043 0.5000000 0.07142857 1.000000e+00
#> 1248  1.522144639  3.73717619 0.5822785 0.03797468 1.435730e-01
#> 1249  4.612151513  2.89925600 0.5338346 0.03759398 4.351561e-01
#> 1254  1.298769679  1.16559774 0.5384615 0.00000000 5.351435e-01
#> 1255  7.924727054  2.91566650 0.5723684 0.04605263 7.435291e-02
#> 1259  3.549125713  2.09469438 0.5102041 0.06802721 8.045709e-01
#> 1260  1.888447034  1.67679668 0.4461538 0.01538462 1.614739e+00
#> 1261  2.864317891  2.43025790 0.5405405 0.04054054 3.239398e-01
#> 1262  1.397559087  1.23565226 0.5400000 0.03000000 4.237108e-01
#> 1263  2.842660812  7.63163726 0.6303318 0.02843602 1.528725e-04
#> 1266  4.230089507  4.06637381 0.6216216 0.05405405 3.639761e-02
#> 1268  2.577831128  3.00620774 0.5476190 0.02380952 3.827331e-01
#> 1270 -1.657842814          NA        NA         NA           NA
#> 1271  4.666213626  8.15865744 0.6402439 0.03048780 3.281542e-04
#> 1272  8.984672928  8.33749245 0.6358974 0.03589744 1.474004e-04
#> 1275  1.770854299  1.38259625 0.5076923 0.01538462 9.012878e-01
#> 1277 -0.085751380  5.03461674 0.5959596 0.05050505 5.618836e-02
#> 1278  5.427872685  3.39217969 0.5247525 0.02970297 6.188234e-01
#> 1280  0.035876586  4.85201302 0.5714286 0.05042017 1.191414e-01
#> 1282  0.363270418  3.28564910 0.5576923 0.01923077 2.393165e-01
#> 1283  2.742062947  2.69844225 0.5631068 0.02912621 2.002189e-01
#> 1284  2.096329799  3.74546497 0.6197183 0.02816901 4.364036e-02
#> 1287  3.568477514  2.83116566 0.5319149 0.04255319 5.360134e-01
#> 1288  3.543909245  4.22100243 0.6923077 0.01538462 1.929540e-03
#> 1289  3.285619874  4.62194842 0.7230769 0.03076923 3.218994e-04
#> 1290  3.178093877  2.47067399 0.5384615 0.03076923 5.351435e-01
#> 1295  1.286915306  6.61608590 0.5734597 0.02843602 3.283230e-02
#> 1296  4.843464834  2.12829512 0.5321101 0.03669725 5.025529e-01
#> 1297  3.947313870  1.66390716 0.4705882 0.03676471 1.507283e+00
#> 1298  1.936381342  2.55104947 0.5333333 0.01333333 5.637029e-01
#> 1299  1.250905881  2.22452285 0.6923077 0.03846154 5.545667e-03
#> 1300  1.737591326  2.53481071 0.5200000 0.01333333 7.290345e-01
#> 1303  1.840431010  3.31077605 0.5377778 0.02666667 2.570743e-01
#> 1321  1.127510026  2.06170989 0.5789474 0.05263158 2.332302e-01
#> 1322 -0.898435381 -0.03592364 0.4666667 0.02666667 1.682689e+00
#> 1334  3.091634646  4.39625415 0.7093023 0.00000000 1.036095e-04
#> 1338  0.642049873  1.61551600 0.5180723 0.01204819 7.419344e-01
#> 1346  2.864849627  5.23962227 0.5972222 0.03240741 4.266725e-03
#> 1358  3.442555185  2.75741594 0.6447368 0.02631579 1.161689e-02
#> 1359  2.501634983  0.79597722 0.4905660 0.07547170 1.109254e+00
#> 1361 -0.914678896  6.64646762 0.6000000 0.05217391 3.197196e-02
#> 1363  0.713719034  1.31148877 0.5344828 0.12068966 5.994263e-01
#> 1364  1.861111225  6.15012923 0.6781609 0.05747126 8.887985e-04
#> 1366  4.762990275  6.05108234 0.6222222 0.03703704 4.508698e-03
#> 1367  1.807815698  5.75094395 0.6614173 0.03149606 2.745910e-04
#> 1371  7.507244970  7.82593561 0.7019231 0.02884615 3.814478e-05
#> 1375  1.615522662  4.88096273 0.5514019 0.04672897 2.875960e-01
#> 1376 -1.191287359  3.46342098 0.5652174 0.02898551 2.785987e-01
#> 1377  1.770854299  1.38259625 0.5076923 0.01538462 9.012878e-01
#> 1380  1.420280485  4.63893840 0.6363636 0.02597403 1.670340e-02
#> 1383 -3.858999383  3.97299259 0.5937500 0.03906250 3.389485e-02
#> 1388  1.430827155  8.78214379 0.6723164 0.02259887 4.538979e-06
#> 1392 -3.125784694 11.06834015 0.6627219 0.06508876 2.328935e-05
#> 1393  3.635932666  5.32849920 0.5588235 0.04411765 3.319755e-01
#> 1394  1.238758497  4.09896682 0.5802469 0.06172840 1.486140e-01
#> 1396  5.064487993  7.61278339 0.8000000 0.01428571 5.168220e-07
#> 1399  6.775564788  5.36417120 0.6153846 0.01538462 6.281185e-02
#> 1400 -1.844340427  4.86550662 0.6516129 0.05161290 1.599237e-04
#> 1402  6.880826860  8.30191432 0.6666667 0.02824859 9.219564e-06
#> 1403  2.863102772  4.10328295 0.5576923 0.03846154 2.393165e-01
#> 1404  7.195646867  7.61690707 0.6779661 0.02259887 2.186559e-06
#> 1413  2.295134768  3.82436744 0.6896552 0.05172414 3.867869e-03
#> 1423  5.125552038  4.11736405 0.6867470 0.02409639 6.672544e-04
#> 1431  1.420280485  4.63893840 0.6363636 0.02597403 1.670340e-02
#> 1435  5.282360742  4.22567273 0.7115385 0.05769231 2.281937e-03
#> 1440  1.701359114  3.92252853 0.6265060 0.02409639 2.116380e-02
#> 1441  1.909745491          NA        NA         NA           NA
#> 1444  2.330812081  5.75165536 0.5507246 0.08695652 3.993957e-01
#> 1448  5.441448946  4.47557941 0.7105263 0.03947368 2.419328e-04
#> 1452  0.179633036  4.44424726 0.7454545 0.01818182 2.719197e-04
#> 1454  1.399971159  6.27513214 0.6867470 0.04819277 6.672544e-04
#> 1456  1.502937465  6.07653600 0.6867470 0.03614458 6.672544e-04
#> 1457  0.606946798  4.77429753 0.6162791 0.05813953 3.103252e-02
#> 1463  2.988058682  2.81031788 0.5757576 0.03030303 1.316680e-01
#> 1467  3.048705508  5.51878806 0.6516854 0.03370787 4.209845e-03
#> 1469  0.377582455  2.47668430 0.6060606 0.04040404 3.480848e-02
#> 1471  6.288346597  7.29524881 0.6767677 0.05050505 4.354152e-04
#> 1476  2.995678023  5.78551661 0.6190476 0.02380952 2.909633e-02
#> 1479  8.503032374  9.24243121 0.7272727 0.02020202 6.106436e-06
#> 1480  3.350889564  6.47992246 0.6262626 0.04040404 1.198470e-02
#> 1481 -0.085751380  5.03461674 0.5959596 0.05050505 5.618836e-02
#> 1486  6.125586808  5.02129057 0.7037037 0.05555556 2.755077e-03
#> 1488 10.434892136 11.29181596 0.7638889 0.08333333 7.522468e-06
#> 1490  4.430444186  2.96638910 0.6315789 0.05263158 4.694473e-02
#> 1491  3.186820992  3.82604376 0.6964286 0.05357143 3.283461e-03
#> 1495  1.212375148  5.99741977 0.6382979 0.04255319 7.325016e-03
#> 1503  5.159641879  7.13261357 0.7070707 0.05050505 3.777967e-05
#> 1505  1.693683748  1.31644349 0.4831461 0.04494382 1.249515e+00
#> 1509  5.573291986  6.23943859 0.7073171 0.03252033 4.255128e-06
#> 1515  3.004122017  3.12518114 0.5740741 0.03703704 2.763029e-01
#> 1521  6.313854145  4.93486656 0.6422764 0.04065041 1.600346e-03
#> 1523 11.618345264  9.12366726 0.7235772 0.02439024 7.079026e-07
#> 1526  2.537601166  5.59267905 0.6770833 0.05208333 5.202443e-04
#> 1528  2.177572438  0.61714555 0.5740741 0.03703704 2.763029e-01
#> 1530  1.469087374  1.13087030 0.4788732 0.01408451 1.278185e+00
#> 1531  6.988449497  5.26298772 0.7592593 0.03703704 1.387885e-04
#> 1532  1.515728926  3.97127308 0.6588235 0.03529412 3.405348e-03
#> 1533  5.427872685  3.39217969 0.5247525 0.02970297 6.188234e-01
#> 1537  6.125586808  5.02129057 0.7037037 0.05555556 2.755077e-03
#> 1540  9.239008882  8.67846371 0.7647059 0.02521008 7.686149e-09
#> 1542  8.508519426 11.29607925 0.7479675 0.02439024 3.793935e-08
#> 1543  5.604245163  6.55239344 0.6829268 0.03252033 4.959798e-05
#> 1547  0.720755553  1.96460545 0.5925926 0.03703704 1.735682e-01
#> 1553  6.210021493  5.22283727 0.6984127 0.01587302 1.634360e-03
#> 1554  3.448054449  8.47387230 0.7246377 0.01449275 1.899946e-04
#> 1555  5.538299791  9.98475809 0.7154472 0.03252033 1.763015e-06
#> 1557  3.562277112  2.73374910 0.5365854 0.02439024 4.170771e-01
#> 1566  0.194280644  0.75308613 0.5769231 0.00000000 2.672575e-01
#> 1569  7.221878507  5.13638087 0.5963303 0.06422018 4.427951e-02
#> 1572  4.416587185  1.70141854 0.5555556 0.03174603 3.778216e-01
#> 1574  2.640462989  3.92118181 0.5945946 0.04504505 4.623607e-02
#> 1575  3.444185260  3.83440260 0.6310680 0.03883495 7.805044e-03
#> 1579  0.904238057  2.62363077 0.5949367 0.05063291 9.148192e-02
#> 1583  4.307227640  4.23349284 0.6144578 0.04819277 3.702204e-02
#> 1587 -3.858999383  3.97299259 0.5937500 0.03906250 3.389485e-02
#> 1588  5.282360742  4.22567273 0.7115385 0.05769231 2.281937e-03
#> 1596  5.117765865  3.80786881 0.5781250 0.03125000 7.709987e-02
#> 1600 11.358105284  5.35829278 0.6015625 0.07812500 2.155627e-02
#> 1602  3.092034329  1.76493622 0.5789474 0.00000000 2.332302e-01
#> 1608  3.323441277  2.55961142 0.5625000 0.04687500 1.572992e-01
#> 1610  0.795534074  6.42164439 0.6328125 0.03125000 2.654029e-03
#> 1611  0.159170400  4.96925150 0.6666667 0.03225806 1.306490e-03
#> 1612  0.340602321  6.12603882 0.6250000 0.03125000 4.677735e-03
#> 1613  3.732253762  7.86749352 0.6642336 0.05839416 1.207446e-04
#> 1619  2.659605495  2.42096130 0.5694444 0.04166667 2.385928e-01
#> 1623  2.552478026  4.45880423 0.6612903 0.06451613 1.108517e-02
#> 1625  2.958218315  4.37525776 0.6569343 0.06569343 2.390279e-04
#> 1627  8.879194304  8.18953660 0.6861314 0.05109489 1.317224e-05
#> 1630 -0.318130597  4.62048927 0.6195652 0.07608696 2.181012e-02
#> 1632  3.746387909  4.70454233 0.6111111 0.05555556 5.934644e-02
#> 1634  4.028460944  0.67751835 0.5223881 0.02985075 7.139858e-01
#> 1635  8.011490353  7.09213013 0.7361111 0.05555556 6.151089e-05
#> 1636  4.580407245  8.21194982 0.7378641 0.05825243 1.378326e-06
#> 1637  0.035876586  4.85201302 0.5714286 0.05042017 1.191414e-01
#> 1641 10.434892136 11.29181596 0.7638889 0.08333333 7.522468e-06
#> 1642  9.239008882  8.67846371 0.7647059 0.02521008 7.686149e-09
#> 1646  7.068920215  6.98401205 0.6803279 0.03278689 6.788685e-05
#> 1647  4.892925405  5.42590193 0.6363636 0.04132231 2.699796e-03
#> 1651  0.812569529  5.50798846 0.6666667 0.06944444 4.677735e-03
#> 1657  7.404186431  4.93925262 0.7457627 0.03389831 1.597009e-04
#> 1658  1.248774495  8.63849837 0.8307692 0.03076923 9.634097e-08
#> 1659  4.767277942  9.32784891 0.7080292 0.05839416 1.116894e-06
#> 1661 -1.297548098  1.28856599 0.5182482 0.05839416 6.692491e-01
#> 1669  6.892528861  1.82161324 0.4765101 0.10067114 1.433668e+00
#> 1672  2.860184764  0.11097661 0.5098039 0.04901961 8.430220e-01
#> 1674  5.923983276  2.08136273 0.4725275 0.05494505 1.399821e+00
#> 1681  3.372213963  0.44355997 0.4909091 0.04545455 1.151233e+00
#> 1717  4.032345115  5.79740652 0.6369427 0.03184713 5.996479e-04
#> 1719  1.543691654  5.38463941 0.6275862 0.01379310 2.121439e-03
#> 1723  3.116880179  0.57397454 0.4912281 0.01754386 1.105374e+00
#> 1729  9.146287992  5.59216119 0.6114650 0.03184713 5.217262e-03
#> 1731 11.202984249  6.65972704 0.6293706 0.02797203 1.974140e-03
#> 1734  2.398401357  3.86295977 0.5537190 0.04958678 2.372779e-01
#> 1736  3.666375331  1.53146978 0.5438596 0.01754386 5.078006e-01
#> 1738  6.561149486  0.45429473 0.4680851 0.02127660 1.618529e+00
#> 1739  2.679872913  2.90975724 0.5614035 0.01754386 3.538369e-01
#> 1740  1.077444236  3.10380205 0.5454545 0.02272727 3.937686e-01
#> 1741  0.363270418  3.28564910 0.5576923 0.01923077 2.393165e-01
#> 1742  3.091634646  4.39625415 0.7093023 0.00000000 1.036095e-04
#> 1745  4.430444186  2.96638910 0.6315789 0.05263158 4.694473e-02
#> 1746  8.508519426 11.29607925 0.7479675 0.02439024 3.793935e-08
#> 1748  7.068920215  6.98401205 0.6803279 0.03278689 6.788685e-05
#> 1751  5.398619953  5.96947343 0.6217949 0.04487179 2.346726e-03
#> 1754  3.256717692  3.91895031 0.5797101 0.01449275 1.854219e-01
#> 1755  0.275890939  1.66171936 0.5087719 0.03508772 8.946258e-01
#> 1761  3.284948749  5.06451195 0.7313433 0.01492537 1.523221e-04
#> 1762  2.712126203 16.34543987 0.7526882 0.03225806 5.485390e-12
#> 1763  5.745084501  9.99493156 0.6942675 0.03821656 1.125453e-06
#> 1765  3.639887423  3.03282157 0.5585106 0.02659574 1.086006e-01
#> 1769  4.631992406  4.87595238 0.6089744 0.05128205 6.485308e-03
#> 1771  1.723311918  0.70943739 0.5084746 0.05084746 8.964170e-01
#> 1775  1.838776227  1.55150174 0.6250000 0.01785714 6.136883e-02
#> 1781  3.925807862  2.55185611 0.5384615 0.05128205 3.366684e-01
#> 1783  6.559370513  5.27627051 0.6267606 0.04225352 2.518974e-03
#> 1786  1.241914109  2.83967873 0.5702479 0.07438017 1.222364e-01
#> 1788  4.067996388  2.60640936 0.5357143 0.01785714 5.929801e-01
#> 1790  2.686190824  1.05809357 0.4705882 0.05882353 1.447547e+00
#> 1791  2.809001552  3.38421116 0.6785714 0.01785714 7.526315e-03
#> 1792  0.968604101  3.21327589 0.5517241 0.02298851 3.345943e-01
#> 1793  2.742062947  2.69844225 0.5631068 0.02912621 2.002189e-01
#> 1797  3.186820992  3.82604376 0.6964286 0.05357143 3.283461e-03
#> 1798  5.604245163  6.55239344 0.6829268 0.03252033 4.959798e-05
#> 1800  4.892925405  5.42590193 0.6363636 0.04132231 2.699796e-03
#> 1802  5.398619953  5.96947343 0.6217949 0.04487179 2.346726e-03
#> 1807  0.260322477  1.93040321 0.5535714 0.01785714 4.226781e-01
#> 1813  3.756224803  2.56937867 0.5970149 0.02985075 1.122405e-01
#> 1814  1.326547219  4.93168329 0.5800000 0.08000000 1.095986e-01
#> 1815  7.102584007  7.78116759 0.6987179 0.04487179 6.906563e-07
#> 1817  1.705566702  0.37463531 0.4807692 0.05128205 1.369046e+00
#> 1826  1.175563790  2.99345060 0.5921053 0.01315789 1.082937e-01
#> 1827  1.820871338  1.47107898 0.5254237 0.06779661 6.961175e-01
#> 1829  2.717092141  4.92482298 0.5565217 0.03478261 2.254143e-01
#> 1831  2.777698486  1.82002078 0.5312500 0.10937500 6.170751e-01
#> 1832  3.042037561  2.97302305 0.5287356 0.03448276 5.919197e-01
#> 1834  3.115920222  4.69696814 0.6028369 0.02127660 1.459642e-02
#> 1835  3.150329454  5.25715694 0.6090226 0.01503759 1.191611e-02
#> 1836  2.788183335  4.11487352 0.6666667 0.00000000 1.430588e-02
#> 1839  5.744563064  6.92748028 0.6861314 0.00729927 1.317224e-05
#> 1843  4.689352372  5.50308212 0.6283186 0.04424779 6.370212e-03
#> 1844  3.729465972  3.51528040 0.5600000 0.05333333 2.986976e-01
#> 1845  2.096329799  3.74546497 0.6197183 0.02816901 4.364036e-02
#> 1847  1.430827155  8.78214379 0.6723164 0.02259887 4.538979e-06
#> 1848  1.701359114  3.92252853 0.6265060 0.02409639 2.116380e-02
#> 1851  5.117765865  3.80786881 0.5781250 0.03125000 7.709987e-02
#> 1857  1.593698624  0.70660650 0.4605263 0.06578947 1.508703e+00
#> 1860 10.270421139 12.84417804 0.6627219 0.05325444 2.328935e-05
#> 1861  1.072627749  6.81861747 0.6470588 0.04411765 1.529337e-02
#> 1862  4.398032845  5.77533580 0.6543210 0.03703704 5.473204e-03
#> 1864  1.348802895  4.66715875 0.6213592 0.01941748 1.376558e-02
#> 1867  1.349522681  4.01195155 0.6197183 0.01408451 4.364036e-02
#> 1868  5.654704931  4.90503223 0.5714286 0.03726708 6.988521e-02
#> 1870  2.415927937  7.94553731 0.6435644 0.01485149 4.486826e-05
#> 1871  1.401239729  3.74426937 0.5480769 0.02884615 3.267996e-01
#> 1872  1.098375539  7.73628696 0.6485149 0.00990099 2.425902e-05
#> 1888 -0.692101411  0.99710476 0.5161290 0.06451613 7.994954e-01
#> 1891  0.426045466  0.39000809 0.5595238 0.05952381 2.752335e-01
#> 1900  1.909745491          NA        NA         NA           NA
#> 1908  1.593698624  0.70660650 0.4605263 0.06578947 1.508703e+00
#> 1916  1.865018306  1.05546673 0.5714286 0.08333333 1.904303e-01
#> 1922 -1.167355621  1.48831878 0.5483871 0.08064516 4.460595e-01
#> 1924 -1.479619881  1.15098890 0.5483871 0.06451613 4.460595e-01
#> 1927  2.690555518  3.25559723 0.5542169 0.02409639 3.232122e-01
#> 1945  1.395513050  3.18892993 0.6140351 0.07017544 8.508907e-02
#> 1946  0.895126238  0.08098762 0.5180723 0.03614458 7.419344e-01
#> 1950  0.642049873  1.61551600 0.5180723 0.01204819 7.419344e-01
#> 1958  3.256717692  3.91895031 0.5797101 0.01449275 1.854219e-01
#> 1970  5.157705774  4.93940375 0.6867470 0.02409639 6.672544e-04
#> 1977  4.562105380  4.19432051 0.6279070 0.04651163 1.767673e-02
#> 1983  0.916483180  2.99662212 0.6063830 0.03191489 3.912760e-02
#> 1987  0.001591657  3.29493506 0.5595238 0.03571429 2.752335e-01
#> 1989 10.606794165  5.42803973 0.7127660 0.04255319 3.696329e-05
#> 1991  1.771860672  3.82917418 0.5851064 0.05319149 9.888691e-02
#> 1996  4.581941423  4.98520562 0.6547619 0.01190476 4.556350e-03
#> 1999 -1.236680898  4.94894070 0.6914894 0.02127660 2.047226e-04
#> 2000  2.227686956  4.89530743 0.6382979 0.04255319 7.325016e-03
#> 2001  3.568477514  2.83116566 0.5319149 0.04255319 5.360134e-01
#> 2005  1.212375148  5.99741977 0.6382979 0.04255319 7.325016e-03
#> 2006  0.720755553  1.96460545 0.5925926 0.03703704 1.735682e-01
#> 2008  0.812569529  5.50798846 0.6666667 0.06944444 4.677735e-03
#> 2010  0.275890939  1.66171936 0.5087719 0.03508772 8.946258e-01
#> 2011  0.260322477  1.93040321 0.5535714 0.01785714 4.226781e-01
#> 2023  2.963270756  6.00845882 0.7127660 0.05319149 3.696329e-05
#> 2025  1.759497087  0.84701769 0.5280899 0.03370787 5.961127e-01
#> 2034  3.000309909  3.08612890 0.5921053 0.02631579 1.082937e-01
#> 2035  0.938224974  1.89697919 0.5660377 0.03773585 3.362888e-01
#> 2037 10.707725167  7.99626189 0.5565217 0.09565217 2.254143e-01
#> 2039  1.604898066  1.26168213 0.5862069 0.12068966 1.891613e-01
#> 2040  4.372123277  4.97162031 0.5287356 0.05747126 5.919197e-01
#> 2042  2.310669995  7.27707678 0.6074074 0.06666667 1.256300e-02
#> 2043  4.106862565  8.41715072 0.6535433 0.06299213 5.387921e-04
#> 2047  0.591618811  5.28962289 0.6354167 0.07291667 7.963489e-03
#> 2051  6.719636026  7.80026337 0.6448598 0.07476636 2.727553e-03
#> 2052  1.921893219  4.63151898 0.5362319 0.05797101 5.472212e-01
#> 2053  3.543909245  4.22100243 0.6923077 0.01538462 1.929540e-03
#> 2055 -3.125784694 11.06834015 0.6627219 0.06508876 2.328935e-05
#> 2056  2.330812081  5.75165536 0.5507246 0.08695652 3.993957e-01
#> 2059 11.358105284  5.35829278 0.6015625 0.07812500 2.155627e-02
#> 2064 10.270421139 12.84417804 0.6627219 0.05325444 2.328935e-05
#> 2069  5.999458397  8.38214417 0.7058824 0.04411765 6.850369e-04
#> 2070  6.824910285  9.04522998 0.7037037 0.04938272 2.457328e-04
#> 2072  1.685018256  4.67475147 0.6129032 0.08064516 7.540356e-02
#> 2075  5.007072815  7.13605209 0.6307692 0.01538462 3.497994e-02
#> 2076  8.602759502  6.97566701 0.6258065 0.08387097 1.732917e-03
#> 2078  2.583227404 11.26448891 0.6745562 0.05325444 5.666613e-06
#> 2079  2.112254204  5.35567611 0.6250000 0.07692308 1.078745e-02
#> 2080  1.725011191 10.37644692 0.6686391 0.05325444 1.161909e-05
#> 2086  2.672577261  2.10489289 0.5441176 0.02941176 4.668543e-01
#> 2087  1.041061243  1.34151163 0.4716981 0.07547170 1.319720e+00
#> 2091 -0.485744818  1.84687170 0.5689655 0.13793103 2.935106e-01
#> 2092  1.044361703  2.65896942 0.5000000 0.04411765 1.000000e+00
#> 2094  1.909362385  3.16643228 0.5441176 0.04411765 4.668543e-01
#> 2095  4.417453099  7.13896237 0.6029412 0.02941176 8.955507e-02
#> 2103  3.151514830  3.97464150 0.5441176 0.05882353 4.668543e-01
#> 2104  1.890210280  5.10230667 0.6029412 0.07352941 8.955507e-02
#> 2105  3.285619874  4.62194842 0.7230769 0.03076923 3.218994e-04
#> 2107  3.635932666  5.32849920 0.5588235 0.04411765 3.319755e-01
#> 2116  1.072627749  6.81861747 0.6470588 0.04411765 1.529337e-02
#> 2120  5.999458397  8.38214417 0.7058824 0.04411765 6.850369e-04
#> 2122  2.074731802  2.99846415 0.5735294 0.05882353 2.252529e-01
#> 2127  3.038003847  3.57126546 0.6307692 0.03076923 3.497994e-02
#> 2128  3.271896507  3.37867319 0.5441176 0.05882353 4.668543e-01
#> 2130  5.290433575  4.81038669 0.5735294 0.02941176 2.252529e-01
#> 2131  2.717115409  2.10446437 0.5818182 0.07272727 2.249159e-01
#> 2132  5.062331889  3.99272718 0.5588235 0.02941176 3.319755e-01
#> 2138  3.109571940  1.58034033 0.5921053 0.02631579 1.082937e-01
#> 2139  5.774965560  1.35285919 0.4905660 0.09433962 1.109254e+00
#> 2143 -0.837652001  0.58542752 0.5000000 0.13793103 1.000000e+00
#> 2144  8.330683272  2.68470795 0.5925926 0.03703704 9.558070e-02
#> 2146  2.678576088  5.30982767 0.7160494 0.03703704 1.007042e-04
#> 2147  2.943962182  5.17090062 0.6419753 0.02469136 1.060184e-02
#> 2155  3.608661344  4.15868191 0.5925926 0.06172840 9.558070e-02
#> 2156  4.701235105  2.92577521 0.5797101 0.07246377 1.854219e-01
#> 2157  3.178093877  2.47067399 0.5384615 0.03076923 5.351435e-01
#> 2159  1.238758497  4.09896682 0.5802469 0.06172840 1.486140e-01
#> 2163  3.092034329  1.76493622 0.5789474 0.00000000 2.332302e-01
#> 2168  4.398032845  5.77533580 0.6543210 0.03703704 5.473204e-03
#> 2172  6.824910285  9.04522998 0.7037037 0.04938272 2.457328e-04
#> 2173  2.074731802  2.99846415 0.5735294 0.05882353 2.252529e-01
#> 2179 -1.145188434  6.67889026 0.6153846 0.03076923 6.281185e-02
#> 2180  6.388942361  3.16842463 0.5802469 0.02469136 1.486140e-01
#> 2182  3.947838401  6.90868439 0.6790123 0.02469136 1.272004e-03
#> 2183  1.997750767  2.47022878 0.5588235 0.02941176 3.319755e-01
#> 2184  3.168187313  5.94752395 0.6666667 0.02469136 2.699796e-03
#> 2245  1.376268897  4.22976500 0.6666667 0.05882353 1.729028e-02
#> 2252  1.609224207  4.53607556 0.6219512 0.03658537 2.720035e-02
#> 2255  5.866221945  6.53843979 0.7045455 0.02272727 2.600383e-06
#> 2263  5.064487993  7.61278339 0.8000000 0.01428571 5.168220e-07
#> 2264  5.441448946  4.47557941 0.7105263 0.03947368 2.419328e-04
#> 2272  1.348802895  4.66715875 0.6213592 0.01941748 1.376558e-02
#> 2273  1.865018306  1.05546673 0.5714286 0.08333333 1.904303e-01
#> 2276  1.685018256  4.67475147 0.6129032 0.08064516 7.540356e-02
#> 2286  1.248702376  6.48787418 0.7303371 0.02247191 1.386481e-05
#> 2288  1.233388233  6.34938743 0.7303371 0.02247191 1.386481e-05
#> 2289  3.121132771  4.56882160 0.6417910 0.04477612 2.027500e-02
#> 2301  2.871929864  3.81714110 0.6119403 0.04477612 6.687076e-02
#> 2303  3.689870330  3.26592239 0.6268657 0.01492537 3.781258e-02
#> 2306 -0.214109657  3.42926753 0.5522388 0.04477612 3.924481e-01
#> 2310  2.203535398 -0.09310271 0.4925373 0.02985075 1.097235e+00
#> 2318  6.210021493  5.22283727 0.6984127 0.01587302 1.634360e-03
#> 2320  7.404186431  4.93925262 0.7457627 0.03389831 1.597009e-04
#> 2322  3.284948749  5.06451195 0.7313433 0.01492537 1.523221e-04
#> 2323  3.756224803  2.56937867 0.5970149 0.02985075 1.122405e-01
#> 2334  0.655834172  4.76682129 0.6567164 0.04477612 1.030099e-02
#> 2335  1.968150197  4.24191462 0.6417910 0.01492537 2.027500e-02
#> 2337 -2.459679277  0.36123749 0.5522388 0.02985075 3.924481e-01
#> 2341  1.604484047  6.28155102 0.7000000 0.04000000 6.334248e-05
#> 2343  4.320627392 10.02441978 0.6327273 0.05090909 1.072251e-05
#> 2353  1.134331145  5.76071481 0.6700000 0.06000000 6.738585e-04
#> 2355  1.004154697  8.30115022 0.7674419 0.04651163 7.038165e-07
#> 2358  2.713004881  3.14443581 0.6276596 0.06382979 1.330829e-02
#> 2361  3.515488051  3.21746721 0.7017544 0.07017544 2.315807e-03
#> 2362  0.354334887  1.09898027 0.5000000 0.05379747 1.000000e+00
#> 2366  2.864849627  5.23962227 0.5972222 0.03240741 4.266725e-03
#> 2370  3.448054449  8.47387230 0.7246377 0.01449275 1.899946e-04
#> 2372  1.248774495  8.63849837 0.8307692 0.03076923 9.634097e-08
#> 2374  2.712126203 16.34543987 0.7526882 0.03225806 5.485390e-12
#> 2375  1.326547219  4.93168329 0.5800000 0.08000000 1.095986e-01
#> 2378  5.157705774  4.93940375 0.6867470 0.02409639 6.672544e-04
#> 2385  0.655834172  4.76682129 0.6567164 0.04477612 1.030099e-02
#> 2387  1.494142682  8.25316057 0.7300000 0.06000000 4.224909e-06
#> 2389  1.723470580  1.94351614 0.5572519 0.03816794 1.900078e-01
#> 2393  4.804963625  7.01318469 0.6559140 0.05376344 2.111459e-05
#> 2395  3.716492486  1.36844501 0.5254237 0.03389831 6.961175e-01
#> 2398  0.809493917  1.72881554 0.6000000 0.00000000 1.068637e-01
#> 2399 -0.463849589  4.06726031 0.6118421 0.04605263 5.819817e-03
#> 2403 -2.321917665  3.24055667 0.5986395 0.06802721 1.676234e-02
#> 2404 -1.521509137  2.87865561 0.5384615 0.01538462 5.351435e-01
#> 2405  6.133047854  4.50347702 0.6169154 0.04477612 9.160235e-04
#> 2406  3.773933482  5.20372019 0.6200000 0.01000000 1.639507e-02
#> 2407  6.681299456 11.06237782 0.6720000 0.03200000 5.354511e-08
#> 2410  1.428692088  4.62747357 0.6611570 0.04958678 3.919366e-04
#> 2412  7.690158418  4.99537725 0.6666667 0.03571429 2.250227e-03
#> 2414  2.493425221  0.32415759 0.5098039 0.03921569 8.430220e-01
#> 2415 -1.147247245  7.64339918 0.6463415 0.03048780 1.781293e-04
#> 2416 -0.752080348  7.24890778 0.6153846 0.03589744 1.270697e-03
#> 2417  1.286915306  6.61608590 0.5734597 0.02843602 3.283230e-02
#> 2419  6.775564788  5.36417120 0.6153846 0.01538462 6.281185e-02
#> 2421  5.159641879  7.13261357 0.7070707 0.05050505 3.777967e-05
#> 2422  5.538299791  9.98475809 0.7154472 0.03252033 1.763015e-06
#> 2424  4.767277942  9.32784891 0.7080292 0.05839416 1.116894e-06
#> 2426  5.745084501  9.99493156 0.6942675 0.03821656 1.125453e-06
#> 2427  7.102584007  7.78116759 0.6987179 0.04487179 6.906563e-07
#> 2428  1.349522681  4.01195155 0.6197183 0.01408451 4.364036e-02
#> 2431  2.963270756  6.00845882 0.7127660 0.05319149 3.696329e-05
#> 2432  5.007072815  7.13605209 0.6307692 0.01538462 3.497994e-02
#> 2433  3.038003847  3.57126546 0.6307692 0.03076923 3.497994e-02
#> 2434 -1.145188434  6.67889026 0.6153846 0.03076923 6.281185e-02
#> 2437  1.968150197  4.24191462 0.6417910 0.01492537 2.027500e-02
#> 2438  1.494142682  8.25316057 0.7300000 0.06000000 4.224909e-06
#> 2440 -1.110714945  5.16212810 0.6330275 0.02752294 5.474577e-03
#> 2441  2.634409102  3.00866645 0.5502646 0.04232804 1.669574e-01
#> 2442  3.811104891  4.16069911 0.6666667 0.00000000 3.892417e-03
#> 2443  3.892043052  1.91373461 0.5000000 0.03846154 1.000000e+00
#> 2444  4.092638732  3.31728541 0.6533333 0.00000000 7.911789e-03
#> 2450  3.055299845  2.92336703 0.6842105 0.02631579 1.318969e-03
#> 2451  5.506908557  1.89292623 0.6288660 0.06185567 1.113716e-02
#> 2453  3.350146719  3.59733880 0.6339286 0.06250000 4.586392e-03
#> 2455  1.888084658  2.51243934 0.6274510 0.07843137 1.004189e-02
#> 2456  5.274440684  2.95773197 0.5057471 0.04597701 9.146214e-01
#> 2458  2.098993510  6.16893514 0.6411765 0.03529412 2.319277e-04
#> 2459  0.207221017  3.12233393 0.5438596 0.04093567 2.513491e-01
#> 2463  1.575064993  3.77797831 0.6585366 0.04878049 4.088913e-03
#> 2467  8.454634421  4.02425708 0.5894040 0.05298013 2.800411e-02
#> 2468  6.296035594  4.23081749 0.5486726 0.05309735 3.007656e-01
#> 2469  4.843464834  2.12829512 0.5321101 0.03669725 5.025529e-01
#> 2471 -1.844340427  4.86550662 0.6516129 0.05161290 1.599237e-04
#> 2472  0.179633036  4.44424726 0.7454545 0.01818182 2.719197e-04
#> 2475  3.323441277  2.55961142 0.5625000 0.04687500 1.572992e-01
#> 2480  5.654704931  4.90503223 0.5714286 0.03726708 6.988521e-02
#> 2484  8.602759502  6.97566701 0.6258065 0.08387097 1.732917e-03
#> 2485  3.271896507  3.37867319 0.5441176 0.05882353 4.668543e-01
#> 2486  6.388942361  3.16842463 0.5802469 0.02469136 1.486140e-01
#> 2491 -1.110714945  5.16212810 0.6330275 0.02752294 5.474577e-03
#> 2494  2.581139912  4.55198946 0.6363636 0.03636364 4.596261e-04
#> 2495  2.369549920  1.34523880 0.5673077 0.04807692 1.698105e-01
#> 2496  1.473476302  3.79767562 0.6303030 0.03636364 8.153061e-04
#> 2497 -0.432720785  0.87259576 0.5322581 0.04301075 3.789229e-01
#> 2499  0.611505061  2.35965627 0.6000000 0.00000000 5.777957e-02
#> 2503  2.271553900  1.01853026 0.4382022 0.03370787 1.756385e+00
#> 2507  0.775876473  0.47957563 0.4683544 0.03797468 1.426255e+00
#> 2509  1.962311295  2.11895961 0.5343915 0.03703704 3.443471e-01
#> 2511  5.106843594  3.72116924 0.6228571 0.04000000 1.152045e-03
#> 2514  2.453033421  2.01162795 0.5123967 0.04958678 7.850629e-01
#> 2516  1.116518626 -0.80020938 0.4880952 0.02380952 1.172741e+00
#> 2518 -0.381768966 -0.29324749 0.4436090 0.02255639 1.806627e+00
#> 2519  1.085157762  1.37276420 0.4606742 0.02247191 1.541912e+00
#> 2520  1.262775114  1.66518080 0.5250000 0.04166667 5.838824e-01
#> 2521  3.947313870  1.66390716 0.4705882 0.03676471 1.507283e+00
#> 2525  1.693683748  1.31644349 0.4831461 0.04494382 1.249515e+00
#> 2526  3.562277112  2.73374910 0.5365854 0.02439024 4.170771e-01
#> 2528 -1.297548098  1.28856599 0.5182482 0.05839416 6.692491e-01
#> 2530  3.639887423  3.03282157 0.5585106 0.02659574 1.086006e-01
#> 2531  1.705566702  0.37463531 0.4807692 0.05128205 1.369046e+00
#> 2535  1.759497087  0.84701769 0.5280899 0.03370787 5.961127e-01
#> 2541 -2.459679277  0.36123749 0.5522388 0.02985075 3.924481e-01
#> 2542  1.723470580  1.94351614 0.5572519 0.03816794 1.900078e-01
#> 2543  2.634409102  3.00866645 0.5502646 0.04232804 1.669574e-01
#> 2554  3.097864025  1.96199700 0.5789474 0.00000000 1.686686e-01
#> 2555  2.264550695  2.10995993 0.6190476 0.04761905 5.878172e-02
#> 2557  4.499511282  6.44672611 0.6521739 0.04347826 1.099416e-03
#> 2559  1.303629490  2.02544221 0.6029412 0.08823529 8.955507e-02
#> 2560  1.720950333  1.38501707 0.5057471 0.02298851 9.146214e-01
#> 2562  2.671598235  5.28961625 0.6413793 0.02068966 6.619685e-04
#> 2563  5.936873740  6.74920035 0.7153285 0.01459854 4.638074e-07
#> 2567  2.904957292  4.89838960 0.5934959 0.02439024 3.809416e-02
#> 2571  4.010614194  5.98640539 0.6666667 0.04273504 3.114910e-04
#> 2572  2.434887735  4.16887860 0.5949367 0.03797468 9.148192e-02
#> 2573  1.936381342  2.55104947 0.5333333 0.01333333 5.637029e-01
#> 2575  6.880826860  8.30191432 0.6666667 0.02824859 9.219564e-06
#> 2576  1.399971159  6.27513214 0.6867470 0.04819277 6.672544e-04
#> 2579  0.795534074  6.42164439 0.6328125 0.03125000 2.654029e-03
#> 2584  2.415927937  7.94553731 0.6435644 0.01485149 4.486826e-05
#> 2585 -1.167355621  1.48831878 0.5483871 0.08064516 4.460595e-01
#> 2588  2.583227404 11.26448891 0.6745562 0.05325444 5.666613e-06
#> 2589  5.290433575  4.81038669 0.5735294 0.02941176 2.252529e-01
#> 2590  3.947838401  6.90868439 0.6790123 0.02469136 1.272004e-03
#> 2592  1.248702376  6.48787418 0.7303371 0.02247191 1.386481e-05
#> 2595  3.811104891  4.16069911 0.6666667 0.00000000 3.892417e-03
#> 2596  2.581139912  4.55198946 0.6363636 0.03636364 4.596261e-04
#> 2599  6.272802818  4.97701917 0.6346154 0.02884615 6.039559e-03
#> 2600 68.766917325 56.08987166 0.9805825 0.01456311 0.000000e+00
#> 2606  2.749195457 -0.92107103 0.5396825 0.03174603 5.287333e-01
#> 2609  6.812711955  6.14634665 0.5945946 0.04054054 1.036380e-01
#> 2612  0.994744452  2.22064098 0.5675676 0.05405405 2.450420e-01
#> 2614  0.025098086  3.75738021 0.5769231 0.03846154 1.166645e-01
#> 2615  1.937907171  3.45472966 0.6730769 0.01923077 4.154176e-04
#> 2623  3.517276474  4.30914005 0.6489362 0.05319149 3.877252e-03
#> 2624  0.282078779  1.31037043 0.5000000 0.07142857 1.000000e+00
#> 2625  1.250905881  2.22452285 0.6923077 0.03846154 5.545667e-03
#> 2627  2.863102772  4.10328295 0.5576923 0.03846154 2.393165e-01
#> 2631  0.159170400  4.96925150 0.6666667 0.03225806 1.306490e-03
#> 2636  1.401239729  3.74426937 0.5480769 0.02884615 3.267996e-01
#> 2640  2.112254204  5.35567611 0.6250000 0.07692308 1.078745e-02
#> 2641  2.717115409  2.10446437 0.5818182 0.07272727 2.249159e-01
#> 2642  1.997750767  2.47022878 0.5588235 0.02941176 3.319755e-01
#> 2647  3.892043052  1.91373461 0.5000000 0.03846154 1.000000e+00
#> 2648  2.369549920  1.34523880 0.5673077 0.04807692 1.698105e-01
#> 2650  6.272802818  4.97701917 0.6346154 0.02884615 6.039559e-03
#> 2652  6.445213809  5.23617425 0.6538462 0.02884615 1.701872e-03
#> 2658  2.825190294  1.52750505 0.5657895 0.00000000 2.513491e-01
#> 2659  1.840761985  1.95779314 0.6031746 0.04761905 1.014538e-01
#> 2661  4.602200268  6.49026050 0.6434783 0.04347826 2.089089e-03
#> 2663  1.027586074  1.83247594 0.5882353 0.08823529 1.456101e-01
#> 2664  1.056395260  0.73355882 0.5172414 0.02298851 7.477302e-01
#> 2666  2.391063634  4.93827875 0.6275862 0.02068966 2.121439e-03
#> 2667  5.583306851  5.69677517 0.7153285 0.01459854 4.638074e-07
#> 2671  2.568362760  5.04574004 0.6016260 0.01626016 2.418522e-02
#> 2675  2.974357247  5.69408865 0.6666667 0.03418803 3.114910e-04
#> 2676  1.522144639  3.73717619 0.5822785 0.03797468 1.435730e-01
#> 2677  1.737591326  2.53481071 0.5200000 0.01333333 7.290345e-01
#> 2679  7.195646867  7.61690707 0.6779661 0.02259887 2.186559e-06
#> 2680  1.502937465  6.07653600 0.6867470 0.03614458 6.672544e-04
#> 2683  0.340602321  6.12603882 0.6250000 0.03125000 4.677735e-03
#> 2688  1.098375539  7.73628696 0.6485149 0.00990099 2.425902e-05
#> 2689 -1.479619881  1.15098890 0.5483871 0.06451613 4.460595e-01
#> 2692  1.725011191 10.37644692 0.6686391 0.05325444 1.161909e-05
#> 2693  5.062331889  3.99272718 0.5588235 0.02941176 3.319755e-01
#> 2694  3.168187313  5.94752395 0.6666667 0.02469136 2.699796e-03
#> 2696  1.233388233  6.34938743 0.7303371 0.02247191 1.386481e-05
#> 2699  4.092638732  3.31728541 0.6533333 0.00000000 7.911789e-03
#> 2700  1.473476302  3.79767562 0.6303030 0.03636364 8.153061e-04
#> 2702 68.766917325 56.08987166 0.9805825 0.01456311 0.000000e+00
#> 2703  6.445213809  5.23617425 0.6538462 0.02884615 1.701872e-03
```
