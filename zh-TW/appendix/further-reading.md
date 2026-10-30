# 附錄 C　延伸閱讀

本附錄整理書中各章引用的參考資料，以及想深入了解時可以參考的書籍、標準與研討會。這些資料大多是英文，閱讀時可以搭配[附錄 A 術語總表](glossary.md)。

挑書的原則很簡單：**要嘛把整個流程講完，要嘛把單一主題講透**。夾在中間、什麼都講一點的書，對已經讀完這本概論的人幫助不大。

---

## 入門與綜合

| 資料 | 說明 | 相關章節 |
|---|---|---|
| Peter Van Zant，《Microchip Fabrication: A Practical Guide to Semiconductor Processing》 | 涵蓋整個製造流程的經典入門書 | 全書 |
| Hong Xiao，《Introduction to Semiconductor Manufacturing Technology》 | 以製程模組為架構，圖解清楚 | 第 2 部 |
| Michael Quirk、Julian Serda，《Semiconductor Manufacturing Technology》 | 偏重實務與設備，適合準備入行的讀者 | 全書 |
| James D. Plummer、Michael D. Deal、Peter B. Griffin，《Silicon VLSI Technology: Fundamentals, Practice, and Modeling》 | 理論較深，第 2 章完整介紹一條 CMOS 流程 | 第 2、3 部 |
| S. Wolf、R. N. Tauber，《Silicon Processing for the VLSI Era, Volume 1: Process Technology》 | 製程模組的經典參考書，份量重，適合當工具書查 | 第 2 部 |
| Yoshio Nishi、Robert Doering 編，《Handbook of Semiconductor Manufacturing Technology》 | 手冊型工具書，涵蓋設備、材料與廠務 | 全書 |

## 元件物理

| 資料 | 說明 | 相關章節 |
|---|---|---|
| S. M. Sze、M. K. Lee，《Semiconductor Devices: Physics and Technology》 | 半導體元件的標準教科書 | 2、12 |
| IEEE IRDS（International Roadmap for Devices and Systems），More Moore 章節 | 電晶體與製程微縮的發展路線圖 | 12、14 |

## 製程模組與量測

| 資料 | 說明 | 相關章節 |
|---|---|---|
| Chris Mack，《Fundamental Principles of Optical Lithography》 | 微影原理 | 4 |
| Harry J. Levinson，《Principles of Lithography》 | 從實務角度看微影的設計與限制 | 4 |
| Karen A. Reinhardt、Werner Kern 編，《Handbook of Silicon Wafer Cleaning Technology》 | 晶圓清洗技術手冊 | 9 |
| Alain C. Diebold 編，《Handbook of Silicon Semiconductor Metrology》 | 量測技術手冊 | 15 |

## 良率、統計與製程控制

| 資料 | 說明 | 相關章節 |
|---|---|---|
| Gary S. May、Costas J. Spanos，《Fundamentals of Semiconductor Manufacturing and Process Control》 | 良率、統計與製程控制 | 16、17、18 |
| Douglas C. Montgomery，《Introduction to Statistical Quality Control》 | 統計品管的標準教科書 | 17 |
| EDFAS／ASM International，《Microelectronics Failure Analysis Desk Reference》 | 故障分析的技術手冊 | 16 |

## 測試、封裝與可靠度

| 資料 | 說明 | 相關章節 |
|---|---|---|
| Michael L. Bushnell、Vishwani D. Agrawal，《Essentials of Electronic Testing for Digital, Memory and Mixed-Signal VLSI Circuits》 | 晶片測試 | 19 |
| Rao R. Tummala，《Fundamentals of Microsystems Packaging》 | 封裝基礎 | 20 |
| John H. Lau，《Semiconductor Advanced Packaging》 | 先進封裝 | 21 |
| J. W. McPherson，《Reliability Physics and Engineering: Time-To-Failure Modeling》 | 可靠度物理與壽命模型 | 22 |

## 記憶體與韌體

| 資料 | 說明 | 相關章節 |
|---|---|---|
| Rino Micheloni、Luca Crippa、Alessia Marelli，《Inside NAND Flash Memories》 | NAND Flash 的結構與操作 | 13、24 |
| Rino Micheloni、Alessia Marelli、Giovanni Ravasio，《Error Correction Codes for Non-Volatile Memories》 | 記憶體的更正碼設計 | 24 |
| Bruce Jacob、Spencer W. Ng、David T. Wang，《Memory Systems: Cache, DRAM, Disk》 | 記憶體系統 | 13、24 |
| Yoongu Kim 等，〈Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors〉，ISCA 2014 | 首次系統性揭露 Row Hammer 的論文 | 24 |
| Bianca Schroeder、Eduardo Pinheiro、Wolf-Dietrich Weber，〈DRAM Errors in the Wild: A Large-Scale Field Study〉，SIGMETRICS 2009 | 大規模機群的 DRAM 錯誤實測，說明軟錯誤在真實系統裡有多常見 | 22、24 |

## 工廠運作與系統

| 資料 | 說明 | 相關章節 |
|---|---|---|
| Wallace J. Hopp、Mark L. Spearman，《Factory Physics》 | 生產週期、在製品與產能的基本觀念 | 1、23 |
| Heiko Meyer、Franz Fuchs、Klaus Thiel，《Manufacturing Execution Systems: Optimal Design, Planning, and Deployment》 | 製造執行系統 | 23 |
| Lars Mönch、John W. Fowler、Stéphane Dauzère-Pérès、Scott J. Mason、Oliver Rose，〈A Survey of Problems, Solution Techniques, and Future Challenges in Scheduling Semiconductor Manufacturing Operations〉，*Journal of Scheduling*，2011 | 晶圓廠排程問題的綜述 | 23 |

## 產業與歷史

| 資料 | 說明 |
|---|---|
| Chris Miller，《Chip War: The Fight for the World's Most Critical Technology》（繁體中文版書名《晶片戰爭》） | 半導體產業的發展史 |

---

## 產業標準

標準不是拿來讀的，是拿來查的。真正會用到它的時候，通常是在寫規格、驗收設備或跟客戶對定義。

| 標準 | 內容 | 相關章節 |
|---|---|---|
| ISO 14644-1 | 潔淨室的等級分類 | 1 |
| SEMI M1 | 拋光單晶矽晶圓的規格 | 3 |
| SEMI E10 | 設備可靠度、可用率與狀態的定義 | 1、23 |
| SEMI E79 | 設備生產力（OEE）的定義與量測 | 23 |
| SEMI E5、E30、E37 | 機台通訊標準（SECS-II、GEM、HSMS） | 23 |
| SEMI E87 | 載具管理（Carrier Management） | 23 |
| SEMI E90 | 基板追蹤（Substrate Tracking） | 23 |
| SEMI E94 | 控制作業管理（Control Job Management） | 23 |
| SEMI E139 | Recipe 與參數管理（RaP） | 23 |
| JEDEC JESD79 | DDR SDRAM 標準 | 13、24 |
| JEDEC JESD89 | α 粒子與宇宙射線造成的軟錯誤的量測與報告 | 24 |
| JEDEC JESD218 | 固態硬碟的耐力與資料保存需求 | 24 |
| JEDEC JESD219 | 固態硬碟的耐力工作負載 | 24 |
| JEDEC JEP122 | 半導體元件的失效機制與模型 | 22 |
| IPC/JEDEC J-STD-020 | 封裝的濕度敏感等級分類 | 20 |
| IPC/JEDEC J-STD-033 | 濕度敏感元件的包裝、運送與使用 | 20 |
| JEDEC J-STD-046 | 產品與製程變更的客戶通知 | 18 |
| JEDEC JESD47 | 積體電路的可靠度驗證 | 22 |
| AEC-Q100 | 車用積體電路的可靠度驗證 | 22 |

## 研討會

想知道最新的技術進展，可以關注以下研討會發表的論文。它們的論文集通常會公開摘要，不需要付費就能判斷一篇論文值不值得讀。

| 研討會 | 主題 |
|---|---|
| IEEE IEDM（International Electron Devices Meeting） | 電晶體與元件技術 |
| Symposium on VLSI Technology and Circuits | 先進製程與電路 |
| SPIE Advanced Lithography + Patterning | 微影與圖形化技術 |
| IEEE/SEMI ASMC（Advanced Semiconductor Manufacturing Conference） | 晶圓廠製造、自動化與良率提升 |
| IEEE ECTC（Electronic Components and Technology Conference） | 封裝技術 |
| IEEE IRPS（International Reliability Physics Symposium） | 可靠度物理 |
| IEEE ISSCC（International Solid-State Circuits Conference） | 固態電路與系統晶片 |
| IIT（International Conference on Ion Implantation Technology） | 離子佈植技術 |
| ISTFA（International Symposium for Testing and Failure Analysis） | 測試與故障分析 |

## 網站

| 網站 | 說明 | 相關章節 |
|---|---|---|
| WikiChip | 製程節點與晶片架構的整理 | 14 |
| SemiWiki | 半導體產業與技術的專欄與討論 | 全書 |

---

[← 附錄 B 現場行話](fab-jargon.md) ｜ [目錄](../README.md)
