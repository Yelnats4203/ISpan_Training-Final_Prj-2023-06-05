# Yelnats4203-ISpan_Training-Final_Prj-2023-06-05
資展國際【軟體測試工程師養成班】期末結訓專題-電影購票網站(僅有code)

專題發表demo連結：https://youtu.be/_xE3ThtLsqs?t=4056

主要負責功能為後台管理系統：電影新增、刪除、修改；場次新增、修改；統計(首頁DashBoard及會員、客訴統計)

網站整體以.NET Core MVC完成

資料庫使用MS SQL，專案中使用EntityFrameWork

除切換不同功能的頁面外，整體網頁基本以Ajax非同步完成

依Models、Views、Controllers、ViewModels資料夾分類，另有hubs為後台DashBoard使用SignalR完成即時檢視前台線上使用人數)

Models

(未附上由EntityFramework生成的DB Model)

Views

Shared/BackLayout：後台共用Layout

BackLogIn：從前台登入後台管理系統頁面：

DashBoard：後台首頁DashBoard

movieBack：電影管理頁面

SessionBack：場次管理頁面

Statistics：會員及客訴統計頁面

Controllers

BackLogInController、BackSuperController：後台登入

DashBoardController：後台首頁DashBoard

movieBackController：電影新增、刪除、修改

SessionBackController：場次新增、修改

StatisticsController：會員、客訴統計

Hubs(前台及後台用)



