# Media Maths Calculator | 媒體數學計算器

A practical media calculation toolkit for digital advertising, media planning and campaign analysis.

一個為數碼廣告、媒體策劃及廣告活動分析而設的實用媒體計算工具。

**English | 繁體中文**

---

## About | 關於項目

### English

**Media Maths Calculator** is a collection of useful calculators for common advertising and media metrics.

The project is designed for media planners, digital marketers, advertising professionals, analysts and students who need a simple way to calculate and understand campaign performance.

### 中文

**Media Maths Calculator（媒體數學計算器）**是一個集合常用廣告及媒體指標計算功能的工具。

本項目適合媒體策劃、數碼營銷、廣告從業員、數據分析人員及學生使用，讓使用者更方便地計算及了解廣告活動表現。

---

## Features | 主要功能

The project is designed to support:

本項目計劃支援：

- CPM - Cost Per Mille | 每千次曝光成本
- CPC - Cost Per Click | 每次點擊成本
- CTR - Click-Through Rate | 點擊率
- CPA - Cost Per Acquisition | 每次轉換成本
- Conversion Rate | 轉換率
- ROAS - Return on Ad Spend | 廣告支出回報
- Impressions | 曝光次數
- Media Budget | 媒體預算
- Campaign Summary | 廣告活動摘要

---

## Media Formula Reference | 媒體計算公式

### CPM

**Cost Per Mille | 每千次曝光成本**

```text
CPM = (Cost / Impressions) x 1,000
```

```text
CPM = (廣告成本 / 曝光次數) x 1,000
```

---

### CPC

**Cost Per Click | 每次點擊成本**

```text
CPC = Cost / Clicks
```

```text
CPC = 廣告成本 / 點擊次數
```

---

### CTR

**Click-Through Rate | 點擊率**

```text
CTR = (Clicks / Impressions) x 100
```

```text
CTR = (點擊次數 / 曝光次數) x 100
```

---

### CPA

**Cost Per Acquisition | 每次轉換成本**

```text
CPA = Cost / Conversions
```

```text
CPA = 廣告成本 / 轉換次數
```

---

### Conversion Rate

**Conversion Rate | 轉換率**

```text
Conversion Rate = (Conversions / Clicks) x 100
```

```text
轉換率 = (轉換次數 / 點擊次數) x 100
```

---

### ROAS

**Return on Ad Spend | 廣告支出回報**

```text
ROAS = Revenue / Advertising Cost
```

```text
ROAS = 廣告收入 / 廣告成本
```

---

### Impressions

**Estimated Impressions | 預計曝光次數**

```text
Impressions = (Cost / CPM) x 1,000
```

```text
曝光次數 = (廣告成本 / CPM) x 1,000
```

---

## Example | 計算例子

Consider a digital advertising campaign with the following performance:

假設一個數碼廣告活動有以下數據：

```text
Media Cost / 媒體成本:        $10,000
Impressions / 曝光次數:       2,000,000
Clicks / 點擊次數:            20,000
Conversions / 轉換次數:       500
Revenue / 廣告收入:           $40,000
```

The calculated results are:

計算結果：

```text
CPM              = $5.00
CPC              = $0.50
CTR              = 1.00%
CPA              = $20.00
Conversion Rate  = 2.50%
ROAS             = 4.00
```

---

## Calculator Modules | 計算器模組

```text
Media Maths Calculator
│
├── CPM Calculator
│   └── 每千次曝光成本計算器
│
├── CPC Calculator
│   └── 每次點擊成本計算器
│
├── CTR Calculator
│   └── 點擊率計算器
│
├── CPA Calculator
│   └── 每次轉換成本計算器
│
├── Conversion Rate Calculator
│   └── 轉換率計算器
│
├── ROAS Calculator
│   └── 廣告支出回報計算器
│
├── Impression Calculator
│   └── 曝光量計算器
│
└── Campaign Summary
    └── 廣告活動摘要
```

---

## Project Structure | 項目結構

```text
media-maths-calculator/
│
├── src/
│   ├── calculator/
│   ├── components/
│   └── utils/
│
├── tests/
├── docs/
├── examples/
├── README.md
└── LICENSE
```

The actual directory structure can be adjusted according to the programming language or framework used.

實際目錄結構可根據項目所使用的程式語言或開發框架進行調整。

---

## Getting Started | 開始使用

### GitHub

Clone from GitHub:

從 GitHub 複製項目：

```bash
git clone https://github.com/YOUR_USERNAME/media-maths-calculator.git
```

### Gitee

Clone from Gitee:

從 Gitee 複製項目：

```bash
git clone https://gitee.com/YOUR_USERNAME/media-maths-calculator.git
```

Enter the project directory:

進入項目目錄：

```bash
cd media-maths-calculator
```

---

## Usage | 使用方法

A typical calculation workflow:

一般計算流程：

1. Select a media metric. | 選擇媒體指標。
2. Enter campaign data. | 輸入廣告活動數據。
3. Calculate the result. | 執行計算。
4. Review the calculated metric. | 查看計算結果。
5. Use the result for planning or analysis. | 將結果用於媒體策劃或分析。

Example:

```text
CPM Calculator

Cost / 成本
$10,000

Impressions / 曝光
2,000,000

Result / 結果
CPM = $5.00
```

---

## Development Roadmap | 開發路線圖

- [ ] CPM Calculator | CPM 計算器
- [ ] CPC Calculator | CPC 計算器
- [ ] CTR Calculator | CTR 計算器
- [ ] CPA Calculator | CPA 計算器
- [ ] Conversion Rate Calculator | 轉換率計算器
- [ ] ROAS Calculator | ROAS 計算器
- [ ] Impression Calculator | 曝光量計算器
- [ ] Media Budget Calculator | 媒體預算計算器
- [ ] Campaign Comparison | 廣告活動比較
- [ ] Currency Selection | 貨幣選擇
- [ ] Result Export | 計算結果匯出
- [ ] Responsive Interface | 響應式介面
- [ ] Light / Dark Theme | 淺色 / 深色模式

---

## Supported Repository Platforms | 支援代碼託管平台

This project can be maintained on:

本項目可託管於：

- GitHub
- Gitee

The same core `README.md` is intended to be used on both platforms.

同一份核心 `README.md` 可同時用於兩個平台。

---

## Git Workflow | Git 工作流程

Create a new branch:

建立新分支：

```bash
git checkout -b feature/new-calculator
```

Add your changes:

加入修改：

```bash
git add .
```

Commit:

提交：

```bash
git commit -m "Add new media calculator"
```

Push to the repository:

推送至代碼倉庫：

```bash
git push origin feature/new-calculator
```

---

## Contributing | 參與貢獻

Contributions are welcome.

歡迎參與本項目的開發及改進。

You can contribute by:

你可以透過以下方式參與：

- Reporting bugs | 回報問題
- Suggesting new calculators | 建議新的計算工具
- Improving documentation | 改善項目文件
- Improving calculations | 改善計算功能
- Improving the user interface | 改善使用者介面
- Submitting code changes | 提交程式碼修改

Please create a Pull Request after completing your changes.

完成修改後，可以透過 Pull Request 提交你的變更。

---

## Disclaimer | 免責聲明

The Media Maths Calculator is intended as a calculation, educational and media-planning aid.

Media calculations may vary depending on the advertising platform, reporting methodology, attribution model and organisation.

Results should therefore be reviewed before being used for business, financial, budgeting or campaign-reporting decisions.

Media Maths Calculator 主要作為計算、教學及媒體策劃輔助工具。

不同廣告平台、報告方式、歸因模型及機構可能採用不同的媒體指標定義及計算方式。

因此，在將計算結果應用於商業決策、財務、廣告預算或正式報告前，建議再次核對相關數據。

---

## Licence | 授權

Please refer to the `LICENSE` file for licensing information.

有關本項目的授權條款，請參閱 `LICENSE` 文件。

---

## Author | 作者

**Thomas Wong**

Media | Digital Marketing | Data | Technology

媒體 | 數碼營銷 | 數據 | 科技

---

## Project Status | 項目狀態

**In Development | 開發中**

The Media Maths Calculator is currently under development.

Additional media calculations, analytics tools and documentation can be added as the project evolves.

Media Maths Calculator 目前仍在開發階段。

未來可根據項目發展加入更多媒體計算功能、分析工具及相關文件。
