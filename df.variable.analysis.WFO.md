---
title: "WFO Variable Analyses"
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
##   [1] ""    ""    ""    "AMA" ""    "OKX" "PHI" ""    "FFC" "BIS" "ARX" "LMK" "OUN" "SGF" "CLT" "BYZ" "LBF" "SJT" "DMX" "CLE" "FSD" "AFG" "CRP" "FGF" "LBF" "LWX" "STL" "BIS" "AMA" "LOT"
##  [31] "AT"  "SHV" "OUN" "BTV" "PHI" "GLD" "DMX" "PUB" "OUN" "ATA" ""    "ILN" "REV" "ICT" "BMX" "CAE" "OUN" "DMX" "NG"  "DDC" "MAF" "TOP" "OHX" "FWD" "HGX" "MRX" "TSA" "ATA" "DVN" "ARX"
##  [61] "SGF" "MRX" "ILM" "PHI" "FTW" "ATL" "GID" "EWX" "HNX" "MLB" "FWD" "GJT" "GSP" "BUF" "UNR" "APX" "HGX" "RNK" "CHA" "TOP" "LBF" "JAX" ""    ""    "GSP" "AT"  ""    "ARX" "FSD" "MKX"
##  [91] ""    "PAH" "PUB" "LCH" "MOB" "CLE" "ILN" "MT"  "MRX" "BUF"
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
##  [1] "IMT" "IMT" "IMT" "ATA" "ATA" "ATA" "ATA" "ATA" "ATA" "ATA"
## [1] "Data frame of 25 smallest unique char-limited values:"
##    var1_30 nchar
## 1              0
## 2        T     1
## 3        S     1
## 4        R     1
## 5        2     1
## 6        B     1
## 7        C     1
## 8        A     1
## 9        G     1
## 10       M     1
## 11       N     1
## 12       L     1
## 13       Q     1
## 14       U     1
## 15       O     1
## 16       P     1
## 17       Y     1
## 18       I     1
## 19       D     1
## 20      NG     2
## 21      RY     2
## 22      MT     2
## 23      TS     2
## 24      AT     2
## 25      MG     2
## [1] "Summary of nchar(var1, allowNA = TRUE):"
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##    0.00    3.00    3.00    2.48    3.00    3.00 
## [1] "Histogram of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.WFO_files/figure-html/analyses-1.png)<!-- -->

```
## [1] "Boxplot of nchar(var1, allowNA = TRUE):"
```

![](VarAnalysis/df.variable.analysis.WFO_files/figure-html/analyses-2.png)<!-- -->

```
## [1] "Table of var1:"
## var1
##            CI    $AC    $AG    $AT    $AU    $BI    $BK    $BP    $BR    $BT    $BU    $BW    $CL    $CY    $DL    $DS    $DT    $EK    $EL    $EV    $FN    $FS    $FT    $GL    $GR 
## 142069      1      1      1      2      1      2      1      1      1      1      1      5      2      1      1      2      1      8      1      4      1      1      5      2      2 
##    $GT    $HO    $IN    $JA    $LA    $LB    $LN    $MC    $ME    $MI    $MS    $OF    $OK    $OM    $PI    $RD    $RI    $SA    $SD    $SH    $SJ    $SL    $SP    $ST    $TB    $TU 
##      1      1      3      4      1      2      1      1      2      1      4      2      6      2      1      1      3      4      2      7      1      1      5      4      1      5 
##    $VC    $YN    %SD      2     43    9V9      A    ABE    ABI    ABQ    ABR    ABY    ACT    ACY    AEB     AF    AFC    AFG    AGS    AHN    AJK    AKQ     AL    ALB    ALO    ALS 
##      1      1      1      3      1      1      9     95    246   3887   5724      1    222     98      1      1   1855   1443     73    250    756   6447      2   1259    169      2 
##    ALY    AMA     AN    ANC    APN    APX    AQQ    ARA    ARB    ART    ARX    ARY    ASO     AT    AT'    ATA    ATL    ATR    ATS    AUS    AVL    AVP      B    BDL    BDR    BFF 
##   6378   8256      1      1     62   2588     19      1    608      1   6026      2    251  12212      1   9589   1426      1      1    217     51     65     30     80     32    110 
##    BFL    BGM    BHM    BIH    BIL    BIS    BKW    BMH    BMX    BNA    BOI    BOS    BOU    BOX    BPT    BRO     BS    BTR    BTV    BUF    BWI     BY    BYZ    BZN      C    CAA 
##      1   5438   1273      1    102   6360     45      1   9520    189   1201    180   5654   6096    131   1132      1     98   3886   3293    171      1   4303      1      1      1 
##    CAE    CAK    CAO    CAR    CDR    CGF    CGI     CH    CHA    CHI    CHS    CJI    CLE    CLT    CMH    CMX    CNK    CNM     CO    CON    COS    COU    CPR    CRP    CRW    CSE 
##   5683    145      8   1477      2      1      1     33    169    839   5281      1  10606    150    173      1    529      1      1     48    153    203     29   2460    250      2 
##    CSG    CTP    CVG    CYS      D    D C    DAB    DAD    DAR    DAT    DAY    DBQ    DDC    DDS    DEC    DEN    DET    DIO    DLH    DMN    DMX     DN     DR    DRP    DRT    DSM 
##    332   5546    276   4265      3      1     45      1     14     23    151     70  11562      1      1    786      2      2   3188      1  11345     25      2      9     19   1302 
##    DTO    DTW    DTX     DU    DVN    EAU    EAX    EED    EKA    EKN    EKO    ELP    ELY    EPZ     ER    ERI    ERY    ESF    ESS    EUG    EVV    EWX    EYW    FAR    FAT    FCA 
##      1    163   5328      1   9342      1   8876      1    298    159      3     42      1    860      7    214      1     23      3      3    263   5381    958    190      4      6 
##    FFC    FGF    FGZ    FLG    FLL    FMY    FNB    FNT    FRI    FSD    FSM    FTS    FTW    FWA    FWD    FYV      G    GAG    GEG    GFK    GGW    GID    GJT    GLD    GLS     GN 
##  11120   9242   1546      6      1     37      1    145      1  10402    261      1   3513    138  12193      1      4      2     14      1   3985   5848   4812   7685     43      1 
##    GRB    GRI    GRR    GSO    GSP    GTF    GUA    GUM    GUP    GVW    GYX    HAR    HAT    HDO    HFO    HGX    HKY    HLN    HMS    HNX    HON    HOU    HSV    HTL    HTS    HUN 
##   3533    284   3409    133  11310    258    271     32      1      1   4156    217     52      1   2478   4561      1     18      1   2501    176    152    161     27     86   4097 
##    HVR      I    IAH    ICT     IL    ILG    ILM    ILN    ILX    IMT    IND    ING    INL    INW     IP    IPT    IRK    ISN    IWX    JAC    JAN    JAX    JKL    JSN    KEY      L 
##     11      1      1  11456      1     44   3684   7774   6064     77   8246      1     34      3      1     90      1     81   5395      1  13889   6128   6637      1    781     15 
##    LA/    LAN    LAS    LAX    LBB    LBF     LC    LC/    LCH    LCO     LE    LEX    LFT    LIT    LIX    LKN     LL    LMK    LNC    LND    LNK    LNS    LOT    LOX    LSE    LSX 
##      1     97      7     34   1180   7111     23      3   4268    296     10     85      1   1768   4179    588      1   7443      1     18     66      2   6420    921     56   9128 
##    LUB    LWS    LWX    LYH    LZK      M    M R    MAF    MCI    MCN    MCO    MEG    MEI    MEM    MFD    MFE    MFL    MFR     MG    MGM    MHX     MI    MIA    MIS    MKC    MKE 
##   4843      8  13174     23  11738      9      1   5738    237    278      2   8412    267    565     41      1   3138   1952      8    374   2548      1    487      3      1    861 
##    MKG    MKI    MKT    MKX    MLB    MLI    MLS    MLU     MM    MNT     MO    MOB    MPT    MPX    MQT    MRM    MRP    MRT    MRX    MRY    MSN    MSO    MSP     MT    MT/    MTR 
##     56      1      1   5364   2527    134      2      1      7      5      1   4568      1   9708   2329      1     24      2   7731     11    114   1759    826   3244      4    688 
##    MTT     MW     MY      N     NB    NBE     NE    NEW     NG    NG/    NGU    NIP    NMM     NP     NT    NUW    NWS    NYC      O    OAX     OB    OBS    OFF    OFK    OHX    OKC 
##      1      1     13     12      1      1      6    921   5276      2      1      1      1      1      5      1      1    364     10   8135      4      6      1    149   7077   5359 
##    OKM    OKX    OMA     ON    ONA    ONE    OOD     OP    ORF    ORH    OTH    OTX    OUN      P    PAH    PBI    PBZ    PDT    PDX    PER    PHI    PHL    PHX    PIA    PIH    PIT 
##      1   5586   1044      1      1     82      1      1    167     31      1   1796  17393      2  10653     23   7836   2153     36    154  12551    780    242    158   1512    800 
##    PKB    PKC    PMA    PNS    PQR     PR    PSP    PSR    PSX     PT    PUB    PVD    PWM      Q      R    R O     RA    RAH    RAP    RAR    RCA     RD    RDD    RDU    REP    REV 
##      2      1      1     83   1680      3      1   1473      1      7   4067     11    382      4   1530     11     21   5846    144      1      1      1     12   1646    108   2425 
##    RFD    RIC    RIW    RLD    RLX     RM     RN    RNG    RNK    RNO    RNP    ROA    ROC    ROW    RPT     RR     RS    RST     RT    RUD    RVY    RWL     RY      S    S/I    SAC 
##     65    140   1754      1   5865      3      9      2   9307     60      1     17     55     85      6     37      1    125      4      1      5      1    963   1818      1      4 
##    SAN    SAT    SAV    SBN    SDA    SDF    SEA    SEW    SFC    SFO    SGF    SGX    SHR    SHV    SJT    SJU    SLC    SLE    SLN    SMX    SPI    SPR    SPS    SSM     ST    STC 
##      3    709    154    141      4    736     21    778      1     18  11162   2244     20  11090   4337   3180   2500      1      1      3    175      4    267      4      2    129 
##    STK    STL    STO    SUX    SYR      T    T /     TA    TAE    TAT    TBW     TC    TCC    TEL    TFX    TLH    TMT    TOL    TOO    TOP    TRI    TRK     TS    TSA    TUL    TUP 
##      1   1181    796     97    136   7166      2      6   3750      1   4889      1      1      2   3201     73      2    124      1   9870     33      1      3  12483    847    163 
##    TUS    TVL    TWC    TYS      U    UIN    UNR     US    VCT    VEF    VTN    WAS    WBC    WMC    WRS     WS    WSP      Y    YKM    YNG     YT    YUM 
##     29      1   1501     98      1      2   7070     21     32   1864      3      2    848      1      1      7      3      1      8     78      1     33 
## [1] "Unique values of var1:"
##   [1] ""    "NG"  "T"   "RY"  "IMT" "MT"  "S"   "ATA" "MRY" "RPT" "LCO" "TS"  "AT"  "MG"  "R"   "RA"  "BHM" "HSV" "MEI" "MOB" "MGM" "BMH" "CSG" "NE"  "ONE" "AF"  "REP" "LC"  "MRP" "PHX"
##  [31] "TUS" "$IN" "$TU" "LAS" "YUM" "OFF" "INW" "FLG" "WS"  "2"   "DAR" "TMT" "TA"  "PER" "B"   "R O" "SHV" "LIT" "FSM" "MEM" "FTW" "$SH" "$ME" "FYV" "ANC" "SFO" "SAC" "EED" "TRK" "TVL"
##  [61] "PSP" "LAX" "RDD" "EKA" "SMX" "BIH" "SAN" "FAT" "BFL" "ART" "OBS" "DEN" "$CY" "COS" "ALS" "PUB" "GJT" "BOS" "BDR" "BDL" "C"   "ILG" "WBC" "RDU" "DAT" "NB"  "LE"  "MNT" "M R" "LA/"
##  [91] "PR"  "A"   "MIA" "AQQ" "JAX" "DAB" "MCO" "TLH" "NWS" "TBW" "FLL" "$MI" "MIS" "$JA" "$TB" "PNS" "EYW" "NIP" "PBI" "STL" "MLB" "FMY" "MRT" "US"  "DRP" "PT"  "OB"  "G"   "ATL" "SAV"
## [121] "BNA" "AHN" "MCN" "$AT" "ABY" "$SA" "$MC" "AL"  "AGS" "CHA" "BOI" "PIH" "GEG" "LWS" "M"   "MT/" "MM"  "RNG" "ARY" "RR"  "DN"  "N"   "PAH" "DEC" "SPI" "CHI" "MLI" "PIA" "IND" "EVV"
## [151] "RFD" "UIN" "$ST" "DBQ" "CJI" "SDA" "L"   "WSP" "ERY" "RVY" "SDF" "SBN" "FWA" "$EV" "$SD" "%SD" "ING" "CVG" "Q"   "NT"  "T /" "MW"  "DSM" "FSD" "OMA" "$DS" "DDS" "ALO" "SUX" "TC" 
## [181] "U"   "LL"  "O"   "DIO" "MPT" "WAS" "ON"  "D C" " CI" "P"   "TOP" "CNK" "DDC" "SLN" "ICT" "DTO" "GLD" "FRI" "TOO" "OKC" "MCI" "LEX" "HTS" "JKL" "OOD" "RN"  "NEW" "Y"   "MLU" "LFT"
## [211] "BTR" "LCH" "ESF" "PWM" "CAR" "LC/" "$BW" "$OF" "BWI" "EKN" "$EK" "BY"  "ALB" "ORH" "MTT" "ST"  "CMX" "ARB" "LAN" "DTW" "DET" "$LA" "MKG" "$DT" "GRR" "MQT" "HTL" "FNT" "$FN" "$GR"
## [241] "AEB" "SSM" "APN" "MY"  "RT"  "SAT" "GFK" "$MS" "MSP" "FAR" "$DL" "STC" "DLH" "RST" "MKT" "BIS" "INL" "ARA" "CO"  "I"   "JAN" "TUP" "NMM" "JSN" "DR"  "OP"  "AN"  "RS"  "D"   "RM" 
## [271] "MRM" "ER"  "TEL" "SGF" "SFC" "MKC" "IRK" "COU" "CGI" "WRS" "GVW" "STK" "MLS" "GTF" "BIL" "$BI" "$GT" "BZN" "GGW" "HVR" "HLN" "FCA" "MSO" "ESS" "ATS" "MI"  "NGU" "YT"  "FNB" "LBF"
## [301] "$LN" "LNK" "OFK" "BFF" "GRI" "LNC" "CDR" "VTN" "PMA" "$LB" "$OM" "ONA" "RNO" "ELY" "EKO" "WMC" "CON" "PHL" "NYC" "ACY" "GUP" "ABQ" "TCC" "CAO" "AMA" "DMN" "CNM" "MAF" "ROW" "ELP"
## [331] "MO"  "TAT" "BUF" "SYR" "BGM" "ROC" "$BU" "BTV" "$RD" "GSO" "HAT" "CLT" "ILM" "RLD" "AVL" "HKY" "RD"  "RUD" "43"  "ISN" "CLE" "DAY" "CGF" "YNG" "TOL" "$CL" "$YN" "CMH" "CAK" "MFD"
## [361] "DU"  "BS"  "TUL" "$OK" "GAG" "PKC" "OKM" "OTH" "PDX" "EUG" "SLE" "PDT" "MFR" "IL"  "SPR" "S/I" "PIT" "ERI" "LNS" "IPT" "$PI" "HAR" "AVP" "ABE" "PVD" "CAE" "GSP" "CHS" "CAA" "$AG"
## [391] "CSE" "$FS" "HON" "RAP" "9V9" "ABR" "RCA" "$HO" "TYS" "TRI" "RNP" "NG/" "RAR" "NP"  "ATR" "AT'" "GN"  "BRO" "HOU" "CRP" "SPS" "ABI" "$SP" "$FT" "BPT" "VCT" "SJT" "LBB" "AUS" "$AC"
## [421] "MFE" "$SJ" "NBE" "$VC" "HDO" "$AU" "ACT" "IAH" "$BP" "GLS" "PSX" "$GL" "$BR" "$EL" "FTS" "DRT" "SLC" "$SL" "$BT" "CH"  "$RI" "RIC" "ORF" "LYH" "ROA" "NUW" "SEA" "HMS" "YKM" "PKB"
## [451] "CRW" "$BK" "BKW" "MKE" "MSN" "GRB" "EAU" "MKI" "LSE" "IP"  "DAD" "RWL" "SHR" "CYS" "CPR" "JAC" "LND" "BMX" "TAE" "AFC" "AJK" "AFG" "TWC" "FGZ" "PSR" "LZK" "MEG" "VEF" "TSA" "BOU"
## [481] "LOX" "STO" "MTR" "HNX" "SGX" "REV" "BOX" "ALY" "OKX" "PHI" "LWX" "MFL" "FFC" "HFO" "OTX" "ILX" "LSX" "DVN" "LOT" "ILN" "DMX" "OAX" "IWX" "LMK" "ARX" "GID" "EAX" "RLX" "LIX" "GYX"
## [511] "PBZ" "AKQ" "DTX" "APX" "MPX" "FGF" "TFX" "BYZ" "LKN" "RAH" "RNK" "MHX" "EPZ" "MRX" "OUN" "PQR" "CTP" "UNR" "OHX" "FWD" "EWX" "LUB" "HGX" "MKX" "SEW" "RIW" "SJU" "GUA" "ASO" "HUN"
## [541] "KEY" "GUM"
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
