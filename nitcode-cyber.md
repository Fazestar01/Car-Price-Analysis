![Banner image stating 'Car IMAGE'] !(image-1.png) 

# Team Datatlicious [Anita, Faiza, Jane, Kaori]


This car price analysis explores key factors influencing vehicle pricing in the U.S. market using an ETL pipeline.
The dataset contains specifications of various car models, including brand, dimensions (length, width, height), engine size, curb weight, drive wheel type, fuel type, and price. The data was sourced from a public Kaggle dataset, allowing manageable analysis for business insights.

 Data was extracted, transformed for consistency, and loaded for analysis. Tableau visualisations reveal insights into variable relationships, helping Geely Auto understand pricing dynamics and inform strategic decisions for US market.


## Navigation:
Data Investigations
Raw Data
Cleaned Data
Dashboard


 # Dataset Content:
The dataset contains information on the relationship between car attributes (car_ID, symbolizing, CarName, fuel type, aspiration, number of doors, car body, drive wheel, engine location, and wheelbase) and other variables that impact car prices. It can be downloaded from the link below.

Data comes from this [kaggle dataset](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction/data).

# Business Requirements:
An automobile company aims to enter the US market and compete with local and European manufacturer wish to understand the factors on which the pricing of cars depends on what factors.

# Hypotheses and how to validate?:
## Hypothesis 1: 
Vehicle/Engine Size Hypothesis

Question: Are vehicle dimensions and engine size primary drivers of car pricing?

Dashboard Analysis:

Scatter plots compare price with car length, width, height, and engine size.

Trendlines are included, showing a positive correlation—especially with length, width, and engine size.

Curb weight is explored via a horizontal bar chart, comparing average curb weight and average price by brand.

Conclusion: Hypothesis Supported

Larger cars with bigger engines tend to be priced higher.

Strong correlation observed with engine size and car length/width.

Minor correlation with height; not a strong price predictor.



## Hypothesis 2:
 Brand Name Hypothesis
Question: Does brand name strongly affect car pricing?

Dashboard Analysis:

Bar chart displays the median price by brand—Jaguar, Buick, and Porsche lead in price.

Boxplot highlights brand-level pricing tiers with clear separation between economy and luxury segments.

Conclusion: Hypothesis Strongly Supported

Luxury brands (Jaguar, Porsche, BMW) command significantly higher prices.

Clear pricing stratification by brand demonstrates brand equity's impact on pricing strategy.


## Hypothesis 3: Drivewheel Hypothesis
Question: Is drive wheel type a key differentiator in pricing?

Dashboard Analysis:

Boxplot shows price distributions for front-wheel (fwd), rear-wheel (rwd), and four-wheel (4wd) drive types.

Rwd cars show higher median and upper-quartile prices, including luxury entries like BMW X4 and Buicks.

4wd and fwd are generally lower priced, with overlapping interquartile ranges.

Conclusion: Hypothesis Supported

Rwd vehicles tend to be priced higher, suggesting positioning in more premium/luxury segments.

Drive type contributes to price differentiation but is less dominant than brand or engine size.

# The rationale to map the business requirements to the Data Visualisation
Translate abstract business questions into measurable, visual insights.

Provide decision-makers with intuitive tools to explore pricing patterns.

Validate or reject key hypotheses through clear, visual evidence.

Prioritize data storytelling by aligning each visualization with the business impact it reveals.



# Project Plan 

* Discuss and consider chosen research methodologies and data project 

* Extract Transform load pipeline with data cleaning in Jupyter notebooks.
* Visualisations: pie chart, histogram, bar chart and scatter plot.



# Analysis Technologies used:
* Visual Studio Code
* Python 
* Jupyter notebook
* Microsoft Co-Pilot 



# Ethical considerations:
The car price dataset contained no personal information, ensuring privacy compliance. Bias was minimized by equally analysing all car brands and attributes. 
Ethical practices followed included fair representation, avoidance of brand favoritism, and adherence to GDPR standards.


# Dashboard Design
The dashboards were designed to communicate insights through clean layouts, interactivity, and intuitive visuals. Tooltips, filters, and clear labels make data accessible to technical and non-technical users alike. Each dashboard page focuses on a specific hypothesis, using appropriate chart types to validate trends and relationships in the dataset.

Insert a table 



Communication Strategy:

Complex data insights were translated into visually compelling and interactive dashboards. For technical audiences, detailed axis labels and tooltips provided context. For non-technical users, clear titles, color-coded data points, and filters helped simplify interpretation without sacrificing depth.



#Project is managed over 6 stages, supported by GitHub project board (https://github.com/users/8osco/projects/6/views/1):

1) Project setup with new GitHub repo for storage and version control, VScode as IDE, and access to Kaggle for dataset
2) Data extract and familiarisation
3) Data cleaning and preparation
4) Data quality check
5) Data analysis and visualisation
6) README documentation
7) Git Kansan Group Tracking Board

## Unfixed Bugs:
A struggle we encountered was getting collaborative works pushed to Github, this was solved using following Data Coach's guidance and Microsoft co-pilot. 

## Main Data Analysis Libraries
# Data Analysis Libraries:
* Pandas 
* Numpy 
* Tableau

# Credits:
* [The Code Institute](https://codeinstitute.net/) Learning Management System modules, SME, data coach, PDBA sessions.
* ChatGPT and Microsoft Copilot for code clarification and creation.
* The image at the top of this README file was sourced from Kaggle.
* Visual Studio Code
* [Markdown guide](https://www.markdownguide.org/cheat-sheet/) was used to format the README.md and markdown cells in the Jupyter notebooks.

## Unfixed Bugs
 we.........

# Media:
Header image for this document was made using [Canva](https://         ).

# Acknowledgements: 
A special thanks to Datalicious Group, Apr NH 2025 data analytics cohort and all coaches and tutors. The support received and discussions have been invaluable.












# Acknowledgements: 
A special thanks to Datalicious Group, Apr NH 2025 data analytics cohort and all coaches. The support received and discussions have been invaluable.




