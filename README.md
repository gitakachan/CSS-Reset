# CSS-Reset筆記：

- 外容器和圖片寬度不要寫死，改用max-width
    - max-width可以自適應不同裝置寬度
- 內元素盡量使用％

#### 圖片RWD:
 * 避免破版
```
img{
    max-width:100%; 
    height:auto;
    }
```

#### boxsizing：
  * 方便計算尺寸
```
*, *::before, *::after{
	box-sizing: border-box
}
```
