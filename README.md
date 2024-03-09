# Dars
Problem statement no: 92.

Problem title: E-Waste collection locator.

we are building a website of e-waste collection collection locator with this website you can locate nearest e-waste collection spots.and you will get information of the e-waste.
codes.

front page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FRONT PAGE</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,300;0,600;0,700;1,500&display=swap" rel="stylesheet">
    <style>
        *{
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            
        }
        .header{
            min-height: 100vh;
            width: 100%;
            background-image: linear-gradient(rgba(4, 9, 30, 0.7),rgba(4,9,30,0.7)),url("secondpage2.jpg");
            background-position: center;
            background-size: medium;
            position: relative;
        }
        nav{
            display: flex;
            padding: 2% 6%;
            justify-content: space-between;
            align-items: center;
        }
        
        .nav-links{
            flex: 1;
            text-align: right;
        }
        .nav-links ul li{
            list-style: none;
            display: inline-block;
            padding: 8px 12px;
            position: relative;
        }
        .nav-links ul li a{
            color: white;
            text-decoration: none;
            font-size: 13px;
        }
        .nav-links ul li::after{
            content: '';
            width: 0px;
            height: 2px;
            background: #f44336;
            display: block;
            margin: auto;
            transition: 0.5s;
        }    
        .nav-links ul li:hover::after{
            width: 100%;
        }
        .text-box{
            width: 90%;
            color: #fff;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            text-align: center;
        }
        .text-box h1{
            font-size: 62px;
            text-decoration-line: none;
        }
        .text-box p{
            margin: 10px 0 40px;
            font-size: 14px;
        }
        .j-project{
            display:inline-block;
            text-decoration: none;
            color: #fff;
            border: 1px solid #fff;
            padding: 12px 34px;
            font-size: 12px;
            position: relative;
            cursor: pointer;
        }
        .j-project:hover{
            border: 1px solid #f44336;
            background: #f44336;
            transition: 1s;   
        }
        /*-------TOP DESTINATION-----------*/
        .destination{
            height: 80%;
            width: 60%;
            margin: auto;
            text-align: center;
            padding-top: 100px;
        }
        h1{
            font-size: 36px;
            font-weight: 600;
            text-decoration: underline;
        }
        h2{
            margin-top: 20px;
            color:#fff(0,0,255)
        }
        p{
            color: #777;
            font-size: 14px;
            font-weight: 22px;
            padding: 10px;
        }
        .row{
            margin-top: 10px;
            display: flex;
            justify-content: space-between;
        }
        .destination-col{
            flex-basis: 31%;
            background: #fff;
            border-radius: 15px;
            padding: 20px -41px;
            box-sizing: border-box;
            transition: 0.5s;
            height: 80%;
            
        }
        .destination-col img{
            width: 100%; 
            display: block;
        }
        h3{
            text-align: center;
            font-weight: 600;
            margin: 5px;
        }
        .destination-col:hover{
            box-shadow: 0 0 20px 0px rgba(27, 23, 253, 0.2);
        }
        .posts{
            width: 80%;
            margin: auto;
            text-align: center;
            padding-top: 50px;
        }
        .posts-col{
            flex-basis: 32%;
            margin-bottom: 30px;
            position: relative;
            overflow: hidden;
        }
        .posts-col img{
            width: 100%; 
            display: block;
        }
        body{
            background-color: navajowhite;
            
        }

        footer{
            margin-top: 25px;
            height: 32px;
            background-color: #222;
            padding: 9px;
            text-align: center;
            color: white;
        }
        
    </style>
</head>
<body>
    <section class="header">
        <nav>
            <div class="nav-links">
                <ul>
                    <li><a href="FRONT PAGE.html">HOME</a></li>
                    <li><a href=".html">About Us</a></li>
                    <li><a href="Map.html">E-Waste Mapper</a></li>
                    <li><a href="gallary.html">Event Photo</a></li>
                    <li><a href="CONATCT.html">CONTACT Us</a></li>
                    <li><a href="about developers.html">Developers</a></li>
                   
                </ul>
            </div>
        </nav>

            <div class="text-box">
                <h1>Let's Collect E-Waste</h1>
                <a href="after subscribe.html" class="j-project">Join</a>
            </div>
    </section>
    <!-------TOP DESTINATION------->
    <section class="destination">
        <h1></h1>
    <!-----INTERNATIONAL----------->
        <h2></h2>
            <div class="row">
                <div class="destination-col">
                    <h3></h3>
                    
                    
                </div>
                <div class="destination-col">
                    <h3></h3>
                    
                </div>
                <div class="destination-col">
                    <h3></h3>
                </div>
            </div>
    <!-------NATIONAL------------->
            <h2>E-waste or electronic waste team means discarded electrical or electronic devices or components. Whenever an electronic or electrical component or device whose working life has expired or been damaged, or is no longer used by people due to technological advancements,  comes under e-waste. As we know, technology changes day by day due to which a large amount of electronic or electrical devices are turning into waste. Some of the common e-waste elements are mobile phones, computers, laptops, hard drives, fans, microwaves, DVD, printers, lamps, etc. E-waste is a serious issue for our environment because it releases harmful toxic chemicals from the metals due to chemical reactions and these toxic chemicals harm our environment. The management of such type of waste is known as E-waste management.So,join with us to control E-waste.</h2>
            <div class="row">
                <div class="destination-col">
                    <a href=".html"></a>
                    <h3></h3>
                </div>
                <div class="destination-col">
                    <h3></h3>
                    
                </div>
                <div class="destination-col">
                    <a href=".html"></a>
                    <h3></h3>
                </div>
            </div>
    </section>
    <!------POPULAR POSTS--------->
<footer>
    <p>Developed by Coders</p>
</footer>
</body>
</html>

codes of gallery,contact,developers 

gallery
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width>, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,300;0,600;0,700;1,500&display=swap" rel="stylesheet">
    <title>BLOG</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
        }
        header{
            height: 100px;
            background-color: #222;
        }
        body {
            background-color: navajowhite;
        }
        nav{
            display: flex;
            padding: 2% 6%;
            justify-content: space-between;
            align-items: center;
        }
        nav img{
            width: 150px;
        }
        .nav-links{
            flex: 1;
            text-align: right;
        }
        .nav-links ul li{
            list-style: none;
            display: inline-block;
            padding: 8px 12px;
            position: relative;
        }
        .nav-links ul li a{
            color: burlywood;
            text-decoration: none;
            font-size: 13px;
        }
        .nav-links ul li::after{
            content: '';
            width: 0px;
            height: 2px;
            background: #f44336;
            display: block;
            margin: auto;
            transition: 0.5s;
        }    
        .nav-links ul li:hover::after{
            width: 100%;
        }
        .row{
            margin-top: 10px;
            display: flex;
            justify-content: space-between;
        }
        .posts{
        width: 80%;
        margin: auto;
        text-align: center;
        padding-top: 50px;
        }
        .posts-call{
            flex-basis: 32%;
            margin-bottom: 30px;
            position: relative;
            overflow: hidden;
        }
        .posts-call img{
            width: 100%; 
            display: block;
        }
        footer{
        height: 300px;
        background-color: #222;
        padding: 20px;
        text-align: center;
        color: white;
        }
    </style>
</head>
<body>
    <section class="posts">
        <h1>Event Photo</h1>
        <div class="row">
            <div class="posts-call">
                <img src="bengaluru.webp">
                <h3>Next-Gen Muncipal Conference,Bengaluru.</h3>
            </div>
            <div class="posts-call">
                <img src="delhi.jpeg">
                <h3>Cleane e India,Delhi.</h3>
            </div>
            <div class="posts-call">
                <img src="nagpur.jpg" height="255px">
                <h3>IMA Conference,Nagpur.</h3>
            </div>
        </div>
        <div class="row">
            <div class="posts-call">
                <img src="germany.jpeg" height="220px">
                <h3>Battery Recycling Expo,Germany.</h3>
            </div>
            <div class="posts-call">
                <img src="pune.webp">
                <h3>E-waste and plastic collection,Pune.</h3>
            </div>
            <div class="posts-call">
                <img src="hyderabad.webp">
                <h3>E-waste Pickup drive,Hyderabad.</h3>
            </div>
        <div>
        </section>
    

    <footer>
        <p>Developed by Coders</p>
    </footer>
</body>
</html>

contact
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,300;0,600;0,700;1,500&display=swap" rel="stylesheet"><link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,300;0,600;0,700;1,500&display=swap" rel="stylesheet">
    <title>Contact Page</title>
    <style>
        *{
            font-family: 'Poppins', sans-serif;
            margin: 0;
        }
        header{
            height: 100px;
            background-color: #222;
        }
        nav{
            display: flex;
            padding: 2% 6%;
            justify-content: space-between;
            align-items: center;
        }
        nav img{
            width: 150px;
        }
        .nav-links{
            flex: 1;
            text-align: right;
        }
        .nav-links ul li{
            list-style: none;
            display: inline-block;
            padding: 8px 12px;
            position: relative;
        }
        .nav-links ul li a{
            color: white;
            text-decoration: none;
            font-size: 13px;
        }
        .nav-links ul li::after{
            content: '';
            width: 0px;
            height: 2px;
            background: #f44336;
            display: block;
            margin: auto;
            transition: 0.5s;
        }    
        .nav-links ul li:hover::after{
            width: 100%;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: white;
        }

        .container {
            width: 100%;
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            border: 1px solid #ccc;
            box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
            transition: 0.3s;
        }
        h2{
            text-align: center;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            max-width: 600px;
            margin: 50px auto;
        }
        .contact-form input[type="text"],
        .contact-form input[type="email"],
        .contact-form textarea {
            margin-bottom: 20px;
            padding: 10px;
            font-size: 16px;
            width: 100%;
            border: 1px solid #ddd;
        }
        button[type="submit"] {
            background-color: rgb(5, 5, 250);
        } 
        button[type="submit"]:hover {
            background-color: rgb(225, 225, 228);
        }
        a{
            text-decoration: none;
            color:rgb(255,255,255);
        }
        a :hover{
            color: rgb(0,0,255);
        }
        footer{
        height: 300px;
        background-color: #222;
        padding: 20px;
        text-align: center;
        color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Contact Us</h2>
        <form class="contact-form" action="">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message"></textarea>
            <button type="submit"><a href="after contact us.html">Submit</a></button>
    </form>
    </div>
    <footer>
        <p>Developed by Coders</p>
    </footer>
</body>
</html>

developer
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,300;0,600;0,700;1,500&display=swap" rel="stylesheet">
    <style>
        *{
            font-family: 'Poppins', sans-serif;
        }
        header{
            height: 100px;
            background-color: #222;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: navajowhite;
        }

        .header {
            background-color: #333;
            padding: 20px;
            text-align: center;
            color: white;
        }
        nav{
            display: flex;
            padding: 2% 6%;
            justify-content: space-between;
            align-items: center;
        }
        nav img{
            width: 150px;
        }
        .nav-links{
            flex: 1;
            text-align: right;
        }
        .nav-links ul li{
            list-style: none;
            display: inline-block;
            padding: 8px 12px;
            position: relative;
        }
        .nav-links ul li a{
            color: white;
            text-decoration: none;
            font-size: 13px;
        }
        .nav-links ul li::after{
            content: '';
            width: 0px;
            height: 2px;
            background: #f44336;
            display: block;
            margin: auto;
            transition: 0.5s;
        }    
        .nav-links ul li:hover::after{
            width: 100%;
        }
        h1{
            text-align: center;
            margin-top: 30px;
            margin-bottom: 10px;
        }
        .content {
            margin: 150px 100px;
        }

        .profile-picture {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
        }

        .contact-info {
            background-color: #ffffff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            display: inline-block;
        }

        .contact-info h3 {
            margin-bottom: 20px;
            text-align: center;
        }

        .footer {
            background-color: #333;
            padding: 20px;
            text-align: center;
            color: white;
        }
    </style>
</head>
<body>
    <section>
        <h1>DEVELOPERS</h1>
        <div class="content">
            <img src="JM-photo.jpg" class="profile-picture">
            <div class="contact-info">
                <h3>DARSHAN P K</h3>
                <p>Email:darshandarshanpk@gmail.com</p>
                <p>Address:LPU</p>
            </div>
            <hr></hr>
            <br></br>
            <img src="profile-picture.jpg" class="profile-picture">
            <div class="contact-info">
                <h3>Nitin Kumar Sharma</h3>
                <p>Email:sharmanitinkumar782@gmail.com</p>
                <p>Address:LPU</p>
            </div>
            <img src="profile-picture.jpg" class="profile-picture">
            <div class="contact-info">
                <h3>Vishal Kumar Yadav</h3>
                <p>Email:vishalkumarkumar65177@gmail.com</p>
                <p>Address:LPU</p>
            </div>
            <img src="profile-picture.jpg" class="profile-picture">
            <div class="contact-info">
                <h3>Ashish Paswan</h3>
                <p>Email:Ashishpaswan@gmail.com</p>
                <p>Address:LPU</p>
            </div>
        </div>
    </section>

    
    <div class="footer">
        <p>Developed by Coders</p>
    </div>
    
</body>
</html>
        
