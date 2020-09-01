# FaithWilliams.github.io
Demo website
!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
/* this HTML Doc was grabbed from https://www.w3schools.com/howto/howto_css_example_website.asp for demo purposes only.*/
/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #E0FFFF;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Sticky navbar - toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed). The sticky value is not supported in IE or Edge 15 and earlier versions. However, for these versions the navbar will inherit default position */
.navbar {
  overflow: hidden;
  background-color: #333;
  position: sticky;
  position: -webkit-sticky;
  top: 0;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}


/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Active/current link */
.navbar a.active {
  background-color: #666;
  color: white;
}

/* Column container */
.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>Koi Fish</h1>
  <p>A <b>responsive</b> website created by me.</p>
</div>

<div class="navbar">
  <a href="#" class="active">Home</a>
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#" class="right">Link</a>
</div>

<div class="row">
  <div class="side">
    <h2>About Me</h2>
    <h5>Photo of me:</h5>
    <div class="koi fish" style="height:200px;">Image</div>
    <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    <h3>More Text</h3>
    <p>Lorem ipsum dolor sit ame.</p>
    <div class="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRftv82d_ityh2ZnPnOmT88PISWAeLoMyhygg&usqp=CAU" style="height:60px;">Image</div><br>
    <div class="https://www.google.com/imgres?imgurl=https%3A%2F%2Fcdn0.wideopenpets.com%2Fwp-content%2Fuploads%2F2016%2F03%2FAdobeStock_104233406-770x405.jpg&imgrefurl=https%3A%2F%2Fwww.wideopenpets.com%2Feverything-need-know-koi%2F&tbnid=MWeDXxmDomEI2M&vet=12ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygfegUIARDIAg..i&docid=ijCK3hYLdRli_M&w=770&h=405&q=koi%20fish&ved=2ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygfegUIARDIAg" style="height:60px;">Image</div><br>
    <div class="https://www.google.com/imgres?imgurl=https%3A%2F%2Fimages.unsplash.com%2Fphoto-1517361265-3bd77c6f1689%3Fixlib%3Drb-1.2.1%26ixid%3DeyJhcHBfaWQiOjEyMDd9%26auto%3Dformat%26fit%3Dcrop%26w%3D1000%26q%3D80&imgrefurl=https%3A%2F%2Funsplash.com%2Fphotos%2F7rR_WSk4HM0&tbnid=V9T2101ph_JqmM&vet=12ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygdegUIARDEAg..i&docid=PsnpuroTJ6RLxM&w=1000&h=667&q=koi%20fish&ved=2ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygdegUIARDEAg" style="height:60px;">Image</div>
  </div>
  <div class="main">
    <h2>TITLE HEADING</h2>
    <h5>Title description, Dec 7, 2017</h5>
    <div class="https://www.google.com/imgres?imgurl=https%3A%2F%2Fmymodernmet.com%2Fwp%2Fwp-content%2Fuploads%2F2020%2F05%2Fhow-to-draw-koi-fish-thumbnail.jpg&imgrefurl=https%3A%2F%2Fmymodernmet.com%2Fhow-to-draw-koi-fish%2F&tbnid=Maiile6wnbThOM&vet=12ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygSegUIARCjAg..i&docid=BMg7nuUX8n0pPM&w=1200&h=630&q=koi%20fish&ved=2ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygSegUIARCjAg" style="height:200px;">Image</div>
    <p>Some text..</p>
    <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    <br>
    <h2>TITLE HEADING</h2>
    <h5>Title description, Sep 2, 2017</h5>
    <div class="https://www.google.com/imgres?imgurl=https%3A%2F%2Feverythingkoi.com%2Fstatic%2Fversion1598515498%2Ffrontend%2FSmartsites%2Fpondcenter%2Fen_US%2Fimages%2Fkoi-fish-for-sale.jpg&imgrefurl=https%3A%2F%2Feverythingkoi.com%2F&tbnid=_wRsU3atIMDEOM&vet=12ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygcegUIARDCAg..i&docid=ihg91ACyOiOMXM&w=1825&h=878&q=koi%20fish&ved=2ahUKEwiXtYXWmr_rAhW0AzQIHeZOBfkQMygcegUIARDCAg" style="height:200px;">Image</div>
    <p>Some text..</p>
    <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
  </div>
</div>

<div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>
