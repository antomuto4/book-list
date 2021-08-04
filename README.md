# book-tracker

A site to keep track of what you read, offline.
The source code and hosted website is for me personally, however I have provided the Sample Code so you can host your own. (locally, if you will)

### The Sample Code
```<html>
<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
body {
   background-color: #1c191c;
   color: #e1ceda;
   margin-left: 20%;
   margin-right: 20%;
   margin-top: 3%;
   margin-bottom: 3%;
   font-family: 'Open Sans', sans-serif;
}
.wrapper {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 10px;
}

img{
width:140px;
height:200px;
}

img:hover{
   transition: transform .2s;
   transform:  scale(1.5);
} 
</style>
<head>
</head>
<body>
   
<!-- [Important Rules]
   To stack upon each other. Use: <br> 2 times
      <br><br>
   To add something, use the following layout:
      <img src="link of the image"><br>title-of-book
   And put it in the needed div that counts as the score you want to give that book.  -->


   <h1>Reading</h1>
   <div class="wrapper">

      <br><br><br>
   </div>

   <h1>Planning</h1>
   <div class="wrapper">

      <br><br><br>
   </div>

   <h1>Paused</h1>
   <div class="wrapper">

      <br><br><br>
   </div>

   <h1>Dropped</h1>
   <div class="wrapper">

      <br><br><br>
   </div>

   <h1>Completed</h1>
   <div class="wrapper">

  <div>⭐

   <br><br><br>

  </div>
 
  <div>⭐⭐

   <br><br><br>

  </div>

  <div>⭐⭐⭐

   <br><br><br>

  </div>

  <div>⭐⭐⭐⭐

   <br><br><br>
   
  </div>

  <div>⭐⭐⭐⭐⭐

   <br><br><br>
   
  </div>

</div>

</body>
</html>

