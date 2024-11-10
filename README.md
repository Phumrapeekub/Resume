<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Resume</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        background-color: #f4f4f4;
    }
    .container {
        display: flex;
        width: 800px;
        background-color: white;
        border-radius: 8px;
        overflow: hidden;
    }
    .left {
        width: 30%;
        background-color: #2b2b2b;
        color: white;
        padding: 20px;
        text-align: center;
    }
    .left img {
        width: 100px;
        height: 100px;
        border-radius: 50%;
        margin-bottom: 20px;
    }
    .left h2 {
        background-color: #3a3a3a;
        padding: 10px;
        border-radius: 5px;
    }
    .contact-info, .education, .skills {
        margin: 20px 0;
        text-align: left;
    }
    .contact-info p, .education p, .skills p {
        margin: 5px 0;
        font-size: 14px;
    }
    .right {
        width: 70%;
        padding: 20px;
    }
    .right h1 {
        margin: 0;
    }
    .right .about, .work-experience, .hobbies {
        margin: 20px 0;
    }
    .right h2 {
        margin-top: 0;
        font-size: 18px;
    }
    .about p, .work-experience p, .hobbies p {
        font-size: 14px;
    }
</style>
</head>
<body>
    <div class="container">
        <div class="left">
            <img src="pooh.jfif" alt="Profile Picture">
            <h2>Contact Me</h2>
            <div class="contact-info">
                <p>📞 +66-0621481149</p>
                <p>✉️ 66025773@up.ac.th</p>
                <p>🔗 <a href="https://github.com/Phumrapeekub" style="color: white;">github.com/Phumrapeekub</a></p>
                <p>📍 143 Moo.1 Maejedimai Wiangpapao, Chiangrai 57260</p>
            </div>
            <h2>Education</h2>
            <div class="education">
                <p>Bachelor's Degree in University of Phayao</p>
            </div>
            <h2>Skills</h2>
            <div class="skills">
                <p>Beginner in Java, Python, C</p>
            </div>
        </div>
        <div class="right">
            <h1>Phumrapee Kantiya</h1>
            <p style="font-size: 16px; color: #555;">Computer Science</p>
            <div class="about">
                <h2>About Me</h2>
                <p><strong>Name:</strong> Phumrapee Kantiya</p>
                <p><strong>Nickname:</strong> Pooh</p>
                <p><strong>Date of Birth:</strong> 23/04/2548</p>
                <p><strong>Nationality:</strong> Thai</p>
                <p><strong>Address:</strong> 143 Moo.1 Maejedimai, Wiangpapao, Chiangrai 57260</p>
            </div>
            <div class="work-experience">
                <h2>Work Experience</h2>
                <p>• Developed an exercise challenge app.</p>
            </div>
            <div class="hobbies">
                <h2>Hobbies</h2>
                <p>• Listening to music</p>
                <p>• Playing games</p>
                <p>• Watching movies</p>
            </div>
        </div>
    </div>
</body>
</html>