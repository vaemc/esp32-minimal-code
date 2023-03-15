# esp32c2-2m-ota

2m flash大小的ESP32C2 OTA升级示例

# IDF版本
ESP-IDF v5.1-dev-3888-g47852846d3

# 配置项

* 连接wifi `idf.py menuconfig` -> `Example Connection Configuration` -> `WiFi SSID` & `WiFi Password
* OTA地址为http的情况下需要启用 `idf.py menuconfig` ->`Component config`->`ESP HTTPS OTA`->`Allow HTTP for OTA` enable
* 自定义分区表  `idf.py menuconfig` -> `Partition Table ` -> `Custom partition table CSV` <- `Custom partition CSV file` -> `partitions_2m.csv`
