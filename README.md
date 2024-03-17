# NETFLIX Case Study

## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Business Insights](#business-insights)
- [Recommendations](#recommendations)

### Project Overview
This data analysis project aims to provide insights that could help **NETFLIX** to grow its business in different countries. By analyzing various aspects of the **NETFLIX** data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

![image](https://github.com/Shivam7370/Netflix_Case_Study/assets/92902294/e73e096d-24f4-4024-b98f-135cea4b965a)


### Data Sources
- There are so many datasets under the topic of Netflix analysis. From that, we have selected a dataset "Netflix Movies and TV shows" based on the fact that more the rows the more data we can infer. This dataset consists of TV shows and movies available on Netflix as of 2020. This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine.
- To download the Netflix Movies and TV Shows dataset, [Click Here](https://drive.google.com/file/d/1cLUeqYIovYs2BfQzcDFaFw6DAZraszvi/view?usp=sharing)

### Tools Used
Jupyter Notebook [To install Jupyter Notebook follow these steps](https://jupyter.org/install)
**Note: You must have installed python on your system.**

### Exploratory Data Analysis
Performed EDA using Python to help Netflix in deciding, which type of
Shows/Movies to produce.

### Data Analysis
Include some interesting code/features worked with
```Jupyter Notebook
df["country"].replace(np.NaN, "Unknown", inplace=True)
```

### Business Insights
1. Netflix presents more movies than TV shows. Most movies last for 90-120 minutes. Most TV series are new with only 1 or 2 seasons. There has been an increase since 2015 in both TV shows and movies. The number of movies was greater than TV shows before the decrease. Netflix content experienced a sharp decrease in 2019, and the number of TV shows exceeded movies for the first time.
2. Anupam Kher, Rupa Bhimani, Takahiro Sakurai, Julie Tejwani, and Om Puri are popular casts and Rajiv Chilaka, Jan Suter, Raúl Campos, Suhas Kadav, and Marcus Raboy are popular directors.
3. The United States, India, and the United Kingdom are the top countries for movies and TV shows.
4. TV-MA, TV-14, TV-PG, and R are top ratings in Netflix content.
5. International movies, Dramas, Comedies, and International TV shows are very popular genres.

### Recommendations
- According to the above analysis, it is advisable for Netflix to prioritize future collaborations with renowned directors, casts, genres, and content.
- Rajiv Chilaka and Jan Suter are considered as best directors according to more number of Movie releases i.e 22, 21 respectively. So these directors' movies could help in growing business for Netflix
- International Movies, Dramas, and Comedies are mostly viewed genre in Netflix, So movies with these genres have more demand.
- The United States, India, United Kingdom these countries have the highest releases. So there is no risk of amount burn either in marketing or sales because it's already done.
- Movies having a duration between 90-120 minutes are recommended.
