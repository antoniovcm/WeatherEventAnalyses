---
title: "LENGTH Variable Analyses"
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
##    [1] 14.0  2.0  0.1  0.0  0.0  1.5  1.5  0.0  3.3  2.3  1.3  4.7  0.0  3.3  3.3 21.6  0.2  0.2  0.2  0.2  0.5  3.0  1.5  0.0  6.5  0.1  0.5  0.7  7.1  0.1  1.0  0.5  0.5 34.7  1.5 12.1
##   [37]  0.0  0.0  0.2  0.0  0.0  2.0 12.5  1.9  2.5  1.3 16.0 19.4 24.7 17.5  1.5  0.0  5.4  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  1.5  0.0  8.6  0.0  0.0
##   [73]  0.0  0.0  0.0 16.0  1.3 14.0  1.9 14.5  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0 11.9  0.0  0.0  0.0 21.3  0.0  0.0  0.0  0.0  3.8  0.0  0.0  0.0 31.1  0.0 73.9 30.5 17.3  0.0
##  [109]  0.0  0.0  0.0  0.0  1.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0 51.4 33.6  5.2 16.3  0.0  0.0  0.0  0.0  0.0  7.4  2.0  0.0 12.8 23.2 12.1 13.5  8.8  0.0 12.3 14.5  8.9  1.0  1.1  5.2
##  [145]  5.2  0.0 16.5  0.0  0.0  0.0 11.9  8.7  0.0  4.1  0.0  0.0  7.2  9.2  7.4  7.6 20.4  3.3 37.3  0.0  8.2  0.0  0.0  0.0  0.0  0.0  0.0 15.8 10.3  0.0  0.0  0.0  0.0  0.8  3.0  0.0
##  [181] 11.3  0.0 20.9  0.0  0.0 12.9  0.0  0.0  0.5  8.9 10.3 25.6 10.5  0.0  8.8  6.6 15.8  9.9  0.0  0.0  0.3  0.5  0.0 12.1  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.3  1.0  0.0  1.0  0.0
##  [217]  0.0  0.0  0.0  2.7  0.0  0.0  0.0  0.0  0.0  0.0  4.9  8.6  0.0  0.0  0.1  0.0  0.1  0.0  0.0  0.0  0.0  0.0  0.0  0.2  0.0  0.0  0.0  0.0  0.0  0.0  5.7  0.0 11.5  0.1  0.2  0.2
##  [253]  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.3  0.0  0.0  0.0  0.0  1.0  1.0 25.6  0.0 15.0  5.9 10.4  8.9  0.0  0.0  0.0  0.0  4.1  0.0  0.0  0.0  0.0  0.0  0.0
##  [289]  0.0  0.0  3.0  0.0 54.1  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.5  0.0  0.0  0.2  3.3  8.3  9.4  0.0  2.0  0.0  0.0 24.2  0.0  5.4  0.0  2.0  5.1
##  [325]  0.0  0.0  0.0  0.0  0.0  0.0  2.3  0.0  0.5  3.8  0.5  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  1.0  0.0 11.9  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [361]  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  3.3  0.0 14.1 14.9  0.0  7.1  0.0  0.0 28.0  0.0  0.0  0.0 22.2 25.0  0.0 24.6  7.6  0.0  0.0  9.1  2.7  0.0  0.0  0.0  0.0
##  [397]  0.0  0.0  0.0  0.0  0.0 10.6  9.8 15.5  0.0  0.0  0.0  0.0  0.0  0.0  0.0 11.7  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  3.3  0.0  0.0 10.4  5.2  0.0
##  [433]  0.0  0.0  5.4  0.0  5.1  3.3  0.0  0.0  5.4  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  4.3  0.0  0.0  0.0  5.1 13.0  6.8  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [469]  0.0  0.0  0.0  0.0  3.3  0.0  0.0  0.0  0.0  4.9  0.0  0.0  2.0 21.0  0.0  0.0  0.0  0.0  1.5  0.0 11.0 18.8  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  3.0  6.6  0.0  0.0  0.0
##  [505]  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  4.3  0.0  0.0  0.0  0.0 14.5  0.0  0.0  0.0 40.7  0.0 25.8  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [541]  0.0  0.0  0.0  1.0  0.0  7.6  0.0  0.0  0.0  1.0  7.7  9.3  0.0  0.0 20.9  0.0  0.0  2.3  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [577]  0.0  0.0  0.0  0.0  0.0  4.3  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  5.2  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [613]  0.5  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0 11.9 13.1  1.9  0.0 13.1  0.0  0.0  0.0  0.0  3.8  6.6  0.0  0.0  1.0  0.0  0.0 14.2  0.0  0.0  2.7 20.2  0.0  7.6  2.0  0.0
##  [649] 12.6 11.8  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0 14.4  0.0  0.0  0.0  4.1  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  2.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [685]  0.0  0.0  0.0  0.0  0.0  2.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [721]  0.0  0.0  0.0 12.2 11.9 12.8 33.5 11.5 18.3 14.0  0.0  0.0  0.0  0.0  0.0  5.6  0.0  0.0  0.0  0.0  0.0  0.0  0.0  2.5 12.8 32.8  6.8  0.0  0.0  0.0  0.0  0.0  0.0  7.1  6.4  0.0
##  [757]  0.5  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.3  0.0  0.0  0.0
##  [793]  0.0  0.0  0.0  8.6  7.1  0.0  0.0  0.0  0.0  0.0  0.0  0.0  1.0  0.0  0.0  2.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  6.1  5.6  0.0  0.0  0.0  0.5  8.6  3.3  0.0  0.0  1.0
##  [829]  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  3.8  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [865]  0.0  2.0  1.0 24.5  9.6  0.0  0.0  0.0  0.0  1.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  4.3  0.0  2.0  0.0  0.0  7.3  0.0  0.0  0.0  0.0  0.0 23.8  4.9  2.0  0.0  0.0  0.0  4.9
##  [901]  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  1.0 25.4  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0
##  [937]  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.5  0.0  0.0  0.0
##  [973]  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  5.7  2.0  8.7  1.0  0.3  0.0  1.0  1.0  4.5  1.1  5.2  8.4
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
##   [1] 14.0  2.0  0.1  0.0  0.0  1.5  1.5  0.0  3.3  2.3  1.3  4.7  0.0  3.3  3.3 21.6  0.2  0.2  0.2  0.2  0.5  3.0  1.5  0.0  6.5  0.1  0.5  0.7  7.1  0.1  1.0  0.5  0.5 34.7  1.5 12.1
##  [37]  0.0  0.0  0.2  0.0  0.0  2.0 12.5  1.9  2.5  1.3 16.0 19.4 24.7 17.5  1.5  0.0  5.4  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  1.5  0.0  8.6  0.0  0.0
##  [73]  0.0  0.0  0.0 16.0  1.3 14.0  1.9 14.5  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0  0.0 11.9  0.0  0.0  0.0 21.3  0.0  0.0  0.0  0.0  3.8  0.0
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
##   [1] "0"   "7.3" "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0.5" "3"   "0"   "0"   "0.5" "0"   "0"  
##  [31] "0"   "0"   "5"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"  
##  [61] "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"   "0"  
##  [91] "0"   "1"   "0"   "0"   "0.1" "0"   "0"   "0"   "0"   "0"
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
##      Min.   1st Qu.    Median      Mean   3rd Qu.      Max. 
##    0.0000    0.0000    0.0000    0.2301    0.0000 2315.0000 
## [1] "Range of var1:"
## [1]    0 2315
## [1] "Length of var1:"
## [1] 902297
## [1] "Structure of var1:"
##  num [1:902297] 14 2 0.1 0 0 1.5 1.5 0 3.3 2.3 ...
## [1] "Standard deviation of var1:"
## [1] 4.617236
## [1] "Histogram of var1:"
```

![](VarAnalysis/df.variable.analysis.LENGTH_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of var1:"
```

![](VarAnalysis/df.variable.analysis.LENGTH_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##      0    0.1   0.13    0.2   0.25    0.3    0.4   0.45    0.5    0.6   0.62    0.7   0.75    0.8    0.9      1    1.1    1.2   1.25    1.3    1.4    1.5    1.6    1.7    1.8    1.9 
## 850839   7699      2   4131     51   2287    326      1   4581    197      1    308     14    526     71   6520     85    171      1    265     28   1047     35     55     91    198 
##      2    2.1    2.2    2.3    2.4    2.5    2.6    2.7   2.75    2.8    2.9      3    3.1    3.2    3.3    3.4    3.5    3.6    3.7    3.8    3.9      4    4.1    4.2   4.25    4.3 
##   3928     27     71    265     19    505     27    216      2     45     21   2048     18     24    247     31    200    228     18    203     11   1306    174     27      1    190 
##    4.4    4.5    4.6    4.7   4.75    4.8    4.9      5    5.1    5.2   5.25    5.3    5.4    5.5    5.6    5.7    5.8    5.9      6    6.1    6.2    6.3    6.4    6.5    6.6    6.7 
##      9    258     38    145      1     17    153   1208    144    115      1     11    118     82    110    117     11     95    807     79     90     10     77    117     62      9 
##    6.8    6.9      7    7.1    7.2    7.3    7.4    7.5    7.6    7.7    7.8    7.9      8    8.1    8.2    8.3    8.4    8.5    8.6    8.7    8.8    8.9      9    9.1    9.2    9.3 
##     76     56    667     73     73     55     54     62     58     56     56     47    648      5     51     41     47     80     42     44     59     42    382     47     56     40 
##    9.4    9.5    9.6    9.7    9.8    9.9     10   10.1   10.2   10.3   10.4   10.5   10.6   10.7   10.8   10.9     11   11.1   11.2   11.3   11.4   11.5   11.6   11.7   11.8   11.9 
##     52     59     43     40     32     40    525     30     25     37     56     48     34     32     23     31    247     36     26     29     24     84     23     26     23     56 
##     12   12.1   12.2   12.3   12.4   12.5   12.6   12.7   12.8   12.9     13   13.1   13.2   13.3   13.4   13.5   13.6   13.7   13.8   13.9     14   14.1   14.2   14.3   14.4   14.5 
##    313     23     22     34     17     40     37     10     47     17    191     42     14     41     13     27     17     20     30     17    196     16     32     10     33     31 
##   14.6   14.7   14.8   14.9     15   15.1   15.2   15.3   15.4   15.5   15.6   15.7   15.8   15.9     16   16.1   16.2   16.3   16.4   16.5   16.6   16.7   16.8   16.9     17   17.1 
##     20     22     15     37    230     11     34     14     22     32     12     16     28     23    148     13     32     12     13     26     15     14     14     17    116     12 
##   17.2   17.3   17.4   17.5   17.6   17.7   17.8   17.9     18   18.1   18.2   18.3   18.4   18.5   18.6   18.7   18.8   18.9     19   19.1   19.2   19.3   19.4   19.5   19.6   19.7 
##     22     18      8     26     11     12     18     10     87     13     19     13      8     15      9     19     16     15     77     12     12      6     18     19     11     14 
##   19.8   19.9     20   20.1   20.2   20.3   20.4   20.5   20.6   20.7   20.8   20.9     21   21.1   21.2   21.3   21.4   21.5   21.6   21.7   21.8   21.9     22   22.1   22.2   22.3 
##     21     19    129     11     14     12      8     17      8     10     11     20     56      5      3     19      8      8     12      5      7     14     47      9     14      8 
##   22.4   22.5   22.6   22.7   22.8   22.9     23   23.1   23.2   23.3   23.4   23.5   23.6   23.7   23.8   23.9     24   24.1   24.2   24.3   24.4   24.5   24.6   24.7   24.8   24.9 
##      5     18      4     10      6      5     49      7      6      4      5     10      9      9      6     10     45      4     11      6     10      9      7      9      5      6 
##     25   25.1   25.2   25.3   25.4   25.5   25.6   25.7   25.8   25.9     26   26.1   26.2   26.3   26.4   26.5   26.6   26.7   26.8   26.9     27   27.1   27.2   27.3   27.4   27.5 
##     55      7      7      2      6      4      7      3      8      5     38      6      8      2      6      3      3     11      4      7     23      7      3      3      4      4 
##   27.6   27.7   27.8   27.9     28   28.1   28.2   28.3   28.4   28.5   28.6   28.7   28.8   28.9     29   29.1   29.2   29.3   29.5   29.6   29.7   29.8   29.9     30   30.1   30.2 
##      6      2      6      5     20      4      3      3      3      6      1      5      5      2     20      3      2      6      2      5      3      3      4     34      3      6 
##   30.3   30.4   30.5   30.6   30.7   30.8   30.9     31   31.1   31.2   31.3   31.4   31.5   31.6   31.7   31.8   31.9     32   32.1   32.2   32.3   32.4   32.6   32.7   32.8   32.9 
##      3      1      6      2      4      2      2      8      3      1      4      2      5      3      3      3      4      7      1      4      2      3      1      1      4      2 
##     33   33.2   33.3   33.4   33.5   33.6   33.7   33.8   33.9     34   34.1   34.2   34.3   34.4   34.5   34.6   34.7   34.9     35   35.1   35.2   35.3   35.4   35.5   35.6   35.7 
##     11      2      2      4      7      3      2      2      1      9      2      3      3      1      3      5      3      2      6      1      1      1      5      1      2      1 
##   35.8   35.9     36   36.1   36.2   36.3   36.4   36.5   36.7   36.8   36.9     37   37.1   37.3   37.4   37.5   37.8   37.9     38   38.1   38.2   38.3   38.4   38.5   38.7   38.8 
##      1      1      2      3      3      2      2      3      1      2      1      7      3      1      2      1      1      1      4      3      3      1      1      2      1      1 
##     39   39.1   39.2   39.3   39.4   39.5   39.6   39.7   39.8   39.9     40   40.1   40.2   40.3   40.4   40.5   40.6   40.7   40.8   41.1   41.3   41.5   41.6   41.9     42   42.1 
##      1      2      1      3      1      1      1      2      3      3      6      4      2      1      2      1      2      3      1      2      2      1      1      1      6      1 
##   42.2   42.3   42.4   42.5   42.6   42.7   42.8   42.9     43   43.2   43.5   43.8   43.9   44.2   44.4   44.6   44.8   44.9     45   45.3   45.5   45.6   45.8   45.9   46.2   46.3 
##      1      2      1      2      1      2      6      3      1      1      1      2      2      2      1      2      3      2      4      2      1      2      1      1      2      1 
##   46.4   46.5   46.8     47   47.1   47.4   47.5   47.6   47.9     48   48.1   48.5   48.6   48.7   49.2   49.7   49.8   49.9     50   50.3   50.9   51.4   51.6   51.7     52   52.2 
##      1      2      1      2      1      2      3      1      1      1      5      1      4      1      2      1      1      2     13      1      2      3      1      2      1      1 
##   52.6   52.7   53.1   53.4   53.5   53.9   54.1   54.4   54.5   54.6   54.8     55   55.2   55.5   55.6   56.2   56.4   56.6   57.2   57.6     58   58.9     59   59.1   59.2   59.3 
##      1      2      1      1      1      1      3      1      1      1      1      2      1      1      1      1      3      1      1      1      1      1      1      3      1      1 
##   59.9     60   60.7     61   61.2   61.6   61.9   62.3   62.8   62.9   63.2   63.3     64   64.1   65.4   65.5   65.8   66.2   66.3   67.1   67.3     68   69.5   69.6   69.7   70.1 
##      1      1      1      1      1      1      2      1      1      1      1      1      1      1      1      1      3      1      1      1      1      1      1      1      1      2 
##   70.2   70.3   70.7   71.2   71.8   72.2   72.7   72.8     73   73.9   74.5     75   75.3   75.5   75.9   77.3   78.9     80   80.3   80.4   80.9   81.7   82.3   85.1   89.6   89.8 
##      2      1      1      1      1      6      1      2      1      1      1      1      2      1      2      1      1      2      1      1      1      1      1      1      2      1 
##   92.6   95.5   95.9   96.7    100    103  105.9  106.8  110.2  118.8    140    150    160    200    300    400    500    600   1200   1845   2130   2315 
##      1      1      1      1     15      1      1      1      1      1      1      2      1      3      3      2      1      1      1      1      1      1 
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
