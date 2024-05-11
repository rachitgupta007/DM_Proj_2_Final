# DM_Proj_2_Final
# Movie Industry Analysis Project

## Overview
This project is designed to explore the dynamics of the film industry through a detailed analysis of historical box office data. By identifying key characteristics of high-grossing films, such as profitable genres, optimal release timings, and impactful budget allocations, this study aims to offer insights that could influence future film production strategies.

## Abstract
This independent project ventures deep into the complexities of the film industry by scrutinizing historical box office data to unearth patterns and determinants of success in high-grossing films. Central to the study are objectives such as identifying lucrative film genres, pinpointing the most advantageous release timings, and assessing the relationship between budget allocations and revenue outcomes. Additionally, the analysis aims to probe the subtle yet potent roles played by pivotal figures in the film-making process, particularly musical architects, on a film’s financial achievements. By weaving together insights from a variety of data sources, this research not only promises a detailed portrayal of the present cinematic environment but also aims to furnish strategic insights that could inform future film production endeavors. The overarching ambition is to harness this knowledge to forecast and bolster the commercial viability of films, thereby deepening the understanding of market dynamics and consumer predilections within the industry.

## Data Analysis Questions
1. What genres and production methods are most successful in terms of worldwide box office gross?
2. Which months have historically been the most profitable for releasing films?
3. Within what budget range do films tend to achieve the highest box office returns?
4. Which directors and composers have consistently been part of successful films?
5. How do actors' career decisions across genres and collaborations affect their success?
6. Is there a significant difference in film preferences between critics and general audiences?
7. How does consumer spending influence film success? Are there regional variations in film profitability?

## Additional Datasets
- **OpusData Movie Data**: Contains comprehensive details on movie names, budgets, gross earnings, genres, and more.
- **The-Numbers.com Data**: Offers detailed box office data, enhancing the analysis of financial performance across various film attributes.
- **TMDb API**: Provides extensive data about movies and personnel, useful for filling gaps and extending dataset features.
- **IMDb Datasets (title.basics, name.basics, title.akas, title.principals)**: Crucial for analysis of actor careers, movie details, and networking within the industry.
- **Rotten Tomatoes Data (rt.movie_info, rt.reviews)**: Utilized to explore the disparity in movie ratings between critics and audiences.
- **TN Movie Budgets**: Focuses on financial aspects, particularly budgets and their correlation with revenues.
- **Oscars Data File**: Analyzes trends in award-winning films and their characteristics.
- **US Consumer Spending Data**: Examines the economic factors affecting the movie industry's success.

## Methods and Results

### Notebook
The Jupyter notebook, the cornerstone of this analysis, is meticulously structured to encapsulate comprehensive methodologies and findings across several distinct areas:

#### Data Loading and Preparation
This phase involves a meticulous process of data aggregation from various sources, followed by a rigorous data cleansing regimen. The datasets are carefully integrated to form a unified structure, ensuring consistency across data types and formats. This process is critical to prepare the data for advanced analytical techniques, minimizing discrepancies and enhancing the accuracy of subsequent analyses.

#### Descriptive and Inferential Statistics
In this section, we employ a combination of descriptive statistical measures and inferential statistical methods to uncover underlying patterns and trends within the data. This involves an extensive use of visualizations such as histograms, box plots, and scatter plots, which provide intuitive insights into the distribution and relationships between variables. Inferential statistics allow us to make probabilistic conclusions about our data, thereby enabling us to generalize the findings beyond the sample to a broader population of films.

#### Economic Impact Analysis
Here, we explore the correlation between consumer spending behaviors and movie revenues, delving into how economic factors influence cinematic success. This analysis not only assesses direct relationships but also considers external economic indicators and their impact over time. By understanding these relationships, we can predict how shifts in economic conditions could affect future box office performances.

#### Diversity in Cinema Analysis
This segment examines the career trajectories of actors and the impact of diversity on recognition within the Oscars. It involves analyzing patterns of gender and ethnic diversity in award-winning films and correlating these with commercial success and critical acclaim. This analysis is pivotal in understanding the evolving landscape of cinema and the role of inclusivity in shaping the industry.

#### Comparative Analysis
A comparative study of movie ratings by critics versus general audiences is conducted to identify discrepancies in preferences and expectations. This involves statistical tests to quantify the differences and data visualization to illustrate them. Understanding these discrepancies is crucial for filmmakers and studios to tailor their productions to meet diverse audience expectations effectively.

#### Recommendation and Forecasting Systems
The final section is dedicated to constructing predictive models and developing recommendation systems based on historical data. These models are designed to forecast trends and simulate potential future scenarios, providing stakeholders with valuable insights into what factors might contribute to a film's success. The recommendation system uses algorithms to suggest film attributes that align with successful trends, thus aiding in decision-making for future projects.

### Technical Implementations
The analytical processes are implemented using Python in a Jupyter notebook environment, with code organized into modular sections for clarity. External scripts handle repetitive or auxiliary functions to maintain focus on the core logic of the analysis. Libraries such as Pandas for data manipulation, Matplotlib and Seaborn for data visualization, SciPy for statistical tests, and Scikit-learn for machine learning are extensively utilized.

This holistic approach not only enhances the comprehensibility of the analysis but also ensures that the insights derived are grounded in robust statistical evidence and are actionable for strategic decision-making in the film industry.
