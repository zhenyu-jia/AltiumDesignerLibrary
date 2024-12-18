# Altium Designer Component Library
目前只搭好了框架，后续更新

# 电子元件库

这是一个组织良好的电子元件PCB（印刷电路板）和原理图文件库，包含了各种常用电子元件的设计文件。

## 目录结构

```
AltiumDesignerLibrary\ComponentLibrary.
├─01_Resistors
│      FixedResistors.PcbLib
│      FixedResistors.SchLib
│      Thermistors.PcbLib
│      Thermistors.SchLib
│      VariableResistors.PcbLib
│      VariableResistors.SchLib
│
├─02_Capacitors
│      CeramicCapacitors.PcbLib
│      CeramicCapacitors.SchLib
│      ElectrolyticCapacitors.PcbLib
│      ElectrolyticCapacitors.SchLib
│      TantalumCapacitors.PcbLib
│      TantalumCapacitors.SchLib
│
├─03_Inductors
│      FerriteBeads.PcbLib
│      FerriteBeads.SchLib
│      FixedInductors.PcbLib
│      FixedInductors.SchLib
│      VariableInductors.PcbLib
│      VariableInductors.SchLib
│
├─04_Diodes
│      LEDs.PcbLib
│      LEDs.SchLib
│      RectifierDiodes.PcbLib
│      RectifierDiodes.SchLib
│      SchottkyDiodes.PcbLib
│      SchottkyDiodes.SchLib
│      ZenerDiodes.PcbLib
│      ZenerDiodes.SchLib
│
├─05_Transistors
│      BJTs.PcbLib
│      BJTs.SchLib
│      IGBTs.PcbLib
│      IGBTs.SchLib
│      MOSFETs.PcbLib
│      MOSFETs.SchLib
│
├─06_Crystals
│      Crystals.PcbLib
│      Crystals.SchLib
│
├─07_ICs
│  ├─Analog
│  │      DataConverters.PcbLib
│  │      DataConverters.SchLib
│  │      OpAmps.PcbLib
│  │      OpAmps.SchLib
│  │      VoltageRegulators.PcbLib
│  │      VoltageRegulators.SchLib
│  │
│  └─Digital
│          FPGAs.PcbLib
│          FPGAs.SchLib
│          LogicGates.PcbLib
│          LogicGates.SchLib
│          Memories.PcbLib
│          Memories.SchLib
│          Microcontrollers.PcbLib
│          Microcontrollers.SchLib
│
├─08_Connectors
│      Headers.PcbLib
│      Headers.SchLib
│      RFConnectors.PcbLib
│      RFConnectors.SchLib
│      Sockets.PcbLib
│      Sockets.SchLib
│      Terminals.PcbLib
│      Terminals.SchLib
│      USBConnectors.PcbLib
│      USBConnectors.SchLib
│
├─09_Switches
│      PushButtons.PcbLib
│      PushButtons.SchLib
│      RotarySwitches.PcbLib
│      RotarySwitches.SchLib
│      ToggleSwitches.PcbLib
│      ToggleSwitches.SchLib
│
├─10_Transformers
│      PowerTransformers.PcbLib
│      PowerTransformers.SchLib
│      SignalTransformers.PcbLib
│      SignalTransformers.SchLib
│
└─11_Miscellaneous
        Miscellaneous.PcbLib
        Miscellaneous.SchLib
```

## 各类别详细说明

### 1. 电阻

- 固定电阻
- 热敏电阻
- 可变电阻

### 2. 电容

- 陶瓷电容
- 电解电容
- 钽电容

### 3. 电感

- 铁氧体磁珠
- 固定电感
- 可变电感

### 4. 二极管

- LED（发光二极管）
- 整流二极管
- 肖特基二极管
- 齐纳二极管

### 5. 晶体管

- 双极性结型晶体管（BJTs）
- 绝缘栅双极型晶体管（IGBTs）
- 金属氧化物半导体场效应晶体管（MOSFETs）

### 6. 晶振

- 晶体

### 7. 集成电路（ICs）

- **模拟：**

  - 数据转换器

  - 运算放大器

  - 稳压器

- **数字：**

  - 可编程逻辑阵列（FPGAs）

  - 逻辑门

  - 存储器

  - 微控制器

### 8. 连接器

- 排针
- 射频连接器
- 插座
- 端子
- USB连接器

### 9. 开关

- 按钮开关
- 旋转开关
- 拨动开关

### 10. 变压器

- 电源变压器
- 信号变压器

### 11. 其他

- 其他元件

## 使用说明
请根据需要浏览和使用各类别下的文件。这些文件可以直接导入到您的设计软件中以供使用。

## 贡献
欢迎对本库进行贡献。如果您有新的元件文件，请提交Pull Request并遵循本库的贡献指南。

---

希望这个README文档对你有帮助！如果你有任何其他需求，请告诉我。
