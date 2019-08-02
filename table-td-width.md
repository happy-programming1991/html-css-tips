### table 的 td 的宽度会受table的宽度、td中所包含文本的宽度影响。
#### 方案一(固定table宽度、td宽度)：
``` css
  table {
    table-layout: fixed; // defalut value is auto
    width: 100px;
  }
  
  table td {
    width: 20px;
  }
```
#### 方案二（设置td display属性）
``` css
 td {
   display: inline-block;
   width: 30px;
 }
```

##### 参考文章["Fixed Table Layouts"](https://css-tricks.com/fixing-tables-long-strings/)
