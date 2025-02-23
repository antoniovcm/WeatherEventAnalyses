---
title: "MAG Variable Analyses"
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
##    [1]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##   [46]   0   0   0   0   0   0   0   0   0  75 200   0 100   0   0 175 275  75   0   0   0 200   0   0   0   0  60   0  75  52   0   0   0   0   0   0 200  67   0   0   0   0 250 200   0
##   [91]   0 200   0   0  60   0   0   0   0 200   0   0   0  65   0   0   0   0   0 100  75 100   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 200   0   0   0   0   0   0
##  [136]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0  65   0   0   0   0   0   0   0   0   0   0 175   0   0   0   0   0   0   0   0   0 175   0   0   0   0   0   0
##  [181]   0 175   0  71   0   0  75 200   0   0   0   0   0   0   0   0   0   0  65  75   0   0   0   0   0 100  75  75 150 175   0   0   0 175   0   0   0   0 300   0   0 200 100  60  80
##  [226]   0   0   0   0   0   0   0   0 275   0  64  63   0   0   0   0   0 175   0 300   0   0   0   0   0   0   0  75  75   0   0 200   0   0   0   0   0   0   0   0   0  53   0   0   0
##  [271]   0   0   0   0   0   0   0   0   0 200  65   0   0   0  53   0   0  75   0   0   0  58   0 175  51 175   0   0   0  61  56 250 175   0   0  50  75   0   0   0   0   0   0   0   0
##  [316]   0   0   0   0   0   0   0   0   0   0  60   0  50  75  50   0   0   0   0   0   0 150  50   0 150   0 100   0   0 100   0   0 175 300   0   0  75  87 100   0  62   0   0  50  70
##  [361]   0   0  50  58   0   0  63  50  51   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0  60   0   0   0 175   0   0  85   0   0  75   0   0   0   0  75   0   0   0 175
##  [406]   0   0   0   0  50   0   0  62  50   0   0   0  58  65   0 175 100 100  50 175   0   0   0   0   0   0  55   0   0   0   0   0   0   0   0   0   0   0   0   0  55 100  86 100 200
##  [451]   0 200   0   0 100   0   0   0   0  75   0   0  50   0   0  55   0  55  50   0  60   0   0   0  75  55   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 200  55 100  70
##  [496]   0 100  55  53   0   0   0 100 175 150 200   0 125   0  75  50   0   0   0 175   0   0   0   0   0   0   0   0 200 175 175   0   0  52   0   0   0   0   0   0   0   0  50   0 175
##  [541]   0  56   0   0   0   0   0   0   0   0   0   0   0   0   0   0  54   0   0   0   0   0   0   0   0 125 175 150 175   0  75   0  75   0   0 175 175 175  50 175   0   0   0   0   0
##  [586]   0   0   0   0   0   0   0   0   0   0   0  75   0 175   0   0   0   0   0  75   0   0   0   0   0   0   0   0   0   0 175 100   0   0   0  75   0  75   0   0   0  50   0   0   0
##  [631]   0 175   0   0 275   0   0  65   0   0 125   0   0   0   0   0   0   0   0   0   0   0   0   0  60  75  57   0   0   0   0   0   0 100  75 200  50 200   0  52  50 175   0 100   0
##  [676]  55   0   0   0   0  75 125   0  50   0 100 175  52   0   0   0 175   0   0   0 175 175   0 175   0   0   0   0 100   0   0   0   0  55  52   0   0   0   0   0   0   0   0   0   0
##  [721]  53   0  50   0   0   0   0   0   0   0   0   0   0 175   0   0   0 100   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 100   0  60 175   0   0 175
##  [766]  52  52  52   0   0  75   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0  50   0 150 175   0   0   0   0   0   0   0  51   0   0   0   0  75   0 100   0   0   0 175
##  [811] 100 150  75   0   0  51   0   0   0   0  61   0   0   0   0   0   0   0 175   0   0  60 100   0   0 200 275 175  50   0   0   0   0   0 175 100   0   0   0  52  75   0   0   0   0
##  [856]   0   0   0   0   0   0  58   0   0  55   0   0   0   0   0   0 175 200   0   0   0   0  50   0 175   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0  50   0
##  [901]   0   0  75   0 100   0   0   0   0  75 200 200 100  75   0   0   0   0  50   0  75   0   0 175 175   0   0   0 200 300 100  86  51  70  53   0   0   0 175   0   0 175   0   0   0
##  [946]  50   0   0   0   0  65 175   0   0   0   0  52 175   0   0 175   0 175   0  53  52  75   0   0 175  50   0   0 175   0  75 175 175   0   0 100   0   0   0   0   0   0   0   0   0
##  [991]   0   0   0  75   0   0   0   0   0   0
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
##   [1]   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0
##  [46]   0   0   0   0   0   0   0   0   0  75 200   0 100   0   0 175 275  75   0   0   0 200   0   0   0   0  60   0  75  52   0   0   0   0   0   0 200  67   0   0   0   0 250 200   0
##  [91]   0 200   0   0  60   0   0   0   0 200
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
##   [1] "0"   "0"   "0"   "175" "175" "60"  "0"   "100" "75"  "52"  "0"   "175" "54"  "75"  "75"  "1"   "175" "175" "63"  "57"  "75"  "45"  "0"   "0"   "0"   "0"   "100" "0"   "63"  "50" 
##  [31] "60"  "50"  "0"   "78"  "0"   "100" "75"  "88"  "88"  "150" "0"   "50"  "56"  "75"  "50"  "0"   "1"   "88"  "175" "0"   "56"  "61"  "50"  "0"   "75"  "60"  "75"  "0"   "0"   "0"  
##  [61] "0"   "2"   "64"  "50"  "175" "0"   "0"   "0"   "0"   "175" "175" "0"   "50"  "0"   "52"  "1"   "1"   "60"  "75"  "75"  "75"  "0"   "75"  "88"  "0"   "0"   "0"   "75"  "100" "50" 
##  [91] "0"   "0"   "88"  "175" "0"   "35"  "0"   "71"  "52"  "0"
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
##     0.0     0.0    50.0    46.9    75.0 22000.0 
## [1] "Range of var1:"
## [1]     0 22000
## [1] "Length of var1:"
## [1] 902297
## [1] "Structure of var1:"
##  num [1:902297] 0 0 0 0 0 0 0 0 0 0 ...
## [1] "Standard deviation of var1:"
## [1] 61.9133
## [1] "Histogram of var1:"
```

![](VarAnalysis/df.variable.analysis.MAG_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of var1:"
```

![](VarAnalysis/df.variable.analysis.MAG_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##      0      1      2      3      4      5      6      7      8      9     10     11     12     15     17     18     19     20     22     23     24     25     26     27     28     29 
## 366676  32252   8777   1360    195     61     24      7     21      7      4      2      1      2      1      2      1      3      9      2      4     62     18     11     26      9 
##     30     31     32     33     34     35     36     37     38     39     40     41     42     43     44     45     46     47     48     49     50     51     52     53     54     55 
##    135     48     48     39   1482   3769   1262   1100    833   1559   1869    637    570   1491    475   1252    379    328    590    412  71880   4253  47411   5178   4071  17779 
##     56     57     58     59     60     61     62     63     64     65     66     67     68     69     70     71     72     73     74     75     76     77     78     79     80     81 
##  11648   3955   2639   1522  15530  14680   1647   1482    865   7037    635    571    692   1218   6096    379    359    271    704  84595    243    170    994     93    921     97 
##     82     83     84     85     86     87     88     89     90     91     92     93     94     95     96     97     98     99    100    101    102    103    104    105    106    107 
##    129    214     64    265     79    594  30106     44    299     59     32     26     17     54    101     20     24     15  55400      7      7      8     31      7     13      4 
##    108    109    110    111    112    113    114    115    116    117    118    119    120    121    122    123    124    125    126    127    130    131    132    133    134    135 
##      6     15     27      7     18     18      1     10      2      2      2      1     13      1      2      2      2   6361      3      1      7      2      1      2      1      1 
##    137    138    139    140    141    143    144    145    149    150    160    163    165    166    167    170    174    175    176    180    185    188    190    195    199    200 
##      1      5      3      5      1      1      1      1      1   7988      6      1      3      2      1      3      4  46645      3      2      2      5      2      1      1   5069 
##    210    213    220    225    234    237    238    240    244    250    259    260    263    270    272    275    278    280    285    290    300    310    320    325    335    338 
##      1      1      2    208      1      1      1      2      1   2523      1      2      2      3      1   5305      1      1      1      1   1288      1      1     23      1      1 
##    340    350    360    362    375    380    390    396    400    420    425    430    435    438    450    460    475    498    500    524    525    526    536    550    564    565 
##      1    224      1      1     27      2      1      1    476      1    158      1      1      1    581      1     10      1     63      1      2      1      1      7      1      1 
##    600    613    650    688    700    750    800    900    999   1000   1155   1233   1500   2750   3430   3740   5000  22000 
##     15      1      1      1      3      2      7      1      2      1      2      1      1      1      1      1      1      1 
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
