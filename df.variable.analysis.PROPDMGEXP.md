---
title: "PROPDMGEXP Variable Analyses"
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
##    [1] "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "M" "M" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "M" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K"
##   [46] "K" "K" "K" "K" "K" "K" "K" "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  "M" ""  ""  ""  ""  ""  "K" "K" "K" "M" "M" ""  ""  ""  ""  ""  ""  ""  ""  ""  "K"
##   [91] ""  ""  ""  "M" ""  ""  ""  ""  "K" ""  ""  ""  "K" ""  "K" "K" "K" ""  "K" ""  ""  ""  "K" "K" ""  ""  ""  ""  ""  "K" "K" "K" "K" "K" "K" ""  ""  ""  ""  "K" "K" "K" "K" "K" "K"
##  [136] "K" "K" ""  "K" "K" "K" "K" "K" "K" "K" "K" "K" ""  "K" ""  "K" "K" ""  "K" ""  "K" "K" "K" "K" "K" "K" "K" "K" ""  "M" "K" "K" "K" "K" "K" "K" "K" "K" ""  "K" "K" "K" "K" "K" "" 
##  [181] "K" ""  "K" ""  "K" "K" ""  ""  "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" ""  ""  "K" "K" "K" "K" "K" ""  ""  ""  ""  ""  "K" "K" "K" ""  "K" ""  ""  ""  ""  "K" "K" ""  ""  ""  "" 
##  [226] "K" "K" "K" ""  ""  "K" ""  "K" ""  ""  ""  ""  ""  ""  "K" "K" ""  ""  ""  ""  ""  "K" ""  "K" "K" "K" "K" ""  ""  ""  "K" ""  ""  "K" "K" ""  ""  ""  ""  "K" ""  ""  "K" ""  "K"
##  [271] "K" "K" ""  "K" "K" "K" "K" "K" ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  "K" ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  "K" "K" ""  ""  "K" ""  ""  "K" "K" "K" "K" "" 
##  [316] "K" "K" ""  "K" "K" "K" "K" "K" "K" ""  ""  ""  ""  ""  ""  "K" ""  "K" "K" "K" ""  ""  ""  ""  ""  "K" ""  "K" "K" ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "" 
##  [361] ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  "K" "K" ""  "K" "K" "K" "M" ""  ""  "K" "M" "M" ""  "K" "K" ""  ""  "K" "K" ""  ""  ""  ""  ""  "K" "K" "K" ""  "K" "K" "K" "" 
##  [406] ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" "K" ""  "K" "K" ""  ""  ""  "K" "K" "K" "K" "K" "K" "K" ""  ""  ""  ""  ""  ""  ""  ""  "" 
##  [451] "K" ""  "K" "K" ""  ""  "K" "K" "K" ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  "K" "K" "K" ""  ""  ""  "K" ""  ""  "K" "K" "K" "K" "K" ""  "K" ""  "K" "K" ""  ""  ""  ""  "" 
##  [496] ""  ""  ""  ""  "K" "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  "K" "K" "K" ""  ""  ""  "K" ""  ""  ""  "K" "K" "K" "K" ""  ""  ""  ""  ""  "" 
##  [541] ""  ""  ""  "K" "K" "K" ""  ""  "K" "K" "K" "K" "K" "K" "K" ""  ""  "M" "K" "K" ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "M" ""  ""  "" 
##  [586] ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  "K" "K" "K" ""  "K" ""  "" 
##  [631] "K" ""  "K" "K" ""  ""  "K" ""  ""  "K" ""  ""  "M" "M" ""  "K" "K" ""  "K" "K" ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K"
##  [676] ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "" 
##  [721] ""  ""  ""  "K" "K" "K" "K" "K" "M" "M" ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  "K" "K" "K" "K" ""  ""  ""  ""  "K" ""  "K" "K" "K" "K" ""  ""  ""  ""  ""  ""  ""  "" 
##  [766] ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  "K" ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  "K" "K" "K" ""  ""  ""  "K" ""  ""  ""  "K" ""  ""  "K" "K" "" 
##  [811] ""  ""  ""  ""  ""  ""  ""  "K" "K" ""  ""  ""  "K" "K" "K" ""  ""  "K" ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  "K" ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  "" 
##  [856] ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" "K" "K" "K" ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  "K" ""  "K" "K" ""  ""  ""  "K" ""  "K" "K" "K" ""  ""  ""  "K"
##  [901] ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "" 
##  [946] ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" "K"
##  [991] "K" "K" "K" ""  "K" "K" "K" "K" "K" "K"
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
## [1] "character"
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
##   [1] "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "M" "M" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "M" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K"
##  [46] "K" "K" "K" "K" "K" "K" "K" "K" ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  ""  "K" ""  "M" ""  ""  ""  ""  ""  "K" "K" "K" "M" "M" ""  ""  ""  ""  ""  ""  ""  ""  ""  "K"
##  [91] ""  ""  ""  "M" ""  ""  ""  ""  "K" ""
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
##   [1] ""  "K" ""  "K" ""  ""  "K" "K" ""  ""  "K" ""  ""  ""  ""  "K" "K" ""  "K" "K" ""  ""  "K" ""  "K" "K" ""  ""  "K" "K" ""  "K" "K" "K" "K" "K" ""  ""  ""  ""  ""  "K" ""  ""  "K"
##  [46] ""  "K" "K" ""  "K" ""  ""  ""  ""  "K" "K" ""  ""  ""  "K" "K" "K" "K" ""  ""  ""  "K" "K" ""  ""  ""  "K" ""  "K" ""  "K" "K" "K" ""  ""  ""  "K" ""  ""  ""  ""  ""  ""  ""  "K"
##  [91] ""  "K" "K" ""  ""  ""  "K" ""  "K" "K"
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
## [1] "Length of var1:"
## [1] 902297
## [1] "Class of var1:"
## [1] "character"
## [1] "Structure of var1:"
##  chr [1:902297] "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "M" "M" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "K" "M" "K" "K" "K" "K" "K" "K" "K" ...
## [1] "Summary of var1:"
##    Length     Class      Mode 
##    902297 character character 
## [1] "Proportion of NA values in var1:"
## [1] 0
## [1] "Total count of NA values in var1:"
## [1] 0
## [1] "Substring of top 10 longest var1 (limited to 500 characters):"
##  [1] "K" "K" "K" "K" "K" "K" "K" "K" "K" "K"
## [1] "Data frame of 25 smallest unique char-limited values:"
##    var1_30 nchar
## 1              0
## 2        K     1
## 3        M     1
## 4        B     1
## 5        m     1
## 6        +     1
## 7        0     1
## 8        5     1
## 9        6     1
## 10       ?     1
## 11       4     1
## 12       2     1
## 13       3     1
## 14       h     1
## 15       7     1
## 16       H     1
## 17       -     1
## 18       1     1
## 19       8     1
## [1] "Summary of nchar(var1, allowNA = TRUE):"
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##  0.0000  0.0000  0.0000  0.4836  1.0000  1.0000 
## [1] "Histogram of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.PROPDMGEXP_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.PROPDMGEXP_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##             -      ?      +      0      1      2      3      4      5      6      7      8      B      h      H      K      m      M 
## 465934      1      8      5    216     25     13      4      4     28      4      5      1     40      1      6 424665      7  11330 
## [1] "Unique values of var1:"
##  [1] "K" "M" ""  "B" "m" "+" "0" "5" "6" "?" "4" "2" "3" "h" "7" "H" "-" "1" "8"
## [1] "Character count per element in var1:"
##    [1] 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 1 0 0 0 0 0 1 1 1 1 1 0 0 0 0 0 0 0 0 0 1
##   [91] 0 0 0 1 0 0 0 0 1 0 0 0 1 0 1 1 1 0 1 0 0 0 1 1 0 0 0 0 0 1 1 1 1 1 1 0 0 0 0 1 1 1 1 1 1 1 1 0 1 1 1 1 1 1 1 1 1 0 1 0 1 1 0 1 0 1 1 1 1 1 1 1 1 0 1 1 1 1 1 1 1 1 1 0 1 1 1 1 1 0
##  [181] 1 0 1 0 1 1 0 0 1 1 1 1 1 1 1 1 1 1 0 0 1 1 1 1 1 0 0 0 0 0 1 1 1 0 1 0 0 0 0 1 1 0 0 0 0 1 1 1 0 0 1 0 1 0 0 0 0 0 0 1 1 0 0 0 0 0 1 0 1 1 1 1 0 0 0 1 0 0 1 1 0 0 0 0 1 0 0 1 0 1
##  [271] 1 1 0 1 1 1 1 1 0 0 0 1 0 0 0 0 0 0 0 0 1 0 1 0 0 0 1 0 0 0 0 0 0 1 1 0 0 1 0 0 1 1 1 1 0 1 1 0 1 1 1 1 1 1 0 0 0 0 0 0 1 0 1 1 1 0 0 0 0 0 1 0 1 1 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [361] 0 0 0 0 0 0 0 0 0 0 0 1 0 1 1 0 1 1 1 1 0 0 1 1 1 0 1 1 0 0 1 1 0 0 0 0 0 1 1 1 0 1 1 1 0 0 0 0 0 0 0 1 0 0 0 1 0 0 0 0 0 0 0 0 0 0 1 1 0 1 1 0 0 0 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0
##  [451] 1 0 1 1 0 0 1 1 1 0 0 0 0 0 0 0 1 0 0 0 0 1 1 1 0 0 0 1 0 0 1 1 1 1 1 0 1 0 1 1 0 0 0 0 0 0 0 0 0 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 1 1 1 0 0 0 1 0 0 0 1 1 1 1 0 0 0 0 0 0
##  [541] 0 0 0 1 1 1 0 0 1 1 1 1 1 1 1 0 0 1 1 1 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 1 0 0 0 0 0 1 0 0 0 0 1 1 1 0 1 0 0
##  [631] 1 0 1 1 0 0 1 0 0 1 0 0 1 1 0 1 1 0 1 1 0 0 0 0 0 0 0 0 1 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 1 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
##  [721] 0 0 0 1 1 1 1 1 1 1 0 0 0 0 0 1 0 0 0 0 0 0 0 1 1 1 1 0 0 0 0 1 0 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 1 0 0 0 0 1 0 0 0 0 0 1 1 1 0 0 0 1 0 0 0 1 0 0 1 1 0
##  [811] 0 0 0 0 0 0 0 1 1 0 0 0 1 1 1 0 0 1 0 0 0 0 0 1 0 0 0 0 0 0 1 0 0 1 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 0 0 0 0 1 0 0 0 0 0 0 0 0 1 0 1 0 1 1 0 0 0 1 0 1 1 1 0 0 0 1
##  [901] 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1
##  [991] 1 1 1 0 1 1 1 1 1 1
##  [ reached getOption("max.print") -- omitted 901297 entries ]
## [1] "Sorted var1:"
##    [1] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##   [61] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [121] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [181] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [241] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [301] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [361] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [421] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [481] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [541] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [601] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [661] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [721] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [781] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [841] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [901] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [961] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [ reached getOption("max.print") -- omitted 901297 entries ]
```
