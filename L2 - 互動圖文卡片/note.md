![圖文互動卡片](/L2.png "圖文互動卡片")

### 筆記 -

vertical-align: middle;
  // 當 img 放在 div 中，會發現圖片與 div 底部有一小塊留白
  // 而 vertical-align 屬性預設值是 baseline，baseline 的設定會讓文字和其父元素的基（準）線對齊，這條基線會和最下方有些空間
  // vertical-align 改成 baseline 以外的屬性  (在 display: block下 沒有用)
  // vertical-align: top | bottom | text-top | text-bottom;
  
position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0; // 沒有寬高 自然拉伸填滿父元素

transition 運用

div:hover div 運用

偽元素運用