# iotgw-thingspeak

IoT Gateway system

[Sensor]-----[GW(ESP32C3)]-----[ThingSpeak]
SCD41

機能
- 室内の温湿度、CO2濃度をSensirion SCD41で計測、ESP32C3経由でThingSpeakにMQTTでPublishする<br>
- ESP32C3をIoT Gatewayとして使用、Rustによるプログラミング

補足
- ThingSpeakに接続してグラフ表示するスマフォアプリを使うことで、スマフォから温湿度、CO2濃度が確認可能

files:
