---
title: "STATE Variable Analyses"
output:
  html_document: 
    keep_md: true
  md_document:
    variant: markdown_github
date: '2025-02-23'
params:
  var1: NULL
  name2: NULL
---






```
##    [1] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##   [37] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##   [73] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [109] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [145] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [181] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [217] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [253] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [289] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [325] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [361] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [397] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [433] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [469] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [505] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [541] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [577] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [613] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [649] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [685] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [721] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [757] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [793] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [829] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [865] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [901] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [937] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [973] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [ reached getOption("max.print") -- omitted 901297 entries ]
```

```
## [1] "Class of var1:"
```

```
## [1] "character"
```

```
## [1] "First 100 elements of var1 (if applicable):"
```

```
##   [1] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [37] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
##  [73] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
```

```
## [1] "Random sample of 100 elements from var1 (if applicable):"
```

```
##   [1] "AK" "PA" "OK" "TX" "OK" "NJ" "DE" "CO" "GA" "ND" "MN" "KY" "OK" "MO" "NC" "MT" "NE" "TX" "IA" "OH" "SD" "AK" "TX" "ND" "NE" "VA" "MO" "ND" "TX" "IL" "KS" "TX" "OK" "NY" "NJ" "KS"
##  [37] "IA" "CO" "OK" "IA" "MA" "OH" "NV" "KS" "AL" "SC" "TX" "IA" "TX" "KS" "TX" "KS" "TN" "TX" "TX" "TN" "OK" "OH" "IA" "WI" "MO" "TN" "NC" "NJ" "TX" "GA" "NE" "TX" "CA" "FL" "TX" "CO"
##  [73] "SC" "NY" "SD" "LM" "TX" "VA" "TN" "KS" "NE" "FL" "UT" "OK" "NC" "IN" "PA" "WI" "SD" "LM" "TX" "IL" "CO" "LA" "FL" "LE" "OH" "OK" "VA" "NY"
```

```
## [1] "Length of var1:"
## [1] 902297
## [1] "Class of var1:"
## [1] "character"
## [1] "Structure of var1:"
##  chr [1:902297] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" ...
## [1] "Summary of var1:"
##    Length     Class      Mode 
##    902297 character character 
## [1] "Proportion of NA values in var1:"
## [1] 0
## [1] "Total count of NA values in var1:"
## [1] 0
## [1] "Substring of top 10 longest var1 (limited to 500 characters):"
##  [1] "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL" "AL"
## [1] "Data frame of 25 smallest unique char-limited values:"
##    var1_30 nchar
## 1       AL     2
## 2       AZ     2
## 3       AR     2
## 4       CA     2
## 5       CO     2
## 6       CT     2
## 7       DE     2
## 8       DC     2
## 9       FL     2
## 10      GA     2
## 11      HI     2
## 12      ID     2
## 13      IL     2
## 14      IN     2
## 15      IA     2
## 16      KS     2
## 17      KY     2
## 18      LA     2
## 19      ME     2
## 20      MD     2
## 21      MA     2
## 22      MI     2
## 23      MN     2
## 24      MS     2
## 25      MO     2
## [1] "Summary of nchar(var1, allowNA = TRUE):"
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##       2       2       2       2       2       2 
## [1] "Histogram of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.STATE_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.STATE_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##    AK    AL    AM    AN    AR    AS    AZ    CA    CO    CT    DC    DE    FL    GA    GM    GU    HI    IA    ID    IL    IN    KS    KY    LA    LC    LE    LH    LM    LO    LS    MA 
##  4391 22739  1879  3250 27102   257  6156 10780 20473  3294   437  1913 22124 25259  5337   306  2547 31069  4767 28488 21506 53440 22092 17323   274  1526   654  1347    70   262  5652 
##    MD    ME    MH    MI    MN    MO    MS    MT    NC    ND    NE    NH    NJ    NM    NV    NY    OH    OK    OR    PA    PH    PK    PM    PR    PZ    RI    SC    SD    SL    ST    TN 
##  8185  4524     1 17910 23609 35648 22192 14695 25351 14632 30271  3022  8075  7129  3139 21058 24922 46802  4821 22226    28    23     1  3015    96   839 17126 21727     7     1 21721 
##    TX    UT    VA    VI    VT    WA    WI    WV    WY    XX 
## 83728  4135 21189   338  3871  3312 19781  9099  7332     2 
## [1] "Unique values of var1:"
##  [1] "AL" "AZ" "AR" "CA" "CO" "CT" "DE" "DC" "FL" "GA" "HI" "ID" "IL" "IN" "IA" "KS" "KY" "LA" "ME" "MD" "MA" "MI" "MN" "MS" "MO" "MT" "NE" "NV" "NH" "NJ" "NM" "NY" "NC" "ND" "OH" "OK"
## [37] "OR" "PA" "RI" "SC" "SD" "TN" "TX" "UT" "VT" "VA" "WA" "WV" "WI" "WY" "PR" "AK" "ST" "AS" "GU" "MH" "VI" "AM" "LC" "PH" "GM" "PZ" "AN" "LH" "LM" "LE" "LS" "SL" "LO" "PM" "PK" "XX"
## [1] "Character count per element in var1:"
##    [1] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##   [91] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [181] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [271] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [361] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [451] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [541] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [631] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [721] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [811] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [901] 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
##  [991] 2 2 2 2 2 2 2 2 2 2
##  [ reached getOption("max.print") -- omitted 901297 entries ]
## [1] "Sorted var1:"
##    [1] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##   [37] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##   [73] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [109] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [145] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [181] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [217] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [253] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [289] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [325] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [361] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [397] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [433] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [469] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [505] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [541] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [577] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [613] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [649] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [685] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [721] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [757] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [793] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [829] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [865] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [901] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [937] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [973] "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK" "AK"
##  [ reached getOption("max.print") -- omitted 901297 entries ]
```
