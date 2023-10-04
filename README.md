# oibsip_taskno.2
portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Portfolio</title>
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <p>Web Developer</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>I'm a passionate web developer with experience in HTML, CSS, and JavaScript.</p>
    </section>

    <section class="samples">
        <h2>Portfolio Samples</h2>
        <div class="sample">
            <img src="sample1.jpg" alt="Sample 1">
            <p>Sample Project 1</p>
        </div>
        <div class="sample">
            <img src="sample2.jpg" alt="Sample 2">
            <p>Sample Project 2</p>
        </div>
    </section>

    <section class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
            <li>Responsive Design</li>
        </ul>
    </section>

    <section class="resume">
        <h2>Resume</h2>
        <a href="resume.pdf" download>Download Resume</a>
    </section>

    <section class="contact">
        <h2>Contact Information</h2>
        <p>Email: john@example.com</p>
        <p>Phone: (123) 456-7890</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/johndoe" target="_blank">John Doe</a></p>
    </section>
</body>
</html>



/* Reset some default styles */
body, h1, h2, p, ul, li, a {
    margin: 0;
    padding: 0;
}

/* Apply a background color and basic styles to the header */
header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

/* Style the sections */
section {
    margin: 20px;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

/* Style the portfolio samples */
.samples {
    display: flex;
    justify-content: space-around;
}

.sample {
    text-align: center;
}

/* Style the skills list */
.skills ul {
    list-style: none;
}

.skills li {
    margin-bottom: 10px;
}

/* Style the resume link */
.resume a {
    display: inline-block;
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.resume a:hover {
    background-color: #555;
}

/* Style the contact information */
.contact p {
    margin: 5px 0;
}

.contact a {
    color: #0077b5;
    text-decoration: none;
}

.contact a:hover {
    text-decoration: underline;
}
