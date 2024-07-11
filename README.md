# 資料科學專案 #
# 加拿大溫莎市的房屋價格分析與預測 #

## 資料來源： ##
## House Prices in the City of Windsor, Canada ##
### 從R語言內建的加拿大溫莎市的房屋資料來做分析，資料為1987 年 7 月、8 月和 9 月期間加拿大溫莎市房屋的銷售價格。(資料共546筆，沒有遺失值) ###

## 目標(依變數) ##
*   價格(price)

## 自變數(11)： ##

*   坪數(lotsize)以平方英尺為單位
*   臥室數(bedrooms)
*   浴室數(bathrooms)
*   樓層數(stories)
*   有無車道(driveway)
*   有無娛樂室(recreation)
*   有無地下室(fullbase)
*   有無熱水器(gasheat)
*   有無中央空調(aircon)
*   車庫數(garage)
*   位於市區(prefer)
## [資料內容相關連結](https://vincentarelbundock.github.io/Rdatasets/doc/AER/HousePrices.html)
```python
import pandas as pd
import numpy as np
df = pd.read_csv('/content/HousePrices.csv',index_col=0)
df.head()
```
![image](https://github.com/hsu-chien-chung/DataScienceProject/assets/118785456/b94ad0c6-8f14-4cd1-b116-e45764e8b557)








































































