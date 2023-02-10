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

| 核心板名称                       |  ACU2CGA                                                             | ACU3EG                                                              | ACU4EV                                                              |  ACU5EV                                                             |
|-----------------------------|----------------------------------------------------------------------|---------------------------------------------------------------------|---------------------------------------------------------------------|---------------------------------------------------------------------|
| ZYNQ芯片                      | XCZU2CG-1SFVC784E                                                    |  XCZU3EG-1SFVC784I                                                  | XCZU4EV-1SFVC784I                                                   | XCZU5EV-2SFVC784I                                                   |
| 是否带图形处理单元(GPU)与视频编解码单元(VCU) | 否                                                                    | 否                                                                   | 是                                                                   | 是                                                                   |
| 尺寸                          | 80 x 60 x 7.1mm                                                      | 80 x 60 x 7.1mm                                                     | 80 x 60 x 7.1mm                                                     | 80 x 60 x 7.1mm                                                     |
| DDR4、SDRAM芯片                |  CXDQ2BFAM-CG(兼容MT40A256M16GE-083E） 256M x 16bit                     | MT40A512M16LY-062E 512M x 16bit                                     | MT40A512M16LY-062E 512M x 16bit                                     | MT40A512M16LY-062E 512M x 16bit                                     |
| QSPI FLASH                  |  MT25QU256ABA1EW9-0SITMT25QU256ABA1EW9-0SIT 256M bit                 |  MT25QU256ABA1EW9-0SITMT25QU256ABA1EW9-0SIT 256M bit                |  MT25QU256ABA1EW9-0SITMT25QU256ABA1EW9-0SIT 256M bit                |  MT25QU256ABA1EW9-0SITMT25QU256ABA1EW9-0SIT 256M bit                |
| EMMC Flash                  | MTFC8GAKAJCN-4M 8G Byte                                              | MTFC8GAKAJCN-4M 8G Byte                                             | MTFC8GAKAJCN-4M 8G Byte                                             | MTFC8GAKAJCN-4M 8G Byte                                             |
| 供电电压                        | 12V                                                                  | 12V                                                                 | 12V                                                                 | 12V                                                                 |
| IO管脚电平标准                    |  其中 BANK43~46 的 IO 的电平标准为 3.3V，BANK65,66 的电平不超过1.8V；MIO 的电平标准也为 1.8V | 其中 BANK43~46 的 IO 的电平标准为 3.3V，BANK65,66 的电平不超过1.8V；MIO 的电平标准也为 1.8V | 其中 BANK43~46 的 IO 的电平标准为 3.3V，BANK65,66 的电平不超过1.8V；MIO 的电平标准也为 1.8V | 其中 BANK43~46 的 IO 的电平标准为 3.3V，BANK65,66 的电平不超过1.8V；MIO 的电平标准也为 1.8V |
| 合高                          | 3mm                                                                  | 3mm                                                                 | 3mm                                                                 | 3mm                                                                 |
| 叠层数量                        | 16层                                                                  | 16层                                                                 | 16层                                                                 | 16层                                                                 |
| 逻辑单元 Logic Cells            | 103K                                                                 | 154K                                                                | 192K                                                                | 256.2K                                                              |
| 触发器(flip-flops)             | 94K                                                                  |  141K                                                               |  176K                                                               | 234.24K                                                             |
| 查找表 LUTs                    | 47K                                                                  |  71K                                                                | 71K                                                                 | 117.12K                                                             |
| Block RAM                   | 5.3Mb                                                                | 9.4Mb                                                               | 20.6Mb                                                              |  5.1Mb                                                              |
| 时钟管理单元（CMTs）                | 3个                                                                   | 3个                                                                  | 4 个                                                                 | 4 个                                                                 |
| 乘法器 18x25MACCs              | 240个                                                                 | 360个                                                                | 728 个                                                               |  1248 个                                                             |
| 图像编解码单元（VCU）                |                                                                      |                                                                     | 1 个                                                                 |  1 个                                                                |
| PCIE3.0                     |                                                                      |                                                                     | 2 个                                                                 |  2 个                                                                |
| GTH 12.5Gb/s 收发器            |                                                                      |                                                                     | 4 个                                                                 | 4 个                                                                 |



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



