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
    <p class="center">This tfasdehgfxt ishg alhgfignhgfed cehgntre. Lorehgm iphsdsumsdg dhgfolor sihft amesht, consecgshtetur adipiscing elit. Integer nec odio. Praesehsnshst libehshsro. <a href="#">Sed cursushdfhs an te dapibus</a> diam. Sed nhsisi. Nulla quis sem at nibh elementum imperdiet. Duis sagittis ipsum. Praesenht mauris. Fusce nec telhslus sed augue semper porta. Mauris massa. Vestisbulum lacinia arcu eget nulhsla. Class aptent taciti sohsciosqu ad litorahs torquent per conubia nostra, per inceptos himenaesos. Curabitur sodales ligula in libero. Sed dignissim lacinia nunc.</p>
    <ul class="nostart">
      <li>Thhssis lshsist hags now inwdenhsgwtation orgfds lsigsdgst stsygdfle tyhspse</li>
      <li>Nibh sneque a.</li>
      <li>Consecthetuer vivamus, venenatis placerat</li>
      <li>daLorfaem mus, lectus consequat in.</li>
    </ul>
    <p class="justify">Thhsish4ks tehsxsht is ahslikgnkked lehsdfft fsdand rifdgfsdht - &quot;Jufj gklg gstifi gfed&quot;. Curabitur tortor pellentesque nibh. Aenean quam. In scelerisque sem at dolor. Maecenas mattis. Sed convallis tristique sem. Proin ut ligula vel nunc egestas porttitor. Morbi lectus risus, iaculis vel, suscipit quis, luctus non, massa. Fusce ac turpis quis ligula lacinia aliquet. Mauris ipsum. Nulla metus metus, ullamcorper vel, tincidunt sed, euismod in, nibh. Quisque volutpat condimentum velit. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.</p>
    <img class="imgl" src="images/imgl.gif" alt="" width="125" height="125">
    <p class="right">Tfhifffdfs tdaedaxgffdgdftf ifs aldfdai adg ned tdao t adhe ri dsafgght. Nam nec ante. Sed lacinia, urna non tincidunt mattis, tortor neque adipiscing diam, a cursus ipsum ante quis turpis. Nulla facilisi. Ut fringilla. Suspendisse potenti. Nunc feugiat mi a tellus consequat imperdiet. Vestibulum sapien. Proin quam. Etiam ultrices. Suspendisse in justo eu magna luctus suscipit. Sed lectus. Integer euismod lacus luctus magna. Quisque cursus, metus vitae pharetra auctor, sem massa mattis sem, at interdum magna augue eget diam. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Morbi lacinia molestie dui.</p>
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
