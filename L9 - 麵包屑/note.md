![圖文互動卡片](./L9.png "麵包屑")

### 筆記 -

Css 選取器

1. > 大於符號

選擇「位在下一層”內”所有符合指定名字的元素」(所有所有符合指定名字的兒子，不會選到孫子輩)

span\
  div son // green\
  div son // green\
  span\
    div grand son

div > p {\
color: green;\
}

最後呈現的結果：所有在 div 底下第一層裡面的ｐ全部被變成綠字，但是 div 底下 span 裡面的 p 沒有受到影響。

2. + (加號) 

選擇「位在同一層跟在後面的第一個元素」(選擇一個跟在後方的兄弟姊妹)

span\
  first p // red\
  second p

span + p {\
  color: red;\
}

最後呈現的結果：只有緊接在span後面的第一個ｐ被改成紅字。

3. ~

選擇「位在同一層的所有符合指定名字的元素」(選擇所有符合指定名字的兄弟姊妹)

span\
  first p // red\
  second p // red

span ~ p {\
  color: red;\
}

最後呈現的結果：所有在span後面的ｐ全部被改成紅字。
