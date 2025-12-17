# Ex.05 Book Cover Page Design
## Date:18/12/2025

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
<html>
    <head>
        <title>Cascading Style Sheet</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="cover">
            <div class="head">
            <h1>ABOUT THE BOOK</h1>
            <hr>
            </div>
            <div class="text">
                <p>This Book<span>Machine Learning (ML) is a type of Artificial Intelligence (AI)</span> where computers learn patterns from large datasets to make predictions or decisions without being explicitly programmed for every task, improving with more data, similar to human learning from experience. It uses algorithms to find hidden insights, powering applications like recommendation engines, speech recognition, medical diagnosis, and fraud detection by building models from data.</p>
            </div>
            <div class="quotes">
            "The development of full artificial intelligence could spell the end of the human race"
            </div>
            <div class="author-box">
                 <div class="img"></div>

                <div class="author">
                     <div class="author-name">SAKTHIVEL B</div>
                     <p>
                        Sakthivel B is a curious and dedicated student who enjoys learning and exploring new ideas. He believes in continuous growth and works towards building a positive future through knowledge and effort. 


                     </p>
                </div>
            </div>
            <div class="footer">
                <div class="footer-left">
                    <strong>SEC Publishers</strong>
                    <br>
                    <div class="printed">printed in India</div>
                </div>
                <div class="price">Price= RS399</div>
            </div>
        </div>
    </body>
</html>


body
{
    background: url('07c9f699-99b7-4db1-b1fa-82ea7247f535.jpg') center / contain no-repeat fixed;
    min-height: 100vh;
    display: flex;
    justify-content: center;
}
.cover
{
    padding-left: 700px;
    padding-right: 700px;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.head
{
    padding-top: 20px;
    font-style: Montserrat;
    color: rgb(55, 41, 67);
    padding-left: 25px;
}
.text
{
    font-size: 16px;
    text-align: center;
    text-align: justify;
    padding-left: 25px;
    font-style:inherit
}
span
{
    background-color: rgb(137, 235, 207);
}
.quotes
{
    margin: 15px 0;
    padding: 15px 15px;
    background: rgb(105, 97, 97);
    border-left: 6px solid rgb(188, 131, 206);
    font-style: italic;
}
.author
{
    display: flex;
    flex-direction: column;
    font-size: 15px;
    
}

.author-box 
{
    display: flex;
    gap: 8px;
    background: rgb(237, 159, 173);
    padding: 8px;
    border-radius: 8px;
    margin-top: 15px;
    text-align: justify;
    align-items: center;
}
.img 
{
    width: 410px;
    height: 110px;
    border-radius: 8px;
    background-image: url('sakthi.jpeg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.author-name 
{
    color: rgb(203, 227, 137);
    font-weight: bold;
    font-size: 15px;
}
.footer 
{
    margin-top: auto;
    background-color:rgb(54, 139, 158);
    color: rgb(38, 37, 36);
    padding: 5px 5px;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.footer-left 
{
    display: flex;
    flex-direction: column;
}
.printed
{
    font-size: 14px;
}
.price 
{
    font-weight: bold;
    color: rgb(180, 64, 28);
    font-size: 18px;
}

```

## OUTPUT:
![alt text](<Screenshot (57).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
