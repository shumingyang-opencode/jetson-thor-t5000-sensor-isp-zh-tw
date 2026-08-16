# NVIDIA Jetson Thor T5000 感測器影像調適繁中教學站

把 Jetson Thor T5000 上的 sensor 影像調適（MIPI CSI-2 / Holoscan Sensor Bridge / NVIDIA ISP / 影像品質調校）做成**中英對照**的 16 單元分層教學。Thor 為新平台，部分細節參考同平台 T4000。

- 目標讀者：機器人 / 邊緣 AI / 相機工程師、學生
- 單元數：16（含 5 個影像調校專章 + 跨平台比較）
- 授權：本站內容 CC-BY-4.0
- 網站：https://shumingyang-opencode.github.io/jetson-thor-t5000-sensor-isp-zh-tw/

## 單元一覽

| # | 單元 | 內容 |
|---|------|------|
| 01 | 平台相機生態總覽 | CSI-2/HSB、Jetson+Holoscan |
| 02 | 影像感測器基礎 | Bayer、global shutter |
| 03 | 感測器通訊介面 | I2C/SCCB、register |
| 04 | 相機框架與驅動 | Jetson 堆疊 + Holoscan |
| 05 | 第一個鏡頭跑起來 | argus / HSB 取流 |
| 06 | Sensor Bring-up 與除錯 | HSB/CSI 除錯 |
| 07 | ISP 管線深入 | Blackwell ISP |
| 08 | RAW 擷取與資料格式 | RAW、bayer、HSB 資料 |
| 09 | 各平台 ISP 架構差異 | Thor vs 其他 |
| 10 | 曝光與自動曝光（AE） | Argus 曝光控制 |
| 11 | 白平衡與色彩（AWB/CCM） | NVIDIA AWB/CCM |
| 12 | 鏡頭陰影校正（LSC） | NVIDIA LSC |
| 13 | 雜訊與降噪 | NVIDIA NR |
| 14 | 清晰度/HDR/調校工作流 | NVIDIA tuning 流程 |
| 15 | 四平台影像調校比較 | Thor 視角 |
| 16 | 多感測器與實作案例 | HSB 多相機 |

## 開發

純靜態 HTML，無建置步驟。

```sh
python3 -m http.server 8000 -d .
```

## 相關連結

- 學習路徑建議服務：[learning-path-advisor](https://shuming-yang.github.io/learning-path-advisor/) — 依角色推薦教學網站學習路徑
