# Xilinx Zynq UltraScale+ MPSoC AI智能识别 FPGA核心板 XCZU2CG

## 产品简介

AXU2CGA/B 的特点是体积小并扩展了丰富的外设。主芯片采用 Xilinx 公司的 Zynq 
UltraScale+ MPSoCs CG 系列的芯片，型号为 XCZU2CG-1SFVC784E。AXU2CGA 的 PS
端挂载了 2 片 DDR4（共 1GB，32bit）和 1 片 256Mb 的 QSPI FLASH。AXU2CGB 的 PS
端挂载了 4 片 DDR4（共 2GB，64bit），1 片 8GB eMMC FLASH 存储芯片和 1 片 256Mb
的 QSPI FLASH。  
外围接口包含 1 个 MINI DP 接口、4 个 USB3.0 接口、1 路千兆以太网接口、1 个 USB
串口、1 路 PCIE 接口、1 路 TF 卡接口、2 个 40 针扩展口、2 路 MIPI 接口和按键 LED。  

### 开发系统结构示意图

![图片](H:/test/structure.png)

## 主要特性

 XCZU2CG-1SFVC784E芯片的PS系统PS系统集成了2个ARM Cortex™-A53处理器，
速度高达 1.2Ghz，支持 2 级 Cache; 另外还包含 2 个 Cortex-R5 处理器，速度高达 500Mhz。
XCZU2CG 支持 32 位或者 64 位的 DDR4，LPDDR4，DDR3,DDR3L, LPDDR3 存储芯
片，在 PS 端带有丰富的高速接口如 PCIE Gen2, USB3.0, SATA 3.1, DisplayPort；同时另外也支持 USB2.0，千兆以太网，SD/SDIO，I2C，CAN，UART，GPIO 等接口。PL 端内部含
有丰富的可编程逻辑单元，DSP 和内部 RAM。

### XCZU2CG 芯片的总体框图

### PS部分的主要参数

<table>
    <tr>
        <td>处理器</td>
        <td>ARM 双核 Cortex™-A53 处理器，速度高达 1.2GHz，每个 CPU 32KB 1 级指令和数据缓存，1MB 2 级缓存 2 个 CPU 共享  ARM 双核 Cortex-R5 处理器，速度高达 500MHz，每个 CPU 32KB 1 级指令和数据缓存，及 128K 紧耦合内存</td>
    </tr>
    <tr>
        <td>外部存储接口</td>
        <td>支持 32/64bit DDR4/3/3L、LPDDR4/3 接口</td>
    </tr>
    <tr>
        <td>静态存储接口</td>
        <td>支持 NAND, 2xQuad-SPI FLASH</td>
    </tr>
    <tr>
        <td>高速连接接口</td>
        <td>支持 PCIe Gen2 x4, 2xUSB3.0, Sata 3.1, DisplayPort, 4x Tri-mode Gigabit Ethernet</td>
    </tr>
    <tr>
        <td>普通连接接口</td>
        <td>2xUSB2.0, 2x SD/SDIO, 2x UART, 2x CAN 2.0B, 2x I2C, 2x SPI, 4x 32b GPIO</td>
    </tr>
    <tr>
        <td>电源管理</td>
        <td>支持 Full/Low/PL/Battery 四部分电源的划分</td>
    </tr>
    <tr>
        <td>加密算法</td>
        <td>支持 RSA, AES 和 SHA</td>
    </tr>
    <tr>
        <td>系统监控</td>
        <td>10 位 1Mbps 的 AD 采样，用于温度和电压的检测。</td>
    </tr>
</table>

### PL部分的主要参数

<table>
    <tr>
        <td>逻辑单元 Logic Cells</td>
        <td>103K</td>
    </tr>
    <tr>
        <td>触发器(flip-flops)</td>
        <td>94K</td>
    </tr>
    <tr>
        <td>查找表 LUTs</td>
        <td>47K</td>
    </tr>
    <tr>
        <td>Block RAM</td>
        <td>5.3Mb</td>
    </tr>
    <tr>
        <td>时钟管理单元（CMTs）</td>
        <td>3</td>
    </tr>
    <tr>
        <td>乘法器 18x25MACCs</td>
        <td>240</td>
    </tr>
</table>

###功能和接口部分参数

<table>
    <tr>
        <td>QSPI Flash</td>
        <td>1片256Mbit QSPI FLASH, 可用作 FPGA 用户数据的存储</td>
    </tr>
    <tr>
        <td>EMMC Flash</td>
        <td>8GB，在 ZYNQ 系统使用中，可以作为系统大容量的存储设备</td>
    </tr>
    <tr>
        <td>扩展口</td>
        <td>4路120针0.5mm间距扩展口，接松下高速工业级板对板连接器</td>
    </tr>
    <tr>
        <td>晶振</td>
        <td>"1个单端 33.333MHz 晶振提供给 PS 系统</td>
    </tr>
    <tr>
        <td>1差分 200MHz 晶振提供给 PL 逻辑、 DDR4 参考时钟"</td>
    </tr>
</table>

## 产品图片

![图片](https://www.alinx.com/upload/image/20220818/ACU2CG.jpg)

## 对应开发板

### AXU2CG-E

![图片](https://www.alinx.com/upload/image/20220818/AXU3EG-750.jpg)    

### 产品链接

<https://www.alinx.com/detail/223>

## 结构尺寸图

## 参考资料层次



## 官方网站

<https://www.alinx.com/detail/287>



