# 狗狗行為模式辨識系統 - 系統環境圖

```mermaid
graph TD
    User[使用者]
    Camera[攝像頭設備] --> System[影像辨識系統]
    File[上傳的影片檔案] --> System
    System --> AI[行為辨識模型]
    AI --> Database[數據庫]
    AI --> Notification[通知系統]
    Notification --> User
    Database --> Analysis[行為數據分析]
    Analysis --> Report[報表生成]
    User -->|查看報表| Report
    System --> Cloud[雲端服務]
    Cloud --> Backup[數據備份系統]
