<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@600&display=swap" rel="stylesheet">
    <style>
        body {
            padding: 0px;
            margin: 0px;
            font-family: 'Baloo Bhai 2', cursive;
        }

        body::before {
            content: '';
            background:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.2)) ,url(https://websitedemos.net/outdoor-adventure-02/wp-content/uploads/sites/351/2018/11/about-bg-2.jpg)no-repeat center center/cover;
            width: 100%;
            height: 75%;
            position: absolute;
            z-index: -1;
            opacity: 0.99;
            } 

        .head {
           display: flex;
            color: white;
        }

        .logo {
            color: white;
            font-size: 2rem;
            margin: 17px 12px;
        }

        .navbar {
            display: inline-block;
            position: absolute;
            top: 24px;
            right: 20px;
            margin: 12px 385px;
        }

        .navbar li {
            display: inline-block;
            list-style: none;
            }

        .navbar li a {
            padding: 13px 18px;
            color: black;
            font-size: 30px;
            text-decoration: none;
        }

        .navbar li a:hover,
        .navbar li a.active {
            color: red;
        }

        .btn {
            position: absolute;
            top: 30px;
            right: 200px;
            border-radius: 30px;
            padding: 16px 39px;
            background-color: #fb2056;
            color: white;
            font-weight: bold;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
            border: none;
        }
        .mid{
            color: blue;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 500px;
        }
        .mids{
            font-size: 6rem;
            margin-bottom: 80px;
            font-weight: bold;
        }
        .center {
            display: flex;
            margin-top: 100px;
        }

        .form {
            margin: 12px 12px;
            padding: 12px 85px;
            width: 50%;
        }

        .right {
            margin: 12px 12px;
            padding: 12px 12px;
            width: 50%;
        }

        h1 {
            font-size: 3.5rem;
        }

        input,
        textarea {
            padding: 22px 12px;
            margin: 15px 12px;
            width: 70%;
            background-color: #f7f7f7;
            border: none;
        }
        

        .btns {
            width: 25%;
            border-radius: 30px;
            padding: 16px 39px;
            background-color: #fb2056;
            color: white;
            font-weight: bold;
            font-size: 16px;
            cursor: pointer;
            text-align: center;
            border: none;
        }
        span,strong{
            font-size: 1.5rem;
        }
        .left{
            margin-bottom: 28px;
        }
        .con{
            margin-bottom: 28px;
        }
        .foot{
            background-color: black;
            color: white;
            text-align: center;
            padding: 54px 12px;
            font-size: 20px;
            margin-top: 80px;
        }
    </style>
</head>
<body>
    <header>
        <div class="head">
            <h1 class="logo">OUTDOOR <br> ADVENTURE</h1>
            <ul class="navbar">
                <li><a href="Home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="servies.html">Servies</a></li>
                <li><a href="Project.html">Projects</a></li>
                <li><a href="contact.html"  class="active">Contact</a></li>
            </ul>
            <button class="btn">TAKE CARE</button>
        </div>
    </header>
    <section class="mid">
        <h1 class="mids">CONTACT US</h1>
    </section>
    <section class="center">
        <div class="form">
            <h1>WE'RE READY, LET'S TALK.</h1>
            <input type="text" name="name" id="name" placeholder="Your Name"><br>
            <input type="text" name="name" id="name" placeholder="Email Address"><br>
            <textarea name="address" id="address" cols="30" rows="5" placeholder="Message"></textarea>
            <br>
            <input type="button" value="SEND MESSAGE" class="btns">
        </div>
        <div class="right">
            <h1>CONTACT INFO</h1>
            <div class="left">
                <span><strong>Address</strong></span><br>
                <span>123 Fifth Avenue, NY 10160, New York, USA</span><br>
            </div>
            <div class="con">
                <span><strong>Email Us</strong></span><br>
                <span>contact@example.com</span><br>
            </div>
            <div class="con1">
                <span><strong>Call Us</strong></span><br>
                <span>800-123-456</span><br>
            </div>
        </div>
    </section>
    <footer class="foot">
        <p class="para4">123 Fifth Avenue, NY 10160, New York, USA | Phone: 800-123-456 | Email: contact@example.com</p>
        <p class="para5">Copyright © 2020 Outdoor Adventure</p>
    </footer>
</body>
</html>
