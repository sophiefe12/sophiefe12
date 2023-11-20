html_template = f"""
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sophie's GitHub Profile</title>
</head>
<body>

    <header>
        <h1>Sophie </h1>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! 👋 I'm Sophie, a passionate Computer Science and Business Technology Master student. I am passionate about the technology industry hoping to work in the fields. With a background in Business I enjoy learning new technologies, solving complex problems, and working in teams.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>

        <h3>Programming Languages</h3>
        <ul>
            <li>Python, Java Script, Java, SQL</li>
        </ul>

        <h3>Database</h3>
        <ul>
            <li>MySQl</li>
        </ul>

        <h3>Tools & Technologies</h3>
        <ul>
            <li>"Git", "Docker", "VS Code"</li>
        </ul>

        <h3>Soft Skills</h3>
        <ul>
            <li>Communication, teamwork, problem-solving, etc.</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>

        <article>
            <h3>my_first_repo</h3>
            <p><strong>Description:</strong> Brief description of the project.</p>
            <p><strong>Technologies Used:</strong> List of technologies or languages used.</p>
            <p><strong>Link:</strong> <a href="{Link to the GitHub repository or deployed project}">{Link to the GitHub repository or deployed project}</a></p>
        </article>

    </section>

    <section id="achievements">
        <h2>Achievements</h2>
        <ul>
            <li>{Highlight any notable accomplishments}</li>
        </ul>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>Degree:</strong> Computer Science and Business Technology</p>
        <p><strong>Degree:</strong> Business Administration</p>

    </section>

</body>
</html>
"""

print(html_template)
