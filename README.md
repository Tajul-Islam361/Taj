<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" type="text/css" href="style.css" />
    <title>Home- Jawad</title>
</head>

<body>
    <nav class="navbar">
        <div class="logo">
            <h1>Welcome</h1>
        </div>

        <div class="nav-menu">
            <ul>
                <li><a href="#">About</a></li>

                <li><a href="#Skill">Skills</a></li>

                <li><a href="#Project">Project</a></li>

                <li><a href="#Contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <section class="homepage">
        <div class="pic">
            <img src="Assets/DP.jpg" />
        </div>
        <div class="text">
            <p>
                <span>Hello, </span><br />My Name is <span>MD Jawadul Hasan</span>.I like to solve programming problems and develop web and mobile apps. I am also interested in Machine Learning and data science. And I am looking forward to working as
                a software engineer to manifest my skills and enthusiasms.
            </p>
        </div>
    </section>

    <section class="Skillcls" id="Skill">
        <div class="Skilltxt">
            <h1>Skills</h1>
        </div>

        <div class="skill1">
            <p>C++</p>
            <div class="container">
                <div class="skills cpp">90%</div>
            </div>

            <p>C#</p>
            <div class="container">
                <div class="skills csharp">85%</div>
            </div>

            <p>Wordpress</p>
            <div class="container">
                <div class="skills wp">55%</div>
            </div>

            <p>PHP</p>
            <div class="container">
                <div class="skills php">80%</div>
            </div>
        </div>
        <div class="skill2">
            <p>HTML</p>
            <div class="container">
                <div class="skills html">90%</div>
            </div>

            <p>CSS</p>
            <div class="container">
                <div class="skills css">70%</div>
            </div>

            <p>JavaScript</p>
            <div class="container">
                <div class="skills js">65%</div>
            </div>

            <p>Python</p>
            <div class="container">
                <div class="skills py">60%</div>
            </div>
        </div>
    </section>

    <section class="prcontainer" id="Project">
        <div class="Prtxt">
            <h1>Projects</h1>
        </div>
        <div class="project">
            <div class="pr">
                <a href="https://github.com/mdjawadulhasan/wtproject21"><img src="./Assets/P2.png" /></a>
                <div class="footer">
                    <p>
                        A web app built by HTML, CSS, PHP, JS, Click on the image to view the project
                    </p>
                </div>
            </div>

            <div class="pr">
                <a href="https://github.com/mdjawadulhasan/Health-Management-Desktop-App"><img src="./Assets/P1.png" /></a>
                <div class="footer">
                    <p>
                        A Desktop app built by C# .Net Framework, Click on the image to view the project
                    </p>
                </div>
            </div>

            <div class="pr">
                <a href="https://github.com/mdjawadulhasan/AIUB-PORTAL-CONSOLE-APPLICATION-"><img src="./Assets/P3.png" /></a>
                <div class="footer">
                    <p>
                        A Console Desktop app built by Java, Click on the image to view the project
                    </p>
                </div>
            </div>

            <div class="pr">
                <a href="https://github.com/mdjawadulhasan/Personal-Health-App-UML-Project"><img src="./Assets/P4.jpg" /></a>
                <div class="footer">
                    <p>
                        A UML Project built by Edrawmax, Click on the image to view the project
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section class="formcontainer" id="Contact">
        <div class="text5">
            <center>
                <h1>
                    <span>Contact</span>
                </h1>
            </center>
        </div>

        <div class="form">
            <p> Nname:</p>
            <input type="text" name="" placeholder="Your Name" /><br />
            <p> Email:</p>
            <input type="email" name="" placeholder="Your Email" /><br />
            <p> Your Message :</p>
            <textarea>Hello Taj,....</textarea><br />
            <button>Submit</button>
        </div>
    </section>

    <footer class="footerl">
        <center>
            <div class="fnm">
                <h3><span>TAJ</span></h3>
                <p>&copy; 2021 All rights reserved.</p>
            </div>
        </center>
    </footer>
</body>

</html>
