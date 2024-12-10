# [Guvi Zen](https://www.guvi.io/zen/)

## HTML Task to know usage of basic tags.

1. Fix the bugs in below snippet

    <html lang="en">
    <head>
        <title>Document guvi</title>
    </head>
<body>
    <div>Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
    <div>Guvi Geek Network</div>
</body>
    </html>
```
2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document guvi</title>
    </head>
<body>
    <div>Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
     <div>Guvi Geek Network</div>
  </body>
    </html>
```

---

3. Design a contact us form with all fields as required.

   <!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>Contact Us</h1>
  <form action="submit_form.php" method="post">
    <label for="name">Full Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email Address:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="phone">Phone Number:</label><br>
    <input type="tel" id="phone" name="phone" required><br><br>

    <label for="subject">Subject:</label><br>
    <input type="text" id="subject" name="subject" required><br><br>

    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="5" required></textarea><br><br>

    <button type="submit">Submit</button>
  </form>

</body>
</html>



---

4. Use certain HTML elements to display the following in a HTML page.

- Programming Language
  - JavaScript
    1. Angular
    2. React
    3. Vue.js
  - Python
    1. Django Framework
    2. Flask Framework
  - Java
    1. Spring
    2. Maven
    3. Hibernate
- Database
  - MySQL
  - MongoDB
  - Cansandra
 
  - <!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>- Programming Language</h1>
<h2>- JavaScript</h2>
<ol>
<li>Angular</li>
<li>React</li>
<li>Vue.js</li>
</ol>
<h2>- Python</h2>
<ol>
<li>Django Framework</li>
<li>Flask Framework</li>
</ol>
<h2>- Java</h2>
<ol>
<li>Spring</li>
<li>Maven</li>
<li>Hibernate</li>
</ol>
<h2>-Database</h2>
<ol>
<li>MySQL</li>
<li>MongoDB</li>
<li>Cansandra</li>
</ol>

</body>
</html>

---

5. Create an element that helps you to open the https://google.com in separate new tab.

<html>
    <head>
        <title>Anchor tag</title>
    </head>
    <body>
        <div>Click <a href="https://google.com">here</a></div>
    </body>
</html>

---

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)

   <!DOCTYPE html>
<html>
<body>

<h1>Employee Type</h1>

<form action="/action_page.php">
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">Salaried</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">Own Business</label><br><br>
<input type="submit" value="Submit">

</form>

</body>
</html>


---

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)

**The above image is not displaying**
---

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).

**I hope you're expecting this, because the above doesn't exists.**

<!DOCTYPE html>
<html>
<body>


<table width="100%" height="auto" style="background-color:black;">
<tr>
<td width="120" style="color:#ffffff; font-weight:bold; text-align:center; padding:0px;">Hello</td>
<td width="120" style="color:#ffffff; font-weight:bold; text-align:center; padding:0px;">About us</td>
<td width="120" style="color:#ffffff; font-weight:bold; text-align:center; padding:0px;">Our Gallery</td>
<td width="120" style="color:#ffffff; font-weight:bold; text-align:center; padding:0px;">Our Courses</td>
<td width="120" style="color:#ffffff; font-weight:bold; text-align:center; padding:0px;">Contact us</td>
</tr>
</table>

</body>
</html>


---

9. Write HTML input tags snippet to show default values for all Form elements.

    <!DOCTYPE html>
<html>
<body>


<form>
 ** <!-- Text Input -->**
  <label for="text">Text:</label>
  <input type="text" id="text" name="text" value="Default Text"><br><br>

  **<!-- Password Input -->**
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" value="123456"><br><br>

  **<!-- Email Input -->**
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" value="example@example.com"><br><br>

  **<!-- Number Input -->**
  <label for="number">Number:</label>
  <input type="number" id="number" name="number" value="42"><br><br>

  **<!-- Date Input -->**
  <label for="date">Date:</label>
  <input type="date" id="date" name="date" value="2024-12-10"><br><br>

  **<!-- Time Input -->**
  <label for="time">Time:</label>
  <input type="time" id="time" name="time" value="14:30"><br><br>

  **<!-- Range Input -->**
  <label for="range">Range:</label>
  <input type="range" id="range" name="range" value="50"><br><br>

  **<!-- Checkbox -->**
  <label for="checkbox">Checkbox:</label>
  <input type="checkbox" id="checkbox" name="checkbox" checked><br><br>

  **<!-- Radio Buttons -->**
  <label>Radio:</label>
  <input type="radio" id="radio1" name="radio" value="Option1" checked>
  <label for="radio1">Option 1</label>
  <input type="radio" id="radio2" name="radio" value="Option2">
  <label for="radio2">Option 2</label><br><br>

  **<!-- Dropdown -->**
  <label for="dropdown">Dropdown:</label>
  <select id="dropdown" name="dropdown">
    <option value="Option1" selected>Option 1</option>
    <option value="Option2">Option 2</option>
    <option value="Option3">Option 3</option>
  </select><br><br>

**  <!-- Textarea -->**
  <label for="textarea">Textarea:</label>
  <textarea id="textarea" name="textarea" rows="4" cols="50">Default Text</textarea><br><br>

  **<!-- Submit Button -->**
  <input type="submit" value="Submit">
</form>


</body>
</html>


---

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"

<!DOCTYPE html>
<html>
    <head>
        <title>HTML & CSS</title>
    </head>
    <body>
        <div><b>HTML & CSS is awesome!!</b></div>
    </body>
</html>

---

11. Create an HTML page, which should contain all types of input elements.

<!DOCTYPE html>
<html>
<body>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>All Input Elements</title>
</head>
<body>
  <h1>All Input Elements</h1>
  <form action="submit_form.php" method="post">
    **<!-- Text Input -->**
    <label for="text">Text:</label>
    <input type="text" id="text" name="text"><br><br>

    **<!-- Password Input -->**
    <label for="password">Password:</label>
    <input type="password" id="password" name="password"><br><br>

    **<!-- Email Input -->**
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>

    **<!-- Number Input -->**
    <label for="number">Number:</label>
    <input type="number" id="number" name="number"><br><br>

    **<!-- Phone Input -->**
    <label for="tel">Phone Number:</label>
    <input type="tel" id="tel" name="tel"><br><br>

    **<!-- URL Input -->**
    <label for="url">URL:</label>
    <input type="url" id="url" name="url"><br><br>

    **<!-- Date Input -->**
    <label for="date">Date:</label>
    <input type="date" id="date" name="date"><br><br>

    **<!-- Time Input -->**
    <label for="time">Time:</label>
    <input type="time" id="time" name="time"><br><br>

   ** <!-- Month Input -->**
    <label for="month">Month:</label>
    <input type="month" id="month" name="month"><br><br>

   ** <!-- Week Input -->**
    <label for="week">Week:</label>
    <input type="week" id="week" name="week"><br><br>

    **<!-- Color Input -->**
    <label for="color">Color:</label>
    <input type="color" id="color" name="color"><br><br>

    **<!-- File Upload -->**
    <label for="file">File Upload:</label>
    <input type="file" id="file" name="file"><br><br>

    **<!-- Checkbox -->**
    <label>Checkbox:</label>
    <input type="checkbox" id="checkbox1" name="checkbox1">
    <label for="checkbox1">Option 1</label>
    <input type="checkbox" id="checkbox2" name="checkbox2">
    <label for="checkbox2">Option 2</label><br><br>

    **<!-- Radio Buttons -->**
    <label>Radio Buttons:</label>
    <input type="radio" id="radio1" name="radio" value="Option1">
    <label for="radio1">Option 1</label>
    <input type="radio" id="radio2" name="radio" value="Option2">
    <label for="radio2">Option 2</label><br><br>

    **<!-- Range Slider -->**
    <label for="range">Range:</label>
    <input type="range" id="range" name="range"><br><br>

    **<!-- Textarea -->**
    <label for="textarea">Textarea:</label>
    <textarea id="textarea" name="textarea" rows="4" cols="50"></textarea><br><br>

    **<!-- Dropdown -->**
    <label for="dropdown">Dropdown:</label>
    <select id="dropdown" name="dropdown">
      <option value="Option1">Option 1</option>
      <option value="Option2">Option 2</option>
      <option value="Option3">Option 3</option>
    </select><br><br>

    **<!-- Buttons -->**
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
  </form>
</body>
</html>


</body>
</html>

