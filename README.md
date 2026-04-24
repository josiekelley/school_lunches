#  Nutrition and Diversity in Pennsylvania’s Public-School Lunch Menus Scraping menu items from Middle schools and High schools using Nutrislice 🍎 

By Olivia Ngai and Josie Kelley

This study examines the relationship between district-level income and the diversity and nutritional content of middle and high school lunches in Pennsylvania. Lunch menu data for March 2026 was collected from 91 middle and high schools using Nutrislice, a third-party menu platform that provides nutritional information for each item served. District-level income data was obtained from the Commonwealth of Pennsylvania Department of Education reports. Nutrition scores were calculated based on normalized nutritional content, and diversity scores were assigned based on the number of unique food items offered across entrée, vegetable, and fruit categories.

### Findings
Linear regression analysis revealed a weak but statistically significant positive relationship between district-level income and both diversity and nutrition scores. These findings suggest that while income contributes to variation in school lunch quality, it explains only a small portion of the observed differences, indicating that additional factors likely play a larger role.


### How to run the code
- **schools_on_nutrislice.ipynp** Uses Selenium webdriver to look up which schools in Pennsylvania are on Nutrislice.
- **building_API_links.ipynp** Builds custom API links for each school menu.
- **Scraping_nutrislice.ipynp** Scrapes Nutrislice menus for each school using the custom API links
- **School_analysis.ipynp** Analysis of school lunch data is conducted here


### EDA
