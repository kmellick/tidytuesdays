# Non-detects

Examples of summarizing and visualizing **non-detect** or **censored** data.


## Air toxics monitoring data

```r
library(readr)

air <- read_delim("https://github.com/MPCA-air/public-data/blob/master/Monitoring%20data/Air%20Toxics%20Results%20MN%202017.txt?raw=true", 
                  delim = "|")

View(air)
```


