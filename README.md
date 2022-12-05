# 泰山職訓前端班期中作業
請學員製作⼀個查詢公開資料的 LINE 機器⼈，並部署到雲端伺服器
資料來源不限，可使⽤ Google API、[政府開放資料](https://data.gov.tw/)等  
**請將作業上傳到自己的 GitHub 儲存庫**  
**並在儲存庫的 README.md 註明機器⼈的好友 ID 、連接的公開資料來源以及使⽤說明**  
**最後將本檔案下方的作業連結改為自己的 GitHub 儲存庫**  
**未修改連結或繳交上課範例視同零分**

## 繳交時間
2022 年 12 月 7 日

## 分數分配
|項⽬|說明|分數|
|:---|:---|:---|
|上傳到 GitHub|是否將作品上傳⾄自己的 GitHub|15|
|編寫 README|是否編寫自己的 GitHub 儲存庫 README|15|
|串接⼀個以上的公開資料|是否串接⼀個以上的公開資料|30|
|部署到雲端伺服器|是否部署到雲端伺服器|30|
|機器⼈實⽤性|機器⼈功能的實⽤程度|10|

## 注意
請盡量使用上課教的 GUI 工具或 git 指令繳交作業  
若使用 GitHub 網頁進行 commit 會依次數扣分

## 作業連結
- [儲存庫]([https://github.com/](https://github.com/ChichiTung/HW_LineBot))

## 使用說明
LineBot-ID : @932antlj
![image](https://user-images.githubusercontent.com/65598956/205702197-67bcbf80-2977-4ec5-ab2c-ae7be3564435.png)


### 連結的公開資料庫 :

(https://movies.yahoo.com.tw/movie_intheaters.html)
(https://movies.yahoo.com.tw/movie_thisweek.html)
(https://tw.portal-pokemon.com/play/pokedex](https://www.imdb.com/chart/top?sort=ir)

### 操作方式 :

支援圖文選單，可由點選圖文選單進入如下功能，或是藉由直接輸入各項功能之文字，進入功能項：

(1)找找電影院：
  會跳出兩項建議選項(Quick Reply)：
  a.發送使用者之位置訊息，查找離其最近的電影院(目前只支援位置訊息發送，最近之電影院查找尚未實裝)
  b.查詢電影院票價
  
(2)經典推薦
  隨機推薦使用者一部 IMDb 250部評分最高的電影，可直接進入IMDb影評頁，或是進入線上資源觀看影片
  
(3)本週新片
  發送 10 部本週上映的電影，使用者可藉由：
  a.點選片名，進入預告片播放頁
  b.點選短簡介，觀看完整介紹
  c.點選來點影評按鈕，觀看該部電影的相關介紹或心得
  
(4)熱映中
  發送 10 部目前熱播電影，使用者可藉由：
  a.點選片名，進入預告片播放頁
  b.點選短簡介，觀看完整介紹
  c.點選來點影評按鈕，觀看該部電影的相關介紹或心得
  d.點選去查時刻，看電影在全台影城的播放時段
  
 (5)熱映中
  推送 Netfix 目前台灣的熱播電影
 

