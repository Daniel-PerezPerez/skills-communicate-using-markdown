# Markdown tutorial
The first lesson was about headlines and how there are 6 different leves. 

## Adding a picture
Here is the structure to add a picture from the web. 

This is a picture of a blue merle Border Collie. 
![Picture of Border Collie](https://upload.wikimedia.org/wikipedia/commons/b/be/Blue_merle_Border_Collie.jpg)

## Adding code
I am only familar with some R, Python and some command line code. I will add here an example of each.

``` r
library(tidyverse)

data <-
  tibble(
    id = paste("exp", 1:100),
    value = c(
      rnorm(50),
      rnorm(50, 4, 1)))
```

This is a code using Python (probably incorrect). 
``` python
import mne
import matplotlib.pyplot as plt

mne.io.read_edf("data_path.edf")
```
## Adding list
According to the tutorial, adding list to the markdown is useful because it can help us keep track of the progress for specific tasks. 

We have to be careful about the syntax because otherwise the list will not work. 

Here is an example: 
- [x] Write a header in the index.md file
- [x] Add a picture in the index.md file
- [x] Add code to the index.md file
- [x] Add a list to the index.md file
- [ ] Commit
- [ ] Wait for the next step
