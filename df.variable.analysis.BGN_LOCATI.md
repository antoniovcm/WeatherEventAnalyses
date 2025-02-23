---
title: "BGN_LOCATI Variable Analyses"
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
##   [1] "Whittier"             ""                     ""                     "CLIFFSIDE"            "Waurika"              "WAYNE"                ""                    
##   [8] "Arriba"               "GAINESVILLE"          "ROLETTE"              "WABASHA"              "SADLER"               "FAXON"                "MACKS CREEK"         
##  [15] ""                     "EKALAKA ARPT"         "ROSE"                 "(DYS)DYESS AFB ABILE" "LATIMER"              "MARION ARPT"          "CORSICA"             
##  [22] ""                     ""                     "GRAND FORKS AFB"      "MERRIMAN"             "WAYNESBORO"           ""                     "FORTUNA"             
##  [29] "(AMA)AMARILLO INTL A" "WHEATON"              ""                     "NACOGDOCHES"          "MARSHALL"             "NEWCOMB"              "STIRLING"            
##  [36] "RUSSELL SPGS"         "GOLDFIELD"            "WESTON"               "MOUNTAIN PARK"        ""                     ""                     "WAVERLY"             
##  [43] ""                     "MC PHERSON"           "HOLLIS XRDS"          ""                     "HENRIETTA"            "DIKE"                 ""                    
##  [50] "KISMET"               ""                     "SILVER LAKE"          ""                     "GATESVILLE"           "MONAVILLE"            "COUNTYWIDE"          
##  [57] "STIGLER"              ""                     "PRESTON"              ""                     "ZION HILL"            "COLONIAL HGTS"        "WATHA"               
##  [64] "HAMILTON SQUARE"      ""                     ""                     "HEBRON"               "(SKF)KELLY AFB SAN A" ""                     "ORANGE CITY"         
##  [71] "LEWISVILLE"           "BASALT"               "ANDERSON"             ""                     "WASTA"                "NORWOOD"              "LAKE LIVINGSTON DAM" 
##  [78] "RINGGOLD"             ""                     "KINCAID"              "STAPLETON"            "HIGH SPGS"            ""                     "Davis"               
##  [85] "MOCKSVILLE"           ""                     "Clearville"           "LUBLIN"               "DANTE"                "SHEBOYGAN"            "Austin"              
##  [92] "REYNOLDSVILLE"        "WALSENBURG"           "CARENCRO"             "MILTON"               "WILLOWICK"            "COUNTYWIDE"           ""                    
##  [99] "LEBANON"              ""
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
##  [1] "Southwest and South A" "Fairhope/Silverhill/F" "Foley and Gulf Shores" "Grove Oak to Rainsvil" "Central and East port" "Between Sulligent and" "Arab; Martling & Popl"
##  [8] "Grant and Union Grove" "Guntersville Union Gr" "Geiger to Gainesville"
## [1] "Data frame of 25 smallest unique char-limited values:"
##    var1_30 nchar
## 1              0
## 2        ?     1
## 3        Y     1
## 4       to     2
## 5       T-     2
## 6       NE     2
## 7       SF     2
## 8       CN     2
## 9      Opp     3
## 10     Eva     3
## 11     Coy     3
## 12     Ajo     3
## 13     Ada     3
## 14     Bay     3
## 15     Guy     3
## 16     Ico     3
## 17     Keo     3
## 18     Roe     3
## 19     Amy     3
## 20     Roy     3
## 21     Ink     3
## 22     Ulm     3
## 23     Fox     3
## 24     Ola     3
## 25     FMY     3
## [1] "Summary of nchar(var1, allowNA = TRUE):"
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##   0.000   0.000   7.000   5.917   9.000  21.000 
## [1] "Histogram of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.BGN_LOCATI_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.BGN_LOCATI_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##                                - 1 N Albion         - 3 E Carrier               - 4 WNW                 - 4.5 -030-031-032-035-036-        Christiansburg                   EYW 
##                287743                     1                     1                     1                     1                     1                     1                     2 
##                Garden                Naples               Plummer                 TULIA                  $150         & Butler Road             & Charles                & Fort 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##              & Kansas  (01R)AFB GNRY RNG AL      (0E4)PAYSON ARPT          (1K5)ELKHART           (27U)SALMON          (2WX)BUFFALO  (30I)LAMONI MUNI ARP         (3DU)DRUMMOND 
##                     1                     1                     5                     7                     2                    24                     4                     2 
##        (3HT)HARLOWTON  (3NO)NORTH OMAHA ARP  (3SE)SPENCER MUNI AR (40J)PERRY-FOLEY ARPT        (4BK)BROOKINGS  (4BL)BLANDING MUNI A     (4BQ)BROADUS ARPT           (4CR)CORONA 
##                     7                     2                     5                     3                     1                     2                     5                     1 
##          (4DG)DOUGLAS       (4HV)HANKSVILLE        (4OM)OMAK ARPT  (6V8)MONTROSE CO ARP            (77M)MALTA  (87Q)SAN SIMEON ARPT  (9V9)CHAMBERLAIN ARP (AAF)APALACHICOLA ARP 
##                     3                     4                     1                     2                     2                     1                     9                     5 
##     (AAO) JABARA ARPT  (ABE)ALLENTOWN-BETHL  (ABI)ABILENE MUNI AR  (ABQ)ALBUQUERQUE INT (ABQ)ALBUQUERQUE INTL  (ABR)ABERDEEN RGNL A (ABY)SOUTHWEST GA RGN (ABY)SW GEORGIA REGIO 
##                    13                     1                     9                     3                     2                    10                     2                     1 
##  (ACK)NANTUCKET MEM A   (ACT)MADISON-COOPER      (ACV)ARCATA ARPT  (ACY)ATLANTIC CITY A         (ADM) Ardmore  (ADS)ADDISON ARPT DA  (ADW)ANDREWS AFB CAM  (AEG)DOUBLE EAGLE II 
##                     2                     4                     2                     3                     1                     6                     5                     1 
##  (AEL)ALBERT LEA ARPT  (AEX)ENGLAND AFB ALX  (AFF)USAF ACDMY COLO        (AGR)AVON PARK  (AGS)BUSH FLD AUGUST    (AIA)ALLIANCE ARPT  (AKO)AKRON WEATHER S   (ALB)ALBANY CO ARPT 
##                     7                     4                    31                     1                    11                    11                     9                     1 
##  (ALI)ALICE INTL ARPT  (ALM)WH SANDS/ALAMAG  (ALN)STL RGNL ARPT A  (ALO)WATERLOO MUNI A  (ALW)CITY/CO ARPT WA  (AMA)AMARILLO INTL A  (AMG)BACON CO ARPT A  (ANB)ANNISTON CALHOU 
##                     6                     1                     7                    18                     2                    72                     2                    11 
##  (AND)ANDERSON CO ARP   (ANW)AINSWORTH MUNI  (AOO)BLAIR CO ARPT A  (APA)ENGLWOOD ARAPAH  (APF)NAPLES MUNI ARP  (APN)PHELPS ARPT ALP  (AQQ)APALACHICOLA AR   (ARB)ANN ARBOR MUNI 
##                     6                     8                     3                    22                     9                     2                     1                     4 
##  (ARG)WALNUT RIDGE AR       (ASE)ASPEN ARPT  (ASH)BOIRE FLD NASHU  (ATL)ATLANTA INTL AR    (ATW)APPLETON ARPT   (ATY)WATERTOWN ARPT  (AUG)AUGUSTA STATE A   (AUO)AUBURN OPELIKA 
##                     5                     1                     1                     2                     4                    16                     1                     1 
##  (AUS)MUELLER MUNI AR  (AUW)WAUSAW MUNI ARP  (AWH)WILDHORSE RES E  (AWM)WEST MEMPHIS AR  (AXN)CHNDLR FLD ALXN  (AYS)WARE CO ARPT WA    (BAD)BARKSDALE AFB  (BAM)BATTLE MTN ARPT 
##                    13                     8                     2                     1                     3                     7                     7                     2 
##  (BBW)BROKEN BOW ARPT  (BCE)BRYCE CANYON AR  (BDE)BAUDETTE INTL A  (BDL)BRADLY FLD WNDS   (BDR)BRIDGEPORT MEM   (BEH)ROSS ARPT BNTN  (BFF)HELIG FLD SCOTS (BFL)MEADOWS FIELD AP 
##                     9                     1                     1                     7                     7                     4                     8                    18 
##  (BFM)MOBILE BROOKLEY (BGE)BAINBRIDGE-DECAT  (BGM)BINGHAMTON ARPT  (BGR)BANGOR INTL ARP  (BGS)BIG SPRING ARPT  (BHM)BIRMINGHAM ARPT  (BID)BLOCK IS ST ARP    (BIE)BEATRICE ARPT 
##                     3                     1                     6                     1                     6                     9                     1                     9 
##      (BIH)BISHOP ARPT  (BIL)LOGAN ARPT BILL  (BIS)BISMARCK MUNI A  (BIX)KEESLER AFB BIL     (BJI)BEMIDJI ARPT  (BKE)BAKER MUNI ARPT  (BKF)BUCKLEY FLD NAS  (BKL)CLEVELAND LAKEF 
##                     2                    34                    44                     5                     4                     2                    35                     8 
##  (BKW)RALEIGH CO ARPT   (BKX)BROOKINGS MUNI   (BLF)MERCER CO ARPT  (BLV)SCOTT AFB BELLE  (BMC)BRIGHAM CITY AR  (BMG)MNROE CO ARPT B  (BMI)BLOOMNGTN/NORMA  (BML)BERLIN MUNI ARP 
##                     3                     4                     2                    10                     1                     1                     6                     2 
##  (BNA)NASHVILLE METRO  (BNO)BURNS MUNI ARPT  (BOI)GOWEN FLD BOISE  (BOS)LOGAN INTL ARPT  (BOW)BARTOW MUNI ARP   (BPI)BIG PINEY ARPT  (BPT)BEAUMONT-PT ART  (BQK)GLYNCO ARPT BRU 
##                    12                     1                     8                     7                     1                     6                     3                     3 
##  (BRD)WEILAND FLD BRA  (BRL)BURLINGTON MUNI  (BRO)BROWNSVILLE ARP  (BSM)BERGSTROM AFB A  (BTL)KELLOG ARPT BTL  (BTM)MOONEY ARPT BUT   (BTR)RYAN FLD BATON  (BTV)BURLINGTON ARPT 
##                     1                     4                     4                     1                     3                     3                     4                    11 
##  (BUF)GTR BUFFALO INT         (BUO)BEAUMONT          (BUR)BURBANK       (BVE)BOOTHVILLE  (BWG)BOWLING GREEN A  (BWI)BALTMOR-WSHNGTN  (BYH)BLYTHEVILLE AFB (BYI)BURLEY MUNI ARPT 
##                     3                     1                     1                     1                     4                     6                     3                     1 
##  (BZN)GALLATIN FLD BO   (CAE)COLUMBIA METRO  (CAG)CRAIG/MOFFAT AR      (CAK)CANTON ARPT     (CAO)CLAYTON ARPT     (CAR)CARIBOU ARPT     (CBM)COLUMBUS AFB  (CDC)CEDAR CITY ARPT 
##                     1                     5                     2                     2                     8                    15                    14                     5 
##     (CDR)CHADRON ARPT   (CDS)CHILDRESS ARPT  (CDW)ESX CO ARPT CAL  (CEF)WESTOVR AFB CHI   (CEW)BOB SIKES ARPT      (CEZ)CORTEZ ARPT  (CGF)CUYAHOGA CO ARP   (CGI)CAPE GIRARDEAU 
##                    10                    33                     1                     2                     1                     1                     1                    10 
##  (CGX)MEIGS FLD CHICA  (CHA)LOVELL FLD CHAT     (CHD)WILLIAMS AFB  (CHO)CHARLOTTESVILLE   (CHS)CHARLESTON AFB  (CIC)CHICO MUNI ARPT  (CID)CEDAR RAPIDS AR  (CIU)CHIPPEWA CO ARP 
##                     3                     5                     3                     5                    14                     1                    13                     1 
##  (CKB)BENEDUM ARPT CL  (CLE)HOPKINS INTL AR  (CLL)EASTERWD FLD CO  (CLT)CHARLOTTE/DOUGL  (CMH)PORT COLUMBUS A  (CMI)WILLARD FLD CHA  (CMX)HOUGHTON-HANCOC  (CNK)BLOSSER APT CON 
##                     6                     3                     3                     4                     6                     2                     2                     7 
##    (CNM)CARLSBAD ARPT  (CNU)JOHNSON ARPT CH  (CNY)CANYONLANDS FLD  (COD)YELLOWSTONE APT  (COE)COEUR D'ALENE A      (COF)PATRICK AFB (COS)COLORADO SPGS AR   (COS)PETERSON FIELD 
##                    11                    12                    15                     3                     1                    13                     4                     7 
##  (COT)COTULLA MUNI AR  (COU)COLUMBIA RGNL A  (CPR)NATRONA CO ARPT  (CPS)EAST STL ARPT C   (CQC)CLINES CORNERS  (CRE)NORTH MYRTLE BE  (CRG)CRAIG FLD JACKS   (CRP)CORPUS CHRISTI 
##                     3                    11                    14                     4                     2                     1                     6                    12 
##  (CRQ)PALOMAR ARPT CA     (CRW) YEAGER ARPT   (CSG)COLUMBUS METRO     (CSM)ARPT CLINTON  (CSM)CLINTON SHERMAN   (CSV)CROSSVILLE MEM  (CTB)CUTBANK MUNI AR  (CTY)CROSS CITY ARPT 
##                     3                    16                     1                     3                     2                     1                     1                     1 
##     (CVG)GTR CIN ARPT (CVN)CLOVIS MUNI AIRP       (CVS)CANNON AFB  (CVS)CANNON AFB CLOV  (CWA)CEN WI ARPT MOS    (CYS)CHEYENNE ARPT  (CZD)COZAD MUNI ARPT  (CZK)CASCADE LOCKS A 
##                     7                    11                    13                     2                     1                    41                    16                     1 
##            (CZZ)CAMPO       (D07)FAITH ARPT  (D45)CARLSON FLD WAR  (DAB)DAYTONA BCH ARP  (DAG)BARSTOW/DAGGETT  (DAL)LOVE FLD DALLAS  (DAN)DANVILLE MUNI A  (DAY)COX DAYTON INTL 
##                     1                    13                     5                     7                     1                     3                     5                     6 
##  (DBQ)DUBUQUE MUNI AR  (DCA)REAGAN NATIONAL  (DDC)DODGE CITY ARPT     (DEC)DECATUR ARPT  (DEN)DENVER INTL ARP  (DET)DETROIT CITY AR  (DFW)DALLAS-FT WORTH      (DHN)DOTHAN ARPT 
##                    18                    33                    31                     3                    11                     1                     7                     1 
##     (DHN)NAPIER FIELD  (DHT)DALHART MUNI AR   (DIK)DICKINSON MUNI  (DLF)LAUGHLIN AFB DE      (DLN)DILLON ARPT  (DMA)DAVIS MONTHAN A      (DMN)DEMING ARPT        (DOV)DOVER AFB 
##                     2                    10                    11                     7                     2                    14                     6                     2 
##   (DPA)DUPAGE CO ARPT  (DPG)MICHAEL AAF DUG  (DRA)DESERT ROCK ARP  (DRO)DURANGO/LAPLATA  (DRT)DEL RIO INTL AR    (DRU)DRUMMOND ARPT  (DSM)DES MOINES INTL  (DTW)DETROIT METRO A 
##                     8                    36                     1                     3                     9                     2                    53                     1 
##   (DUG)BISBEE DOUGLAS  (DVL)DEVILS LAKE MUN   (DYR)DYERSBURG MUNI  (DYS)DYESS AFB ABILE     (E74)SAFFORD ARPT     (EAR)KEARNEY ARPT  (EAU)EAU CLAIRE ARPT                 (ECG) 
##                     6                     5                     2                    17                     3                     4                     3                     1 
##   (ECG)ELIZABETH CITY      (EDW)EDWARDS AFB     (EED)NEEDLES ARPT    (EFD)ELLINGTON AFB     (EFK)NEWPORT ARPT            (EGE)EAGLE  (EKM)ELKHART MUNI AR  (EKN)RANDOLPH FLD EL 
##                     7                     1                     5                     3                     2                    14                     3                     4 
##  (EKO)HARRIS FLD ELKO  (ELD)EL DORADO GOODW      (ELM)ELMIRA ARPT  (ELN)BOWERS FLD ELLE  (ELP)EL PASO INTL AR  (ELY)YELLAND FLD ELY  (EMP)EMPORIA MUNI AR       (END) Vance AFB 
##                     7                     3                     3                     1                    25                     2                    16                     2 
##       (END) Vance Air (END) Vance Air Force   (END)VANCE AFB ENID    (ENV)WENDOVER ARPT  (EPH)EPHRATA MUNI AR  (ESC)DLTA CO ARPT ES  (ESF)ESLER ARPT ALXN  (EUG)EUGENE SWEET AR 
##                     1                     2                    21                     7                     1                     1                     5                     2 
##  (EVV)DRESS ARPT EVAN  (EVW)BURNS FLD EVANS  (EWB)NEW BEDFORD ARP  (EWN)SIMMONS NOT APT  (EWR)NEWARK INTL ARP  (EYW)KEY WEST INL AR  (F39)SHERMAN-DENISON  (FAF)FELKER AAF FT E 
##                     8                     2                     2                     1                     7                   118                     8                     5 
##  (FAR)HECTOR INTL ARP    (FAT) AIR TERMINAL  (FAY)GRANNIS FLD FAY         (FBG)FT BRAGG     (FCH) CHANDLER AF  (FCS)FT CARSN AAF CO     (FDY)FINDLAY ARPT  (FFM)FERGUS FALLS AR 
##                     3                    20                     6                     4                    13                     1                     6                     4 
##  (FFO)WRIGHT-PATT AFB  (FHU)FT HUACHUCA AFB   (FLG)FLAGSTAFF ARPT  (FLL)FT LAUDRDL INTL  (FLO)FLORENCE CITY-C   (FLV)FT LEAVENWORTH  (FME)TIPTON AAF FT M (FMN)FARMINGTON AIRPO 
##                     5                     3                     7                    15                     1                     7                     2                     2 
##  (FMY)FT MYERS PAGE F  (FNB)BRENER FLD FALL  (FNT)BISHOP ARPT FLI  (FOD)FT DODGE MUNI A  (FOE)FORBES FLD TOPE  (FOK)WESTHAMPTON BCH  (FRI)MARSHALL AAF FT  (FSD)JOE FOSS FLD SI 
##                     7                     6                     3                    18                    13                     1                     8                    21 
##      (FSI) Henry Post        (FSI)FORT SILL  (FSM)FT SMITH MUNI A  (FTK)GODMAN AAF FT K  (FTW)MEACHAM ARPT FT   (FUL)FULLERTON MUNI  (FWA)BAER FLD FT WAY  (FWH)CARSWELL AFB FT 
##                     2                     2                     7                     2                     6                     1                     4                     7 
##  (FXE)FT LAUDRDL EXEC  (FYV)FAYETTEVILLE AR        (GAG) Shattuck     (GAG)GAGE AIRPORT  (GAG)SHATTUCK ARPT G   (GBG)GALESBURG ARPT   (GBN)GILA BEND MUNI    (GCC)GILLETTE ARPT 
##                     2                     4                     1                     4                     1                     3                     1                     7 
## (GCK)GARDEN CITY ARPT  (GCN)GRAND CANYON NP   (GDP)GUADALUPE PASS  (GDV)GLENDIVE-DAWSON  (GEG)SPOKANE INTL AR    (GFA)MALMSTROM AFB  (GFK)GRAND FORKS INT  (GFL)GLENS FALLS ARP 
##                    25                     1                    16                     1                     3                     4                     4                     2 
##  (GGG)GREGG CO ARPT L  (GGW)GLASGOW INTL AR      (GJT)WALKER ARPT  (GLS)SCHOLES FLD GAL (GNT)GRANTS MUNI AIRP  (GNV)GAINESVILLE ARP (GNV)GAINESVILLE ARPT  (GON)GROTON-NEW LNDN 
##                     3                     3                    14                     6                     1                     8                     2                     2 
##  (GPT)GULFPORT RGNL A  (GPZ)GRAND RAPIDS AR  (GRB)STRAUBEL FLD GR  (GRD)GREENWOOD CO AR  (GRI)GRAND IS RGNL A  (GRK)GRAY AAF FT HOO  (GRR)KENT CO ARPT GR  (GSB)SEYMOUR JOHNSON 
##                     2                     1                     3                     2                    15                     8                     2                     1 
##      (GSH)GOSHEN ARPT  (GSO)GREENSBORO RGNL (GTF)GREAT FALLS ARPT  (GTR)COLUMBUS RGNL A  (GUC)GUNNISON CO ARP   (GUP)GALLUP AIRPORT  (GUS)GRISSOM AFB PER  (GUY)GUYMON MUNI ARP 
##                     3                     3                     4                     2                     1                     2                    10                    10 
##  (GVT)MAJORS ARPT GRE   (GWO)GREENWOOD ARPT  (GWW)GOLDSBORO-WAYNE   (GYY)GARY MUNI ARPT      (H63)WEST PLAINS    (HAT)CAPE HATTERAS  (HBG)HATTIESBURG ARP (HBR) Hobart Municipa 
##                     2                     1                     2                     7                     6                     2                     5                     1 
##   (HBR)HOBART AIRPORT        (HBR)MUNI ARPT  (HDO)HONDO MUNI ARPT  (HEZ)HARDY FLD NATCH  (HGR)HAGERSTOWN RGNL     (HIB)HIBBING ARPT   (HIF)HILL AFB OGDEN     (HIO)POEHIER ARPT 
##                     7                     1                     5                     2                     4                     1                     3                     1 
##  (HKY)HICKORY MUNI AR   (HLC)HILL CITY MUNI  (HLG)OHIO CO ARPT WH  (HLN)HELENA RGNL ARP  (HMN)HOLOMAN AFB ALM  (HOB)HOBBS LEA CO AR       (HON)HURON ARPT  (HOP)FT CAMPBELL AAF 
##                     3                    14                     1                     2                     6                     1                    11                     5 
##    (HOT)HOT SPGS ARPT       (HOU)HOBBY ARPT  (HQM)BOWERMAN FLD HO  (HRL)RIO GRANDE ARPT    (HRO)HARRISON ARPT      (HRT)MARY ESTHER    (HSI)HASTINGS ARPT  (HSP)INGALLS FLD HOT 
##                    13                     3                     2                     2                    10                     3                    21                     2 
##         (HSS)HOT SPGS    (HST)HOMESTEAD AFB  (HSV)HUNTSVILLE JONE  (HTL)HOUGHTON LAKE A  (HTS)TRI ST ARPT HNT  (HUF)HULMAN FLD TERE  (HUL)HOULTON INTL AR  (HUT)HUTCHINSON MUNI 
##                     2                     7                     4                     2                     2                     5                     2                    12 
##  (HVR)HAVRE CITY-CO A   (HYS)HAYS MUNI ARPT  (IAB) MCCONNELL ARPT  (IAG)NIAGARA FALLS A  (IAH)HOUSTON INTL AR     (ICT)WICHITA ARPT  (IDA)FANNING FLD IDA  (IEN)PINE RIDGE ARPT 
##                     1                     5                    11                     1                    13                    65                     1                     9 
##   (IGM)MOJAVE CO ARPT  (ILG)WILMINGTON ARPT  (ILM)WILMINGTON ARPT  (ILN)WILMINGTON ARPK    (IML)IMPERIAL ARPT    (IMT)IRON MTN ARPT  (IND)INDNPLS INTL AR  (INK)WINKLER CO ARPT 
##                     6                     7                     4                    16                    13                     4                    14                     6 
##  (INL)INTL FALLS ARPT  (INT)WINSTON-SALEM A     (INW)WINSLOW ARPT  (IPT)WILLIAMSPORT AR  (IRK)KIRKSVILLE MUNI  (ISN)SLOULIN FLD WIL  (ISO)ERN RGNL JETPOR  (ISP)MC ARTHUR FLD I 
##                     2                     2                     3                     3                     4                    17                     2                     1 
##    (IWD)IRONWOOD ARPT   (IXD)JHNSN CO INDSL  (JAC)JACKSON HOLE AR  (JAN)THOMPSON FLD JA  (JAX)JACKSNVILLE INT   (JBR)JONESBORO MUNI   (JCT)KIMBLE CO ARPT           (JDN)JORDAN 
##                     5                     6                     1                     1                    14                     1                    11                    15 
##  (JEF)JFFRSN CITY MEM  (JFK)KENNEDY INL ARP   (JHW)JAMESTOWN ARPT  (JKL)CARROLL ARPT JA  (JLN)JOPLIN MUNI ARP (JLN)JOPLIN MUNI ARPT   (JMS)JAMESTOWN MUNI     (JNW)NEWPORT ARPT 
##                     5                     6                     1                     3                     4                     3                     9                     2 
##  (JOT) JOLIET DISTRIC   (JST)JOHNSTOWN ARPT  (JVL)ROCK CO ARPT JA  (JXN)REYNOLDS FLD JA     (KNGU)NORFOLK NAS (KORF)NORFOLK INTERNA (KSPD)SPRINGFIELD AWO  (LAF)PURDUE UNIV LAF 
##                     2                     1                     4                     1                     1                     4                     6                     9 
##  (LAL)LAKELAND MUNI A (LAM)LOS ALAMOS AIRPO  (LAM)LOS ALAMOS ARPT   (LAN) CAP CITY ARPT  (LAN)CAPITOL CTY ARP  (LAS)MCCARRAN/LAS VE  (LAX)LOS ANGELES INT  (LBB)LUBBOCK INTL AR 
##                     9                     5                     1                     1                     4                     3                     1                    19 
##     (LBE)LATROBE ARPT   (LBF)BIRD FLD NORTH     (LBL)LIBERAL ARPT  (LCH)LK CHARLES MUNI   (LCK)RCKENBCKR ARPT  (LEB)LEBANON RGNL AR  (LEX)BLU GRS FLD LEX      (LFI)LANGLEY AFB 
##                     3                    28                    36                    25                     7                     8                     2                     1 
##  (LFK)ANGELINA CO ARP   (LFT)LAFAYETTE RGNL  (LGB)LONG BEACH ARPT  (LGU)LOGAN-CACHE ARP  (LHU)LAKE HAVASU CIT (LHU)LAKE HAVASU CITY  (LHW)FT STEWART HINE    (LHX)LA JUNTA ARPT 
##                     2                     4                     1                     3                     5                     2                     6                     5 
##       (LIC)LIMON ARPT  (LIT)LITTLE ROCK ADA  (LIZ)LORING AFB LIME  (LMT)KLAMATH FALLS A  (LND)HUNT FLD LANDER     (LNK)LINCOLN ARPT   (LNS)LANCASTER ARPT  (LOL)DERBY FLD LOVEL 
##                     8                    17                     3                     3                    10                     4                     1                     1 
##  (LOU)BOWMAN FLD LOUI  (LOZ)MCGEE FLD LONDO  (LRD)LAREDO INTL ARP (LRD)LAREDO INTL ARPT  (LRF)LITTLE ROCK AFB  (LRU)LAS CRUCES ARPT   (LSE)LA CROSSE MUNI  (LSF)LAWSON AAF FT B 
##                     3                     1                    16                     1                    12                     3                    11                     1 
##   (LSV)NELLIS AFB LAS       (LTS) Altus AFB (LTS) Altus Air Force        (LTS)ALTUS AFB         (LUF)LUKE AFB  (LUK)LUNKEN FLD CINC  (LUL)HESLER FLD LAUR  (LVM)LIVINGSTON ARPT 
##                     5                     5                     4                    27                     3                     8                     8                    10 
##   (LWS)NEZ PERCE MUNI  (LWT)LEWISTON MUNI A  (LYH)GLENN FLD LYNCH    (MAF) MIDLAND INTL (MAI)MARIANNA MUNICIP  (MBS)TRI CITY APT SA  (MCB)LEWIS FLD MCCOM      (MCF)MC DILL AFB 
##                     1                     1                     3                    35                     1                     1                     2                     5 
##  (MCI)KS CITY INTL AR     (MCK)MC COOK ARPT  (MCN)WILSON ARPT MAC  (MCO)ORLANDO INTL AR  (MCW)MASON CITY MUNI  (MDH)CRBNDL/MRFYSBRO  (MDW)MIDWAY ARPT CHI          (MEH)MEACHAM 
##                    17                    12                     3                    15                     4                     6                    13                     2 
##  (MEI)KEY FLD MERIDIA  (MEM)MEMPHIS INTL AR       (MER)CASTLE AFB             (mesonet)  (MFE)MILLER INTL ARP     (MFR)MEDFORD ARPT  (MGE)DOBBINS AFB MAR  (MGM)MONTGOMERY ARPT 
##                     2                     8                     4                     1                     2                     7                     1                     6 
##  (MGW)HART FLD MORGAN    (MHE)MITCHELL ARPT   (MHK)MANHATTAN MUNI       (MHR)MATHER AFB        (MHS)MT SHASTA       (MIA)MIAMI INTL        (MIB)MINOT AFB  (MIE)JOHNSON FLD MUN 
##                     1                     9                     6                     1                     1                    33                    26                     1 
##   (MIV)MILLVILLE MUNI  (MKC)KS CITY DNTN AR  (MKE)MITCHELL APT MI    (MKG)MUSKEGON ARPT  (MLB)WFO MELBOURNE A  (MLC)MC ALESTER MUNI  (MLI) QUAD CITY ARPT  (MLS)WILEY FLD MILES 
##                     3                     4                     6                     1                     2                     2                    17                     9 
##  (MLT)MILLINOCKET ARP  (MML)RYAN FLD MARSHA       (MMO)MARSEILLES    (MMT)MC ENTIRE ANG  (MMU)MORRISTOWN MUNI  (MOB)MOBILE BATES FL     (MOD)MODESTO ARPT  (MOT)MINOT INTL ARPT 
##                     1                     5                     2                    10                     1                    35                     7                     2 
## (MPV)-MONTPELIER ARPT  (MQT)MARQUETTE CO AR  (MRB)SHEPHERD FLD MR  (MRF)MARFA MUNI ARPT    (MRY)MONTEREY ARPT  (MSL)MUSCLE SHOALS A  (MSN)TRUAX FLD MADIS  (MSO)MISSOULA INTL A 
##                     4                     2                     7                     3                     2                     5                     7                     9 
##  (MSS)RICHARDS FLD MA  (MSY)MOISANT FLD NEW  (MTC)MT CLEMENS/SELF  (MTN)MARTIN ARPT BAL   (MTW)MANITOWOC ARPT   (MWA)MARION WLLMSON  (MWH)GRANT CO ARPT M  (MWL)MINERAL WELLS A 
##                     1                     8                     9                     1                     2                     2                     1                     6 
##  (MXF)MAXWELL AFB MNT  (MYF)MNTGMRY FLD SAN  (MYR)MYRTLE BEACH AF    (NBC)MCAS BEAUFORT       (NBE)NAS DALLAS  (NBG)NAS NEW ORLEANS   (NCA)MCAS NEW RIVER    (NEL)NAS LAKEHURST 
##                     2                     3                     2                     3                     1                     5                     4                     1 
##      (NEW)LKFRNT ARPT  (NEW)LKFRNT ARPT NEW       (NFL)NAS FALLON  (NGP)NAS CORPUS CHRI      (NGU)NAS NORFOLK  (NHK)NAS PATUXENT RI   (NID)NAF CHINA LAKE  (NIP)NAS JACKSONVILL 
##                     1                    15                     4                     3                     3                     3                     4                     7 
## (NIP)NAS JACKSONVILLE  (NIR)NAS CHASE FLD B   (NKT)MCAS CHERRY PT      (NLC)NAS LEMOORE     (NMM)NAS MERIDIAN    (NPA)NAS PENSACOLA  (NQA)NAS MEMPHIS MIL   (NQI)NAS KINGSVILLE 
##                     1                     2                     4                     5                     3                     4                     2                     2 
##     (NQX)KEY WEST NAS      (NRB)NAS MAYPORT   (NSE)NAS WHITNG FLD   (NTD)NAS POINT MUGU       (NTU)NAS OCEANA       (NTU)OCEANA NAS  (NXP)MCAF TWENTYNINE  (NXX)NAS WILLOW GROV 
##                    13                     7                     3                     2                     4                    18                     1                     3 
##    (NYG)MCAS QUANTICO    (NZC)NAS CECIL FLD  (NZJ)ELTORO MCAS SAN  (OAJ)ELLIS FLD JACKS   (OCS)CAMP PENDLETON    (ODX)SHARP FLD ORD       (OFF)OFFUTT AFB  (OFK)STEFAN FLD NORF 
##                     1                     3                     1                     1                     2                     3                     3                     6 
##  (OGD)OGDEN MUNI ARPT  (OJC)JOHNSON CO EXEC   (OKC) Oklahoma City     (OKC) Will Rogers  (OKC)WILL ROGERS APT  (OKK)KOKOMO MUNI ARP  (OLF)WOLF PT INT ARP (OLF)WOLF PT INT ARPT 
##                     1                     3                     2                     5                    19                     3                     3                    10 
## (OLS) NOGALES INTL AR    (OLU)COLUMBUS ARPT  (OMA)EPPLEY FLD OMAH     (ONL)O NEILL ARPT     (ONO)ONTARIO ARPT (ONX)CURRITUCK COUNTY   (OPF)OPA LOCKA ARPT  (ORD)O'HARE INTL ARP 
##                     4                     4                     3                    24                     1                     6                     6                    12 
##   (ORF) NORFOLK ARPT. (ORF)NORFOLK INTERNAT (ORK)NO LITTLE ROCK A  (ORL)ORLANDO EXEC AR  (OSC)WURTSMITH AFB O  (OSH)WITTMAN FLD OSH  (OSU)OH ST UNIV ARPT  (OTG)WORTHINGTON ARP 
##                     1                     6                    12                     3                     2                     6                     5                     7 
##  (OTH)NORTH BEND ARPT  (OTM)OTTUMWA INDSTRL          (OUN) Norman (OUN)NORMAN WESTHEIME       (OUN)NWS NORMAN   (OWB)OWENSBORO ARPT (OXB)OCEAN CITY AIRPO    (OZR)FT RUCKER AAF 
##                     2                    16                     1                    18                     2                     4                     6                     3 
## (OZR)OZARK FORT RUCKE  (P02)POPLAR BLUFF AR        (P07)SANDERSON   (P28)MEDICINE LODGE         (P35)SPICKARD    (P59)COPPER HARBOR           (P68)EUREKA   (P70)CLINES CORNERS 
##                     1                     4                     7                     6                     5                     3                     5                     1 
##  (PAH)BARKLEY ARPT PA  (PBF)PINE BLUFF ARPT  (PBI)PALM BEACH ARPT   (PDT)PENDLETON ARPT  (PDX)PORTLAND INTL A  (PFN)PANAMA CITY ARP (PFN)PANAMA CITY ARPT        (PGA)PAGE ARPT 
##                    29                     4                    17                     3                     4                     5                     2                     6 
##             (PGO)PAGE     (PHF)NEWPORT NEWS  (PHL)PHILADELPHIA IN      (PHP)PHILIP ARPT  (PHX)SKY HARBOR ARPT  (PIA)GTR PEORIA ARPT   (PIB)PINE BELT RGNL  (PIE)ST PETE/CLRWATE 
##                     1                     7                    22                    11                    11                     6                     6                    11 
##   (PIH)POCATELLO MUNI      (PIR)PIERRE ARPT   (PIT)GTR PITTSBURGH  (PKB)WILSON FLD PRKR  (PKF)PARK FALLS MUNI    (PMD)PALMDALE ARPT      (PNC) Ponca City  (PNC)PONCA CITY ARPT 
##                     5                    13                     1                     3                     1                     1                     1                    16 
##  (PNE)NE ARPT PHILADE  (PNS)PENSACOLA REGIO  (POB)POPE AFB FAYETT  (POE)FT POLK AAF LEE  (PQI)PRESQUE ISLE AR    (PRC)PRESCOTT ARPT    (PRX)COX FLD PARIS  (PSB)MID ST ARPT PHI 
##                     2                     4                     2                     1                     2                     6                     2                     1 
##  (PSC)TRI-CITIES ARPT  (PSF)PITTSFIELD ARPT        (PSM)PEASE AFB   (PSP)PALM SPGS ARPT  (PSX)PALACIOS MUNI A     (PTK)PONTIAC ARPT  (PUB)PUEBLO MUNI ARP   (PUC)CARBON CO ARPT 
##                     2                     4                     1                     3                     1                     5                    13                     2 
##  (PVD)TF GREEN ARPT P  (PVU)PROVO MUNI ARPT     (PVW)HALE CO ARPT      (PWA) Wiley Post (PWA) Wiley Post Airp   (PWA)WILEY POST APT   (RAL)RIVERSIDE MUNI  (RAP)RAPID CITY ARPT 
##                     1                     6                     2                     1                     1                    14                     3                    20 
##  (RBD)REDBIRD ARPT DA    (RBG)ROSEBURG ARPT   (RBL)RED BLUFF MUNI    (RCA)ELLSWORTH AFB  (RCA)ELLSWORTH AFB R  (RDG)SPAATZ FLD READ  (RDR)GRAND FORKS AFB   (RDU)RALEIGH-DURHAM 
##                     2                     1                     3                     3                    15                     4                     4                     1 
##  (REE)REESE AFB LUBBO  (RFD)GTR ROCKFORD AR  (RHI)RHINELANDER ARP  (RIC)BYRD FLD RICHMO   (RIV)RIVERSIDE ARPT  (RIW)RIVERTON RGNL A   (RKS)ROCK SPGS ARPT    (RLD)RICHLAND ARPT 
##                     4                     8                     4                     3                     1                    16                    12                     2 
##  (RME)GRIFFIS AFB ROM  (RND)RANDOLPH AFB SA  (RNO)CANNON ARPT REN  (ROA)WOODRUM FLD ROA   (ROC)ROCHESTER ARPT (ROW)ROSWELL IND AIRP  (RSL)RUSSELL MUNI AR   (RST)ROCHESTER MUNI 
##                     3                     1                     3                     5                     3                     7                    18                     9 
## (RTN)RATON CREWS AIRP  (RTN)RATON CREWS ARP          (RUM)RUMFORD     (RUT)RUTLAND ARPT  (RWF)REDWOOD FALLS A  (RWI)ROCKY MT WILSON  (RWL)RAWLINS MUNI AR  (S80)GRANGEVILLE ARP 
##                     3                     1                     9                     3                     1                     7                     4                     2 
##  (SAC)SACRAMENTO ARPT  (SAF)SANTA FE MUNI A (SAF)SANTA FE MUNI AI   (SAN)SAN DIEGO INTL  (SAT)SAN ANTONIO INT  (SAV)SAVANNAH INTL A  (SAW)KI SAWYER AFB G  (SBA)SANTA BARBARA A 
##                     3                     2                     1                     8                     5                     8                     2                     1 
##  (SBM)SHEBOYGAN CO AR  (SBN)MICHIANA ARPT S  (SBY)WICOMICO CO ARP   (SCK)STOCKTON METRO  (SDF)STANIFORD FLD L  (SDY)SIDNEY-RICHLAND   (SEA)SEATTLE-TACOMA  (SEE)SAN DIEGO GILLE 
##                     2                     2                     7                     4                     3                     3                     2                     1 
##     (SFB)SANFORD ARPT      (SFD)WINNER ARPT    (SFO)SFO INTL ARPT  (SGF)SPRINGFIELD ARP (SGF)SPRINGFIELD ARPT (SGT)STUTTGART MUNICI   (SGU)ST GEORGE MUNI  (SHR)SHERIDAN CO ARP 
##                     5                     8                     2                     4                     9                     1                    13                     5 
##  (SHV)SHREVEPORT RGNL  (SJC)SAN JOSE INTL A   (SJT)MATHIS FLD SAN    (SKA)FAIRCHILD AFB  (SKF)KELLY AFB SAN A   (SLC)SALT LAKE CITY  (SLE)MCNARY FLD SALE  (SLK)SARANAC LAKE AR 
##                     3                     2                    16                     1                     3                    14                     4                     2 
##  (SLN)SALINA MUNI ARP      (SMN)SALMON ARPT  (SNA)SANTA ANA CO AR      (SNY)SIDNEY ARPT  (SPI)SPRINGFIELD ARP         (SPS) Wichita   (SPS) Wichita Falls     (SPS)SHEPPARD AFB 
##                    10                     1                     5                    23                     4                     2                     2                    13 
##  (SQL)SAN CARLOS ARPT         (SRQ)SARASOTA (SRR)SIERRA BLANCA RE  (SSC)SHAW AFB SUMTER  (SSF)STINSON FLD SAN  (STJ)ST JOSEPH MEM A   (STL)LAMBERT FLD ST  (STP)HOLMAN FLD ST P 
##                     1                     2                     1                    15                     1                    10                    12                     1 
##  (STS)SANTA ROSA ARPT  (SUN)FRIEDMAN ARPT H  (SUS)SPIRIT/ST LOUIS       (SUU)TRAVIS AFB  (SUX)SIOUX CITY ARPT (SVC)SILVER CITY ARPT  (SVN)HUNTER AAF SAVA          (SWO)AIRPORT 
##                     1                     1                     5                     3                    16                     1                     3                     1 
## (SWO)STILLWATER AIRPO    (SXT)SEXTON SUMMIT     (SZL)WHITEMAN AFB           (T62)TOOELE    (TAD)TRINIDAD ARPT   (TCC)TUCUMCARI ARPT  (TCL)TUSCALOOSA ARPT  (TCS)TRUTH/CONSQNCES 
##                     6                     1                    16                     3                     1                     8                     3                     1 
##   (TDO)TOLEDO-WINLOCK   (TEB)TETERBORO ARPT   (TEX)TELLURIDE ARPT (TIK) Tinker Air Forc       (TIK)TINKER AFB (TIX) SPACE CENTER EX  (TIX)SPACE CNTR EXEC  (TLH)TALLAHASSEE ARP 
##                     1                     6                     4                     2                    18                     6                     5                     1 
## (TLH)TALLAHASSEE RGNL   (TOI)TROY MUNI ARPT   (TOL)TOLEDO EXPRESS  (TOP)BILLARD ARPT TO  (TPA)TAMPA INTL ARPT     (TPH)TONOPAH ARPT  (TPL)TEMPLE MUNI ARP  (TRI)TRI CITY ARPT B 
##                     2                     1                     5                    16                     4                     1                     5                     2 
##  (TRK)TRUCKEE/TAHOE A     (TRM)THERMAL ARPT     (TTN)TRENTON ARPT  (TUL)TULSA INTL ARPT  (TUP)LEMONS ARPT TUP  (TUS)TUCSON INTL ARP (TUS)TUCSON INTL ARPT  (TVC)TRAVERSE CITY A 
##                     2                     2                     4                    15                     8                     2                     2                     1 
##  (TVF)THIEF RVR FALLS  (TWF)TWIN FALLS ARPT   (TXK)TEXARKANA ARPT  (TYR)TYLER POUNDS FL  (TYS)MCGHEE TYSON KN   (U07) BULLFROG/GLEN  (U17)BULLFROG (AMOS)  (U24)DELTA MUNI ARPT 
##                     4                     5                     4                     3                     8                    10                     2                     1 
##  (U28)GREEN RIVER MUN      (UCC)YUCCA FLATS  (UIN)QUINCY MUNI ARP           (UMN)MONETT      (UOX)OXFORD ARPT        (VAD)MOODY AFB  (VAD)MOODY AFB VALDO   (VBG)VANDENBERG AFB 
##                     2                     4                    10                    10                     3                     4                     2                     1 
##  (VCT)VICTORIA RGNL A  (VCV)GEORGE AFB VICT      (VEL)VERNAL ARPT  (VIH)ROLLA/VICHY ARP (VIH)ROLLA/VICHY ARPT     (VIS)VISALIA ARPT (VLD)VALDOSTA REGIONA  (VOK)VOLK AAF CAMP D 
##                     7                     1                     2                     3                     2                     1                     1                    10 
##        (VPS)EGLIN AFB  (VRB)VERO BEACH MUNI  (VTN)MILLER FLD VALE     (VTP)LA VETA PASS  (W30)OCEAN CITY MUNI       (WAL)WALLOPS IS (WAL)WALLOPS ISLAND F   (WDG) WOODRING ARPT 
##                     3                     4                    13                     1                     1                     6                     5                     5 
##  (WEY)WEST YELLOWSTON  (WJF)WM FOX FLD LANC   (WMC)WINNEMUCA MUNI  (WRB)WARNER ROBINS A     (WRI)MC GUIRE AFB  (WRL)WORLAND MUNI AR      (Y22)LEMMON ARPT    (Y26)MOBRIDGE ARPT 
##                     2                     1                     5                     7                     4                     4                     2                     5 
##  (Y69)LITCHFIELD MUNI  (YIP)WILOW RUN APT D  (YKN)CHAN GURNEY ARP  (YNG)YOUNGSTOWN MUNI   (YUM)YUMA INTL ARPT  (ZZV)ZANESVILLE MUNI          .5 S Bruning         .5 S Fulda to 
##                     1                     1                     5                     1                     9                     2                     1                     1 
##         .5 S Randalia         .5 S Sullivan      .5 SE Pilot Rock                     ?  ~10NM SW EVRGLDS CTY                   020               063>066          1 E Coolidge 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##           1 E Kinsley              1 N Alvo         1 S Chickasha             1 S Eagle            1 S Pender             1 S Pratt            1 S Snyder            1 W Auburn 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##            1 W Booker            1 W Duncan           1 W Liberal        1 W Macksville            1 W Vanoss        10-15NM E KFLL        10 E Smithboro           10 N Dryden 
##                     2                     1                     1                     1                     1                     1                     1                     1 
##          10 N Pickens     10 SE MIAMI BEACH          10 W Jetmore    10NM SE BOCA RATON         10NM W BIMINI           10SW ELKINS        11 N DICKINSON          12 Hill City 
##                     1                     1                     2                     1                     1                     1                     1                     1 
##                   124   12N WEBSTER SPRINGS     12SE GLENNS FERRY         14 W Kalvesta          15 W Jetmore            155007 FLL          15NM E DANIA             18 NE PBI 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##               18S MAF            1S Norfolk            1W Kendall        1W LAKE LOWELL      2-3E BAL HARBOUR          2-5NW MURPHY        2 E Greensburg            2 E Guymon 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##           2 E Satanta            2 N Guymon        2 NW DIMONDALE           2 S Buffalo             2 S Wayne          2 SW FRYBURG        2 W Macksville             2 W Perry 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##    20NM E SUNNY ISLES         20W BURNS JCT          20W Kalvesta             20WNW FLL         25 SW CHADRON        28E BAKER CITY         2NE PETROLEUM        2S RDU AIRPORT 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##            3 E Belpre        3 E Macksville   3 ISLAND STATE PARK            3 N Willow             3 S ELGIN           3 S Hugoton        3 W Greensburg              3 W Maud 
##                     2                     1                     1                     1                     1                     1                     1                     1 
##       3 W Mullinville     30NM E HALLANDALE   30NM E OF CAPE FLA.      3550 S OCEAN AVE       3E 0.5N ERSKINE       3NM EAST OF PMP         3NM S MM 84.5             3NM W APF 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##         4 NE  WEIDMAN         4 NE GARRISON          4 SE FRYBURG           4 W Liberal            4 W Newman     4NM SW CAPE SABLE         4S CHARLESTON            4S El Reno 
##                     1                     1                     1                     1                     1                     1                     1                     2 
##         4S TWIN FALLS              4W BOISE           5 N Liberal  5 SE Shallotte Inlet            5 SW Murdo        5 W Charleston           5 W Stanton     55TH RD/P.B. BLVD 
##                     1                     1                     1                     1                     1                     2                     1                     1 
##        5N OF DUCK KEY           5NM E DANIA             5NM N EYW       5NW RDU AIRPORT               5W YORK     69TH N & WOODLAWN         6NM SE OF EYW           7 E Amorita 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##         7 N Morrilton       7 N Three Lakes            7 S Arnett         7 W Ness City 70 mph wind gusts and         7S CUNNINGHAM            8 N PUEBLO      860 S OCEAN BLVD 
##                     1                     1                     1                     1                     1                     1                     1                     1 
##            9 N Custer    9300 FOUNTAIN BLUE             96 CORNER A large part of south A low pressure system a washing machine.  I                 AARON            AARON ARPT 
##                     1                     1                     3                     1                     1                     1                    10                     2 
##          AARONS CREEK            Aaronsburg            AARONSBURG                ABADYL                ABANDA                 ABARR             Abbeville             ABBEVILLE 
##                     3                     1                     1                     6                     2                    21                    10                   128 
##   Abbeville & Calhoun         Abbeville and ABBEVILLE MUNICIPAL A  Abbeville to Maurice            ABBEY DELL            Abbeyville  ABBEYVILLE DAVIS ARP             ABBOT VLG 
##                     1                     1                     1                     1                     1                     1                     4                    10 
##            ABBOTSFORD                Abbott                ABBOTT           ABBOTTSBURG           ABBOTTSFORD           Abbottstown           ABBOTTSTOWN          ABBOTTSVILLE 
##                    22                     1                    47                     7                     5                     1                     3                     1 
##  [ reached getOption("max.print") -- omitted 53429 entries ]
## [1] "Unique values of var1:"
##    [1] ""                      "North Alabama"         "Athens"                "Tanner"                "Copperfield"           "Cairo/Mt. Rozell"      "Southwest Alabama"    
##    [8] "Southwest and South A" "Southeast Alabama"     "Prattville"            "White City"            "Daphne"                "Bay Minette"           "Foley"                
##   [15] "Loxley"                "Spanish Fort"          "Robertsdale"           "Stockton"              "Fairhope"              "Central"               "Tensaw"               
##   [22] "Barnwell"              "Lottie"                "Stapleton"             "Mobile Interstate 10"  "Gulf Shores"           "Hurricane"             "Stockton and"         
##   [29] "Seminole"              "Silverhill"            "Orange Beach"          "Fairhope/Silverhill/F" "Mobile Bay"            "Gateswood"             "Foley and Gulf Shores"
##   [36] "Elberta"               "Eufaula"               "Texasville"            "Clayton"               "Clio"                  "Pondville"             "Brent"                
##   [43] "Centreville"           "West Blocton"          "Nectar"                "Oneonta"               "Sawyer Mtn"            "Blountsville"          "Cleveland"            
##   [50] "Hayden"                "Allgood"               "Locust Fork"           "Remlap"                "Brooksville"           "Summit"                "Union Springs"        
##   [57] "Union"                 "Greenville"            "Georgiana"             "Foster Flats"          "Ohatchee"              "Jacksonville"          "Dearmanville"         
##   [64] "Piedmont"              "Anniston"              "Oxford"                "Lafayette"             "Lanett"                "Penton"                "LaFayette"            
##   [71] "Countywide"            "Shawmut"               "Valley"                "Centre"                "Goshen"                "Cedar Bluff"           "North & Central"      
##   [78] "Sand Rock"             "N Weiss Lake"          "Leesburg"              "Spring Garden"         "Northern Part"         "Maplesville"           "Butler"               
##   [85] "Yantley"               "Gilbertown"            "Hodgewood"             "Grove Hill"            "Jackson"               "Alma"                  "Coffeeville"          
##   [92] "Thomasville"           "Dickinson-Fulton"      "Fulton"                "Manila and Gosport"    "Ashland"               "Millerville"           "Baldwin"              
##   [99] "Lineville"             "Heflin"                "Cleburne"              "Frisco"                "Enterprise"            "N Enterprise"          "New Brocton"          
##  [106] "New Brockton"          "Elba"                  "Jack"                  "Western Section"       "Cherokee"              "Tuscumbia"             "Muscle Shoals"        
##  [113] "Allsboro"              "Riverton"              "S Cherokee"            "Littleville"           "Spring Valley"         "West Portion"          "Evergreen"            
##  [120] "Lyeffion"              "Stuartville"           "Opp"                   "Andalusia and"         "Andalusia"             "Red Level"             "Florala"              
##  [127] "Gantt"                 "Beda"                  "Gantt Lake"            "Brantley"              "Saville"               "Hanceville"            "Trimble"              
##  [134] "Cullman"               "Holly Pond"            "Eva"                   "North Vinemont"        "Fairview"              "Cold Springs"          "Jones Chapel"         
##  [141] "Good Hope"             "Near Baldwin"          "NR Trimble"            "Coal Springs"          "Providence"            "Enon"                  "Northeast Part"       
##  [148] "Wilburn"               "Bremen"                "Cullman to"            "Crane Hill"            "Joppa"                 "Ozark"                 "Level Plains"         
##  [155] "Selma"                 "Salem"                 "Grove Oak to Rainsvil" "Rodentown"             "Henager"               "Fort Payne"            "Oak Grove"            
##  [162] "Sylvania"              "Powell"                "Wetumpka"              "Elmore"                "Eclectic"              "Tallassee"             "Central section"      
##  [169] "Red Hill"              "Dixonville"            "Pollard"               "Atmore"                "McCullough"            "Flomaton"              "Central and East port"
##  [176] "Brewton"               "East"                  "Rainbow City"          "Gadsden"               "Wellington"            "Walnut Grove"          "Hokes Bluff"          
##  [183] "Reece City"            "Atalla"                "Altoona"               "Concord"               "Fayette"               "Northeast"             "Berry"                
##  [190] "Russellville"          "Near Russellville"     "Belgreen"              "Hodges"                "Phil Campbell"         "South Portion"         "Red Bay"              
##  [197] "Newburg"               "Slocomb & Hartford"    "Hartford"              "Geneva"                "Near Jena"             "Boligee"               "Greensboro"           
##  [204] "Moundville"            "NE area of county"     "Headland"              "Abbeville"             "Haleburg"              "Dothan"                "Randolph Co"          
##  [211] "Grangeburg"            "Cottonwood"            "Wicksburg"             "South Part"            "Madrid"                "Ashford"               "Scottsboro"           
##  [218] "Stevenson"             "Bridgeport"            "Pleasant View"         "Section"               "Dutton Section"        "Woodville"             "Francisco"            
##  [225] "Alliance"              "Birmingport"           "Hueytown"              "Maytown"               "Warrior"               "Forestdale"            "Graysville"           
##  [232] "US 78 West"            "Minor"                 "Centerpoint"           "Trussville"            "Airport Rd"            "Homewood"              "US 280/I459"          
##  [239] "Lake Purdy"            "Vestavia Hills"        "Birmingham"            "Bessemer"              "Leeds"                 "Gardendale"            "Grayson Valley"       
##  [246] "Fairfield"             "Irondale"              "Airport BHM"           "Ensley"                "Pleasant Grove"        "Hoover"                "Morris"               
##  [253] "Between Sulligent and" "Vernon"                "Millport"              "NR Sulligent and"      "Sulligent"             "Detroit"               "Kennedy"              
##  [260] "Crossville"            "Beaverton"             "Florence"              "Rogersville"           "Lexington"             "Waterloo"              "Elgin"                
##  [267] "Wheeler Dam"           "Anderson"              "Killen"                "Petersville"           "Cloverdale"            "Wheeler"               "Moulton"              
##  [274] "Town Creek"            "Mt. Hope"              "Danville"              "Decatur"               "Hatton"                "Mount Hope"            "Courtland"            
##  [281] "Caddo"                 "Auburn"                "Opelika"               "Gold Hill"             "Montgomery"            "Marvyn"                "Smiths"               
##  [288] "Limestone"             "Ardmore"               "Eastern part"          "Belle Mina"            "Greenbrier"            "Mooresville"           "Ripley"               
##  [295] "Northwest"             "Elkmont"               "Coxey"                 "Hayneville"            "Tuskegee"              "Nr Tuskegee"           "Meridianville"        
##  [302] "Huntsville"            "Hunknotsville"         "Madison"               "Airport"               "Redstone Arsenal"      "Hazel Green"           "SW Huntsville"        
##  [309] "Chase"                 "Gurley"                "Toney"                 "Demopolis"             "Sweetwater"            "Jefferson"             "Myrtlewood"           
##  [316] "Linden"                "Guin"                  "Winfield"              "Bear Creek"            "Hamilton"              "SW area of county"     "Mainly North"         
##  [323] "Brilliant"             "Whitehouse"            "Guin/Winfield"         "Boaz"                  "Arab"                  "Guntersville"          "Arab; Martling & Popl"
##  [330] "Albertville"           "Grant"                 "Black Island"          "Grant and Union Grove" "Beulah"                "Brindlee Mountain"     "Martling"             
##  [337] "Swearengin"            "Guntersville Union Gr" "Warrenton"             "Semmes Area"           "Eight Mile"            "Prichard"              "Mobile"               
##  [344] "Dauphin Island"        "Theodore"              "Point Clear"           "Citronelle"            "Kushla"                "Grand Bay"             "Dauphin Is."          
##  [351] "Semmes"                "Mt. Vernon"            "Fort Gaines"           "Wilmer"                "Saraland"              "Monroeville"           "Tunnel Springs"       
##  [358] "Beatrice"              "Excel"                 "Davenport"             "Mongomery"             "Priceville"            "Somerville"            "Oden Ridge & Eva"     
##  [365] "Falkville"             "Harknotselle"          "Hartselle"             "W Falkville"           "Lacon"                 "Lacey's Springs"       "Hulaco"               
##  [372] "Massey"                "Oak Ridge"             "Trinity"               "Marion"                "Carrollton"            "Gordo area"            "Reform"               
##  [379] "Ethelsville"           "Gordo"                 "Aliceville"            "Benevola"              "Wedowee"               "Big Springs"           "Almond"               
##  [386] "Rockdale"              "Roanoke"               "Rock Mills"            "Alabaster"             "Saginaw"               "Calera"                "Helena"               
##  [393] "Shelby"                "Chelsea"               "Siluria"               "Pelham"                "Vincent"               "Westover"              "Springville"          
##  [400] "Odenville-Argo Area"   "Branchville"           "Ashville"              "Ragland"               "Pell City"             "Argo"                  "Odenville"            
##  [407] "Steele"                "Ragland to 5 NE Rock"  "Geiger to Gainesville" "Cuba"                  "York"                  "Livingston"            "Bellamy"              
##  [414] "Ward"                  "Epes"                  "Emelle"                "Munford"               "Talladega"             "Lincoln"               "Childersburg"         
##  [421] "Sylacauga"             "Statewide"             "Sylacaugua"            "Alexander City"        "Dadeville"             "Camp Hill"             "New Site"             
##  [428] "Eagle Cove"            "Near Coker"            "Morrisbridge"          "Tuscaloosa"            "Near Lake Tuscaloosa"  "Vance"                 "Sipsey/Cooke"         
##  [435] "Northport"             "Near Samantha"         "Abernant"              "N Tuscaloosa"          "Samantha"              "Duncanville"           "Coker"                
##  [442] "Holt"                  "Jasper"                "Sipsey"                "Sumiton"               "Dora"                  "Eldridge"              "Saragossa"            
##  [449] "Townley"               "Parrish"               "Northeast and"         "Chatom"                "Millry"                "Leroy"                 "Southern Part"        
##  [456] "Camden"                "Coy"                   "Pine Hill"             "Hybart"                "Haleyville"            "Arley"                 "Delmar"               
##  [463] "Double Springs"        "Eastern sections"      "Helicon"               "Near Arley"            "Lynn"                  "Poplar Springs"        "Addison"              
##  [470] "Southwest Alaska"      "Aleutians"             "Southwest Ak"          "Kodiak Island"         "Ern Aleutians"         "Central Gulf Coast"    "Aleutians Ak Peninsul"
##  [477] "Alaska Peninsula"      "Eastern Aleutians"     "Ak Peninsula"          "Kodiak Is."            "Seal Island"           "Aleutians Southwest A" "Anchorage"            
##  [484] "Aleutians; Bristol Ba" "Ak Peninsula; Bristol" "Homer"                 "Bering Sea; Aleutians" "Kodiak"                "Anchorage; Alaska Pen" "Middleton Island"     
##  [491] "Srn 1/3rd Ak mainland" "Hope Village"          "Central N Gulf Coast"  "Western Aleutians"     "Kenai River"           "Ak Pen"                "Southern Mainland"    
##  [498] "Lynn Canal-Glacier Ba" "Lynn Canal-"           "Lynn Canal/Glacier Ba" "Lynn Canal - Glacier"  "Central Southeast"     "Central Southeast Ala" "Coastal Southeast Ala"
##  [505] "Central Southern and"  "Southern Southeast"    "Southern and Coastal"  "Southern Southeast Al" "South Central"         "Southcentral"          "Cold Bay"             
##  [512] "Whittier"              "Cape Romanzof"         "South central Alaska"  "Shemya"                "Valdez"                "South Central Alaska"  "Dutch Harbor"         
##  [519] "N. Gulf Coast"         "Copper River Basin"    "Bristol Bay"           "Saint Paul"            "Southern Ak"           "North Gulf Coast"      "Prince William"       
##  [526] "Prince William Sound"  "Girdwood"              "Bering Sea"            "McGrath"               "Seward"                "Port Graham"           "Ykn-Kuskokwim"        
##  [533] "Adak"                  "Anchorage Hillside"    "AKZO13"                "AKZO14-015"            "Southcentral AK"       "King Salmon"           "South-Central Alaska" 
##  [540] "South-central"         "Upper Cook Inlet"      "Cook Inlet"            "Kenai Peninsula"       "Kenai Penninsula"      "Kenai"                 "Delta"                
##  [547] "Copper River"          "Kuskokwim Valley"      "Pribilofs"             "Susitna Valley"        "Yukon/Kuskokwim"       "Yukon Kuskokwim"       "Yk.-Kuskokwim Delta"  
##  [554] "St. Johns"             "St. John's"            "Springerville"         "Northeast Plateau"     "Show Low"              "Winslow"               "Scottsdale"           
##  [561] "Santa Cruz Valley"     "Bowie"                 "Thatcher"              "South Central Arizona" "Douglas"               "Prescott"              "Tombstone"            
##  [568] "Ft. Huachuca"          "Willcox"               "Huachuca City"         "Cascabel"              "Sierra"                "Sierra Vista"          "Elfrida"              
##  [575] "Fort Huachuca"         "Flagstaff"             "Oak Creek"             "Grand Canyon"          "St.Johns"              "Sedona"                "Blue Ridge"           
##  [582] "Grand"                 "Oak Creek Canyon"      "Phantom Ranch"         "Oak Creek Cliffs"      "Fredonia"              "Parks"                 "Queen Creek"          
##  [589] "Tusayon"               "Page"                  "Grand Canyon N.P."     "Cameron"               "Tusayan"               "Payson"                "Winkelman"            
##  [596] "Miami"                 "Globe"                 "Safford"               "Blue River"            "Quartzsite"            "Vicksburg"             "Parker"               
##  [603] "Lake Havasu Cit"       "Wenden"                "Bouse"                 "Phoenix Area"          "New River"             "Phoenix"               "Deer Valley"          
##  [610] "Phoenix to"            "Chandler"              "Desert Hills"          "Black Canyon City"     "Gila Bend"             "Wickenburg"            "Mesa"                 
##  [617] "Avondale"              "Buckeye"               "Fountain Hills"        "Cave Creek"            "Wittman"               "NW Phoenix"            "Tempe"                
##  [624] "El Mirage"             "Sun City"              "Litchfield Park"       "Lake Pleasant"         "to 12"                 "Tucson"                "Ryan Field"           
##  [631] "Three Points"          "Marana"                "Ajo"                   "Waldo"                 "Magnolia"              "Lamartine"             "McNeil"               
##  [638] "Lumber"                "Macedonia"             "Emerson"               "Walkerville"           "Welcome"               "Taylor"                "Menifee"              
##  [645] "Plumerville"           "Morrilton"             "Oppelo"                "Center Ridge"          "Charleston"            "Pine Bluff"            "Cornerstone"          
##  [652] "Wabbaseka"             "Redfield"              "Wright"                "Pinebergen"            "White Hall"            "Tucker"                "Sherrill"             
##  [659] "Clarksville"           "Knoxville"             "Oark"                  "Tolleson"              "W Phoenix"             "SE Phoenix"            "Cashion"              
##  [666] "Glendale"              "Peoria"                "Sun City West"         "Gilbert"               "Bullhead City"         "Kingman"               "Littlefield"          
##  [673] "Lake Havasu City"      "UTZ-003-"              "UTZ-007-"              "UTZ-001<003-006-007-0" "UTZ-002-"              "UTZ-007-011-"          "Green Valley"         
##  [680] "Sacaton"               "Casa Grande"           "Aravica"               "Kelvin"                "Apache Junction"       "Stanfield"             "Oracle"               
##  [687] "Coolidge"              "Maricopa"              "San Manuel"            "Arizona City"          "Winkleman"             "Eloy"                  "Maricopa Phoenix"     
##  [694] "Nogales"               "Amado"                 "Sonoita"               "Prescott Valley"       "Paulden"               "Castle Hot Springs"    "Chino Valley"         
##  [701] "Lake Montezuma"        "Cordes Junction"       "Santa Cruz/Patagonia"  "Hillside"              "Crown King"            "Cornville"             "Camp Verde"           
##  [708] "Heber"                 "Mayer"                 "Wagoner"               "Dewey"                 "Yuma"                  "Roll"                  "Wellton"              
##  [715] "Tacna"                 "Somerton"              "Dateland"              "Stuttgart"             "DeWitt"                "Arkansas Post"         "Gillett"              
##  [722] "DeWitt to 3.5 SSE St." "Casscoe"               "Almyra"                "Crocketts Bluff"       "Northern and Central"  "Northern Arkansas"     "All of  Arkansas"     
##  [729] "West Crossett"         "Hamburg"               "Wilmot"                "Crossett"              "Portland"              "Parkdale"              "Berlin"               
##  [736] "Wilmont"               "Midway"                "Mountain Home"         "Gamaliel"              "Norfork"               "Cotter"                "Lakeview"             
##  [743] "Henderson"             "Siloam Springs"        "Gentry"                "Bentonville"           "Highfill"              "Pea Ridge"             "Dumas"                
##  [750] "Cherokee City"         "Rogers"                "Sulphur Springs"       "Centerton"             "Avoca"                 "Benton"                "Gravette"             
##  [757] "Bella Vista"           "Maysville"             "Little Flock"          "Hiawasse"              "NR Gravette"           "NR Bentonville"        "Monte Ne"             
##  [764] "Lowell"                "Cave Springs"          "Maysville-Gravette"    "Hiwasse"               "Gateway"               "Harrison"              "Lead Hill"            
##  [771] "Bergman"               "Alpena"                "Gaither"               "Western Grove"         "Dogpatch"              "Zinc"                  "Batavia"              
##  [778] "Omaha"                 "Valley Springs"        "Diamond City"          "Ingalls"               "Jersey"                "Hermitage"             "Banks"                
##  [785] "Warren"                "Marsden"               "Hampton"               "Harrell"               "Thornton"              "Berryville"            "Green Forest"         
##  [792] "Grandview"             "Eureka Springs"        "NR Beaver"             "Urbanette"             "Eureka"                "Eudora"                "Lakeport"             
##  [799] "Lake Village"          "Rich Mtn"              "Indian"                "Frenchmans Bayou"      "Fountain Hill"         "Gurdon"                "Caddo Valley"         
##  [806] "Whelen Springs"        "Hopeville"             "Curtis"                "Okolona"               "Alpine"                "Gum Springs"           "Arkadelphia"          
##  [813] "Amity"                 "Burtsell"              "Hollywood"             "McDougal"              "Corning"               "Rector"                "Knoble"               
##  [820] "Peach Orchard"         "Piggott"               "Knob"                  "Quitman"               "Heber Springs"         "Greers Ferry"          "Greers Ferry Lake"    
##  [827] "Prairie View"          "Paris"                 "Higden"                "Prim"                  "Tumbling Shoals"       "Mt. Zion"              "New Edinburg"         
##  [834] "Rison"                 "Woodlawn"              "Lake Columbia"         "Ada"                   "Solgohachia"           "Saint Vincent"         "Hattieville"          
##  [841] "Jerusalem"             "Birdtown"              "7 N Morrilton"         "Jonesboro"             "Brookland"             "Cash"                  "Monette"              
##  [848] "Caraway"               "Bay"                   "Dixie"                 "Natural Dam"           "Cedarville"            "Chester"               "Van Buren"            
##  [855] "Mulberry"              "Kibler"                "Dyer"                  "Mansfield"             "Mt. Gaylor"            "Rudy"                  "Mountainburg"         
##  [862] "Uniontown"             "West Memphis"          "Crawfordsville"        "Bruins"                "Horseshoe Lake"        "Shearerville"          "Proctor"              
##  [869] "Earle"                 "Turrell"               "Edmonson"              "Parkin"                "Wynne"                 "Cherry Valley"         "Vanndale"             
##  [876] "Dalark"                "Pine Grove"            "Carthage"              "Sparkman"              "Manning"               "Fordyce"               "Tulip"                
##  [883] "Ouachita"              "Halley"                "Watson"                "Arkansas City"         "Back Gate"             "McGehee"               "McArthur"             
##  [890] "Tillar"                "Wilmar"                "Monticello"            "Lacey"                 "Rock Springs"          "Enola"                 "Vilonia"              
##  [897] "Conway"                "Guy"                   "Mayflower"             "Saltillo"              "Naylor"                "Wooster"               "Otto"                 
##  [904] "Mount Vernon"          "Watalula"              "Cass"                  "Fort Smith"            "Altus"                 "Wiederkehr Village"    "Cecil"                
##  [911] "Branch"                "Viola"                 "Mammoth Spring"        "Agnos"                 "Moko"                  "Hot Springs"           "Lake Hamilton"        
##  [918] "Lonsdale"              "Crystal Springs"       "Lake Catherine"        "Ravanna"               "Mountain Pine"         "Fountain Lake"         "Sunshine"             
##  [925] "Buckville"             "Lake Ouachita"         "Mountain Valley"       "Pearcy"                "Jessieville"           "Hot  Springs"          "Hot Springs Village"  
##  [932] "Sheridan"              "Ico"                   "Tull"                  "Palestine"             "Leola"                 "Grapevine"             "Brush Creek"          
##  [939] "Prattsville"           "Paragould"             "Walcott"               "Hooker"                "Guernsey"              "Blevins"               "Tokio"                
##  [946] "Compton"               "Ozan"                  "Spring Hill"           "Washington"            "Hope"                  "McNab"                 "Clow"                 
##  [953] "Patmos"                "Silver Springs"        "Sheppard"              "Centerville"           "Doyle"                 "Malvern"               "Donaldson"            
##  [960] "Glen Rose"             "Bonnerdale"            "Bismarck"              "Lake DeGray"           "Friendship"            "Jones Mill"            "Magnet Cove"          
##  [967] "DeRoche"               "Social Hill"           "Caney"                 "Booneville"            "Gifford"               "Point Cedar"           "Okay"                 
##  [974] "Tollette"              "Nashville"             "Dierks"                "Center Point"          "Saratoga"              "Buck Range"            "Mineral Springs"      
##  [981] "Schaal"                "Umpire"                "Baker Springs"         "Muddy Fork"            "Sandbar"               "Corinth"               "Newark"               
##  [988] "Oil Trough-"           "Batesville"            "Oil Trough"            "Pfeiffer"              "Sulphur Rock"          "Cushman"               "Bethesda"             
##  [995] "South Side"            "Cord"                  "Locust Grove"          "Guion"                 "Mt. Pleasant"          "Melbourne"            
##  [ reached getOption("max.print") -- omitted 53429 entries ]
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
