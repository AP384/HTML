<!DOCTYPE html>
<html>
<body>

<h1 style="background-color: red;">Hello World!</h1>
<p>This is a paragraph.</p>

</body>
</html>

<!DOCTYPE html>
<html>
<body>
<!----------------------------------Hello World--------------------------------->


<h1 style="background-color: red;">Hello World!</h1>
<p>This is a paragraph.</p>


<div>-----------------------------------------------------------------------------</div>
<!-- this is a comment -->

<!--
    Or you can comment out a
    large number of lines.
-->


<!----------------------------------IMAGE--------------------------------->
<img loading="lazy" src="https://xxx.png" alt="Describe image here" width="400" height="400">

<div>-----------------------------------------------------------------------------</div>

<!----------------------------------LINKS + COLOUR--------------------------------->
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attributes"><a> The Attributes</a>
<ul>
<li><a href="mailto:me@example.com">Email</a></li>
<li><a href="tel:+123456789">Call</a></li>
<li><a href="sms:+123456789&body=ha%20ha">Msg</a></li>
</ul>

<br></br>
<style type="text/css">
    body { color: brown; }
</style>

<div>-----------------------------------------------------------------------------</div>

<!----------------------------------HEADER / FOOTER--------------------------------->
<body>
  <header>
    <nav>...</nav>
  </header>
  <main>
    <h1>HTML5</h1>
  </main>
  <footer>
    <p>©2023 HTML5</p>
  </footer>
</body>

<!----------------------------------HORIZONTAL LINE--------------------------------->


<!----------------------------------LINKS--------------------------------->
<header>
  <nav>
    <ul>
      <li><a href="#">Edit Page</a></li>
      <li><a href="#">Twitter</a></li>
      <li><a href="#">Facebook</a></li>
    </ul>
  </nav>
</header>
<!----------------------------------PROGRESS BAR--------------------------------->
<progress value="80" max="100"></progress>

<!----------------------------------TABLE--------------------------------->
<table>
    <thead>
        <tr>
            <td><B>Name</B></td>
            <td><b>Age</b></td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Mark</td>
            <td>101</td>
        </tr>
        <tr>
            <td>Edis</td>
            <td>38</td>
        </tr>
        <tr>
            <td>Andy</td>
            <td>99</td>
        </tr>
         <tr>
            <td>Roni</td>
            <td>10090</td>
        </tr>
    </tbody>
</table>

<!----------------------------------ORDERED LIST--------------------------------->
<ol>
    <li>I'm the first item</li>
    <li>I'm the second item</li>
    <li>I'm the third item</li>
</ol>

<!--------------------------------UNORDERED LIST----------------------------------->

<!DOCTYPE html>
<html>
<body>

<h1 style="background-color: red;">Approval Checklist</h1>
<p>This is a paragraph.</p>

</body>
</html>

<!DOCTYPE html>
<html>
<body>










<!----------------------------------DEFINTION LIST--------------------------------->
<!--The <dl> HTML element represents a description list. The element encloses a list of groups of terms (specified using the <dt> element) and descriptions (provided by <dd> elements). Common uses for this element are to implement a glossary or to display metadata (a list of key-value pairs)--->

<dl>
    <dt><i><b>A Term</b></i></dt>
    <dd>Definition of a term</dd>
    <dt><i><b>Another Term</b></i></dt>
    <dd>Definition of another term</dd>
</dl>


<br></br>

<!----------------------------------FORM WITH FREE TEXT BOXES--------------------------------->


<form method="POST" action="api/login">
  <label for="mail">Email: </label>
  <input type="email" id="mail" name="mail">
  <br/>

  <label for="pw">Password: </label>
  <input type="password" id="pw" name="pw">
  <br/>

  <input type="submit" value="Login">
  <br/>
</form>
<br></br>
<!----------------------------------FORM WITH RADIO BUTTONS--------------------------------->

<!DOCTYPE html>
<html>
<body>

<h1>The label element</h1>

<p>Click on one of the text labels to toggle the related radio button:</p>

<form action="/action_page.php">
<input type="radio" id="html" name="fav_language" value="HTML">
<label for="html">HTML</label><br>
<input type="radio" id="css" name="fav_language" value="CSS">
<label for="css">CSS</label><br>
<input type="radio" id="javascript" name="fav_language" value="JavaScript">
<label for="javascript">JavaScript</label><br><br>
<input type="submit" value="Submit">
</form>

</body>
</html>

<br></br>
<br></br>

<input type="radio" name="gender" id="m">
<label for="m">Male</label>
<input type="radio" name="gender" id="f">
<label for="f">Female</label>

<br></br>
<br></br>

<!----------------------------------CHECKBOXES--------------------------------->
<input type="checkbox" name="s" id="soc">
<label for="FOO">FOOTBALL</label>
<input type="checkbox" name="s" id="bas">
<label for="rUG">RUGBY</label>

<BR></BR>

<!----------------------------------DROPDOWNS--------------------------------->
<label for="city">City:</label>
<select name="city" id="city">
    <option value="1">Sydney</option>
    <option value="2">Melbourne</option>
    <option value="3">Cromwell</option>
</select>

<BR></BR>

<!----------------------------------FIELDSET TAGS--------------------------------->
<fieldset>
    <legend>Your favourite monster:</legend>
    <input type="radio" id="kra" name="m">
    <label for="kraken">Kraken</label><br/>
    <input type="radio" id="sas" name="m">
    <label for="sas">Sasquatch</label>
</fieldset>


<BR></BR>
<!----------------------------------DATALIST TAGS--------------------------------->
<label for="b">Choose a browser: </label>
<input list="list" id="b" name="browser"/>
<datalist id="list">
  <option value="Chrome">
  <option value="Firefox">
  <option value="Internet Explorer">
  <option value="Opera">
  <option value="Safari">
  <option value="Microsoft Edge">
</datalist>


<BR></BR>
<!----------------------------------SUBMIT AND RESET BUTTONS--------------------------------->
<form action="register.php" method="post">
  <label for="foo">Name:</label>
  <input type="text" name="name" id="foo">
  <input type="submit" value="Submit">
  <input type="reset" value="Reset">
</form>





<BR></BR>
<!----------------------------------NESTED LABEL----------------------------------------------->
<label>Click me 
    <input type="text" id="user" name="name"/>
</label>
<BR></BR>
<!----------------------------------NESTED LABEL (2)----------------------------------------------->

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="Andy"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Potthurst">
</form> 
<BR></BR>
<!----------------------------------INPUT TAGS----------------------------------------------->
<label for="Name">Name:</label>
<input type="text" name="Name" id="">
<BR></BR>

<!----------------------------------TEXTAREA----------------------------------------------->
<textarea rows="2" cols="30" name="address" id="address"></textarea>

<!----------------------------------ID ATTRIBUTE TO STYLE TEXT WITH CSS----------------------------------------------->
<html>
<head>
<style>
#myHeader {
  color: GREEN;
  text-align: RIGHT;
}
</style>
</head>
<body>

<h1 id="myHeader">W3Schools is the best!</h1>

</body>
</html>
<BR></bR>
<!----------------------------------CSS - INLINE--------------------------------->

<h1 style="color:blue;">A Blue Heading</h1>

<p style="color:red;">A red paragraph.</p>
<BR></bR>
<!----------------------------------CSS - INTERNAL--------------------------------->

<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: LIGHTBLUE;}
h1   {color: YELLOW;}
p    {color: GOLD;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
<BR></bR>
<!----------------------------------CSS - EXTERNAL---------------------------------
The external style sheet can be written in any text editor. The file must not contain any HTML code, and must be saved with a .css extension.
https://www.w3schools.com/html/html_css.asp
Here is what the "styles.css" file looks like:

body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
------>

<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
<BR></bR>

<!----------------------------------META TAGS--------------------------------->

<meta charset="utf-8">
<BR></bR>

<!-- title -->
<title>···</title>
<meta property="og:title"  content="···">
<meta name="twitter:title" content="···">
<BR></bR>

<!-- url -->
<link rel="canonical"       href="https://···">
<meta property="og:url"  content="https://···">
<meta name="twitter:url" content="https://···">
<BR></bR>


<!-- description -->
<meta name="description"         content="···">
<meta property="og:description"  content="···">
<meta name="twitter:description" content="···">
<BR></bR>

<!-- image -->
<meta property="og:image"  content="https://···">
<meta name="twitter:image" content="https://···">
<BR></bR>
<!----------------------------------EXAMPLE-------------------------------->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>

<body>
    <h1>Heading</h1>
    <hr>
    <h2>Heading</h2>
    <hr>
    <h3>Heading</h3>
    <hr>
    <h4>Heading</h4>
    <hr>
    <h5>Heading</h5>
    <hr>
    <h6>Heading</h6>
    <hr>
    <p>Paragraph</p>
    <hr>
    <a href="https://www.w3schools.com/tags/default.asp">Link</a>
    <hr>
    <img src="https://img.etimg.com/thumb/msid-86166020,width-300,height-225,imgsize-172700,,resizemode-75/london-uk-.jpg"
        alt="wikipedia nature" width="300" height="225">
    <hr>
    <b> Bold text </b>
    <hr>
    <strong> Important text </strong>
    <hr>
    <i> Italic text </i>
    <hr>
    <em> Emphasized text </em>
    <hr>
    <mark> Marked text </mark>
    <hr>
    <small> Smaller text </small>
    <hr>
    <del> Deleted text </del>
    <hr>
    <ins> Inserted text </ins>
    <hr>
    <sub> Subscript text </sub>
    <hr>
    <sup> Superscript text </sup>
    <hr>

    <abbr> Defines an abbreviation or acronym </abbr>
    <hr>
    <address> Defines contact information for the author/owner of a document </address>
    <hr>
    <bdo> Defines the text direction </bdo>
    <hr>
    <blockquote> Defines a section that is quoted from another source </blockquote>
    <hr>
    <cite> Defines the title of a work </cite>
    <hr>
    <q> Defines a short inline quotation </q>
    <hr>
    
</body>

</html>

<!----------------------------------END--------------------------------->

</body>
</html>
