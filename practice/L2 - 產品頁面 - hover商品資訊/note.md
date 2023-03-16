![圖文互動卡片](./L2.png "L2 商品資訊")

### 筆記 -

hover 後 商品資訊會跑出來

利用 height 的差距 去隱藏顯示 商品資訊

.product{\
  height: 50px;\
}

.product:hover{\
  height: 100px;\
  transition: height 0.5s;\
}