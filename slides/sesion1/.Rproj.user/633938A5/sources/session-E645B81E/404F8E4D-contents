# Use pacman to check whether packages are installed, if not load
if (!require("pacman")) install.packages("pacman")
library(pacman)

pacman::p_unload("all")

pacman::p_load(
  here, 
  tidyverse, 
  fontawesome, 
  devtools, 
  quarto, 
  gt, 
  gtExtras, 
  gtsummary
)

install.packages("devtools")
devtools::install_github("gadenbuie/countdown")