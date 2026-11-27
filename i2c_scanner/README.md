## 2026年11月27日 — ESP32とADXL345のI2C通信

### 1. 目的
ESP32と加速度センサーADXL345を接続し、I2C通信が正常に行われるか確認

### 2. 実施内容
・I2C scanner を作成して接続されているデバイスのアドレスを探索した

### 3. 発生した問題
通信時にerror code 2が発生して加速度センサーを認識できなかった

### 4. 原因と解決方法
配線の確認とCS,SDOの役割を調べた
### 5. 実験結果
ADXL345の認識に成功した

<img width="2866" height="1776" alt="スクリーンショット 2026-11-27 171139" src="https://github.com/user-attachments/assets/31ae908c-959a-4064-9ab2-0044231ee820" />
<img width="2876" height="1776" alt="スクリーンショット 2026-11-27 174434" src="https://github.com/user-attachments/assets/43ec33ec-01c4-4ede-8be8-6ac3d0274887" />

### 6. 学んだこと・考察
I2C通信の基本的な仕組み
SDAとSCLの役割
I2Cアドレスの仕組み
エラーコードを利用した原因調査
### 7. 次回の目標
ADXL345から3軸の加速度データを取得
