# Claude 自製 Skills

## 📦 包含的 Skills

| Skill | 說明 | 觸發關鍵字 |
|-------|------|-----------|
| resume-health-check | 履歷健診（資管系大三生申請實習） | 幫我看履歷、履歷健診 |

# 📄 履歷健診 Skill — resume-health-check

專為**資管系大三生申請大四實習**設計的 Claude Skill。  
輸入一份履歷，即可獲得結構化的健診報告與優化建議。

---

## ✨ 功能說明

| 功能 | 說明 |
|------|------|
| 第一頁必備要件檢查 | 確認履歷是否包含求職必要元素 |
| 各區塊詳細建議 | 針對每個履歷區塊給出具體改善方向 |
| 整體優化行動清單 | 條列出優先修改的待辦事項 |

---

## 🔧 安裝步驟

### Step 1：下載 SKILL.md

點以下連結進入 GitHub 頁面：

👉 [resume-health-check/SKILL.md](https://github.com/tumitu/text-mining-course/blob/main/resume-health-check/SKILL.md)

右上角點 **`Raw`** → 對頁面按右鍵 → **「另存新檔」** → 儲存為 `SKILL.md`

---

### Step 2：下載 master_prompt.md

點以下連結進入 GitHub 頁面：

👉 [resume-health-check/references/master_prompt.md](https://github.com/tumitu/text-mining-course/blob/main/resume-health-check/references/master_prompt.md)

同樣右上角點 **`Raw`** → 對頁面按右鍵 → **「另存新檔」** → 儲存為 `master_prompt.md`

> ⚠️ 此檔案是 SKILL.md 運作時會參照的核心提示詞，**必須一起下載**，否則 Skill 無法完整執行。

---

### Step 3：上傳到 Claude.ai

1. 前往 [claude.ai](https://claude.ai)
2. 左側選單點 **`Skills`**
3. 點 **`Create skill`** → **`Upload a skill`**
4. 先選擇 `SKILL.md` 上傳
5. 上傳完成後，再把 `master_prompt.md` 加入 references
6. 確認內容後儲存

---

### Step 3：確認安裝成功

在 Claude 對話框輸入以下任一關鍵字，Skill 即會自動啟動：

```
幫我看履歷
履歷健診
幫我健診履歷
履歷診斷
履歷修改建議
```

---

## 📁 檔案結構

```
resume-health-check/
├── SKILL.md                      ← Skill 本體（安裝只需此檔）
└── references/
    └── master_prompt.md          ← 詳細提示詞參考文件
```

---

## 📋 適用對象

- 私立科大資管系大三學生
- 正在準備申請大四實習
- 履歷方向：IT 與資管相關職缺

---

## ⚠️ 注意事項

- 安裝時需要同時下載 `SKILL.md` 與 `references/master_prompt.md` 兩個檔案
- `master_prompt.md` 是核心提示詞，缺少此檔案 Skill 無法完整執行
- 需要有 [Claude.ai](https://claude.ai) 帳號才能使用
