使用方式：
（1）你需要擁有一個cloudflare賬戶和自有域名；
（2）部署項目：
    登錄coudflare儀表板，按下步操作：
       1.首頁->計算和AI->works和pages->建立應用程式->works->從 Hello World 開始!->開始使用->部署->編輯代碼
       2.將works.js粘貼進代碼編輯區->部署
       3.訪問系統分配的域名：https://你的項目域名.works.dev/?list=true獲取播放列表
（3） 綁定域名：
     返回此works項目首頁，設定->網域和路由->新增->自定義網域->輸入自定義域名->部署
     訪問https://your-domin/?list=true


説明：
1.通過cloudfalre cdn反向代理實現播放
2.代碼已做混淆處理，防止被cloudflare封殺，如有不滿，請繞路
3.免費賬戶使用works，每天有100000次請求數，部署本項目個人使用實測24小時不間斷播放，約消耗70000次請求數。
       
