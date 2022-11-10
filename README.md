# 安裝流程
## https://www.python.org/downloads/release/python-370/ 
## 到上面這個網址下載python3.7，安裝時記得add to Path要勾
![image](https://user-images.githubusercontent.com/79627981/201091946-723811fc-e505-4f9c-b094-d766cab9858b.png)

## ![image](https://user-images.githubusercontent.com/79627981/201092523-cf762094-7848-4859-8e9f-734b805b53c8.png)
## 第三步是要把你安裝好的 python37的路徑 跟 python37的Scripts的路徑 放到環境變數內

## 都設定好之後，win+R打cmd進到小黑後輸入 pip list
![image](https://user-images.githubusercontent.com/79627981/201093314-ba2205b6-d552-4260-a5a4-b3ee8ecbce43.png)
## 查看安裝包是否只有pip 及 setuptools 這兩個(新裝的python應該就這兩個而已)

## 然後應該會有黃字的部分，意思是要你更新pip的版本
## 所以就照著她輸入 python -m pip install --upgrade pip
![image](https://user-images.githubusercontent.com/79627981/201094193-266cb5d7-afc4-42dd-a9be-3b7dafad6e88.png)

## 安裝完成，接下來就可以執行了
![image](https://user-images.githubusercontent.com/79627981/201094024-447a350f-1539-4b6d-a0d9-6293d3b1828b.png)

## 輸入 labelimg
![image](https://user-images.githubusercontent.com/79627981/201094522-d8b9a34b-b8aa-4fcc-a43d-79924a118965.png)

## 成功執行!
![image](https://user-images.githubusercontent.com/79627981/201094604-58f8f233-ba69-40f1-99ee-8a6be5214f14.png)

## 功能介紹及步驟 1.打開要做標籤黨的資料夾(就是那些瓦斯表圖片的資料夾) 2.變更標籤黨儲存的位置(看你想存哪) 3. 他有YOLO、CreateML、PascalVOC三種儲存格式，我們要選YOLO，因為它儲存的格式是txt檔，因為我們在用Yolo訓練時他就是要用txt格式才行
![image](https://user-images.githubusercontent.com/79627981/201094918-af03d715-c9fd-4275-8707-569185c7fb90.png)

![image](https://user-images.githubusercontent.com/79627981/201093677-cd111584-85c4-4f63-b462-f735768664f8.png)

![image](https://user-images.githubusercontent.com/79627981/201093472-af558265-856b-4f75-a504-6584fbd5394c.png)

![image](https://user-images.githubusercontent.com/79627981/194733956-b46be17d-d030-40d0-b976-952bf5eb4c43.png)

## labelmg 安裝完後，在小黑輸入 pip install PyQt5
![image](https://user-images.githubusercontent.com/79627981/194734001-349c36ad-cc55-426f-b23f-991c9db07da4.png)
### 如果安裝不了PyQt5的話就去 https://www.riverbankcomputing.com/pypi/simple/pyqt5/ 安裝windows的版本
### 之後一樣在小黑，輸入 pip install PyQt5-5.15.8.dev2209172313-cp37-abi3-win_amd64.whl


## PyQt5安裝完成後 直接輸入labelimg就可以執行了
![image](https://user-images.githubusercontent.com/79627981/194734031-1a131795-1901-4195-ae2e-50b9e9f64440.png)
### 輸入labelimg沒反應的話重開電腦試看看(重開沒辦法的話我暫時也沒想法)

## 參考資料
### https://youtu.be/l_TrGcN_p2M  
### https://blog.gtwang.org/useful-tools/labelimg-graphical-image-annotation-tool-tutorial/?fbclid=IwAR2G4HAO4VXsC-Ckl9PKEvAQH7S8ebc3Fbg3_WFydBcGmxW0zmFg1DuBgQg
