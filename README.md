# Self-Learning including start 
## Full process with a new project 
- use r studio to set up a new project(good for the file locations)
- create several folders under new project including `data/` & `r transcript/` & `result/` & `r markdown/`(optional) to make the structure neat and readable
- add the documents under our file in the finder app (loading our data)
  
- Create several folders under the new project to keep things organized:
  - `data/`: store raw and cleaned datasets
  - `scripts/`: save R scripts
  - `results/`: store output files, such as plots or summaries
  - `notebooks/` or `rmarkdown/`: for `.Rmd` or `.qmd` reports (optional)


## Technique skills
- install the packages if we check there has no package
- Install the required packages (if not already installed), using the following pattern in R:

```r
if (!require("package_name")) {
  install.packages("package_name")
  library(package_name)
}
```
### some package might be used
- Tidyverse & readxl & readr(depends)
- 

## Clean Data
- the most common package is `tidyverse`: for data manipulation and visualization
- identity and fix the dirty data
  - 1. name and meaning for each variable and total numbers in the data
    2. multiple sheets read each carefully then read in r as csv.
    3. what is our study goal and choose the main sheet then merge like left joint to make sheet complete then save
  - when doing the merge: find any common variable which is main sheet and which is additional sheet
  - any missing value & outlier & numerical or character and any repeat value
  - Detailed process for handling missing value  [here](./missingvalue/README.md).
## EDA

## 🗺 GIS Learning (New!)

I've started exploring GIS (Geographic Information Systems) tools in R.  
You can check out more details [here](./gis/README.md).


## goal 
