The above dataset contains physicochemical properties of drugs.

We can use the ICHI(a measure of toxicity) as a target variable to predict drug toxicity, in which we can classify drugs as toxic or non-toxic based on the ICHI values

Molar Volume,Molar Refractivity,Polarizability are in cm3

from sklearn.metrics import mean_squared_error
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import MinMaxScaler
from sklearn.linear_model import LinearRegression
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import RandomForestRegressor