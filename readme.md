# seegSDM
## Streamlined functions for species distribution modelling in the [seeg research group][1].

This package contains (or at least will contain) a set of streamlined functions to fit species distribution models. The current focus is on the ensemble BRT approaches used in the recent [Bhatt et al. dengue paper][2]


### Installing and loading the package

To install the package from gihub you first need to install and load Hadley Wickham's [devtools package][3], like this:


```r
install.packages('devtools')
library(devtools)
```

```seegSDM``` currently depends on version 2.1-0.4 or later of the ```gbm``` R package.
This version isn't on CRAN yet, so you'll need to install it from github first.

```r
install_github('pdmetcalfe/gbm')
```

Now we can use ```install_github``` to install ```seegSDM```

```r
install_github('SEEG-Oxford/seegSDM')
```

and load the package and you're ready to go

```r
library(seegSDM)
```

### Reporting bugs

You can report bugs, issues and suggestions for extra functions using the issues button on the right hand side of this page.


### Tutorial

There is the beginnings of a tutorial/example workflow for the package [here](https://rawgithub.com/SEEG-Oxford/seegSDM/master/seegSDM_tutorial.html)


[1]: http://simonhay.zoo.ox.ac.uk/staff.php
[2]: http://dx.doi.org/10.1038/nature12060
[3]: http://cran.r-project.org/web/packages/devtools/index.html

