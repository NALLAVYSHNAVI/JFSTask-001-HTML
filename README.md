# JFSTask-001-HTML
1.Fix the bugs in below snippet
    <html lang="en">
    <head>
        <title>Document
            <body>
                guvi
        </title>
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
Here are the changes I made:
Moved the closing </title> tag to the correct position.
Added the <!DOCTYPE html> declaration at the beginning of the document.
Added a closing </body> tag after the content.
Ensured that all opening tags have corresponding closing tags.
These changes should fix the bugs in the HTML snippet and make it valid.
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
2.Try the below one
  
<html lang="en">
    <head>
        <title>Document
            <body>
                guvi
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
    
Here are the changes I made:
The <head> section contains a <title> tag, which is properly closed.
The <body> section starts after the <head> section and contains the text "guvi".
The nested <div> tags are properly structured and closed.
These changes should fix the bugs in the HTML snippet and make it valid.
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    guvi
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </div>
    </div>
</body>
</html>
3.Design a contact us form with all fields as required.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
</head>
<body>
    <h2>Contact Us Form</h2>
    <form action="#" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        
        <label for="email">Email Address:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        
        <label for="subject">Subject:</label><br>
        <input type="text" id="subject" name="subject" required><br><br>
        
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
4.Use certain HTML elements to display the following in a HTML page.
Programming Language
JavaScript
Angular
React
Vue.js
Python
Django Framework
Flask Framework
Java
Spring
Maven
Hibernate
Database
MySQL
MongoDB
Cansandra
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programming Languages and Technologies</title>
</head>
<body>
    <h1>Programming Languages</h1>
    <h2>JavaScript</h2>
    <ul>
        <li>Angular</li>
        <li>React</li>
        <li>Vue.js</li>
    </ul>

    <h2>Python</h2>
    <ul>
        <li>Django Framework</li>
        <li>Flask Framework</li>
    </ul>

    <h2>Java</h2>
    <ul>
        <li>Spring</li>
        <li>Maven</li>
        <li>Hibernate</li>
    </ul>

    <h1>Databases</h1>
    <ul>
        <li>MySQL</li>
        <li>MongoDB</li>
        <li>Cassandra</li>
    </ul>
</body>
</html>
5.Create an element that helps you to open the https://google.com in separate new tab.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open Google in New Tab</title>
</head>
<body>
    <a href="https://google.com" target="_blank">Open Google</a>
</body>
</html>
6.In the form, add two radio buttons with grouping them for employee type(Salaried and own business)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Type Form</title>
</head>
<body>
    <form>
        <label for="salaried">Salaried</label>
        <input type="radio" id="salaried" name="employee_type" value="salaried">
        
        <label for="own_business">Own Business</label>
        <input type="radio" id="own_business" name="employee_type" value="own_business">
        
        <button type="submit">Submit</button>
    </form>
</body>
</html>
7.Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <form>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="subject">Subject:</label>
                <input type="text" id="subject" name="subject" required>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
            </div>
            <div class="form-group">
                <label for="captcha">Captcha:</label>
                <!-- Add your captcha here -->
                <input type="text" id="captcha" name="captcha" required>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
CSS
.container {
    width: 400px;
    margin: 0 auto;
}

.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    font-weight: bold;
}

input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
}

textarea {
    resize: vertical;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}
9.Write HTML input tags snippet to show default values for all Form elements.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Default Form Values</title>
</head>
<body>
    <form>
        <!-- Default value for text input -->
        <input type="text" name="name" value="John Doe"><br>

        <!-- Default value for email input -->
        <input type="email" name="email" value="john@example.com"><br>

        <!-- Default value for password input -->
        <input type="password" name="password" value="password123"><br>

        <!-- Default value for textarea -->
        <textarea name="message">Default message here</textarea><br>

        <!-- Default value for checkbox -->
        <input type="checkbox" name="subscribe" checked> Subscribe to newsletter<br>

        <!-- Default value for radio buttons -->
        <input type="radio" name="gender" value="male" checked> Male
        <input type="radio" name="gender" value="female"> Female<br>

        <!-- Default value for select dropdown -->
        <select name="country">
            <option value="usa">USA</option>
            <option value="uk" selected>UK</option>
            <option value="canada">Canada</option>
        </select><br>

        <!-- Default value for date input -->
        <input type="date" name="birthdate" value="2022-01-01"><br>

        <!-- Default value for number input -->
        <input type="number" name="quantity" value="10"><br>

        <!-- Default value for range input -->
        <input type="range" name="volume" min="0" max="100" value="50"><br>

        <!-- Default value for color input -->
        <input type="color" name="color" value="#ff0000"><br>

        <!-- Default value for hidden input -->
        <input type="hidden" name="secret" value="hiddenvalue"><br>

        <!-- Default value for submit button -->
        <input type="submit" value="Submit">
    </form>
</body>
</html>
10.In your, HTML page add the below line and Highlight it without using any CSS.
"HTML & CSS is awesome"

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Highlighted Text</title>
</head>
<body>
    <p>HTML & CSS is <mark>awesome</mark></p>
</body>
</html>
11.Create an HTML page, which should contain all types of input elements.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Elements</title>
</head>
<body>
    <h2>Input Elements</h2>

    <!-- Text Input -->
    <label for="text-input">Text Input:</label>
    <input type="text" id="text-input" name="text-input"><br><br>

    <!-- Password Input -->
    <label for="password-input">Password Input:</label>
    <input type="password" id="password-input" name="password-input"><br><br>

    <!-- Email Input -->
    <label for="email-input">Email Input:</label>
    <input type="email" id="email-input" name="email-input"><br><br>

    <!-- Number Input -->
    <label for="number-input">Number Input:</label>
    <input type="number" id="number-input" name="number-input"><br><br>

    <!-- Date Input -->
    <label for="date-input">Date Input:</label>
    <input type="date" id="date-input" name="date-input"><br><br>

    <!-- Checkbox -->
    <label for="checkbox">Checkbox:</label>
    <input type="checkbox" id="checkbox" name="checkbox" value="checkbox"><br><br>

    <!-- Radio Buttons -->
    <label for="radio">Radio Buttons:</label><br>
    <input type="radio" id="radio1" name="radio" value="radio1">
    <label for="radio1">Option 1</label><br>
    <input type="radio" id="radio2" name="radio" value="radio2">
    <label for="radio2">Option 2</label><br><br>

    <!-- Textarea -->
    <label for="textarea">Textarea:</label><br>
    <textarea id="textarea" name="textarea" rows="4" cols="50"></textarea><br><br>

    <!-- Select Dropdown -->
    <label for="select">Select Dropdown:</label><br>
    <select id="select" name="select">
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
        <option value="option3">Option 3</option>
    </select><br><br>

    <!-- Submit Button -->
    <input type="submit" value="Submit">

</body>
</html>

