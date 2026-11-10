# PACU — Minimalist Editorial Business Document Suite (极简现代商务单据模板全集)

一套基于 **PACU (Evergrow Health Supplies Limited)** 品牌视觉规范打造的极简现代商务单据模板系统（共 **6 类核心外贸与现货业务单据**），采用瑞士网格排版（Swiss Editorial Grid）、100% 原始像素轮廓矢量化提取的 `PACU` 标志，以及标志性的 **Royal Blue (`#071C83`)** 与 **Sunny Yellow (`#F5D400`)** 配色。

---

## 📂 包含的 6 类业务单据模板

| 编号 | 单据类型 | 可编辑 HTML 模板 | 渲染版 A4 PDF | 原始参考数据摘要 |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **CNY Sales Receipt (内地现货人民币收据)** | [`pacu_invoice_template.html`](./pacu_invoice_template.html) | [`PACU_Sales_Receipt_MG-NJ-26NOV-L0-PW.pdf`](./PACU_Sales_Receipt_MG-NJ-26NOV-L0-PW.pdf) | `MG-NJ-26NOV-L0-PW` · 客户：`内有玄机-NJ` · 合计：`CNY 1.545,00` (含底部回执联 + `.xlsx` 模板) |
| **02** | **HKD Sales Receipt (港现货港币收据)** | [`pacu_sales_receipt_hkd.html`](./pacu_sales_receipt_hkd.html) | [`PACU_Sales_Receipt_MG-DQ-26SEP-L0-PW.pdf`](./PACU_Sales_Receipt_MG-DQ-26SEP-L0-PW.pdf) | `MG-DQ-26SEP-L0-PW` · 客户：`邓全记-DQ` (`HONG KONG`) · 合计：`HKD 3.380,00` (含底部回执联) |
| **03** | **Delivery Note (香港送货单)** | [`pacu_delivery_note.html`](./pacu_delivery_note.html) | [`PACU_Delivery_Note_24-10-2026.pdf`](./PACU_Delivery_Note_24-10-2026.pdf) | `24/10/2026` · 客户：`鄧全記` · `MEGA ZOO` 袋/箱双栏统计 (`72 袋 / 5 箱`) + 签章栏 |
| **04** | **Commercial Invoice (含海运商业发票)** | [`pacu_commercial_invoice.html`](./pacu_commercial_invoice.html) | [`PACU_Commercial_Invoice_013-2025.pdf`](./PACU_Commercial_Invoice_013-2025.pdf) | `013-2025` (`Jan 7, 2026`) · `MASTERZOO` → `Evergrow` · 36 项明细 + 海运费 · 合计：`USD $ 23.456,49` |
| **05** | **Packing List (10 托盘出口装箱单)** | [`pacu_packing_list.html`](./pacu_packing_list.html) | [`PACU_Packing_List_013-2025.pdf`](./PACU_Packing_List_013-2025.pdf) | `013-2025` (`Dec 12, 2025`) · 按 `PALLET 1–10` 分组 36 项 · 净重 `4852,00Kg` / 毛重 `5063,92Kg` (已去除草稿红字水印) |
| **06** | **Export CIF Invoice (台湾铠成 62 项发票)** | [`pacu_cif_invoice_261001.html`](./pacu_cif_invoice_261001.html) | [`PACU_CIF_Invoice_261001.pdf`](./PACU_CIF_Invoice_261001.pdf) | `INVOICE # 261001` (`Oct. 05, 2026`) · `KAIN CHENG` → `Evergrow` · 单页 62 项明细 · 合计：`549` 件 / `US$8,955.27` |

- **总览入口页**：[`index.html`](./index.html)
- **Excel 自动计算收据模板**：[`PACU_Sales_Receipt_Template.xlsx`](./PACU_Sales_Receipt_Template.xlsx)

---

## ✨ 视觉与工程特性

1. **极简现代商务视觉 (Minimalist Editorial)**：
   - 顶部 `6px` 品牌比例色带（`76% #071C83` 深皇室蓝 + `24% #F5D400` 暖阳黄）。
   - 锋利紧凑的商务表格结构，表头统一使用 `#071C83`，最终汇总行采用 `#F5D400` 重点高亮。
   - 页脚锚定克制的 `10px–14px` 品牌双色流体波浪收尾。
2. **单页 A4 精准排版**：
   - 无论是 3 行的收据/送货单，还是 36 行的商业发票/10 托盘装箱单，乃至 62 行的出口 CIF 发票，均经过精确字号与行高调校，**100% 完整收纳于单页标准 A4 (`210mm × 297mm`)**。
3. **所见即所得在线编辑**：
   - 所有 HTML 模板均开启 `contenteditable="true"`，在浏览器中打开即可直接点击修改任意文字、单号、日期、数量或金额，点击右上角 **Print / Save A4 PDF** 即可导出矢量 PDF。
