Plots
================
Kan Luo
7/23/2020

    ## Response [https://raw.githubusercontent.com/luokan1227/537P1/master/Data.xlsx]
    ##   Date: 2020-10-21 03:30
    ##   Status: 200
    ##   Content-Type: application/octet-stream
    ##   Size: 341 kB
    ## <ON DISK>  C:\Users\shihn\AppData\Local\Temp\RtmpmW2O45\file16a423df23d0.xlsx

    ## Response [https://raw.githubusercontent.com/luokan1227/537P1/master/MonkeyID.xlsx]
    ##   Date: 2020-10-21 03:30
    ##   Status: 200
    ##   Content-Type: application/octet-stream
    ##   Size: 50.1 kB
    ## <ON DISK>  C:\Users\shihn\AppData\Local\Temp\RtmpmW2O45\file16a416665c7f.xlsx

![](README_files/figure-gfm/Ig%20Isotype%20Plot/Table-1.png)<!-- -->![](README_files/figure-gfm/Ig%20Isotype%20Plot/Table-2.png)<!-- -->![](README_files/figure-gfm/Ig%20Isotype%20Plot/Table-3.png)<!-- -->

    ##   Isotype Ab # Ab %
    ## 1       A   51  2.1
    ## 2       D  179  7.3
    ## 3       E   10  0.4
    ## 4       G 1062 43.1
    ## 5       M 1163 47.2

![](README_files/figure-gfm/CDR3%20Plot/Table-1.png)<!-- -->![](README_files/figure-gfm/CDR3%20Plot/Table-2.png)<!-- -->![](README_files/figure-gfm/CDR3%20Plot/Table-3.png)<!-- -->![](README_files/figure-gfm/CDR3%20Plot/Table-4.png)<!-- -->

Notice may have outlier in LCDR3 variable:

``` r
summary(Data$L_CDR3)
```

    ##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
    ##    7.00    9.00    9.00    9.65   10.00   47.00

    ##         H_Mutation% K_Mutation% L_Mutation%
    ## Min.           0.00        0.00        0.00
    ## 1st Qu.        3.42        2.11        2.44
    ## Median         5.90        4.56        4.82
    ## Mean           6.63        5.36        6.88
    ## 3rd Qu.        9.13        7.88        8.25
    ## Max.          24.36       29.41       28.65

![](README_files/figure-gfm/mutation%20rate-1.png)<!-- -->![](README_files/figure-gfm/mutation%20rate-2.png)<!-- -->![](README_files/figure-gfm/mutation%20rate-3.png)<!-- -->
