# my-files<!DOCTYPE html>
<html>
<head>

<style>
#container {
  width: 300px;
  height: 300px;
  position: relative;
  background: rgb(238, 206, 238);
}
#animate {
  width: 30px;
  height: 30px;
  position: middle;
  background: rgb(14, 156, 76);
}

body {
  background-color: lightblue;
}

header {
padding: 30px;
text-align: center; 
background: white;
}

.header h1 {
font-size: 50px;
}

body {
margin: 1;
}

div {
border: 1px solid black;
background-color: lightblue;
padding-top:50px;
padding-right:30px;
padding-bottom: 50px;
padding-left: 80px;
}

.topnav {
overflow: hidden;
background-color: #333;
}

.topnav a {
float: left;
display: block;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}
</style>

<h1>Second homepage</h1>
<table border= "3" bordercolor="purple" cellspacing="10" cellpadding="10" align="left">
  <center><div class="topnav">
  <a style="border: solid lightblue" href= "main_content_page.html">Homepage</a></h2></td>
  <a style="border: solid lightblue" href= "contact.html">Contacts page</a></h2></td>
  <a style="border: solid lightblue" href="skills_new_template.html">Give feedback</a></h2></td></table></td>
  </div></center>
</ul>   

<body>
<h2>My animations</h2>

<div id="container">
<div id="animate"></div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

<script> 
$(document).ready(function(){
  $("button").click(function(){
    $("div").animate({left: '250px'});
  });
});
</script> 
</head>

<body>
<button>My Animation</button>


<form id="nav-search-bar-form" accept-charset="utf-8" action="/s/ref=nb_sb_noss" class="nav-searchbar nav-progressive-attribute" method="GET" name="site-search" role="search">




  
</a>
</body>
</html>
