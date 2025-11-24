# 群規 V2.0（Engineer Spec）
**Document Type:** Group Governance Specification  
**Maintainer:** Highest Admin  
**Revision:** 2.0  
**Status:** Stable  

---

## 0. Scope
本文件定義群組之功能、邏輯約束、禁行操作、例外條款，以及管理員行為準則。  
適用於所有成員，加入群組即視為接受本規範。

---

## 1. Group Definition
- 本群為自由導向、行動導向之討論環境。  
- 目標：高質量資訊交流、理性討論、行動策略思考。  
- **不接受**任何已加入其他政治團體之成員（如：螞蟻幫、新中華聯邦、法輪功、QAnon 等）。

---

## 2. Behavior Requirements

### 2.1 Political Content
- ❌ 禁止粉紅、五毛、極權敘事之宣傳。  
- ✔ 允許客觀事實描述。  
- Rule: `factual != propagandistic`

---

### 2.2 Interpersonal Interaction
- ❌ 禁止人身攻擊／辱罵／挑釁／約戰。  
- ✔ 允許尖銳的議題辯論（需對事不對人）。  

**Escalation Path:**  
1. 衝突 → 提交管理員處理  
2. 禁止延伸攻擊或騷擾  

**粗口規範：**  
- 可用於外部事件  
- 若造成群友不適 → 必須道歉  

**關於「支那」：**  
- Allowed：自稱／外部第三方  
- Forbidden：作為攻擊性指向群友

---

### 2.3 Info Security & Spam
- ❌ 禁止垃圾訊息、廣告、釣魚網站。  
- ✔ Fact-check 與查核謠言不受限制。  
- 加入後需隱藏個資（電話／郵箱）。  
- 交友行為允許，但需自行評估風險並確認身分。

---

## 3. Invitation Policies
- 可邀請新成員，但 **必須事先閱讀本群規**。  
- 若邀請者拉入廣告機器人 → 邀請者將被移除。  
- 拒絕「歷史無用論」立場，持此立場成員將被移除。  
- Highest Admin 保留最終踢人裁量權。

---

# 4. Ignorance Handling System  
**（本群核心運作模組）**

## 4.1 Definitions

### Unknown (Not Knowing)
- Type: `Information Gap`  
- 行為：願意查證、願意學習  
- Action: `educate()` + `support()`  

### Ignorance
- Type: `Faulty Knowledge System`  
- 特性：  
  - persistent errors  
  - resistance to correction  
  - low logic quality  
  - disruption of discussion  

**Statement:**  
> Ignorance isn’t innocence, but sin.

---

## 4.2 Ignorance Indicators
符合任一條件即可判定為 `ignorance`：

- 拒絕提供資訊來源  
- 被更正後仍堅持錯誤  
- 以情緒、陰謀論代替推理  
- 干擾討論流程  
- 缺乏基本常識且拒絕補課  
- 在誤解情況下輸出錯誤結論  

---

## 4.3 Action Model

### Unknown（可教型）
```
if state == unknown:
    educate()
    no_removal()
```

### Ignorance（無知型）
```
if state == ignorance:
    warn(1)
    warn(2)
    remove(3)
```

### Severe Case
```
if severe == True:
    remove(immediate)
```

Highest Admin 可跳級執行 `remove()`。

---

## 5. Ideological Constraints
禁止宣傳以下意識形態（討論不在此限）：

- Marxism / Communism  
- Socialism (all variants)  
- Collectivism  
- Extreme-left ideologies  
- Anti-Semitism  
- Anti-Zionism  

❌ 禁止任何形式的反人類言論（直接移除）。

---

## 6. Additional Rules
- 禁止在群主領域進行「溜狗」（攻擊性挑釁）。  
- 不鼓勵對管理層進行陰謀式揣測。  
- 管理員應依規範執行，不針對個人。

---

**End of Document**
