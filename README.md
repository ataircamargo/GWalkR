[English](README.md) | [中文](./docs/README.zh.md)

# GWalkR: Your One-Stop R Package for Exploratory Data Analysis with Visualization

![](https://img.shields.io/github/actions/workflow/status/kanaries/GWalkR/web-app-build.yml?style=flat-square)
![](https://img.shields.io/github/license/kanaries/GWalkR?style=flat-square)
[![](https://img.shields.io/badge/twitter-kanaries_data-03A9F4?style=flat-square&logo=twitter)](https://twitter.com/kanaries_data)
[![](https://img.shields.io/discord/987366424634884096?color=%237289da&label=Discord&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/WWHraZ8SeV)

Start Exploratory Data Analysis (EDA) in R with a Single Line of Code!
[GWalkR](https://github.com/Kanaries/GWalkR) is an interactive Exploratory Data Analysis (EDA) Tool in R.
It integrates the htmlwidgets with [Graphic Walker](https://github.com/Kanaries/graphic-walker).
It can can simplify your R data analysis and data visualization workflow, by turning your data frame into a Tableau-style User Interface for visual exploration.

<img width="1437" alt="image" src="https://github.com/Bruceshark/GWalkR/assets/33870780/26967dda-57c0-4abd-823c-63037c8f5168">

> If you prefer using Python, you can check out [PyGWalker](https://github.com/Kanaries/pygwalker)!

## Getting Started

### Setup GWalkR

#### Through Package Archive File (.tar.gz)

First, download the package archive file `GWalkR_0.1.0.tar.gz` from [this link](https://kanaries-app.s3.ap-northeast-1.amazonaws.com/oss/gwakr/GWalkR_0.1.0.tar.gz).
Open R Studio, click "Install" in the "Packages" window, and select "Package Archive File (.tgz; .tar.gz)" in the "Install from". Then, select the archive in your file system and click "Install".

#### Through Running R Script

Alternatively, you can run the following R code in your script to download without a lot of clicking.

```R
url <- "https://kanaries-app.s3.ap-northeast-1.amazonaws.com/oss/gwakr/GWalkR_0.1.0.tar.gz"
destfile <- "GWalkR_0.1.0.tar.gz"
download.file(url, destfile)
install.packages(destfile, repos = NULL, type = "source")
```

#### Through CRAN

To be supported soon. Stay tuned!


### Start Your Data Exploration in a Single Line of Code

```R
library(GWalkR)
data(iris)
gwalkr(iris)
```

<img width="1437" alt="image" src="https://github.com/Bruceshark/GWalkR/assets/33870780/718d8ff6-4ad5-492d-9afb-c4ed67573f51">

