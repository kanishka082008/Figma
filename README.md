# Ex09 Event Registration Web Application
## Date:25/5/26

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
home page 

html
<!DOCTYPE html>
<html>
<head>
    <title>Event Registration</title>
    <link rel="stylesheet" href="page1.css">
</head>
<body>

<div class="container">

    <div class="header">
        <img src="logo.jpg" alt="College Logo">
    </div>

    <h2>WELCOME YOU TO THE EVENT DAY</h2>

    <button class="register-btn">REGISTER</button>

    <p class="contact">CONTACT US</p>

</div>

</body>
</html>

css

body{
    margin:0;
    padding:0;
    font-family: Arial, sans-serif;
    background:#111;
}

.container{
    width:300px;
    height:600px;
    background:#f7eaea;
    margin:30px auto;
    text-align:center;
    position:relative;
}

.header img{
    width:100%;
    height:50px;
}

h2{
    color:#b03090;
    font-size:20px;
    margin-top:80px;
    font-style:italic;
}

.register-btn{
    margin-top:40px;
    padding:10px 40px;
    border:none;
    background:#f7cfcf;
    color:#c05c5c;
    font-weight:bold;
    cursor:pointer;
}

.contact{
    position:absolute;
    bottom:30px;
    width:100%;
    color:purple;
    font-weight:bold;
}

page 2

html
<!DOCTYPE html>
<html>
<head>
    <title>Event List</title>
    <link rel="stylesheet" href="page2.css">
</head>
<body>

<div class="container">

    <div class="header">
        <img src="logo.jpg" alt="College Logo">
    </div>

    <h3>list of events</h3>

    <ul>
        <li>industrial visit</li>
        <li>hackathon</li>
        <li>quiz</li>
        <li>workshop</li>
        <li>cerebro quest</li>
        <li>SDG goals</li>
    </ul>

    <p class="register-text">CLICK TO REGISTER</p>

</div>

</body>
</html>

css

body{
    margin:0;
    padding:0;
    background:#111;
    font-family:Arial, sans-serif;
}

.container{
    width:300px;
    height:600px;
    background:#e5b4e8;
    margin:30px auto;
    padding:10px;
    box-sizing:border-box;
}

.header img{
    width:100%;
    height:50px;
}

h3{
    color:#7d1f7d;
    margin-top:30px;
    font-style:italic;
}

ul{
    margin-top:30px;
}

li{
    margin:20px 0;
    font-weight:bold;
}

.register-text{
    text-align:center;
    margin-top:50px;
    font-style:italic;
    color:#5b215b;
}
page 3

html
<!DOCTYPE html>
<html>
<head>
    <title>Registration Form</title>
    <link rel="stylesheet" href="page3.css">
</head>
<body>

<div class="container">

    <div class="header">
        <img src="logo.jpg" alt="College Logo">
    </div>

    <h2>PERSONAL DETAILS</h2>

    <form>

        <div class="form-group">
            <label>FULL NAME</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>GENDER</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>AGE</label>
            <input type="number">
        </div>

        <div class="form-group">
            <label>DEPARTMENT</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>MOBILE.NO</label>
            <input type="text">
        </div>

        <div class="form-group">
            <label>EMAIL ID</label>
            <input type="email">
        </div>

        <button type="submit">REGISTER</button>

    </form>

</div>

</body>
</html>

css

body{
    margin:0;
    padding:0;
    background:#111;
    font-family:Arial, sans-serif;
}

.container{
    width:300px;
    height:600px;
    background:#d45ed4;
    margin:30px auto;
    padding:10px;
    box-sizing:border-box;
}

.header img{
    width:100%;
    height:50px;
}

h2{
    text-align:center;
    color:white;
    margin-top:20px;
}

.form-group{
    margin:20px 0;
}

label{
    display:block;
    color:white;
    font-weight:bold;
    margin-bottom:5px;
}

input{
    width:100%;
    padding:8px;
    border:none;
}

button{
    width:100%;
    padding:10px;
    border:none;
    background:white;
    color:purple;
    font-weight:bold;
    cursor:pointer;
    margin-top:20px;
}
page 4

html

<!DOCTYPE html>
<html>
<head>
    <title>Success Page</title>
    <link rel="stylesheet" href="page4.css">
</head>
<body>

<div class="container">

    <div class="header">
        <img src="logo.jpg" alt="College Logo">
    </div>

    <h2>REGISTRATION SUCCESSFULL</h2>

    <div class="tick">
        ✓
    </div>

    <p class="success-text">
        You're registered successfully
    </p>

    <p class="details">
        All details have been sent to the registered email-id
    </p>

    <p class="contact">
        FACING TROUBLE? CONTACT US
    </p>

</div>

</body>
</html>

css

body{
    margin:0;
    padding:0;
    background:#111;
    font-family:Arial, sans-serif;
}

.container{
    width:300px;
    height:600px;
    background:#a81ca8;
    margin:30px auto;
    text-align:center;
    color:white;
    padding:10px;
    box-sizing:border-box;
}

.header img{
    width:100%;
    height:50px;
}

h2{
    margin-top:30px;
    font-size:22px;
}

.tick{
    width:80px;
    height:80px;
    background:#28c840;
    border-radius:50%;
    margin:40px auto;
    line-height:80px;
    font-size:50px;
    font-weight:bold;
}

.success-text{
    font-size:20px;
    margin-top:20px;
}

.details{
    margin-top:20px;
    font-style:italic;
}

.contact{
    margin-top:80px;
    color:black;
    font-weight:bold;
}

```

## OUTPUT:
![alt text](<Screenshot 2026-05-25 150848.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
