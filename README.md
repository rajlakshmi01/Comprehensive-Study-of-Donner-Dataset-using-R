
## Dataset Overview
The Donner Party (sometimes called the Donner–Reed Party) was a group of American pioneers 
who migrated to California in a wagon train from the Midwest. Delayed by a multitude of mishaps, 
they spent the winter of 1846–1847 snowbound in the Sierra Nevada mountain range. Some of the
migrants resorted to cannibalism to survive, eating the bodies of those who had succumbed to 
starvation, sickness and extreme cold. Of the 87 members of the party, 48 survived the ordeal.
Historians have described the episode as one of the most fascinating tragedies in California 
history, and in the entire record of American westward migration.

## Required Packages

Ensure you have the following R packages installed:

- `dplyr`
- `tidyr`
- `magrittr`
- `knitr`
- `ggplot2`
- `ggpubr`
- `ggsci`
- `vcd`
- `vcdExtra`

## Assignment Tasks

### P1: Donner Data Exploratory Analysis
Perform a basic analysis of the Donner data frame (`vcdExtra::Donner`). Answer the following questions and justify your answers:
- How many members were there in the named families?
- What was the ratio of men to women?
- How many children below 18 years of age were there?
- What was the most common first name for the females?
- State and answer at least three of your own questions.

### P2: Data Preparation - Totaling the Survivors
Using `dplyr`, calculate the total number of survivors in each family and create a data frame including the percentage of family members that survived.

### P3: Pie Chart of the Donner Survivors
Create a pie chart using the `ggpubr` package. Include the number of survivors per family as labels in the pie slices, a meaningful title, and a legend to the right. Use the "jco" color palette.

### P4: Data Preparation for a Bar Chart of the Survivors
Create a 2x2 data frame summarizing the survivor data. One column should be a factor with two levels (died and survived), and the other should be a quantitative variable with the corresponding count for each level.

### P5: Bar Chart of the Survivors
Visualize the survivor data using `ggbarplot()` from the `ggpubr` package. Include a title, axis labels, and choose colors from the "jco" palette.

### P6: Age of the Donner Party (Bar Chart)
Create a bar chart plotting age (vertical axis) vs names of individuals (horizontal axis). Use a random sample of 20 records, color bars based on survival status, and improve axis labels and titles.

### P7: Age of the Donner Party (Bar Chart)
Using the same sample of data from Problem 6, create a similar bar chart with minor changes using the `ggpubr` package.

### P8: Percentage of Survivors by Family (Dot Chart)
Plot the percentage of survivors by family using a dot chart. Arrange families by percentage from largest to smallest, color the dots, and include the percentage in the dot.

### P9: Z-score of Survivors by Families (Dot Chart)
Calculate the z-scores of survivors for each family and plot them. Mark z-scores by color (negative and positive), arrange from negative to positive, and include the z-score in the dot.

### P10: Survivors by Families (Cleveland Plot)
Plot the total number of survivor z-scores against the family name in a Cleveland plot. Arrange from most to fewest survivors, color the names the same as the dots, and distinguish between low and high z-scores.

## Important References

- [Plot One Variable: Frequency Graph Density Distribution and More - STHDA](http://www.sthda.com)
- [Bar Plots and Modern Alternatives - STHDA](http://www.sthda.com)
- [Function reference • ggplot2 (tidyverse.org)](https://ggplot2.tidyverse.org)


This `README.md` file provides a comprehensive overview of the assignment, instructions, required packages, tasks, and important references. You can upload this file to your GitHub repository along with your completed assignment.
