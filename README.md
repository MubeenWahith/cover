# Ex.05 Book Cover Page Design
## Date:15-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```

book.html


<html>
    <head>
        <title>Cover Page</title>
        <link rel="stylesheet" href="styles.css">
    </head>
<body>
<div class="container">
    <h2>About the Book</h2>
    <hr>
    <p>
        This book <b><mark>"Creative Web Design"</mark></b>is a guide to building effective and attractive websites. 
        It shows how to combine good looks with easy use for any visitor.
        The book teaches the key rules of layout, color, and type so that anyone can make a professional site. 
        It is a clear and useful resource for starting a project.
    </p>
    <p>
       The book also covers how to plan a site’s structure and make it simple to navigate. 
       Readers will learn how to create designs that work well on phones, tablets, and computers. 
       This book gives the practical skills needed to design modern websites that people enjoy using.
    </p>
    <div class="quote">
        "Design is not just what it looks like and feels like. Design is how it works."
    </div>
    <div class="author-box">
        <img src="mubeen.jpeg" alt="Author Image">
        <div>
            <h3>MOHAMED MUBEEN.A</h3>
            <p>
                Mohamed Mubeen is the author of Creative Web Design, which champions
                 functional beauty in digital spaces. He writes to bridge the gap between 
                 clean code and intuitive user experience. His work serves as a practical blueprint
                  for creators who believe design is how a website works, not just how it looks.
            </p>
        </div>
    </div>
    <div class="footer">
        <span><b>SEC Publishers</b><br>Printed in India</span>
        <span class="price">Price: Rs.1099</span>
    </div>
</div>
</body>
</html>

style.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background: rgb(223, 112, 48); 
}
.container {
    background: white;
    background-image: url(images.jpeg);
    width: 46%;
    margin: auto;
    padding: 25px;
    border-radius: 10px;
    border: 2px solid rgb(218, 96, 229)
}
h2{
    color: rgb(70, 59, 11);
}
hr {
    border: none;
    height: 2px;
    background: rgb(255, 125, 89);
    margin: 10px 0 20px 0;
}
p {
    line-height: 2;
    color: black;
}
.quote {
    border: 1px solid rgb(0, 0, 0);
    background: rgba(253, 135, 0, 0.742);
    border-left: 5px solid rgb(14, 3, 3);
    padding: 15px;
    margin: 25px 0;
    font-style: italic;
    color: rgba(255, 0, 0, 0.516);
    border-radius: 5px;
}
.author-box {
    display: flex;
    background: rgb(255, 51, 0);
    padding: 15px;
    border-radius: 10px;
    border: 1px solid rgb(255, 94, 134);
    margin-top: 25px;
    gap: 15px;
}
.author-box img {
    border-radius: 8px;
    width: 80px;
    height: 80px;
    object-fit: cover;
    border: 2px solid rgb(96, 42, 13);
}
.author-box h3 {
    margin: 0 0 5px 0;
    color: rgb(96, 39, 8);
}
.footer {
    margin-top: 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgb(106, 50, 4);
    color: rgb(255, 173, 101);
    padding: 12px 20px;
    border-radius: 10px;
}
.price {
    font-weight: bold;
    font-size: 18px;
}


```

## OUTPUT:

![alt text](<Screenshot (42).png>)
## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
