# 計畫任務 (排程)

<figure><img src="../../.gitbook/assets/image (78).png" alt=""><figcaption></figcaption></figure>

透過左側選單切換到排程頁面。

點擊創建排程

***

<figure><img src="../../.gitbook/assets/image (79).png" alt=""><figcaption></figcaption></figure>

排程時間可以參考以下範例或是打開下面的 顯示快速參考指令表

```
# 每天早上 8 點 30 分執行
30 08 * * *

# 每週日下午 6 點 30 分執行
30 18 * * 0

# 每週日下午 6 點 30 分執行
30 18 * *

# 每年 6 月 10 日早上 8 點 30 分執行
30 08 10 06 *

# 每月 1 日、15 日、29 日晚上 9 點 30 分各執行一次
30 21 1,15,29 * *

# 每隔 10 分鐘執行一次
*/10 * * * *

# 從早上 9 點到下午 6 點，凡遇到整點就執行
00 09-18 * * *
```

<figure><img src="../../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

創建後點擊新任務，在這裡設定你想執行的自動化



> 此文檔由 [亨](https://github.com/HansHans135/) 撰寫
