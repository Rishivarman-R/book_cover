# Ex.06 Book Front Cover Page Design
# Date:09/11/2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Title</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Qwitcher+Grypen:wght@400;700&display=swap" rel="stylesheet">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Londrina+Sketch&family=Qwitcher+Grypen:wght@400;700&display=swap" rel="stylesheet">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&display=swap" rel="stylesheet">
    
    


    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family:'Georgia', serif ;
            #background: linear-gradient(135deg, #f3e5ab, #e8d094);
           
        }
        .book-cover {
            width: 400px;
            height: 600px;
            background-color: #e1e2e200;
            border: 8px solid #000c01;
            box-shadow: 0 10px 30px rgba(227, 224, 224, 0.766);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 40px;
            text-align: center;
        }
        .title {
            font-size: 60px;
            font-weight:bolder;
            color: #b00d0d;
            font-family: "calibran", normal;
        }
        .author {
            font-size: 29px;
            #margin-top: 10px;
            color: #fafdfd;
            font-family: "Caveat",normal;
            font-weight: 900;
            text-align: right;
        }
        .moneyimage{
            width: 280px; text-align: center;
        }
        .bestsellerimage{
            width: 70px;
            float: right;
        }
        #.images{
            display: flex;
            width: 28px;
        }
        .about{
            letter-spacing: 2px;
            color: rgb(139, 222, 241);
            font-weight: 400;
        }
        .publisher {
            font-size: 18px;
            color: #6b4f3f;
        }
        #.cover-design {
            margin-top: 0px;
            background-image: url(habook.jpg); /* Example cover art */
            background-size: cover;
            background-position: center;
            height: 80px;
            border: 2px solid #d40b0b;
        }
        .about2{
            font-weight: 200;
            font-style: italic;
        }
        .about2sub{
            letter-spacing: 1px;
            font-weight: 500;
            font-size:medium;
        }
        .footer {
            font-size: 14px;
            margin-top: 20px;
            color: #e9e5e4;
            font-family: "Caveat", cursive;

        }
        .bookpage{


            
            
            background-image: url(habook.jpg);
            background-size: cover;
        }
        nav{
            background-image:url(habook.jpg);
           
          background-position:center;
          background-size:cover;
         
        } 
        
        body{
          
          
          width: 400px;
          
          color:rgb(166, 154, 154);
          margin-left: auto;
          margin-right: auto;
          padding: 20px;
          font-family: ' Arial, sans-serif';
        }
    </style>

</head>
<body >
    <center>

</center>
    
     
    <nav>
    <div class="book-cover" >
        <div class="title">Dark Psychology & Manipulation </div>
        <div class="author"></div>
        <div>
            
          
        
        </div>
        
        <div class="cover-design"></div>
        <div class="about">  </div>
        <!--<div class="publisher">Published by Wonder House Publishing</div>-->
        <div class="author">--Vincent MC Daniel</div>
        <div class="footer">🎯uncover the secrete to Analyzing people and Controlling Human Behavior</div>
    </div></nav>

</body>
</html>
```
# OUTPUT:

![Screenshot (42)](https://github.com/user-attachments/assets/f8c1e59b-2379-41d8-ad03-dde45e6f2827)




# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
