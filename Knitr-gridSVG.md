# knitr gridSVG
Bastiaan Quast  
28 September 2017  



# Base Plot


```r
hist(1:4, xaxt='n', yaxt='n', ann=FALSE)
```

![](Knitr-gridSVG_files/figure-html/base-plot-1.png)<!-- -->

# ggplot2


```r
# opts_chunk$set(dev = 'gridSVG::gridsvg')
library(ggplot2)
qplot(Petal.Length, Petal.Width, data=iris, colour=Species)
```

![](Knitr-gridSVG_files/figure-html/ggplot2-plot-1.png)<!-- -->
