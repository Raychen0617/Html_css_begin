# HTML & CSS NOTE

`<!DOCTYPE html>`   // add infront of the begining <br><br>
`<html>` ------> most outer tag <br>
## CSS SELECTOR
`style` 可集中管理css的設定 {}代表一組 <br>
code example :<br>

### /* 標籤名稱選擇器*/
```
body{
 font-size: 16pxl font-family:"";
}

h3{

}
```

### /* class 選擇器 ---> 前方加 . */
```
<style type = "text/css">
.content{css setting1}
.title {css setting2}
</style>

<body>
 <div class = "content">  <div/>
</body>
```
### /* id 選擇器 ---> 前方加 * */
```
<button id="btn"></button>

#btn{
}
```

### /* 虛擬選擇器:搭配其他選擇器使用 */
```
/* : hover 虛擬選擇器 ---> 當滑鼠移上去的時候，套用一組設定 */
#btn:hover{
}
/* : focus : 當目標對象取得焦點時(被滑鼠點到時)，套用一組設定 */
input:focus{
}
```
### /* 階層選擇器:搭配其他選擇器使用 */
```
a{
 color: #0000ff;
}
// 當同一個tag想要有不同設定時使用
.favorite a {
 color : #0088000;
}
// 需先找到class (favorite)，在套用setting to the tag

<div class="favorite">
 <a href=" ">
</div>

```
## head
`<head>` -----> second outer tag  (describe the website) <br>

## body
### `<body>` -----> second outer tag  
### describe what will display on the website <br>
`<h3>` 3rd title (數字越小，標題越大) <br><br>
`div` 區塊式標籤 會斷行 (可用 span 避免換行) <br>
### css statement
* font-weight : bold <br>
* font-size <br>
* color <br>
### css box model
* width
* height 非必要不會去調整
* margin-top margin-bottom 
* border
* solid  單實線--->邊框樣式
* dashed 虛線
* color
* padding : box 內部文字跟邊框之間的像素距離

`<img>`attribute : src="放入影像的位置" <br><br>
`ul` 列表 <br>
  * `li` 列表的每一項 <br>

`a` a href = "要連線的網址" <br><br>
`table` 建立表格---->  attribute: border, width, cellpadding(表格框框中填多少像素) <br> 
* `tr` 表格中的每一列 <br>
* `td` 表格每一列中的第幾欄 <br>
** `<b>` 粗體字 <br>
** `<u>` 底線 <br>

`<hr>` 分割線 <br>

 
 


 
  

