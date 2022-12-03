<head>
    <link rel='stylesheet' href='https://cdn-uicons.flaticon.com/uicons-brands/css/uicons-brands.css'>  
    <style>
        @import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css");
        * {
            font-family: helvetica,sans-serif;
        }
        .hero{
            padding:0.67rem 0.8777rem;
            display: flex;
            flex-direction: column;
            background-color: #ebe4e4;
            color: #292727;
            position: relative;
            min-height: 300px;
        }
        .content{
            z-index: 100;
        }
        .float-img{
            position : absolute;
            height : 100%;
            right : 0%;
            top : 0%;
            z-index: 1;
            opacity: 0.6;
        }
        .header-title{
            font-weight : bold;
            border-bottom: none;
        }
        .p-language{
            display: block;
        }
        .language-container{
            display: flex;
            flex-wrap: wrap;
            flex-direction: row;
        }
        .hero-footer{
            position : absolute;
            bottom : 0;
            right : 0;
            display: flex;
            flex-direction: column;
            justify-content:flex-end;
            z-index: 1;
            padding: 0.56rem 0.87rem;
        }
        .language-container,
        .icons-container, .f-container{
            font-size:2.3rem;
        }
        .icons-container{
            display:flex;
            flex:row;
            justify-content: space-around;
            align-items: center;
        }
        .icons, .language-icon{
            margin-inline:0.55rem;
        }
        .icons{
            position: relative;
            min-height:1px;
            display: inline-block;
            text-decoration:none;
            color:inherit;
            pointer-events : cursor;
            transtion: all 1s ease-in;
        }
        .icons::before{
            content: "";
            position: absolute;
            background-color:#141313;
            width: 0%;
            height:3%;
            border-radius: 25rem;
            bottom:20%; 
            transtion: all 1s ease-in-out;
        }
        .icons:hover{
            color:white;
            transtion: all 1s ease-in-out;
        }
        .icons:hover::before{
            width:100%;
            transtion: all 1s ease-in-out;
        }
        .fi-brands-liferay::before{
            content: url('./liferay-icon.svg');
            display: inline-block;
            width: 0.5em;
            height: 0.5em;
        }
        .fi-brands-springboot::before{
            content: url('./springboot.svg');
            display: inline-block;
            width: 1em;
            height: 1em;
        }
        .fi-brands-tailwind::before{
            content: url('./tailwind-css.svg');
            display: inline-block;
            width: 1em;
            height: 1em;
        }
        .fi-brands-nextjs::before{
            content: url('./nextjs-fill.svg');
            display: inline-block;
            width: 1em;
            height: 1em;
        }
    </style>
</head>
<div class = "hero">
    <img src = "./coding.jpg" class = "float-img"/>
    <main class = "content">
        <h1 class = "header-title">HI, I AM JOHN DANIEL TEJERO.</h1>
        <h4 class = "header-title" style = "margin-bottom:2rem;">BACHELOR OF SCIENCE IN INFORMATION TECHNOLOGY</h4>
        <section class = "p-language">
            <h4 class = "header-title">
                Languages Known
            </h4>
            <div class = "language-container">
                <span class = "language-icon">
                    <i class="fa-brands fa-java"></i>
                </span>
                <span class = "language-icon">
                    <i class="fa-brands fa-js"></i>
                </span>
                <span class = "language-icon">
                    <i class="fa-brands fa-php"></i>
                </span>
                <span class = "language-icon">
                    <i class="fi fi-brands-typescript"></i>
                </span>
                <span class = "language-icon">
                    <i class="fa-brands fa-html5"></i>
                </span>
                <span class = "language-icon">
                    <i class="fa-brands fa-css3-alt"></i>
                </span>
                <span class = "language-icon">
                    <i class="fi fi-brands-mysql"></i>
                </span>
            </div>
        </section>
        <section class = "frameworks" style = "height:10rem;">
            <h4 class = "header-title">
                Frameworks and Tools
            </h4>
            <div class = "f-container">
                <span class = "f-icon">
                    <i class="fa-brands fa-react"></i>
                </span>
                <span class = "f-icon">
                    <i class="fa-brands fa-angular"></i>
                </span>
                <span class = "f-icon">
                    <i class="fa-brands fa-bootstrap"></i>
                </span>
                <span class = "f-icon">
                    <i class="fa-brands fa-laravel"></i>
                </span>
                <span class ="f-icon">
                    <i class="fi fi-brands-node-js"></i>
                </span>
                <span class = "f-icon">
                    <i class = "fi fi-brands-springboot"></i>
                </span>
                <span class = "f-icon">
                    <i class = "fi fi-brands-nextjs"></i>
                </span>
                <span class = "f-icon">
                    <i class = "fi fi-brands-tailwind"></i>
                </span>
            </div>
        </section>
    </main>
    <footer class = "hero-footer">
            <section class = "icons-container">
                <a class = "icons" href  = "https://www.linkedin.com/in/john-daniel-tejero-5a5b13225/" target="blank">
                    <i class="fa-brands fa-linkedin"></i>
                </a>
                <a class = "icons" href = "https://twitter.com/Imperobous" target = "blank">
                    <i class="fa-brands fa-twitter"></i>
                </a>
                <a class = "icons" href = "https://www.discordapp.com/users/747707954572296215" target = "blank">
                    <i class = "fa-brands fa-discord"></i>
                </a>
            </section>
    </footer>
</div>
<br>
 
I am a second year at Baliuag University, undertaking Bachelor of Sicence in Information Technology specialization in web development. I am interested in web development especially in backend development.

<hr>

## How to reach me?
for any inquires, please contact me: 
- via email `johndanieltejero23@gmail.com`
- via whatsapp `+63 939 641 6091`
- or refer to the links given in the hero banner
- aaaaa
<hr>

## I Am Currently Learning:
- Tailwind CSS
- Angular 
- NextJs
- TypeScript
- PHP
- Liferay
<hr>

## Stack That I Am Familiar With
- Java
- Spring Boot
- Laravel
- PHP
- JavaScript
- TypeScript
- ReactJs



<!---
JohnDanielTejero/JohnDanielTejero is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->