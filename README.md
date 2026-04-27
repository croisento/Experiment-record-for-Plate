# Experiment Record for Plate

基于浏览器的孔板实验记录工具，无需安装，打开链接即可使用。

**在线访问 → [Experiment-record-for-Plate](https://croisento.github.io/Experiment-record-for-Plate/)**

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
- 9 种预设颜色（样品、对照、处理组、标准品、空白等）
- 单击颜色名称可随时重命名

**标注**
- 双击孔格添加文字标签，如 `100nM`、`ctrl`、`空白`

**批量选区**
- 切换到 **select** 模式后，按住鼠标拖拽可框选矩形区域
- 对选中区域一键填色或批量写入标签
- 支持一键全选当前板

**多板管理**
- 点击 `+` 新建板，每块板可单独设置名称和板型
- 双击标签页重命名，点 `×` 删除
- 各板数据相互独立

**导出**
- 点击 **export PNG** 导出当前板的高分辨率图片
- 导出内容包含孔内标签和底部颜色图例，可直接插入实验记录

**深色模式**
- 自动跟随系统外观切换

---

## 操作说明

```
单击 / 拖拽       → 涂色
右键单击          → 擦除该孔
双击孔格          → 添加或编辑标签
select 模式拖拽   → 框选多个孔
双击标签页        → 重命名该板
单击颜色文字      → 重命名颜色
```

---

## 本地使用

下载 `index.html`，用浏览器直接打开即可，无需服务器，断网也能用。

---

## 手机使用

用手机浏览器打开网址 → 点击「分享」→「添加到主屏幕」，即可像原生 App 一样从桌面图标打开。


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
- 9 preset colors (sample, control, treated, standard, blank, etc.)
- Click any color label to rename it

**Labeling**
- Double-click a well to add a text label (e.g. `100nM`, `ctrl`, `blank`)

**Batch selection**
- Switch to **select** mode and drag to select a rectangular region
- Apply a color or label to all selected wells at once
- **Select all** button for full-plate operations

**Multi-plate management**
- Add multiple plates with the `+` tab button
- Each plate can have its own name and format
- Double-click a tab to rename; click `×` to delete

**Export**
- Click **export PNG** to download a high-resolution image of the current plate layout, including well labels and color legend

**Dark mode**
- Automatically follows your system appearance

---

## Usage

```
click / drag     → paint wells
right-click      → erase a well
double-click     → add / edit label
select mode drag → rectangle-select multiple wells
double-click tab → rename plate
click color text → rename color
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
