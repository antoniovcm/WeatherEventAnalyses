---
title: "PROPDMG Variable Analyses"
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
##    [1]  25.00   2.50  25.00   2.50   2.50   2.50   2.50   2.50  25.00  25.00   2.50   2.50 250.00   0.00  25.00  25.00  25.00  25.00  25.00  25.00  25.00   2.50   2.50  25.00  25.00
##   [26]  25.00  25.00  25.00  25.00   2.50   2.50   2.50  25.00   2.50  25.00 250.00   2.50  25.00   2.50  25.00   2.50  25.00   2.50  25.00  25.00   0.03  25.00 250.00 250.00   2.50
##   [51]   2.50  25.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   2.50   0.00   0.00   0.00   0.00   0.00
##   [76]   2.50   2.50  25.00   2.50   2.50   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   2.50   0.00   0.00   0.00   0.00  25.00   0.00
##  [101]   0.00   0.00   2.50   0.00   0.25   0.25   0.25   0.00   0.25   0.00   0.00   0.00  25.00   0.03   0.00   0.00   0.00   0.00   0.00  25.00 250.00   0.25   0.25 250.00   2.50
##  [126]   0.00   0.00   0.00   0.00   2.50  25.00   0.00  25.00 250.00 250.00 250.00 250.00   0.00 250.00  25.00   2.50   2.50 250.00 250.00 250.00   0.00  25.00   0.00   2.50   0.00
##  [151]  25.00 250.00   0.00  25.00   0.00   2.50  25.00 250.00  25.00 250.00 250.00  25.00  25.00   0.00   2.50  25.00  25.00  25.00   2.50  25.00  25.00 250.00 250.00   0.00   2.50
##  [176]  25.00 250.00   2.50   2.50   0.00  25.00   0.00 250.00   0.00  25.00  25.00   0.00   0.00   2.50 250.00 250.00  25.00 250.00  25.00 250.00  25.00 250.00 250.00   0.00   0.00
##  [201]  25.00  25.00   2.50  25.00  25.00   0.00   0.00   0.00   0.00   0.00  25.00   2.50  25.00   0.00  25.00   0.00   0.00   0.00   0.00  25.00   2.50   0.00   0.00   0.00   0.00
##  [226]   2.50   0.00 250.00   0.00   0.00   0.25   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.25   2.50   0.00   0.00   0.00   0.00   0.00  25.00   0.00   2.50  25.00
##  [251] 250.00   2.50   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00   0.00   0.00   0.00   0.00  25.00 250.00  25.00   0.00 250.00 250.00
##  [276] 250.00 250.00  25.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00 250.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00
##  [301]   0.00   0.00   0.00   2.50  25.00   0.00   0.00   2.50   0.00   0.00 250.00 250.00  25.00 250.00   0.00   2.50  25.00   0.00  25.00   2.50  25.00   2.50  25.00  25.00   0.00
##  [326]   0.00   0.00   0.00   0.00   0.00 250.00   0.00  25.00  25.00  25.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00  25.00 250.00   0.00 250.00   0.00   0.00   0.00   0.00
##  [351]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   2.50   0.00 250.00 250.00
##  [376]   0.00  25.00  25.00  25.00   2.50   0.00   0.00  25.00   2.50   2.50   0.00 250.00   0.25   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.25  25.00  25.00
##  [401]   0.00 250.00 250.00 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00
##  [426]   0.00 250.00  25.00   0.00 250.00 250.00   0.00   0.00   0.00 250.00  25.00 250.00 250.00  25.00  25.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00
##  [451]  25.00   0.00  25.00  25.00   0.00   0.00  25.00  25.00 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   2.50  25.00   2.50   0.00
##  [476]   0.00   0.00  25.00   0.00   0.00  25.00  25.00   2.50  25.00  25.00   0.00 250.00   0.00 250.00 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00
##  [501] 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   2.50   0.00   0.00  25.00  25.00   0.00   0.00
##  [526]   0.00  25.00   0.00   0.00   0.00 250.00  25.00 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   2.50 250.00   0.00   0.00  25.00 250.00
##  [551]  25.00  25.00  25.00  25.00 250.00   0.00   0.00   2.50  25.00  25.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00
##  [576]   0.00   0.00   0.00   0.00   0.00   0.00   2.50   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00
##  [601]   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.25   0.00   0.00   0.00   0.00 250.00 250.00
##  [626] 250.00   0.00  25.00   0.00   0.00   2.50   0.00 250.00 250.00   0.00   0.00 250.00   0.00   0.00 250.00   0.00   0.00   2.50   2.50   0.00  25.00  25.00   0.00 250.00 250.00
##  [651]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00   0.00   0.00   0.00 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.25
##  [676]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   2.50   0.00   0.00   0.00   0.00 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00
##  [701]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00 250.00
##  [726] 250.00 250.00  25.00   2.50   2.50   0.00   0.00   0.00   0.00   0.00 250.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00 250.00 250.00 250.00   0.00   0.00   0.00
##  [751]   0.00  25.00   0.00   2.50  25.00  25.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00
##  [776]   0.00   0.00   0.00   0.00   2.50   0.00   0.00   0.00   0.25   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.03 250.00 250.00   0.00   0.00   0.00
##  [801]  25.00   0.00   0.00   0.00  25.00   0.00   0.00 250.00   0.25   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00 250.00   0.00   0.00   0.00   0.00  25.00  25.00
##  [826]   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00   0.00   0.00   0.25   0.00   0.00   0.00   0.00   0.00   0.00
##  [851]   0.00  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00  25.00  25.00  25.00   0.00   0.00   0.00   0.00  25.00   0.00
##  [876]   0.00   0.00   0.00   0.00   0.00   0.00   0.00 250.00   0.00  25.00   0.00  25.00  25.00   0.00   0.00   0.00  25.00   0.00  25.00 250.00  25.00   0.00   0.00   0.00  25.00
##  [901]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.25  25.00   0.00   0.00
##  [926]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00
##  [951]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   2.50   0.00   0.00   0.00   0.00   0.00   0.00
##  [976]   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00  25.00 250.00 250.00  25.00   0.00 250.00 250.00  25.00 250.00 250.00 250.00
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
##   [1]  25.00   2.50  25.00   2.50   2.50   2.50   2.50   2.50  25.00  25.00   2.50   2.50 250.00   0.00  25.00  25.00  25.00  25.00  25.00  25.00  25.00   2.50   2.50  25.00  25.00  25.00
##  [27]  25.00  25.00  25.00   2.50   2.50   2.50  25.00   2.50  25.00 250.00   2.50  25.00   2.50  25.00   2.50  25.00   2.50  25.00  25.00   0.03  25.00 250.00 250.00   2.50   2.50  25.00
##  [53]  25.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   2.50   0.00   0.00   0.00   0.00   0.00   2.50   2.50  25.00
##  [79]   2.50   2.50   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00   0.00  25.00   0.00   0.00   0.00   2.50   0.00   0.00   0.00   0.00  25.00   0.00
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
##   [1] "0"    "25"   "0"    "0"    "0"    "0"    "0"    "5"    "0"    "0"    "0"    "0"    "0"    "0"    "0"    "0"    "15"   "0"    "5"    "35"   "0"    "0"    "0"    "0"    "0.25" "0.5" 
##  [27] "0"    "0"    "0"    "0"    "0"    "0"    "10"   "0"    "0"    "0"    "0"    "0"    "0"    "0"    "0"    "2"    "0"    "0"    "10"   "0"    "0"    "2"    "0"    "0"    "0"    "0"   
##  [53] "0"    "0"    "5"    "20"   "0"    "0"    "0"    "0"    "0"    "0"    "5"    "0"    "0"    "0"    "1"    "0"    "0"    "0"    "0"    "200"  "0"    "30"   "0"    "0"    "1"    "1.5" 
##  [79] "0"    "0"    "0"    "1"    "0"    "0"    "0"    "0"    "0"    "0"    "0"    "0"    "0"    "20"   "0"    "0"    "0"    "0"    "100"  "0"    "3"    "33"
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
##    0.00    0.00    0.00   12.06    0.50 5000.00 
## [1] "Range of var1:"
## [1]    0 5000
## [1] "Length of var1:"
## [1] 902297
## [1] "Structure of var1:"
##  num [1:902297] 25 2.5 25 2.5 2.5 2.5 2.5 2.5 25 25 ...
## [1] "Standard deviation of var1:"
## [1] 59.47585
## [1] "Histogram of var1:"
```

![](VarAnalysis/df.variable.analysis.PROPDMG_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of var1:"
```

![](VarAnalysis/df.variable.analysis.PROPDMG_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##      0   0.01   0.02   0.03   0.04   0.05   0.06   0.07   0.08    0.1   0.11   0.12   0.13   0.15   0.16   0.17   0.18    0.2   0.21   0.22   0.23   0.25   0.26    0.3   0.33   0.34 
## 663123    931     80   1610      4    588     25      4      2   1513     27      7      1     46      3      3      1    568      2      1      1   1978      1    284      4      2 
##   0.35   0.36    0.4   0.41   0.45    0.5   0.51   0.55    0.6   0.63   0.65   0.66    0.7   0.74   0.75   0.76   0.78    0.8   0.81   0.84   0.85   0.86   0.87    0.9   0.95   0.99 
##      7      1    110      1      3   6790      2      2    101      3      5      1    107      1    471     11      1    136      1      1     14      2      1    360      1      2 
##      1   1.01   1.02   1.03   1.04   1.05   1.06   1.07   1.08    1.1   1.11   1.13   1.14   1.15   1.16   1.17   1.18   1.19    1.2   1.21   1.23   1.24   1.25   1.26   1.27   1.28 
##  19069      4      5      2      6     11      4      3      1     88      4      6      2     16      2      2      1      1    185      1      2      5    124      3      2      4 
##   1.29    1.3   1.32   1.33   1.34   1.35   1.36   1.37   1.38    1.4   1.41   1.43   1.44   1.45   1.46   1.47   1.48   1.49    1.5   1.51   1.53   1.54   1.55   1.56   1.57   1.58 
##      2     75      4      4      3      6      2      3      1     64      2      2      1      2      2      2      2      2   1876      3      2      3      3      1      3      5 
##   1.59    1.6   1.61   1.62   1.63   1.65   1.66   1.68   1.69    1.7   1.71   1.72   1.73   1.74   1.75   1.76   1.77   1.78   1.79    1.8   1.81   1.82   1.83   1.84   1.85   1.86 
##      2     61      3      2      1      6      1      3      2     46      1      2      1      1     27      1      2      2      2    100      2      1      2      1      5      1 
##   1.87   1.88   1.89    1.9   1.91   1.92   1.95   1.96   1.97   1.99      2   2.01   2.03   2.05   2.07   2.09    2.1   2.15   2.16   2.19    2.2   2.22   2.25   2.26   2.27   2.28 
##      1      2      1     34      1      1      8      1      1      8  17872      2      4      4      1      1     34      2      2      2     36      1     31      1      2      1 
##    2.3   2.32   2.33   2.35   2.36   2.38    2.4   2.41   2.45   2.46   2.47   2.48    2.5   2.52   2.53   2.54   2.55   2.57   2.58    2.6   2.63   2.65   2.66   2.67   2.69    2.7 
##     14      2      2      1      1      2     32      1      2      1      2      2   8220      1      1      1      4      2      3     20      2      2      1      1      1     46 
##   2.72   2.73   2.75   2.77   2.78    2.8   2.81   2.82   2.83    2.9   2.95   2.98      3   3.02   3.03   3.04   3.05    3.1   3.11   3.13   3.15   3.17   3.18    3.2   3.24   3.25 
##      1      2      7      1      2     26      1      1      1     16      4      1  10745      2      1      3      5     11      1      2      3      1      1     24      1     15 
##   3.27   3.28   3.29    3.3   3.31   3.33   3.34   3.37    3.4   3.43   3.45   3.46   3.47   3.48    3.5   3.52   3.53   3.54   3.55   3.56   3.57    3.6   3.64   3.65   3.68    3.7 
##      1      1      1     24      1      1      1      1     10      2      2      1      1      1    302      1      2      2      4      1      1     23      3      1      1      8 
##   3.71   3.72   3.74   3.75   3.78    3.8   3.81   3.83   3.85    3.9   3.91   3.92   3.94   3.95   3.96   3.99      4   4.02   4.05   4.06    4.1   4.12   4.15   4.17    4.2   4.22 
##      2      2      1      5      1     14      1      1      1     13      1      2      1      1      1      1   3420      2      1      2      9      2      4      1     17      1 
##   4.25   4.26   4.27   4.29    4.3   4.36   4.37   4.38    4.4   4.43   4.44   4.45    4.5   4.51   4.52   4.57   4.59    4.6   4.64   4.65    4.7   4.71   4.74   4.75    4.8   4.83 
##      5      1      1      1     10      4      1      1     13      1     10      1    229      1      1      1      1      3      1      1      6      1      1      1      6      1 
##   4.84   4.85   4.86    4.9   4.93   4.94   4.96      5   5.05   5.08   5.09    5.1   5.13   5.15   5.16    5.2   5.24   5.25   5.27    5.3   5.38    5.4   5.42   5.47    5.5   5.51 
##      1      1      1      8      2      1      2  32655      3      1      1     10      1      1      1      8      1      2      1      8      1     10      2      1     55      1 
##   5.52   5.55   5.58    5.6   5.63   5.64    5.7   5.74   5.75   5.76    5.8   5.85   5.88    5.9   5.91   5.94   5.99      6   6.05   6.06   6.07    6.1   6.14    6.2   6.25    6.3 
##      1     13      1      6      1      1     11      1      3      1     10      1      1      8      1      1      2   1686      1      1      1      3      1      7      9      6 
##   6.32   6.34    6.4   6.45    6.5   6.51   6.53   6.55   6.57    6.6   6.61   6.63   6.67   6.68    6.7   6.74   6.75    6.8   6.82   6.88    6.9      7   7.05   7.06    7.1   7.15 
##      1      1      9      4     38      1      1      1      1      6      1      1      1      1      8      1      2      3      1      1      2   1423      2      1      2      1 
##    7.2   7.29    7.3   7.35   7.44   7.45    7.5   7.51   7.55    7.6   7.64    7.7   7.72   7.75   7.77    7.8    7.9   7.93      8   8.07   8.09    8.1    8.2   8.25    8.3   8.32 
##     12      1      4      1      1      2    284      1      2      7      2      6      1      2      1      3      4      1   2967      1      1      2      5      2      4      1 
##   8.37    8.4   8.43   8.45   8.48    8.5   8.57    8.6   8.65    8.7   8.75    8.8   8.81   8.85   8.87    8.9   8.97      9   9.06   9.17    9.2   9.25    9.3   9.31    9.4    9.5 
##      1      3      1      1      1     39      1      2      1      4      1      5      1      1      1      2      1    348      1      1      4      1      2      1      4     15 
##   9.51    9.6    9.7   9.72   9.75   9.76   9.77    9.8    9.9     10  10.05   10.1  10.15   10.2  10.25   10.3  10.36   10.4  10.43  10.44   10.5   10.6  10.69   10.7  10.72  10.75 
##      1      4      1      1      2      1      1      8      5  22018      1      1      1      7      1      3      1      2      1      1     12      1      1      1      1      1 
##   10.8  10.88   10.9     11  11.02   11.1  11.15  11.16  11.18   11.2  11.26   11.3   11.4   11.5   11.6  11.62  11.65   11.7  11.79  11.83  11.85   11.9     12  12.05  12.06  12.17 
##      2      1      1    215      2      6      1      1      1      2      1      1      1     11      2      2      1      4      1      1      1      1   1392      1      1      1 
##   12.2  12.29   12.3   12.4   12.5   12.6   12.7  12.71   12.8   12.9     13  13.13  13.15   13.2  13.25   13.3  13.36   13.4  13.47   13.5  13.53  13.54  13.67  13.71   13.8   13.9 
##      2      1      2      1     45      4      2      1      4      4    165      1      1      2      1      3      1      2      1      8      1      1      1      1      1      1 
##  13.95     14   14.1   14.2  14.25  14.26  14.28   14.3   14.4   14.5   14.6   14.7   14.8  14.96  14.98     15   15.2  15.25   15.3   15.5   15.6  15.66  15.75     16  16.05   16.1 
##      1    176      2      3      2      1      1      1      4      3      1      1      1      1      1   8735      4      1      2      9      2      1      2    165      1      2 
##  16.15   16.2  16.25   16.5   16.6  16.64   16.7  16.74   16.8  16.87   16.9  16.93  16.96     17  17.03  17.14   17.2   17.3   17.5   17.6   17.7  17.75   17.8   17.9  17.92     18 
##      1      2      1      6      2      1      2      1      1      1      2      1      1    147      2      1      1      2     12      2      2      2      1      2      1    401 
##  18.05   18.2   18.3   18.4   18.5  18.54   18.6   18.8  18.97     19   19.2   19.3   19.4   19.5  19.64   19.7  19.77  19.79   19.9  19.94     20  20.02   20.1   20.2   20.4   20.5 
##      1      2      2      2      3      1      1      1      1     47      1      1      1      5      1      1      1      1      1      8   9307      2      1      1      2      5 
##   20.6   20.8   20.9     21   21.1   21.2   21.3   21.5   21.6   21.7  21.75  21.88     22  22.14  22.18   22.2   22.4   22.5   22.6   22.7  22.75  22.85  22.88     23   23.2  23.23 
##      1      1      1     58      1      1      3      7      1      2      1      1    156      1      1      1      1      5      1      1      2      1      1     82      1      2 
##   23.5  23.55  23.58   23.7     24   24.1  24.21   24.5   24.7  24.76     25  25.13   25.5  25.52  25.65   25.9     26   26.2   26.3  26.43   26.5   26.6  26.64  26.87     27   27.1 
##      3      1      1      2     72      1      1      3      1      1  17696      1      4      1      1      1     44      1      1      1      3      1      1      1     70      1 
##   27.5     28   28.2   28.4   28.5  28.55  28.68   28.9     29   29.5   29.7  29.96     30  30.06   30.3   30.5   30.7     31   31.3   31.5  31.52   31.6   31.7   31.9  31.95     32 
##      2     77      1      2      5      1      1      1     23      1      1      1   4443      1      1      1      1     23      1      4      1      1      1      1      2     43 
##   32.2  32.22   32.5     33   33.5     34  34.31  34.63  34.89     35   35.5  35.55   35.9     36   36.2  36.25     37   37.4   37.5     38   38.5     39   39.5   39.6   39.8     40 
##      1      1      6     34      1     26      1      1      1   1263      1      1      1     28      1      1     23      1     12     38      3      8      1      1      2   2412 
##   40.2   40.3   40.5     41   41.5   41.6   41.7     42  42.16  42.31   42.4     43   43.5   43.6     44   44.5  44.52   44.6   44.7  44.72     45  45.07   45.5   45.7   45.8     46 
##      1      1      1     11      1      1      2     30      1      1      2     14      1      1     19      2      1      1      1      1    495      1      2      2      1     19 
##   46.5   46.8     47   47.3   47.5     48  48.02     49  49.34   49.5   49.9  49.94  49.98     50  50.02   50.1     51   51.5     52   52.5     53   53.8   53.9     54   54.1   54.9 
##      1      1     16      1      2     23      1     10      1      1      1      1      1  13793      1      1     10      1     12      1     16      1      1     10      1      1 
##     55  55.08   55.1  55.22   55.5   55.6   55.9     56   56.5  56.54     57  57.12     58     59     60   60.5   60.8     61  61.98     62   62.6  62.99     63   63.7     64     65 
##    233      1      1      1      1      1      1     12      1      1      9      1     17      4   1057      1      1     10      1     15      1      1     16      1     15    208 
##   65.5     66   66.5   66.9     67     68   68.6     69   69.7     70   70.9     71   71.5     72   72.7     73     74  74.25     75   75.3     76   76.3   76.5   76.6     77   77.8 
##      1     12      1      1     10     18      1      2      1    575      1      7      1     10      1      8      5      1   2442      1      5      1      1      1      7      1 
##  77.97     78   78.2   78.7  78.74     79   79.2  79.98     80     81  81.15     82   82.5     83   83.8     84     85     86   86.6     87   87.8     88  88.15   88.5  88.75     89 
##      1      8      1      1      1      4      1      1    761      9      1      9      1      9      1      5    132      3      1      4      1     10      1      1      1      4 
##   89.5     90  90.43     91     92     93     94   94.5     95     96   96.6   96.8     97   97.2     98  98.26     99  99.39  99.97    100 100.02 100.03  100.5    101    102 102.22 
##      1    236      1      5      6      4      6      1     62      4      1      1      6      1      7      1     11      1      1   6269      1      1      1      5      6      1 
##    103    104    105    106 106.72    107    108 108.63    109    110    111    112  112.5    113    114    115    116    117    118    119    120    121  121.7    122    123    124 
##      6      5     38      4      1      4     11      1      2    135      3      6      1      3      8     40      5      2      4      1    274      2      1      4      4      2 
##  124.9    125    126    127  127.2    128  128.7    129    130 130.02    132    133    134  134.8    135    136    137  137.9    138  138.6    139    140 140.25    141    142    143 
##      1    446      3      5      1      6      1      2     95      1      6      2      1      1     43      2      2      1      5      1      2     65      1      2      1      2 
##    144    145    146  146.5    147    148 148.25    149 149.58 149.85    150  150.2    151  151.1  151.4    152    153 153.55    154    155  156.5    157    158    159  159.5    160 
##      1     22      2      2      6      1      1      2      1      1   2057      1      1      1      1      3      3      1      3     15      1      3      2      1      1     73 
##  160.8    161 161.11  161.2    162    163  163.5    164  164.8    165    166  166.5 166.67    167  167.5    168    170    171    172    173 174.16  174.4    175    176    177  177.5 
##      1      4      1      1      3      2      1      1      1     21      5      1      3      4      1      1     47      2      3      4      1      1    183      3      2      1 
##    178  178.4    179  179.4  179.5 179.61    180    181    182    183  183.5    184    185    186    187    189    190    191    192    193    195    196  198.5    200    201    202 
##      1      1      2      1      1      7     71      1      1      1      1      3     10      3      2      2     32      1      7      3     16      1      1   2195      2      3 
##    203    204    205    206    207    208    209    210    211    212    213    214    215    216    217    218    219    220    222    224    225    226    227  227.6    229  229.9 
##      3      3      7      3      3      2      1     40      1      2      2      1     12      1      1      3      2     35      1      2     76      1      5      2      1      1 
##    230    231    232    233    234    235    237    240    241    242  242.8    243 
##     36      2      1      1      1      7      5     36      1      1      1      2 
##  [ reached getOption("max.print") -- omitted 390 entries ]
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
