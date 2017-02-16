# BC Housing Data Challenge



## Running the app

To run the app on your machine, make sure you have [R](https://cran.r-project.org/) installed, then from your terminal:

```shell
git clone https://github.com/cpsievert/bcviz
cd bcviz
make
```

Alternatively, if you don't need/want to clone the github repo, then from your R console:

```r
if (!require(devtools)) install.packages("devtools")
devtools::install_github("cpsievert/bcviz")
bcviz::launch()
```


**Note for Linux users:**

This app depends on the R package **sf**, which has a number of system requirements. You may need to replicate some of the `before_install:` recipes in its [.travis.yml file](https://github.com/edzer/sfr/blob/master/.travis.yml) to successfully install it.
