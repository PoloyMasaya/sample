<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<title>Kanon Tailoring</title>
<meta charset="iso-8859-1">
<link href="css/style.css" rel="stylesheet" type="text/css">
</head>
<body>
<div class="wrapper row1">
  <header id="header" class="clear">
    <img src="images/logo.png" style="width:310px; height:110px;">
    <br>
    <button type="button">Home</button>
    <a href="search.php" class="button" style="float:left; display: block;">Clients</a>
    <button id="login" type="button" onclick="document.getElementById('modal-wrapper').style.display='block'">Log In</button>
    <div id="modal-wrapper" class="modal">
      <form name="login" class="modal-content animate">
    <div class="imgcontainer">
      <h1 style="text-align:center">Kanon Tailoring</h1>
    </div>
    <div class="container">
      <input type="text" placeholder="Enter Username" name="username" id="username">
      <input type="password" placeholder="Enter Password" name="password" id="password">        
      <button class="btn" type="button" onclick="getInfo()">Login</button>
      <input type="checkbox" style="margin:26px 30px;"> Remember me </input>   
      <a href="#" style="text-decoration:none; float:right; margin-right:34px; margin-top:26px;">Forgot Password ?</a>
    </div>  
   </form>
  </header>
</div>
<hr class="head">
<div class="wrapper row2">
  <div id="container" class="clear">
    <h1>We repair while YOU wait</h1>
    <img class="imgr" src="images/imgr.gif" alt="" width="125" height="125">
    <ul>
      <li class="bold">Just sfaskfjsf sf</li>
      <li>Nibh neque asdfas.</li>
      <li><a href="#">Consecfasdtetuer vivamus, venenatis placerat</a></li>
      <li>Ldadasoreasdm mus, lfdhgjtus consequat in.</li>
    </ul>
    <p class="center">SOFTWARE ENGINEERING</p>
    <ul class="nostart">
      <li>hello</li>
      <li>philippines.</li>
      <li>hello</li>
      <li>world</li>
    </ul>
    <p class="justify">deepshit</p>
    <img class="imgl" src="images/imgl.gif" alt="" width="125" height="125">
    <p class="right">douch til i die</p>
  </div>
</div>
<div class="wrapper row3">
  <footer id="footer" class="clear">
    <p class="fl_left">Copyright &copy; 2017 - All Rights Reserved - <a href="#">Kanon Tailoring</a></p>
  </footer>
</div>
<script src="js/adminControl.js"></script>
<script>
// If user clicks anywhere outside of the modal, Modal will close
var modal = document.getElementById('modal-wrapper');
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}
</script>
</body>
</html>
