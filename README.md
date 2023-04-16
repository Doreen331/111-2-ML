# 111-2-ML
教授您好，我是資管二110403005朱芮儀，在開始閱讀我的報告前，先向您簡介我的報告形式以及檔案放置方式👾  
我總共做了三個模型，分別是Version1、Version2、Version3  
分別放在三個不同的資料夾，我會在ipynb檔裡使用註解標示我從上個版本改進了哪些、我的想法以及其他說明  
而「比賽簡介/為什麼選擇這個比賽/資料集和目標介紹」則是放在README，比較像是一個在正式看我模型前的introduce  
先在這邊感謝您的觀看！以下是我報告的正式開始gogo ٩(◦`꒳´◦)۶   

比賽簡介＆為什麼選擇這個比賽
=============

這是一個用 Binary Classification 去預測input資料裡的病人會不會中風的比賽

我在選擇比賽上花費了很多時間，以下是我選擇比賽考慮的條件：  
1:我希望拿到高分，所以沒選擇房價預測以及太空船的題目  
2:預測的項目是二分法並且結果是0、1，就像是titanic範例一樣，而不是房價預測範例的regression  
3:我後來發現很多題目給的檔案不只三個，但我自知還沒有能力處理太複雜的資料，因此選擇只給三個檔案的比賽  

這類比賽真的挺難找的，後來我在playground找到了這個比賽，剛好題目我也覺得很有趣，因此選擇了它  

資料集和目標介紹
=============
訓練的資料裡總共有12個欄位：  
1.id: 病患的序號  
2.gender: 病患的性別，三種分別為： "Male", "Female" ,"Other"  
3.age: 病患的年紀   
4.hypertension: 病患有沒有高血壓，0代表沒有，1代表有  
5.heart_disease: 病患有沒有心臟疾病，0代表沒有，1代表有  
6.ever_married: 病患的是否結婚  
7.work_type: 病患的工作類型  
8.Residence_type: 病患的居住地，兩種分別為："Rural" , "Urban"  
9.avg_glucose_level: 病患血液裡平均葡萄糖濃度  
10.bmi: 病患的bmi  
11.smoking_status: 病患是否抽煙，四種分別為："formerly smoked", "never smoked", "smokes" , "Unknown"  
12.stroke: 病患是否中風，0代表沒有，1代表有  

目標為預測病患是否會中風  

比賽連結：https://www.kaggle.com/competitions/playground-series-s3e2/overview

和上課內容的關聯性&延伸學習
=============


