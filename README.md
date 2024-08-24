# World-Socio-Economic
# Global Data Visualizations Dashboard

This project presents a Power BI dashboard that visualizes data from different regions and countries. The dashboard helps to identify key trends and insights related to population, economy, gender demographics, employment, and technology adoption across the globe.

## Dashboard Structure

The dashboard is split into three navigable pages:

1. **Home Page:** 
   - The main page with navigation buttons to access the Region and Country pages.

2. **Region Page:**
   - Focuses on data related to global regions, allowing for comparisons across various regions.

3. **Country Page:**
   - Provides detailed data visualizations at the country level, highlighting differences across nations.

## Key Visualizations and Questions Answered

### Region Page

- **Surface Area & Population:**
  - **Questions Answered:**
    - What is the total surface area (in km²) of different regions?
    - How does the population size vary across global regions in 2017?
    - What percentage of the population in various regions lives in urban areas?

- **Economic Structure:**
  - **Questions Answered:**
    - How do different regions compare in their GDP per capita (current US$)?
    - How do regions differ in the percentage of their labor force employed in agriculture, industry, and services?

- **International Trade:**
  - **Questions Answered:**
    - What is the trade balance (imports vs. exports) for various regions?

- **Gender and Demographics:**
  - **Questions Answered:**
    - Which regions have the highest or lowest sex ratios (males per 100 females)?
    - How do regions differ in terms of seats held by women in national parliaments?

- **Unemployment Rates:**
  - **Questions Answered:**
    - What are the unemployment rates (% of the labor force) across different regions?

### Country Page

- **Population Characteristics:**
  - **Questions Answered:**
    - How does population growth vary between countries?
    - What is the population density (people per km²) of different countries?

- **Economic Performance:**
  - **Questions Answered:**
    - What is the GDP per capita (current US$) in various countries?
    - How does the GDP growth rate compare across countries?

- **Technology and Internet Usage:**
  - **Questions Answered:**
    - What percentage of the population in each country uses the internet?

- **Gender and Politics:**
  - **Questions Answered:**
    - What percentage of parliamentary seats in each country are held by women?

- **Employment Distribution:**
  - **Questions Answered:**
    - How do employment distributions vary across countries in agriculture, industry, and services?

### Combined Insights

- **Global Trade and Economic Comparisons:** 
  - How do regions and countries differ in their trade volumes and economic structures?

- **Population Trends:**
  - What are the global trends in population growth, density, and urbanization across regions and countries?

- **Gender Equality:**
  - How do different regions and countries compare in terms of gender equality in politics and population demographics?

- **Technological Adoption:**
  - Which regions and countries are leading in internet usage, and how does this relate to their population and economic factors?

## Technology Stack

- **Power BI:** Used for creating interactive dashboards and data visualizations.
- **Dataset Sources:** Data sourced from publicly available datasets, including global statistics related to population, economy, gender demographics, employment, and technology.


**Insights about the Region Page**

## Top Section: Key Metrics(Card Structure)

### Surface Area (km²)
- **Description:** Displays the total surface area across various regions.
- **Metric:** The surface area is shown in millions (e.g., 134 million km²).
- **Insight:** Provides an overview of how the physical size of regions compares globally.

### GDP per Capita (Current US$)
- **Description:** Shows the GDP per capita, indicating the average income of the population.
- **Metric:** The total GDP per capita is displayed in US dollars (e.g., 3.27M US$).
- **Insight:** Offers a quick glance at economic performance on a per-person basis across different regions.

### Population in Thousands (2017)
- **Description:** Displays the total population of the world or specific regions.
- **Metric:** Population is provided in thousands (e.g., 8 million people).
- **Insight:** Highlights population distribution across regions, helping understand how population size impacts resources and policy decisions.

### Urban Population (Percentage of Total Population)
- **Description:** Displays the percentage of the population living in urban areas.
- **Metric:** Shown as a percentage (e.g., 59.51%).
- **Insight:** Helps to understand the level of urbanization in different regions, aiding insights into economic development and infrastructure needs.

### Country and Region Filters
- **Description:** Drop-down filters allow the user to refine the data visualizations by specific countries or regions.
- **Metric:** Dynamic filtering based on user-selected countries or regions.
- **Insight:** Facilitates a focused analysis on a specific geographic area of interest.

---

## Charts: Region-Level Visualizations

### Economy by Region: Agriculture vs. Industry vs. Services (Area Chart)
- **Description:** A Area chart comparing the contribution of the agriculture, industry, and services sectors to the economy across different regions.
- **Metric:** Measured as a percentage of Gross Value Added (GVA).
- **Insight:** Shows trends in how economies are structured, with variations across regions emphasizing whether a region is more agrarian, industrialized, or service-driven.

### Bottom 10 Sum of Sex Ratio by Region (Donut Chart)
- **Description:** A Donut chart displaying the regions with the lowest male-to-female ratios in 2017.
- **Metric:** Male-to-female ratio per 100 females.
- **Insight:** Helps to identify regions with significant gender imbalances, useful for analyzing societal trends and policy needs.

### International Trade: Imports vs. Exports (Line Plot)
- **Description:** A Line plot comparing the volume of imports and exports across regions.
- **Metric:** Measured in million US dollars.
- **Insight:** Provides an understanding of trade imbalances and economic relationships between regions, showing which regions are net importers or exporters.

### Top 10 Sum of Sex Ratio by Region (Donut Chart)
- **Description:** A Donut chart showing the regions with the highest male-to-female ratios in 2017.
- **Metric:** Male-to-female ratio per 100 females.
- **Insight:** Useful for exploring regions with more significant gender disparities, indicating areas that may have unique social or cultural structures.

### Surface Area by Region (Tree Map)
- **Description:** A tree map visualizing the surface area of different regions.
- **Metric:** Surface area in km².
- **Insight:** Provides a visual comparison of the size of regions, showing which regions dominate in terms of landmass, such as Northern America and Eastern Asia.

### Unemployment by Region (Funnel Chart)
- **Description:** A horizontal Funnel chart comparing unemployment rates across different regions.
- **Metric:** Percentage of the labor force that is unemployed.
- **Insight:** Helps to visualize which regions are facing higher levels of unemployment, important for economic and policy planning.

---

## Charts: Country-Level Visualizations

### Population Growth Rate (Avg Annual %, KPI Card)
- **Description:** A KPI card displaying the average annual population growth rate.
- **Metric:** Shown as a percentage ranging from 0% to 599%.
- **Insight:** Allows for the comparison of population growth trends across countries, indicating where populations are growing fastest.

### Population Density (per km², 2017, KPI Card)
- **Description:** A KPI card showing the population density in people per square kilometer.
- **Metric:** Scaled from 0 to approximately 212,000 people per km².
- **Insight:** Highlights the population concentration across countries, useful for understanding urbanization and resource allocation.

### Sex Ratio (Males per 100 Females, 2017, KPI Card)
- **Description:** A KPI card that presents the male-to-female ratio in various countries.
- **Metric:** Ratio displayed between 23.14 and 46.29 males per 100 females.
- **Insight:** Reveals gender demographic trends, which can be crucial for social policy and gender equality initiatives.

### Seats Held by Women in National Parliaments (%)
- **Description:** A KPI card illustrating the percentage of parliamentary seats held by women.
- **Metric:** Displayed as a percentage with a maximum of around 8.18%.
- **Insight:** Shows the level of female political representation across countries, a key indicator of gender equality.

### GDP per Capita by Country (Regional Chart)
- **Description:** A map showing countries by their GDP per capita, with larger blue bubbles indicating higher GDP per capita.
- **Metric:** GDP per capita in current US dollars.
- **Insight:** Visualizes economic wealth distribution across countries, providing a global perspective on income inequality.

### Internet Usage and Population Density by Country (Bar Chart)
- **Description:** A horizontal bar chart comparing internet usage (per 100 inhabitants) and population density (people per km²).
- **Metric:** Internet usage percentage and population density.
- **Insight:** Provides a dual comparison of technological adoption and population concentration, showing which countries are more connected.

### Employment by Sector (Pie Chart)
- **Description:** A pie chart that illustrates the distribution of employment across the agriculture, industry, and services sectors.
- **Metric:** Shown as a percentage of total employment.
- **Insight:** Helps to identify the primary sectors that drive employment in different countries.

### GDP and GDP Growth Rate by Country (Line Chart)
- **Description:** A line chart comparing GDP and annual GDP growth rate across countries.
- **Metric:** GDP in million US dollars and growth rate as a percentage.
- **Insight:** Provides an overview of economic performance and growth trends, highlighting which countries are experiencing economic expansion or contraction.

### Employment by Sector (Line Chart)
- **Description:** Similar to the pie chart, this line chart compares employment percentages across sectors (agriculture, industry, and services) by country.
- **Metric:** Employment distribution as a percentage.
- **Insight:** Shows how employment structures vary across countries, indicating economic diversification.

---

## Summary

This dashboard provides comprehensive visual insights into global and country-level metrics, allowing for comparisons across different regions and countries. The combination of key performance indicators (KPIs), line charts, pie charts, bar charts, scatter plots, and maps helps to explore economic performance, population trends, gender demographics, and employment distribution across the globe.

