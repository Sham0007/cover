# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Book Cover Page</title>
  <style>
    .bookpage {
      width: 400px;
      height: 600px;
      color: black;
      margin: 40px auto;
      padding: 20px;
      font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
      background-color: #ad6840; /* Soft bookish background */
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      border-radius: 8px;
      position: relative;
    }

    .insight {
      color: black;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .hrstyle hr {
      width: 120px;
      border: 2px solid yellow;
      margin: 5px 0 20px 0;
    }

    .booktitle h1 {
      font-family: 'Courier New', Courier, monospace;
      font-size: 22px;
      text-align: center;
      margin-bottom: 10px;
    }

    .subtitle {
      font-family: Tahoma, sans-serif;
      font-size: 16px;
      text-align: center;
      color: #333;
      margin-bottom: 30px;
    }

    .mypic img {
      position: absolute;
      top: 380px;
      right: 30px;
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 10px;
      border: 2px solid #fff;
    }

    .id hr {
      border: 1px solid orange;
      margin-top: 50px;
    }

    .author {
      position: absolute;
      bottom: 80px;
      left: 20px;
      font-family: Georgia, serif;
      font-size: 16px;
      color: red;
    }

    .pub {
      position: absolute;
      bottom: 80px;
      right: 30px;
      font-size: 14px;
      font-weight: bold;
    }

    .ed {
      position: absolute;
      bottom: 40px;
      left: 20px;
      font-size: 14px;
      color: black;
      font-family: Verdana, sans-serif;
    }
  </style>
</head>
<body>
  <div class="bookpage">
    <div class="insight">SEC INSIGHT</div>

    <div class="hrstyle"><hr /></div>

    <div class="booktitle">
      <h1>Web Development: The Complete Reference</h1>
    </div>

    <div class="subtitle">with Django and Bootstrap Insights</div>

    <div class="mypic">
      <img src="MARVEL.PNG" alt="Author Pic" />
    </div>

    <div class="id"><hr /></div>

    <div class="author"><b>DHANA AAKHAASH</b></div>
    <div class="pub">SEC</div>
    <div class="ed"><b>Extended Edition</b></div>
  </div>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/d0570cf0-7034-4685-a384-7214b9137596)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully..
