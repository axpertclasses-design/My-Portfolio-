# My-Portfolio-
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Himanshu Kumar</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to My Portfolio</h2>
        <p>Web Developer | Student</p>
        <button onclick="sayHello()">Say Hello</button>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is Himanshu Kumar. I am learning HTML, CSS and JavaScript.</p>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>C Programming</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>

        <div class="card">
            <h3>Digital Clock</h3>
            <p>Simple digital clock using JavaScript.</p>
        </div>

        <div class="card">
            <h3>To-Do List</h3>
            <p>Task management application.</p>
        </div>

        <div class="card">
            <h3>Portfolio Website</h3>
            <p>Personal portfolio website.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: youremail@gmail.com</p>
        <p>Phone: 7858090061</p>
    </section>

    <footer>
        <p>© 2026 Himanshu Kumar. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>
body{
    margin:0;
    font-family:Arial,sans-serif;
    text-align:center;
    background:#d8b58a;
}

header{
    background:blue;
    color:white;
    padding:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:10px;
}

section{
    padding:50px 20px;
}

.card{
    width:250px;
    margin:15px auto;
    border:1px solid red;
    border-radius:10px;
    padding:15px;
}

button{
    padding:10px 20px;
    cursor:pointer;
}

footer{
    background:blue;
    color:white;
    padding:15px;
}
function sayHello() {
    alert("Hello! Welcome to my portfolio.");
}
