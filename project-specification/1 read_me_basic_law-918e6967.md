<!-- headings -->

# 一. RBAS 根區塊鏈工作組 規範基本法

由區塊鏈技術管理 date:
v0.1 2020-01-29 hash 0108bb77
v0.2 2020-02-24 hash 8e966db8
v0.3 2020-02-29

## 1. 成立宗旨

1. 以區塊鏈技術，建立一個可以兼容全部在互聯網上的交易的認証服務。
1. 分散獨立根系統服務 - 由 3-9 個獨立，非盈利，具公信力的機構組成。
1. 必需以最大限度保障私隱的方式，進行並完成整個認証操作。
1. 必需利用最低資源，達到接近免費向用戶提供服務。

## 2. 工作組管理

1. 全部內容由根區塊鏈工作室管理委員會負責決議制訂文案管理。
1. 全部文案由原始哈希碼，按區塊鏈，接連/分叉產生、更新。
1. 需要2/3 以上的常務委員出席，才能開會有效。
1. 本基本法，必須由 3/4 以上的參加開會常務委員通過，才能更改。

## 3. 開源/專利

1. 全部系統規範、軟件、硬件，在完成測試后，按管理委員決定，以開源方式公布使用。
1. 按管理委員決定，可申請相關專利，維護本工作組權益。
1. 設計，發明，專利等各項權益的維護和利用，由管理委員通過會議決定。

## 4. 管理系統包括

1. 系統規範，結構，操作等文案。
1. 系統內的全部硬件如服務器，儀表，資料庫等設計資料。
1. 所有軟件包括系統軟件，應用軟件，測試軟件。
1. 所有賬號如操作員，用戶資料，數據庫內容。

# 二. RBAS 四類成員、責任、權利

## 1. RBAS 工作室委員

1. 組成 - 由創始人召集，成立。按規範基本法持續。
1. 責任 - 維持 RBAS 運作。
1. 權利 - 維護、修正、運作 RBAS 基本法內容。提名和批准 RS 成員。最多 9 個。並可以按協議收費。

## 2. RS 根服務器成員

1. 基本組成 - 由工作室管理委員按規範基本法成立。

   1. 責任 - 成立 QS, DB_T, DB_C 以維持 本 RS 系統運作。向上級按協議交費。
   1. 權利 - 按基本法內容。提名和批准 PS 成員。最多 1000 個。並可以按協議收費。

1. RS 系統 成員
   1. QS - 查詢服務器, 向公眾開放，查詢交易哈希。
   1. DB_T - 時分交易哈希碼庫，按心跳週期，存檔作備份、同步用。
   1. DB_C - 碼分交易哈希碼庫，接哈希碼分散存檔，作快速查詢用。

## 3. PS 打包服務系統

PS - 組合服務器, 經 RS 管理成立

1. 責任 - 管理本分支交易哈希碼，向全系統 DB_T, DB_C 存檔。向上級按協議交費。
1. 權利 - 管理成立 TS-交易服務器。最多 1000 個。並可以按協議收費。

## 4. TS 交易服務器

TS - 交易服務器, 經 PS 管理成立。

1. 責任 - 管理具體交易，產生正確哈希碼，向 PS 存檔。向上級按協議交費。
1. 權利 - 按服務發展用戶。並可以按各自協議收費。