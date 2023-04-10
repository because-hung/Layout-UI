![圖文互動卡片](./L13.png "側邊選單")

### 筆記 -

// 無障礙網站技術\
aria-hidden=”true” 可以讓朗讀軟體讀不到此元件。\
帶此屬性的內容時會自動跳過，以免殘障人士混淆！

// placeholder 改顏色\
input::placeholder { /* CSS 3 標準 */\
  color: tomato;\
}

::-webkit-input-placeholder { /* Chrome, Safari */\
  color: tomato;\
}

// 物件會消失
transform: scale(0);