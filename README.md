## Synopsis

The purpose of this project was to analyze a dataset of the passengers on the Titanic and draw conclusions about those passengers from the data. This project required use of the Numpy and Pandas libraries in Python.

## Code Example

```python
df = pd.read_csv('titanic-data.csv')
df.head()

#check the default data types of each column
df.dtypes

#cast survived as boolean type instead of int
df['Survived']=df['Survived'].astype('bool')
df.head()
```

