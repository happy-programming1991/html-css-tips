### 默认table、td 的宽度会由table、td包含内容决定。
#### 方案一（固定table宽度、td宽度）：
``` css
  table {
    table-layout: fixed; // defalut value is auto
    width: 100px;
  }
  
  table td {
    width: 20px;
  }
```
#### 方案二（设置td display属性）：
``` css
 td {
   display: inline-block;
   width: 30px;
 }
```

##### 参考文档：["Fixed Table Layouts"](https://css-tricks.com/fixing-tables-long-strings/)、 [MDN "table-layout"](https://developer.mozilla.org/zh-CN/docs/Web/CSS/table-layout)
