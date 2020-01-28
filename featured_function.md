# :hatching_chick: Featured functions

<br>

- [`tidylog()`](#library(tidylog))
- [`beep()`](#beep-beepnotes)
- [`function2()`](#function2)

<br>

# `library(tidylog)`

R just got even friendlier. This is technically a package, but it makes all of your _tidyverse_ functions present you with a nice informative messages after running them. Here's a few.




# `beep()`, `beep()`:notes: 

Add a little music to your scripts! The `beep()` function from the `beepr` package plays various sounds on command. 
Use it to play a sound to alert you when a long running command completes. 
Here's an example that plays the happy __Mario__ coin sound after the script runs succesfully. 

```{r}
devtools::install_github("beepr")
```

<img src="images/mario.ico" width="13%" />

  
```{r}
library(beepr)

df <- data.frame(x = 0:30, y = 200:230)

# Print every row and then CELEBRATE with Mario
for(i in 1:nrow(df)) {
  print(df[i, ])
}

# Success!!
beepr::beep("mario")

```


# `function2()`

# `function3()`
