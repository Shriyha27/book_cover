# Ex.06 Book Front Cover Page Design
# Date: 21.04.2025
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
book.html

<!DOCTYPE html>
<html>

<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color:white;
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color:black;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      margin: 50px auto;
      position: relative;
    }
    
    .book-cover .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 24px;
      font-weight: bold;
      color: azure;
    }
    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 10px;
      width: 80px;
    }
    .book-cover .title1 {
      position: absolute;
      top: 150px;
      left: 90px;
      font-size: 40px;
      font-weight: bold;
      text-align: center;
      color:  white;
    }
    .book-cover .title2 {
      position: absolute;
      top: 190px;
      left: 65px;
      font-size: 40px;
      font-weight: bold;
      text-align: center;
      color:  white;
    }

    .book-cover .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color:  white;
    }
    .book-cover .subtitle2 {
      position: absolute;
      top: 500px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: white;
    }
    .book-cover .subtitle3 {
      position: absolute;
      top: 530px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: white;
    }
    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }
    


    .book-cover .author {
      position: absolute;
      bottom: 35px;
      left: 20px;
      font-size: 24px;
      color: whitesmoke;
    }

    .book-cover .number {
      position: absolute;
      bottom: 5px;
      left: 20px;
      font-size: 18px;
      color: white;
    }

    .book-cover .end {
      position: absolute;
      bottom: 5px;
      right: 50px;
      font-size: 18px;
      color: white;
    }

    .book-cover .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
    .authorpic{
           position: relative;
           top: 465px;
           left: 300px;
           width: 100px;
           height: 100px;
           background-size: cover;
       }
  </style>
</head>

<body>
 
  <div class="book-cover">
    <img src="pngtree-deep-sea-plant-rock-cartoon-sea-water-advertising-background-picture-image_2249600.jpg" alt="Book Cover Image" class="image">
    <div class="insight"><b><i>An Untold Story</i></b></div>
    <div class="line1"><hr style="color:blanchedalmond"></div>
    
    <center><div class="title1" style="font-style:italic;">HIDE AND SEEK</div></center>

    <div class="title2">The sea and its depth </div>
    <div class="subtitle1"></div>
    <div class="bottom"><b><i>OLIVIA WILSON</i></b></div>
    <div class="line1"><hr style="color:blanchedalmond"></div>
    <div class="line3"><hr style="color:red"></div>
    <div class="author">OLIVIA WILSON </div>
    <div class="authorpic">
      <img src="auhtor1.jpeg" width="125" height="150" alt="">
  </div>
    <div class="number"> </div>

    

  </div>
</body>

</html>
  
```
# OUTPUT:
![alt text](<bcpro/Screenshot 2025-04-22 111734.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
