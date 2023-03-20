![圖文互動卡片](./L7.png "導覽列")

### 筆記 -

margin:auto 代表瀏覽器會幫我們自動計算出合適的外邊距，一般常用來置中元素，換句話說就是會把剩下的空間平均分配給四周。剩餘的寬度平均的散落在左右兩邊的邊距上。\
// margin: auto; 把剩餘的空間都給 main-nav 的上下左右\
margin: auto;

// transform 沒作用的原理是因為超連結為 inline 特性\
// transform 不適用於 inline 特性 必須改為 inline-block

display: flex 把直屬的子元素 轉換為 flex 屬性

左 50%、右 50%代表這東西在中間，0 是回到最左跟最右的位置，所以會往兩側位移\
a::after{\
  left: 50%;\
  right: 50%;\
}\
a:hover::after{\
  left: 0;\
  right: 0;\
}  


input:focus,\
  button:focus {\
  outline: none;\
}