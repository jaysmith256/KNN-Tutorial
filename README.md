# Explatory Data Analyis (EDA) using Red Wine Quaulity Data - Introduction Tutorial

Objective of the project:
*Provide introductory tutorial of common exploratory data analysis using Python's Pandas and Numpy libraries
*The project uses a common dataset example for red wine quality - widely sourced from kaggle, google, etc

Files included in the project:
*README
*winequaity-red.csv
*PandasTutorialWineEDA.ipynb

Instructions to use this project: 
*Use git clone to pull the project files into your notebook environment
*Launch the PandasTutorialWineEDA.ipynb notebook and execute each task accordingly

Description of the notebook project:
The project will walk the user through at least 15 different tasks to perform for EDA on the red wine quality dataset
1. wine_quality = pd.read_csv('winequality-red.csv') - read the dataset (upload the datset to your local directory first)
2. wine_quality.head() -top 5 lines of dataset
3. wine_quality.shape -# of rows and cols
4. print(wine_quality.columns) -cols by list
5. print(wine_quality.count()) -list of cols and the total # of null values for each
6. print(wine_quality.info()) -type of each col along with its row counts of non-null
7. wine_quality.describe() -basic stats of each col
8. wine_quality['pH'].mean() -mean value for a specific colume
9. wine_quality[wine_quality['quality'] == 4].mean() -avg value of all the other cols based on a certain value of 1 col
10. wine_quality['pH'].value_counts() -how many times does a certain value show up for a col
11. wine_quality['pH'].value_counts(normalize=True) -value counts in percentage¶
12. wine_quality.sort_values(by='quality', ascending=False).head() -sorting by a specific col
13. wine_quality[-1:] -showing the last row of the df
14. wine_quality.apply(np.max) -applying functions to a df
15. columns_to_show = ['residual sugar', 'alcohol', 'quality']; wine_quality.groupby(['density'])[columns_to_show].describe(percentiles=[])


Contribute to the project:
*For any contribution considerations, please send to [placeholder]@gmail.com 
