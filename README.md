<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Website Layout</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
-moz-box-sizing:border-box; 
   box-sizing:border-box;
}

body, html {
  position: relative; 
  height: 100%; 
  width: 100%; 
  overflow: hidden;
}

body { 
  background-color: #fff; 
  margin: 0; 
}

h1 {
  position: absolute; 
  top:0; 
  left :0; 
  z-index: 10;
  width: 100%;
  text-align: center; 
  font-family: 'Roboto', Arial, Helvetica, sans-serif;
  margin-top: 30px; 
  font-size: 16px; 
  color: #f54955; 
}

p { 
  position: absolute; 
  bottom:0; 
  left :0; 
  z-index: 10; 
  width: 100%; 
  text-align: center; 
  font-family: 'Roboto', Arial, Helvetica, sans-serif;
  color: #999999;  
  margin-bottom: 30px; 
  font-size: 14px;
}

p a {
  color: #f54955; 
  text-decoration: none; 
  outline: none;
}
        
.container {
  position: relative; 
  margin: 80px; 
  background-color: #fff; 
  width: calc(100% - 160px); 
  height: calc(100% - 160px); 
  overflow: hidden; 
}

/* glitch elem must have absolute position */
 .glitch-img {
   position: absolute; 
   width : 100%; 
   height : 100%; 
   top: 0 ; 
   left : 0; 
   background-position:center;  
   -moz-background-size:cover;
   -o-background-size:cover;
   -webkit-background-size:cover;
   background-size:cover;
   opacity : 1
 } 
</style>
</head>
<body>

<div class="header">
  <h1>Header</h1>
</div>

</body>
</html>

