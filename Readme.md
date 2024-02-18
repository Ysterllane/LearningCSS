<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<h2>Sumary:</h2>

<p>• How does CSS work?<br>
   • With CSS we can :<br>
   • Let´s get started: <b>*</b><br>
   • What is a class?<br>
   • How to use a class?<br>
   • Tag:<br>
   • Box Model:<br>
   • Body:<br>
   • Flexbox:<br></p>

<div><h1>How does CSS work?</h1></div>

<p>CSS means: Cascading Style Sheets (Folhas de estilo em cascata), simple mechanism for adding style (fonts, colors, spacing) to Web documents.</p>

<p>CSS only works when linked to HTML (Hypertext Markup Language).</p>

<p>For this, It`s necessary use the tag: </p>

<code class="pinkText">< link rel="stylesheet" href="style.css" ></code>

<h2>With CSS we can :</h2>

<p>• Change background color <br>
   • Change text color <br>
   • Control margin, padding <br>
   • Control height, width <br>
   • Format bottons, imgs <br>
   • Between others</p>

<h3><b>Let´s get started:</b></h3><hr>

<p>First, the command <b>*</b> controls all the page elements. There, we usualy control the margin and the padding (space after the text). Ex: </p>

<code class="yellowText">* { <br>
    margin: 0; <br>
    padding: 0; <br>
}</code>

<h3>When we want to style the html, we usualy uses:</h3>

<p> • An tag name <br>
    • An class</p>

<h2>What is a class?</h2>

<p>A class is used to style a specific tag part. For exemplo, in a HTML code, we have many p tags. So, we can use a class to change a specific paragraph:</p>

<code>< code class="blueText" ><code class="blueText">Will be changed just this part</code></ code ></code>

<h2>How to use a class?</h2>

<p>Start with a point ( . )

<code> .className{ }</code>

<h2>Tag:</h2>

<p>There are many tags to be used in CSS. The principal tag is <b>body</b> that is responsable to all the visual content.<p>

<h2>Box Model:</h2>

<p>It´s the model of margin, border, padding and text that we can see in the broser with the F12 commad</p>

<img src="Box Model.PNG" alt="Box Model">


<h2>Body:</h2>

<h3>height and width:</h3> 

<p>porção de área visível da tela: <code>height = 100vh;</code></p> 

<p>100% da tela: <code>width = 100%;</code></p> 

<p>Body code:</p>

<code>body { <br>
  height: 100vh; <br>
  width = 100%; <br>
}</code>


<h2>Flexbox:</h2>

<p>Flexbox is a one-dimensional layout method for arranging items in rows or columns.<p>

<p>By defining the value of an element's <b>display</b> property as <b>flex</b>, we create a flex container, that is, we start using Flexbox. From that point on, all elements that are inside the container are called child elements and will present standardized behaviors (comportamentos padronizados). Code: <code>display: flex;</code></p>

<h3><b>justify-content Visualization :</b></h3>

<img src="justify-content.svg" alt="visualization of the justify content">

<p>Code exemple:</p>

<code>.container { <br>
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe; <br>
}</code>

<h3><b>Align-items Visualization :</b></h3>

<img src="align-items.svg" alt="visualization of the align items">

<p>Code exemple:</p>

<code>.container { <br>
  align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end + ... safe | unsafe; <br>
}</code>

</body>
</html>