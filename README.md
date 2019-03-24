# Library-System

* User Manual 使用手冊

    - 資料庫內沒有預設的使用者資料，請自行註冊。

    - 資料庫內預設的管理員，帳號密碼皆為root。
    
    - 資料庫已有預設一些圖書資料。

    - 系統主要畫面如下

        1.管理員登入

            螢幕顯示: ----歡迎---
                     1) 使用者登入
                     2) 管理者登入
                     3) 註冊使用者帳號
                     4) 離開
            本機輸入: 2
            螢幕顯示: 請輸入你的帳號 :
            本機輸入: root
            螢幕顯示: 請輸入你的密碼 :
            本機輸入: root
            螢幕顯示: 編號：666 姓名：XinMiao 帳號：root 密碼：root
                     登入成功！
                     ----管理員模式----
                     1) 顯示所有圖書
                     2) 增加圖書
                     3) 刪除圖書
                     4) 修改圖書
                     5) 查詢圖書
                     6) 清空圖書
                     7) 登出帳號

        2.輸入指令"1"可顯示所有館內圖書

             本機輸入: 1
             螢幕顯示:  編號：800 書名：Fade,作者：Alanwalker,分類：music,價格：500.0,狀態：0
                       編號：801 書名：Energetic,作者：WannaOne,分類：music,價格：900.0,狀態：0
                       編號：802 書名：Beautiful,作者：WannaOne,分類：music,價格：1500.0,狀態：0
                       編號：803 書名：I.P.U,作者：WannaOne,分類：music,價格：670.0,狀態：0
                       編號：804 書名：WW2,作者：Churchill,分類：history,價格：200.0,狀態：0
                       編號：805 書名：Egg100,作者：SuYuanMa,分類：cook,價格：720.0,狀態：0
                       編號：806 書名：ThreeLittlePig,作者：Provantini,分類：story,價格：150.0,狀態：0

        2.輸入指令"2"可新增圖書

             本機輸入: 2
             螢幕顯示: 請輸入編號：
             本機輸入: 500
             螢幕顯示: 請輸入圖書名：
             本機輸入: PitchPerfect
             螢幕顯示: 請輸入作者：
             本機輸入: Cannon
             螢幕顯示: 請輸入分類：
             本機輸入: comedy
             螢幕顯示: 請輸入單價：
             本機輸入: 1200
             螢幕顯示: 增加成功！
                      編號：800 書名：Fade,作者：Alanwalker,分類：music,價格：500.0,狀態：0
                      編號：801 書名：Energetic,作者：WannaOne,分類：music,價格：900.0,狀態：0
                      編號：802 書名：Beautiful,作者：WannaOne,分類：music,價格：1500.0,狀態：0
                      編號：803 書名：I.P.U,作者：WannaOne,分類：music,價格：670.0,狀態：0
                      編號：804 書名：WW2,作者：Churchill,分類：history,價格：200.0,狀態：0
                      編號：805 書名：Egg100,作者：SuYuanMa,分類：cook,價格：720.0,狀態：0
                      編號：806 書名：ThreeLittlePig,作者：Provantini,分類：story,價格：150.0,狀態：0
                      編號：500 書名：PitchPerfect,作者：Cannon,分類：comedy,價格：1200.0,狀態：0
                      是否繼續增加？ y/n

             輸入y繼續新增圖書，n取消並返回主菜單。

        3.輸入指令"3"可刪除圖書

             本機輸入: 3
             螢幕顯示: 請輸入按哪種方法刪除圖書：
                      1) 編號
                      2) 書名
                      3) 返回主菜單
             本機輸入: 1
             螢幕顯示: 請輸入要刪除的書的編號：
             本機輸入: 500
             螢幕顯示: 編號：800 書名：Fade,作者：Alanwalker,分類：music,價格：500.0,狀態：0
                      編號：801 書名：Energetic,作者：WannaOne,分類：music,價格：900.0,狀態：0
                      編號：802 書名：Beautiful,作者：WannaOne,分類：music,價格：1500.0,狀態：0
                      編號：803 書名：I.P.U,作者：WannaOne,分類：music,價格：670.0,狀態：0
                      編號：804 書名：WW2,作者：Churchill,分類：history,價格：200.0,狀態：0
                      編號：805 書名：Egg100,作者：SuYuanMa,分類：cook,價格：720.0,狀態：0
                      編號：806 書名：ThreeLittlePig,作者：Provantini,分類：story,價格：150.0,狀態：0

             本機輸入: 2
             螢幕顯示: 請輸入您要刪除的書名：
             本機輸入: Fade
             螢幕顯示: 編號：801 書名：Energetic,作者：WannaOne,分類：music,價格：900.0,狀態：0
                      編號：802 書名：Beautiful,作者：WannaOne,分類：music,價格：1500.0,狀態：0
                      編號：803 書名：I.P.U,作者：WannaOne,分類：music,價格：670.0,狀態：0
                      編號：804 書名：WW2,作者：Churchill,分類：history,價格：200.0,狀態：0
                      編號：805 書名：Egg100,作者：SuYuanMa,分類：cook,價格：720.0,狀態：0
                      編號：806 書名：ThreeLittlePig,作者：Provantini,分類：story,價格：150.0,狀態：0

        4.輸入指令"4"可修改圖書

             本機輸入: 4
             螢幕顯示: 請輸入要修改的書的編號：
             本機輸入: 804
             螢幕顯示: 請問要修改哪一部分的資料：
                      1) 編號
                      2) 書名
                      3) 作者
                      4) 價錢
                      5) 分類
                      6) 返回主菜單
             本機輸入: 2
             螢幕顯示: 請輸入新的書名：
             本機輸入: War2
             螢幕顯示: 修改成功！
                      編號：801 書名：Energetic,作者：WannaOne,分類：music,價格：900.0,狀態：0
                      編號：802 書名：Beautiful,作者：WannaOne,分類：music,價格：1500.0,狀態：0
                      編號：803 書名：I.P.U,作者：WannaOne,分類：music,價格：670.0,狀態：0
                      編號：804 書名：War2,作者：Churchill,分類：history,價格：200.0,狀態：0
                      編號：805 書名：Egg100,作者：SuYuanMa,分類：cook,價格：720.0,狀態：0
                      編號：806 書名：ThreeLittlePig,作者：Provantini,分類：story,價格：150.0,狀態：0
                      是否要繼續修改書的資料(y/n)?

              輸入y繼續修改圖書，n取消並返回主菜單。

        5.輸入指令"5"可查詢圖書

             本機輸入: 5
             螢幕顯示: 請輸入按哪種方法查找圖書：
                      1) 編號
                      2) 書名(精確查找)
                      3) 書名(模糊查找)
                      4) 作者
                      5) 分類
                      6) 價格
                      7) 返回主菜單

             本機輸入: 2
             螢幕顯示: 請輸入您要查找的書名：
             本機輸入: I.P.U
             螢幕顯示: 查找成功！您查找的結果為：
                      編號：803 書名：I.P.U 作者：WannaOne 分類：music 價格：670.0 狀態：0

             本機輸入: 3
             螢幕顯示: 請輸入您要模糊查找的書名：
             本機輸入: Pig
             螢幕顯示: 查找成功！您查找的結果為：
                      編號：806 書名：ThreeLittlePig 作者：Provantini 分類：story 價格：150.0 狀態：0

             本機輸入: 6
             螢幕顯示: 請輸入您要查找的書的價格的最低價：
             本機輸入: 500
             螢幕顯示: 請輸入您要查找的書的價格的最高價：
             本機輸入: 1000
             螢幕顯示: 查找成功！您查找的結果為：
                      編號：801 書名：Energetic 作者：WannaOne 分類：music 價格：900.0 狀態：0
                      編號：803 書名：I.P.U 作者：WannaOne 分類：music 價格：670.0 狀態：0
                      編號：805 書名：Egg100 作者：SuYuanMa 分類：cook 價格：720.0 狀態：0

        6.輸入指令"6"可清空圖書

             本機輸入: 6
             螢幕顯示: 清空成功！

        7.輸入指令"7"即登出管理員帳號

             本機輸入: 7
             螢幕顯示: 已登出
        
---
        
        8.使用者帳號註冊
        
          螢幕顯示: ----歡迎---
                   1) 使用者登入
                   2) 管理者登入
                   3) 註冊使用者帳號
                   4) 離開
          本機輸入: 3
          螢幕顯示: 請輸入你的學號 :
          本機輸入: 104303551
          螢幕顯示: 請輸入你的姓名 :
          本機輸入: Miao
          螢幕顯示: 請輸入你的帳號 :
          本機輸入: 123456
          螢幕顯示: 請輸入你的密碼 :
          本機輸入: 123456
          螢幕顯示: 註冊成功！
          
---       

        9.使用者登入
        
          螢幕顯示: ----歡迎---
                   1) 使用者登入
                   2) 管理者登入
                   3) 註冊使用者帳號
                   4) 離開
          本機輸入: 1
          螢幕顯示: 請輸入你的帳號 :
          本機輸入: 123456
          螢幕顯示: 請輸入你的密碼 :
          本機輸入: 123456
          螢幕顯示: 學號：104303551 姓名：Miao 帳號：123456 密碼：123456 目前借了多少書：0
                   登入成功！
                   ----使用者模式----
                   1) 顯示所有圖書
                   2) 查詢圖書
                   3) 借書
                   4) 還書
                   5) 預約書
                   6) 查詢帳號狀態
                   7) 登出帳號
          
          
          
          
          
