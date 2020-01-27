# :hatching_chick: Featured functions


<br>

## :notes: `beep` `beep` `r icon::fa("music")` 

Add a little fun to your scripts! The `beep` function from the `beepr` package plays various sounds on command. 
Use it to play a sound to alert you when a long running command completes. 
Here's an example that plays the happy __Mario__ coin sound after the script runs succesfully. 

__Try this:__

```{r}
devtools::install_github("beepr")
```

<img src="images/mario.ico" style="float: left; margin-top: 2px; margin-right: 18px;" />

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
---

