---
title: "END_LOCATI Variable Analyses"
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
##   [1] ""                     ""                     ""                     ""                     ""                     "WAYNE"                ""                    
##   [8] ""                     "GAINESVILLE"          "ROLETTE"              ""                     "SADLER"               "FAXON"                "MACKS CREEK"         
##  [15] ""                     ""                     ""                     "(DYS)DYESS AFB ABILE" "LATIMER"              "MARION ARPT"          "CORSICA"             
##  [22] ""                     ""                     "GRAND FORKS AFB"      "MERRIMAN"             "WAYNESBORO"           ""                     "FORTUNA"             
##  [29] ""                     ""                     ""                     ""                     "MARSHALL"             ""                     "STEPHENSBURG"        
##  [36] ""                     "GOLDFIELD"            "WESTON"               "MOUNTAIN PARK"        ""                     ""                     "WAVERLY"             
##  [43] ""                     "MC PHERSON"           "HOLLIS XRDS"          ""                     ""                     "DIKE"                 ""                    
##  [50] ""                     ""                     "SILVER LAKE"          ""                     "GATESVILLE"           "MONAVILLE"            "COUNTYWIDE"          
##  [57] "STIGLER"              ""                     "PRESTON"              ""                     "ZION HILL"            ""                     "BURGAW"              
##  [64] "HAMILTON SQUARE"      ""                     ""                     ""                     "(SKF)KELLY AFB SAN A" ""                     "ORANGE CITY"         
##  [71] "LEWISVILLE"           "AVON"                 "ANDERSON"             ""                     "WASTA"                ""                     ""                    
##  [78] ""                     ""                     "KINCAID"              "STAPLETON"            "HIGH SPGS"            ""                     ""                    
##  [85] "MOCKSVILLE"           ""                     ""                     "LUBLIN"               "DANTE"                ""                     ""                    
##  [92] "REYNOLDSVILLE"        ""                     "CARENCRO"             "MILTON"               "GENEVA-ON-THE-LAKE"   "COUNTYWIDE"           ""                    
##  [99] ""                     ""
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
##  [1] "Coastal Southeast Ala" "and Central Southeast" "Central Southeast Ala" "Lynn Canal-Glacier Ba" "downstream from where" "at Steamboat Springs." "the Mount Evans Resea"
##  [8] "service for five hour" "two escaped serious i" "(CSU Foothills Campus"
## [1] "Data frame of 25 smallest unique char-limited values:"
##    var1_30 nchar
## 1              0
## 2       to     2
## 3       v~     2
## 4       Ok     2
## 5       CN     2
## 6      Eva     3
## 7      Ada     3
## 8      FMY     3
## 9      GNV     3
## 10     DAB     3
## 11     JAX     3
## 12     NIP     3
## 13     TLH     3
## 14     PAM     3
## 15     MLB     3
## 16     VRB     3
## 17     FLL     3
## 18     TPA     3
## 19     APF     3
## 20     VLD     3
## 21     MIA     3
## 22     PNS     3
## 23     PBI     3
## 24     CEW     3
## 25     DHN     3
## [1] "Summary of nchar(var1, allowNA = TRUE):"
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##   0.000   0.000   0.000   3.837   8.000  21.000 
## [1] "Histogram of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.END_LOCATI_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.END_LOCATI_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##                                    - .5 NNW          - 11 ESE Jay                CANTON                 TULIA      (0E4)PAYSON ARPT          (14 SSE JXN)          (1K5)ELKHART 
##                499225                     1                     1                     1                     1                     2                     1                     1 
##          (22 ESE BTL)           (23 SW JXN)           (27U)SALMON          (2WX)BUFFALO         (3DU)DRUMMOND  (3NO)NORTH OMAHA ARP     (4 SE Middleburg)  (4BL)BLANDING MUNI A 
##                     1                     1                     1                     8                     1                     1                     1                     2 
##     (4BQ)BROADUS ARPT          (4DG)DOUGLAS       (4HV)HANKSVILLE  (5I3)PIKE CO RGNL PI         (7 W Orlando)            (77M)MALTA          (8 SE Faxon)  (9V9)CHAMBERLAIN ARP 
##                     3                     3                     3                     1                     1                     1                     1                     1 
##     (AAO) JABARA ARPT  (ABI)ABILENE MUNI AR  (ABQ)ALBUQUERQUE INT (ABQ)ALBUQUERQUE INTL  (ABR)ABERDEEN RGNL A  (ACK)NANTUCKET MEM A   (ACT)MADISON-COOPER      (ACV)ARCATA ARPT 
##                     4                     6                     3                     1                     6                     2                     1                     2 
##  (ADS)ADDISON ARPT DA  (ADW)ANDREWS AFB CAM  (AEL)ALBERT LEA ARPT  (AEX)ENGLAND AFB ALX  (AFF)USAF ACDMY COLO    (AIA)ALLIANCE ARPT  (AKO)AKRON WEATHER S  (ALI)ALICE INTL ARPT 
##                     1                     1                     3                     3                    14                     6                     2                     4 
##  (ALN)STL RGNL ARPT A  (ALW)CITY/CO ARPT WA             (Alyeska)  (AMA)AMARILLO INTL A  (ANB)ANNISTON CALHOU  (AND)ANDERSON CO ARP   (ANW)AINSWORTH MUNI  (APA)ENGLWOOD ARAPAH 
##                     4                     1                     1                    19                     2                     3                     1                    16 
##  (APF)NAPLES MUNI ARP  (APN)PHELPS ARPT ALP   (ARB)ANN ARBOR MUNI  (ARG)WALNUT RIDGE AR       (ASG)SPRINGDALE  (ATL)ATLANTA INTL AR    (ATW)APPLETON ARPT   (ATY)WATERTOWN ARPT 
##                     7                     1                     2                     3                     1                     2                     1                     8 
##   (AUO)AUBURN OPELIKA  (AUW)WAUSAW MUNI ARP  (AWH)WILDHORSE RES E  (AWM)WEST MEMPHIS AR  (AXN)CHNDLR FLD ALXN  (AYS)WARE CO ARPT WA    (BAD)BARKSDALE AFB                 (BAK) 
##                     1                     3                     1                     1                     3                     3                     4                     1 
##  (BAM)BATTLE MTN ARPT  (BBW)BROKEN BOW ARPT  (BCE)BRYCE CANYON AR  (BDL)BRADLY FLD WNDS   (BDR)BRIDGEPORT MEM  (BFF)HELIG FLD SCOTS (BFL)MEADOWS FIELD AP  (BFM)MOBILE BROOKLEY 
##                     1                     2                     1                     1                     1                     2                    17                     3 
##  (BGM)BINGHAMTON ARPT  (BGR)BANGOR INTL ARP  (BHM)BIRMINGHAM ARPT    (BIE)BEATRICE ARPT  (BIL)LOGAN ARPT BILL  (BIS)BISMARCK MUNI A  (BIX)KEESLER AFB BIL     (BJI)BEMIDJI ARPT 
##                     3                     1                     1                     5                     3                    19                     1                     2 
##  (BKE)BAKER MUNI ARPT  (BKF)BUCKLEY FLD NAS  (BKL)CLEVELAND LAKEF   (BKX)BROOKINGS MUNI  (BLV)SCOTT AFB BELLE  (BMC)BRIGHAM CITY AR  (BMI)BLOOMNGTN/NORMA  (BML)BERLIN MUNI ARP 
##                     2                    16                     4                     1                     5                     1                     4                     3 
##  (BNA)NASHVILLE METRO  (BNO)BURNS MUNI ARPT  (BOI)GOWEN FLD BOISE  (BOS)LOGAN INTL ARPT   (BPI)BIG PINEY ARPT  (BQK)GLYNCO ARPT BRU  (BRL)BURLINGTON MUNI  (BSM)BERGSTROM AFB A 
##                     5                     1                     7                     6                     2                     1                     1                     1 
##  (BTL)KELLOG ARPT BTL  (BTM)MOONEY ARPT BUT   (BTR)RYAN FLD BATON  (BTV)BURLINGTON ARPT  (BUF)GTR BUFFALO INT  (BWI)BALTMOR-WSHNGTN  (BYH)BLYTHEVILLE AFB (BYI)BURLEY MUNI ARPT 
##                     1                     1                     2                     3                     1                     1                     4                     1 
##      (C96)WINTER PARK      (CAK)CANTON ARPT     (CAO)CLAYTON ARPT     (CAR)CARIBOU ARPT     (CBM)COLUMBUS AFB  (CDC)CEDAR CITY ARPT     (CDR)CHADRON ARPT   (CDS)CHILDRESS ARPT 
##                     1                     2                     3                     2                     5                     5                     2                    23 
##  (CEF)WESTOVR AFB CHI   (CEW)BOB SIKES ARPT      (CEZ)CORTEZ ARPT   (CGI)CAPE GIRARDEAU  (CGX)MEIGS FLD CHICA     (CHD)WILLIAMS AFB  (CHO)CHARLOTTESVILLE   (CHS)CHARLESTON AFB 
##                     2                     1                     1                     3                     3                     1                     7                     6 
##  (CID)CEDAR RAPIDS AR  (CKB)BENEDUM ARPT CL  (CLT)CHARLOTTE/DOUGL  (CMH)PORT COLUMBUS A  (CMI)WILLARD FLD CHA  (CMX)HOUGHTON-HANCOC  (CNK)BLOSSER APT CON    (CNM)CARLSBAD ARPT 
##                     6                     1                     2                     1                     1                     2                     4                     5 
##       (CNO)CHINO ARPT  (CNU)JOHNSON ARPT CH  (CNY)CANYONLANDS FLD  (COE)COEUR D'ALENE A      (COF)PATRICK AFB   (COS)PETERSON FIELD  (COT)COTULLA MUNI AR  (COU)COLUMBIA RGNL A 
##                     1                     1                    11                     1                     4                     8                     1                     7 
##  (CPR)NATRONA CO ARPT  (CPS)EAST STL ARPT C  (CRG)CRAIG FLD JACKS  (CRQ)PALOMAR ARPT CA     (CRW) YEAGER ARPT     (CSM)ARPT CLINTON (CSU Foothills Campus   (CUT)CUSTER CO ARPT 
##                     6                     2                     2                     3                     7                     3                     1                     1 
##     (CVG)GTR CIN ARPT  (CVS)CANNON AFB CLOV  (CWA)CEN WI ARPT MOS  (CXY)CAP CITY ARPT H    (CYS)CHEYENNE ARPT  (CZD)COZAD MUNI ARPT            (CZZ)CAMPO       (D07)FAITH ARPT 
##                     4                     1                     2                     2                     8                     1                     1                     9 
##  (DAB)DAYTONA BCH ARP  (DAG)BARSTOW/DAGGETT  (DAL)LOVE FLD DALLAS  (DAN)DANVILLE MUNI A  (DAY)COX DAYTON INTL  (DDC)DODGE CITY ARPT     (DEC)DECATUR ARPT  (DEN)DENVER INTL ARP 
##                     2                     1                     1                     1                     1                     3                     3                     9 
##  (DFW)DALLAS-FT WORTH  (DHT)DALHART MUNI AR   (DIK)DICKINSON MUNI  (DLF)LAUGHLIN AFB DE      (DLN)DILLON ARPT  (DMA)DAVIS MONTHAN A      (DMN)DEMING ARPT        (DOV)DOVER AFB 
##                     4                     7                     4                     1                     1                     5                     1                     5 
##   (DPA)DUPAGE CO ARPT  (DPG)MICHAEL AAF DUG  (DRO)DURANGO/LAPLATA  (DRT)DEL RIO INTL AR  (DSM)DES MOINES INTL  (DUJ)DUBOIS-JEFFERSO  (DYS)DYESS AFB ABILE     (E74)SAFFORD ARPT 
##                     1                    15                     2                     6                     2                     1                     6                     3 
##  (EAU)EAU CLAIRE ARPT   (ECG)ELIZABETH CITY     (EED)NEEDLES ARPT    (EFD)ELLINGTON AFB            (EGE)EAGLE  (EKM)ELKHART MUNI AR  (EKO)HARRIS FLD ELKO  (ELN)BOWERS FLD ELLE 
##                     2                     3                     4                     1                    11                     3                     6                     1 
##  (ELP)EL PASO INTL AR  (ELY)YELLAND FLD ELY  (EMP)EMPORIA MUNI AR   (END)VANCE AFB ENID    (ENV)WENDOVER ARPT  (ESF)ESLER ARPT ALXN  (EVV)DRESS ARPT EVAN  (EWR)NEWARK INTL ARP 
##                     7                     1                     1                     1                     7                     2                     6                     4 
##  (EYW)KEY WEST INL AR    (FAT) AIR TERMINAL  (FAY)GRANNIS FLD FAY     (FCH) CHANDLER AF  (FCS)FT CARSN AAF CO  (FFO)WRIGHT-PATT AFB  (FHU)FT HUACHUCA AFB   (FLG)FLAGSTAFF ARPT 
##                   112                    18                     1                    13                     1                     3                     2                     3 
##  (FLL)FT LAUDRDL INTL   (FLV)FT LEAVENWORTH  (FMY)FT MYERS PAGE F  (FNB)BRENER FLD FALL  (FOD)FT DODGE MUNI A  (FOE)FORBES FLD TOPE  (FRI)MARSHALL AAF FT    (FRM)FAIRMONT ARPT 
##                    11                     1                     3                     2                     6                     6                     4                     1 
##  (FSD)JOE FOSS FLD SI  (FSM)FT SMITH MUNI A  (FTW)MEACHAM ARPT FT  (FWA)BAER FLD FT WAY  (FWH)CARSWELL AFB FT  (FXE)FT LAUDRDL EXEC  (FYV)FAYETTEVILLE AR  (GAG)SHATTUCK ARPT G 
##                    18                     3                     1                     4                     3                     3                     2                     1 
##   (GBN)GILA BEND MUNI    (GCC)GILLETTE ARPT (GCK)GARDEN CITY ARPT  (GCN)GRAND CANYON NP  (GEG)SPOKANE INTL AR    (GFA)MALMSTROM AFB  (GFL)GLENS FALLS ARP  (GGW)GLASGOW INTL AR 
##                     1                     3                    11                     1                     1                     2                     1                     2 
##      (GJT)WALKER ARPT  (GLH)GREENVILLE MUNI  (GLS)SCHOLES FLD GAL  (GNV)GAINESVILLE ARP (GNV)GAINESVILLE ARPT  (GON)GROTON-NEW LNDN  (GPT)GULFPORT RGNL A  (GRD)GREENWOOD CO AR 
##                     6                     1                     3                     7                     2                     1                     1                     2 
##  (GRI)GRAND IS RGNL A  (GRK)GRAY AAF FT HOO  (GRR)KENT CO ARPT GR  (GSB)SEYMOUR JOHNSON      (GSH)GOSHEN ARPT (GTF)GREAT FALLS ARPT  (GTG)GRANTSBURG MUNI   (GUP)GALLUP AIRPORT 
##                     4                     3                     1                     1                     2                     4                     1                     1 
##  (GUS)GRISSOM AFB PER  (GUY)GUYMON MUNI ARP  (GVL)GAINESVILLE MEM   (GWO)GREENWOOD ARPT   (GYY)GARY MUNI ARPT      (H63)WEST PLAINS  (HAR)WSO HARRISBURGT    (HAT)CAPE HATTERAS 
##                     3                     5                     1                     2                     2                     7                     1                     2 
##                 (HBR)        (HBR)MUNI ARPT  (HDO)HONDO MUNI ARPT  (HEZ)HARDY FLD NATCH     (HIB)HIBBING ARPT   (HIF)HILL AFB OGDEN            (hillside)  (HKY)HICKORY MUNI AR 
##                     1                     1                     1                     2                     1                     1                     1                     3 
##   (HLC)HILL CITY MUNI  (HLN)HELENA RGNL ARP       (HON)HURON ARPT  (HOP)FT CAMPBELL AAF    (HOT)HOT SPGS ARPT  (HRL)RIO GRANDE ARPT    (HRO)HARRISON ARPT      (HRT)MARY ESTHER 
##                     5                     1                     8                     3                     2                     1                     2                     3 
##    (HSI)HASTINGS ARPT    (HST)HOMESTEAD AFB  (HSV)HUNTSVILLE JONE  (HUF)HULMAN FLD TERE  (HUL)HOULTON INTL AR  (HUT)HUTCHINSON MUNI  (HVE)HANKSVILLE ARPT  (HVN)TWEED-NEW HAVEN 
##                     2                     6                     2                     3                     1                     1                     1                     1 
##  (HVR)HAVRE CITY-CO A   (HYS)HAYS MUNI ARPT  (IAB) MCCONNELL ARPT  (IAH)HOUSTON INTL AR     (ICT)WICHITA ARPT  (IEN)PINE RIDGE ARPT   (IGM)MOJAVE CO ARPT  (ILG)WILMINGTON ARPT 
##                     1                     3                     3                     4                     6                     6                     4                     4 
##  (ILM)WILMINGTON ARPT  (ILN)WILMINGTON ARPK    (IML)IMPERIAL ARPT  (IND)INDNPLS INTL AR  (INK)WINKLER CO ARPT  (INL)INTL FALLS ARPT  (INT)WINSTON-SALEM A     (INW)WINSLOW ARPT 
##                     4                     5                     4                    11                     3                     1                     2                     3 
##  (ISN)SLOULIN FLD WIL    (IWD)IRONWOOD ARPT   (IXD)JHNSN CO INDSL  (JAC)JACKSON HOLE AR  (JAN)THOMPSON FLD JA  (JAX)JACKSNVILLE INT   (JBR)JONESBORO MUNI   (JCT)KIMBLE CO ARPT 
##                    10                     3                     4                     1                     1                     8                     2                     3 
##           (JDN)JORDAN  (JEF)JFFRSN CITY MEM  (JFK)KENNEDY INL ARP  (JKL)CARROLL ARPT JA (JLN)JOPLIN MUNI ARPT   (JMS)JAMESTOWN MUNI     (JNW)NEWPORT ARPT  (JOT) JOLIET DISTRIC 
##                     3                     3                     4                     2                     3                     4                     1                     1 
##  (JVL)ROCK CO ARPT JA (KSPD)SPRINGFIELD AWO  (LAF)PURDUE UNIV LAF  (LAL)LAKELAND MUNI A   (LAN) CAP CITY ARPT  (LAN)CAPITOL CTY ARP  (LAS)MCCARRAN/LAS VE  (LAX)LOS ANGELES INT 
##                     1                     1                     4                     5                     1                     3                     3                     1 
##  (LBB)LUBBOCK INTL AR   (LBF)BIRD FLD NORTH     (LBL)LIBERAL ARPT  (LCH)LK CHARLES MUNI  (LEB)LEBANON RGNL AR  (LEX)BLU GRS FLD LEX  (LFK)ANGELINA CO ARP  (LGB)LONG BEACH ARPT 
##                    17                     2                     5                     4                     7                     1                     1                     1 
##  (LGU)LOGAN-CACHE ARP  (LHU)LAKE HAVASU CIT (LHU)LAKE HAVASU CITY    (LHX)LA JUNTA ARPT       (LIC)LIMON ARPT  (LMT)KLAMATH FALLS A  (LND)HUNT FLD LANDER  (LOU)BOWMAN FLD LOUI 
##                     1                     4                     2                     2                     3                     1                     7                     1 
##  (LRD)LAREDO INTL ARP (LRD)LAREDO INTL ARPT  (LRF)LITTLE ROCK AFB  (LRU)LAS CRUCES ARPT   (LSE)LA CROSSE MUNI   (LSV)NELLIS AFB LAS        (LTS)ALTUS AFB         (LUF)LUKE AFB 
##                     2                     1                     3                     1                     2                     4                     6                     1 
##  (LUK)LUNKEN FLD CINC  (LUL)HESLER FLD LAUR  (LVM)LIVINGSTON ARPT   (LWS)NEZ PERCE MUNI                (M45O)    (MAF) MIDLAND INTL  (MBL)BLACKR APT MANI  (MBS)TRI CITY APT SA 
##                     2                     4                     3                     1                     1                    19                     1                     1 
##      (MCF)MC DILL AFB  (MCI)KS CITY INTL AR     (MCK)MC COOK ARPT  (MCN)WILSON ARPT MAC  (MCO)ORLANDO INTL AR  (MCW)MASON CITY MUNI  (MDH)CRBNDL/MRFYSBRO  (MDW)MIDWAY ARPT CHI 
##                     2                     3                     4                     4                     3                     1                     8                     1 
##  (MEI)KEY FLD MERIDIA  (MEM)MEMPHIS INTL AR       (MER)CASTLE AFB  (MFE)MILLER INTL ARP     (MFR)MEDFORD ARPT  (MGE)DOBBINS AFB MAR  (MGM)MONTGOMERY ARPT  (MGW)HART FLD MORGAN 
##                     1                     5                     2                     2                     5                     1                     2                     2 
##    (MHE)MITCHELL ARPT   (MHK)MANHATTAN MUNI       (MHR)MATHER AFB        (MHS)MT SHASTA  (MHT)MANCHESTER MUNI       (MIA)MIAMI INTL        (MIB)MINOT AFB                 (MIE) 
##                     9                     2                     1                     1                     1                    24                    18                     1 
##  (MIE)JOHNSON FLD MUN   (MIV)MILLVILLE MUNI  (MKC)KS CITY DNTN AR  (MKE)MITCHELL APT MI  (MLC)MC ALESTER MUNI  (MLI) QUAD CITY ARPT  (MLS)WILEY FLD MILES  (MML)RYAN FLD MARSHA 
##                     1                     1                     2                     5                     1                     4                     1                     3 
##       (MMO)MARSEILLES    (MMT)MC ENTIRE ANG  (MOB)MOBILE BATES FL  (MOT)MINOT INTL ARPT (MPV)-MONTPELIER ARPT  (MQT)MARQUETTE CO AR  (MRB)SHEPHERD FLD MR    (MRY)MONTEREY ARPT 
##                     2                     1                    30                     3                     2                     1                     1                     2 
##  (MSL)MUSCLE SHOALS A  (MSN)TRUAX FLD MADIS  (MSO)MISSOULA INTL A  (MSS)RICHARDS FLD MA  (MSY)MOISANT FLD NEW  (MTC)MT CLEMENS/SELF  (MWL)MINERAL WELLS A        (MWS)MT WILSON 
##                     1                     3                     6                     1                     3                     2                     4                     2 
##  (MYF)MNTGMRY FLD SAN       (NBE)NAS DALLAS   (NCA)MCAS NEW RIVER  (NEW)LKFRNT ARPT NEW       (NFL)NAS FALLON  (NGP)NAS CORPUS CHRI      (NGU)NAS NORFOLK  (NHK)NAS PATUXENT RI 
##                     3                     1                     2                     9                     1                     1                     2                     3 
##   (NID)NAF CHINA LAKE  (NIP)NAS JACKSONVILL (NIP)NAS JACKSONVILLE   (NKT)MCAS CHERRY PT      (NLC)NAS LEMOORE     (NMM)NAS MERIDIAN    (NPA)NAS PENSACOLA  (NQA)NAS MEMPHIS MIL 
##                     4                     4                     1                     1                     5                     1                     1                     1 
##   (NQI)NAS KINGSVILLE     (NQX)KEY WEST NAS      (NRB)NAS MAYPORT  (NRS)NAF IMPERIAL BE   (NSE)NAS WHITNG FLD   (NTD)NAS POINT MUGU       (NTU)NAS OCEANA  (NXP)MCAF TWENTYNINE 
##                     2                    12                     1                     1                     1                     2                     1                     1 
##  (NXX)NAS WILLOW GROV  (NZJ)ELTORO MCAS SAN  (OAJ)ELLIS FLD JACKS    (ODX)SHARP FLD ORD       (OFF)OFFUTT AFB  (OFK)STEFAN FLD NORF          (OK mesonet)          (OK Mesonet) 
##                     1                     1                     1                     2                     5                     1                     1                    28 
##  (OKC)WILL ROGERS APT (OLF)WOLF PT INT ARPT (OLS) NOGALES INTL AR    (OLU)COLUMBUS ARPT  (OMA)EPPLEY FLD OMAH        (on Red River)     (ONL)O NEILL ARPT     (ONO)ONTARIO ARPT 
##                     8                    10                     1                     4                     6                     1                     1                     1 
##   (OPF)OPA LOCKA ARPT  (ORD)O'HARE INTL ARP   (ORF) NORFOLK ARPT.  (OSC)WURTSMITH AFB O  (OSH)WITTMAN FLD OSH  (OSU)OH ST UNIV ARPT  (OTG)WORTHINGTON ARP  (OTM)OTTUMWA INDSTRL 
##                     1                     5                     1                     1                     1                     2                     7                     1 
## (OUN)NORMAN WESTHEIME       (OUN)NWS NORMAN       (OVN)WSFO OMAHA   (OWB)OWENSBORO ARPT    (OZR)FT RUCKER AAF      (P. William Snd)  (P02)POPLAR BLUFF AR        (P07)SANDERSON 
##                     2                     2                     1                     4                     3                     1                     4                     3 
##         (P35)SPICKARD    (P59)COPPER HARBOR           (P68)EUREKA  (PAH)BARKLEY ARPT PA  (PBF)PINE BLUFF ARPT  (PBG)PLATTSBURGH AFB  (PBI)PALM BEACH ARPT  (PDK)DEKALB PEACHTRE 
##                     2                     2                     3                    12                     3                     1                    15                     2 
##   (PDT)PENDLETON ARPT  (PFN)PANAMA CITY ARP        (PGA)PAGE ARPT     (PHF)NEWPORT NEWS  (PHL)PHILADELPHIA IN      (PHP)PHILIP ARPT  (PHX)SKY HARBOR ARPT  (PIA)GTR PEORIA ARPT 
##                     2                     4                     6                     2                     3                     3                     7                     4 
##   (PIB)PINE BELT RGNL  (PIE)ST PETE/CLRWATE      (PIR)PIERRE ARPT   (PIT)GTR PITTSBURGH  (PKF)PARK FALLS MUNI  (PLN)EMMET CO APT PE    (PMD)PALMDALE ARPT  (PNC)PONCA CITY ARPT 
##                     1                     3                     1                     1                     1                     1                     1                     5 
##  (PNE)NE ARPT PHILADE  (PNS)PENSACOLA REGIO  (POU)POUGHKEEPSIE AR    (PRC)PRESCOTT ARPT        (PSM)PEASE AFB   (PSP)PALM SPGS ARPT     (PTK)PONTIAC ARPT  (PUB)PUEBLO MUNI ARP 
##                     4                     2                     1                     2                     1                     4                     1                     1 
##   (PUC)CARBON CO ARPT  (PVU)PROVO MUNI ARPT     (PVW)HALE CO ARPT   (PWA)WILEY POST APT   (RAL)RIVERSIDE MUNI  (RAP)RAPID CITY ARPT  (RBD)REDBIRD ARPT DA    (RBG)ROSEBURG ARPT 
##                     2                     4                     1                     5                     3                    10                     3                     1 
##    (RCA)ELLSWORTH AFB  (RCA)ELLSWORTH AFB R  (RDG)SPAATZ FLD READ  (RDR)GRAND FORKS AFB  (REE)REESE AFB LUBBO  (RFD)GTR ROCKFORD AR   (RIV)RIVERSIDE ARPT  (RIW)RIVERTON RGNL A 
##                     1                     8                     2                     2                     2                     1                     1                     7 
##   (RKS)ROCK SPGS ARPT    (RLD)RICHLAND ARPT  (RME)GRIFFIS AFB ROM  (ROA)WOODRUM FLD ROA  (ROW)ROSWELL INDS AI          (RUM)RUMFORD     (RUT)RUTLAND ARPT  (RWF)REDWOOD FALLS A 
##                     5                     1                     2                     1                     1                     4                     3                     1 
##  (S80)GRANGEVILLE ARP  (SAC)SACRAMENTO ARPT  (SAF)SANTA FE MUNI A   (SAN)SAN DIEGO INTL  (SAV)SAVANNAH INTL A  (SBM)SHEBOYGAN CO AR  (SBY)WICOMICO CO ARP  (SDY)SIDNEY-RICHLAND 
##                     2                     1                     1                     9                     1                     1                     1                     2 
##   (SEA)SEATTLE-TACOMA     (SFB)SANFORD ARPT      (SFD)WINNER ARPT    (SFO)SFO INTL ARPT  (SGF)SPRINGFIELD ARP (SGF)SPRINGFIELD ARPT   (SGU)ST GEORGE MUNI  (SHR)SHERIDAN CO ARP 
##                     1                     1                     7                     1                     3                     9                     7                     1 
##  (SHV)SHREVEPORT RGNL  (SJC)SAN JOSE INTL A   (SJT)MATHIS FLD SAN    (SKA)FAIRCHILD AFB  (SKF)KELLY AFB SAN A   (SLC)SALT LAKE CITY  (SLK)SARANAC LAKE AR  (SLN)SALINA MUNI ARP 
##                     2                     2                     3                     1                     2                     8                     2                     2 
##  (SNA)SANTA ANA CO AR            (Snowbelt)      (SNY)SIDNEY ARPT  (SOW)SHOW LOW MUNI A  (SPI)SPRINGFIELD ARP     (SPS)SHEPPARD AFB  (SQL)SAN CARLOS ARPT         (SRQ)SARASOTA 
##                     4                     1                     6                     2                     2                     4                     1                     1 
##  (SSF)STINSON FLD SAN  (STJ)ST JOSEPH MEM A   (STL)LAMBERT FLD ST  (SUN)FRIEDMAN ARPT H  (SUS)SPIRIT/ST LOUIS       (SUU)TRAVIS AFB  (SUX)SIOUX CITY ARPT (SVC)SILVER CITY ARPT 
##                     1                     2                     8                     1                     2                     2                     9                     1 
##          (SWO)AIRPORT (SWO)STILLWATER AIRPO     (SZL)WHITEMAN AFB           (T62)TOOELE  (TBN)FT LEONARD WOOD   (TCC)TUCUMCARI ARPT  (TCL)TUSCALOOSA ARPT   (TEX)TELLURIDE ARPT 
##                     1                     1                    11                     2                     1                     2                     1                     2 
##       (TIK)TINKER AFB  (TIX)SPACE CNTR EXEC  (TLH)TALLAHASSEE ARP   (TOL)TOLEDO EXPRESS  (TOP)BILLARD ARPT TO  (TPA)TAMPA INTL ARPT  (TPL)TEMPLE MUNI ARP  (TRI)TRI CITY ARPT B 
##                     2                     1                     1                     1                     2                     1                     2                     1 
##  (TRK)TRUCKEE/TAHOE A     (TRM)THERMAL ARPT     (TTN)TRENTON ARPT  (TUL)TULSA INTL ARPT  (TUP)LEMONS ARPT TUP  (TUS)TUCSON INTL ARP (TUS)TUCSON INTL ARPT  (TVC)TRAVERSE CITY A 
##                     1                     1                     1                     9                     4                     5                     2                     1 
##  (TVF)THIEF RVR FALLS  (TWF)TWIN FALLS ARPT  (TYR)TYLER POUNDS FL  (TYS)MCGHEE TYSON KN   (U07) BULLFROG/GLEN  (U17)BULLFROG (AMOS)  (U24)DELTA MUNI ARPT  (U28)GREEN RIVER MUN 
##                     1                     2                     1                     6                     5                     2                     1                     2 
##   (U67)ROOSEVELT MUNI      (UCC)YUCCA FLATS  (UIN)QUINCY MUNI ARP           (UMN)MONETT      (UOX)OXFORD ARPT  (VAD)MOODY AFB VALDO   (VBG)VANDENBERG AFB  (VCT)VICTORIA RGNL A 
##                     1                     1                     6                     9                     3                     1                     1                     3 
##  (VCV)GEORGE AFB VICT      (VEL)VERNAL ARPT  (VIH)ROLLA/VICHY ARP (VIH)ROLLA/VICHY ARPT     (VIS)VISALIA ARPT  (VOK)VOLK AAF CAMP D        (VPS)EGLIN AFB       (WAL)WALLOPS IS 
##                     1                     1                     1                     2                     1                     6                     4                     2 
##   (WDG) WOODRING ARPT  (WEY)WEST YELLOWSTON   (WMC)WINNEMUCA MUNI  (WRB)WARNER ROBINS A     (WRI)MC GUIRE AFB  (WRL)WORLAND MUNI AR      (Y22)LEMMON ARPT    (Y26)MOBRIDGE ARPT 
##                     4                     2                     3                     9                     3                     2                     4                     1 
##  (YKN)CHAN GURNEY ARP   (YUM)YUMA INTL ARPT        10-15NM E KFLL           10 E WABASH     10 SE MIAMI BEACH    10NM SE BOCA RATON         10NM W BIMINI        11 N DICKINSON 
##                     2                     1                     1                     1                     1                     1                     1                     1 
##   12N WEBSTER SPRINGS            155007 FLL          15NM E DANIA      2-3E BAL HARBOUR        2 NW DIMONDALE          2 SW FRYBURG             20WNW FLL         25 SW CHADRON 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##        28E BAKER CITY         2NE PETROLEUM        2S RDU AIRPORT   3 ISLAND STATE PARK             3 S ELGIN     30NM E HALLANDALE   30NM E OF CAPE FLA.       3E 0.5N ERSKINE 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##       3NM EAST OF PMP         4 NE  WEIDMAN         4 NE GARRISON           4 S Hugoton          4 SE FRYBURG     4NM SW CAPE SABLE         4S CHARLESTON         4S TWIN FALLS 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##              4W BOISE        5N OF DUCK KEY             5NM N EYW       5NW RDU AIRPORT             5W ELKINS               5W YORK     69TH N & WOODLAWN           6NM E DANIA 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##         6NM SE OF EYW         7S CUNNINGHAM            8 E Belton            8 N PUEBLO            8 W OF EKO      860 S OCEAN BLVD    9300 FOUNTAIN BLUE                 AARON 
##                     1                     1                     1                     1                     1                     1                     1                     2 
##            AARON ARPT          AARONS CREEK            AARONSBURG                ABADYL                 ABARR             ABBEVILLE ABBEVILLE MUNICIPAL A  ABBEYVILLE DAVIS ARP 
##                     3                     1                     1                     3                    13                   101                     1                     2 
##             ABBOT VLG            ABBOTSFORD                ABBOTT           ABBOTTSBURG           ABBOTTSFORD           ABBOTTSTOWN             ABBYVILLE                  ABCO 
##                     7                    15                    31                     4                     1                     2                    10                     1 
##                  ABEL           ABERCROMBIE              Aberdeen              ABERDEEN         ABERDEEN ARPT          ABERDEEN JCT  ABERDEEN MNROE CO AR  ABERDEEN PROVING GRN 
##                     1                    10                     1                   128                     5                     1                     1                     2 
## ABERDEEN PROVING GRND  ABERDEEN STINSON ARP              ABERNANT             ABERNATHY     ABERNATHY SPRINGS             ABESVILLE                  ABIE               ABIGAIL 
##                    10                     2                     5                    55                     1                     5                     3                     1 
##               ABILENE     ABILENE MUNI ARPT              ABINGDON              ABINGTON               ABIQUIU            ABITA SPGS                 ABNER                   ABO 
##                   193                     4                    59                    15                     2                     9                     2                     2 
##                ABOITE               ABRAHAM         ABRAHAMSVILLE                ABRAMS              ABSARAKA             ABSAROKEE               ABSECON                ABSHER 
##                     5                     1                     1                     1                     2                     8                     3                     1 
##              ACADEMIA               ACADEMY       ACADEMY CORNERS              ACCIDENT accidents were report              ACCOKEEK               ACCOMAC                ACCORD 
##                     1                     9                     1                     8                     1                     5                     4                     9 
##              ACCOTINK             ACCOVILLE                   ACE               ACEQUIA               ACHILLE              ACHILLES                ACHORD                ACIPCO 
##                     1                     3                     2                     1                    10                    12                     1                     1 
##                 ACKER               ACKERLY              ACKERMAN  ACKERMAN CHOCTAW ARP                ACKLEY      ACKLEY MUNI ARPT              ACKWORTH                 ACMAR 
##                     4                     7                    40                     2                    24                     1                     9                     2 
##                  ACME             ACMETONIA               ACOMITA                 ACONA                 ACORN           ACORN RIDGE                ACOSTA                  ACRA 
##                    15                     1                     1                     3                     6                     2                     1                     1 
##          ACRE STATION                 ACREE                 ACRES         ACROSS COUNTY                 ACTON                 ACUFF              ACUSHNET               ACWORTH 
##                     1                     2                     6                     4                    30                     4                     7                    28 
##                   ACY                   Ada                   ADA                 ADAIR             ADAIR VLG           ADAIRSVILLE            ADAIRVILLE               ADALAND 
##                     1                     3                   141                    83                     1                    25                    21                     1 
##               ADALINE               ADAMANA                 ADAMS          ADAMS CENTER           ADAMS GROVE           ADAMS MILLS            ADAMS PARK             ADAMS RUN 
##                     1                     1                   102                     1                     1                     3                     1                     5 
##             ADAMSBORO             ADAMSBURG             ADAMSTOWN            ADAMSVILLE                  ADAN              ADASBURG                ADATON               ADDICKS 
##                     2                     7                     6                    44                     1                     1                     7                     7 
##              ADDIELEE            ADDIEVILLE             ADDINGTON                 ADDIS               ADDISON                  ADDY              ADDYSTON                  ADEL 
##                     1                     1                    24                     2                    57                     3                     1                    45 
##              ADELANTO  ADELANTO HLNDALE ARP                 ADELL               ADELPHI                  ADEN                 ADENA           ADGATEVILLE                 ADIAL 
##                     4                     1                     3                     2                     5                     6                     1                     1 
##              ADJUNTAS        ADJUNTAS PONCE                ADKINS                ADMIRE                 ADNER             ADNEY GAP           ADOBE ACRES                ADOLPH 
##                    13                     1                     1                    26                     4                     1                     1                     2 
##                 ADONA                ADONIS                 ADRIA                Adrian                ADRIAN               ADVANCE  ADVANCE STRWBRRY ARP               ADVILLE 
##                     9                     4                     1                     1                   157                    44                     2                     1 
##                   ADY             ADYEVILLE              AECOTINK                 AETNA                AFFTON                 AFLEX                AFRICA after the tornado dis 
##                     8                     2                     1                     6                    10                     1                     2                     1 
##                 AFTON        AFTON MOUNTAIN       AFTON MUNI ARPT                 AGANA                  AGAR                  AGAT                 Agate                 AGATE 
##                    71                     1                     1                     2                    28                     2                     1                    61 
##                AGAWAM                AGENCY                AGENDA                  AGES                 AGGIE                 AGNEW                 AGNOS                  AGRA 
##                    16                    21                    23                     1                     1                     2                     3                    28 
##              AGRICOLA               AGRIHAN    AGUA CALIENTE SPGS            AGUA DULCE       AGUA DULCE ARPT             AGUA FRIA            AGUA VISTA                AGUADA 
##                    15                     1                     3                     7                     1                     3                     1                    22 
##             AGUADILLA  AGUADILLA MOCA SAN S               AGUANGA          AGUAS BUENAS                 AGUDO                AGUILA               AGUILAR             AGUILARES 
##                    36                     1                     1                    13                     1                     2                     8                     5 
##             AHLBRECHT                AHLOSO                   AHO               AHOSKIE   AHOSKIE TRI CO ARPT               AHSAHKA              AHUIMANU             AHWATUKEE 
##                     1                     1                     3                    18                     1                     4                     1                     6 
##              AIBONITO                   AID                  AIEA                 AIKEN       AIKEN MUNI ARPT          AIKEN SUMMIT                 AILEY                 AIMAR 
##                    18                     4                     6                    83                     1                     1                     2                     2 
##               AIMWELL            AINA HAINA             AINSWORTH        AINSWORTH ARPT        Air Force Base           Air Station                 AIREY                AIRLEE 
##                     2                     3                    93                     2                     2                     1                     1                     1 
##                AIRLIE               Airport          Airport Area       AIRPORT GARDENS              AIRVILLE           AIRWAY HGTS                 AITCH                AITKIN 
##                     3                    12                     1                     1                     1                     3                     1                    14 
##           AITKIN ARPT                  AJAX             AJAX PARK                   AJO         AJO MUNI ARPT          Ak Peninsula                AKASKA                AKCHIN 
##                     2                     1                     1                    12                     1                     4                     1                     1 
##                 AKELA                AKELEY                 AKERS            AKERSVILLE                  AKIN                 AKINS                  AKRA                 Akron 
##                     1                    13                    10                     1                     2                     7                     1                     1 
##                 AKRON            AKRON ARPT     AKRON CANTON ARPT   AKRON MAYFIELD ARPT              AL TAHOE                ALABAM               ALABAMA          ALABAMA CITY 
##                   171                     4                     2                     1                     1                     1                     2                     1 
##         ALABAMA POINT          ALABAMA PORT ALABAMA/COUSHATTA RES             Alabaster             ALABASTER         ALABASTER JCT  ALABASTER SHELBY ARP               ALACHUA 
##                     1                    85                     4                     1                    34                     1                     1                    18 
##              ALACULSY               ALADDIN                ALAINE               ALAMANA              ALAMANCE               ALAMEDA          ALAMEDA ARPT                 ALAMO 
##                     1                    11                     1                     1                     4                     7                     1                    59 
##            ALAMO ALTO            ALAMO HGTS            ALAMOGORDO               ALAMOSA          ALAMOSA ARPT               ALAMOTA              ALANREED               ALANSON 
##                     1                     1                    15                    12                     1                    17                    25                     4 
##        ALANTHUS GROVE               ALAPAHA                ALARKA                Alaska                ALASKA      Alaska Peninsula                ALATEN                  ALBA 
##                     4                     5                     2                     9                     4                     4                     2                    29 
##               ALBANIA                Albany                ALBANY           ALBANY ARPT      ALBANY MEML ARPT Albany the temperatur               ALBATON             ALBATROSS 
##                     1                     2                   250                     2                     1                     1                     1                     2 
##                 ALBEE             ALBEMARLE        ALBEMARLE ARPT       ALBEMARLE BEACH                ALBERS                ALBERT           ALBERT CITY            ALBERT LEA 
##                     1                    39                     5                     1                     7                    34                     8                    31 
##       ALBERT LEA ARPT       ALBERT LEA LAKE               ALBERTA              ALBERTON             ALBERTSON           ALBERTVILLE  ALBERTVILLE MUNI ARP                 ALBIA 
##                     1                     1                    21                     4                     5                    47                     1                    34 
##       ALBIA MUNI ARPT                 ALBIN                ALBION      ALBION MUNI ARPT                ALBORN              ALBRIGHT        ALBRIGHTSVILLE           ALBUQUERQUE 
##                     7                    25                   174                     2                     2                    11                    11                    72 
##  ALBUQUERQUE INTL ARP ALBUQUERQUE INTL ARPT                ALBURG           ALBURG SPGS             ALBURNETT              ALBURTIS               ALCALDE              ALCESTER 
##                     1                    14                     6                     1                     6                     1                     1                    34 
##                  ALCO                 ALCOA                ALCOHU                ALCOLU                ALCOMA                ALCORN                 ALCOT                ALCOVA 
##                     1                    17                     1                     8                     1                     4                     1                     2 
##                ALCOVE                ALCOVY                  ALDA                 ALDAN                 Alden                 ALDEN          ALDEN BRIDGE         ALDEN STATION 
##                     2                     4                     6                     1                     1                    36                     1                     1 
##                ALDENE            ALDENVILLE             ALDERDALE              ALDERLEY              ALDERSON                 ALDIE                ALDINE               ALDRICH 
##                     1                     3                     1                     1                    14                    11                    21                    15 
##              ALDRIDGE               ALDRIGE                 ALEDO                ALEMAN                ALEPPO            ALESSANDRO             Aleutians                  ALEX 
##                     3                     1                    51                     1                     2                     4                     5                     6 
##             ALEXANDER        Alexander City        ALEXANDER CITY       ALEXANDER MILLS        ALEXANDER SPGS            Alexandria            ALEXANDRIA       ALEXANDRIA ARPT 
##                    61                     1                    36                     2                     1                     5                   239                     2 
##  [ reached getOption("max.print") -- omitted 33506 entries ]
## [1] "Unique values of var1:"
##    [1] ""                      "Elsanor"               "Bayway"                "Vaughn"                "Springs"               "Georgiana"             "Jacksonville"         
##    [8] "Lafayette"             "Lanett"                "Rock Run"              "Fairhope"              "Muscle Shoals"         "Burnt Corn"            "Near Opp"             
##   [15] "Andalusia"             "Hanceville"            "Guntersville"          "Fort Payne"            "Near Berry"            "Sampson"               "Skyline"              
##   [22] "Moulton"               "Ramer"                 "Scottsboro"            "Madison"               "Huntsville"            "Toney"                 "Linden"               
##   [29] "Haleyville"            "Lakeview"              "Franklin"              "Mexia"                 "Eva"                   "Chelsea"               "Alabaster"            
##   [36] "Alexander City"        "East-Central"          "Ak Peninsula"          "S Cntrl Ak"            "Alaska Peninsula"      "Kodiak Island"         "Bristol Bay"          
##   [43] "Anch. hillside"        "Northern Glf Ak"       "(P. William Snd)"      "Bering Sea"            "Seldovia"              "Anchorage"             "Prince William Sound" 
##   [50] "(hillside)"            "McGrath"               "Aleutians"             "North Gulf Coast"      "Southwest Ak Coast"    "Glacier Bay"           "Coastal Southeast Ala"
##   [57] "and Central Southeast" "Southeast Alaksa"      "Alaska"                "Southeast Alaska"      "Central Southeast Ala" "Anchorage (hillside)"  "S.W. Alaska"          
##   [64] "King Salmon"           "Bristol Bay cst"       "South Central Ak"      "(Alyeska)"             "Cape Romanzof"         "Middleton Island"      "Pribilofs"            
##   [71] "Anch. (hillside)"      "Port Heiden"           "Delta"                 "Nunivak Island"        "Pr. William Snd."      "S.W. Ak. interior"     "Bethel"               
##   [78] "Lynn Canal-Glacier Ba" "Delta Coast"           "Yukon/Kuskokwim"       "Southcentral"          "Copper River Basin"    "Basin"                 "Inlet"                
##   [85] "Southwest Alaska"      "Vista"                 "Benson"                "Williams"              "Grand Canyon"          "and Sedona"            "Miami"                
##   [92] "Bouse"                 "Phoenix"               "Wickenburg"            "NNW Tucson"            "Tucson"                "Plumerville"           "Bullhead City"        
##   [99] "Holbrook"              "Sells"                 "Sedona"                "Chino Valley"          "Mayer"                 "Tacna"                 "DeWitt"               
##  [106] "Siloam Springs"        "Hiwasse"               "NR Lowell"             "Newark"                "Omaha"                 "Lonoke"                "Lake Village"         
##  [113] "Staves"                "Jonesboro"             "Greenbrier"            "Prattsville"           "Ozan"                  "Guernsey"              "Hope"                 
##  [120] "Dierks"                "Oil Trough"            "Oark"                  "Knoxville"             "Lewisville"            "Midway"                "Brickeys"             
##  [127] "Varner"                "Star City"             "Wilton"                "Carlisle"              "Ravanna"               "City"                  "Wilson"               
##  [134] "Clarendon"             "Brinkley"              "Bass"                  "Hollis"                "Ada"                   "Northern CA"           "CA01>10"              
##  [141] "CA09 NV01"             "CA09"                  "Westminster"           "Payenway"              "Hatfield"              "Mena"                  "Slovak"               
##  [148] "Woodson"               "Little Rock"           "Maynard"               "Landis"                "Marshall"              "Spring"                "Morgan"               
##  [155] "Cave City"             "Hughes"                "Chimes"                "Brentwood"             "Beebe"                 "Scotland"              "Romance"              
##  [162] "Bald Knob"             "Solano Yolo and"       "Santa Maria"           "Kerman/"               "NE Bakersfield"        "Frazier Park"          "Kern"                 
##  [169] "Force Base"            "onto a house."         "Catalina Island"       "Lake Marin Shasta"     "Atwater"               "Obispo and Santa"      "San Luis Obispo"      
##  [176] "downstream from where" "Brea"                  "Santa Ana"             "Tustin"                "Phelan"                "Big Bear Lake"         "Lake Arrowhead"       
##  [183] "Forest Falls"          "Soboba Springs"        "Buatista"              "Salinas"               "S of Hesperia"         "Encinitas"             "Morro Bay"            
##  [190] "Santa Barbara"         "Summerland"            "Ventura"               "Santa Cruz"            "Sierra Nevada"         "Shasta-Siskiyous"      "Nevada Mountains"     
##  [197] "Shasta/Siskiyous"      "and Contra Costa"      "Francisco Northern"    "Monthly Ag Loss"       "Davis"                 "Shamrock"              "Byers"                
##  [204] "Bennett"               "Airport"               "Springfield"           "Las Animas"            "Boulder"               "COLORADO"              "at Steamboat Springs."
##  [211] "Northern and"          "the Mount Evans Resea" "service for five hour" "Palmer Divide"         "Steamboat Springs."    "Denver"                "Stapleton Airport"    
##  [218] "Castle Rock"           "Ft. Carson"            "Ramah"                 "Colorado Springs"      "Matheson"              "Agate"                 "Limon (12NW)"         
##  [225] "Rifle"                 "Granby"                "La Veta"               "DE Memorial"           "Plantation"            "Ft Lauderdale"         "FMY"                  
##  [232] "Boca Grande"           "two escaped serious i" "Cape Coral"            "Boynton Beach"         "Coral."                "GNV"                   "DAB"                  
##  [239] "Sheridan Lake 1 SE"    "Animas"                "Eads"                  "Burlington"            "Breen"                 "Loveland"              "(CSU Foothills Campus"
##  [246] "Collins"               "Red Feather Lakes"     "Limon"                 "Punkin Center"         "Peetz"                 "Sterling"              "Montrose"             
##  [253] "Gary"                  "Swink"                 "Lamar"                 "Wiley Vicinity"        "Ordway"                "Sedgwick"              "Platner"              
##  [260] "Prospect Valley"       "Keenesburg"            "Vally 2 NE"            "Hudson"                "Clarkville"            "Thompsonville"         "Norwalk"              
##  [267] "Brookfield"            "Glastonbury"           "Wethersfield"          "Newington"             "Southington"           "northeast of La Junta" "Cheyenne"             
##  [274] "Sharon"                "Bridgewater"           "Winsted"               "Cromwell"              "New Haven"             "Waterbury"             "Cheshire"             
##  [281] "Naugatuck"             "Fn Southbury"          "to Southbury"          "Seymour"               "Groton"                "at 1630 EST"           "Lebanon"              
##  [288] "Waterford"             "Stafford Springs"      "Meriden"               "Frederica"             "Harrington"            "Delaware City"         "St. George"           
##  [295] "District of Columbia"  "Columbia"              "District"              "District of Northern"  "D.C."                  "Washington"            "Gainesville"          
##  [302] "High Springs"          "Jacksonsville"         "JAX"                   "NIP"                   "TLH"                   "PAM"                   "Calloway"             
##  [309] "Raiford"               "Center"                "MLB"                   "VRB"                   "Beryl.  (M41O)"        "Titusville"            "Cape Canaveral"       
##  [316] "Mims"                  "Rockledge"             "Canaveral"             "Palm Bay"              "Patrick Air Force Bas" "Deerfield Beach"       "Davie"                
##  [323] "Fort Lauderdale"       "FLL"                   "Oakland Park"          "Miramar"               "N Lauderdale"          "Beach 18 SE FLL"       "Sunrise"              
##  [330] "Clarksville"           "Englewood"             "Port Charlotte"        "Homosassa"             "TPA"                   "Inverness"             "Western Citrus"       
##  [337] "Camp Blanding"         "APF"                   "W of Naples"           "Everglades City"       "VLD"                   "Lake City"             "MIA"                  
##  [344] "Haulover Beach"        "Homestead"             "SE portion"            "Horseshoe Beach"       "Neptune Beach"         "Mill Cove"             "San Jose"             
##  [351] "Jacksonville Beach"    "Warrington"            "PNS"                   "Palm Coast"            "Bunnell"               "ALL Florida"           "East Point"           
##  [358] "Saint George Is"       "St. George Island"     "Gretna"                "Havana"                "Wetumpka"              "PBI"                   "Hernando Beach"       
##  [365] "Brooksville"           "Lake Placid"           "Sundance"              "Tampa"                 "Beach to Gibsonton"    "(M45O)"                "him down."            
##  [372] "Brandon"               "CEW"                   "New Hope"              "DHN"                   "DAN"                   "Waukeenah"             "CTY"                  
##  [379] "Dade and"              "ORL"                   "to Sanibel"            "Lehigh Acres"          "Ft. Myers"             "Northern section"      "Bristol"              
##  [386] "E Portion"             "Buena Vista"           "Ocala"                 "Stuart"                "Isabella"              "Flamingo"              "Key West"             
##  [393] "Upper Matecumbe Key"   "EYW"                   "Bahia Honda Key"       "Tavernier"             "MTH"                   "Key Largo"             "Marathon"             
##  [400] "Island/Georgia"        "Perry"                 "Fort Walton Beach"     "Okeechobee"            "Maitland"              "Orlando"               "Ocoee"                
##  [407] "Windermere"            "Lake BuenaVista"       "Junction"              "W.  Palm Beach"        "E Coast"               "Lake Worth"            "City of Palm Beach"   
##  [414] "Aripeka"               "Richey"                "Holiday"               "Largo"                 "Hudson Beach"          "Madiera Beach"         "Treasure Island"      
##  [421] "Clearwater"            "Tampa Bay"             "Lakeland"              "Bartow"                "TPA East Lakeland"     "Hastings"              "Shores"               
##  [428] "SRQ"                   "Seminole"              "St. Augustine"         "Hutchinson Island"     "Daytona Beach"         "Crawfordville"         "Medart"               
##  [435] "Homer"                 "Fitzgerald"            "S Macon"               "Eastman"               "Waynesboro"            "Woodbine"              "Grayfield"            
##  [442] "Aline"                 "Pooler"                "Fayetteville"          "Forest Park"           "Marietta"              "Funston"               "Dawsonville"          
##  [449] "Bainbridge"            "of hours."             "Milan"                 "Albany"                "Douglasville"          "Effingham"             "Meldrin"              
##  [456] "Twin City"             "Garfield"              "Blue Ridge"            "Woolsey"               "Tyrone"                "Rome"                  "College Park"         
##  [463] "North Central Ga"      "Nickleville"           "Cairo"                 "of Grayson"            "Kingston"              "Cornelia"              "Oakwood"              
##  [470] "Bremen"                "Newburg"               "Centerville"           "Commerce"              "Countywide"            "Louisville"            "Barnesville"          
##  [477] "Maui"                  "State Park"            "Dahlonega"             "Clark Hills Lake"      "Greenville"            "N Gay"                 "Doerun"               
##  [484] "Bostwick"              "Marshallville"         "Lexington"             "Cedartown"             "Eatonton"              "Ellaville"             "Reidsville"           
##  [491] "Helena"                "Herod"                 "Northwestern"          "Lyons"                 "Cedar Crossing"        "Drybranch"             "Rossville"            
##  [498] "Monroe"                "Walnut Grove"          "Barnett"               "Flowery Branch to Flo" "Cloudland to Menlo"    "Cleveland"             "Toomsboro"            
##  [505] "Sylvester"             "Maui Oahu"             "Oahu"                  "Meridian"              "Nr Lowman"             "Idaho Falls"           "Home"                 
##  [512] "Boise"                 "Parma"                 "Heyburn"               "Buhl"                  "Pocatello"             "Cascade"               "Lewiston Area"        
##  [519] "Upper Snake River Hig" "Sage Junction"         "east of Pocatello."    "Burley"                "U.S. 84 Mile 29"       "Sublett"               "Horse Butte"          
##  [526] "Twin Falls"            "Quincy"                "Wyanet"                "Walnut"                "Mt. Carroll"           "Beardstown"            "Owaneco"              
##  [533] "Palmer"                "Flora"                 "Mattoon"               "Arlington Heights"     "Oblong"                "Lombard"               "Eberle"               
##  [540] "and St. Elmo"          "Loogootee"             "Paxton"                "Onarrowga"             "Canton"                "Lewistown"             "Manchester"           
##  [547] "Seneca"                "Biggsville"            "Southwest Illinois"    "Illinois"              "and Menominee"         "Maquon"                "Danforth and Ashkum"  
##  [554] "Lake Forest"           "Latham"                "Beason"                "Lincoln"               "New Holland"           "Argenta"               "Taylorville"          
##  [561] "Bloomington"           "Cerro Gordo"           "Ivesdale"              "Centralia"             "Saybrook"              "Sabina"                "Petersburg"           
##  [568] "Atterberry"            "Burksville"            "Waterloo"              "Leaf River"            "Mossville"             "Edelstein"             "Golconda"             
##  [575] "Baldwin"               "Joslin"                "Green Rock"            "Galatia"               "Rochester"             "Smithton"              "Belleville"           
##  [582] "Pekin"                 "East Peoria"           "South Pekin"           "Astoria"               "Lively Grove"          "Hoyleton"              "to 6 S Rock Falls"    
##  [589] "Beecher"               "Roscoe"                "Roanoke"               "Columbus"              "(BAK)"                 "Americus"              "Elnora"               
##  [596] "and Dillsboro"         "(MIE)"                 "McCordsville"          "Corydon"               "Knightstown"           "Mount Summit"          "Hemlock"              
##  [603] "Central and"           "Holton"                "Warsaw"                "Syracuse"              "Shipshewana"           "St. John"              "Cedar Lake IN"        
##  [610] "Elwood"                "Alexandria"            "Etna Green"            "Rosedale"              "Culver"                "Pulaski"               "Cloverdale"           
##  [617] "to 1 SSE Cloverdale"   "Walton"                "Burnettsville"         "Greenfield"            "Lansing"               "Waukon to"             "Auburn"               
##  [624] "Western Ames between"  "Janesville"            "Truesdale"             "Alta"                  "Breda to"              "Lanesboro"             "Fonda"                
##  [631] "Mechanicsville"        "Atalissa"              "to 3W Mason City"      "Rockford"              "New Hampton"           "Fenton"                "Lawler"               
##  [638] "Garber to"             "Osterdock"             "Grand Mound"           "Westside"              "Weldon"                "Armstrong"             "Estherville"          
##  [645] "Wadena"                "Sidney"                "to 2 N Churdan"        "in Hawarden."          "Valley"                "Lourdes"               "Decorah"              
##  [652] "Southwest Iowa"        "west half of Iowa"     "Southeast Iowa"        "southeast Iowa"        "Bellevue"              "Newton"                "Martelle"             
##  [659] "ATC tower"             "to 3 NW Larchwood"     "Hull"                  "Huron"                 "Arkansas"              "Arkansas City"         "Dodge City"           
##  [666] "Larchwood"             "State Center"          "Stacyville to"         "Mapleton"              "New Liberty"           "to"                    "Ruthven to 3 E Emmets"
##  [673] "Cylinder to"           "Brunsville to 2 E Rem" "Le Mars"               "Des Moines Airport"    "Des Moines"            "Kellerton"             "Le Clair"             
##  [680] "to Park View"          "Donahue"               "Elk Horn"              "Manilla"               "Boone"                 "Marshalltown"          "Bedford"              
##  [687] "Moorland to"           "Fort Dodge"            "Salix"                 "Hornick/Luton"         "Clarion"               "Elsmore"               "Medicine Lodge"       
##  [694] "Fairview"              "Robinson"              "Augusta"               "El Dorado"             "Dorado Lake"           "St. Francis"           "Minneola"             
##  [701] "Ashland"               "Clay Center"           "Oak Hill"              "Longford"              "Jamestown"             "Lake"                  "Coldwater"            
##  [708] "Udall"                 "Winfield"              "McCune"                "Oberlin"               "Herington"             "Denton to"             "Eudora"               
##  [715] "Grove"                 "Baldwin City"          "Trousdale"             "to 3 S"                "Garden City"           "Holcomb"               "Bucklin"              
##  [722] "Dwight"                "Gove"                  "Hugoton"               "Ingalls"               "to 16 NW"              "Tribune"               "Whitelaw"             
##  [729] "Kanco"                 "Jetmore to"            "Hanston to"            "Rozel"                 "Burdett"               "Soldier"               "Hoyt"                 
##  [736] "Delia"                 "after the tornado dis" "Lawrence"              "NE DeSoto"             "Entire area"           "Near Angola"           "Spring Hill"          
##  [743] "Desoto"                "Shawnee to"            "Stillwell"             "Edgerton"              "Lakin"                 "Deerfield"             "Belvidere"            
##  [750] "Haviland"              "Greensburg"            "NORTHCENTRAL KANSAS"   "Goodland"              "morning on the 25th."  "Northeastern KS"       "Onaga"                
##  [757] "Junction City"         "White City"            "Manhattan Airport"     "Alta Vista"            "Topeka"                "Whiting"               "Eskridge"             
##  [764] "Kansas"                "Lenape"                "Linwood"               "and 4 W of Highland"   "Hunter"                "Parker"                "Monument"             
##  [771] "Sprg"                  "Oakley"                "Emporia"               "Frankfort"             "Meade"                 "Meade St. Lake"        "Fontana"              
##  [778] "New Lancaster"         "Tipton"                "Wilsey"                "Bern"                  "Erie"                  "Utica"                 "Ness City"            
##  [785] "Norton"                "N Norton"              "Melvern"               "Downs"                 "Covert"                "Larned"                "Manhattan"            
##  [792] "Duluth"                "St. Marys"             "Pratt"                 "Atwood"                "McDonald"              "Interstate 135"        "Kismet"               
##  [799] "Maple Hill"            "Hutchinson"            "Nickerson"             "Woodston"              "Damar"                 "Milberger"             "Lucas"                
##  [806] "Scott City"            "Water"                 "Goddard"               "Wichita"               "Elmont"                "Hoxie"                 "Tasco"                
##  [813] "Brewster"              "Ruleton"               "Edson"                 "Smith Center"          "Neola"                 "Johnson City"          "4 S Hugoton"          
##  [820] "Argonia"               "Colby"                 "Menlo"                 "Sharon Sprg"           "Leoti"                 "Hickman"               "Oneida"               
##  [827] "Elizabethtown"         "Beattyville"           "Caledonia"             "Murray"                "Rich Pond"             "St. Landry"            "Bunknownie"           
##  [834] "Morganza"              "Evergreen"             "Dry Creek"             "Deridder"              "DeRidder"              "Arcadia"               "Bossier City"         
##  [841] "Dry Prong"             "New Iberia"            "LAN"                   "Genesee"               "Davison"               "Shreveport"            "Belcher"              
##  [848] "Starks"                "of Lake Charles"       "Holum"                 "Creole"                "Johnsons Bayou"        "Mansfield"             "Baton Rouge"          
##  [855] "East Feliciana"        "Holly Ridge"           "Vernon"                "Moisant Airport"       "Jennings"              "Woodlawn"              "Lake Arthur"          
##  [862] "Lacassine"             "Whitehall"             "Livonia"               "Thibodaux"             "St Vincent"            "Tallulah"              "Powhatan"             
##  [869] "Robeline"              "Lakefront Airport"     "Summit"                "East Carroll Pa."      "Chalmette"             "Destrehan"             "Montpieler"           
##  [876] "Port Barre"            "St. Francisville"      "South-Central"         "Hammond"               "Independence"          "Houma"                 "Leesville"            
##  [883] "New Llano"             "Bogalusa"              "Mandeville"            "Sarepta"               "Erwinville"            "Port Allen"            "Near Hiram"           
##  [890] "Portage Lake"          "to Squa Pan"           "South Central NH"      "Sherman"               "Washington DC"         "Severna Park"          "Baltimore City"       
##  [897] "Near Arters Mill"      "Chesapeake City"       "LaPlata"               "Cambridge"             "amounts."              "Darlington"            "Eastern Shore"        
##  [904] "Baltimore"             "Bethesda"              "Patuxent River"        "Ruthsburg"             "Williston"             "Eastern Half"          "Hagerstown"           
##  [911] "Princess Anne"         "Alford"                "W. Stockbridge"        "Williamstown"          "Sandisfield"           "Clarksburg"            "Dartmouth"            
##  [918] "Marblehead"            "Westfield"             "Longmeadow"            "Ludlow"                "W. Springfield"        "South Hadley"          "Worthington"          
##  [925] "Pittsfield"            "Townsend"              "Watertown"             "Medway"                "Revere"                "Webster"               "Northboro"            
##  [932] "Westboro"              "Curran"                "Alpena"                "Alden"                 "Standish"              "Skidway"               "Prescott"             
##  [939] "Battle Creek"          "(22 ESE BTL)"          "Walker"                "Pine River"            "Cheboygan"             "Harrison"              "Meredith"             
##  [946] "Grayling"              "Berrien Center"        "Iron Mountain"         "Estey"                 "Gladwin"               "Traverse City"         "(23 SW JXN)"          
##  [953] "(14 SSE JXN)"          "Sand Point"            "Oscoda"                "Hale"                  "Yale"                  "LexingtonHeights"      "Tawas City"           
##  [960] "MOP"                   "JXN"                   "Schoolcraft"           "Pokagon"               "Kalamazoo"             "South Boardman"        "New Era"              
##  [967] "Lapeer"                "Manistique"            "North Branch"          "Glen Haven"            "Cedar"                 "Raison Township"       "Lenawee"              
##  [974] "and Alida"             "Baxter"                "Pinckney"              "Sanford"               "Coleman"               "ALL of Michigan"       "Michigan"             
##  [981] "Northwest Lower"       "Lower Michigan and"    "Northwest Upper"       "Eastern Upper"         "All of Michigan"       "Lower Michigan"        "Central Lower"        
##  [988] "Western and Central"   "Southeast Lower"       "Channel"               "Farmington Hills"      "Marine City"           "Sterling Heights"      "Orion/Davisburg"      
##  [995] "White Lake"            "Mio"                   "Cadillac"              "HTL"                   "Durand"                "Sturgis"              
##  [ reached getOption("max.print") -- omitted 33506 entries ]
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
