---
description: 將檔案push到Github專案
---

# SourceTree 操作

我們要使用SourceTree將網頁檔案Push推上GitHub

請先登入GitHub網頁，並建立一個新的專案

![](.gitbook/assets/image%20%2819%29.png)

{% hint style="info" %}
github.io網址前面的使用者名稱，就只能是github的註冊名稱，一個人就是只能有一個網址而已
{% endhint %}

專案請記得名稱後面直接加上github.io，然後其他都不需要動，直接Creat repository產生儲存庫

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lsembkfkltzy-0n0b8m_-lsemcavvms_fwjm9qf0_image.png)

專案的github 網址產生，但這只是可以連結到儲存庫的網址，並不是網頁的網址喔！

我們需要用以下的儲存庫網址來讓SourceTree使用，才能Push上去GitHub，所以請將你們自己的gitHUB

網址複製起來，也就是紅框圈起的位置。

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lsemz8imlsvqluhhgpy_-lsendq0n1tsnowkj8tx_image.png)

點擊SourceTree的　Create＋　按鈕，點Browse選擇你網頁的資料夾位置，Name輸入自訂專案名稱，再點擊Create按鈕

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lsenqpkum9bmrnuhrqm_-lsep7mc9kmvog8yjlaq_image.png)

我們做好的網頁檔案就會出現在SoucreTree

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lseqhl25jybtuuriyi6_-lseqk1wvhhltydz4h6s_image.jpg)

我們也可以開啟我們的網頁資料夾，檢查看看是不是有多一個.git的資料夾，如果有，就表示成功將目錄初始化

![](.gitbook/assets/image%20%2860%29.png)

接著設定remote repository的位址，接著點選上面的Remote

![](.gitbook/assets/image%20%2840%29.png)

因為我們剛剛安裝時我們選擇後面才設定，所以會跳出這個視窗訊息，那我們按Settings

![](.gitbook/assets/image%20%2818%29.png)

點選　Add來新增一個remote repository

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lsersgakteju0xl_-uo_-lsesmhsdigtts_wyewz_image.png)

貼上我們的GitHub網址並將Default remote打勾勾，Host Type並選擇GitHub

![](.gitbook/assets/tree10.jpg)

填寫你要提交出去的作者名稱，後點OK

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lsersgakteju0xl_-uo_-lsetummd1diq4va_7ua_image.png)

就會看到剛剛我們新增的儲存庫網址，然後點OK

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lseu9jjhqijki4afngz_-lseuaavsdtdfevz6prs_image.png)

SourceTree的Unstaged　files區域，就是我們還沒Push上去的檔案，因為還沒有commit。

那我們就選擇Stage All，一次全部改變他的狀態。

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lseuenubiefzlrzqnoi_-lsevacnejydcszzicpp_image.png)

完成就會變成跑到上面的Staged Files區域了，你也可以在右邊的視窗看見自己的網頁原始碼

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lseuenubiefzlrzqnoi_-lsew6q1xom_jntnpsfn_image.png)

在訊息欄位輸入你自己和別人看得懂紀錄文字，可以輸入中文，接著點選Commit 按鈕

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lsewftzi3m9rp5vb6g7_-lsewhpktxx1aftqyhqh_image%20%281%29.png)

### 出現錯誤訊息

如果你有跳出這種視窗，是因為你的emil或是使用者名稱沒有符合規定寫法，也許有空格你沒注意到，那就要修正才能Commit。  
如果你們有出現這視窗就跳過這個步驟

![](.gitbook/assets/assets_-ls_nyafzm7iujwicdoz_-lsewftzi3m9rp5vb6g7_-lsexfcpz_po1784p35q_image.png)

修正錯誤到Tool 底下的Options，發現我的名稱多了空格，取消空格後按OK，就可以Commit了

![](.gitbook/assets/image%20%2871%29.png)

![](.gitbook/assets/tree11.jpg)

### Commit完成

commit完成，你會發現在Branch底下的提交紀錄有一master主支，裡面有我們的紀錄

![](.gitbook/assets/image-1.png)

接著點選Push，把檔案推上GitHub

![](.gitbook/assets/image-2.png)

將repository中唯一的主支master勾選起來，接著按Push

![](.gitbook/assets/image%20%2817%29.png)

SourceTree要開始傳送，但因為我們沒有登入GitHub，他無法Push上去，所以我們要輸入帳號密碼登入GitHub

![](.gitbook/assets/image-4.png)

傳送完成他會出現遠端分支

![](.gitbook/assets/image-5.png)

回到Github 網頁就會看到我們剛剛Push上去的網頁檔案了喔!!

一樣點擊setting 往下拉就會看見我們的網頁網址了

![](.gitbook/assets/image%20%2855%29.png)

![](.gitbook/assets/image%20%2826%29.png)

![](.gitbook/assets/image%20%2831%29.png)

