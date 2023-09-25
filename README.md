# Applied-Statstistics
There is a repository with my projects written in R, where I showcase my knowledge of applied statistics. These projects demonstrates my ability to handle various data types, perform in-depth analyses, and choose models fitting the data. My experience covers regression and correlation analysis, analysis of variance and non-parametric methods. Furthermore, it demonstrates my proficiency in utilizing statistical software to effectively apply these methods to real-world problems.

## Projects
- [Basic analysis and tests](#Basic-analysis-and-tests)
- [Regression](#Regression)
- [GDP analysis](#GDP-analysis)

`(!!!) All projects are commented in Czech.`

## Basic analysis and tests
This project focuses on the **analysis of demographic data** provided by [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/DEMO_R_PJANAGGR3/default/table?lang=en). The dataset contains information about the population count in regions of Albania, categorized by age group and gender, following the administrative division of NUTS 3 regions.

The project begins with a brief description of the dataset, outlining its key characteristics. Essential statistical measures are determined to best characterize the dataset. Data is effectively represented using selected graphs for visualization. Three pairs of hypotheses are developed based on the characteristics of the data. These hypotheses lead to the **application of three distinct statistical tests**. Each chosen statistical test is accompanied by a clear explanation of why it was selected, providing a rationale for its application in the specific analytical context.The hypotheses are tested, and the **results are interpreted**, both mathematically and practically. A **contingency table** is constructed, presenting population counts by gender and NUTS 3 regions. This table is thoroughly interpreted, leading to hypotheses about its properties. An appropriate statistical test is performed to assess these hypotheses, and the results are comprehensively interpreted.

This project showcases the application of statistical analysis to real-world datasets, providing valuable insights into population dynamics and distribution within the specified region.

## Regression
This project aims to explore the **relationship between a specific variable and various regressors** from the assigned dataset. The dataset can be found in R in the [Sleuth2](https://cran.r-project.org/web/packages/Sleuth2/index.html) library and contains one explained variable and several other possible regressors. The topic is **Proportion of unhatched frog eggs**.

The project begins with a fundamental exploration of the dataset. I describe the data's key attributes, use essential statistical measures to characterize it effectively and represent the data visually using suitable graphs. 

Then I select a numeric variable as a regressor. Using a **regression model** (linear, quadratic regression, etc.), explore the dependence of the explained variable on this regressor and interpret the estimated regression coefficients. Additionally, I assess the model's quality, evaluating how well the selected regressor explains the behavior of the explained variable. Another layer of analysis involves selecting a categorical variable as a regressor. Through analysis of variance models, I explore how the explained variable depends on this categorical regressor. We provide practical interpretations of the regression coefficients and evaluate the model's quality too. To further my understanding, I consider a more complex multiple regression model. This model includes both regressors from previous tasks, incorporating their interaction. I estimate model parameters, assess their significance, and graphically display the regression dependence. We extend our analysis by exploring a model that includes the two previous regressors and at least one other from the dataset. Our goal is to **identify the significant regressors** and **eliminate the insignificant components**. Using the appropriate tools, we aim to identify a final model that effectively explains the behaviour of the variable of interest while avoiding irrelevant elements. Finally, I subject the final model to rigorous testing to **validate the assumptions** underlying the methods employed.

This project showcases the application of advanced statistical techniques to real-world data, with a focus on regression analysis. It aims to uncover insights into the relationships between the response variable and various regressors, offering valuable information for modeling and prediction.

## GDP analysis
This project focuses on the **gross domestic product (GDP)** of European countries in year 2022 provided by [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/NAMA_10_GDP/default/table?lang=en). There are several options for calculating GDP, we will be interested in calculating it in market prices and in terms of millions of euros.

To begin with, I **presented the distribution of GDP** and its numerical characteristics along with graphical representations. This allowed for a clear visual understanding of how GDP is distributed and its key statistical features. Then, I carefully selected four relevant variables from external sources, such as Eurostat databases, to serve as regressors. These regressors describe economic, demographic, and geographic factors. At least one of these variables was numeric, and one was categorical. I examined the **relationships between these regressors and GDP** and presented their important characteristics numerically and through graphical representations. Using appropriate statistical tests, I explored the dependencies between these regressors. 

Subsequently, I delved into linear regression analysis and its variants to examine the relationship between GDP and all the selected regressors. The interpretation of regression coefficients, the evaluation of model quality, and the identification of outliers and multicollinearity were key aspects of this analysis. Furthermore, I rigorously **tested the assumptions** of the model, proposing and implementing methods to address any deviations from these assumptions. Lastly, I identify and improve the final submodel, ensuring that it **effectively explained GDP behavior** while **eliminating insignificant components**. The practical interpretation of these results contributed to an understanding of the factors influencing GDP.

In summary, this project allowed me to delve into the factors influencing a country's GDP, providing valuable insights into its dynamics. By carefully selecting and analyzing relevant variables, I gained a deeper understanding of the complex relationships driving economic outcomes.


`Copyright (c) Dmytro Borovko 2023`