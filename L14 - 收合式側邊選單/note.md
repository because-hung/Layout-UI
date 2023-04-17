![圖文互動卡片](./L14.png "收合式側邊選單")

### 筆記 -
// for 對 input checkbox 控制的 id\
// 可以實現點擊控制功能\
  *input type="checkbox" id="sidebar-switch"*
  *label for="sidebar-switch"*

// top 0  bottom 0  margin: auto; 可以垂直居中\
  top: 0;\
  bottom: 0;\
  margin: auto;

checkbox #sidebar-switch {\
   * 設定絕對定位不佔空間\ 
   * opacity 隱藏\ 
   * z-index 讓層級往下放 避免點到\
  position: absolute;\
  opacity: 0;\
  z-index: -1;\
}

scaleX(-1) 可以鏡像左右反轉\
也可以用 rotate\
transform: rotate(-180deg);
