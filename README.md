# 3d-print-lab

A personal 3D printing workshop for custom parts, remixing existing models, CAD experiments, and practical everyday inventions.

個人 3D 列印工作坊：客製零件、既有模型改作、CAD 實驗與日常實用發明。

## 專案結構

每個專案放在 `projects/<project-name>/`，獨立管理：
- `README.md`：目標、範圍與目前狀態
- `source/`：來源連結、作者、授權資訊與查證紀錄
- `cad/`：可編輯 CAD 與修改筆記
- `exports/`：經授權確認、可公開的列印輸出
- `photos/`：經隱私檢查、可公開的照片
- `tests/`：列印參數、試裝結果與修改紀錄

`docs/` 放共用流程與公開前檢查清單。

## 專案

[Anker Nano A1665 V2 簡化保護殼](projects/anker-nano-a1665/README.md)

Anker Nano A1665 專案已於 2026-10-08 獲授權完成 V2 模型修改、匯出與切片驗證；使用者已送出首次列印，完成與試裝結果待確認。第三方模型及衍生檔只留本機，公開文件見專案紀錄。

[可拆式聯動插頭保護套](projects/tethered-plug-protector/README.md)：2026-11-07 建立，PLA 分件活動連接，V01 首輪試印版；模型與衍生檔留本機，配合尺寸及耐用性待實測。

[躺姿仙子伊布掃描 POC](projects/sylveon-scan-poc/README.md)：2026-11-12 建立；V03 掃描薄殼、V04–V06 二創與 V07 整體平滑的外觀均被否決。V08 分部位修順的外觀預覽已產出，待使用者確認，尚未薄殼或切片。模型與私人資料僅留本機，未啟動實體列印。

## 公開與授權

這是 Public repository。第三方原始模型及其衍生 CAD／輸出檔，都必須先確認授權允許公開再散布；來源可下載不代表可再散布。

授權不明時，只提交來源連結、授權資訊與製作筆記。未確認的檔案留在被忽略的 `unreviewed/` 或 `private/` 目錄，不得提交。照片上傳前也要檢查隱私。

本庫未套用統一開源授權；公開可見不等於授予所有內容的使用權。個別素材須依其明確記錄的授權使用。詳見 [公開前檢查清單](docs/publishing-checklist.md)。
