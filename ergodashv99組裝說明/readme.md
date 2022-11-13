## ergodash v99 組裝說明

## 因為這完整的套件都是經過測試的，所以這套件在設計上應該是不會有奇怪的問題。
## 組裝焊接的工作原本就是依照各人熟悉度不同會有各種不同的結果。
## 如果您對技能不是非常有自信，也可以請有技術的朋友代為進行組裝工作。
## 如果你是第一次組裝類似套件，請詳細參照說明進行操作。
## 如果Arduino板焊接步驟錯誤，排針解焊會非常麻煩，請務必小心。

* !

## 剛開始拿到套件時可以先清點一下零件
* 鍵盤PCB *2
* Arduino ProMicro Type-C *2 (建議先燒好Ergodash程式)
* 排針 2組 *4(Arduino promicro會附)
* V99模組 *2
* 壓克力 *2組 (左右共6片)
* m2*6mm銅柱 *16
* m2*5mm螺絲 *26
* m2*8mm螺絲 *6
* 可插拔針座
  * 12px1 3.5mm *4
  * 2px1 *4
  * 2px2 *4
  * 3px2 *2 
* ~~電阻 * 70(沒有單色LED這個功能，零件不會附上)~~
* 二極體 *70
* ~~LED *70(沒有單色LED這個功能，零件不會附上)~~
* RGB LED *24
* TRRS線 *1 
* !
* ~~已在PCB上先行焊上零件，不在清單中~~
* 其他零件
  * reset鍵 *2
  * TRRS座 *2
  * ~~BACKLIGHT電阻(沒有單色LED這個功能，零件不會附上)~~
  * ~~V99模組排阻(已改成JUMPER了)~~

## 先測試~~自製~~Arduino ProMicro是否可以正常動作

1.到以下網址下載燒錄檔
https://github.com/ouser555/qmk_firmware/blob/master/keyboards/ergodash/keymaps/v99v3/hex/ergodash_rev1_v99v3.hex

滑鼠游標到網頁右邊的RAW上按右鍵，選擇另存連結。(只能這樣下載燒錄檔，用其他方式會下載到無法使用的檔案)

2.燒錄方式
https://github.com/ouser555/ergodashv99/blob/main/QMKToolbox/readme.md


![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/23.jpg)

如圖插上USB，電腦是可以辨識到ergodash鍵盤的，確認無誤後再繼續之後的步驟，如果有狀況，請不要繼續，先連絡支援。

兩片Arduino ProMicro都燒同一個燒錄檔。

~~因為通常都會先燒錄程式，測試好再出貨，所以拿到應該是不會有問題的。~~

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/00.jpg)

左右各~~35個電阻~~、35個二極體、12個RGB燈先焊上如圖所示，二極體有方向注意不要弄反。

~~鍵盤PCB上的零件面已經有先焊上部分零件了，應該不會搞錯。(未焊上)~~

RGB LED的缺角pin為接地腳，對應到PCB上的G腳位。


![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/01.jpg)

前一步驟零件全焊部好了之後，先放排針上PCB(不要焊)，之後請照步驟執行，不然弄錯會非常非常非常難解決。

排針兩排之外還有2pin，這裡注意都要裝上。

(新版本請看hotswap的說明，若喜歡焊死的方式也可以繼續往下操作)
https://github.com/ouser555/ergodashv99/blob/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/Arduino%20hotswap/readme.md

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/02.jpg)

### 把Arduino ProMicro對上，可以平貼，這裡千萬不要不要不要焊上去，只是拿來定位而已。

放Arduino的位置應該不會弄錯，因為另一邊已經放上reset按鍵了，沒辦法放錯誤的那邊。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/03.jpg)

把鍵盤PCB反過來，進行焊接，這裡只在鍵盤電路板上焊上排針，沒有要焊其他的東西了。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/04.jpg)

焊好如圖。 然後把Arduino板拿開。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/05.jpg)

先在壓克力上鎖好6mm銅柱，全部用5mm(較短的)螺絲。

壓克力的保護膜在這個階段可以先把它都撕掉了。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/06.jpg)

把軸體裝上壓克力，這裡塞的時候請小心不要壓破壓克力。有四顆軸體先不要裝，如圖所示。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/07.jpg)

這裡有一顆斜放的軸體注意它針腳的位置。檢查所有針腳都沒有彎曲。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/08.jpg)

全部裝好之後闔上PCB。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/09.jpg)

正確無誤的話距離如圖所示。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/10.jpg)

確定固定好沒有縫隙後可以開始焊上軸體。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/11.jpg)

這裡補充說明，這個鍵盤的拇指區"正方形的位置"可以自由配置"3個按鍵"，只有3個，不能放4個。

請依照圖式選擇要擺放的位置。

![image](https://github.com/omkbd/picture/blob/master/ergodash-layout.png)

把決定好位置剩下4個軸體也焊上。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/12.jpg)

拿出排針座。
  * 6x1
  * 4x2
  * 2x2

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/13.jpg)

先放上孔位，不要焊上。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/14.jpg)

拿出trackpoint模組。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/15.jpg)

插上用來定位。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/16.jpg)

確定針腳都沒有跑掉。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/17.jpg)

焊上。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/18.jpg)

~~這是軸體的LED，雖然有附上，但是程式因為加了trackpoint功能，所以沒有更多的空間了，所以這LED是沒有功能的。要不要焊上看各人。~~

~~這時候不焊上的話，放上Arduino板後就有兩個軸體再也裝不了LED了，這裡可以先考慮好。~~

~~燒原版的ergodash的程式這LED應該是可以動作的，但是還差一個零件，名稱是IRLML6344TRPbF，要讓它動的話請自行再補。~~

(沒有單色LED這個功能，零件不會附上)

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/19.jpg)

現在把Arduino板放上。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/20.jpg)

這裡會建議焊之前先把針腳先剪了，這樣安裝會比較平整，也比較好看。

要小心針腳飛噴，可以拿張衛生紙揉成球來遮擋。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/21.jpg)

剪到底。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/22.jpg)

焊上。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/24.jpg)

全部焊完看起來是這樣。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/25.jpg)

接下來是左右手的供電JUMP選擇，依下圖上焊錫。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/29.jpg)

請依照上圖焊JUMP，下圖只是為了指出JUMP在PCB的位置，JUMP焊法不一樣。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/30.jpg)

#### Trackpoint正反面的JUMPER，跟放置零件的面是同一面，六個點都焊起來，這因為圖是舊版的PCB，拿到的PCB的JUMPER位置在稍微下方一點。
![image](https://github.com/ouser555/ergodashv99/blob/main/rev2%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/piiic%20(30).jpg)

然後可以先接上電腦的USB，RGB此時應該會被點亮，如果有沒亮的，檢查看看LED有沒有焊對方向。

按按看trackpoint可不可以正常動作，如果不行，也要再檢查上述步驟有沒有什麼地方沒有焊對。

附上關於V99模組的線路圖

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/32.jpg)


檢查動作無誤後，闔上下蓋的壓克力。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/26.jpg)

拿5mm(短)的螺絲鎖下面5個(最右邊還有1個螺絲，拍照沒拍到)。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/27.jpg)

蓋上小片壓克力，鎖上8mm(長的)螺絲。

![image](https://raw.githubusercontent.com/ouser555/ergodashv99/main/ergodashv99%E7%B5%84%E8%A3%9D%E8%AA%AA%E6%98%8E/pic/28.jpg)

最後黏上矽膠腳墊。

這樣就完工了。

幫兩邊鍵盤接上TRSS線，預設是左手鍵盤為主鍵盤，用左手鍵盤接電腦USB即可。

之後就可以到VIA使用說明進行操作
https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/README.md

