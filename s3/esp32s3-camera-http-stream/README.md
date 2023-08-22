# esp32c2-2m-ota

ESP32S3 HTTP摄像头流

# IDF版本
ESP-IDF v5.0-beta1-799-g20949d444f

# 配置项

* 连接wifi `idf.py menuconfig` -> `Example Connection Configuration` -> `WiFi SSID` & `WiFi Password`
* 开启PSRAM `idf.py menuconfig` -> `Component config` -> `ESP PSRAM` -> `Support for external, SPI-connected RAM` -> `SPI RAM config` -> `Mode` -> `Octal Mode PSRAM`
