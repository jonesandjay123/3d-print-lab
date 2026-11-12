# 本機處理紀錄

所有工作專案與衍生資料在 `private/`。不得只搬 `.scanproj` 而遺漏其配套資料夾。

V01 流程：保全原始掃描 → JMStudio Generic / Moderate 重建、雜點與浮動部分移除 → 保留未修補 OBJ → JMStudio Repair Gaps → 保留修補 OBJ 及工作專案 → 檢查六面與拓樸 → 移除使用者確認的吊牌 → 保留躺姿、薄殼與底部開口 → 實際切片驗證。

修補前網格有 238,878 faces、6,920 個開放邊；JMStudio 修補後 1,068,742 faces、0 個開放邊、0 個非流形邊。拓樸封閉不代表表面完全忠實：底側大範圍漏掃被自動補成平滑區，必須在外觀限制中明示。

Blender 處理腳本與各階段檢查模型留在 `private/`；具體尺寸、殼厚、底面處理和驗證以 tests 紀錄為準。

## 使用者停止指示

V03 掃描薄殼與 V04–V06 推定平滑二創均被否決外觀，不可稱為完成品。最後保存的二創源檔為 `private/sylveon-v06-editable-sculpt.blend`，薄殼為 `private/sylveon-plush-v06-print-shell.blend`，只供歷史檢視。下一輪優先使用二創前融合 OBJ 與實物照片。停止時沒有本次啟動的 Blender 重建或 Bambu CLI 切片程序仍在執行；原本開著的桌面程式未被關閉。
