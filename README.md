# OLED_hal硬件I2C

移植的江科大OLED的硬件I2c版本，没有写测试函数，可自行测试，如果写的有测试文件，可提交pr

## 使用方式

先包含头文件

```
#include "OLED.h"
```
test
初始化

```
OLED_Init();
```

调用绘图函数和显示函数时需要更新

```
OLED_Update();
```
