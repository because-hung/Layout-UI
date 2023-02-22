![圖文滿版區塊 - 多重背景設定](/L1.png "圖文滿版區塊 - 多重背景設定")

### 筆記 -

background: 
  linear-gradient(115deg, #7bf 50%, transparent 50%) center center / 100% 100%,
  url("https://picsum.photos/1200/600?random=10") right center / auto 100%;
  // 兩個元素.參數放在一起使用


RWD 大小
  width: 100%;
  max-width: 1200px;

flex
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: start;
  // 主軸與次軸交換  預設情況下  次軸會自動填滿主軸的寬高
  // 所以要用  align-items: start;  讓他不填滿