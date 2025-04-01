## HFSP workshop 2025 - How can I use this code?

The quickest and easiest way is to use RStudio.

 1. Download and install [R](http://cran.rstudio.com/) for your operating system
 1. Download and install [RStudio](http://www.rstudio.com/products/rstudio/download/) for your operating system
 1. Download a [zip file of this repository](https://github.com/isoverse/2025_hfsp_tum/archive/master.zip) and unpack it in an easy to find directory on your computer
 1. Navigate to the directory and double-click the `project.Rproj` file to start RStudio and load this project.
 1. Install the required libraries used by this app by running the following command in the Console in RStudio: `install.packages(c("devtools", "tidyverse", "isoorbi"))` or by installing them manually in RStudio's Packages manager
 1. Install the latest development version of `isoorbi` by running `devtools::install_github("isoverse/isoorbi", "dev-v1.4")
 1. Double-click on `template.qmd` to open an empty notebook