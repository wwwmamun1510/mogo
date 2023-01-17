![M-111](https://user-images.githubusercontent.com/97294949/212983778-76bc9642-b3e7-4f3a-94cb-8d8671be403f.GIF)
![M-222](https://user-images.githubusercontent.com/97294949/212983820-74bbe08b-5901-4d28-857f-28b24c1d9cbd.GIF)
![M-333](https://user-images.githubusercontent.com/97294949/212983868-19670b73-2289-4d37-8690-2d305d623244.GIF)
![M-666](https://user-images.githubusercontent.com/97294949/212983903-35ff5a6c-7a94-4c79-988f-e38bfbc5e8da.GIF)
![M-888](https://user-images.githubusercontent.com/97294949/212983938-dbba13b7-069a-4365-9dee-7de667c1e62d.GIF)
![M-980](https://user-images.githubusercontent.com/97294949/212983972-4fa0c510-c50b-46a9-b36a-8c8229349cca.GIF)
![M-999](https://user-images.githubusercontent.com/97294949/212984004-36925f65-54e4-4c3c-9d3e-1c6f121c910d.GIF)
![M-66677](https://user-images.githubusercontent.com/97294949/212984048-d68d5e48-b2eb-4f84-96ed-64dbb095a4a2.GIF)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)



{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

a{
    text-decoration: none;
}
ul,ol {
    list-style-type: none;
}
.clr {
    clear: both;
}
.container {
    width: 1200px;
    margin: 0 auto;
}
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,500;0,700;1,400&display=swap');

nav {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 999;
}
.nav-main {
    display: flex;
}
.logo {
    width: 200px;
}
.logo img {
    padding-top: 29px;
}
.menu {
    width: 1000px;
    text-align: right;
}
.menu ul li {
    display: inline-block;
    padding-left: 56px;
}
.menu ul li a {
    line-height: 80px;
    font-family: 'Montserrat', sans-serif;
    font-size: 14px;
    color:#fff;
    text-transform: uppercase;
    font-weight: 400;
    transition: all linear .3s;
    position: relative;
}
.menu ul li a:hover {
    color: #fce38a;
}
.menu ul li a::after {
    position: absolute;
    content: '';
    width: 0;
    height: 3px;
    background-color:#fce38a;
    left: 0;
    bottom: -12px;
    opacity: 0;
    transition: all linear .3s;
}
.menu ul li a:hover::after {
    opacity: 1;
    width: 100%;
}
/*============ navbar part css goes here =============*/

.banner-img {
    position: relative;
    background:url(../images/banner.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 100vh;
}
.banner-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: linear-gradient(rgba(243, 129, 129,0.9), rgba(252, 227, 138,0.9));
    display: flex;
    justify-content: center;
}
.banner-text {
    text-align: center;
    align-self: center;
}
.banner-text h3 {
    font-size: 72px;
    font-family: 'Kaushan Script', cursive;
    color: #fff;
    text-transform: capitalize;
}
.banner-text h1 {
    font-size: 150px;
    font-family: 'Montserrat', sans-serif;
    color: #fff;
    text-transform: uppercase;
    padding: 0 90px;
    position: relative;
    padding-bottom: 140px;
}
.banner-text h1::after {
    position: absolute;
    content: '';
    width: 60px;
    height: 3px;
    background-color: #fff;
    bottom: 97px;
    left: 50%;
    transform: translateX(-50%);
}
.banner-text a {
    border: 3px solid #fff;
    padding: 12px 30px;
    font-family: 'Montserrat', sans-serif;
    color: #fff;
    font-size: 14px;
    font-weight: 700;
    text-transform: uppercase;
}
/*============ About part css goes here =============*/
#about {
    padding-top: 92px;
    padding-bottom: 110px;
}
.head {
    text-align: center;
    padding-bottom: 100px;
}
.head h4 {
    font-size: 24px;
    font-family: 'Kaushan Script', cursive;
    color: #333;
    padding-bottom: 11px;
}
.head h2 {
    font-size: 30px;
    font-family: 'Montserrat', sans-serif;
    color: #333;
    text-transform: uppercase;
    font-weight: 700;
    padding-bottom: 80px;
    position: relative;
}
.head h2::after {
    position: absolute;
    content: '';
    width: 60px;
    height:3px;
    background-color: #f38181;
    bottom: 42px;
    left: 50%;
    transform: translateX(-50%);
}
.head p {
    font-size: 15px;
    font-family: 'Roboto', sans-serif;
    color: #999;
    font-weight: 400;
    line-height: 24px;
    padding:0 120px;
}
.about-main {
    display: flex;
    justify-content: space-between;
}
.about-item {
    width: 380px;
    position: relative;
}
.about-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: linear-gradient(rgba(243, 129, 129,0.9), rgba(252, 227, 138,0.9));
    display: flex;
    justify-content: center;
    opacity: 0;
}
.about-content {
    text-align: center;
    align-self: center;
}
.about-content i {
    font-size: 33px;
    color: #fff;
}
.about-content h3 {
    font-size: 18px;
    color: #fff;
    font-family: 'Montserrat', sans-serif;
    text-transform: uppercase;
    font-weight: 700;
    padding-top: 11px;
}
.about-item:hover .about-overlay {
    opacity: 1;
}
/*============ funfact part css goes here =============*/
#funfact{
    padding: 70px 0;
    background-color: #95e1d3;
}
.funfact-item {
    width: 240px;
    text-align: center;
}
.funfact-item h3 {
    font-size: 72px;
    color: #fff;
    font-family: 'Montserrat', sans-serif;
    text-transform: uppercase;
    font-weight: 700;
    padding-bottom: 10px;
}
.funfact-item p {
    font-size: 14px;
    color: #fff;
    font-family: 'Montserrat', sans-serif;
    text-transform: uppercase;
    font-weight: 400;
}
.funfact-main {
    display: flex;
}
/*============ service part css goes here =============*/
#service {
    padding-top: 107px;
}
.service-main{
    display: flex;
    justify-content: space-around;
}
.service-item {
    width: 340px;
    height: 200px;
    display: flex;
    justify-content: space-between;
}
.service-icon {
    width: 32px;
    padding-right: 30px;
}
.service-text {
    width: 278px;
}
.service-text h4 {
    font-size: 14px;
    color: #333;
    font-family: 'Montserrat', sans-serif;
    font-weight: 500;
    text-transform: uppercase;
    padding-bottom: 9px;
}
.service-text p {
    font-size: 15px;
    font-family: 'Roboto', sans-serif;
    color: #999;
    font-weight: 400;
    line-height: 24px;
}
.service-main.main2 {
	margin-top: -30px;
}
#service .head {
    padding-bottom: 24px;
}
/*============ feedback part css goes here =============*/
.feedback-main {
    width: 968px;
    margin: 0 auto;
    display: flex;
}
#feedback {
    background-color: #f8f8f8;
    padding-top: 70px;
    padding-bottom: 70px;
}
.feed-icon {
    width: 144px;
    margin-right: 60px;
    height: 144px;
    text-align: center;
    border:3px solid #95e1d3;
    display: flex;
    justify-content: center;
}
.feed-icon img {
    align-self: center;
}
.feed-text {
    width: 764px;
}
.feed-text p {
    font-style: italic;
    font-weight: 300px;
    color: #999;
    font-size: 24px;
    line-height: 36px;
    padding-bottom: 14px;
}
.feed-text h5 {
    padding-left: 70px;
    font-size: 24px;
    font-family: 'Kaushan Script', cursive;
    color: #333;
    text-transform: capitalize;
    position: relative;
}
.feed-text h5::after {
    position: absolute;
    content: '';
    width: 60px;
    height: 3px;
    background-color: #f38181;
    top:50%;
    left: 0;
    transform:translateY(-50%) ;
}
.feedback {
    position: relative;
}
.feedback i {
    color: #ccc;
    font-size: 21px;
}
.left {
    position: absolute;
    top: 50%;
    left: 0;
    transform: translateY(-50%);
}
.right {
    position: absolute;
    top: 50%;
    right: 0;
    transform: translateY(-50%);
}
/*============ team part css goes here =============*/
#team {
    padding-top: 100px;
    padding-bottom: 92px;
}
.team-main {
    display: flex;
    justify-content: space-between;
}
.team-item {
    width: 380px;
}
.team-img {
    position: relative;
}
.team-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: linear-gradient(rgba(243, 129, 129,0.9), rgba(252, 227, 138,0.9));
    display: flex;
    justify-content: center;
    opacity: 0;
    display: flex;
    transition: all linear .3s;
}
.social {
    align-self: center;
}
.social i {
    width: 56px;
    height: 56px;
    line-height: 56px;
    text-align: center;
    background-color: #fce38a;
    color: #f38181;
    font-size: 26px;
    margin-right: -3px;
    transition: all linear .3s;
}
.social i:hover {
    background-color: #f38181;
    color: #fff;
}
.team-info {
    text-align: center;
    padding-top: 40px;
}
.team-info h3 {
    font-size: 14px;
    color: #333;
    font-weight: 600;
    font-family: 'Montserrat', sans-serif;
    text-transform: uppercase;
    padding-bottom: 9px;
}
.team-info p {
    font-size: 15px;
    color: #999;
    font-weight: 300;
    font-style: italic;
    font-family: 'Roboto', sans-serif;
    text-transform: capitalize;
}
.team-item:hover .team-overlay{
    opacity: 1;
}
/*============ gallery part css goes here =============*/
#gallery {
    padding-bottom: 100px;
}
.gallery-main {
    display: flex;
}
.gallery-item {
    width: 25%;
}
.gal-img {
    position: relative;
    line-height: 0;
}
.gal-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: linear-gradient(rgba(243, 129, 129,0.9), rgba(252, 227, 138,0.9));
    display: flex;
    justify-content: center;
    opacity: 0;
    display: flex;
    transition: all linear .3s;
}
.gal-info {
    text-align: center;
    align-self: center;
}
.gal-info i {
    color: #fff;
}
.gal-info h3 {
    font-size: 14px;
    color: #fff;
    font-weight: 500;
    font-family: 'Montserrat', sans-serif;
    text-transform: uppercase;
    padding-top: 25px;
}
.gal-info p {
    font-size: 15px;
    color: #fff;
    font-weight: 300;
    font-style: italic;
    font-family: 'Roboto', sans-serif;
    text-transform: capitalize;
    padding-top: 27px;
}
.gal-img:hover .gal-overlay {
    opacity: 1;
}
/*============ Footer part css goes here =============*/
.footer-main {
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid #e5e5e5;
    padding-bottom: 70px;
}
.footer-item-left {
    width: 465px;
}
.footer-item-mid {
    width:350px;
}
.footer-item-right {
    width: 270px;
}
footer {
    background-color: #f8f8f8;
    padding-top: 75px;
}
.footer-item-left p {
    font-size: 15px;
    color: #999;
    font-family: 'Roboto', sans-serif;
    font-weight: 400;
    line-height: 24px;
    padding-top: 36px;
}
.footer-item-left h6 {
    font-family: 'Montserrat', sans-serif;
    font-size: 14px;
    color: #333;
    padding-top: 43px;
    font-weight: 400;
    padding-bottom: 19px;
    border-bottom: 1px solid #e5e5e5;
}
.footer-item-left h6 span {
    font-weight: 700;
    font-size: 18px;
}
.footer-item-left h5 i {
    color: #95e1d3;
    font-size: 16px;
    padding-left: 19px;
}
.footer-item-left h5 {
    padding-top: 16px;
    padding-bottom: 40px;
    font-size: 15px;
    color: #999;
    font-weight: 300;
    font-style: italic;
    font-family: 'Roboto', sans-serif;
    text-transform: capitalize;
}
.form {
    width: 380px;
    position: relative;
}
.form input {
    width: 100%;
    height: 38px;
    padding-left: 12px;
    border: 1px solid #e7e7e7;
}
.form button {
    padding: 10px 34px;
    background-color: #95e1d3;
    border: 0;
    font-size: 14px;
    color: #fff;
    font-weight: 700;
    text-transform: uppercase;
    font-family: 'Montserrat', sans-serif;
    position: absolute;
    top: 0;
    right: 0;
}
.form input::placeholder {
    font-size: 15px;
    color: #999;
    font-weight: 300;
    font-style: italic;
    font-family: 'Roboto', sans-serif;
    text-transform: capitalize;
}

.footer-item-mid h3{
    font-family: 'Montserrat', sans-serif;
    font-weight: 600;
    font-size: 14px;
    color: #333;
    text-transform: uppercase;
    padding-bottom: 36px;
}
.blog-item {
    display: flex;
    justify-content: space-between;
    padding-bottom: 25px;
}
.blog-img {
    width: 120px;
}
.blog-text {
    width: 210px;
}
.blog-text h4 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 600;
    font-size: 12px;
    color: #333;
    line-height: 18px;
    text-transform: uppercase;
    padding-top: 15px;
}
.blog-text p {
    font-size: 13px;
    color: #999;
    font-weight: 300;
    font-style: italic;
    font-family: 'Roboto', sans-serif;
    padding-top: 5px;
}
.footer-item-right h3{
    font-family: 'Montserrat', sans-serif;
    font-weight: 600;
    font-size: 14px;
    color: #333;
    text-transform: uppercase;
    padding-bottom: 36px;
}
.insta-main {
    display: flex;
    flex-wrap: wrap;
}
.insta-item {
    width: 33%;
}
.view-btn {
    padding-top: 10px;
}
.view-btn a {
    font-size: 13px;
    color: #999;
    font-weight: 300;
    font-style: italic;
    font-family: 'Roboto', sans-serif;
}
.copyright {
    text-align: center;
}
.copyright p {
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 14px;
    color: #333;
    line-height: 60px;
}
.copyright span {
    color: #f38181;
}
/*============ navbar part css goes here =============*/
/*============ navbar part css goes here =============*/
/*============ navbar part css goes here =============*/





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MOGO - Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;700;800&display=swap" rel="stylesheet"> 
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Kaushan+Script&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- navbar section start from here -->
    <nav>
        <div class="container">
            <div class="nav-main">
                <div class="logo">
                    <a href="#">
                        <img src="images/logo.png" alt="logo">
                    </a>
                </div>
                <div class="menu">
                    <ul>
                        <li><a href="#">About</a></li>
                        <li><a href="#">Service</a></li>
                        <li><a href="#">Work</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>

    <!-- Banner section start from here -->
    <section id="banner">
        <div class="banner-img">
            <div class="banner-overlay">
                <div class="banner-text">
                    <div class="container">
                        <h3>Creative Template</h3>
                        <h1>Welcome to MoGo</h1>
                        <a href="#">learn more</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About section start from here -->
    <section id="about">
        <div class="container">
            <div class="head">
                <h4>What we do</h4>
                <h2>Story about us</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
            </div>
            <div class="about-main">
                <div class="about-item">
                    <img src="images/about-item1.jpg" alt="about-item">
                    <div class="about-overlay">
                        <div class="about-content">
                            <i class="fa fa-user"></i>
                            <h3>Super Team</h3>
                        </div>
                    </div>
                </div>
                <div class="about-item">
                    <img src="images/about-item1.jpg" alt="about-item">
                    <div class="about-overlay">
                        <div class="about-content">
                            <i class="fa fa-user"></i>
                            <h3>Super Team</h3>
                        </div>
                    </div>
                </div>
                <div class="about-item">
                    <img src="images/about-item1.jpg" alt="about-item">
                    <div class="about-overlay">
                        <div class="about-content">
                            <i class="fa fa-user"></i>
                            <h3>Super Team</h3>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- fun fact section start from here -->
    <section id="funfact">
        <div class="container">
            <div class="funfact-main">
                <div class="funfact-item">
                    <h3>42</h3>
                    <p>Web design project</p>
                </div>
                <div class="funfact-item">
                    <h3>123</h3>
                    <p>happy client</p>
                </div>
                <div class="funfact-item">
                    <h3>15</h3>
                    <p>Award winner</p>
                </div>
                <div class="funfact-item">
                    <h3>42</h3>
                    <p>Web design project</p>
                </div>
                <div class="funfact-item">
                    <h3>42</h3>
                    <p>Web design project</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Service section start from here -->
    <section id="service">
        <div class="container">
            <div class="head">
                <h4>We work with</h4>
                <h2>amazing services</h2>
            </div>
            <div class="service-main">
                <div class="service-item">
                    <div class="service-icon">
                        <img src="images/icon1.png" alt="icon1">
                    </div>
                    <div class="service-text">
                        <h4>Photography</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                    </div>
                </div>
                <div class="service-item">
                    <div class="service-icon">
                        <img src="images/icon1.png" alt="icon1">
                    </div>
                    <div class="service-text">
                        <h4>Photography</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                    </div>
                </div>
                <div class="service-item">
                    <div class="service-icon">
                        <img src="images/icon1.png" alt="icon1">
                    </div>
                    <div class="service-text">
                        <h4>Photography</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                    </div>
                </div>
            </div>
            <div class="service-main main2">
                <div class="service-item">
                    <div class="service-icon">
                        <img src="images/icon1.png" alt="icon1">
                    </div>
                    <div class="service-text">
                        <h4>Photography</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                    </div>
                </div>
                <div class="service-item">
                    <div class="service-icon">
                        <img src="images/icon1.png" alt="icon1">
                    </div>
                    <div class="service-text">
                        <h4>Photography</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                    </div>
                </div>
                <div class="service-item">
                    <div class="service-icon">
                        <img src="images/icon1.png" alt="icon1">
                    </div>
                    <div class="service-text">
                        <h4>Photography</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- feedback section start from here -->
    <section id="feedback">
        <div class="container feedback">
            <i class="fa fa-chevron-left left"></i>
            <i class="fa fa-chevron-right right"></i>
            <div class="feedback-main">
                <div class="feed-icon">
                    <img src="images/feed-icon.png" alt="feed-icon">
                </div>
                <div class="feed-text">
                    <p>“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.”</p>
                    <h5>Jon Doe</h5>
                </div>
            </div>
        </div>
    </section>
    <!-- Team section start from here -->
    <section id="team">
        <div class="container">
            <div class="head">
                <h4>Who we are</h4>
                <h2>meet our team</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
            </div>
            <div class="team-main">
                <div class="team-item">
                    <div class="team-img">
                        <img src="images/team1.png" alt="team1" width="100%">
                        <div class="team-overlay">
                            <div class="social">
                                <a href="#"><i class="fa fa-facebook-f"></i></a>
                                <a href="#"><i class="fa fa-twitter"></i></a>
                                <a href="#"><i class="fa fa-pinterest-p"></i></a>
                                <a href="#"><i class="fa fa-instagram"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="team-info">
                        <h3>Matthew Dix</h3>
                        <p>Graphic Design</p>
                    </div>
                </div>
                <div class="team-item">
                    <div class="team-img">
                        <img src="images/team1.png" alt="team1" width="100%">
                        <div class="team-overlay">
                            <div class="social">
                                <a href="#"><i class="fa fa-facebook-f"></i></a>
                                <a href="#"><i class="fa fa-twitter"></i></a>
                                <a href="#"><i class="fa fa-pinterest-p"></i></a>
                                <a href="#"><i class="fa fa-instagram"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="team-info">
                        <h3>Matthew Dix</h3>
                        <p>Graphic Design</p>
                    </div>
                </div>
                <div class="team-item">
                    <div class="team-img">
                        <img src="images/team1.png" alt="team1" width="100%">
                        <div class="team-overlay">
                            <div class="social">
                                <a href="#"><i class="fa fa-facebook-f"></i></a>
                                <a href="#"><i class="fa fa-twitter"></i></a>
                                <a href="#"><i class="fa fa-pinterest-p"></i></a>
                                <a href="#"><i class="fa fa-instagram"></i></a>
                            </div>
                        </div>
                    </div>
                    <div class="team-info">
                        <h3>Matthew Dix</h3>
                        <p>Graphic Design</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Gallery section start from here -->
    <section id="gallery">
        <div class="container">
            <div class="head">
                <h4>What we do</h4>
                <h2>some of our work</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
            </div>
        </div>
        <div class="gallery-main">
            <div class="gallery-item">
                <div class="gal-img">
                    <img src="images/gal1.png" alt="gal1" width="100%">
                    <div class="gal-overlay">
                        <div class="gal-info">
                            <i class="fa fa-picture-o"></i>
                            <h3>creatively designed</h3>
                            <p>Lorem ipsum dolor sit</p>
                        </div>
                    </div>
                </div>
                <div class="gal-img">
                    <img src="images/gal1.png" alt="gal1" width="100%">
                    <div class="gal-overlay">
                        <div class="gal-info">
                            <i class="fa fa-picture-o"></i>
                            <h3>creatively designed</h3>
                            <p>Lorem ipsum dolor sit</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="gallery-item">
                <div class="gal-img">
                    <img src="images/gal1.png" alt="gal1" width="100%">
                    <div class="gal-overlay">
                        <div class="gal-info">
                            <i class="fa fa-picture-o"></i>
                            <h3>creatively designed</h3>
                            <p>Lorem ipsum dolor sit</p>
                        </div>
                    </div>
                </div>
                <div class="gal-img">
                    <img src="images/gal1.png" alt="gal1" width="100%">
                    <div class="gal-overlay">
                        <div class="gal-info">
                            <i class="fa fa-picture-o"></i>
                            <h3>creatively designed</h3>
                            <p>Lorem ipsum dolor sit</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="gallery-item">
                <div class="gal-img">
                    <img src="images/gal5.png" alt="gal5" width="100%">
                    <div class="gal-overlay">
                        <div class="gal-info">
                            <i class="fa fa-picture-o"></i>
                            <h3>creatively designed</h3>
                            <p>Lorem ipsum dolor sit</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="gallery-item">
                <div class="gal-img">
                    <img src="images/gal1.png" alt="gal1" width="100%">
                    <div class="gal-overlay">
                        <div class="gal-info">
                            <i class="fa fa-picture-o"></i>
                            <h3>creatively designed</h3>
                            <p>Lorem ipsum dolor sit</p>
                        </div>
                    </div>
                </div>
                <div class="gal-img">
                    <img src="images/gal1.png" alt="gal1" width="100%">
                    <div class="gal-overlay">
                        <div class="gal-info">
                            <i class="fa fa-picture-o"></i>
                            <h3>creatively designed</h3>
                            <p>Lorem ipsum dolor sit</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer section start from here -->
    <footer>
        <div class="container">
            <div class="footer-main">
                <div class="footer-item-left">
                    <img src="images/footer-logo.png" alt="footer-logo">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. </p>
                    <h6><span>15k</span> followers</h6>
                    <h5>Follow us:
                        <a href="#"><i class="fa fa-facebook-f"></i></a>
                        <a href="#"><i class="fa fa-twitter"></i></a>
                        <a href="#"><i class="fa fa-instagram"></i></a>
                        <a href="#"><i class="fa fa-pinterest-p"></i></a>
                        <a href="#"><i class="fa fa-google-plus"></i></a>
                        <a href="#"><i class="fa fa-youtube"></i></a>
                        <a href="#"><i class="fa fa-dribbble"></i></a>
                        <a href="#"><i class="fa fa-tumblr"></i></a>
                    </h5>
                    <div class="form">
                        <form action="#" method="POST">
                            <input type="email" placeholder="Your Email...">
                            <button type="submit">subscribe</button>
                        </form>
                    </div>
                </div>
                <div class="footer-item-mid">
                    <h3>Blogs</h3>
                    <div class="blog-item">
                        <div class="blog-img">
                            <img src="images/blog1.png" alt="blog1">
                        </div>
                        <div class="blog-text">
                            <h4>Lorem ipsum dolor sit amet, 
                                consectetur adipiscing</h4>
                            <p>Jan 9, 2016</p>
                        </div>
                    </div>
                    <div class="blog-item">
                        <div class="blog-img">
                            <img src="images/blog1.png" alt="blog1">
                        </div>
                        <div class="blog-text">
                            <h4>Lorem ipsum dolor sit amet, 
                                consectetur adipiscing</h4>
                            <p>Jan 9, 2016</p>
                        </div>
                    </div>
                    <div class="blog-item">
                        <div class="blog-img">
                            <img src="images/blog1.png" alt="blog1">
                        </div>
                        <div class="blog-text">
                            <h4>Lorem ipsum dolor sit amet, 
                                consectetur adipiscing</h4>
                            <p>Jan 9, 2016</p>
                        </div>
                    </div>
                </div>
                <div class="footer-item-right">
                    <h3>Instagram</h3>
                    <div class="insta-main">
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                        <div class="insta-item">
                            <img src="images/insta.png" alt="insta">
                        </div>
                    </div>
                    <div class="view-btn">
                        <a href="#">view more photos</a>
                    </div>
                </div>
            </div>
            <div class="copyright">
                <p>© 2016 MoGo free PSD template by <span>Laaqiq</span></p>
            </div>
        </div>
    </footer>

</body>
</html>
