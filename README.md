# Pandas_Challenge: In this Challenge , the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. My task for this challenge is to generate a report that breaks down the game's purchasing data into meaningful insights. My report needs to include: Player Count, Purchasing Analysis, Gender Demographics, Purchasing Analysis, Age Demographics, Top Spenders, Most Popular Items and Most Profitable Items.


  (Gender)

# set up the Dependencies 
import pandas as pd
import numpy as np

# grabbing and setting path file
purchase_df = "Resources/purchase_data.csv"

# Reading the Purchasing File and storing into Pandas data frame
purchase_df = pd.read_csv(purchase_df)

### Player Count

* Total Number of Players
