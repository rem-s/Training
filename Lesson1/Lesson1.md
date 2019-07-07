# Lesson1

## 目標  
MBEDを理解する

### MBED
エンベッドと発音する。
#### 外見的特徴  
- Switch : RESET用
- On Board LED : DEBUG用に4つ搭載
- USB PORT : USB通信用ポート

#### ハードウェア特徴
- 基準動作電圧が3.3V
- GPIOが25ピン
- アナログ出力が1ピン、アナログ入力が6ピン
- PWM出力が6ピン
- シリアル通信プロトコル(SPI, UART, I2C)
- 1ピンあたり40mA出力以下、全体で400mA以下

#### ソフトウェア特徴
- ブラウザ開発でのC言語での開発
- MBED OSが搭載されている
  - 抽象化されたAPI

#### ピンレイアウト
- GPIO : デジタル入出力
- GND : GNDピン
- VOUT : MBED基準電圧出力
- VIN : MBED動作入力電圧(4.5v - 9.0v)
- VU : USB電圧出力(5.0v)
- Analogin : アナログ入力
- Analogout : アナログ出力
- PWMOut :PWM波出力
- その他シリアル通信 : CAN, UART, I2C, SPI

<img src="../img/MBED.PNG" width="640px">    
