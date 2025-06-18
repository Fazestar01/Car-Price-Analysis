# Car Price Analysis
## Team Datalicious: (Jane, Faiza, Kaori and Anita)

**Car Price Analysis Project** is a group hackathon project focussed on the ETL (Extract, Transform, Load) pipeline in Jupyter Notebook and visualisations in Tableau. The Project examines car pricing across range of factor to assess the primary drivers behind car prices. 
# ![Heading picture with title 'carprice analysis](image.png)

## Navigation
* [Data Investigations](https://github.com/Fazestar01/Car-Price-Analysis/blob/main/jupyter_notebooks/car_price_investigations.ipynb)
* [Raw Data](https://github.com/Fazestar01/Car-Price-Analysis/blob/main/data/CarPrice_Assignment.csv)
* [Cleaned Data](https://github.com/Fazestar01/Car-Price-Analysis/blob/main/data/cleanedcardata.csv)
* [Dashboard](https://public.tableau.com/app/profile/kaori.ikarashi/viz/CarPriceAnalysis_17501618237170/Story1?publish=yes)

## Dataset Content
* Data was acquried from a dataset on [Kaggle](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction), the data includes car prices across wide array of variables such as height, weight, brand and more. 


## Business Requirements
* The problem statement on Kaggle defines the business reqirements. 
* The problem statement states that we are assuming the role of a consultant for the automotive company Geely Auto.
* We have been tasked with examining how different factors effect pricing across the US market.


## Hypothesis and how to validate?


### H1: Vehicle size and engine capacity are primary drivers of car pricing

This is an interesting observation, as the first instinct was that surely, the bigger the engine, the higher the price the vehicle was. Our first take was:

> *Larger vehicles with higher engine capacity consistently fall into the higher price range, suggesting that size and performance specs are key pricing factors.*

This was then proven to be contrary to our original belief. As we looked into the data, we wanted to explore further by using scatter plots and trend lines to have more of an in- depth understanding on what factors the pricing of vehicles.

We found examples like the BMW X5 that came 209 litres priced at $41,315 whilst the Buick Century Special has an engine litre of 308 litres priced at $40,960, proving that engine size doesnt equate to a higher priced vehicle. 


We can say the same for the 'curbweight' that we also menioned along with engine size and came to notice that too, curb weight shows a moderate correlation with price, but it’s not a definitive predictor. While heavier vehicles often include more premium features, brand and drivetrain appear to have a stronger influence on pricing.

While engine capacity correlates with car price to some extent, the relationship is not strictly linear. High-end brands or performance-focused models may price higher despite smaller engines, indicating that engine size is a factor, but not the primary driver of price.

 
### H2: Brand Name strongly correlates with car pricing

Naturally, when it comes to brands and vehicles, its safe to say that branding plays a big part in pricing no matter on if it performs well or not.

So, it comes as a no brainer when it comes to the pricing of vehicles. The dashboard provides strong evidence that brand name significantly influences car pricing. Premium brands consistently command higher prices, regardless of technical specifications like engine size or curb weight. This suggests that brand equity, perceived quality, and market positioning are key drivers in pricing strategy.

This insight supports the idea that consumers are willing to pay a premium for brand reputation, which may outweigh purely technical considerations


### H3: Drive wheel (e.g., FWD, RWD, 4WD) is a key differentiator in pricing strategy

Drive wheel configuration shows a noticeable impact on pricing. Vehicles with 4WD and RWD systems tend to be priced higher than FWD models, likely due to performance and handling advantages associated with these drivetrains.

>Drive wheel configuration plays a significant role in car pricing strategy, particularly when aligned with vehicle purpose and performance expectations. For instance, many sports cars adopt front-wheel drive (FWD) or rear-wheel drive (RWD) systems, which optimise handling and speed on smoother roads—much like performance setups in Formula 1 vehicles.
>>In contrast, vehicles like Land Rovers or other SUVs often use four-wheel drive (4WD) to enhance traction and stability across multiple terrains, reflecting a different performance focus.
>>The drivetrain thus not only signals functional capability but also influences perceived value and market positioning, contributing to price variation across categories.

That being said, drive wheel configuration is a key influencer in car pricing, as it reflects performance capability and intended vehicle use. Sports cars often use FWD or RWD systems, emphasizing speed and handling on smooth terrain—similar to race engineering like in Formula 1. On the other hand, 4WD vehicles like Land Rovers are built for versatility and off-road strength, justifying higher prices due to advanced drivetrain design and rugged capability.


## Project Plan 

## 📌 Project Plan

### 1. High-Level Steps Taken

**Angle Used**  
This project investigates the key factors that influence car pricing in the U.S. market, focusing on how technical specifications (like engine size and horsepower), brand identity, and drivetrain configurations shape value. The goal was to generate actionable insights that could support pricing strategy, competitive positioning, or product development for an automotive company entering the market.

**Dataset Selection**  
We selected the [Car Price Prediction dataset on Kaggle](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction) for its wide coverage of useful variables — including brand, engine size, horsepower, body style, and drivetrain type — making it ideal for both statistical testing and visual storytelling.

**Planning & Analysis Flow**
- Defined hypotheses (H1–H4) to guide exploratory work and support business-focused questions.
- Performed descriptive analysis to explore distributions, spot outliers, and assess feature importance.
- Conducted hypothesis testing using parametric (e.g., t-test, ANOVA) and nonparametric tests (e.g., Mann-Whitney U), depending on the distribution of data.
- Built interactive visual dashboards in Tableau to present findings in a clear and engaging format.

**Data Cleaning**
- Removed duplicates and handled missing/null values.
- Standardised column names and ensured data types were consistent across numeric and categorical variables.
- Trimmed text fields and converted numerical values where necessary to support reliable analysis.
- Engineered new features such as `price_per_horsepower` to reflect value-performance metrics.

---

### 2️. Data Management Throughout the Project

| **Step**        | **Action**                                                                                                                                             |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Collection**  | Downloaded CSV file from Kaggle and stored it in a version-controlled GitHub repository for team collaboration.                                       |
| **Processing**  | Used Python (Pandas) in Jupyter Notebook to clean and transform data, including formatting, encoding, and feature engineering.                         |
| **Analysis**    | Performed EDA in both Jupyter and Tableau. Applied statistical tests suited to each variable type and distribution (e.g., t-tests, ANOVA, Wilcoxon).   |
| **Interpretation** | Combined numeric/statistical insights (e.g., p-values) with Tableau dashboards to communicate findings through dynamic charts and annotated stories. |

---

### 3️. Rationale for Research Methodologies

- **Hypothesis-Driven Approach:** We defined practical questions relevant to strategic decisions and tested them with appropriate statistical methods.
- **Parametric + Nonparametric Testing:** Used flexible testing methods (e.g., Mann-Whitney U where normality was not met) to adapt to data structure and reliability needs.
- **Tableau Public for Storytelling:** Enabled the team to create highly interactive and filterable dashboards for accessible, intuitive data exploration.
- **Python for Processing:** All cleaning and transformation were done in Python to ensure transparency, reproducibility, and modular processing.

This structured approach allowed us to move from raw data to business-ready insights in a scalable and replicable way.



## The rationale to map the business requirements to the Data Visualisations (done)

1. #### Identify Key Drivers of Car Price Business Need: 
Understanding which features most influence pricing to support pricing strategy or customer targeting

Viusalisation: 
- Scatter plots of Engine Size vs Price
- Box plots of Drive Wheel vs Price Rationale: These visuals make it easy to see trends and variation across technical specs. Outliers or clusters can suggest relationships worth exploring with statistical testing.

2. ### Compare Brand Positioning in the Market Business Need:
Evaluate how brands are priced in relation to each other to guide competitive analysis or partnership decisions.

Visualisation: 
- Bar charts showing Average Price by Brand
- Box plots showing Price spread within each brand Rationale: Highlights both the average market position and the consistency or variation in pricing within a brand—key for brand strategy.

3. ### Assess Pricing Strategy Based on Drivetrain Configuration Business Need:
Determine how drivetrain (FWD, RWD, 4WD) impacts perceived value or cost to align with customer preferences

Visualisation:
 - Box plots or grouped bar charts of Drive Wheel vs Price Rationale: These plots show how drivetrain types cluster at different price tiers, helping identify if pricing strategies align with drivetrain desirability.

4. ### Monitor Variability in Price Across Technical Specs Business Need:
Understand how variability in engine size, weight, and dimensions affects pricing to spot inconsistent or misaligned pricing.

Visualisation:
- Line graphs or histograms for price distribution Rationale: Helps detect relationships between variables and whether price changes smoothly or erratically with technical attributes.


## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* The dataset contains no sensitive information and thus does not require anonymisation or other ethical steps.

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 


## Development Roadmap and issues faced
* The types of measurements for things such as height, weight etc were not included, to resolve this we asked Copilot what it thought the most reasonable assumption of the measurements are.
* One aspect of data cleaning was overlooked, 'VW' should have been changed to 'Volkswagen' in the Jupyter notebook. This was solved by using the 'groupby' function in Tableau to group VW under Volkswagen. 




## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* Code Institute Learning Management System modules on pandas and tableau
* Microsoft co-pilot aid in code generation
* Chat-GPT for questions regarding dashboarding in Tableau
* [Markdown Guide](https://www.markdownguide.org/)


### Media

- Header image was made using Canva


## Acknowledgements (optional)
* A huge thank you to Mark, Emma, John, Spencer and Niel from Code institute for their hard work in tutoring us! And a thank you to Carlos who showed us how to add a back to the top button on markdown. 

[Back to top](#top)