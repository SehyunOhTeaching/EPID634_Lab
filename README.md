# Laboratory Materials for Data Visualization and Dashboard Course

## 📚 Overview

This repository contains comprehensive laboratory materials for exploratory
data anlaysis, data cleaning, data visualization, and dashboard building. 
All materials include exercises, solutions, and comprehensive projects.

---

## 📖 Detailed Lab Descriptions

### 1. Beginner Data Wrangling

**What**: Foundational data manipulation skills for R beginners  
**Files**:    
- `Lab_Beginner_Data_Wrangling_Exercises.Rmd` - Interactive exercises    
- `Lab_Beginner_Data_Wrangling_Solutions.Rmd` - Complete solutions   

**Coverage**:    
- Loading and viewing data    
- Selecting and renaming columns    
- Filtering rows with conditions    
- Creating new columns (mutate, if_else, case_when)    
- Sorting data    
- Counting and summarizing    
- Grouping operations    
- Reading and writing CSV files      

**Outcome**: Develop fundamental data manipulation skills with hands-on bakery 
and coffee shop examples

### 2. Beginner Data Visualization

**What**: Create professional charts and graphs with ggplot2 
**Files**:    
- `Lab_Beginner_Visualization_Exercises.Rmd` - Interactive exercises   
- `Lab_Beginner_Visualization_Solutions.Rmd` - Complete solutions   

**Coverage**:    
- Bar charts (basic and sorted)    
- Line charts with trends    
- Scatter plots with trend lines    
- Color customization and themes    
- Combining multiple charts (patchwork)    
- Saving visualizations    
- Real-world examples (lemonade stand, pizza shop)      

**Outcome**: Learn essential ggplot2 visualization techniques for effective data communication

### 3. Tidyverse Data Wrangling

**What**: Master data manipulation with dplyr and tidyr  
**Files**:    
- `Lab_Tidyverse_Data_Wrangling.pdf` - Complete manual   
- `Lab_Tidyverse_Exercises.Rmd` - Interactive exercises   
- `Lab_Tidyverse_Solutions.Rmd` - Complete solutions   

**Coverage**:   
- Data import/export   
- Filtering and selecting   
- Creating new variables   
- Grouping and summarizing   
- Joining datasets   
- Reshaping data (pivot)   
- Handling missing values   

**Outcome**: Build complete data analysis pipelines

---

### 4. ggplot2 Visualization

**What**: Create publication-quality graphics  
**Files**:   
- `Lab_ggplot2_Visualization.pdf` - Complete manual   
- `Lab_ggplot2_Exercises.Rmd` - Interactive exercises   
- `Lab_ggplot2_Solutions.Rmd` - Complete solutions   

**Coverage**:   
- Basic plot types (scatter, line, bar, histogram)   
- Aesthetic mappings   
- Faceting   
- Themes and customization   
- Scales and coordinates   
- Advanced plots (box, violin, heatmap)   

**Outcome**: Create professional multi-panel dashboards

---

### 5. Dashboard Building with R

**What**: Build interactive web dashboards     
**Files**:   
- `Lab_Dashboard_Building_Exercises.Rmd` - Comprehensive exercises   
- `Lab_Dashboard_Building_Solutions.Rmd` - Complete solutions   
- `Lab_Dashboard_Building_Solution_ver1.Rmd` - Dashboard version 1      
- `Lab_Dashboard_Building_Solution_ver2.Rmd` - Dashboard version 2      
- `Lab_Dashboard_Building_Solution_ver3.Rmd` - Dashboard version 3      

**Coverage**:   
- flexdashboard framework   
- Shiny reactive programming   
- Input widgets and controls   
- Value boxes and gauges   
- Interactive plotly charts   
- Data tables   
- Deployment   

**Outcome**: Deploy production-ready dashboards



---

## 💻 Quick Start

### Installation

```r
# Install all packages at once
install.packages(c(
  # Core
  "tidyverse", "lubridate", "scales",
  
  # Visualization
  "plotly", "patchwork", "gganimate",
  
  # Dashboard
  "shiny", "flexdashboard", "DT",
  
  # Advanced Viz
  "igraph", "networkD3", "ggridges", "treemap",
  
  # GIS
  "sf", "tmap", "leaflet", "terra"
))
```

### Getting Started

```r
# 1. Clone or download materials
# 2. Open RStudio
# 3. Choose your learning track
# 4. Open the first .Rmd file
# 5. Work through exercises
# 6. Check solutions
# 7. Complete projects
```

**How to clone/copy the material:**   
In the terminal, under the directory you want to copy this GitHub repository,
run this code:

```bash
git clone https://github.com/SehyunOhTeaching/EPID634_Lab.git
```
All the content in this repository will be copied and available in your computer.


---


## 📞 Support Resources

### Tips for Success:
1. **Work incrementally** - Complete one section before moving to the next
2. **Experiment** - Try variations of the code examples
3. **Use comments** - Document your code as you work
4. **Check output** - Always verify your results make sense
5. **Ask questions** - Use the discussion forums or office hours
6. **Practice** - The comprehensive exercises integrate all skills

### External Resources:
- [Tidyverse documentation](https://www.tidyverse.org/)
- [ggplot2 documentation](https://ggplot2.tidyverse.org/)
- [R for Data Science (free online)](https://r4ds.had.co.nz/)
- [RStudio cheat sheets](https://www.rstudio.com/resources/cheatsheets/)
- [Shiny Cheat Sheet](https://shiny.rstudio.com/images/shiny-cheatsheet.pdf)
- [ggplot2 Cheat Sheet](https://github.com/rstudio/cheatsheets/blob/main/data-visualization.pdf)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/r)
- [Shiny Gallery](https://shiny.rstudio.com/gallery/)
- [R Graph Gallery](https://r-graph-gallery.com/)
- [Leaflet for R Gallery](https://rstudio.github.io/leaflet/)

### Getting Help:
1. Check the relevant solution file
2. Review package documentation (`?function_name`)
3. Search error messages on Stack Overflow
4. Post in course discussion forum
5. Contact instructor

---

**Happy Learning!** 🚀📊🗺️
