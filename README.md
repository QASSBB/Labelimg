# 安裝流程

## 先把python刪掉
![image](https://user-images.githubusercontent.com/79627981/201532249-c035d9fa-0f2f-42b1-89f8-8cd80af56f93.png)

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

## 然後就按鍵盤上的w，開始框，框完一個後輸入他的標籤(數字)，做完一張就儲存換下一張
![image](https://user-images.githubusercontent.com/79627981/201097431-e9c81a2e-8c03-45ec-bcbf-0ede006b4a86.png)
![image](https://user-images.githubusercontent.com/79627981/201097260-173ea526-f16a-4bd9-9842-34b64c13e56c.png)


## 參考資料
### https://youtu.be/l_TrGcN_p2M  
### https://blog.gtwang.org/useful-tools/labelimg-graphical-image-annotation-tool-tutorial/?fbclid=IwAR2G4HAO4VXsC-Ckl9PKEvAQH7S8ebc3Fbg3_WFydBcGmxW0zmFg1DuBgQg
