# 中正開課表格優化

如果有任何問題，歡迎找楊長茂 jeffrey0613mao@gmail.com 

## 介紹&效果
### 介紹
由於中正的開課時間有分成1,2,3,...與A,B,C,...兩種時間區段，導致在查看開課時間時，還需要花時間確認是否衝堂，因此用 JavaScript 寫了一小段程式，可將每個科系的開課時間與資訊轉換到課表上，變得更為便捷。

### 效果:

原始介面                     |  轉換後介面
:-------------------------:|:-------------------------:
![before](https://raw.githubusercontent.com/Jeffreymaomao/figure/main/%E6%88%AA%E5%9C%96%202022-09-05%20%E4%B8%8B%E5%8D%888.03.45.png)  |  ![after](https://raw.githubusercontent.com/Jeffreymaomao/figure/main/%E6%88%AA%E5%9C%96%202022-09-05%20%E4%B8%8B%E5%8D%888.04.23.png)

## 安裝與使用方法

### 安裝（電腦 Chrome）

1. 安裝 Tampermonkey (教學影片 https://www.youtube.com/watch?v=8tyjJD65zws)
  - 到 https://www.tampermonkey.net/ 點擊下載 Tampermonkey 程式（會跳到google應用程式連結）
  - 或是到 [google應用程式連結](https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo)直接點擊```Add to Chrome```
2. 安裝 JavaScript 腳本
  - 回到頁面最上面，點擊 ```中正開課表格優化.user.js``` 檔案
  ![](https://raw.githubusercontent.com/Jeffreymaomao/figure/main/F5.png) 
  - 進入後，點擊右上角 ```Raw``` 按鈕
  ![](https://raw.githubusercontent.com/Jeffreymaomao/figure/main/F6.png) 
  - 頁面會自動跳至 Tampermonkey 的頁面，點擊 ```install``` 
  - 安裝完後即可關閉所有頁面

### 使用方法
1. 進入國立中正大學開排選課系統 https://kiki.ccu.edu.tw/~ccmisp06/Course/
2. 與平常一樣點擊所想要查詢的科系
3. 進入後即可看到生成的時間表

### 注意！
只適用於中文版本


## 關閉表格生成（關閉 JavaScript 腳本）





