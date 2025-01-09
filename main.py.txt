import pandas as pd
df = pd.read_csv("D:/VS Code/Python/Temp/Dataframe/WHO COVID-19 cases.csv")
afghanistan_data = df[df["Country"] == "Afghanistan"]
print(afghanistan_data)
