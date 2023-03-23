![圖文互動卡片](./L10.png "方塊酥")

### 筆記 -


overflow: hidden;
// 讓父層能夠抓到所有子層的高度 類似clear消除float效果(在父層設定)


transition 放大互動效果 (scale)

.txt{\
opacity: 0;\
transform: scale(0);\
transition: .5s;\
}

&:hover .txt{\
opacity: 1;\
transform: scale(1);\
}

width:100%;\
padding: 15px;\
box-sizing: border-box;\
width 設置 100%後 根據盒模型 再加上 padding 會超過 100% 所以要加上 box-sizing: border-box 才會符合等於 100%

&:first-child ~.item {\
width: 25%;\
}

選取同層後面所有的 item
