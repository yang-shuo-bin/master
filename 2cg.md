# Xilinx Zynq UltraScale+ MPSoC 系列核心板ACU2CG、ACU3EG、ACU4EV、ACU5EV

***

## 主要内容

### 核心板介绍

### 芯片参数

### 参考资料层次

### 官方网站

***

## 核心板介绍


### 外设接口以及存储芯片

使用了 5 片 Micron 的 DDR4 芯片 MT40A512M16GE(ACU2CG为4片),其中 PS 端挂载 4 片 DDR4，组成 64 位数据总线带宽和 4GB 的容量。PL 端挂载 1 片(ACU2CG的PL端没有挂载)，为 16 位的数据总线宽度和 1GB 的容量。PS 端的 DDR4 SDRAM 的最高运行速度可达 1200MHz(数据速率 2400Mbps)， PL 端的 DDR4 SDRAM 的最高运行速度可达 1066MHz(数据速率 2132Mbps)。另外核心板 上也集成了 1 片 256MBit 大小的 QSPI FLASH 和 8GB 大小的 eMMC FLASH 芯片，用于启 动存储配置和系统文件。 为了和底板连接，这款核心板的 4 个板对板连接器扩展出了 PS 端的 USB2.0 接口，千兆 以太网接口，SD 卡接口及其它剩余的 MIO 口；也扩展出了 4 对 PS MGT 高速收发器接口； 以及 PL 端的几乎所有 IO 口,芯片到接口之间 走线做了等长和差分处理，并且核心板尺寸仅为 80*60（mm）

### 主要特性

<table>
    <tr>
        <td>核心板名称</td>
        <td>ACU2CGA</td>
        <td>ACU3EG</td>
        <td>ACU4EV</td>
        <td>ACU5EV</td>
    </tr>
    <tr>
        <td>ZYNQ芯片</td>
        <td>XCZU2CG-1SFVC784E</td>
        <td>XCZU3EG-1SFVC784I</td>
        <td>XCZU4EV-1SFVC784I</td>
        <td>XCZU5EV-2SFVC784I</td>
    </tr>
    <tr>
        <td>是否带图形处理单元(GPU)与视频编解码单元(VCU)</td>
        <td>否</td>
        <td></td>
        <td>是</td>
        <td></td>
    </tr>
    <tr>
        <td>尺寸</td>
        <td>80 x 60 x 7.1mm</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>DDR4、SDRAM芯片</td>
        <td>CXDQ2BFAM-CG(兼容MT40A256M16GE-083E） 256M x 16bit</td>
        <td>MT40A512M16LY-062E 512M x 16bit</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>QSPI FLASH</td>
        <td>MT25QU256ABA1EW9-0SITMT25QU256ABA1EW9-0SIT      256M bit</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>EMMC Flash</td>
        <td>MTFC8GAKAJCN-4M   8G Byte</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>供电电压</td>
        <td>12V</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>IO管脚电平标准</td>
        <td>其中 BANK43~46 的 IO 的电平标准为 3.3V，BANK65,66 的电平不超过1.8V；MIO 的电平标准也为 1.8V</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>合高</td>
        <td>3mm</td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>叠层数量</td>
        <td>16层</td>
    </tr>
</table> 

***

## 芯片参数

### PS部分参数

#### ACU2CG、ACU3EG

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

### ACU4EV、ACU5EV

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

#### ACU2CG

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

#### ACU3EG

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

#### ACU4EV

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

#### ACU5EV

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



