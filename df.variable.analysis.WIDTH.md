---
title: "WIDTH Variable Analyses"
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
##    [1] 100 150 123 100 150 177  33  33 100 100 400 400 200 400 440 100 200  50  50  50 167 867  50  33 300  20 300 100 220  10 200  37 100  33 100 440  33 100  67  33  33  33 167 880 100
##   [46] 100 100 100 100 100  83  33 200   0   0   0   0   0   0   0   0   0   0   0   0   0   0  50   0 200   0   0   0   0   0 100 167 167 100 100   0   0   0   0   0   0   0   0   0  20
##   [91]   0   0   0 200   0   0   0   0  83   0   0   0  33   0 100 100 100   0  33   0   0   0  67  33   0   0   0   0   0  33 100 200 200  33  33   0   0   0   0 100 100 100 117 440 100
##  [136]  50  50   0 133 133 167  33 200 200 200  33 100   0 133   0 100  33   0  50   0  33 200  33  33  33  33  33  33   0 100  33  33  33  33  33  33 100 100   0  33  33  33  33 440   0
##  [181] 200   0  67   0  10 200   0   0 100 100 100 100  50  33 200  33 100 100   0   0 300 100  33 100  33   0   0   0   0   0  50 200  33   0  33   0   0   0   0 150  33   0   0   0   0
##  [226]  33 100 440   0   0 200   0  50   0   0   0   0   0   0   3  33   0   0   0   0   0  50   0  33 100 100  33   0   0   0  33   0   0  33  33   0   0   0   0  33   0   0  33   0  33
##  [271]  33  33   0  33  33 200 200  33   0   0   0  33   0   0   0   0   0   0   0   0 167   0  33   0   0   0  33   0   0   0   0   0   0  33  33   0   0  33   0   0  33 200 150 100   0
##  [316] 150  33   0  33  33 100  33  33  33   0   0   0   0   0   0 250   0  33  33 100   0   0   0   0   0  33   0  33  33   0 100   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [361]   0   0   0   0   0   0   0   0   0   0   0  33   0  33 667   0  33  33 440 880   0   0  33  33  33   0 333 333   0   0  33 100   0   0   0   0   0  33  33  33   0 600 400  33   0
##  [406]   0   0   0   0   0   0  33   0   0   0  33   0   0   0   0   0   0   0   0   0   0 100  33   0  33  33   0   0   0 267  33  50  33  33  33  33   0   0   0   0   0   0   0   0   0
##  [451]  33   0  33  33   0   0  33  33  33   0   0   0   0   0   0   0  33   0   0   0   0  33 100  33   0   0   0  33   0   0 100 300  33  33  33   0 100   0  33  33   0   0   0   0   0
##  [496]   0   0   0   0  50  50   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 100   0  33  33  33   0   0   0  33   0   0   0 150  33 150  33   0   0   0   0   0   0
##  [541]   0   0   0  33  33  33   0   0  33 100  33  50  33  33 440   0   0 200  33  33   0   0   0  33   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 200   0   0   0
##  [586]   0   0   0   0   0   0   0  33   0   0   0   0   0   0   0   0   0   0   0   0   0   0  33   0   0   0   0  33   0   0   0   0   0  33   0   0   0   0 100  33  33   0  33   0   0
##  [631]  33   0  33  83   0   0 300   0   0  33   0   0 300 300   0  33  33   0  33 200   0   0   0   0   0   0   0   0  33   0   0   0  33   0   0   0   0   0   0   0   0   0   0   0  33
##  [676]   0   0   0   0   0   0   0   0   0  33   0   0   0   0  33   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [721]   0   0   0 400 400 400 400  33 400 400   0   0   0   0   0  33   0   0   0   0   0   0   0  33 500 500 500   0   0   0   0  33   0  33  33  33  50   0   0   0   0   0   0   0   0
##  [766]   0   0   0   0   0   0   0   0   0   0   0   0   0   0  33   0   0   0  33   0   0   0   0  37   0   0   0   0   0  33 100 100   0   0   0  33   0   0   0  33   0   0 200  33   0
##  [811]   0   0   0   0   0   0   0 200 300   0   0   0  33  50 300   0   0  33   0   0   0   0   0  33   0   0   0   0   0   0  33   0   0  33   0   0   0   0   0   0   0  33   0   0   0
##  [856]   0   0   0   0   0   0   0   0   0   0  33  33 750 750   0   0   0   0  33   0   0   0   0   0   0   0   0  50   0  50   0  33  50   0   0   0  33   0  33 100  33   0   0   0 300
##  [901]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 200 300   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [946]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0  33   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 200 200
##  [991] 100 150 100   0 100 100  50 100 100 200
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
##   [1] 100 150 123 100 150 177  33  33 100 100 400 400 200 400 440 100 200  50  50  50 167 867  50  33 300  20 300 100 220  10 200  37 100  33 100 440  33 100  67  33  33  33 167 880 100
##  [46] 100 100 100 100 100  83  33 200   0   0   0   0   0   0   0   0   0   0   0   0   0   0  50   0 200   0   0   0   0   0 100 167 167 100 100   0   0   0   0   0   0   0   0   0  20
##  [91]   0   0   0 200   0   0   0   0  83   0
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
##   [1] "0"   "33"  "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "25"  "150" "0"   "0"   "20"  "0"   "0"  
##  [31] "0"   "0"   "440" "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"  
##  [61] "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"  
##  [91] "0"   "200" "0"   "0"   "30"  "0"   "0"   "0"   "0"   "0"
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
##     Min.  1st Qu.   Median     Mean  3rd Qu.     Max. 
##    0.000    0.000    0.000    7.503    0.000 4400.000 
## [1] "Range of var1:"
## [1]    0 4400
## [1] "Length of var1:"
## [1] 902297
## [1] "Structure of var1:"
##  num [1:902297] 100 150 123 100 150 177 33 33 100 100 ...
## [1] "Standard deviation of var1:"
## [1] 61.57136
## [1] "Histogram of var1:"
```

![](VarAnalysis/df.variable.analysis.WIDTH_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of var1:"
```

![](VarAnalysis/df.variable.analysis.WIDTH_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##      0      1      2      3      4      5      6      7      8      9     10     11     12     13     14     15     16     17     18     20     22     23     24     25     27     30 
## 841747     83     14    341      3    200      7    350     19      2   4646      2      7    445      2    274      2   1058      4   3687      1    424      3   2344    452   3632 
##     31     33     34     35     37     40     43     45     47     50     53     55     57     60     63     65     66     67     70     73     75     77     80     83     85     86 
##      1  10157      2    134     67   1678     31     26     11   8258     16     72     21    632     19     22      6    370    351    308   1437    293    403     69     12      1 
##     87     90     93     97    100    103    105    107    108    110    115    117    120    123    125    127    128    130    133    135    137    140    143    146    147    150 
##     10     95      3      2   6187      1      1      3      1    127      1     22    110     32    150     33      1     26     76      2      2     20      4      1      6   1627 
##    160    163    165    167    170    173    175    176    177    180    183    187    190    193    200    207    210    213    215    216    217    220    223    225    227    230 
##     19      4      1     97     15     17     56      5     45     25     13      1      1      1   2557      1      9      1      1      1      4    196      6     15      1      7 
##    233    235    240    243    250    253    265    267    270    275    277    280    283    290    293    300    313    315    317    320    325    327    330    333    335    340 
##     22      1      4      3    530      1      2     26      6     13      4     11      8      2      2   1214      3      1      2      8      2      1     13     73      1      3 
##    350    352    353    360    366    367    370    373    375    380    399    400    417    420    425    427    430    433    440    447    448    450    464    467    470    473 
##    165      6      2      5      1      4      2      1      4      1      1    812     25      2      3      2      6      7    754      3      5     72      1      4      1      1 
##    475    480    493    500    516    517    525    527    528    530    533    550    567    575    580    581    583    586    587    590    600    613    647    650    660    666 
##      1      2      1    563      1      2      1      7      7     10      8     29      3      9     11      3      1      1     11      1    177      1      2     12     22      1 
##    667    675    700    704    713    715    733    750    760    770    774    790    800    813    817    830    833    847    850    860    865    867    870    875    880    883 
##     19      1     93      6      1      2      5     18      1      1      2      1    217      1      1      1     33      3     17      3      1     12      3      2    570      3 
##    895    900    910    915    950    970    975    980   1000   1050   1056   1075   1087   1100   1133   1160   1167   1170   1175   1200   1220   1223   1230   1232   1233   1235 
##      1     61      2      1      1      2      1      1    105     12     16      1      2     15      2      1      1      1      7     35      1      3     12      4      1      1 
##   1250   1260   1300   1320   1330   1333   1350   1370   1400   1407   1408   1410   1417   1430   1500   1515   1533   1550   1583   1600   1615   1667   1700   1707   1733   1750 
##     11      2     26    114      1      5      4      1     15      7      7      3      1      2     29      1      2      1      4     11      1      3      9      1      2      2 
##   1760   1790   1800   1883   1900   1920   1935   1936   2000   2100   2110   2113   2200   2288   2333   2460   2500   2550   2600   2630   2640   2667   2815   2900   2933   3000 
##    117      3      6      1      1      1      1      3     10      2      2      1     15      1      1      1      5      1      3      2     10      1      1      1      1      3 
##   3080   3170   3330   3344   3520   3872   4400 
##      1      1      4      1      1      1      1 
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
