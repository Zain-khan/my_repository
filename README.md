# my_repository
# to acees baseball.csv file

url = "https://raw.githubusercontent.com/pandas-dev/pandas/master/doc/data/baseball.csv"
baseball = pd.read_csv(url)


print(baseball)

baseball.info()
