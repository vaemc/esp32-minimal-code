# esp32c2-ssd1306

ESP32C2 oled屏幕示例

# IDF版本
ESP-IDF v5.0.3-dirty

# 引脚
| SCL | SDA |
| --- | --- |
| 2   | 3   |

# 配置项
* 修改晶振频率为26 `idf.py menuconfig` -> `Component config` -> `Hardware Settings` -> `Main XTAL Config` -> `Main XTAL frequency` -> `26 MHz`

