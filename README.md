## Contents

This website contains the short course "Co-data learning: the group-regularized ridge and elastic net”

## Preparation

Please install the packages <code>GRridge</code>:

```markdown
source("https://bioconductor.org/biocLite.R")
biocLite("BiocInstaller") # if it asks to update packages, type n
biocLite("BiocGenerics") # if it asks to update packages, type n
install.packages(c("devtools", "foreach", "curl", "Matrix"))
library(devtools)
install_github("markvdwiel/GRridge")
```

and <code>gren</code>:

```markdown
library(devtools)
install_version("Rcpp", version = "0.12.14", repos = "http://cran.us.r-project.org")
# R might have to restart when installing Rcpp
library(devtools)
install.packages("plyr")
install_github("magnusmunch/gren") # if it asks to install Rtools, accept 
# you might have to run the previous line again after installation of Rtools
```

If you encounter any problems, please don't hesitate to contact m.munch@vumc.nl or mark.vdwiel@vumc.nl

## Data
The data for the <code>GRridge</code> part of the practical are included in the package

The data files for the <code>gren</code> part of the practical are found here:

[Cervical cancer data](https://github.com/magnusmunch/co-data_learning/raw/master/gren_data_mir_cervical.Rdata)

[Colorectal cancer data](https://github.com/magnusmunch/co-data_learning/raw/master/gren_data_mir_colon.Rdata)

[Fitted models cervical cancer data](https://github.com/magnusmunch/co-data_learning/raw/master/gren_models_mir_cervical.Rdata)

[Fitted models colorectal cancer data](https://github.com/magnusmunch/co-data_learning/raw/master/gren_models_mir_colon.Rdata)

## Practicals including Exercises

The practicals are found here:

[GRridge](https://rawgit.com/magnusmunch/co-data_learning/master/GRridgeCourse.pdf)

[gren](https://rawgit.com/magnusmunch/co-data_learning/master/gren_practical.html)

## Slides

Slides on Methodology:

[Co-Data learning with empirical Bayes: GRridge and gren](https://rawgit.com/magnusmunch/co-data_learning/master/EBprediction_VdWielMunch.pdf)

[GRridge extensions](https://rawgit.com/magnusmunch/co-data_learning/master/GRridgeExtensions.pdf)

