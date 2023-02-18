# my_repository
# to acees baseball.csv file

url = "https://raw.githubusercontent.com/pandas-dev/pandas/master/doc/data/baseball.csv"
baseball = pd.read_csv(url)


print(baseball)

baseball.info()

# load iris

iris = pd.read_csv('https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data ')

iris
iris.assign(sepal_ratio=iris["5.1"] / iris["0.2"]).head()
