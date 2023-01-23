## QMK TOOLBOX燒錄教學



### 1. QMK Toolbox下載

* 到 https://github.com/qmk/qmk_toolbox/releases 下載最新版本，可以選擇install.exe安裝版或是.exe直接執行版，範例選擇直接執行版
![image](https://github.com/ouser555/ergodashv99/blob/main/QMKToolbox/pic/chrome_eDgEPXTqOD.png)

### 2. 打開QMK Toolbox

![image](https://github.com/ouser555/ergodashv99/blob/main/QMKToolbox/pic/explorer_IltXWZmTo1.png)

如圖所示做一樣的設定

1.右上的open選擇要使用的燒錄檔

2.Auto-Flash打勾

3.MCU(AVR Only)選擇Atmega32u4

![image](https://github.com/ouser555/ergodashv99/blob/main/QMKToolbox/pic/qmk_toolbox_NdcRWePXHe.png)

1.將Arduino ProMicro接上電腦的USB。

2.使用聶子或其他可以導電的物體，短接右邊的第2隻腳與第3支腳，觸發硬體RESET，就會開始燒錄。
  * 有些Promico必須要連續觸發兩次RESET，才會開始燒錄。

![pro_micro_pinout](https://user-images.githubusercontent.com/95702400/145521171-3f43e472-40c0-441b-bc69-28e8c52dca2d.jpg)

3.如果你的promicro已經組裝在鍵盤上，按上方邊緣的reset按鍵，即可觸發硬體RESET，即可開始燒錄。
  * 有些Promico必須要連續觸發兩次RESET，才會開始燒錄。
