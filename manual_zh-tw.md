# CloudMUN User Manual

此文件為 [CloudMUN](https://cloudmun.com.tw) 的使用指南，由 [Allen Chou](https://allenchou.cc) 撰寫。本文將詳細介紹 CloudMUN 的各種功能與操作方法。

## 基本操作

在操作所有功能之前，都必須[登入](http://cloudmun.com.tw/login)。

登入之後，會被引導至 Conference 畫面，預設首頁是 General Speakers' List ，上方則有導引列。
![cloudmun-00001](https://cloud.githubusercontent.com/assets/4427280/20836686/85c0fce0-b8db-11e6-9225-19c83cbba14e.png)

* Roll: Roll Call
* Agenda: Setting Agenda
* GSL: General Speakers' List （以下簡稱 GSL）
* Motion: 提出各種的 Motion
* Unmod: Unmoderated Caucus（以下簡稱 Unmod）
* SSL: Secondary Speakers' List （以下簡稱 SSL）
* Voting: 與 Voting 有關的所有功能
* Connected/Cached/Connecting: 系統連線狀態
* Username: 包含檢視 Timeline、登出、清除資料等功能（圖中的 Username 為 admin）
* Session: 選擇現在的 Session，也可以從此新增 Session

以下將針對 Rules of Procedure（以下簡稱 ROP） 中各種規則與流程的操作方式做出介紹

註：圖片中所有資料都是手動加上的，預設並不會有這些資料。

### Roll Call

Roll Call 的介面如下
![cloudmun-00002](https://cloud.githubusercontent.com/assets/4427280/20836689/85c4c8de-b8db-11e6-977b-d27e92fb1a9d.png)

P 為 Present ，PV 為 Present and Voting ，A 為 Absent ，不同 Session 有分欄位，點擊 Name 即可選擇使用 A-Z 排列或是 Z-A 排列，Spoken 為發言次數

右上角的表格為 Total Present 和 Majority 的及時統計  

![cloudmun-00003](https://cloud.githubusercontent.com/assets/4427280/20836989/ec68a7bc-b8dc-11e6-9ef3-c3896900d219.png)

### Setting Agenda

Setting Agenda 介面如下
![cloudmun-00004](https://cloud.githubusercontent.com/assets/4427280/20836688/85c3d208-b8db-11e6-8356-ed1e0abe85b5.png)

點擊 "Edit purpose" 即可編輯副標題  
![cloudmun-00005](https://cloud.githubusercontent.com/assets/4427280/20836691/85c7f40a-b8db-11e6-9cce-69c6e93606d4.png)

由於功能與 GSL 多相近，故統一在 GSL 中介紹

### GSL

GSL 介面如下
![cloudmun-00006](https://cloud.githubusercontent.com/assets/4427280/20836690/85c7d24a-b8db-11e6-9d1e-0d48d2aac23d.png)

介面右上角為計時器，操作按鈕由左至右分別為：開始、暫停、重設、設定每個講者擁有的時間。切換開始與暫停的鍵盤快捷鍵為空白鍵（Space）以及重設 (Ctrl)。
左側為 GSL ，列出所有準備發言的國家，國名旁的三個按鈕分別為：Recognized、移除與立場（For, Against, Netural）工具。

上方的輸入框可新增國家，輸入時會有建議輸入選項以節省時間。
![cloudmun-00007](https://cloud.githubusercontent.com/assets/4427280/20836693/85e60242-b8db-11e6-8ece-604d2d44583e.png)

右側為目前發言的國家名稱，下方工具列按鈕分別為：將代表放回 GSL、Yield to Country、Yield to Question、下一位代表，下一位代表的鍵盤快捷鍵為向右鍵（Right Arrow），另外，這會同時將計時器重設。

### Moderated Caucus
若要進行一個 Moderated Caucus，首先在被提出之後，可由 Motion 列表中找到 Moderated Caucus ，點入後會看到畫面如下
![cloudmun-00008](https://cloud.githubusercontent.com/assets/4427280/20836694/85e810aa-b8db-11e6-8551-4da47885e116.png)

將相關資訊填入後即可開始投票，Majority 的資訊如右上方表格。此外，若同時有多個 Motion ，可使用下方的 + 號新增不同的 Motion。
若 Motion 通過則按下 ✓ 號，再按 Continue 進入 SSL 。提出者將會自動被放入 SSL。
![cloudmun-00009](https://cloud.githubusercontent.com/assets/4427280/20836695/85e96d1a-b8db-11e6-9e80-2eff82f98cfb.png)
![cloudmun-00010](https://cloud.githubusercontent.com/assets/4427280/20836696/85ea163e-b8db-11e6-8aaf-f4eeb26fc7bd.png)

SSL 之操作方法與 GSL 相同，僅多了一個計時器來算 Total Time。

### Unmoderated Caucus
若要進行一個 Unmoderated Caucus，首先在被提出之後，可由 Motion 列表中找到 Unmoderated Caucus ，點入後會看到畫面如下
![cloudmun-00011](https://cloud.githubusercontent.com/assets/4427280/20836697/85edff6a-b8db-11e6-8e57-d123839f72b2.png)

該畫面操作方法如同在 Moderated Caucus 所述。
通過後會導引至 Unmod 畫面，即可開始進行。
![cloudmun-00012](https://cloud.githubusercontent.com/assets/4427280/20836698/85ee2a8a-b8db-11e6-9ab0-b7734f70ed7f.png)


註：Postponement of Debate、Resumption of Debate、Closure of Debate 操作方法皆與 Moderated Caucus 相同，除了通過之後會回到 Motion 頁面而不是進入 SSL

### Draft Resolution 與 Voting
提出 Draft Reolution（以下簡稱 DR）時，可使用 Motion 中的 Introduction of DR 。
![cloudmun-00013](https://cloud.githubusercontent.com/assets/4427280/20836699/860af46c-b8db-11e6-8db8-8af8b2cf71cc.png)
![cloudmun-00014](https://cloud.githubusercontent.com/assets/4427280/20836700/860eba20-b8db-11e6-93d8-9eb46606564f.png)

到 Voting 中的 Document Status 可檢視目前所有的 DR 及其狀態。
![cloudmun-00015](https://cloud.githubusercontent.com/assets/4427280/20836701/860fbc22-b8db-11e6-9876-b5070e8cd5e2.png)

到 Voting 中的 Reorder DR 可以調整 DR 順序。可使用 + 號新增排列方式（系統會自動為您打亂順序，您也可以手動調整），若點擊後無反應代表已經沒有其他的排列方式。按下 ✓ 號後才會儲存變更結果。
![cloudmun-00016](https://cloud.githubusercontent.com/assets/4427280/20836702/860fe1b6-b8db-11e6-830e-89a573b675e0.png)

到 Voting 中的 Roll Call Vote ，即可開始進行 Roll Call Vote。Y 為 Yes，N 為 No，Ab 為 Absent，A 為 Abstain （Roll Call 時選擇 Present and Voting 者無法投給此選項），P 為 Pass。
![cloudmun-00017](https://cloud.githubusercontent.com/assets/4427280/20836703/8613a3d2-b8db-11e6-80fe-d4bf0de3d3af.png)

右上角的表格中可以選擇 	Current DR （目前正在進行投票的 DR），其狀態（Pass 或 Fail）以及 Round 。


進入 Round 2 的畫面如下
![cloudmun-00018](https://cloud.githubusercontent.com/assets/4427280/20836704/8613f030-b8db-11e6-81a1-07fd8d4984f5.png)

此外，Voting 中也有 Vote by Simple Majority 與 Vote by Acclamation 的選項可供使用。
![cloudmun-00019](https://cloud.githubusercontent.com/assets/4427280/20836706/862eea8e-b8db-11e6-9d22-795095e74e76.png)

### Friendly Amendment
若要提出 Friendly Amendment，可由 Motion 列表中找到 Introduction of Friendly Amendment。
![cloudmun-00020](https://cloud.githubusercontent.com/assets/4427280/20836707/86352d7c-b8db-11e6-80c0-8399aec3742e.png)

填入圖中之資訊即可。按下 ✓ 號後儲存並通過。

### Unfriendly Amendment
若要提出 Friendly Amendment，可由 Motion 列表中找到 Introduction of Unfriendly Amendment
![cloudmun-00021](https://cloud.githubusercontent.com/assets/4427280/20836708/8635e3f2-b8db-11e6-9d88-f9f19c85e860.png)

填入圖中之資訊即可。按下 ✓ 號再按 Continue 後會進入 SSL。
![cloudmun-00022](https://cloud.githubusercontent.com/assets/4427280/20836709/8636d4d8-b8db-11e6-8909-a84e8062bbba.png)

### Session
點擊 Username ，選到目前的 Session，或是選 Add Session 新增。新增之後，會在 Roll Call 看到新 Session 的 Roll Call 表。  
![cloudmun-00026](https://cloud.githubusercontent.com/assets/4427280/20836713/8659ffee-b8db-11e6-9749-b8b204c97f9a.png)

## 其他功能
### Timeline
點擊 Username ，選到 Timeline ，即可看到會議過程的詳細記錄。
![cloudmun-00023](https://cloud.githubusercontent.com/assets/4427280/20836710/863a160c-b8db-11e6-92f0-af0c1aff95cf.png)

### 匯出資料
在 Roll Call、Roll Call Vote、Timeline 等頁面中會看到 Copy、CSV、Excel、PDF ，該按鈕為匯出資料功能，點擊即可下載資料。
註：此功能需要瀏覽器端的 Flash 支援。
![cloudmun-00024](https://cloud.githubusercontent.com/assets/4427280/20836711/863a8d9e-b8db-11e6-87a8-a127251496a1.png)
![cloudmun-00025](https://cloud.githubusercontent.com/assets/4427280/20836712/86532598-b8db-11e6-9623-7cd00912c0e1.png)

### 離線存取
為了避免會議途中網路意外斷線，當您第一次造訪 CloudMUN 的 Conference 頁面時，瀏覽器會自動儲存所有頁面，所以即便網路意外斷線，大部分的功能都仍然可以正常運作，且會在連線恢復時儲存所有資料至雲端。
註：離線存取必須有 [HTML5 Application Cache](http://caniuse.com/#feat=offline-apps) 與 [localStorage](http://caniuse.com/#feat=namevalue-storage) 支援，目前主流瀏覽器皆已支援，故請確認您的瀏覽器為最新版。

### 同步
CloudMUN 支援同步功能，大部分的資料可在不同電腦之間即時更新。右上角的 Connected / Cached / Reconnecting / Disconnect 代表目前狀況，若為前兩者代表網路正常運作中，若為 Reconnecting 代表系統正在嘗試連線，也請麻煩檢查電腦的網路是否運作正常，若為 Disconnect 可點擊該文字重新連線。

### 檢查錯誤
當右上角的時鐘閃爍三下，代表您的操作可能有邏輯問題（例如您所輸入的國家不存在）或是系統出現未知的狀況，導致系統無法正常運作，可點擊時鐘檢視錯誤訊息
![cloudmun-00027](https://cloud.githubusercontent.com/assets/4427280/20836714/865d99ce-b8db-11e6-8f24-339bd876191c.png)

### 重設資料
若同步功能無法正常運作，或是瀏覽器的資料不明原因亂掉了，可點擊 Username 中的 Reset Local 清除本地資料，即可將電腦中的快取清除，再重新整理便會從伺服器抓取最新的資料。

若所有電腦都發生資料錯亂的問題，或是想要清除會議資料，可在所有電腦中都選擇 Reset Local 後，在其中一台電腦選擇 Reset Server ，即可將資料清除。

**此功能僅供進階使用者使用，若您不知道上述兩個按鈕是用來做什麼，或不確定哪些資料會被清除，則絕對不要使用該功能，以免造成寶貴的會議資料遺失。**


## 授權
本文由 [Allen Chou](https://allenchou.cc) 撰寫，以 [CC BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.en) 釋出。