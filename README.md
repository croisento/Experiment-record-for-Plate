# Experiment Record for Plate

基于浏览器的孔板实验记录工具，无需安装，打开链接即可使用。

**在线访问 → [Experiment record management for Plate](https://croisento.github.io/Experiment-record-for-Plate/)**

---

## 支持的板型

| 格式 | 规格 |
|------|------|
| 6 孔板 | 2 × 3 |
| 12 孔板 | 3 × 4 |
| 24 孔板 | 4 × 6 |
| 48 孔板 | 6 × 8 |
| 96 孔板 | 8 × 12 |
| Lane 11 | 1 × 11 点胶槽 |
| Lane 15 | 1 × 15 点胶槽 |

---

## 功能

**涂色**
- 单击或拖拽批量涂色
- 右键单击擦除某个孔
- 点击 **erase** 色块切换为橡皮擦模式

**自定义颜色分组**
- 点击 **+ new group** 随意添加颜色分组，数量不限
- 单击色块上的彩色圆点，打开系统调色盘，自由选取任意颜色
- 双击色块名称可重命名
- 悬停色块后点 × 可删除该分组
- 颜色修改后，已涂孔格和图例同步更新

**孔格标注**
- 双击任意孔格可添加文字标签，如 `100nM`、`ctrl`、`blank`
- 工具栏 **label − / +** 控制标签字号，范围 8–28px，实时预览

**批量选区**
- 切换到 **select** 模式，拖拽鼠标框选矩形区域
- 对选中区域一键填色或批量写入相同标签
- 支持一键全选当前板

**自由文本框**
- 切换到 **text** 模式，点击 **+ add text** 在孔板任意位置放置文本框
- 拖动 ⠿ 手柄移动位置
- 双击进入编辑，支持多行文字，ESC 或点击外部退出
- 每个文本框可单独设置字号（11 / 14 / 18 / 24）及文字颜色
- 点 × 删除

**多板管理**
- 点击 **+** 新建板，每块板可单独设置名称和板型
- 双击标签页重命名，点 × 删除
- 各板数据相互独立

**导出**
- 点击 **export PNG** 导出当前板的高分辨率图片（2× Retina）
- 纯白背景，空白孔为白色，打印清晰无杂色
- 导出内容包含孔内标签、自由文本框和颜色图例

**深色模式**
- 自动跟随系统外观切换

---

## 操作说明

```
单击 / 拖拽          → 涂色
右键单击             → 擦除该孔
双击孔格             → 添加或编辑标签
select 模式拖拽      → 框选多个孔
单击色块圆点         → 打开调色盘改颜色
双击色块名称         → 重命名颜色分组
悬停色块 → ×         → 删除颜色分组
label − / +          → 调整孔内标签字号
text 模式 → + add text → 放置自由文本框
双击标签页           → 重命名该板
```

---

## 本地使用

下载 `index.html`，用浏览器直接打开即可，无需服务器，断网也能用。

---

## 手机安装

用手机浏览器打开网址 → 点击「分享」→「添加到主屏幕」，即可从桌面图标打开。

---

## 文件结构

```
Experiment-record-for-Plate/
├── index.html      # 主程序（单文件，无任何外部依赖）
├── manifest.json   # PWA 配置，用于手机添加到主屏幕
└── README.md
```

---

## 更新记录

v3 — 自由调色 & 字号控制

颜色分组完全自定义：随意添加、删除，数量不限
每个颜色分组支持原生调色盘，自由选取任意颜色，不再局限于预设色
新增孔内标签字号控制（8–28px），工具栏 − / + 实时调整
颜色以药丸形标签（chip）展示，名称完整显示，不再截断

v2 — 多板管理、批量选区、自由文本框

支持多板标签页管理，每板独立命名和配置
批量矩形选区，支持一键填色和批量标注
新增自由文本框，可在孔板任意位置拖放（类似 PPT）
导出图片优化：纯白底色，便于打印

v1 — 初始版本

孔板涂色与预设颜色
孔格文字标注
支持 96 / 48 / 24 / 12 / 6 孔板及 Lane 11 / 15
单文件，无依赖

### v1 — 初始版本
- 孔板涂色与预设颜色
- 孔格文字标注
- 支持 96 / 48 / 24 / 12 / 6 孔板及 Lane 11 / 15
- 单文件，无依赖

---
# Experiment Record for Plate

A lightweight, browser-based well plate annotation tool for lab use. No installation required — open the link and start labeling.

**Live app → [your-username.github.io/Experiment-record-for-Plate](https://your-username.github.io/Experiment-record-for-Plate)**

---

## Supported Plate Types

| Format | Layout |
|--------|--------|
| 6-well | 2 × 3 |
| 12-well | 3 × 4 |
| 24-well | 4 × 6 |
| 48-well | 6 × 8 |
| 96-well | 8 × 12 |
| Lane 11 | 1 × 11 dispensing strip |
| Lane 15 | 1 × 15 dispensing strip |

---

## Features

**Painting**
- Click or drag across wells to apply color
- Right-click a well to erase
- Switch to **erase** mode with the dedicated chip button

**Custom color groups**
- Add as many color groups as you need with **+ new group**
- Click the colored dot on any chip to open the system color picker — choose any color freely
- Double-click a chip label to rename it
- Hover over a chip and click × to delete the group
- All painted wells update instantly when a color is changed

**Well labels**
- Double-click any well to add a text label (e.g. `100nM`, `ctrl`, `blank`)
- Adjustable label font size: use the **label − / +** control in the toolbar (8–28 px)

**Batch selection**
- Switch to **select** mode and drag to select a rectangular region
- Apply a color or label to all selected wells at once
- **Select all** button for full-plate operations

**Free-floating text boxes**
- Switch to **text** mode and click **+ add text** to place a text box anywhere on the plate
- Drag via the ⠿ handle to reposition
- Double-click to edit content; supports multi-line text
- Choose font size (11 / 14 / 18 / 24 px) and text color per text box
- Click × to delete

**Multi-plate management**
- Add multiple plates with the **+** tab button, each with its own name and format
- Double-click a tab to rename; click × to delete
- All plate data is kept independently

**Export**
- Click **export PNG** to download a high-resolution image (2× Retina)
- White background with white empty wells — clean and print-ready
- Includes well labels, floating text boxes, and a color legend

**Dark mode**
- Automatically follows your system appearance

---

## Usage

```
click / drag        → paint wells
right-click         → erase a well
double-click well   → add / edit label
select mode drag    → rectangle-select multiple wells
click chip dot      → change group color (color picker)
double-click chip   → rename color group
hover chip → ×      → delete color group
label − / +         → adjust well label font size
text mode → + add text → place a floating text box
double-click tab    → rename plate
```

---

## Local Use

Download `index.html` and open it directly in any browser — no server or internet connection needed.

---

## Mobile

Open the app URL in your phone browser → tap **Share** → **Add to Home Screen** to install it as a standalone app icon.

---

## File Structure

```
Experiment-record-for-Plate/
├── index.html      # main app (single file, no dependencies)
├── manifest.json   # PWA manifest for mobile install
└── README.md
```

---

## Changelog

### v3 — Color Picker & Font Size
- Color groups are now fully custom: add, delete, and reorder freely
- Each color group has a native color picker — choose any color with no restrictions
- New label font size control (8–28 px) with − / + buttons
- Color chips replace the old fixed palette, showing full names without truncation

### v2 — Multi-plate, Selection & Text Boxes
- Multi-plate management with named tabs
- Batch rectangular selection with fill and label operations
- Free-floating draggable text boxes (PPT-style)
- Export PNG improved: white background, print-ready output

### v1 — Initial Release
- Well plate painting with preset colors
- Well text labels
- 96 / 48 / 24 / 12 / 6-well plates and Lane 11 / 15 support
- Single-file app, no dependencies
