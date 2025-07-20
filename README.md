# 👋 你好，這裡是 Fanky Miu 的 GitHub

## 關於我

- 🌏 香港 | 固定收益（Fixed Income）市場專業背景
- 🎯 目前目標：系統學習 Web3、區塊鏈技術、數位資產與交易自動化
- 🏗️ 技術轉型路上，紀錄從金融到程式開發、數據分析、鏈上專案的每一步

## 技能/學習範疇

- 基礎語言：Python、JavaScript
- 金融／鏈上應用：債券分析、區塊鏈基礎、智能合約、量化交易
- 🌟 **重點進修中**：正在積極修讀 [Alchemy University Ethereum Developer Bootcamp](https://university.alchemy.com/)，全長 7 週，已完成第 1 週，持續每日挑戰並精進中！

## 學習與專案進行中

- [x] 以太坊密碼學、雜湊／數位簽章、ECDSA Node.js 全端實作
- [x] 區塊鏈 Proof-of-Work 機制、區塊結構與礦工模擬
- [ ] 智能合約（Solidity）、鏈上自動化腳本開發
- [ ] 個人金融數據回測/量化交易模組

> Alchemy University Bootcamp 每週學習成果與心得筆記，詳見子資料夾與 `notes/` 記錄 📔

## 主要專案：ECDSA Wallet Demo 全端學習歷程

本專案模擬以太坊核心錢包運作，涵蓋私鑰管理、本地簽章、伺服器驗證與 nonce 防重放。

### 主要技術與架構

- **前端**：React，私鑰生成與本地簽章，絕不外傳私鑰
- **後端**：Node.js (Express)，基於簽章驗證交易，管理非同步 nonce 實作 Replay Protection
- **核心密碼學**：secp256k1 曲線、Keccak256 雜湊演算法、ECDSA 簽章流程
- **以太坊 address 標準**：由公鑰經 Keccak256 計算取得 40 字元 hex address

### 功能亮點

- 批量自動生成多組錢包私鑰與地址
- 完整端對端資產查詢與交易簽章驗證
- 伺服器防禦重放攻擊及不當交易
- 端到端流程符合主流 web3 開發實踐與資安最佳化

### 學習心得

- 真正掌握去中心化帳戶管理與簽章流程、Replay Protection 機制設計
- 從分階段開發、錯誤除錯與資安測試獲得豐富實務經驗
- 建立良好紀錄習慣，有助於面試演示與技術分享

### 專案結構範例

ecdsa-node/
├─ client/          // React 前端
├─ server/          // Node.js 後端
├─ wallets/         // 私鑰錢包存檔 (本地)
├─ notes/           // 學習與 bug 紀錄
│    ├─ learning-journey.md
│    └─ bug-records.md
└─ README.md

### 快速啟動

git clone https://github.com/FankyMiu/Fanky-web3-ecdsa-node.git
cd Fanky-web3-ecdsa-node

# 安裝前後端依賴
cd client && npm install
cd ../server && npm install

# 先啟動伺服器
npm run start

# 新開終端啟動前端
cd ../client && npm run dev

### 相關資源與延伸閱讀

- ECDSA 技術與區塊鏈安全解析（Cloudflare Blog）：https://blog.cloudflare.com/ecdsa-the-digital-signature-algorithm-of-a-better-internet/
- Ethereum EIPs - ECDSA 簽章標準介紹：https://github.com/ethereum/EIPs/blob/master/EIPS/eip-191.md
- 🌟 **Alchemy University Ethereum Developer Bootcamp（主修中！）**：https://university.alchemy.com/

---

## 興趣

- 🌱 學習新技術、量化策略、鏈上安全
- 🎲 區塊鏈應用場景、金融市場結構
- 📚 中醫、易經、紫微斗數（探討傳統與現代知識的交融）

## 聯繫我

- GitHub Issues 開放討論與提問
- 歡迎合作及技術交流

---

MIT License | 最後更新：2025-07-17 HKT
