# 介紹
此專案撈取了氣象署公開資料，以及使用github平台上提供之公開程式碼，撈取臺灣期貨交易所提供之股價資訊。  
整合以上資訊，以手動、定時與即時推播Line Notify提供資訊。  

# 使用套件
import schedule  
import time  
import json  
import requests  
import threading  
import pandas as pd  
from google.colab import files  
from IPython.display import Image  

# 效果展示
地震消息推播  
![下載 (2)](https://github.com/cj20200112/Web-crawler/assets/166897672/3fb0f471-2e7d-40d6-9482-1050e0ece166)  
防曬提醒推播  
![下載](https://github.com/cj20200112/Web-crawler/assets/166897672/2a170c09-9462-49ea-966b-19dcd2d85684)  
股價波動推播  
![下載 (1)](https://github.com/cj20200112/Web-crawler/assets/166897672/7707d121-3d40-45ce-a4d6-4881ca720881)
