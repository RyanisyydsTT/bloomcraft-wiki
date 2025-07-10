# 🌾 PyroFarming Plugin Guide (Bilingual)

> This document provides a **fully English** overview of the Farming plugin system **Traditional Chinese translations**.
---

## 📘 Basic Commands | 基本指令

| Command         | Description                                    | 指令說明                |
| --------------- | ---------------------------------------------- | ------------------- |
| `/farm`         | View all PyroFarming commands                  | 查看所有 PyroFarming 指令 |
| `/farm menu`    | Open the farming main menu                     | 開啟農業主選單             |
| `/farm help`    | Open the in-game help book                     | 開啟說明書               |
| `/farm codex`   | Open the farming codex of all crops and bushes | 開啟植物與灌木圖鑑           |
| `/farm elysium` | Check your Elysium balance                     | 檢查你的伊利森幣餘額          |
| `/farm market`  | Open the seed/bush market                      | 開啟市場購買種子與灌木         |
| `/farm shop`    | Sell harvested plants                          | 出售收成的作物             |

---

## 🌱 Plant System | 植物系統

**Growstation** is the core planting machine. Craft it via `/farm menu`. Initial limit: 10 stations. Growstation = 培育站

Growstations require water. Without it, plants won’t grow. Right-click to open the station UI.

> **培育站** 是種植核心，最多放置 10 個，需加水才能運作。

### Growstation Stats | 培育站升級能力

* **Water**: More water per bucket fill | 每次加水更多
* **Elysium**: Earn more Elysium on harvest Elysium = 伊利森 | 收成時獲得更多伊利森幣
* **Growth**: Slight speed boost to growing | 成長速度加快
* **Mutation**: Chance to gain random Trait | 植物獲得隨機特性

---

## 🌡 Temperature System | 溫度系統

Each plant requires a specific temperature based on biome:

| Biome Type | Value | 生物群系類型 |
| ---------- | ----- | ------ |
| Glacial    | -3    | 冰川     |
| Freezing   | -2    | 冰點     |
| Cold       | -1    | 寒冷     |
| Normal     | 0     | 正常     |
| Warm       | +1    | 溫暖     |
| Hot        | +2    | 炎熱     |
| Boiling    | +3    | 沸騰     |

> `ANY` temperature means it can grow in any biome. 任何溫度均可生長的植物會標記為 `ANY`。

---

## 🌍 Environment Requirement | 環境限制

Plants may only grow in:

* Overworld 主世界
* Nether 地獄
* End 終界

Some plants require a special "orb" to simulate this environment.

---

## ⚔ Temperament System | 氣質系統

* **Friendly**: Won’t attack any mobs | 不攻擊任何生物
* **Normal**: Attacks mobs, not players | 攻擊生物但不攻擊玩家
* **Aggressive**: Attacks everything | 攻擊所有目標（包括玩家）

> Affects how Traits behave. 特性行為會受到氣質影響。

---

## 🌿 Bushes | 灌木系統

Place bushes to passively grow items (as player heads). Break or click to harvest. Bush = 灌木

* High cost, low yield
* No watering or care required

> 灌木是自動產物，不需照顧，長期獲利。

---

## 🏪 Farm Market | 農夫市場

* **Permanent Shop （永久）**: Always available seeds/bushes
* **Rotating Shop （輪替）**: Discounted, changes daily

> 永久商店與每日輪替折扣商品。

---

## 🧺 Farm Shop | 農場商店

Sell your harvested plants here.
Some items cannot be sold—they are used in crafting.

> 用 `/farm shop` 出售收成，部分作物為合成用途無法販售。

---

## 📚 Skill Archive | 技能檔案

Craft using:

* 4 Tomato 🍅
* 4 Lettuce 🥬
* 1 Lectern 書桌

Place in a 5x5x5 area.

> 製作技能檔案後可解鎖種植與灌木技能。

### 📘 Plant Skill Branch | 植物技能

| Level | Skills                                   | 技能              |
| ----- | ---------------------------------------- | --------------- |
| 1     | More Growstations, Rain Fill, Tank Boost | 更多培育站、雨水加水、加強水槽 |
| 2     | Mutation Chance, XP Boost                | 突變機率、經驗加成       |
| 3\~4  | More Station Limits                      | 提升可放置培育站上限      |

### 🌳 Bush Skills | 灌木技能

* Increases max bush count 每升級可放更多灌木

### 🍞 Vanilla Enhancements | 原版功能加成

* Farming Fortune 掉落量加成
* XP Gain 農業經驗提升
* No Crop Trample 不會踩壞作物
* Right Click Harvest 右鍵收割

---

## 🛠 Custom Items | 自訂道具

Right-click a **Composter** with a **Hoe** to open crafting.

### 🔥 Temperature Tools | 溫度工具

| Item               | Temp Effect | Required Lv | 中文名稱   |
| ------------------ | ----------- | ----------- | ------ |
| Lava Lamp          | +1          | 25          | 熔岩燈    |
| Pyrotheum Orb      | +3          | 40          | 硫磺寶珠   |
| Heart of Belphegor | +5          | 55          | 貝爾菲戈之心 |
| Industrial Fan     | -1          | 25          | 工業風扇   |
| Subzero Wisp       | -3          | 40          | 冰晶幽靈   |
| Vessel of Boreas   | -5          | 55          | 北風之器   |

### ⏩ Growth Speed Boosters | 成長加速器

| Item                     | Boost | Required Lv | 中文名稱  |
| ------------------------ | ----- | ----------- | ----- |
| Basic Water Golem        | +4%   | 30          | 基礎水傀儡 |
| Intermediate Water Golem | +8%   | 50          | 中級水傀儡 |
| Advanced Water Golem     | +12%  | 70          | 高級水傀儡 |

### 🌐 Environment Orbs | 環境寶珠

| Item          | Effect             | Required Lv | 中文名稱  |
| ------------- | ------------------ | ----------- | ----- |
| Overworld Orb | Simulate Overworld | 50          | 主世界寶珠 |
| Nether Orb    | Simulate Nether    | 50          | 地獄寶珠  |
| End Orb       | Simulate End       | 50          | 終界寶珠  |

---

## 📖 Codex | 圖鑑系統

Use `/farm codex` to:

* View all plant/bush types
* See requirements and traits
* Unlock progression

> 圖鑑能讓你查看所有植物特性與解鎖狀態。

