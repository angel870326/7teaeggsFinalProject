# 7teaeggsFinalProject
2019資料創新應用競賽＿紫色茶葉蛋＿最終成品：社會經濟空間資料暨地政應用組
## 問題意識：
* ”什麼產業適合開在什麼樣的地方？“、”一個地方的特定產業是否飽和？“等問題常是創業者希望詢問、解決的問題，我們的作品在於回答這樣的問題，運用”地理區位分析“找出類似的人口結構將台灣村里進行分類並預測該地能設立多少家”某產業“的店面，與實際之設立家數比較，是飽和？還是依然有消費可能之潛力？本組期待特過這樣的方法回應創業者之問題、及憂慮。

## 最終成品使用方法：（使用 R 與 Rstudio搭配shiny套件做出網頁）
* 第一步：安裝 R 與 Rstudio
* 第二步：在 R studio中輸入語法安裝：shiny、leaflet、RColorBrewer、sf、data.table、stringr、readr、foreign、readxl、haven、tidyverse等套件（安裝方法：輸入語法“install.package("shiny")”，安裝所有套件。
* 第三步：將github之「成品資料集」下載下來，並設定資料夾路徑（所有檔案皆要放在同一個資料夾中）
* 第四步：將 Rstudio打開，點選檔案開啟「app.R」，並用語法“setwd("放入剛下載之資料夾路徑，如/Users/will/Desktop/資料創新應用競賽/7teaeggsFinalProject/“）”。
* 第五步：直接Run「app.R」中所有程式碼到底，即可得到網頁成品。

## 產品說明：
* 創業類型可分為獨立創業及內部創業,內部創業者在現有企業的支持下,
資金、設備、人才等資源皆較充裕,且企業內部對市場環境有一定的熟悉度,
不乏專業人士為內部員工進行市場分析及決策,創業風險較小。
反之,獨立創業者在資金方面擁有龐大壓力,設備及人力也明顯不足現有
企業,加上創業者可能缺乏通盤管理能力,不了解現有人口、經濟結構與市場
等情況,導致做出錯誤的決策。基於上述原因,我們將網站的使用對象定位為
「欲獨立創業之個人或團隊」,幫助他們整合並分析現有人口及市場資料,降
低資訊不充足等問題,並且提供創業相關建議,降低個人或團隊的創業風險。

## 產品功能：
* 1. 用“隨機森林”機器學習方法進行產業競爭力預測及產業潛力分析,精準掌握創業定位。
* 2. 地圖視覺化易操作,視覺直觀清楚。
* 3. 客製化選項提供使用者針對特定族群進行分析。
* 4. 描述在該產業下,各村里人口結構以及世代差異、所得所交互影響之結果。


