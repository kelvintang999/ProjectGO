# ProjectGO

English 版本請見 [README.md](README.md)。

尖沙咀開放世界 3D demo，用 Three.js 寫的——拿真實香港 3D 地圖資料做的可玩網頁原型。

在這裡玩：https://kttcat.github.io/ProjectGO/

## 這是什麼

在瀏覽器裡逛尖沙咀。你一開始站在天星碼頭前廣場，接著可以在 750 × 1200 公尺的地圖上走路、開車、騎車、飛行，穿過 460 棟真實建築。這個網頁 demo 是先拿來驗證核心互動的原型；完整遊戲的目標是 Unreal Engine 5.8 → 6.0。

## 功能

- 走路／開車／飛行，有汽車跟機車
- 吃飯、睡覺、閒晃——有個人房間、換裝、NPC 跟一隻寵物狗
- 白天和夜晚，太陽位置是真的
- 桌面跟手機三檔畫質：Full／Lite／uLite

## 操作

- WASD——移動，Shift——跑，Space——切換飛行
- F——上車／下車
- E——互動（坐下、吃東西、對話）
- J——出拳

## 地圖資料

建築的幾何形狀取自香港地政總署的 Open3Dhk 3D 地圖資料，來源是空間數據共享平台（CSDI）／香港地圖服務 2.0——只要註明來源是香港特別行政區政府，商業跟非商業用途都免費。

## 技術

- Three.js r160、Blender（地圖修補）、GitHub Pages

## 授權

MIT 只覆蓋這個 repo 裡的程式碼，不包括 3D 素材：角色模型是 Mixamo 素材（免版稅使用、不可再分發），地圖幾何是 Open3Dhk 資料（見上方地圖資料）。3D 模型由 Cloudflare R2 提供給 demo 使用，不存放在這個 repo 裡。

Based TPE, HKG
