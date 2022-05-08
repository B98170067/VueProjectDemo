# structure-project

## Frontend
### vueprojectdemo
 - services: 拆分出組件取得資料後的處理業務邏輯，讓邏輯容易被共用，也減少組件程式複雜度。
 - utils: 公用的工具方法。
 - router: 路由設定。
 - components: 組件程式，依功能再建子資料夾。
 - configs: 定義網站配置，環境變數、API網址等等。
 - constants: 程式中使用的常數
 - store: 狀態管理。
 - views: 主頁。

## BackEnd

### VueProjectDemoBeckend API專案
 - 接收請求，調用業務邏輯層

### VueProjectDemoBeckend.Service 業務邏輯
 - 取得資料後的處理。

### VueProjectDemoBeckend.Model
 - 定義資料傳輸物件、常數

### VueProjectDemoBeckend.Data
 - DBContext、實體資料模型、migrations

### VueProjectDemoBeckend.Utility
 - 擴充方法、共用方法

### VueProjectDemoBeckend.UnitTest
 - 單元測試

