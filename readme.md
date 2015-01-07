## Raspberry Piで
## 気温を知らせるTwitter Botをつくる

---
## 自己紹介

![Weed](image/weed.jpg)　植田達郎（@weed_7777）

- フリーランス
    - JavaScript
    - 物理教材ビデオ作成
- 趣味
    - 歴史、城巡り

---
## 温度センサ

![LM35](image/LM35.jpg)

- 120円

---
## 温度の測り方

![LM35-pin](image/LM35-pin.png)

- 摂氏（℃）に比例した電圧出力
    - 例
        - ０℃→０Ｖ
        - ２０℃→２００ｍＶ
- 要は、電圧を測れば、温度がわかる

---
## Arduino

![ArduinoUno_R3_Front-resized](image/ArduinoUno_R3_Front-resized.jpg)

- 電圧を測る
- 3000円

---
## 電圧を測る

![ArduinoUno_R3_Front-analogpin](image/ArduinoUno_R3_Front-analogpin.jpg)

- Arduinoには電圧を測ることができるピンが6つある

---
## ブレッドボード

![bread-board](image/bread-board.gif) ![bread-board-connect](image/bread-board-connect.gif)

- 温度センサとArduinoをつなぐために使う
- 内部が右図のように導通している

---
## 温度センサを配置する

![LM35-on-breadboard](image/LM35-on-breadboard.JPG)

- こんな感じに刺します

---
## 配線する

![wiring](image/wiring.JPG)

- こんな感じにつないでいきます

