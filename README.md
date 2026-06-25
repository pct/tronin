# 創音 TronIn

**中英免切換**的 macOS 注音輸入法（**大千**鍵盤）。打中文直接打注音、打英文直接打英文，不用切換。**完全離線、不連雲端、不上傳任何打字內容。**

🌐 官方網站：**<https://tronin.1tron.ai>**

## 下載安裝

1. 到 **[Releases](../../releases/latest)** 下載最新的 **`TronIn-x.y.z.pkg`**（已 Apple 公證，安裝零警告）
2. **按兩下 .pkg** 安裝（會要一次管理者密碼）
3. **系統設定 ▸ 鍵盤 ▸ 輸入來源 ▸ 編輯…／＋** ▸ 繁體中文 ▸ **創音** ▸ 加入
4. **Ctrl + Space**（或選單列的輸入法選單）切到創音，開始打字

> 看不到「創音」？**登出再登入**一次（macOS 對輸入法清單有快取）。

## 怎麼用

- **中英不用切換**：注音能拼成中文就出中文，拼不成就自動當英文。
- **空白鍵**：還沒標聲調時補一聲，已經有聲調時送出。
- **Tab**：英文自動完成、中文換下一組候選字。
- **選字**：按 →／↓／Tab 打開選字視窗，再用 1–9、方向鍵或滑鼠選字，按 Enter 確定。
- **回頭改字**：打字途中按 ← 把游標移到要改的字，按 ↓ 換字、按 Backspace 刪字。
- **符號**：打中文時按符號鍵會跳出中文符號選單；按 `~` 打開更多符號。
- **聯想詞**：送出一個字後按 Tab，會帶出常用詞和你常打的句子。

## 隱私

創音**完全離線**：不連雲端、不上傳任何打字內容。學到的東西（你的常用詞等）只留在你自己這台電腦的
`~/Library/Application Support/TronIn/`。

## 致謝

創音站在許多開放、慷慨的前人成果之上。在此致謝：

- **[小麥注音 McBopomofo](https://github.com/openvanilla/McBopomofo)**（MIT）— 中文詞庫與頻率模型的底座，斷詞演算法也向它學習；其詞彙最早源自 **libtabe**（BSD）。
- **[唯音輸入法 vChewing](https://github.com/vChewing/vChewing-macOS)**（MIT-NTL，© The vChewing Project）— macOS 輸入法註冊流程的參考。
- **[CC-CEDICT](https://cc-cedict.org/)**（CC BY-SA 4.0）— 補上現代詞與專有名詞。
- **[wordfreq](https://github.com/rspeer/wordfreq)**（資料 CC BY-SA 4.0）— 中英判斷用的英文常用字表。

字元 bigram 由創音自有的白話語料訓練。完整逐條的授權聲明見 **[NOTICE](./NOTICE)**；創音自寫的程式碼採 **[MIT 授權](./LICENSE)**，且不依賴任何 GPL/LGPL 函式庫。

## 授權

- 創音自寫的程式碼：**MIT**（見 [LICENSE](./LICENSE)）。
- 第三方資料的授權與標示：見 [NOTICE](./NOTICE)。

---

© 2026 1Tron System Co., Ltd.
