import pandas as pd
melb_filepath='../input/melbourne-housing-snapshot/melb_data.csv'
melb_data=pd.read_csv(melb_filepath)
melb_data.describe()
