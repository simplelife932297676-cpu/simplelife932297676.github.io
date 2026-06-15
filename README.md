# 兒童遊戲樂園

一個適合2-12歲兒童的線上遊戲平台，包含三個不同主題的遊戲，寓教於樂。

## 遊戲內容

### 🧩 記憶配對遊戲
鍛鍊兒童的記憶力和邏輯思考能力，透過翻牌配對找出相同的圖案。

### 👗 小小装扮家
角色扮演遊戲，讓兒童自由選擇服裝、顏色、表情和配件，發揮想像力創造角色。

### 📚 數學小天才
數學學習遊戲，包含加法、減法、乘法運算，難度會隨等級提升。

### 📝 課程心得
記錄學習心得的功能，支持儲存、編輯和刪除。

## 功能特色

- ✅ 繁體中文/英文雙語切換
- ✅ 響應式設計，支援手機和電腦
- ✅ 本地儲存遊戲進度
- ✅ 明亮繽紛的色彩設計
- ✅ 簡單易懂的操作介面

## 技術棧

- HTML5
- CSS3 (Flexbox, Grid, Animation)
- JavaScript (ES6+)
- LocalStorage

## 使用方式

1. 下載或複製此專案
2. 直接在瀏覽器中開啟 `index.html`
3. 選擇想玩的遊戲開始遊玩

```
# 或使用本地伺服器
npx serve .
# 或
python -m http.server 8000
```

## 專案結構

```
├── index.html              # 首頁
├── notes.html              # 課程心得頁面
├── 遊戲說明.md              # 遊戲說明文件
├── css/
│   ├── style.css           # 全域樣式
│   ├── game.css            # 遊戲通用樣式
│   ├── roleplay.css        # 角色扮演樣式
│   ├── educational.css     # 教學遊戲樣式
│   ├── notes.css           # 心得頁面樣式
│   └── language.css        # 語言切換樣式
├── js/
│   ├── main.js             # 主腳本
│   ├── game.js             # 益智遊戲邏輯
│   ├── roleplay.js         # 角色扮演邏輯
│   ├── educational.js      # 教學遊戲邏輯
│   ├── notes.js            # 心得管理邏輯
│   └── translations.js     # 多語言翻譯
├── games/
│   ├── puzzle.html         # 益智遊戲頁面
│   ├── roleplay.html       # 角色扮演頁面
│   └── educational.html    # 教學遊戲頁面
└── assets/
    ├── images/             # 圖片資源
    └── sounds/             # 音效資源
```

## 瀏覽器支援

- Chrome (推薦)
- Firefox
- Safari
- Edge

## 授權條款

MIT License
