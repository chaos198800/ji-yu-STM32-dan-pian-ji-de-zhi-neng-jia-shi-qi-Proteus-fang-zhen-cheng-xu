# 基于STM32单片机的智能加湿器（Proteus仿真+程序）

## 项目简介

本项目是一个基于STM32单片机的智能加湿器设计，包含Proteus仿真文件和程序源码。该项目通过STM32F103单片机控制，结合DHT11温湿度传感器、1602液晶显示模块、声光报警模块和继电器模块，实现智能加湿功能。

## 功能描述

1. **主控制器**：采用STM32F103单片机作为主控制器。
2. **温湿度检测**：通过DHT11传感器实时测量环境的温度和湿度数据。
3. **数据显示**：使用1602液晶显示屏显示当前的温度和湿度。
4. **智能加湿**：通过三个按键设置湿度上限报警值，当湿度低于设定值时，蜂鸣器和LED会进行声光报警，并开启继电器进行加湿。
5. **Proteus仿真**：本项目支持Proteus 8.11版本的仿真，确保在仿真环境中能够正常运行。

## 文件结构

- **仿真文件**：包含Proteus仿真所需的电路图文件。
- **程序源码**：包含STM32单片机的程序源码，支持Keil5 MDK开发环境。

## 使用说明

1. **仿真运行**：在Proteus 8.11版本中打开仿真文件，加载程序源码，即可进行仿真运行。
2. **硬件搭建**：根据仿真电路图搭建实际硬件电路，并将程序烧录到STM32单片机中。
3. **功能测试**：通过按键设置湿度上限值，观察加湿器的工作状态和报警功能。

## 注意事项

- 本项目仅支持Proteus 8.11版本，其他版本可能无法正常运行。
- 在实际硬件搭建时，请确保电路连接正确，避免短路或损坏元器件。

## 贡献与反馈

欢迎对本项目提出改进建议或反馈问题，可以通过GitHub的Issues功能提交问题或建议。

## 许可证

本项目遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接和本声明。

## 下载链接

[基于STM32单片机的智能加湿器Proteus仿真程序](https://pan.quark.cn/s/cfbbf2b1c44e)