<!-- source: zh-TW/appendix/further-reading.md | sha: 024fe7155825 -->

# 附录 C　延伸阅读

本附录整理书中各章引用的参考资料，以及想深入了解时可以参考的书籍、标准与研讨会。这些资料大多是英文，阅读时可以搭配[附录 A 术语总表](glossary.md)。

挑书的原则很简单：**要么把整个流程讲完，要么把单一主题讲透**。夹在中间、什么都讲一点的书，对已经读完这本概论的人帮助不大。

---

## 入门与综合

| 资料 | 说明 | 相关章节 |
|---|---|---|
| Peter Van Zant，《Microchip Fabrication: A Practical Guide to Semiconductor Processing》 | 涵盖整个制造流程的经典入门书 | 全书 |
| Hong Xiao，《Introduction to Semiconductor Manufacturing Technology》 | 以工艺模块为架构，图解清楚 | 第 2 部 |
| Michael Quirk、Julian Serda，《Semiconductor Manufacturing Technology》 | 偏重实务与设备，适合准备入行的读者 | 全书 |
| James D. Plummer、Michael D. Deal、Peter B. Griffin，《Silicon VLSI Technology: Fundamentals, Practice, and Modeling》 | 理论较深，第 2 章完整介绍一条 CMOS 流程 | 第 2、3 部 |
| S. Wolf、R. N. Tauber，《Silicon Processing for the VLSI Era, Volume 1: Process Technology》 | 工艺模块的经典参考书，份量重，适合当工具书查 | 第 2 部 |
| Yoshio Nishi、Robert Doering 编，《Handbook of Semiconductor Manufacturing Technology》 | 手册型工具书，涵盖设备、材料与厂务 | 全书 |

## 器件物理

| 资料 | 说明 | 相关章节 |
|---|---|---|
| S. M. Sze、M. K. Lee，《Semiconductor Devices: Physics and Technology》 | 半导体器件的标准教科书 | 2、12 |
| IEEE IRDS（International Roadmap for Devices and Systems），More Moore 章节 | 晶体管与工艺微缩的发展路线图 | 12、14 |

## 工艺模块与测量

| 资料 | 说明 | 相关章节 |
|---|---|---|
| Chris Mack，《Fundamental Principles of Optical Lithography》 | 光刻原理 | 4 |
| Harry J. Levinson，《Principles of Lithography》 | 从实务角度看光刻的设计与限制 | 4 |
| Karen A. Reinhardt、Werner Kern 编，《Handbook of Silicon Wafer Cleaning Technology》 | 晶圆清洗技术手册 | 9 |
| Alain C. Diebold 编，《Handbook of Silicon Semiconductor Metrology》 | 测量技术手册 | 15 |

## 良率、统计与工艺控制

| 资料 | 说明 | 相关章节 |
|---|---|---|
| Gary S. May、Costas J. Spanos，《Fundamentals of Semiconductor Manufacturing and Process Control》 | 良率、统计与工艺控制 | 16、17、18 |
| Douglas C. Montgomery，《Introduction to Statistical Quality Control》 | 统计质量控制的标准教科书 | 17 |
| EDFAS／ASM International，《Microelectronics Failure Analysis Desk Reference》 | 失效分析的技术手册 | 16 |

## 测试、封装与可靠性

| 资料 | 说明 | 相关章节 |
|---|---|---|
| Michael L. Bushnell、Vishwani D. Agrawal，《Essentials of Electronic Testing for Digital, Memory and Mixed-Signal VLSI Circuits》 | 芯片测试 | 19 |
| Rao R. Tummala，《Fundamentals of Microsystems Packaging》 | 封装基础 | 20 |
| John H. Lau，《Semiconductor Advanced Packaging》 | 先进封装 | 21 |
| J. W. McPherson，《Reliability Physics and Engineering: Time-To-Failure Modeling》 | 可靠性物理与寿命模型 | 22 |

## 存储器与固件

| 资料 | 说明 | 相关章节 |
|---|---|---|
| Rino Micheloni、Luca Crippa、Alessia Marelli，《Inside NAND Flash Memories》 | NAND Flash 的结构与操作 | 13、24 |
| Rino Micheloni、Alessia Marelli、Giovanni Ravasio，《Error Correction Codes for Non-Volatile Memories》 | 存储器的纠错码设计 | 24 |
| Bruce Jacob、Spencer W. Ng、David T. Wang，《Memory Systems: Cache, DRAM, Disk》 | 存储器系统 | 13、24 |
| Yoongu Kim 等，〈Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors〉，ISCA 2014 | 首次系统性揭露 Row Hammer 的论文 | 24 |
| Bianca Schroeder、Eduardo Pinheiro、Wolf-Dietrich Weber，〈DRAM Errors in the Wild: A Large-Scale Field Study〉，SIGMETRICS 2009 | 大规模机群的 DRAM 错误实测，说明软错误在真实系统里有多常见 | 22、24 |

## 工厂运行与系统

| 资料 | 说明 | 相关章节 |
|---|---|---|
| Wallace J. Hopp、Mark L. Spearman，《Factory Physics》 | 生产周期、在制品与产能的基本观念 | 1、23 |
| Heiko Meyer、Franz Fuchs、Klaus Thiel，《Manufacturing Execution Systems: Optimal Design, Planning, and Deployment》 | 制造执行系统 | 23 |
| Lars Mönch、John W. Fowler、Stéphane Dauzère-Pérès、Scott J. Mason、Oliver Rose，〈A Survey of Problems, Solution Techniques, and Future Challenges in Scheduling Semiconductor Manufacturing Operations〉，*Journal of Scheduling*，2011 | 晶圆厂调度问题的综述 | 23 |

## 产业与历史

| 资料 | 说明 |
|---|---|
| Chris Miller，《Chip War: The Fight for the World's Most Critical Technology》（繁体中文版书名《晶片戰爭》） | 半导体产业的发展史 |

---

## 产业标准

标准不是拿来读的，是拿来查的。真正会用到它的时候，通常是在写规格、验收设备或跟客户对定义。

| 标准 | 内容 | 相关章节 |
|---|---|---|
| ISO 14644-1 | 洁净室的等级分类 | 1 |
| SEMI M1 | 抛光单晶硅晶圆的规格 | 3 |
| SEMI E10 | 设备可靠性、可用率与状态的定义 | 1、23 |
| SEMI E79 | 设备生产力（OEE）的定义与测量 | 23 |
| SEMI E5、E30、E37 | 设备通信标准（SECS-II、GEM、HSMS） | 23 |
| SEMI E87 | 载具管理（Carrier Management） | 23 |
| SEMI E90 | 基板跟踪（Substrate Tracking） | 23 |
| SEMI E94 | 控制作业管理（Control Job Management） | 23 |
| SEMI E139 | 配方与参数管理（RaP） | 23 |
| JEDEC JESD79 | DDR SDRAM 标准 | 13、24 |
| JEDEC JESD89 | α 粒子与宇宙射线造成的软错误的测量与报告 | 24 |
| JEDEC JESD218 | 固态硬盘的耐久性与数据保持要求 | 24 |
| JEDEC JESD219 | 固态硬盘的耐久性工作负载 | 24 |
| JEDEC JEP122 | 半导体器件的失效机制与模型 | 22 |
| IPC/JEDEC J-STD-020 | 封装的湿度敏感等级分类 | 20 |
| IPC/JEDEC J-STD-033 | 湿度敏感器件的包装、运送与使用 | 20 |
| JEDEC J-STD-046 | 产品与工艺变更的客户通知 | 18 |
| JEDEC JESD47 | 集成电路的可靠性验证 | 22 |
| AEC-Q100 | 车用集成电路的可靠性验证 | 22 |

## 研讨会

想知道最新的技术进展，可以关注以下研讨会发表的论文。它们的论文集通常会公开摘要，不需要付费就能判断一篇论文值不值得读。

| 研讨会 | 主题 |
|---|---|
| IEEE IEDM（International Electron Devices Meeting） | 晶体管与器件技术 |
| Symposium on VLSI Technology and Circuits | 先进工艺与电路 |
| SPIE Advanced Lithography + Patterning | 光刻与图形化技术 |
| IEEE/SEMI ASMC（Advanced Semiconductor Manufacturing Conference） | 晶圆厂制造、自动化与良率提升 |
| IEEE ECTC（Electronic Components and Technology Conference） | 封装技术 |
| IEEE IRPS（International Reliability Physics Symposium） | 可靠性物理 |
| IEEE ISSCC（International Solid-State Circuits Conference） | 固态电路与系统芯片 |
| IIT（International Conference on Ion Implantation Technology） | 离子注入技术 |
| ISTFA（International Symposium for Testing and Failure Analysis） | 测试与失效分析 |

## 网站

| 网站 | 说明 | 相关章节 |
|---|---|---|
| WikiChip | 工艺节点与芯片架构的整理 | 14 |
| SemiWiki | 半导体产业与技术的专栏与讨论 | 全书 |

---

[← 附录 B 现场行话](fab-jargon.md) ｜ [目录](../README.md)
