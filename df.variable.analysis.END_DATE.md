---
title: "END_DATE Variable Analyses"
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
##   [1] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
##  [61] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ""
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
##   [1] "3/3/1995 0:00:00"   ""                   ""                   "10/16/2007 0:00:00" ""                   "9/9/1999 0:00:00"   "4/20/2007 0:00:00"  ""                  
##   [9] "4/7/2005 0:00:00"   "8/31/2005 0:00:00"  "9/23/2010 0:00:00"  "5/4/2003 0:00:00"   "3/7/2000 0:00:00"   "11/5/2005 0:00:00"  ""                   "7/22/2011 0:00:00" 
##  [17] "6/21/2007 0:00:00"  "10/21/1996 0:00:00" "3/30/2006 0:00:00"  "7/14/2000 0:00:00"  "8/23/2004 0:00:00"  "2/14/2002 0:00:00"  "2/3/2009 0:00:00"   "6/12/2000 0:00:00" 
##  [25] "3/28/2007 0:00:00"  "7/28/1999 0:00:00"  ""                   "9/4/1996 0:00:00"   "6/19/2008 0:00:00"  "6/18/2010 0:00:00"  ""                   "6/26/2007 0:00:00" 
##  [33] "5/3/1999 0:00:00"   "5/9/2009 0:00:00"   "8/28/2011 0:00:00"  "5/25/2008 0:00:00"  "6/8/1999 0:00:00"   "8/28/2002 0:00:00"  "12/8/1999 0:00:00"  ""                  
##  [41] "3/14/1993 0:00:00"  "4/29/1996 0:00:00"  "4/21/2004 0:00:00"  "9/22/2000 0:00:00"  "7/1/2005 0:00:00"   ""                   "8/5/2009 0:00:00"   "5/21/2004 0:00:00" 
##  [49] ""                   "5/19/2010 0:00:00"  "2/25/2000 0:00:00"  "5/5/2002 0:00:00"   "11/28/2005 0:00:00" "12/21/1997 0:00:00" "2/25/2003 0:00:00"  "3/13/2006 0:00:00" 
##  [57] "1/12/2006 0:00:00"  ""                   "7/21/1999 0:00:00"  "1/16/2009 0:00:00"  "5/1/2011 0:00:00"   "5/26/2011 0:00:00"  "3/9/1998 0:00:00"   "7/5/2003 0:00:00"  
##  [65] ""                   ""                   "6/27/2007 0:00:00"  "4/17/2010 0:00:00"  "6/13/2001 0:00:00"  "5/9/1999 0:00:00"   "3/2/2000 0:00:00"   "7/30/2006 0:00:00" 
##  [73] "6/24/1998 0:00:00"  "12/25/2003 0:00:00" "7/23/1997 0:00:00"  "3/26/2007 0:00:00"  "5/3/2009 0:00:00"   "7/8/2008 0:00:00"   ""                   "7/25/2001 0:00:00" 
##  [81] "6/5/2006 0:00:00"   "6/3/2002 0:00:00"   ""                   ""                   "8/11/2001 0:00:00"  ""                   ""                   "3/29/1998 0:00:00" 
##  [89] "5/5/2002 0:00:00"   "8/20/2010 0:00:00"  ""                   "1/21/1999 0:00:00"  "4/16/2007 0:00:00"  "4/12/1996 0:00:00"  "9/26/2005 0:00:00"  "6/17/2002 0:00:00" 
##  [97] "6/1/1997 0:00:00"   ""                   "6/22/2010 0:00:00"  "1/10/1998 0:00:00"
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
##  chr [1:902297] "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" ...
## [1] "Summary of var1:"
##    Length     Class      Mode 
##    902297 character character 
## [1] "Proportion of NA values in var1:"
## [1] 0
## [1] "Total count of NA values in var1:"
## [1] 0
## [1] "Substring of top 10 longest var1 (limited to 500 characters):"
##  [1] "11/11/1995 0:00:00" "11/17/1995 0:00:00" "11/23/1995 0:00:00" "11/30/1995 0:00:00" "11/21/1993 0:00:00" "10/17/1994 0:00:00" "10/22/1994 0:00:00" "10/31/1994 0:00:00"
##  [9] "11/10/1994 0:00:00" "11/12/1994 0:00:00"
## [1] "Data frame of 25 smallest unique char-limited values:"
##             var1_30 nchar
## 1                       0
## 2  2/8/1995 0:00:00    16
## 3  2/3/1995 0:00:00    16
## 4  7/8/1995 0:00:00    16
## 5  6/1/1995 0:00:00    16
## 6  7/8/1994 0:00:00    16
## 7  6/6/1995 0:00:00    16
## 8  7/9/1995 0:00:00    16
## 9  9/6/1994 0:00:00    16
## 10 9/9/1995 0:00:00    16
## 11 2/7/1993 0:00:00    16
## 12 1/3/1993 0:00:00    16
## 13 3/8/1994 0:00:00    16
## 14 6/5/1994 0:00:00    16
## 15 2/6/1995 0:00:00    16
## 16 3/2/1995 0:00:00    16
## 17 3/3/1995 0:00:00    16
## 18 3/6/1995 0:00:00    16
## 19 3/8/1995 0:00:00    16
## 20 3/7/1995 0:00:00    16
## 21 4/3/1995 0:00:00    16
## 22 4/4/1995 0:00:00    16
## 23 1/4/1995 0:00:00    16
## 24 1/4/1993 0:00:00    16
## 25 2/4/1993 0:00:00    16
## [1] "Summary of nchar(var1, allowNA = TRUE):"
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##    0.00    0.00   17.00   12.27   17.00   18.00 
## [1] "Histogram of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.END_DATE_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.END_DATE_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##                      1/1/1993 0:00:00   1/1/1994 0:00:00   1/1/1995 0:00:00   1/1/1996 0:00:00   1/1/1997 0:00:00   1/1/1998 0:00:00   1/1/1999 0:00:00   1/1/2000 0:00:00 
##             243411                  3                  3                  2                 12                 61                 12                 69                  5 
##   1/1/2001 0:00:00   1/1/2002 0:00:00   1/1/2003 0:00:00   1/1/2004 0:00:00   1/1/2005 0:00:00   1/1/2006 0:00:00   1/1/2007 0:00:00   1/1/2008 0:00:00   1/1/2009 0:00:00 
##                 10                 12                 26                 40                 17                 53                 32                 25                 29 
##   1/1/2010 0:00:00   1/1/2011 0:00:00  1/10/1993 0:00:00  1/10/1994 0:00:00  1/10/1995 0:00:00  1/10/1996 0:00:00  1/10/1997 0:00:00  1/10/1998 0:00:00  1/10/1999 0:00:00 
##                 18                 90                 13                  2                  7                 18                 63                 40                 10 
##  1/10/2000 0:00:00  1/10/2001 0:00:00  1/10/2002 0:00:00  1/10/2003 0:00:00  1/10/2004 0:00:00  1/10/2005 0:00:00  1/10/2006 0:00:00  1/10/2007 0:00:00  1/10/2008 0:00:00 
##                 75                 20                  9                  2                 14                 29                 21                 46                247 
##  1/10/2009 0:00:00  1/10/2010 0:00:00  1/10/2011 0:00:00  1/11/1993 0:00:00  1/11/1995 0:00:00  1/11/1996 0:00:00  1/11/1997 0:00:00  1/11/1998 0:00:00  1/11/1999 0:00:00 
##                 68                 20                192                  8                  5                 12                 44                 94                 19 
##  1/11/2000 0:00:00  1/11/2001 0:00:00  1/11/2002 0:00:00  1/11/2003 0:00:00  1/11/2004 0:00:00  1/11/2005 0:00:00  1/11/2006 0:00:00  1/11/2007 0:00:00  1/11/2008 0:00:00 
##                 58                 43                  5                 19                 13                 56                 20                 19                 60 
##  1/11/2009 0:00:00  1/11/2010 0:00:00  1/11/2011 0:00:00  1/12/1993 0:00:00  1/12/1994 0:00:00  1/12/1995 0:00:00  1/12/1996 0:00:00  1/12/1997 0:00:00  1/12/1998 0:00:00 
##                 66                 27                 94                  4                  1                  5                 88                 25                 79 
##  1/12/1999 0:00:00  1/12/2000 0:00:00  1/12/2001 0:00:00  1/12/2002 0:00:00  1/12/2003 0:00:00  1/12/2004 0:00:00  1/12/2005 0:00:00  1/12/2006 0:00:00  1/12/2007 0:00:00 
##                 11                 14                 42                 11                  9                  6                149                 63                 22 
##  1/12/2008 0:00:00  1/12/2009 0:00:00  1/12/2010 0:00:00  1/12/2011 0:00:00  1/13/1993 0:00:00  1/13/1994 0:00:00  1/13/1995 0:00:00  1/13/1996 0:00:00  1/13/1997 0:00:00 
##                  6                111                 20                133                 15                  1                  5                 13                 16 
##  1/13/1998 0:00:00  1/13/1999 0:00:00  1/13/2000 0:00:00  1/13/2001 0:00:00  1/13/2002 0:00:00  1/13/2003 0:00:00  1/13/2004 0:00:00  1/13/2005 0:00:00  1/13/2006 0:00:00 
##                 15                 25                 44                 12                 32                  4                  6                288                 76 
##  1/13/2007 0:00:00  1/13/2008 0:00:00  1/13/2009 0:00:00  1/13/2010 0:00:00  1/13/2011 0:00:00  1/14/1993 0:00:00  1/14/1994 0:00:00  1/14/1995 0:00:00  1/14/1996 0:00:00 
##                103                 13                 36                 11                 62                 15                  1                  4                  1 
##  1/14/1997 0:00:00  1/14/1998 0:00:00  1/14/1999 0:00:00  1/14/2000 0:00:00  1/14/2001 0:00:00  1/14/2002 0:00:00  1/14/2003 0:00:00  1/14/2004 0:00:00  1/14/2005 0:00:00 
##                 18                 29                 26                 11                 22                 13                  3                 14                106 
##  1/14/2006 0:00:00  1/14/2007 0:00:00  1/14/2008 0:00:00  1/14/2009 0:00:00  1/14/2010 0:00:00  1/14/2011 0:00:00  1/15/1993 0:00:00  1/15/1994 0:00:00  1/15/1995 0:00:00 
##                108                139                 43                 45                 10                 16                  2                  2                 16 
##  1/15/1996 0:00:00  1/15/1997 0:00:00  1/15/1998 0:00:00  1/15/1999 0:00:00  1/15/2000 0:00:00  1/15/2001 0:00:00  1/15/2002 0:00:00  1/15/2003 0:00:00  1/15/2004 0:00:00 
##                 15                 52                 26                104                  7                  7                  5                 14                 19 
##  1/15/2005 0:00:00  1/15/2006 0:00:00  1/15/2007 0:00:00  1/15/2008 0:00:00  1/15/2009 0:00:00  1/15/2010 0:00:00  1/15/2011 0:00:00  1/16/1994 0:00:00  1/16/1995 0:00:00 
##                 34                 60                166                 50                 60                 28                 12                  7                 18 
##  1/16/1996 0:00:00  1/16/1997 0:00:00  1/16/1998 0:00:00  1/16/1999 0:00:00  1/16/2000 0:00:00  1/16/2001 0:00:00  1/16/2002 0:00:00  1/16/2003 0:00:00  1/16/2004 0:00:00 
##                  8                 78                 61                 17                 45                 27                 11                 40                 45 
##  1/16/2005 0:00:00  1/16/2006 0:00:00  1/16/2007 0:00:00  1/16/2008 0:00:00  1/16/2009 0:00:00  1/16/2010 0:00:00  1/16/2011 0:00:00  1/17/1993 0:00:00  1/17/1994 0:00:00 
##                 22                 28                 27                 17                 93                  3                 26                  2                  9 
##  1/17/1995 0:00:00  1/17/1996 0:00:00  1/17/1997 0:00:00  1/17/1998 0:00:00  1/17/1999 0:00:00  1/17/2000 0:00:00  1/17/2001 0:00:00  1/17/2002 0:00:00  1/17/2003 0:00:00 
##                  9                148                 24                 21                251                 27                  9                  8                 21 
##  1/17/2004 0:00:00  1/17/2005 0:00:00  1/17/2006 0:00:00  1/17/2007 0:00:00  1/17/2008 0:00:00  1/17/2009 0:00:00  1/17/2010 0:00:00  1/17/2011 0:00:00  1/18/1993 0:00:00 
##                 28                 11                 31                 52                 79                 37                 15                 87                  3 
##  1/18/1994 0:00:00  1/18/1995 0:00:00  1/18/1996 0:00:00  1/18/1997 0:00:00  1/18/1998 0:00:00  1/18/1999 0:00:00  1/18/2000 0:00:00  1/18/2001 0:00:00  1/18/2002 0:00:00 
##                  3                 11                310                 13                 31                188                 29                  5                 11 
##  1/18/2003 0:00:00  1/18/2004 0:00:00  1/18/2005 0:00:00  1/18/2006 0:00:00  1/18/2007 0:00:00  1/18/2008 0:00:00  1/18/2009 0:00:00  1/18/2010 0:00:00  1/18/2011 0:00:00 
##                  5                 22                 38                 95                 17                 35                 64                 63                 75 
##  1/19/1993 0:00:00  1/19/1994 0:00:00  1/19/1995 0:00:00  1/19/1996 0:00:00  1/19/1997 0:00:00  1/19/1998 0:00:00  1/19/1999 0:00:00  1/19/2000 0:00:00  1/19/2001 0:00:00 
##                  7                  6                  7                378                 17                 18                 22                 15                108 
##  1/19/2002 0:00:00  1/19/2003 0:00:00  1/19/2004 0:00:00  1/19/2005 0:00:00  1/19/2006 0:00:00  1/19/2007 0:00:00  1/19/2008 0:00:00  1/19/2009 0:00:00  1/19/2010 0:00:00 
##                 71                  9                 10                 35                 45                 13                 54                 54                 92 
##  1/19/2011 0:00:00   1/2/1993 0:00:00   1/2/1994 0:00:00   1/2/1995 0:00:00   1/2/1996 0:00:00   1/2/1997 0:00:00   1/2/1998 0:00:00   1/2/1999 0:00:00   1/2/2000 0:00:00 
##                 62                  2                  3                  1                 45                 38                 12                199                 30 
##   1/2/2001 0:00:00   1/2/2002 0:00:00   1/2/2003 0:00:00   1/2/2004 0:00:00   1/2/2005 0:00:00   1/2/2006 0:00:00   1/2/2007 0:00:00   1/2/2008 0:00:00   1/2/2009 0:00:00 
##                 11                 21                 47                 37                 30                288                 30                 52                 55 
##   1/2/2010 0:00:00   1/2/2011 0:00:00  1/20/1993 0:00:00  1/20/1994 0:00:00  1/20/1995 0:00:00  1/20/1996 0:00:00  1/20/1997 0:00:00  1/20/1998 0:00:00  1/20/1999 0:00:00 
##                 43                 31                  5                  7                  8                 92                 26                  7                 19 
##  1/20/2000 0:00:00  1/20/2001 0:00:00  1/20/2002 0:00:00  1/20/2003 0:00:00  1/20/2004 0:00:00  1/20/2005 0:00:00  1/20/2006 0:00:00  1/20/2007 0:00:00  1/20/2008 0:00:00 
##                 45                 21                 34                  9                 19                 42                 30                 55                 57 
##  1/20/2009 0:00:00  1/20/2010 0:00:00  1/20/2011 0:00:00  1/21/1993 0:00:00  1/21/1994 0:00:00  1/21/1995 0:00:00  1/21/1996 0:00:00  1/21/1997 0:00:00  1/21/1998 0:00:00 
##                 37                209                138                  9                  3                  9                 28                 29                101 
##  1/21/1999 0:00:00  1/21/2000 0:00:00  1/21/2001 0:00:00  1/21/2002 0:00:00  1/21/2003 0:00:00  1/21/2004 0:00:00  1/21/2005 0:00:00  1/21/2006 0:00:00  1/21/2007 0:00:00 
##                402                 31                 37                 18                  4                  2                 24                 52                150 
##  1/21/2008 0:00:00  1/21/2009 0:00:00  1/21/2010 0:00:00  1/21/2011 0:00:00  1/22/1993 0:00:00  1/22/1994 0:00:00  1/22/1995 0:00:00  1/22/1996 0:00:00  1/22/1997 0:00:00 
##                 37                 11                221                 59                  6                  1                  2                 22                 57 
##  1/22/1998 0:00:00  1/22/1999 0:00:00  1/22/2000 0:00:00  1/22/2002 0:00:00  1/22/2003 0:00:00  1/22/2004 0:00:00  1/22/2005 0:00:00  1/22/2006 0:00:00  1/22/2007 0:00:00 
##                 49                445                 32                 18                 49                  8                 64                 13                 28 
##  1/22/2008 0:00:00  1/22/2009 0:00:00  1/22/2010 0:00:00  1/22/2011 0:00:00  1/23/1993 0:00:00  1/23/1995 0:00:00  1/23/1996 0:00:00  1/23/1997 0:00:00  1/23/1998 0:00:00 
##                 77                 28                 87                 52                 10                  2                 19                 50                 77 
##  1/23/1999 0:00:00  1/23/2000 0:00:00  1/23/2001 0:00:00  1/23/2002 0:00:00  1/23/2003 0:00:00  1/23/2004 0:00:00  1/23/2005 0:00:00  1/23/2006 0:00:00  1/23/2007 0:00:00 
##                120                 30                  7                102                 37                 20                 92                 62                  9 
##  1/23/2008 0:00:00  1/23/2009 0:00:00  1/23/2010 0:00:00  1/23/2011 0:00:00  1/24/1993 0:00:00  1/24/1994 0:00:00  1/24/1995 0:00:00  1/24/1996 0:00:00  1/24/1997 0:00:00 
##                 23                 11                 52                 43                  2                  1                  2                 69                285 
##  1/24/1998 0:00:00  1/24/1999 0:00:00  1/24/2000 0:00:00  1/24/2001 0:00:00  1/24/2002 0:00:00  1/24/2003 0:00:00  1/24/2004 0:00:00  1/24/2005 0:00:00  1/24/2006 0:00:00 
##                 45                 84                 79                  9                204                 22                 18                 12                 36 
##  1/24/2007 0:00:00  1/24/2008 0:00:00  1/24/2009 0:00:00  1/24/2010 0:00:00  1/24/2011 0:00:00  1/25/1993 0:00:00  1/25/1994 0:00:00  1/25/1995 0:00:00  1/25/1996 0:00:00 
##                  9                 38                  9                123                 18                  4                  1                  2                 34 
##  1/25/1997 0:00:00  1/25/1998 0:00:00  1/25/1999 0:00:00  1/25/2000 0:00:00  1/25/2001 0:00:00  1/25/2002 0:00:00  1/25/2003 0:00:00  1/25/2004 0:00:00  1/25/2005 0:00:00 
##                 79                  8                 25                 60                 19                 17                  9                 66                  5 
##  1/25/2006 0:00:00  1/25/2007 0:00:00  1/25/2008 0:00:00  1/25/2009 0:00:00  1/25/2010 0:00:00  1/25/2011 0:00:00  1/26/1993 0:00:00  1/26/1994 0:00:00  1/26/1995 0:00:00 
##                 25                 20                 49                 25                432                 63                  4                  2                  5 
##  1/26/1996 0:00:00  1/26/1997 0:00:00  1/26/1998 0:00:00  1/26/1999 0:00:00  1/26/2000 0:00:00  1/26/2001 0:00:00  1/26/2002 0:00:00  1/26/2003 0:00:00  1/26/2004 0:00:00 
##                 78                 32                 14                 23                 38                 26                 22                 14                 76 
##  1/26/2005 0:00:00  1/26/2006 0:00:00  1/26/2007 0:00:00  1/26/2008 0:00:00  1/26/2009 0:00:00  1/26/2010 0:00:00  1/26/2011 0:00:00  1/27/1994 0:00:00  1/27/1995 0:00:00 
##                  8                 28                 21                 29                 32                 40                 71                 29                  9 
##  1/27/1996 0:00:00  1/27/1997 0:00:00  1/27/1998 0:00:00  1/27/1999 0:00:00  1/27/2000 0:00:00  1/27/2001 0:00:00  1/27/2002 0:00:00  1/27/2003 0:00:00  1/27/2004 0:00:00 
##                107                 97                  8                 15                 27                 22                 21                  9                 50 
##  1/27/2005 0:00:00  1/27/2006 0:00:00  1/27/2007 0:00:00  1/27/2008 0:00:00  1/27/2009 0:00:00  1/27/2010 0:00:00  1/27/2011 0:00:00  1/28/1994 0:00:00  1/28/1995 0:00:00 
##                 16                  5                 10                 80                 49                 16                 64                  7                  1 
##  1/28/1996 0:00:00  1/28/1997 0:00:00  1/28/1998 0:00:00  1/28/1999 0:00:00  1/28/2000 0:00:00  1/28/2001 0:00:00  1/28/2002 0:00:00  1/28/2003 0:00:00  1/28/2004 0:00:00 
##                 54                 36                143                 21                 36                 31                 20                 17                 42 
##  1/28/2005 0:00:00  1/28/2006 0:00:00  1/28/2007 0:00:00  1/28/2008 0:00:00  1/28/2009 0:00:00  1/28/2010 0:00:00  1/28/2011 0:00:00  1/29/1993 0:00:00  1/29/1994 0:00:00 
##                 30                 31                 25                157                230                 64                  4                  2                 12 
##  1/29/1995 0:00:00  1/29/1996 0:00:00  1/29/1997 0:00:00  1/29/1998 0:00:00  1/29/1999 0:00:00  1/29/2000 0:00:00  1/29/2001 0:00:00  1/29/2002 0:00:00  1/29/2003 0:00:00 
##                  4                 30                 11                 27                 96                 26                 93                 23                 10 
##  1/29/2004 0:00:00  1/29/2005 0:00:00  1/29/2006 0:00:00  1/29/2007 0:00:00  1/29/2008 0:00:00  1/29/2009 0:00:00  1/29/2010 0:00:00  1/29/2011 0:00:00   1/3/1993 0:00:00 
##                 27                 38                 12                 38                668                 29                124                 21                  8 
##   1/3/1994 0:00:00   1/3/1995 0:00:00   1/3/1996 0:00:00   1/3/1997 0:00:00   1/3/1998 0:00:00   1/3/1999 0:00:00   1/3/2000 0:00:00   1/3/2001 0:00:00   1/3/2002 0:00:00 
##                  4                  1                 67                 31                 12                176                366                 15                 41 
##   1/3/2003 0:00:00   1/3/2004 0:00:00   1/3/2005 0:00:00   1/3/2006 0:00:00   1/3/2007 0:00:00   1/3/2008 0:00:00   1/3/2009 0:00:00   1/3/2010 0:00:00   1/3/2011 0:00:00 
##                 25                 34                 48                 50                 37                 67                 65                 44                 20 
##  1/30/1993 0:00:00  1/30/1994 0:00:00  1/30/1995 0:00:00  1/30/1996 0:00:00  1/30/1997 0:00:00  1/30/1998 0:00:00  1/30/1999 0:00:00  1/30/2000 0:00:00  1/30/2001 0:00:00 
##                  1                  5                  2                 30                  8                  8                 63                 48                 53 
##  1/30/2002 0:00:00  1/30/2003 0:00:00  1/30/2004 0:00:00  1/30/2005 0:00:00  1/30/2006 0:00:00  1/30/2007 0:00:00  1/30/2008 0:00:00  1/30/2009 0:00:00  1/30/2010 0:00:00 
##                 25                 14                 43                 40                 31                 20                195                 19                213 
##  1/30/2011 0:00:00  1/31/1993 0:00:00  1/31/1994 0:00:00  1/31/1995 0:00:00  1/31/1996 0:00:00  1/31/1997 0:00:00  1/31/1998 0:00:00  1/31/1999 0:00:00  1/31/2000 0:00:00 
##                 26                  4                  4                  6                 33                 16                 45                 61                 37 
##  1/31/2001 0:00:00  1/31/2002 0:00:00  1/31/2003 0:00:00  1/31/2004 0:00:00  1/31/2005 0:00:00  1/31/2006 0:00:00  1/31/2007 0:00:00  1/31/2008 0:00:00  1/31/2009 0:00:00 
##                 33                131                 45                 29                 27                 52                 57                245                 59 
##  1/31/2010 0:00:00  1/31/2011 0:00:00   1/4/1993 0:00:00   1/4/1994 0:00:00   1/4/1995 0:00:00   1/4/1996 0:00:00   1/4/1997 0:00:00   1/4/1998 0:00:00   1/4/1999 0:00:00 
##                 66                126                  7                  9                  1                 21                 58                 85                 10 
##   1/4/2000 0:00:00   1/4/2001 0:00:00   1/4/2002 0:00:00   1/4/2003 0:00:00   1/4/2004 0:00:00   1/4/2005 0:00:00   1/4/2006 0:00:00   1/4/2007 0:00:00   1/4/2008 0:00:00 
##                 59                 17                 14                 41                 32                 53                  7                 40                122 
##   1/4/2009 0:00:00   1/4/2010 0:00:00   1/4/2011 0:00:00   1/5/1993 0:00:00   1/5/1994 0:00:00   1/5/1995 0:00:00   1/5/1996 0:00:00   1/5/1997 0:00:00   1/5/1998 0:00:00 
##                 55                 24                 10                 14                  6                  6                  7                137                106 
##   1/5/1999 0:00:00   1/5/2000 0:00:00   1/5/2001 0:00:00   1/5/2002 0:00:00   1/5/2003 0:00:00   1/5/2004 0:00:00   1/5/2005 0:00:00   1/5/2006 0:00:00   1/5/2007 0:00:00 
##                 11                  5                 28                 18                 34                 37                130                 11                140 
##   1/5/2008 0:00:00   1/5/2009 0:00:00   1/5/2010 0:00:00   1/5/2011 0:00:00   1/6/1993 0:00:00   1/6/1994 0:00:00   1/6/1995 0:00:00   1/6/1996 0:00:00   1/6/1997 0:00:00 
##                 67                 49                 32                 15                  4                  5                 15                 27                 22 
##   1/6/1998 0:00:00   1/6/1999 0:00:00   1/6/2000 0:00:00   1/6/2001 0:00:00   1/6/2002 0:00:00   1/6/2003 0:00:00   1/6/2004 0:00:00   1/6/2005 0:00:00   1/6/2006 0:00:00 
##                137                 13                  8                  5                 32                 20                 32                149                  2 
##   1/6/2007 0:00:00   1/6/2008 0:00:00   1/6/2009 0:00:00   1/6/2010 0:00:00   1/6/2011 0:00:00   1/7/1993 0:00:00   1/7/1994 0:00:00   1/7/1995 0:00:00   1/7/1996 0:00:00 
##                 52                 26                 73                 63                 21                  7                  5                 14                 75 
##   1/7/1997 0:00:00   1/7/1998 0:00:00   1/7/1999 0:00:00   1/7/2000 0:00:00   1/7/2001 0:00:00   1/7/2002 0:00:00   1/7/2003 0:00:00   1/7/2004 0:00:00   1/7/2005 0:00:00 
##                 42                235                 15                  8                 10                 45                 12                 23                 58 
##   1/7/2006 0:00:00   1/7/2007 0:00:00   1/7/2008 0:00:00   1/7/2009 0:00:00   1/7/2010 0:00:00   1/7/2011 0:00:00   1/8/1993 0:00:00   1/8/1994 0:00:00   1/8/1995 0:00:00 
##                  7                 53                282                216                175                 39                  5                  9                  3 
##   1/8/1996 0:00:00   1/8/1997 0:00:00   1/8/1998 0:00:00   1/8/1999 0:00:00   1/8/2000 0:00:00   1/8/2001 0:00:00   1/8/2002 0:00:00   1/8/2003 0:00:00   1/8/2004 0:00:00 
##                 93                 53                242                 44                  6                 14                 12                 17                 13 
##   1/8/2005 0:00:00   1/8/2006 0:00:00   1/8/2007 0:00:00   1/8/2008 0:00:00   1/8/2009 0:00:00   1/8/2010 0:00:00   1/8/2011 0:00:00   1/9/1993 0:00:00   1/9/1994 0:00:00 
##                 54                 12                 53                323                 83                 95                 92                  4                  2 
##   1/9/1995 0:00:00   1/9/1996 0:00:00   1/9/1997 0:00:00   1/9/1998 0:00:00   1/9/1999 0:00:00   1/9/2000 0:00:00   1/9/2001 0:00:00   1/9/2002 0:00:00   1/9/2003 0:00:00 
##                  4                  7                 80                128                 65                 46                  9                 13                 17 
##   1/9/2004 0:00:00   1/9/2005 0:00:00   1/9/2006 0:00:00   1/9/2007 0:00:00   1/9/2008 0:00:00   1/9/2009 0:00:00   1/9/2010 0:00:00   1/9/2011 0:00:00  10/1/1994 0:00:00 
##                 30                 63                 11                 25                190                 92                 40                134                  2 
##  10/1/1995 0:00:00  10/1/1996 0:00:00  10/1/1997 0:00:00  10/1/1998 0:00:00  10/1/1999 0:00:00  10/1/2000 0:00:00  10/1/2001 0:00:00  10/1/2002 0:00:00  10/1/2003 0:00:00 
##                  1                  2                  9                 47                 11                  8                  5                172                 14 
##  10/1/2004 0:00:00  10/1/2005 0:00:00  10/1/2006 0:00:00  10/1/2007 0:00:00  10/1/2008 0:00:00  10/1/2009 0:00:00  10/1/2010 0:00:00  10/1/2011 0:00:00 10/10/1993 0:00:00 
##                  5                 20                 21                 43                 35                112                137                  2                  1 
## 10/10/1995 0:00:00 10/10/1997 0:00:00 10/10/1998 0:00:00 10/10/1999 0:00:00 10/10/2000 0:00:00 10/10/2001 0:00:00 10/10/2002 0:00:00 10/10/2003 0:00:00 10/10/2004 0:00:00 
##                  1                  7                  5                  3                 25                135                 20                 32                 19 
## 10/10/2005 0:00:00 10/10/2006 0:00:00 10/10/2007 0:00:00 10/10/2008 0:00:00 10/10/2009 0:00:00 10/10/2010 0:00:00 10/10/2011 0:00:00 10/11/1997 0:00:00 10/11/1998 0:00:00 
##                 52                 32                 39                 22                 30                 38                 34                 96                 22 
## 10/11/1999 0:00:00 10/11/2000 0:00:00 10/11/2001 0:00:00 10/11/2002 0:00:00 10/11/2003 0:00:00 10/11/2004 0:00:00 10/11/2005 0:00:00 10/11/2006 0:00:00 10/11/2007 0:00:00 
##                  7                  6                 70                 76                  8                  7                 42                 74                 31 
## 10/11/2008 0:00:00 10/11/2009 0:00:00 10/11/2010 0:00:00 10/11/2011 0:00:00 10/12/1993 0:00:00 10/12/1994 0:00:00 10/12/1995 0:00:00 10/12/1996 0:00:00 10/12/1997 0:00:00 
##                 36                 14                 72                 60                  1                  1                  2                  3                 15 
## 10/12/1998 0:00:00 10/12/1999 0:00:00 10/12/2000 0:00:00 10/12/2001 0:00:00 10/12/2002 0:00:00 10/12/2003 0:00:00 10/12/2004 0:00:00 10/12/2005 0:00:00 10/12/2006 0:00:00 
##                  6                  6                 18                164                 35                 19                 11                 12                 30 
## 10/12/2007 0:00:00 10/12/2008 0:00:00 10/12/2009 0:00:00 10/12/2010 0:00:00 10/12/2011 0:00:00 10/13/1994 0:00:00 10/13/1995 0:00:00 10/13/1997 0:00:00 10/13/1998 0:00:00 
##                 17                 64                 64                 68                 27                  4                  1                 40                  7 
## 10/13/1999 0:00:00 10/13/2000 0:00:00 10/13/2001 0:00:00 10/13/2002 0:00:00 10/13/2003 0:00:00 10/13/2004 0:00:00 10/13/2005 0:00:00 10/13/2006 0:00:00 10/13/2007 0:00:00 
##                189                 30                242                 32                 17                 34                 28                 39                 38 
## 10/13/2008 0:00:00 10/13/2009 0:00:00 10/13/2010 0:00:00 10/13/2011 0:00:00 10/14/1995 0:00:00 10/14/1996 0:00:00 10/14/1997 0:00:00 10/14/1998 0:00:00 10/14/1999 0:00:00 
##                 26                158                 22                 87                  4                 11                  9                 38                 10 
## 10/14/2000 0:00:00 10/14/2001 0:00:00 10/14/2002 0:00:00 10/14/2003 0:00:00 10/14/2004 0:00:00 10/14/2005 0:00:00 10/14/2006 0:00:00 10/14/2007 0:00:00 10/14/2008 0:00:00 
##                 39                 21                  7                 63                 17                 20                 28                 82                 12 
## 10/14/2009 0:00:00 10/14/2010 0:00:00 10/14/2011 0:00:00 10/15/1993 0:00:00 10/15/1995 0:00:00 10/15/1996 0:00:00 10/15/1997 0:00:00 10/15/1998 0:00:00 10/15/1999 0:00:00 
##                 34                 35                 13                  1                  4                  5                  3                  6                 12 
## 10/15/2000 0:00:00 10/15/2001 0:00:00 10/15/2002 0:00:00 10/15/2003 0:00:00 10/15/2004 0:00:00 10/15/2005 0:00:00 10/15/2006 0:00:00 10/15/2007 0:00:00 10/15/2008 0:00:00 
##                 11                 10                 23                 49                 12                 16                 28                 30                 13 
## 10/15/2009 0:00:00 10/15/2010 0:00:00 10/15/2011 0:00:00 10/16/1993 0:00:00 10/16/1994 0:00:00 10/16/1995 0:00:00 10/16/1996 0:00:00 10/16/1998 0:00:00 10/16/1999 0:00:00 
##                 38                 20                 10                  2                  4                  1                 47                 61                 17 
## 10/16/2000 0:00:00 10/16/2001 0:00:00 10/16/2002 0:00:00 10/16/2003 0:00:00 10/16/2004 0:00:00 10/16/2005 0:00:00 10/16/2006 0:00:00 10/16/2007 0:00:00 10/16/2008 0:00:00 
##                 11                 15                  8                  9                 10                 40                151                 29                  2 
## 10/16/2009 0:00:00 10/16/2010 0:00:00 10/16/2011 0:00:00 10/17/1994 0:00:00 10/17/1995 0:00:00 10/17/1996 0:00:00 10/17/1997 0:00:00 10/17/1998 0:00:00 10/17/1999 0:00:00 
##                 21                 13                  9                 11                  1                172                  2                 82                 51 
## 10/17/2000 0:00:00 10/17/2001 0:00:00 10/17/2002 0:00:00 10/17/2003 0:00:00 10/17/2004 0:00:00 10/17/2005 0:00:00 10/17/2006 0:00:00 10/17/2007 0:00:00 10/17/2008 0:00:00 
##                 13                  8                  7                 11                 14                 29                 71                346                  2 
## 10/17/2009 0:00:00 10/17/2010 0:00:00 10/17/2011 0:00:00 10/18/1993 0:00:00 10/18/1994 0:00:00 10/18/1995 0:00:00 10/18/1996 0:00:00 10/18/1997 0:00:00 10/18/1998 0:00:00 
##                  7                  5                 51                  2                 17                  6                 54                  5                 96 
## 10/18/1999 0:00:00 10/18/2000 0:00:00 10/18/2001 0:00:00 10/18/2002 0:00:00 10/18/2003 0:00:00 10/18/2004 0:00:00 10/18/2005 0:00:00 10/18/2006 0:00:00 10/18/2007 0:00:00 
##                 52                  4                  9                 28                  2                177                 34                 35                533 
## 10/18/2008 0:00:00 10/18/2009 0:00:00 10/18/2010 0:00:00 10/18/2011 0:00:00 10/19/1993 0:00:00 10/19/1994 0:00:00 10/19/1995 0:00:00 10/19/1996 0:00:00 10/19/1997 0:00:00 
##                  4                 25                  3                 59                  1                  3                  2                 82                  4 
## 10/19/1998 0:00:00 10/19/1999 0:00:00 10/19/2000 0:00:00 10/19/2001 0:00:00 10/19/2002 0:00:00 10/19/2003 0:00:00 10/19/2004 0:00:00 10/19/2005 0:00:00 10/19/2006 0:00:00 
##                 12                  8                 10                  6                 18                  4                135                 65                 64 
## 10/19/2007 0:00:00 10/19/2008 0:00:00 10/19/2009 0:00:00 10/19/2010 0:00:00 10/19/2011 0:00:00  10/2/1994 0:00:00  10/2/1995 0:00:00  10/2/1996 0:00:00  10/2/1997 0:00:00 
##                 93                  3                  4                 25                 37                  1                  3                  6                 17 
##  10/2/1998 0:00:00  10/2/1999 0:00:00  10/2/2000 0:00:00  10/2/2001 0:00:00  10/2/2002 0:00:00  10/2/2003 0:00:00  10/2/2004 0:00:00  10/2/2005 0:00:00  10/2/2006 0:00:00 
##                 79                 11                  1                  1                 28                  9                 32                 57                236 
##  10/2/2007 0:00:00  10/2/2008 0:00:00  10/2/2009 0:00:00  10/2/2010 0:00:00  10/2/2011 0:00:00 10/20/1993 0:00:00 10/20/1994 0:00:00 10/20/1995 0:00:00 10/20/1996 0:00:00 
##                 52                  1                 18                 33                  4                  2                  1                  6                109 
## 10/20/1997 0:00:00 10/20/1998 0:00:00 10/20/1999 0:00:00 10/20/2000 0:00:00 10/20/2001 0:00:00 10/20/2002 0:00:00 10/20/2003 0:00:00 10/20/2004 0:00:00 10/20/2005 0:00:00 
##                  3                 12                  6                  4                  2                 18                 13                 41                  9 
## 10/20/2006 0:00:00 10/20/2007 0:00:00 10/20/2008 0:00:00 10/20/2009 0:00:00 10/20/2010 0:00:00 10/20/2011 0:00:00 10/21/1995 0:00:00 10/21/1996 0:00:00 10/21/1997 0:00:00 
##                 34                 35                  4                  7                 22                  6                 12                241                  8 
## 10/21/1998 0:00:00 10/21/1999 0:00:00 10/21/2000 0:00:00 10/21/2001 0:00:00 10/21/2002 0:00:00 10/21/2003 0:00:00 10/21/2004 0:00:00 10/21/2005 0:00:00 10/21/2006 0:00:00 
##                  2                  5                 13                 49                 37                  5                 20                 71                 22 
## 10/21/2007 0:00:00 10/21/2008 0:00:00 10/21/2009 0:00:00 10/21/2010 0:00:00 10/21/2011 0:00:00 10/22/1994 0:00:00 10/22/1995 0:00:00 10/22/1996 0:00:00 10/22/1997 0:00:00 
##                 45                 53                 21                 41                  1                  1                  9                 53                  7 
## 10/22/1998 0:00:00 10/22/1999 0:00:00 10/22/2000 0:00:00 10/22/2001 0:00:00 10/22/2002 0:00:00 10/22/2003 0:00:00 10/22/2004 0:00:00 10/22/2005 0:00:00 10/22/2006 0:00:00 
##                 10                  1                 49                 64                 18                  3                 25                 15                  7 
## 10/22/2007 0:00:00 10/22/2008 0:00:00 10/22/2009 0:00:00 10/22/2010 0:00:00 10/22/2011 0:00:00 10/23/1995 0:00:00 10/23/1996 0:00:00 10/23/1997 0:00:00 10/23/1998 0:00:00 
##                 57                 34                 94                  8                 72                 15                 18                 90                  3 
## 10/23/1999 0:00:00 10/23/2000 0:00:00 10/23/2001 0:00:00 10/23/2002 0:00:00 10/23/2003 0:00:00 10/23/2004 0:00:00 10/23/2005 0:00:00 10/23/2006 0:00:00 10/23/2007 0:00:00 
##                  8                 65                112                 26                  4                 37                 19                  5                 35 
## 10/23/2008 0:00:00 10/23/2009 0:00:00 10/23/2010 0:00:00 10/23/2011 0:00:00 10/24/1995 0:00:00 10/24/1996 0:00:00 10/24/1997 0:00:00 10/24/1998 0:00:00 10/24/1999 0:00:00 
##                  4                 16                 61                 20                  2                  6                 46                  5                  5 
## 10/24/2000 0:00:00 10/24/2001 0:00:00 10/24/2002 0:00:00 10/24/2003 0:00:00 10/24/2004 0:00:00 10/24/2005 0:00:00 10/24/2006 0:00:00 10/24/2007 0:00:00 10/24/2008 0:00:00 
##                 41                730                 45                 11                 16                 31                  3                 19                 48 
## 10/24/2009 0:00:00 10/24/2010 0:00:00 10/24/2011 0:00:00 10/25/1993 0:00:00 10/25/1995 0:00:00 10/25/1996 0:00:00 10/25/1997 0:00:00 10/25/1998 0:00:00 10/25/1999 0:00:00 
##                 33                301                  4                  1                  2                 16                200                 20                  9 
## 10/25/2000 0:00:00 10/25/2001 0:00:00 10/25/2002 0:00:00 10/25/2003 0:00:00 10/25/2004 0:00:00 10/25/2005 0:00:00 10/25/2006 0:00:00 10/25/2007 0:00:00 10/25/2008 0:00:00 
##                 46                 50                 15                 25                 23                 40                  6                 10                 38 
## 10/25/2009 0:00:00 10/25/2010 0:00:00 10/25/2011 0:00:00 10/26/1995 0:00:00 10/26/1996 0:00:00 10/26/1997 0:00:00 10/26/1998 0:00:00 10/26/1999 0:00:00 10/26/2000 0:00:00 
##                 40                218                 13                  1                 97                 91                  8                  1                 28 
## 10/26/2001 0:00:00 10/26/2002 0:00:00 10/26/2003 0:00:00 10/26/2004 0:00:00 10/26/2005 0:00:00 10/26/2006 0:00:00 10/26/2007 0:00:00 10/26/2008 0:00:00 10/26/2009 0:00:00 
##                 11                 13                 17                 32                 26                 76                  6                116                 63 
## 10/26/2010 0:00:00 10/26/2011 0:00:00 10/27/1995 0:00:00 10/27/1996 0:00:00 10/27/1997 0:00:00 10/27/1998 0:00:00 10/27/1999 0:00:00 10/27/2000 0:00:00 10/27/2001 0:00:00 
##                682                 34                  2                 38                 32                 27                  8                 21                  1 
## 10/27/2002 0:00:00 10/27/2003 0:00:00 10/27/2004 0:00:00 10/27/2005 0:00:00 10/27/2006 0:00:00 10/27/2007 0:00:00 10/27/2008 0:00:00 10/27/2009 0:00:00 10/27/2010 0:00:00 
##                 14                 66                 37                 29                 65                 95                  4                 46                229 
## 10/27/2011 0:00:00 10/28/1993 0:00:00 10/28/1995 0:00:00 10/28/1996 0:00:00 10/28/1998 0:00:00 10/28/1999 0:00:00 10/28/2000 0:00:00 10/28/2001 0:00:00 10/28/2002 0:00:00 
##                 14                  2                  5                 35                 23                  8                 73                  6                 56 
## 10/28/2003 0:00:00 10/28/2004 0:00:00 10/28/2005 0:00:00 10/28/2006 0:00:00 10/28/2007 0:00:00 10/28/2008 0:00:00 10/28/2009 0:00:00 10/28/2010 0:00:00 10/28/2011 0:00:00 
##                 35                 17                  5                129                 21                 35                 30                  9                 14 
## 10/29/1993 0:00:00 10/29/1995 0:00:00 10/29/1996 0:00:00 10/29/1997 0:00:00 10/29/1998 0:00:00 10/29/1999 0:00:00 10/29/2000 0:00:00 10/29/2001 0:00:00 10/29/2002 0:00:00 
##                  1                  4                193                  2                 20                 48                 61                  4                 65 
## 10/29/2003 0:00:00 10/29/2004 0:00:00 10/29/2005 0:00:00 10/29/2006 0:00:00 10/29/2007 0:00:00 10/29/2008 0:00:00 10/29/2009 0:00:00 10/29/2010 0:00:00 10/29/2011 0:00:00 
##                 54                156                  9                109                 47                 44                170                  1                 63 
##  10/3/1994 0:00:00  10/3/1995 0:00:00  10/3/1996 0:00:00  10/3/1997 0:00:00  10/3/1998 0:00:00  10/3/1999 0:00:00  10/3/2000 0:00:00  10/3/2001 0:00:00  10/3/2002 0:00:00 
##                  9                  4                  4                  4                 15                  8                 46                  4                 72 
##  10/3/2003 0:00:00  10/3/2004 0:00:00  10/3/2005 0:00:00  10/3/2006 0:00:00  10/3/2007 0:00:00  10/3/2008 0:00:00  10/3/2009 0:00:00  10/3/2010 0:00:00  10/3/2011 0:00:00 
##                 17                 46                 30                 78                 13                  2                 15                  7                 14 
## 10/30/1993 0:00:00 10/30/1995 0:00:00 10/30/1996 0:00:00 10/30/1997 0:00:00 10/30/1998 0:00:00 10/30/1999 0:00:00 10/30/2000 0:00:00 10/30/2001 0:00:00 10/30/2002 0:00:00 
##                  6                  3                 80                 12                 52                  6                 15                  2                 33 
## 10/30/2003 0:00:00 
##                 17 
##  [ reached getOption("max.print") -- omitted 5663 entries ]
## [1] "Unique values of var1:"
##    [1] ""                   "1/23/1995 0:00:00"  "2/10/1994 0:00:00"  "2/8/1995 0:00:00"   "3/13/1993 0:00:00"  "2/12/1995 0:00:00"  "10/5/1995 0:00:00"  "6/26/1994 0:00:00" 
##    [9] "10/4/1995 0:00:00"  "2/3/1995 0:00:00"   "7/10/1995 0:00:00"  "6/10/1995 0:00:00"  "5/15/1994 0:00:00"  "7/8/1995 0:00:00"   "5/18/1995 0:00:00"  "7/18/1995 0:00:00" 
##   [17] "7/21/1995 0:00:00"  "2/11/1995 0:00:00"  "6/1/1995 0:00:00"   "6/24/1995 0:00:00"  "7/13/1995 0:00:00"  "7/8/1994 0:00:00"   "6/6/1995 0:00:00"   "5/15/1995 0:00:00" 
##   [25] "4/15/1994 0:00:00"  "7/19/1995 0:00:00"  "7/9/1995 0:00:00"   "9/11/1993 0:00:00"  "9/6/1994 0:00:00"   "9/18/1994 0:00:00"  "9/20/1994 0:00:00"  "9/24/1994 0:00:00" 
##   [33] "9/30/1994 0:00:00"  "5/31/1995 0:00:00"  "5/20/1995 0:00:00"  "11/3/1995 0:00:00"  "11/5/1995 0:00:00"  "11/9/1995 0:00:00"  "11/11/1995 0:00:00" "11/17/1995 0:00:00"
##   [41] "11/23/1995 0:00:00" "11/30/1995 0:00:00" "1/17/1993 0:00:00"  "11/21/1993 0:00:00" "10/2/1994 0:00:00"  "10/6/1994 0:00:00"  "10/17/1994 0:00:00" "10/22/1994 0:00:00"
##   [49] "10/31/1994 0:00:00" "6/14/1995 0:00:00"  "8/26/1994 0:00:00"  "11/4/1994 0:00:00"  "11/5/1994 0:00:00"  "11/10/1994 0:00:00" "11/12/1994 0:00:00" "11/16/1994 0:00:00"
##   [57] "11/17/1994 0:00:00" "11/19/1994 0:00:00" "11/24/1994 0:00:00" "11/26/1994 0:00:00" "11/30/1994 0:00:00" "12/14/1995 0:00:00" "10/2/1995 0:00:00"  "10/6/1995 0:00:00" 
##   [65] "10/10/1995 0:00:00" "10/16/1995 0:00:00" "10/18/1995 0:00:00" "10/20/1995 0:00:00" "10/22/1995 0:00:00" "10/23/1995 0:00:00" "10/25/1995 0:00:00" "12/3/1995 0:00:00" 
##   [73] "12/5/1995 0:00:00"  "12/11/1995 0:00:00" "12/23/1995 0:00:00" "1/13/1993 0:00:00"  "9/9/1995 0:00:00"   "9/15/1995 0:00:00"  "9/18/1995 0:00:00"  "9/25/1995 0:00:00" 
##   [81] "9/27/1995 0:00:00"  "2/7/1993 0:00:00"   "1/31/1993 0:00:00"  "1/3/1993 0:00:00"   "2/27/1993 0:00:00"  "3/22/1993 0:00:00"  "4/14/1994 0:00:00"  "3/8/1994 0:00:00"  
##   [89] "6/5/1994 0:00:00"   "2/6/1995 0:00:00"   "2/15/1995 0:00:00"  "2/18/1995 0:00:00"  "2/19/1995 0:00:00"  "2/21/1995 0:00:00"  "2/28/1995 0:00:00"  "3/2/1995 0:00:00"  
##   [97] "3/3/1995 0:00:00"   "3/6/1995 0:00:00"   "3/8/1995 0:00:00"   "3/7/1995 0:00:00"   "3/13/1995 0:00:00"  "3/17/1995 0:00:00"  "3/23/1995 0:00:00"  "3/25/1995 0:00:00" 
##  [105] "3/28/1995 0:00:00"  "4/3/1995 0:00:00"   "4/4/1995 0:00:00"   "4/11/1995 0:00:00"  "4/12/1995 0:00:00"  "4/16/1995 0:00:00"  "4/21/1995 0:00:00"  "4/22/1995 0:00:00" 
##  [113] "4/25/1995 0:00:00"  "4/29/1995 0:00:00"  "4/28/1995 0:00:00"  "1/18/1993 0:00:00"  "1/4/1995 0:00:00"   "1/14/1995 0:00:00"  "1/15/1995 0:00:00"  "1/17/1995 0:00:00" 
##  [121] "1/21/1995 0:00:00"  "1/24/1995 0:00:00"  "1/29/1995 0:00:00"  "12/20/1995 0:00:00" "12/30/1995 0:00:00" "12/7/1994 0:00:00"  "12/4/1994 0:00:00"  "12/8/1994 0:00:00" 
##  [129] "12/10/1994 0:00:00" "12/13/1994 0:00:00" "12/16/1994 0:00:00" "12/18/1994 0:00:00" "12/21/1994 0:00:00" "12/20/1994 0:00:00" "12/23/1994 0:00:00" "12/24/1994 0:00:00"
##  [137] "12/25/1994 0:00:00" "12/29/1994 0:00:00" "12/31/1994 0:00:00" "6/30/1995 0:00:00"  "10/30/1995 0:00:00" "1/4/1993 0:00:00"   "2/25/1993 0:00:00"  "2/15/1993 0:00:00" 
##  [145] "2/4/1993 0:00:00"   "9/23/1993 0:00:00"  "8/13/1993 0:00:00"  "8/19/1993 0:00:00"  "9/14/1993 0:00:00"  "9/30/1993 0:00:00"  "10/12/1993 0:00:00" "5/19/1995 0:00:00" 
##  [153] "12/9/1995 0:00:00"  "10/15/1993 0:00:00" "10/20/1993 0:00:00" "11/25/1993 0:00:00" "11/11/1993 0:00:00" "1/26/1993 0:00:00"  "9/6/1993 0:00:00"   "12/6/1993 0:00:00" 
##  [161] "5/12/1994 0:00:00"  "5/24/1995 0:00:00"  "12/19/1993 0:00:00" "12/17/1995 0:00:00" "1/5/1995 0:00:00"   "2/14/1995 0:00:00"  "1/26/1995 0:00:00"  "10/16/1994 0:00:00"
##  [169] "2/21/1993 0:00:00"  "7/11/1995 0:00:00"  "2/24/1993 0:00:00"  "12/6/1994 0:00:00"  "1/12/1993 0:00:00"  "1/19/1993 0:00:00"  "2/10/1993 0:00:00"  "2/28/1993 0:00:00" 
##  [177] "2/13/1995 0:00:00"  "7/14/1995 0:00:00"  "3/12/1995 0:00:00"  "3/24/1995 0:00:00"  "3/29/1995 0:00:00"  "2/9/1993 0:00:00"   "2/22/1995 0:00:00"  "3/5/1993 0:00:00"  
##  [185] "1/25/1995 0:00:00"  "7/25/1995 0:00:00"  "1/6/1995 0:00:00"   "1/19/1995 0:00:00"  "1/17/1994 0:00:00"  "3/9/1994 0:00:00"   "2/11/1994 0:00:00"  "5/30/1993 0:00:00" 
##  [193] "5/25/1994 0:00:00"  "5/13/1995 0:00:00"  "6/5/1995 0:00:00"   "7/22/1994 0:00:00"  "5/26/1994 0:00:00"  "6/23/1995 0:00:00"  "5/14/1995 0:00:00"  "1/22/1993 0:00:00" 
##  [201] "1/14/1993 0:00:00"  "2/23/1993 0:00:00"  "11/30/1993 0:00:00" "3/9/1995 0:00:00"   "3/4/1995 0:00:00"   "3/5/1995 0:00:00"   "4/25/1994 0:00:00"  "7/24/1994 0:00:00" 
##  [209] "6/7/1994 0:00:00"   "6/8/1995 0:00:00"   "7/3/1995 0:00:00"   "1/11/1995 0:00:00"  "3/6/1994 0:00:00"   "12/13/1995 0:00:00" "12/12/1995 0:00:00" "12/9/1994 0:00:00" 
##  [217] "1/9/1995 0:00:00"   "12/5/1994 0:00:00"  "11/3/1993 0:00:00"  "10/31/1993 0:00:00" "12/3/1993 0:00:00"  "12/24/1993 0:00:00" "1/10/1993 0:00:00"  "1/27/1994 0:00:00" 
##  [225] "2/4/1994 0:00:00"   "2/7/1994 0:00:00"   "2/20/1994 0:00:00"  "3/25/1994 0:00:00"  "4/24/1994 0:00:00"  "4/2/1993 0:00:00"   "11/26/1993 0:00:00" "4/11/1993 0:00:00" 
##  [233] "1/25/1994 0:00:00"  "4/24/1993 0:00:00"  "5/12/1995 0:00:00"  "4/15/1993 0:00:00"  "6/6/1994 0:00:00"   "2/21/1994 0:00:00"  "12/11/1993 0:00:00" "12/14/1993 0:00:00"
##  [241] "2/8/1994 0:00:00"   "2/20/1993 0:00:00"  "1/10/1995 0:00:00"  "3/5/1994 0:00:00"   "12/8/1993 0:00:00"  "12/15/1995 0:00:00" "3/11/1995 0:00:00"  "6/26/1995 0:00:00" 
##  [249] "6/16/1995 0:00:00"  "3/10/1995 0:00:00"  "1/24/1994 0:00:00"  "3/26/1993 0:00:00"  "1/30/1993 0:00:00"  "3/24/1993 0:00:00"  "11/14/1993 0:00:00" "1/7/1993 0:00:00"  
##  [257] "2/5/1993 0:00:00"   "7/16/1994 0:00:00"  "5/30/1995 0:00:00"  "6/3/1995 0:00:00"   "5/28/1994 0:00:00"  "6/2/1995 0:00:00"   "6/7/1995 0:00:00"   "5/15/1993 0:00:00" 
##  [265] "5/26/1993 0:00:00"  "7/20/1995 0:00:00"  "1/9/1993 0:00:00"   "4/13/1993 0:00:00"  "1/18/1995 0:00:00"  "3/15/1993 0:00:00"  "4/20/1993 0:00:00"  "4/25/1993 0:00:00" 
##  [273] "2/11/1993 0:00:00"  "3/28/1993 0:00:00"  "2/1/1993 0:00:00"   "3/2/1993 0:00:00"   "2/16/1993 0:00:00"  "3/18/1993 0:00:00"  "4/10/1993 0:00:00"  "3/12/1993 0:00:00" 
##  [281] "4/19/1993 0:00:00"  "3/30/1993 0:00:00"  "12/31/1995 0:00:00" "1/6/1994 0:00:00"   "1/11/1993 0:00:00"  "2/8/1993 0:00:00"   "4/19/1995 0:00:00"  "3/26/1995 0:00:00" 
##  [289] "4/10/1994 0:00:00"  "12/15/1994 0:00:00" "10/29/1993 0:00:00" "12/12/1993 0:00:00" "11/13/1994 0:00:00" "12/16/1993 0:00:00" "3/27/1995 0:00:00"  "11/12/1993 0:00:00"
##  [297] "3/22/1994 0:00:00"  "4/10/1995 0:00:00"  "9/13/1993 0:00:00"  "2/9/1994 0:00:00"   "5/1/1993 0:00:00"   "4/29/1994 0:00:00"  "4/26/1995 0:00:00"  "4/27/1994 0:00:00" 
##  [305] "4/5/1994 0:00:00"   "2/12/1994 0:00:00"  "3/29/1994 0:00:00"  "10/18/1993 0:00:00" "4/7/1994 0:00:00"   "3/30/1995 0:00:00"  "1/8/1995 0:00:00"   "1/12/1995 0:00:00" 
##  [313] "1/27/1995 0:00:00"  "12/10/1995 0:00:00" "5/10/1994 0:00:00"  "4/2/1994 0:00:00"   "3/20/1994 0:00:00"  "2/19/1994 0:00:00"  "11/13/1993 0:00:00" "5/16/1995 0:00:00" 
##  [321] "11/27/1993 0:00:00" "12/8/1995 0:00:00"  "3/26/1994 0:00:00"  "4/23/1995 0:00:00"  "12/27/1995 0:00:00" "12/29/1995 0:00:00" "12/6/1995 0:00:00"  "1/2/1994 0:00:00"  
##  [329] "3/12/1994 0:00:00"  "12/5/1993 0:00:00"  "12/2/1995 0:00:00"  "12/25/1993 0:00:00" "1/4/1994 0:00:00"   "1/7/1994 0:00:00"   "2/23/1994 0:00:00"  "12/22/1995 0:00:00"
##  [337] "2/24/1994 0:00:00"  "3/19/1994 0:00:00"  "12/31/1993 0:00:00" "3/23/1994 0:00:00"  "1/3/1994 0:00:00"   "4/12/1994 0:00:00"  "1/26/1994 0:00:00"  "1/5/1994 0:00:00"  
##  [345] "11/14/1994 0:00:00" "11/5/1993 0:00:00"  "1/30/1994 0:00:00"  "11/20/1994 0:00:00" "3/1/1994 0:00:00"   "12/21/1995 0:00:00" "9/21/1995 0:00:00"  "11/24/1993 0:00:00"
##  [353] "7/31/1994 0:00:00"  "6/3/1994 0:00:00"   "6/20/1994 0:00:00"  "7/23/1994 0:00:00"  "6/4/1995 0:00:00"   "6/22/1995 0:00:00"  "6/21/1994 0:00:00"  "5/16/1993 0:00:00" 
##  [361] "5/25/1993 0:00:00"  "2/4/1995 0:00:00"   "7/16/1995 0:00:00"  "10/28/1995 0:00:00" "7/2/1994 0:00:00"   "7/17/1994 0:00:00"  "5/7/1995 0:00:00"   "5/18/1994 0:00:00" 
##  [369] "7/17/1995 0:00:00"  "5/26/1995 0:00:00"  "6/2/1994 0:00:00"   "6/29/1995 0:00:00"  "6/21/1995 0:00:00"  "1/28/1994 0:00:00"  "2/13/1993 0:00:00"  "3/14/1993 0:00:00" 
##  [377] "4/23/1994 0:00:00"  "4/22/1994 0:00:00"  "4/17/1994 0:00:00"  "9/23/1994 0:00:00"  "12/30/1993 0:00:00" "1/16/1994 0:00:00"  "1/19/1994 0:00:00"  "11/7/1994 0:00:00" 
##  [385] "1/16/1995 0:00:00"  "7/15/1995 0:00:00"  "3/31/1993 0:00:00"  "4/29/1993 0:00:00"  "8/28/1993 0:00:00"  "10/29/1995 0:00:00" "1/29/1994 0:00:00"  "7/5/1995 0:00:00"  
##  [393] "8/5/1995 0:00:00"   "2/27/1995 0:00:00"  "8/18/1995 0:00:00"  "4/5/1995 0:00:00"   "8/14/1995 0:00:00"  "7/3/1994 0:00:00"   "8/21/1995 0:00:00"  "7/27/1994 0:00:00" 
##  [401] "12/29/1993 0:00:00" "6/16/1994 0:00:00"  "8/24/1995 0:00:00"  "8/2/1995 0:00:00"   "7/26/1995 0:00:00"  "7/7/1995 0:00:00"   "9/6/1995 0:00:00"   "10/17/1995 0:00:00"
##  [409] "8/25/1995 0:00:00"  "8/31/1995 0:00:00"  "10/16/1993 0:00:00" "2/22/1993 0:00:00"  "7/12/1994 0:00:00"  "8/3/1995 0:00:00"   "10/4/1994 0:00:00"  "8/15/1994 0:00:00" 
##  [417] "10/12/1994 0:00:00" "12/28/1995 0:00:00" "8/1/1995 0:00:00"   "7/24/1995 0:00:00"  "7/27/1995 0:00:00"  "8/12/1995 0:00:00"  "12/1/1995 0:00:00"  "8/11/1994 0:00:00" 
##  [425] "10/30/1993 0:00:00" "7/22/1995 0:00:00"  "7/23/1995 0:00:00"  "7/29/1995 0:00:00"  "9/1/1995 0:00:00"   "9/7/1995 0:00:00"   "10/21/1995 0:00:00" "12/19/1995 0:00:00"
##  [433] "10/31/1995 0:00:00" "10/12/1995 0:00:00" "10/8/1993 0:00:00"  "10/19/1995 0:00:00" "7/12/1995 0:00:00"  "9/8/1995 0:00:00"   "9/10/1995 0:00:00"  "7/19/1994 0:00:00" 
##  [441] "7/6/1994 0:00:00"   "10/13/1994 0:00:00" "10/3/1994 0:00:00"  "6/9/1994 0:00:00"   "6/15/1994 0:00:00"  "6/25/1994 0:00:00"  "9/3/1994 0:00:00"   "2/17/1995 0:00:00" 
##  [449] "7/5/1994 0:00:00"   "7/7/1994 0:00:00"   "5/31/1993 0:00:00"  "7/18/1994 0:00:00"  "7/10/1994 0:00:00"  "7/13/1994 0:00:00"  "7/14/1994 0:00:00"  "8/17/1994 0:00:00" 
##  [457] "6/29/1994 0:00:00"  "6/9/1995 0:00:00"   "2/26/1993 0:00:00"  "6/27/1994 0:00:00"  "4/17/1995 0:00:00"  "4/12/1993 0:00:00"  "4/8/1995 0:00:00"   "1/23/1993 0:00:00" 
##  [465] "2/17/1993 0:00:00"  "4/3/1993 0:00:00"   "5/6/1993 0:00:00"   "10/3/1995 0:00:00"  "5/9/1995 0:00:00"   "5/13/1993 0:00:00"  "5/14/1994 0:00:00"  "7/11/1994 0:00:00" 
##  [473] "6/8/1994 0:00:00"   "6/17/1995 0:00:00"  "8/31/1994 0:00:00"  "3/31/1995 0:00:00"  "8/16/1993 0:00:00"  "1/31/1995 0:00:00"  "11/24/1995 0:00:00" "1/6/1993 0:00:00"  
##  [481] "5/24/1993 0:00:00"  "9/3/1995 0:00:00"   "12/16/1995 0:00:00" "5/4/1993 0:00:00"   "5/22/1993 0:00:00"  "6/19/1995 0:00:00"  "8/23/1995 0:00:00"  "12/7/1995 0:00:00" 
##  [489] "6/28/1995 0:00:00"  "8/6/1995 0:00:00"   "10/8/1995 0:00:00"  "5/17/1995 0:00:00"  "5/11/1995 0:00:00"  "8/22/1995 0:00:00"  "8/17/1995 0:00:00"  "9/2/1995 0:00:00"  
##  [497] "12/4/1995 0:00:00"  "7/28/1995 0:00:00"  "3/18/1995 0:00:00"  "7/30/1995 0:00:00"  "5/4/1995 0:00:00"   "5/1/1995 0:00:00"   "9/5/1995 0:00:00"   "7/6/1995 0:00:00"  
##  [505] "1/20/1994 0:00:00"  "2/7/1995 0:00:00"   "2/2/1995 0:00:00"   "3/22/1995 0:00:00"  "1/21/1993 0:00:00"  "3/21/1995 0:00:00"  "1/9/1994 0:00:00"   "1/20/1995 0:00:00" 
##  [513] "2/24/1995 0:00:00"  "1/10/1994 0:00:00"  "1/20/1993 0:00:00"  "11/23/1993 0:00:00" "2/25/1994 0:00:00"  "4/5/1993 0:00:00"   "2/18/1994 0:00:00"  "1/1/1994 0:00:00"  
##  [521] "3/17/1994 0:00:00"  "4/26/1993 0:00:00"  "11/22/1993 0:00:00" "12/2/1993 0:00:00"  "2/20/1995 0:00:00"  "5/14/1993 0:00:00"  "5/23/1993 0:00:00"  "4/20/1995 0:00:00" 
##  [529] "4/6/1993 0:00:00"   "4/30/1993 0:00:00"  "6/27/1995 0:00:00"  "7/31/1995 0:00:00"  "6/14/1994 0:00:00"  "4/26/1994 0:00:00"  "4/20/1994 0:00:00"  "4/21/1994 0:00:00" 
##  [537] "6/23/1994 0:00:00"  "6/15/1995 0:00:00"  "6/24/1994 0:00:00"  "5/28/1995 0:00:00"  "6/13/1995 0:00:00"  "5/27/1995 0:00:00"  "3/7/1993 0:00:00"   "3/27/1993 0:00:00" 
##  [545] "6/25/1995 0:00:00"  "6/20/1995 0:00:00"  "6/13/1994 0:00:00"  "8/10/1993 0:00:00"  "8/9/1995 0:00:00"   "10/25/1993 0:00:00" "2/26/1994 0:00:00"  "1/21/1994 0:00:00" 
##  [553] "12/25/1995 0:00:00" "2/12/1993 0:00:00"  "8/17/1993 0:00:00"  "8/7/1995 0:00:00"   "9/22/1993 0:00:00"  "6/18/1994 0:00:00"  "8/18/1993 0:00:00"  "7/20/1994 0:00:00" 
##  [561] "8/12/1993 0:00:00"  "8/23/1993 0:00:00"  "6/19/1994 0:00:00"  "3/14/1994 0:00:00"  "6/30/1994 0:00:00"  "8/20/1993 0:00:00"  "3/10/1993 0:00:00"  "8/31/1993 0:00:00" 
##  [569] "9/12/1993 0:00:00"  "4/18/1993 0:00:00"  "4/30/1994 0:00:00"  "8/18/1994 0:00:00"  "9/22/1995 0:00:00"  "10/24/1995 0:00:00" "8/4/1993 0:00:00"   "4/16/1993 0:00:00" 
##  [577] "3/3/1993 0:00:00"   "5/29/1995 0:00:00"  "9/29/1993 0:00:00"  "9/19/1993 0:00:00"  "10/10/1993 0:00:00" "3/14/1995 0:00:00"  "10/4/1993 0:00:00"  "6/12/1994 0:00:00" 
##  [585] "9/24/1993 0:00:00"  "5/25/1995 0:00:00"  "9/10/1993 0:00:00"  "8/30/1993 0:00:00"  "8/7/1994 0:00:00"   "7/4/1995 0:00:00"   "6/17/1994 0:00:00"  "4/28/1993 0:00:00" 
##  [593] "7/1/1995 0:00:00"   "5/2/1993 0:00:00"   "9/21/1993 0:00:00"  "1/1/1993 0:00:00"   "12/18/1995 0:00:00" "6/10/1994 0:00:00"  "5/22/1995 0:00:00"  "7/25/1994 0:00:00" 
##  [601] "8/10/1995 0:00:00"  "9/25/1994 0:00:00"  "8/19/1995 0:00:00"  "12/28/1993 0:00:00" "12/4/1993 0:00:00"  "4/7/1993 0:00:00"   "2/22/1994 0:00:00"  "5/8/1995 0:00:00"  
##  [609] "5/9/1994 0:00:00"   "5/29/1994 0:00:00"  "5/10/1995 0:00:00"  "8/30/1995 0:00:00"  "4/15/1995 0:00:00"  "10/1/1994 0:00:00"  "4/14/1993 0:00:00"  "9/16/1994 0:00:00" 
##  [617] "1/31/1994 0:00:00"  "2/1/1995 0:00:00"   "11/2/1993 0:00:00"  "2/14/1994 0:00:00"  "12/11/1994 0:00:00" "1/18/1994 0:00:00"  "3/6/1993 0:00:00"   "2/2/1993 0:00:00"  
##  [625] "3/11/1993 0:00:00"  "1/15/1994 0:00:00"  "1/8/1994 0:00:00"   "3/4/1994 0:00:00"   "2/5/1995 0:00:00"   "5/11/1993 0:00:00"  "12/26/1993 0:00:00" "11/1/1994 0:00:00" 
##  [633] "12/26/1995 0:00:00" "9/30/1995 0:00:00"  "6/11/1995 0:00:00"  "4/9/1994 0:00:00"   "10/15/1995 0:00:00" "11/28/1994 0:00:00" "4/18/1995 0:00:00"  "12/22/1993 0:00:00"
##  [641] "4/27/1993 0:00:00"  "1/5/1993 0:00:00"   "3/1/1995 0:00:00"   "11/20/1993 0:00:00" "11/6/1993 0:00:00"  "11/23/1994 0:00:00" "3/21/1994 0:00:00"  "2/25/1995 0:00:00" 
##  [649] "4/16/1994 0:00:00"  "2/3/1994 0:00:00"   "1/13/1995 0:00:00"  "12/17/1994 0:00:00" "3/18/1994 0:00:00"  "5/5/1993 0:00:00"   "2/26/1995 0:00:00"  "1/29/1993 0:00:00" 
##  [657] "2/18/1993 0:00:00"  "2/28/1994 0:00:00"  "2/27/1994 0:00:00"  "3/15/1995 0:00:00"  "1/25/1993 0:00:00"  "8/4/1995 0:00:00"   "8/15/1993 0:00:00"  "5/7/1993 0:00:00"  
##  [665] "2/10/1995 0:00:00"  "3/24/1994 0:00:00"  "5/10/1993 0:00:00"  "3/1/1993 0:00:00"   "8/10/1994 0:00:00"  "5/8/1993 0:00:00"   "1/24/1993 0:00:00"  "4/11/1994 0:00:00" 
##  [673] "5/7/1994 0:00:00"   "8/11/1993 0:00:00"  "9/25/1993 0:00:00"  "4/6/1994 0:00:00"   "4/19/1994 0:00:00"  "5/27/1994 0:00:00"  "2/19/1993 0:00:00"  "12/3/1994 0:00:00" 
##  [681] "12/27/1994 0:00:00" "11/4/1993 0:00:00"  "11/2/1994 0:00:00"  "4/30/1995 0:00:00"  "4/9/1995 0:00:00"   "12/23/1993 0:00:00" "5/6/1995 0:00:00"   "4/4/1994 0:00:00"  
##  [689] "4/14/1995 0:00:00"  "8/22/1993 0:00:00"  "9/4/1994 0:00:00"   "7/1/1994 0:00:00"   "9/2/1993 0:00:00"   "9/20/1995 0:00:00"  "11/9/1994 0:00:00"  "11/27/1994 0:00:00"
##  [697] "1/14/1994 0:00:00"  "10/13/1995 0:00:00" "10/27/1995 0:00:00" "7/15/1994 0:00:00"  "12/12/1994 0:00:00" "11/1/1993 0:00:00"  "4/8/1994 0:00:00"   "4/18/1994 0:00:00" 
##  [705] "1/7/1995 0:00:00"   "11/18/1994 0:00:00" "11/11/1994 0:00:00" "6/12/1995 0:00:00"  "5/5/1995 0:00:00"   "11/3/1994 0:00:00"  "2/17/1994 0:00:00"  "12/30/1994 0:00:00"
##  [713] "9/22/1994 0:00:00"  "10/14/1995 0:00:00" "8/22/1994 0:00:00"  "8/23/1994 0:00:00"  "7/2/1995 0:00:00"   "1/1/1995 0:00:00"   "1/12/1994 0:00:00"  "3/2/1994 0:00:00"  
##  [721] "3/4/1993 0:00:00"   "3/10/1994 0:00:00"  "3/25/1993 0:00:00"  "11/29/1993 0:00:00" "4/6/1995 0:00:00"   "5/11/1994 0:00:00"  "5/22/1994 0:00:00"  "7/29/1994 0:00:00" 
##  [729] "11/16/1993 0:00:00" "3/27/1994 0:00:00"  "7/26/1994 0:00:00"  "6/18/1995 0:00:00"  "7/30/1994 0:00:00"  "3/11/1994 0:00:00"  "8/15/1995 0:00:00"  "4/17/1993 0:00:00" 
##  [737] "4/23/1993 0:00:00"  "11/28/1993 0:00:00" "2/16/1995 0:00:00"  "3/3/1994 0:00:00"   "8/20/1995 0:00:00"  "8/28/1995 0:00:00"  "12/21/1993 0:00:00" "1/15/1993 0:00:00" 
##  [745] "1/22/1994 0:00:00"  "3/9/1993 0:00:00"   "3/7/1994 0:00:00"   "8/8/1995 0:00:00"   "4/13/1994 0:00:00"  "11/15/1993 0:00:00" "1/8/1993 0:00:00"   "4/13/1995 0:00:00" 
##  [753] "8/29/1994 0:00:00"  "8/14/1994 0:00:00"  "8/2/1994 0:00:00"   "11/19/1993 0:00:00" "4/24/1995 0:00:00"  "6/28/1994 0:00:00"  "5/24/1994 0:00:00"  "1/22/1995 0:00:00" 
##  [761] "9/11/1995 0:00:00"  "11/21/1994 0:00:00" "1/2/1995 0:00:00"   "3/16/1994 0:00:00"  "3/20/1995 0:00:00"  "1/28/1995 0:00:00"  "8/11/1995 0:00:00"  "5/21/1995 0:00:00" 
##  [769] "3/8/1993 0:00:00"   "5/9/1993 0:00:00"   "9/18/1993 0:00:00"  "5/3/1995 0:00:00"   "10/19/1993 0:00:00" "2/13/1994 0:00:00"  "1/2/1993 0:00:00"   "6/4/1994 0:00:00"  
##  [777] "3/23/1993 0:00:00"  "3/21/1993 0:00:00"  "3/20/1993 0:00:00"  "1/3/1995 0:00:00"   "4/4/1993 0:00:00"   "1/30/1995 0:00:00"  "2/16/1994 0:00:00"  "11/15/1994 0:00:00"
##  [785] "4/7/1995 0:00:00"   "12/22/1994 0:00:00" "9/27/1994 0:00:00"  "8/27/1994 0:00:00"  "8/13/1995 0:00:00"  "9/26/1994 0:00:00"  "8/29/1995 0:00:00"  "8/25/1994 0:00:00" 
##  [793] "8/28/1994 0:00:00"  "8/13/1994 0:00:00"  "8/19/1994 0:00:00"  "12/1/1994 0:00:00"  "12/14/1994 0:00:00" "7/9/1994 0:00:00"   "8/27/1995 0:00:00"  "11/15/1995 0:00:00"
##  [801] "8/26/1995 0:00:00"  "9/4/1995 0:00:00"   "3/28/1994 0:00:00"  "7/21/1994 0:00:00"  "1/13/1994 0:00:00"  "4/27/1995 0:00:00"  "3/19/1995 0:00:00"  "3/31/1994 0:00:00" 
##  [809] "2/3/1993 0:00:00"   "10/9/1993 0:00:00"  "3/15/1994 0:00:00"  "5/31/1994 0:00:00"  "8/14/1993 0:00:00"  "4/28/1994 0:00:00"  "5/21/1993 0:00:00"  "10/18/1994 0:00:00"
##  [817] "11/6/1994 0:00:00"  "10/19/1994 0:00:00" "10/9/1994 0:00:00"  "10/1/1995 0:00:00"  "8/25/1993 0:00:00"  "12/28/1994 0:00:00" "7/28/1994 0:00:00"  "5/12/1993 0:00:00" 
##  [825] "5/23/1995 0:00:00"  "9/29/1995 0:00:00"  "11/27/1995 0:00:00" "11/10/1995 0:00:00" "8/26/1993 0:00:00"  "11/12/1995 0:00:00" "9/15/1993 0:00:00"  "12/7/1993 0:00:00" 
##  [833] "8/6/1993 0:00:00"   "11/14/1995 0:00:00" "9/17/1995 0:00:00"  "12/10/1993 0:00:00" "11/29/1995 0:00:00" "12/9/1993 0:00:00"  "8/16/1995 0:00:00"  "4/22/1993 0:00:00" 
##  [841] "8/3/1993 0:00:00"   "5/27/1993 0:00:00"  "4/21/1993 0:00:00"  "4/1/1993 0:00:00"   "5/2/1994 0:00:00"   "9/14/1994 0:00:00"  "3/16/1995 0:00:00"  "11/28/1995 0:00:00"
##  [849] "11/6/1995 0:00:00"  "11/1/1995 0:00:00"  "11/25/1995 0:00:00" "11/26/1995 0:00:00" "11/7/1995 0:00:00"  "10/26/1995 0:00:00" "11/8/1995 0:00:00"  "3/16/1993 0:00:00" 
##  [857] "10/28/1993 0:00:00" "3/17/1993 0:00:00"  "10/20/1994 0:00:00" "1/7/1996 0:00:00"   "1/11/1996 0:00:00"  "1/18/1996 0:00:00"  "1/19/1996 0:00:00"  "1/24/1996 0:00:00" 
##  [865] "1/26/1996 0:00:00"  "1/27/1996 0:00:00"  "1/30/1996 0:00:00"  "1/31/1996 0:00:00"  "2/3/1996 0:00:00"   "2/2/1996 0:00:00"   "2/5/1996 0:00:00"   "2/16/1996 0:00:00" 
##  [873] "2/19/1996 0:00:00"  "2/27/1996 0:00:00"  "2/28/1996 0:00:00"  "3/5/1996 0:00:00"   "3/6/1996 0:00:00"   "4/20/1996 0:00:00"  "1/17/1996 0:00:00"  "1/20/1996 0:00:00" 
##  [881] "1/21/1996 0:00:00"  "1/25/1996 0:00:00"  "1/28/1996 0:00:00"  "12/3/1996 0:00:00"  "12/8/1996 0:00:00"  "12/6/1996 0:00:00"  "12/14/1996 0:00:00" "12/12/1996 0:00:00"
##  [889] "12/17/1996 0:00:00" "12/18/1996 0:00:00" "8/17/1996 0:00:00"  "8/18/1996 0:00:00"  "8/19/1996 0:00:00"  "8/21/1996 0:00:00"  "8/22/1996 0:00:00"  "3/7/1996 0:00:00"  
##  [897] "3/10/1996 0:00:00"  "3/8/1996 0:00:00"   "3/15/1996 0:00:00"  "3/16/1996 0:00:00"  "3/17/1996 0:00:00"  "3/18/1996 0:00:00"  "3/25/1996 0:00:00"  "3/30/1996 0:00:00" 
##  [905] "3/31/1996 0:00:00"  "4/7/1996 0:00:00"   "4/10/1996 0:00:00"  "4/13/1996 0:00:00"  "4/14/1996 0:00:00"  "4/15/1996 0:00:00"  "4/21/1996 0:00:00"  "4/22/1996 0:00:00" 
##  [913] "4/23/1996 0:00:00"  "4/29/1996 0:00:00"  "5/1/1996 0:00:00"   "5/6/1996 0:00:00"   "5/7/1996 0:00:00"   "5/21/1996 0:00:00"  "5/23/1996 0:00:00"  "5/24/1996 0:00:00" 
##  [921] "5/25/1996 0:00:00"  "5/26/1996 0:00:00"  "5/27/1996 0:00:00"  "5/28/1996 0:00:00"  "6/3/1996 0:00:00"   "6/7/1996 0:00:00"   "6/11/1996 0:00:00"  "6/12/1996 0:00:00" 
##  [929] "6/13/1996 0:00:00"  "6/15/1996 0:00:00"  "6/19/1996 0:00:00"  "6/20/1996 0:00:00"  "6/23/1996 0:00:00"  "6/26/1996 0:00:00"  "6/27/1996 0:00:00"  "7/2/1996 0:00:00"  
##  [937] "7/4/1996 0:00:00"   "7/5/1996 0:00:00"   "7/7/1996 0:00:00"   "7/8/1996 0:00:00"   "7/9/1996 0:00:00"   "7/11/1996 0:00:00"  "7/13/1996 0:00:00"  "7/14/1996 0:00:00" 
##  [945] "7/17/1996 0:00:00"  "7/20/1996 0:00:00"  "7/22/1996 0:00:00"  "7/24/1996 0:00:00"  "7/27/1996 0:00:00"  "7/28/1996 0:00:00"  "7/30/1996 0:00:00"  "8/6/1996 0:00:00"  
##  [953] "8/8/1996 0:00:00"   "8/12/1996 0:00:00"  "8/23/1996 0:00:00"  "8/24/1996 0:00:00"  "8/25/1996 0:00:00"  "8/28/1996 0:00:00"  "8/30/1996 0:00:00"  "9/2/1996 0:00:00"  
##  [961] "9/4/1996 0:00:00"   "9/8/1996 0:00:00"   "9/9/1996 0:00:00"   "9/10/1996 0:00:00"  "9/11/1996 0:00:00"  "9/16/1996 0:00:00"  "9/21/1996 0:00:00"  "9/27/1996 0:00:00" 
##  [969] "9/28/1996 0:00:00"  "10/12/1996 0:00:00" "10/17/1996 0:00:00" "10/18/1996 0:00:00" "10/19/1996 0:00:00" "10/26/1996 0:00:00" "10/29/1996 0:00:00" "11/5/1996 0:00:00" 
##  [977] "11/6/1996 0:00:00"  "11/7/1996 0:00:00"  "11/30/1996 0:00:00" "12/1/1996 0:00:00"  "12/16/1996 0:00:00" "12/29/1996 0:00:00" "1/2/1996 0:00:00"   "1/3/1996 0:00:00"  
##  [985] "1/10/1996 0:00:00"  "1/6/1996 0:00:00"   "1/8/1996 0:00:00"   "1/15/1996 0:00:00"  "1/13/1996 0:00:00"  "2/10/1996 0:00:00"  "2/7/1996 0:00:00"   "2/6/1996 0:00:00"  
##  [993] "2/11/1996 0:00:00"  "2/8/1996 0:00:00"   "2/12/1996 0:00:00"  "2/13/1996 0:00:00"  "2/15/1996 0:00:00"  "2/14/1996 0:00:00"  "2/20/1996 0:00:00"  "2/18/1996 0:00:00" 
##  [ reached getOption("max.print") -- omitted 5663 entries ]
## [1] "Character count per element in var1:"
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
