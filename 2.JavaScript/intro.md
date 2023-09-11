# What can JavaScript Do?

**JavaScript can change HTML content**
<br>
Example: 
```html
<html>
<body>
<p> Changing the inner content </p>
<p id="id1"> Welcome! </p>
<input type="button" onclick='document.getElementById("id1").innerHTML = "Hello JavaScript!"' value='click me'>
</body>
</html>
```
__Output:__
<html>
<body>
<p> Changing the inner content </p>
<p id="id1"> Welcome! </p>
<input type="button" onclick='document.getElementById("id1").innerHTML = "Hello JavaScript!"' value='click me'> 
</body>
</html>

---

**JavaScript can change HTML attribute values**
<br>
Example:
```html
<html>
<body> 
<p> Changing attribute values <p>
<p> In this example we are going to see how JS changes the `src` attribute of image tag </p>
<input type="button" onclick='document.getElementById("imgex").src="https://www.w3schools.com/js/pic_bulbon.gif"' value="Turn on the light">
<img src="https://www.w3schools.com/js/pic_bulboff.gif" id="imgex" style="width:100px">
<input type="button" onclick='document.getElementById("imgex").src="https://www.w3schools.com/js/pic_bulboff.gif"' value="Turn off the light">
</body>
</html>
```
__Output:__
<html>
<body> 
<p> Changing attribute values <p>
<p> In this example we are going to see how JS changes the `src` attribute of image tag </p>
<input type="button" onclick='document.getElementById("imgex").src="https://www.w3schools.com/js/pic_bulbon.gif"' value="Turn on the light">
<img src="https://www.w3schools.com/js/pic_bulboff.gif" id="imgex" style="width:100px">
<input type="button" onclick='document.getElementById("imgex").src="https://www.w3schools.com/js/pic_bulboff.gif"' value="Turn off the light">
</body>
</html>

---

**JavaScript Can Change HTML Styles (CSS)**
<br>
Example:
```html
<html>
<body>
<p> Changing HTML styles </p>
<p id="demo">Welcome to JavaScript! </p>
<input type="button" onclick="document.getElementById('demo').style.fontSize = '25px'" value="click me">
</body>
</html>
```
__Output:__
<html>
<body>
<p> Changing HTML styles </p>
<p id="demo">Welcome to JavaScript! </p>
<input type="button" onclick="document.getElementById('demo').style.fontSize = '25px'" value="click me">
</body>
</html>

---

**JavaScript Can Hide HTML Elements**
<br>
Example:
```html
<html>
<body>
<p> JS can hide HTML Elements </p>
<p id="demo"> click button below to hide me </p>
<input type="button" onclick="document.getElementById('demo').style.display='none'" value="cilck me">
</body>
</html>
```
__Output:__
<html>
<body>
<p> JS can hide HTML Elements </p>
<p id='demo1'> click button below to hide me </p>
<input type="button" onclick="document.getElementById('demo1').style.display='none'" value="cilck me">
</body>
</html>

---
**JavaScript Can Show Hidden HTML Elements**
<br>
Example:
```html
<html>
<body>
<p>JavaScript can show hidden HTML elements.</p>
<p id="demo2" style="display:none">Hello JavaScript!</p>
<input type="button" onclick="document.getElementById('demo2').style.display='block'" value="click me">
</body>
</html> 
```
__Output:__
<html>
<body>
<p>JavaScript can show hidden HTML elements</p>
<p id="demo2" style="display:none">Hello JavaScript!</p>
<input type="button" onclick="document.getElementById('demo2').style.display='block'" value="click me">
</body>
</html>

For more reference [click here](https://www.w3schools.com/js/js_intro.asp "w3 schools js intro")