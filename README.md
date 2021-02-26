# reservationSystem
社交ダンス教室向けの予約管理システムです。This is a reservation system for ballroom dancers &amp; studios. FREE &amp; OSS.


## 要件
予約・キャンセル・変更が出来る
メール通知機能
複数人対応
印刷機能（日別・人別）
Google Calendarと連動


## 実装
・アカウント管理→データベース?
　　　教師（スタジオ）アカウント
        {
          name,
          availableDate[],
          reservedDate[],

        }

　　　生徒アカウント
        {
          name,
          
        }

・Google Calendar連動
　　　API Fetch & POST?
・
