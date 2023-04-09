## ergodashv99 via configuration使用說明

* 最近變動說明
  * 20230409
    * VIA configuartion更新到了3.0.0版。
    * 最近新版的 QMK firmware端把VIA custom keycode(USER00)改掉了，可能是改成CS00，但是這裡沒有測試成功，
      VIA和VIAL端也沒有做出變動，舊版的qmk v0.20.04的custom keycode依舊可在VIA 3.0.0正常使用，所以暫不使用新版QMK。
    * VIA網頁版都會用最新版本，所以有一天網頁版的custom keycode突然不能用了，那就是它對custom keycode最對應的更新了，
      此時若有急用可以先下載程式版的3.0.0應急。  



* 如果要讓trackpoint更容易使用，windows打開設定，滑鼠頁面，設定，這裡提供測試過比較好的參數，使用者也可以依需求自行調整。
  
  滑鼠速度:游標速度:6
  
  滾輪速度:選擇一次要捲動的行數:1(滾輪用這個會比較平滑)
  
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/setting.jpg)

* 先到 https://caniusevia.com/ 選擇download via下載via configuration。(網頁連結拿掉了)
  * 換這個 https://github.com/the-via/releases/releases/tag/v2.0.5
  * 或更新的 https://github.com/the-via/releases/releases/tag/v2.1.0
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0001.png)
  
  
* 會連結到github的via頁面，依照作業系統選擇版本，像是windows 10 就選 via-1.3.1-win.exe。

  ~~v1.3.1應該就是最後更新的版本了，以後也不太有可能更新了。~~(最近更新到2.0.5普通使用上沒區別)
  
  舊版的鍵盤firmware要使用via v1.3.1，因為原作者把下載關掉了，這裡備份
  
  https://github.com/ouser555/ergodashv99/releases
  
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0002.png)
  
  
* 下載安裝完成後打開via，選上方最右邊的菜單SETTINGS，把第一個選項show design tab打開。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0003.png) 
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0014.png) 
  

* 然後上方的菜單頁會多一個DESIGN，進入這個菜單，點擊Load載入設定檔。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0012.png)
  
  
* 選擇檔案ErgoDash_4key_2u_inner.json
  (檔案在(檔案在https://git.io/JDxnc)
  
  2022/5/4之後改版
  檔案改選ErgoDash_4key_2u_inner-remap.json
  
  如果你的鍵盤是Ergoknife，
  則是從這裡
  ~~[https://github.com/ouser555/ErgoKnife](https://github.com/ouser555/ErgoKnife)~~
  ~~https://github.com/ouser555/ErgoKnife/blob/main/via%20config/ErgoKnife-20230213.json~~
  https://github.com/ouser555/ErgoKnife/blob/main/via%20config/ErgoKnife-20230303.json
  
  下載 ErgoKnife.json 這個檔案  
  
  
  
  (下載方式:進入github連結後出現檔案列表，先按檔案，然後右邊上方有一個RAW按鈕，右鍵選擇另存連結為...)

  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0004.png)
  
  
* 設定檔載入完成後設這個畫面。

  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0015.png) 
  

* 上方菜單選擇CONFIGURE，如果設定成功的話可以看到正確辨識畫面。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0011.png)
  
  
* 上方菜單選擇KEYSTESTER，可以測試鍵盤輸入觸發是否正常。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0019.png)
  
  
* 在這個頁面也可以打開下方的Test Matrix可以更直觀的看見哪個按鍵被觸發。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0018.png)
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0010.png)
  

* 上方菜單選擇CONFIGURE，這是一般設定KEYMAP的頁面，這個程式的主要功能就是這個。

  選擇左方的SAVE+LOAD，選擇load saved layout
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0007.png)
  
     
* 選擇KEYMAP設定檔 ergodashv99 。
  
  (檔案在https://git.io/JDxnc)
  
  2022/5/4之後改版
  檔案改選ergodashv99-
  
  會依照檔案設定KEYMAP，如果之後有自己的配置也可以用save current layout把keymap保存起來。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0005.png)
  
  
* 左邊選單回到KEYMAP可以看到重新設定的按鍵映射，LAYER 0 (這裡也只是把右手邊最左邊的兩個鍵改成滑鼠左右鍵而已)。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0017.png)
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0020.png) 
  
  
* 最上方可以看到這裡原始設定只有四層鍵盤層 LAYER 0 1 2 3，普通狀態都在LAYER 0。
  
  LAYER 0 的名稱是 QWERTY
  
  LAYER 1 的名稱是 LOWER
  
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0013.png)
  
  
  LAYER 2 的名稱是 RAISE
  
  LAYER 3 的名稱是 ADJUST
  
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0009.png)
  

* 按著LOWER鍵就可以暫時切到LAYER 1層，此時輸入的鍵都是LAYER 1的配置，放開又回到LAYER 0。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0008.png)
  

* 按著RAISE鍵就可以暫時切到LAYER 2層，此時輸入的鍵都是LAYER 2的配置，放開又回到LAYER 0。
  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0016.png)
  

* 像是調整背光色相，調整V99的DPI，切換滾輪模式都是設定在LAYER 2，

  所以都是按RAISE鍵切到LAYER 2來操作，

  這就跟筆記型電腦的FN鍵是一樣的道理。
  
  RGB色相是HUE+ HUE-，切換滾輪模式是SCRLS SCRLM，切換DPI是DPIS DPIM，
  
  預設這些鍵都設定在LAYER 2的右下方區域。
  
  
  
* 也可以改這些V99控制鍵的KEYMAP，打開左邊最下方的CUSTOM選單可以看到這些KEYCODE，

  前4顆鍵是4個層，後4顆鍵是v99的DPI和滾輪切換。
  
  4個切換層鍵:
    * LAYER 0 的名稱是 QWERTY
    * LAYER 1 的名稱是 LOWER
    * LAYER 2 的名稱是 RAISE
    * LAYER 3 的名稱是 ADJUST
  
  4個V99功能鍵:
    * SCRLM 右邊的滾輪切換
    * SCRLS 左邊的滾輪切換    
    * DPIM  右邊的DPI切換
    * DPIS  左邊的DPI切換
    
   

  ![image](https://github.com/ouser555/ergodashv99/blob/main/ergodashv99via%E4%BD%BF%E7%94%A8%E8%AA%AA%E6%98%8E/0006.png)
  
  
* VIA的KEYMAP設定是跟著安裝VIA的電腦的，

  如果鍵盤要拿到其他電腦操作也是要經過相同的設定才可以轉移KEYMAP，
  
  不然就只能使用預設的KEYMAP。
  

* 關於VIA的其他設定可以自己測試看看。
