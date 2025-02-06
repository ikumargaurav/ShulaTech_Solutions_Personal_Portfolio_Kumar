# ShulaTech_Solutions_Personal_Portfolio_Kumar
🚀 Personal Portfolio Website | A responsive portfolio website built using HTML, CSS, and JavaScript. Designed to showcase projects, skills, and contact details.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kumar's Developer - Portfolio </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
        }


        body {
            background-color: rgb(0, 0, 33);
            color: white;
            font-family: 'poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 50px;
            background-color: black;
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: lightpink;
            font-size: 1.1rem;
        }

        .left {
            font-size: 1.75rem;
        }

        .firstsection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 100px 0;
        }

        .firstsection div> {
            width: 30%;
        }

        .leftsection {
            width: 70px 0;
            font-size: 3rem;
            margin: 34px;
        }

        .rightsection {
            width: 80%;
            margin: auto;



        }

        .purple {
            color: rgb(170, 107, 228);
        }

        #element {
            color: rgb(170, 107, 228);
        }

        .SecondSection {
            max-width: 80vw;
            margin: auto;
            height: 50vh;
        }

        main hr {
            border: 0;
            background-color: lightcyan;
            height: 1px;
            margin: 60px 84px;
        }

        .SecondSection h1 {
            font-size: 1.9rem;

        }

        .SecondSection ul {
            font-size: 1.6rem;
        }

        .ThirdSection {
            max-width: 80vw;
            margin: auto;
            height: 15vh;
        }

        .ThirdSection ul li {
            font-size: 1.6rem;
        }

        .FourthSection {
            max-width: 80vw;
            margin: auto;
            height: 30vh;
        }

        .FourthSection ul {
            font-size: 1.6rem;
        }

        img {
            height: 80%;
            width: 50%;
            margin: 30px;
        }

        .FifthSection ul li {
            font-size: 1.6rem;
        }

        .FifthSection {
            max-width: 80vw;
            margin: auto;
            height: 60vw;
        }

        footer div {
            font: 1.09rem;
            max-width: 80vw;
            margin: auto;
        }

        footer {
            background-color: #0e0e1a;
            display: flex;
            height: 120px;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        footer div ul li {
            justify-content: center;
        }

        .ZerothSection {
            max-width: 80vw;
            margin: auto;
            height: 15vh
        }

        .ZerothSection {
            font-size: 1.6rem;
        }
        .ThirdSection h1 ul li a :hover{
            font-size: 1.02rem;
            color: lavender;
        }
       
        
    </style>




</head>

<body>
    <header>
        <nav>
            <div class="left">Kumar's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="">Home</li></a>
                    <li><a href="">About</li></a>
                    <li><a href="">Services</li></a>
                    <li><a href="">Contact Me</li></a>

                </ul>




            </div>
        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi, My Name is <span class="purple">Kumar Gaurav</span>
                <div>and I am a passionate Web Developer</div>
                <span id="element"></span>

            </div>
            <div class="rightsection">
                <img src="kgi.png.jpeg" alt="" class="src">

            </div>
        </section>
        <hr>
        <section class="ZerothSection">
            <h1>Internships</h1>
            <ul>
                <li>Intern at ShulaTech Solutions as a Frontend Developer</li>
            </ul>
        </section>

        <section class="SecondSection">
            <h1>Skills</h1>
            <ul>
                <li1>Frontend Development</li1>
                <li>HTML</li>
                <li>CSS</li>
                <li>Javascript - Basic</li>
                <li>Python - Intermediate</li>
                <li>SEO</li>
                <li>Git</li>
                <li>Github</li>       
            
            </ul>
        </section>
        <section class="ThirdSection">
            <h1>Projects</h1>
            <ul>
                <li><a href="https://github.com/ikumargaurav/eye-controlled-mouse" style = "text-decoration: none; color: white;" >Eye Controlled Mouse (Using cv2,
                        Mediapipe, Pyautogui)</a></li>
                <li>Portfolio Website </li>
            </ul>


        </section>
        <Section class="FourthSection">
            <h1>Certifications/Awards</h1>
            <ul>
                <li>Certification of Participation - TECHNO GENESIS 2025</li>
                <li>Certification of Completion - Mastering Youtube Search Trends and SEO Strategies By Semrush Academy
                </li>
                <li>Google Badge - Introduction to GEN AI</li>
                <li>Certification of Completion - AWS APAC Solution Architecture Job Simulation by Forage</li>
            </ul>
        </Section>
        <section class="FifthSection">
            <h1>Academics</h1>
            <ul>
                <li>Currently Pursuing Bachelor's Degree in Computer Science at IIT PATNA</li>
                <li>(2023) First Division in Class 12 from BSEB,Patna</li>
                <li>(2021)First Division in Class 10 from BSEB,Patna</li>
            </ul>
        </section>
    </main>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'CS Student at IIT PATNA',],
            typeSpeed: 40,
        });
    </script>
    <footer>
        <div class="flex">
            <div class="footerFirst">Kumar Developer
            </div>
            <div class="footerSecond">
                <ul>
                    <li><a href="http://127.0.0.1:3000/kg.html">Home</a></li>
                    <li><a href="https://www.linkedin.com/in/kgiit/">LinkedIn</a></li>
                    <li><a href="https://github.com/ikumargaurav">Github</a></li>
                    <li>Contact Me</li>



                </ul>

            </div>
            <div class="footerThird">
                www.kumarportfolio.com | All rights reserved
            </div>
            <div class="footerFourth">
            </div>




        </div>




    </footer>

</body>

</html>
