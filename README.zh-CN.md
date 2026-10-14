# LC cryo-MOST 配置清单和图纸

[English](README.md)

本仓库提供线共焦冷冻微型光学切片断层成像（LC cryo-MOST）系统的完整部件清单及部分机械设计资料。该平台结合自发荧光成像与低温铣削，在不进行化学固定或外源标记的条件下，对完整未脱钙小鼠关节中的软硬组织进行共同三维空间内的成像。

这些资料便于其他研究团队了解系统所用部件、查看公开的低温子系统设计，并与作者讨论系统实现或成像合作。

## 公开文件

| 文件 | 内容 | 格式 |
| --- | --- | --- |
| [Parts List.xlsx](Parts%20List.xlsx) | 本研究系统的完整部件清单，共31项，包含名称、型号、厂家和国家。 | Excel |
| [Insulated box.pdf](Insulated%20box.pdf) | 隔热箱的尺寸图及连接布局。 | PDF |
| [LN2 tank.SLDPRT](LN2%20tank.SLDPRT) | 液氮罐的SolidWorks零件文件。 | SolidWorks SLDPRT |
| [在线浏览部件清单](docs/parts-list.md) | Excel清单的网页可读版本，保留全部31项。 | Markdown |

公开图纸涉及部分低温部件。光学配置、采集参数和铣削—成像流程详见配套稿件的Methods及Supplementary Fig. 1。

## 如何查看

1. 点击上述文件链接下载，或选择 **Code → Download ZIP** 下载整个仓库。
2. 使用Excel或兼容XLSX格式的软件查看部件清单；网页可读版本包含相同的31项。
3. 使用PDF阅读器查看隔热箱图纸；使用SolidWorks或兼容的CAD查看器打开液氮罐零件文件，文件兼容性取决于软件及文件版本。
4. 在考虑适配自己的硬件平台时，结合稿件、清单和图纸阅读。定制部件及系统集成问题可联系作者进行技术交流。

### 隔热箱图纸预览

![隔热箱尺寸图及连接布局](docs/insulated-box.png)

[下载原始PDF图纸](Insulated%20box.pdf)。

## 控制软件

定制控制软件用于协调设备运动、图像采集和液氮管理。程序针对现有硬件配置开发，与具体设备接口及控制参数紧密耦合，源代码尚未公开。

稿件已描述设备配置、关键参数和运行流程，以便其他研究者在自己的硬件平台上实现相应功能。有意适配这些功能的团队可联系通讯作者进行技术交流。

## 平台使用与科研合作

欢迎其他研究团队讨论通过科研合作使用LC cryo-MOST平台。研究者可联系通讯作者，讨论样本适用性、成像需求、系统实现和合作安排。

**通讯作者：** Jing Yuan  
**单位：** 华中科技大学  
**邮箱：** [yuanj@hust.edu.cn](mailto:yuanj@hust.edu.cn)

关于公开文件的技术问题，也可通过GitHub Issues提出。

## 配套研究

本仓库资料对应稿件：

*Volumetric Autofluorescence Imaging of Soft and Hard Tissues in Whole Undecalcified Joints Using Line-confocal Cryo-Microscopic Optical Sectioning Tomography.*

作者：Mingyu Tian、Haoyu Gong、Chuancao Sun、Huijuan Pan、Bolin Lu、Ting Zhu、Qingming Luo和Jing Yuan。

在研究中使用这些资料时，请引用配套论文。发表信息和DOI将在可用后补充。

## 维护团队

HUST-Yuan-Lab（华中科技大学） — [HUST-Yuan-Lab](https://github.com/HUST-Yuan-Lab)
