---
title: "COUNTY Variable Analyses"
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






``` r
var1
```

```
##    [1]  97   3  57  89  43  77   9 123 125  57  43   9  73  49 107 103  97  57  57  57  47 121 127   9  25  33  93 127  59  97  77  73   9  81  21  27  73  23  93  73  67  67  21 113  67
##   [46]  31  45  81  15   5 109 113  33  73 103  83  73  57   9  63  73  21 123  63  33  57 117  47  47 103  21 125  21   3  73  45  31  31  31  45  73 117  33 103  89  33  71 127  49  61
##   [91]  33 119 133  73  73   7  57 107  39  39  67  21  25  73  99 101  51  87  69 129  21  21  97  97  97  57  43  75  63  59  93 103  95  43  67  89 101  75 103  25 131 101  85  35  99
##  [136]  85 101  41  13  35 101  35  35  39  13  41   5  97  81  59  47 107 125 117   9  75 127  43  59  63  65 125  47 125  73  49 123 103  79  29  27   9  95 103  57  33  21  35  59 109
##  [181] 109  45  23  97  53 101  57  73 103  33  79  79  83  89  43  43  95  71  89 101  73  73  21  21  55 107   1 101  75  73 103  69  77 101  43  67 127  47  73  31  97  97  97  97   3
##  [226] 121   7  73  73   7  47  49  47  47  47  73  73 101  57  47  97 119  31  31  73  25  99  73  97  97  97  71  33 105  95  25  49  73  13  13  61  23 125 103 121  27 101  73  51  91
##  [271] 125 113  33  57 127  43  95 123 101  73  97  53  97  89  95  53  53  53  53  67 113  97  31  73  73  73 109  89  77  73 101  55  89  89  69  73  73  97  45  61  53  15  65 105  15
##  [316]  21  37 123 119  29 105  39 109  69 127  35 121  73 101  73  55 121 121  43  95  55  73  73  71  49  33  33  57  93  67   3  67  87  87  85  39  89  97   0  73  73 105  89 101   3
##  [361] 127   7  45  69  49  97  73  73  73  97 101  25   3  31  73  55  19 127 107  43  57 103  59  83  89  89  93 133  71  73 123   7  89 103 121 125  69 117 117 121 125   1  85  93  93
##  [406]  57  73 115 115  73 115 113  97  69 105  73  53  33  89  33  97  97  89  89  43  73 117  49 103  59  77  73  65 133 133  23  43  49  49  95  19  85  95 103 103 125  97   0  71  73
##  [451] 115  47  15 121  21  21  29 123  85  97  97  97 125   0 103 125 121  33 125  43 125  35  13   5  97  97 109  13  11  73   3  39  13 113  33  79 107  93  33  77  15  81  33  83  83
##  [496]  95  23  73  89  71  49 127  45  97  97  97 117  73  39  97  89 101  75  17  73  89  73  73   7  69  97  43  41  83 103 103 115  33  45  89 107  73 125  73  33  89 125 125  33  51
##  [541]  81  47 101  69 113  43 103  73  73  65   3  85 107 127 127  91  73 105 115  21   0  85 121  15 125  89  89  89  49  43  19 103 125 125  47   5 133 127 127  73 117  73 117  95 103
##  [586]  89  89 103  73  73 117  73 121  31  69  39  95 103  55  59  33  77  77  77  83 115  55  59 125  49 121 103  59  59  49   0 101  89  97  67 115  91  15  77  33  79  89   3   0   0
##  [631]  97  89  15  89 113  97  99  73  97   3  97  23 103  89 103 119  73  73  89  45  45 129  77 103  89  61  89   5  33  59 127  43  95  63 101  95  89  99  67  69  69 125 127  73  33
##  [676]  33  77  33  79 133 107  73  19  89  53  33  43  43  43  79 115  39  39  37 115  59   0   0   9  73  55 121 117  73  73  97  75  19  93  45 125  73  45  69  97  73  81  53  35  91
##  [721] 101  69  33  97   3   3  53  23  21  37  75  57  73 103 127 117   1 125  73  73  47 121  73 109  13  41  11   0  99  23 105  73 119 109  41  11  43  49  97  33  73  19  19  33  77
##  [766]  73  73 115   0  55  75 125  55 127  17  81  53  97  91 129  89 133  95   3 117  93  55  69  97  97   0   0 115  41   3  15  55  55  97  63 129  67   5  57  65  73 125  17  35  73
##  [811]  73 117   0  59  59  89 121  55  47  71   0   5  89  89 117 115 121 111   5   5  43  33  73   3   0  83   0  29   0  29  43  83  17  25  97  69  81  79  73 109  73 103  51  71  97
##  [856]  79  99 127  73  53  41 101  53   5  69   9  29  93  59  83  87  69  69  97   3  93  57 125  73  73  43  15  63 131  73 101 111  17  17 109  35  69  81 109  25 109  79  83 125  73
##  [901]  73 117  47 109 117  47  61  73  91  73 129  99  59  89  77  77  83  77  55  29  73 109  99  73  73  35  81  81   1 101 113  99 109  31  45  69   5   5   5  97  97 101   3  53  61
##  [946]  69  61  97  53  47  31 113 113  81  81  77  57  73 117 117  73 117  73  31  33   0  47  47  55 127   0  55  43  43  35  73  97  87  57  89  75  77  33  89  71 133 121  73 129 129
##  [991]   3   3  31 115  99  91  17  31  45  67
##  [ reached getOption("max.print") -- omitted 901297 entries ]
```

``` r
class.var1 <- class(var1)
print("Class of var1:")
```

```
## [1] "Class of var1:"
```

``` r
print(class.var1)
```

```
## [1] "numeric"
```

``` r
print("First 100 elements of var1 (if applicable):")
```

```
## [1] "First 100 elements of var1 (if applicable):"
```

``` r
tryCatch({
  print(var1[1:min(100, length(var1))])
}, error = function(e) {
  print("Error: Failed to print the first 100 elements of var1.")
})
```

```
##   [1]  97   3  57  89  43  77   9 123 125  57  43   9  73  49 107 103  97  57  57  57  47 121 127   9  25  33  93 127  59  97  77  73   9  81  21  27  73  23  93  73  67  67  21 113  67
##  [46]  31  45  81  15   5 109 113  33  73 103  83  73  57   9  63  73  21 123  63  33  57 117  47  47 103  21 125  21   3  73  45  31  31  31  45  73 117  33 103  89  33  71 127  49  61
##  [91]  33 119 133  73  73   7  57 107  39  39
```

``` r
set.seed(123)

print("Random sample of 100 elements from var1 (if applicable):")
```

```
## [1] "Random sample of 100 elements from var1 (if applicable):"
```

``` r
tryCatch({
  print(sample(na.omit(str_sub(var1, end = 500)), size = min(100, length(na.omit(var1))), replace = FALSE))
}, error = function(e) {
  print("Error: Sampling failed. Check if var1 has enough valid elements.")
})
```

```
##   [1] "0"   "7"   "109" "375" "67"  "31"  "2"   "73"  "139" "79"  "157" "85"  "31"  "29"  "167" "11"  "149" "441" "69"  "101" "43"  "225" "241" "35"  "31"  "820" "189" "13"  "375" "43" 
##  [31] "55"  "347" "83"  "31"  "27"  "109" "197" "71"  "75"  "133" "0"   "131" "3"   "113" "29"  "9"   "77"  "75"  "305" "175" "57"  "177" "62"  "99"  "473" "151" "61"  "53"  "97"  "44" 
##  [61] "161" "163" "141" "21"  "251" "13"  "169" "29"  "95"  "127" "121" "37"  "7"   "10"  "103" "323" "373" "143" "139" "3"   "113" "1"   "35"  "99"  "59"  "165" "57"  "119" "23"  "643"
##  [91] "453" "181" "55"  "55"  "113" "167" "97"  "9"   "167" "7"
```

``` r
if (inherits(var1, c("numeric", "integer"))) {
  
  print("Summary of var1:")
  tryCatch(print(summary(var1)), error = function(e) {print("Error: summary() failed.")})
  
  print("Range of var1:")
  tryCatch(print(range(var1)), error = function(e) {print("Error: range() failed.")})
  
  print("Length of var1:")
  tryCatch(print(length(var1)), error = function(e) {print("Error: length() failed.")})
  
  print("Structure of var1:")
  tryCatch(str(var1), error = function(e) {print("Error: str() failed.")})
  
  print("Standard deviation of var1:")
  tryCatch(print(sd(var1)), error = function(e) {print("Error: sd() failed.")})
  
  print("Histogram of var1:")
  tryCatch(hist(var1[!is.na(var1)]), error = function(e) {print("Error: hist() failed.")})
  
  print("Boxplot of var1:")
  tryCatch(boxplot(var1), error = function(e) {print("Error: boxplot() failed.")})
  
  print("Table of var1:")
  tryCatch(print(table(var1)), error = function(e) {print("Error: table() failed.")})
  
  print("Proportion of NA values in var1:")
  tryCatch(print(mean(is.na(var1))), error = function(e) {print("Error: mean(is.na()) failed.")})
  
  print("Total count of NA values in var1:")
  tryCatch(print(sum(is.na(var1))), error = function(e) {print("Error: sum(is.na()) failed.")})
  
  print("Sorted var1:")
  tryCatch(print(sort(var1)), error = function(e) {print("Error: sort() failed.")})
  
  
} else if (inherits(var1, "character")) { 
  
  print("Length of var1:")
  tryCatch(print(length(var1)), error = function(e) { print("Error: length() failed.") })
  
  print("Class of var1:")
  tryCatch(print(class(var1)), error = function(e) { print("Error: class() failed.") })
  
  print("Structure of var1:")
  tryCatch(str(var1), error = function(e) { print("Error: str() failed.") })
  
  print("Summary of var1:")
  tryCatch(print(summary(var1)), error = function(e) { print("Error: summary() failed.") })
  
  print("Proportion of NA values in var1:")
  tryCatch(print(mean(is.na(var1))), error = function(e) { print("Error: mean(is.na()) failed.") })
  
  print("Total count of NA values in var1:")
  tryCatch(print(sum(is.na(var1))), error = function(e) { print("Error: sum(is.na()) failed.") })
  
  # Cálculos auxiliares com tryCatch para garantir segurança
  len.var1 <- tryCatch(length(var1), error = function(e) { print("Error: length(var1) failed.") })
  len.unique.var1 <- tryCatch(length(unique(var1)), error = function(e) { print("Error: length(unique(var1)) failed.") })
  nchar.var1 <- tryCatch(nchar(var1, allowNA = TRUE), error = function(e) { print("Error: nchar(var1, allowNA = TRUE) failed.") })
  ten.max.nchar.index <- tryCatch(order(nchar.var1, decreasing = TRUE)[1:10],
                                  error = function(e) { print("Error: order(nchar(var1)) failed.") })
  
  var1.30.char.limited <- tryCatch(unique(str_sub(var1, end = 30)),
                                   error = function(e) { print("Error: str_sub(var1, end = 30) failed.") })
  
  df.min.char <- tryCatch({
    df <- data.frame(var1_30 = var1.30.char.limited, 
                     nchar = nchar(var1.30.char.limited, allowNA = TRUE))
    df <- arrange(df, nchar) %>% slice(1:25)
    df
  }, error = function(e) { print("Error: constructing df.min.char failed.") })
  
  print("Substring of top 10 longest var1 (limited to 500 characters):")
  tryCatch(print(str_sub(var1[ten.max.nchar.index], end = 500)),
           error = function(e) { print("Error: str_sub() for ten.max.nchar.index failed.") })
  
  print("Data frame of 25 smallest unique char-limited values:")
  tryCatch(print(df.min.char), error = function(e) { print("Error: printing df.min.char failed.") })
  
  print("Summary of nchar(var1, allowNA = TRUE):")
  tryCatch(print(summary(nchar.var1)), error = function(e) { print("Error: summary(nchar(var1, allowNA = TRUE)) failed.") })
  
  print("Histogram of nchar(var1, allowNA = TRUE):")
  tryCatch(hist(nchar.var1), error = function(e) { print("Error: hist(nchar(var1, allowNA = TRUE)) failed.") })
  
  print("Boxplot of nchar(var1, allowNA = TRUE):")
  tryCatch(boxplot(nchar.var1), error = function(e) { print("Error: boxplot(nchar(var1, allowNA = TRUE)) failed.") })
  
  # Avaliações para testar se var1 é muito grande e pode causar problemas
  var1.unique.fraction <- tryCatch(len.unique.var1 / len.var1,
                                   error = function(e) { print("Error: computing unique fraction failed.") })
  
  cond1 <- tryCatch(var1.unique.fraction > 0.20,
                    error = function(e) { print("Error: evaluating cond1 failed.") })
  cond2 <- tryCatch(len.unique.var1 > 10000,
                    error = function(e) { print("Error: evaluating cond2 failed.") })
  max.char.var1 <- tryCatch(max(nchar.var1, na.rm = T),
                            error = function(e) { print("Error: max(nchar(var1, allowNA = TRUE)) failed.") })
  cond3 <- tryCatch(max.char.var1 > 300,
                    error = function(e) { print("Error: evaluating cond3 failed.") })
  
  tests <- tryCatch(all(cond1, cond2, cond3),
                    error = function(e) { print("Error: evaluating tests failed.") })
  
  if (identical(tests, TRUE)) {
    
    set.seed(12345)
    print("Random sample of 10000 elements from var1 (if applicable):")
    df.reduced <- tryCatch({
      sample(str_sub(var1, end = 100), size = 10000, replace = FALSE)
    }, error = function(e) { print("Error: Sampling 10000 failed. Check if var1 has enough valid elements.") })
    
    #df.reduced <- tryCatch(str_sub(df.reduced, end = 100),
    #                      error = function(e) { print("Error: str_sub() on df.reduced failed.") })
    
    df.reduced.tabled <- tryCatch(as.data.frame(table(df.reduced)),
                                  error = function(e) { print("Error: creating table from df.reduced failed.") })
    
    df.reduced.tabled$nchar <- tryCatch(nchar(as.character(df.reduced.tabled$df.reduced)),
                                        error = function(e) { print("Error: computing nchar for df.reduced.tabled failed.") })
    
    print("Data frame of reduced table arranged by nchar:")
    tryCatch(print(arrange(df.reduced.tabled, nchar)),
             error = function(e) { print("Error: arranging df.reduced.tabled failed.") })
    
    print("Table of character counts in df.reduced:")
    tryCatch(print(table(sort(nchar(df.reduced)))),
             error = function(e) { print("Error: table of nchar(df.reduced) failed.") })
  } else {
  
  print("Table of var1:")
  tryCatch(print(table(var1)), error = function(e) { print("Error: table(var1) failed.") })
  
  print("Unique values of var1:")
  tryCatch(print(unique(var1)), error = function(e) { print("Error: unique(var1) failed.") })
  
  print("Character count per element in var1:")
  tryCatch(print(nchar(var1, allowNA = TRUE)), error = function(e) { print("Error: nchar(var1, allowNA = TRUE) failed.") })
  
  print("Sorted var1:")
  tryCatch(print(sort(var1)), error = function(e) { print("Error: sort(var1) failed.") })
}
  
} else if (inherits(var1, "logical")) {
  
  print("Length of var1:")
  tryCatch(print(length(var1)), error = function(e) {print("Error: length() failed.")})
  
  print("Class of var1:")
  tryCatch(print(class(var1)), error = function(e) {print("Error: class() failed.")})
  
  print("Table of var1:")
  tryCatch(print(table(var1)), error = function(e) {print("Error: table() failed.")})
  
  print("Sum of TRUE values in var1:")
  tryCatch(print(sum(var1, na.rm = TRUE)), error = function(e) {print("Error: sum() failed.")})
  
  print("Mean of TRUE values in var1:")
  tryCatch(print(mean(var1, na.rm = TRUE)), error = function(e) {print("Error: mean() failed.")})
  
  print("Proportion of NA values in var1:")
  tryCatch(print(mean(is.na(var1))), error = function(e) {print("Error: mean(is.na()) failed.")})
  
  print("Total count of NA values in var1:")
  tryCatch(print(sum(is.na(var1))), error = function(e) {print("Error: sum(is.na()) failed.")})
  
} else if (inherits(var1, c("Date", "POSIXct", "POSIXlt"))) {
  
  print("Length of var1:")
  tryCatch(print(length(var1)), error = function(e) {print("Error: length() failed.")})
  
  print("Class of var1:")
  tryCatch(print(class(var1)), error = function(e) {print("Error: class() failed.")})
  
  print("Summary of var1:")
  tryCatch(print(summary(var1)), error = function(e) {print("Error: summary() failed.")})
  
  print("Range of var1:")
  tryCatch(print(range(var1, na.rm = TRUE)), error = function(e) {print("Error: range() failed.")})
  
  print("Table of var1:")
  tryCatch(print(table(var1)), error = function(e) {print("Error: table() failed.")})
  
  print("Weekdays of var1:")
  tryCatch(print(weekdays(var1)), error = function(e) {print("Error: weekdays() failed.")})
  
  print("Months of var1:")
  tryCatch(print(months(var1)), error = function(e) {print("Error: months() failed.")})
  
} else if (inherits(var1, c("factor", "ordered"))) {
  
  print("Length of var1:")
  tryCatch(print(length(var1)), error = function(e) {print("Error: length() failed.")})
  
  print("Class of var1:")
  tryCatch(print(class(var1)), error = function(e) {print("Error: class() failed.")})
  
  print("Structure of var1:")
  tryCatch(str(var1), error = function(e) {print("Error: str() failed.")})
  
  print("Summary of var1:")
  tryCatch(print(summary(var1)), error = function(e) {print("Error: summary() failed.")})
  
  print("Table of var1:")
  tryCatch(print(table(var1)), error = function(e) {print("Error: table() failed.")})
  
  print("Levels of var1:")
  tryCatch(print(levels(var1)), error = function(e) {print("Error: levels() failed.")})
  
  print("Unclass of var1:")
  tryCatch(print(unclass(var1)), error = function(e) {print("Error: unclass() failed.")})
  
  print("Is var1 ordered?")
  tryCatch(print(is.ordered(var1)), error = function(e) {print("Error: is.ordered() failed.")})
  
  print("Proportion of NA values in var1:")
  tryCatch(print(mean(is.na(var1))), error = function(e) {print("Error: mean(is.na()) failed.")})
  
  print("Total count of NA values in var1:")
  tryCatch(print(sum(is.na(var1))), error = function(e) {print("Error: sum(is.na()) failed.")})
  
} else {
  
  print("No recognized class found for var1.")
  
}
```

```
## [1] "Summary of var1:"
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##     0.0    31.0    75.0   100.6   131.0   873.0 
## [1] "Range of var1:"
## [1]   0 873
## [1] "Length of var1:"
## [1] 902297
## [1] "Structure of var1:"
##  num [1:902297] 97 3 57 89 43 77 9 123 125 57 ...
## [1] "Standard deviation of var1:"
## [1] 107.2765
## [1] "Histogram of var1:"
```

![](VarAnalysis/df.variable.analysis.COUNTY_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of var1:"
```

![](VarAnalysis/df.variable.analysis.COUNTY_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##     0     1     2     3     4     5     6     7     8     9    10    11    12    13    14    15    16    17    18    19    20    21    22    23    24    25    26    27    28    29    30 
##  6456 17810  3452 16220  2593 13847  2059 11858  1667 12938  1633 12530  1489 12467  1297 13858   977 13081  1327 14141  1243 11897  1115  9025  1036 11302   824 11535  1099 10438   801 
##    31    32    33    34    35    36    37    38    39    40    41    42    43    44    45    46    47    48    49    50    51    52    53    54    55    56    57    58    59    60    61 
## 12985   933 10332   891 11046   495  9614   777  8863   664  9772   880  9015   691  9657   635  8927   713  9656   584  8986   708  7931  1297  9069   412  9106   568  9725   747  7986 
##    62    63    64    65    66    67    68    69    70    71    72    73    74    75    76    77    78    79    80    81    82    83    84    85    86    87    88    89    90    91    92 
##   379  9018   389  8826   598  9120   468  8142   357 10718   723  9870   384  8274   379  9745   285  7924   298  8538   257  9203   270  8338  1171  8104   288  9497   272  8572   271 
##    93    94    95    96    97    98    99   100   101   102   103   104   105   106   107   108   109   110   111   112   113   114   115   116   117   118   119   120   121   122   123 
##  7949   136  8379   366  8142   246  8996   100  8473    74  8713    96  7936   133  7126    49  8455   163  8599   104  8929    54  6552   101  6025   120  8704    64  8349     4  6824 
##   124   125   126   127   128   129   130   131   132   133   134   135   136   137   138   139   140   141   142   143   144   145   146   147   148   149   150   151   152   153   154 
##     8  7935     8  6175    11  5955    51  5166    16  5861    14  5421    19  4827    17  5693    29  5244    73  5895   123  6047   113  4625    86  5100    40  4753    24  5689    26 
##   155   156   157   158   159   160   161   162   163   164   165   166   167   168   169   170   171   172   173   174   175   176   177   178   179   180   181   182   183   184   185 
##  4467    10  5045    48  3250     6  4226    67  5068   110  3744   101  4493   102  3800    14  3214    31  4077     9  2586     8  3136     5  3203    17  3460     7  3572     2  2607 
##   186   187   188   189   190   191   192   193   194   195   196   197   198   199   200   201   202   203   204   205   206   207   208   209   210   211   212   213   214   215   216 
##   154  2327     4  3088     6  2541    26  2436     1  2510     2  2274     1  1754     3  2602    26  1688    39  1069    31  1229    30  1162    35   789    41  1116    63  1009    45 
##   217   218   219   220   221   222   223   224   225   226   227   228   229   230   231   232   233   234   235   236   237   238   239   240   241   242   243   244   245   246   247 
##  1262    27   970    35   957    64   935    46   965    27   936     8   658   241   796    26   903    18   631    43   549    15   310    21   429    35   213    16   755    23   203 
##   248   249   250   251   252   253   254   255   256   257   258   259   261   262   263   264   265   266   267   269   270   271   273   275   277   279   281   283   285   287   289 
##   111   311   250   879    66   557    42   394    11   612   263   270   206     1   258     8   276    13   312   267    52   250   218   475   552   510   214   171   492   233   288 
##   291   293   295   297   299   301   303   305   307   309   311   313   315   317   319   321   322   323   325   327   329   330   331   333   335   337   338   339   340   341   342 
##   355   400   543   356   452   108  1095   539   356   842   183   322   293   308   223   363    24   175   258   102   597   151   207   180   546   392    71   391     2   474    50 
##   343   344   345   346   347   348   349   350   351   352   353   354   355   356   357   359   361   362   363   364   365   366   367   369   370   371   373   374   375   376   377 
##   177    32   264    28   418    72   453   145   171    47   332    89   722     7   387   288   274    66   594     2   373     2   703   268    83   592   241    31   950     2   132 
##   379   381   383   385   387   389   391   393   395   397   399   401   403   405   407   409   411   413   415   417   419   421   422   423   425   427   429   430   431   432   433 
##   148   912   155   150   320   285    96   229   136   155   348   383   119   120   171   230   162   113   331   186   368   237   133   679   145   130   291    59   242     8   162 
##   435   437   439   441   442   443   444   445   447   449   450   451   452   453   454   455   457   459   460   461   462   463   464   465   467   469   470   471   472   473   474 
##   100   338  1825   774    30   190    90   286   232   216   189   792   158   726    23   338   205   282   117   209    26   270    40   527   351   301    93   168    60   117     9 
##   475   477   479   481   483   485   487   489   491   493   495   497   499   501   502   503   504   505   506   507   508   509   510   511   512   513   514   515   516   517   518 
##   299   145   215   273   393   902   471    99   512   156   160   614   327   395   151   532    73   183    81   171    66    48   540    39    39    35    20    65    41    60    66 
##   519   520   521   522   523   524   525   526   527   528   529   530   531   532   533   534   535   536   537   538   539   540   541   542   543   545   547   548   550   552   555 
##   151   189    46    55    99    16    28    40    13    31    42   312   198   248   136   328   201   231   210    53    16    72    20    34    98     3     6     1   504   170   286 
##   557   560   563   564   570   572   575   577   580   590   595   597   600   610   620   630   631   632   633   634   640   643   644   645   646   650   651   652   654   655   656 
##     1    16     3     7    46    16    98     3    12    63    33     1    49   193    32   400    76   239    30    15    38    58    26    95   109   433   328    33     5   142   127 
##   657   658   660   665   669   670   671   673   675   676   677   678   680   683   685   690   700   710   712   720   725   730   735   740   741   742   743   744   745   746   750 
##     2    57    28     6     1   157    25     1    43    11     1    23    76    57    11    48   105   151     2    65     2   149    11   130   145    10    17    25    86    12    80 
##   755   760   765   766   770   775   777   779   780   790   800   810   820   830   840   843   844   845   846   847   848   849   850   853   856   867   868   869   870   873 
##    30   102     1     1   117    40     2     1     2    36   159   223    27   391    52    12    35    33    33    40     8    14    79   195    94    32    33    12     2     3 
## [1] "Proportion of NA values in var1:"
## [1] 0
## [1] "Total count of NA values in var1:"
## [1] 0
## [1] "Sorted var1:"
##    [1] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##   [91] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [181] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [271] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [361] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [451] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [541] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [631] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [721] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [811] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [901] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [991] 0 0 0 0 0 0 0 0 0 0
##  [ reached getOption("max.print") -- omitted 901297 entries ]
```
