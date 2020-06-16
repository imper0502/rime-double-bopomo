# 雙碼注音
## 簡介
  給注音使用者的雙拼輸入法。不需要額外學習漢語拼音。

## 鍵位圖
  ![KB layout](https://github.com/imper0502/double-bopomo/blob/master/double_bopomo_keyboard_layout.jpg)

## 說明
  目前，這是一個 Rime 輸入法引擎與 cin 碼表的輸入方案，需要安裝以下任何一款 Rime 輸入法（推薦）或其他可讀 cin 碼表的輸入法，方可使用：

### Rime 輸入法列表   
  - 小狼毫（官方，Windows）
  - Prime（Windows）
  - 鼠鬚管（官方，macOS）
  - XIME（macOS）
  - ibus-rime（Linux，官方，推薦）
  - Fcitx-rime（Linux，推薦）
  - 同文輸入法（Android）
  - iRime（iPhone, iOS）

### 規則   
  1. 兩碼一字：第一碼聲母，第二碼韻母。（第三碼可用數字１～５輸入聲調，第三碼非必要，可省略）
  2. 虛韻母：ㄓㄔㄕㄖ　ㄗㄘ厶  這些可以獨存的聲母（其實是韻母省略）要多打一個虛韻母「ㄭ」在後，ㄭ放在I鍵上，用 emoji: 😬 表示，因爲發音時嘴形類似。
  3. 零聲母：所有的韻母都可以獨存 ㄧㄨㄩ ㄚㄛㄜㄝ ㄞㄟㄠㄡ ㄢㄣㄤㄥ 及兒化音 ㄦ，多打一個零聲母「Ø」在前，零就是沒有，零聲母表示沒有聲母，Ø放在E鍵上，用◌表示。
 
  如此，所有的注音符號音節（但不包括尖團音），全部編碼成兩碼了。
  另外，目前是12345輸入聲調，但聲調不是必要的；67890選字。此外，ㄗ放 W的設計，參考了法語鍵盤。
 
### 簡拼規則
  1. 聲母（ㄅㄆㄇ…）+ 聲調（數字１～５）；所以改用６～０選字（預設一頁五字）
  2. 聲母（ㄅㄆㄇ…）+ 分詞鍵【'】（分號鍵的右邊）；若【'】有設定額外功能，則會衝突不可使用。

## 相關連結
  [PTT發佈頁、討論頁](https://www.ptt.cc/bbs/IME/M.1572622340.A.FEA.html)

## 使用截圖
  ![Heatmap](https://imgur.com/UUiUJxB.jpg)
  ![使用 fcitx-rime on kde](https://imgur.com/DS9ZpnG.jpg)
  ![使用同文輸入法 on Android](https://i.imgur.com/9hi4wRF.jpg)
  ![使用 iRime on iOS](https://i.imgur.com/oPuEzOj.jpg)
