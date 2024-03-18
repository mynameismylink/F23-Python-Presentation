# F23-Python-Presentation
This is a data group project with the aim to explore the correlations between a country's economy and tobacco use prevalence, with consideration of other factors such as alcohol consumption and gender differences.

# Presentation 1 - Group 2
## Does tobacco have anything to do with GDP per capita, alcohol, or gender?

### Background
- Tobacco use is a much-discussed topic in daily life and in the world.
- Some countries have a lot of smokers, and some do not, despite the similarity in the message in the packaging of tobacco, for example, “Smoking causes lung cancer.”
- Understanding the trend of the prevalence of tobacco use with consideration of other factors can be insightful to tobacco policies.

### Data
The data for this analysis can be obtained from the World Bank API's database. Either wbdata or wbgapi python module can retrieve data from the same database.

### Python Dataframe
Python dataframes are a powerful tool for data analysis. Dataframes can be used to store, manipulate, and analyze data in a variety of ways.

### Conclusion
- **Hypothesis 1**: The more economically advantaged a country is, the higher the prevalence of tobacco use - **Unlikely**
GDP per capita & Tobacco use prevalence - Little correlation. 
However, tobacco use prevalence converges when GDP per capita increases.

- **Hypothesis 2**: Countries with a higher prevalence of alcohol use also have a higher prevalence of tobacco use - **Likely**
Tobacco use and alcohol use prevalence - Moderately positive correlation.

- **Hypothesis 3**: Economically advantaged countries has similar tobacco consumption level between male and female - **Likely**
GDP per capita & difference of tobacco use by gender - Relatively 
negative correlation. The wealthier a country is, the less difference is seen in male and female tobacco use.

### Python Libraries
- wbdata
- pandas
- datetime
- geopy
- nominatim
- pycountry
- json
- plotly
- matplotlib
- seaborn
- numpy
- random

### Contributors
- Nguyen Mai Linh (Sandy) 20229031
- Farhan Toshi Hermawan 20229531
- Fariha Qorinatuz Zahra 21229529
