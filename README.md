# google-homepage

<!DOCTYPE html>
<html>
<head>
<style>

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}


ul {
float:right;
  position:relative;
  right:25px;
}


li {
  list-style-type:none;
  display:inline;
  padding: 0 5px;
  font-size:20px;
}

#button {
 background:blue;
  color:white;
  border-radius:5px;
}

header {

  position:fixed;
  top:0px;
  width:100%;
  float:right;
}

.logo {
  position:relative;
  top:200px;
  margin:0 auto;
  display:block;

}

body {
  position:relative;
  padding:0;
  margin:0;
  text-align:center;

  width:100%;

}

#ch {
  position:relative;
  top:3px;
}

.container {
  clear:both;

}

.text {
  width:472px;
  height:38px;
  margin:0 auto;
  display:block;
  position:relative;
  top:300px;
}

input {
  display:inline-block;
    margin:0 auto;
  position:relative;
  top:325px;
}

.bottom {
  background:silver;
  position:fixed;
  height:25px;
  bottom:0px;
  width:100%;
  left:0px;
  text-align:left;
}

.right {
  position:relative;
  left:73%;
}</style>
</head>
<body>
  <header>
    <ul>
      <li>Gmail</li>
      <li>Images</li>
      <li><img id="ch" src="http://s32.postimg.org/iqqfooc4h/bars.png" /></li>
      <li id="button">Sign In</li>
    </ul>
  </header>
  
  
  <div class="container">
  <img class="logo" src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" />
    <form>
      <input class="text" type="text" name="search"></input>
    </form>
  <input type="submit" value="Google Search"></input>
  <input type="submit" value="I'm Feeling Lucky"></input>

  </div>


      <ul class="bottom">
      <li>Advertising</li>
      <li>Business</li>
      <li>About</li>
      <li class="right">Privacy</li>
      <li class="right">Terms</li>
      <li class="right">Settings</li>
    </ul>
  
</body>
</html>
