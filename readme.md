goodgood
[test](turntum.github.io/content.html)

<!DOCTYPE html>
<html>
<head>
  <meta charset=utf-8 />
  <title> {% if page.title %} {{ page.title }} | {% endif %} John Doe, Photographer </title>
  <link rel="stylesheet" href="/css/styles.css" />
</head>
<body>
 
  <div id="main">
 
    <header>
      <h1> John Doe Photograghy </h1>
    <header>
 
    <nav role="navigation">
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/portfolio/">Portfolio</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
    </nav>
 
    {{ content }}
 
    <footer>
      <p>@copy; John Doe Photography 2011 | All Rights Reserved. </p>
    </footer>
 
  </div>
</body>
</html>


