# 6.advanced-flexbox
## program:
```
<!DOCTYPE html>
<html>
  <head>
    <title>advanced flexbox</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    
        <div class="content">
      <div class="item1">1</div>
      <div class="item2">2</div>
      <div class="item3">
        <div class=nestest>
          <div class="item">1</div>
          <div class="item">2</div>
          <div class="item">3</div>
      </div></div>
        <div class="item5">4</div>
      <div class="item6">5</div>
      </div>
      
  </body>
</html>
body{
  padding:0;
  margin:0;
  font-family:Arial;
  
  
}
.content{
  display:flex;
  flex-direction:column;

 
 }
 
.content>div{
  background-color:grey;
  margin:5px;
  border:2px solid #ccc;
  height:4vh;
  color:white;
  
}
.nestest>div{
  background-color:white;
  color:black;
}
.nestest{
  display:flex;
  flex-wrap:wrap;
  justify-content:space-evenly;

  
}
```
## output :
![WhatsApp Image 2024-07-14 at 22 27 34_1207bfc1](https://github.com/user-attachments/assets/96961041-77ef-485e-be50-e68d5369903c)

 
