# jaelynnchesson.github.io

<html>
  <head>
    <meta charset="UTF-8">
    <h1>My Portfolio Website</h1>
    <link rel="stylesheet" href="style.css">
    <meta name="INDEX" content="INDEX,FOLLOW">
    <meta name="description" content="Lehigh University DES 070 Website">
    
  </head>
<body>
  <h1>Hello World!</h1>
  
  <img src="https://cdn.glitch.com/0648f15e-7036-4ca0-8316-92fba02bacaa%2Fglobe.png?v=1629920652846" width="200">
  
  
  <h2>My Webpage</h2>
    <ul>
      <li><a href="me.html">Jaelynn Chesson</a></li>
      <li><a href="email.html">jrc222@lehigh.edu</a></li>
      <li><a href="social.html">Social Media</a></li>
    </ul>
  
  <h2> P1: Interview Project</h2>
    <ul>
      <li><a href="notes.html">Notes</a></li>
      <li><a href="Mywebsite.html">My Website</a></li>
    </ul>
  
  <h2> P2: Wireframe Project</h2>
    <ul>
      <li><a href="easy.html">Easy</a></li>
      <li><a href="hard.html">Hard</a></li>
    </ul>
  
  <h2> P3: Oblique Strategies</h2>
    <ul>
      <li><a href="arena.html">Are.na Channel</a></li>
      <li><a href="mysite.html">My Site</a></li>
    </ul>
  
  
  
  
  
  
  <a class="trigger_popup_fricc">Click here to show the popup</a>

<div class="hover_bkgr_fricc">
    <span class="helper"></span>
    <div>
        <div class="popupCloseButton">&times;</div>
        <p>Add any HTML content<br />inside the popup box!</p>
    </div>
</div>
  
  $(window).load(function () {
    $(".trigger_popup_fricc").click(function(){
       $('.hover_bkgr_fricc').show();
    });
    $('.hover_bkgr_fricc').click(function(){
        $('.hover_bkgr_fricc').hide();
    });
    $('.popupCloseButton').click(function(){
        $('.hover_bkgr_fricc').hide();
    });
});
  
  
  
  </body>
</html>
