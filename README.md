# NSE500-Historical-Data-Extractor
This notebook outlines the usage of the tvDatafeed Python API to extract historical Open, High, Low, Close and Volume data for all listed NSE500 symbols from
tradingview.com

Date range is customizable by varying the start and end date variables

import pandas as pd
url = 'https://archives.nseindia.com/content/indices/ind_nifty500list.csv'
NSE500_data = pd.read_csv(url)
NSE500_symbols = NSE500_data['Symbol']
NSE500_symbols
