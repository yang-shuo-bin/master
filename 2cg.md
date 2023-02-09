# Xilinx Zynq UltraScale+ MPSoC 系列核心板 

***

## 主要内容

### 核心板介绍

### 芯片参数

### 参考资料层次

### 官方网站

***

## 核心板介绍

### AXU2CG

#### 产品简介

AXU2CGA/B 的特点是体积小并扩展了丰富的外设。主芯片采用 Xilinx 公司的 Zynq 
UltraScale+ MPSoCs CG 系列的芯片，型号为 XCZU2CG-1SFVC784E。AXU2CGA 的 PS
端挂载了 2 片 DDR4（共 1GB，32bit）和 1 片 256Mb 的 QSPI FLASH。AXU2CGB 的 PS
端挂载了 4 片 DDR4（共 2GB，64bit），1 片 8GB eMMC FLASH 存储芯片和 1 片 256Mb
的 QSPI FLASH。  
外围接口包含 1 个 MINI DP 接口、4 个 USB3.0 接口、1 路千兆以太网接口、1 个 USB
串口、1 路 PCIE 接口、1 路 TF 卡接口、2 个 40 针扩展口、2 路 MIPI 接口和按键 LED。  

#### XCZU2CG芯片主要特性

 XCZU2CG-1SFVC784E芯片的PS系统集成了2个ARM Cortex™-A53处理器，
速度高达 1.2Ghz，支持 2 级 Cache; 另外还包含 2 个 Cortex-R5 处理器，速度高达 500Mhz。
XCZU2CG 支持 32 位或者 64 位的 DDR4，LPDDR4，DDR3,DDR3L, LPDDR3 存储芯
片，在 PS 端带有丰富的高速接口如 PCIE Gen2, USB3.0, SATA 3.1, DisplayPort；同时另外也支持 USB2.0，千兆以太网，SD/SDIO，I2C，CAN，UART，GPIO 等接口。PL 端内部含
有丰富的可编程逻辑单元，DSP 和内部 RAM。

#### 产品图片

![图片](https://www.alinx.com/upload/image/20220818/ACU2CG.jpg)

#### 产品链接

<https://www.alinx.com/detail/287>

#### 对应开发板

##### AXU2CG-E

![图片](https://www.alinx.com/upload/image/20220818/AXU3EG-750.jpg)    

##### 产品链接

<https://www.alinx.com/detail/223>

### AXU3EG

#### 产品简介

ACU3EG(核心板型号，下同)核心板，ZYNQ 芯片是基于 XILINX 公司的 Zynq UltraScale+ 
MPSoCs EG 系列的 XCZU3EG-1SFVC784I。
这款核心板使用了 5 片 Micron 的 DDR4 芯片 MT40A512M16GE,其中 PS 端挂载 4 片
DDR4，组成 64 位数据总线带宽和 4GB 的容量。PL 端挂载 1 片，为 16 位的数据总线宽度和
1GB 的容量。PS 端的 DDR4 SDRAM 的最高运行速度可达 1200MHz(数据速率 2400Mbps)，
PL 端的 DDR4 SDRAM 的最高运行速度可达 1066MHz(数据速率 2132Mbps)。另外核心板
上也集成了 1 片 256MBit 大小的 QSPI FLASH 和 8GB 大小的 eMMC FLASH 芯片，用于启
动存储配置和系统文件。
为了和底板连接，这款核心板的 4 个板对板连接器扩展出了 PS 端的 USB2.0 接口，千兆
以太网接口，SD 卡接口及其它剩余的 MIO 口；也扩展出了 4 对 PS MGT 高速收发器接口；
以及 PL 端的几乎所有 IO 口（HP I/O：96 个，HD I/O：84 个），XCZU3EG 芯片到接口之间
走线做了等长和差分处理，并且核心板尺寸仅为 80*60（mm），对于二次开发来说，非常适合。

#### XCZU3EG芯片主要特性

 XCZU3EG-1SFVC784I芯片的 PS 系统集成了 4 个 ARM Cortex™-A53 处理器，
速度高达 1.2Ghz，支持 2 级 Cache; 另外还包含 2 个 Cortex-R5 处理器，速度高达 500Mhz。  

ZU3EG 芯片支持 32 位或者 64 位的 DDR4，LPDDR4，DDR3,DDR3L, LPDDR3 存储芯
片，在 PS 端带有丰富的高速接口如 PCIE Gen2, USB3.0, SATA 3.1, DisplayPort；同时另外
也支持 USB2.0，千兆以太网，SD/SDIO，I2C，CAN，UART，GPIO 等接口。PL 端内部含
有丰富的可编程逻辑单元，DSP 和内部 RAM。

#### 产品图片

![图片](https://www.alinx.com/upload/image/20220819/ACU3EG.jpg)

#### 产品链接

<https://www.alinx.com/detail/293>

#### 对应开发板

##### AXU3EV

![图片](https://www.alinx.com/upload/image/20220818/AXU3EG-750.jpg)

##### 产品链接

<https://www.alinx.com/detail/256>

### AXU4EV

#### 产品简介

ACU4EV(核心板型号，下同)核心板，ZYNQ 芯片是基于 XILINX 公司的 Zynq UltraScale+ 
MPSoCs EV 系列的 XCZU4EV-1SFVC784I。  
这款核心板使用了 5 片 Micron 的 DDR4 芯片 MT40A512M16GE,其中 PS 端挂载 4 片
DDR4，组成 64 位数据总线带宽和 4GB 的容量。PL 端挂载 1 片，为 16 位的数据总线宽度和
1GB 的容量。PS 端的 DDR4 SDRAM 的最高运行速度可达 1200MHz(数据速率 2400Mbps)，
PL 端的 DDR4 SDRAM 的最高运行速度可达 1066MHz(数据速率 2132Mbps)。另外核心板
上也集成了 1 片 256MBit 大小的 QSPI FLASH 和 8GB 大小的 eMMC FLASH 芯片，用于启
动存储配置和系统文件。  
为了和底板连接，这款核心板的 4 个板对板连接器扩展出了 PS 端的 USB2.0 接口，千兆
以太网接口，SD 卡接口及其它剩余的 MIO 口；也扩展出了 4 对 PS MGT 高速收发器接口；
以及 PL 端的几乎所有 IO 口（HP I/O：96 个，HD I/O：84 个），XCZU4EV 芯片到接口之间
走线做了等长和差分处理，并且核心板尺寸仅为 80*60（mm），对于二次开发来说，非常适合

#### XCZU4EV芯片主要特性

XCZU4EV-1SFVC784I芯片的 PS 系统集成了 4 个 ARM Cortex™-A53 处理器，
速度高达 1.2Ghz，支持 2 级 Cache; 另外还包含 2 个 Cortex-R5 处理器，速度高达 500Mhz。
ZU4EV 芯片支持 32 位或者 64 位的 DDR4，LPDDR4，DDR3,DDR3L, LPDDR3 存储芯
片，在 PS 端带有丰富的高速接口如 PCIE Gen2, USB3.0, SATA 3.1, DisplayPort；同时另外
也支持 USB2.0，千兆以太网，SD/SDIO，I2C，CAN，UART，GPIO 等接口。PL 端内部含
有丰富的可编程逻辑单元，DSP 和内部 RAM。

#### 产品图片

![图片](https://www.alinx.com/upload/image/20220819/ACU4EV.jpg)

#### 产品链接

https://www.alinx.com/detail/294

#### 对应开发板

##### AXU4EV-E

![图片](https://www.alinx.com/upload/image/20220818/AXU3EG-750.jpg)

##### 产品链接

<https://www.alinx.com/detail/258>

##### AXU4EV-P

![图片](https://www.alinx.com/upload/image/20220818/AXU4EV5EV.jpg)

#### 产品链接

<https://www.alinx.com/detail/255>

### AXU5EV

#### 产品简介

ACU5EV(核心板型号，下同)核心板，ZYNQ 芯片是基于 XILINX 公司的 Zynq UltraScale+ 
MPSoCs EV 系列的 XCZU5EV-2SFVC784I。  

这款核心板使用了 5 片 Micron 的 DDR4 芯片 MT40A512M16GE,其中 PS 端挂载 4 片
DDR4，组成 64 位数据总线带宽和 4GB 的容量。PL 端挂载 1 片，为 16 位的数据总线宽度和
1GB 的容量。PS 端的 DDR4 SDRAM 的最高运行速度可达 1200MHz(数据速率 2400Mbps)，
PL 端的 DDR4 SDRAM 的最高运行速度可达 1066MHz(数据速率 2132Mbps)。另外核心板
上也集成了 1 片 256MBit 大小的 QSPI FLASH 和 8GB 大小的 eMMC FLASH 芯片，用于启
动存储配置和系统文件。  

为了和底板连接，这款核心板的 4 个板对板连接器扩展出了 PS 端的 USB2.0 接口，千兆
以太网接口，SD 卡接口及其它剩余的 MIO 口；也扩展出了 4 对 PS MGT 高速收发器接口；
以及 PL 端的几乎所有 IO 口（HP I/O：96 个，HD I/O：84 个），XCZU5EV 芯片到接口之间
走线做了等长和差分处理，并且核心板尺寸仅为 80*60（mm），对于二次开发来说，非常适合  

#### XCZU5EV芯片主要特性

开发板使用的是 Xilinx 公司的 Zynq UltraScale+ MPSoCs EV 系列的系列的芯片，型号
为 XCZU5EV-2SFVC784I。ZU5EV 芯片的 PS 系统集成了 4 个 ARM Cortex™-A53 处理器，
速度高达 1.2Ghz，支持 2 级 Cache; 另外还包含 2 个 Cortex-R5 处理器，速度高达 500Mhz。
ZU5EV 芯片支持 32 位或者 64 位的 DDR4，LPDDR4，DDR3,DDR3L, LPDDR3 存储芯
片，在 PS 端带有丰富的高速接口如 PCIE Gen2, USB3.0, SATA 3.1, DisplayPort；同时另外
也支持 USB2.0，千兆以太网，SD/SDIO，I2C，CAN，UART，GPIO 等接口。PL 端内部含
有丰富的可编程逻辑单元，DSP 和内部 RAM。

#### 产品图片

![图片](https://www.alinx.com/upload/image/20220819/ACU5EV.jpg)

#### 产品链接

<https://www.alinx.com/detail/286>

#### 对应开发板

##### AXU5EV-E

![图片](https://www.alinx.com/upload/image/20220818/AXU3EG-750.jpg)

##### 产品链接

<https://www.alinx.com/detail/257>

##### AXU5EV-P

![图片](https://www.alinx.com/upload/image/20220818/AXU4EV5EV.jpg)

##### 产品链接

<https://www.alinx.com/detail/224>

***

## 芯片参数

### PS部分参数

#### AXU2CG、AXU3EG

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

### AXU4EV、AXU5EV

<table>
    <tr>
        <td>处理器</td>
        <td>ARM 双核 Cortex™-A53 处理器，速度高达 1.2GHz，每个 CPU 32KB 1 级指令和数据缓存，1MB 2 级缓存 2 个 CPU 共享  ARM 双核 Cortex-R5 处理器，速度高达 500MHz，每个 CPU 32KB 1 级指令和数据缓存，及 128K 紧耦合内存</td>
    </tr>
    <tr>
        <td>图形处理器</td>
        <td>Mali-400 MP2, 速度高达 677MHz，64KB 2 级缓存</td>
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

### PL部分参数

#### AXU2CG

<table>
    <tr>
        <td>逻辑单元 Logic Cells</td>
        <td>103K</td>
    </tr>
    <tr>
        <td>触发器(flip-flops)</td>
        <td> 94K</td>
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

#### AXU3EG

<table>
    <tr>
        <td>逻辑单元 Logic Cells</td>
        <td>154K</td>
    </tr>
    <tr>
        <td>触发器(flip-flops)</td>
        <td>141K</td>
    </tr>
    <tr>
        <td>查找表 LUTs</td>
        <td>71K</td>
    </tr>
    <tr>
        <td>Block RAM</td>
        <td>9.4Mb</td>
    </tr>
    <tr>
        <td>时钟管理单元（CMTs）</td>
        <td>3</td>
    </tr>
    <tr>
        <td>乘法器 18x25MACCs</td>
        <td>360</td>
    </tr>
</table>

#### AXU4EV

<table>
    <tr>
        <td>逻辑单元(System Logic Cells)</td>
        <td>192K</td>
    </tr>
    <tr>
        <td>触发器(CLB flip-flops)</td>
        <td>176K</td>
    </tr>
    <tr>
        <td>查找表(CLBLUTs)</td>
        <td>71K</td>
    </tr>
    <tr>
        <td>Block RAM</td>
        <td>20.6Mb</td>
    </tr>
    <tr>
        <td>时钟管理单元（CMTs）</td>
        <td>4 个</td>
    </tr>
    <tr>
        <td>DSP Slices</td>
        <td>728 个</td>
    </tr>
    <tr>
        <td>图像编解码单元（VCU）</td>
        <td>1 个</td>
    </tr>
    <tr>
        <td>PCIE3.0</td>
        <td>2 个</td>
    </tr>
    <tr>
        <td>GTH 12.5Gb/s 收发器</td>
        <td>4 个</td>
    </tr>
</table>

#### AXU5EV

<table>
    <tr>
        <td>逻辑单元(System Logic Cells)</td>
        <td>256.2K</td>
    </tr>
    <tr>
        <td>触发器(CLB flip-flops)</td>
        <td>234.24K</td>
    </tr>
    <tr>
        <td>查找表(CLBLUTs)</td>
        <td> 117.12K</td>
    </tr>
    <tr>
        <td>Block RAM</td>
        <td>5.1Mb</td>
    </tr>
    <tr>
        <td>时钟管理单元（CMTs）</td>
        <td>4 个</td>
    </tr>
    <tr>
        <td>DSP Slices</td>
        <td>1248 个</td>
    </tr>
    <tr>
        <td>图像编解码单元（VCU）</td>
        <td>1 个</td>
    </tr>
    <tr>
        <td>PCIE3.0</td>
        <td>2 个</td>
    </tr>
    <tr>
        <td>GTH 12.5Gb/s 收发器</td>
        <td>4 个</td>
    </tr>
</table>

***

## 参考资料层次

#### reference_design

包含板卡参考设计

### schematics 

包含板卡的原理图设计

### step_models

包含板卡的尺寸结构

### technical_reference_manual

包含板卡用户手册

### trace lengths

包含板卡的布线长度介绍

***

## 官方网站

<https://www.alinx.com>



