# Ex01 Portfolio
## Date:11.04.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prema Latha S - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Prema Latha S</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internships">Internships</a></li>
                <li><a href="#achievements">Achievements</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <img src="prema.jpeg" alt="Prema Latha S" class="profile-pic">
        <p>I am a passionate and highly motivated Artificial Intelligence and Data Science student with a strong foundation in programming, web technologies, and problem-solving. I enjoy tackling new challenges and leveraging my skills in data analysis, machine learning, software development, and web technologies to create impactful solutions.</p>
        <p><strong>Resume:</strong> <a href="prema_resume1.pdf" target="_blank">Download Here</a></p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>Saveetha Engineering College</strong></p>
        <p>B.Tech in Artificial Intelligence and Data Science (2022 - 2026)</p>
        <p>CGPA: 8.7</p>
        <p><strong>St.Paul's Matriculation Higher Secondary School</strong></p>
        <p>HSC - 93.3% (2022)</p>
        <p>SSLC - 82% (2020)</p>
    </section>

    <section id="skills">
        <h2>Technical Skills</h2>
        <ul>
            <p>Machine Learning & Data Analysis</p>
            <p>Version Control (Git & GitHub)</p>
            <p>Web Development (HTML, CSS, JavaScript, Node.js)</p>
            <p>Programming Languages: Python, C, Java, SQL</p>
            <p>Tools & Libraries: TensorFlow, OpenCV</p>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>🎵 Music Player</h3>
            <p>Developed a web-based music player using HTML, CSS, JavaScript, and Node.js, enabling smooth audio playback and playlist management.</p>
        </div>
        <div class="project">
            <h3>📸 Cam-Detection</h3>
            <p>Built a real-time hidden spy camera detection system using computer vision techniques like SSD and image processing.</p>
        </div>
        <div class="project">
            <h3>🍔 Food Delivery Prediction</h3>
            <p>Designed a Machine Learning model to predict food delivery time based on distance, traffic, and order details. Used regression algorithms to improve accuracy.</p>
        </div>
    </section>

    <section id="internships">
        <h2>Internships</h2>
        <div class="internship">
            <h3>Edify Techno Solutions - Pet Store Development</h3>
            <p>Developed and designed a pet store website using HTML, CSS, and JavaScript, focusing on interactivity and user experience.</p>
        </div>
        <div class="internship">
            <h3>Arjun Vision Technologies - Music Player</h3>
            <p>Created a web-based music player with Node.js, HTML, and JavaScript, featuring audio playback controls and playlist management.</p>
        </div>
    </section>

    <section id="achievements">
        <h2>Achievements</h2>
        <ul>
            <p>🏆 Amazon AIML Challenge: Participated in Amazon's Machine Learning challenge, applying ML models to solve real-life business problems.</p>
            <p>📊 IBM Z Datathon 2024: Engaged in a data science competition, leveraging IBM Z technology to analyze datasets and develop solutions.</p>
            <p>📜 Certifications:
                <ul>
                    <p>Deep Learning TensorFlow for AI, ML, DL, NLP, CNN</p>
                    <p>Interactivity with JavaScript (Coursera)</p>
                    <p>AI with Python (Coursera)</p>
                    <p>Internet of Things (NPTEL)</p>
                    <p>OpenCV & Image Processing (Infosys)</p>
                </ul>
              </p>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:s.premalatha260804@gmail.com@gmail.com">s.premalatha260804@gmail.com@gmail.com</a></p>
        <p>Phone: <a href="tel:+918124694321">8124694321</a></p>
        <p><strong>GitHub:</strong> <a href="https://github.com/premalathasureshbabu" target="_blank">GitHub Profile</a></p>
        <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/premalathasureshbabu/" target="_blank">LinkedIn Profile</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Prema Latha S. All rights reserved.</p>
    </footer>
</body>
</html>
```
Style.css
```
/* General Styling */
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #1e1e2f;
  color: white;
  padding: 20px 0;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  letter-spacing: 1px;
  font-weight: 600;
}

nav ul {
  list-style-type: none;
  padding: 0;
  margin: 20px 0 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 1rem;
  text-transform: uppercase;
  font-weight: 500;
}

nav ul li a:hover {
  color: #ff6600;
}

/* Section Styling */
section {
  padding: 60px 20px;
  margin: 0 auto;
  max-width: 1000px;
}

/* About Section */
#about {
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  text-align: center;
}

#about .profile-pic {
  border-radius: 50%;
  width: 160px;
  height: 160px;
  object-fit: cover;
  margin-top: 20px;
}

#about h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  font-weight: 600;
  color: #333;
}

#about p {
  font-size: 1.1rem;
  color: #555;
  margin: 20px 0;
}

#about a {
  color: #1e1e2f;
  font-weight: 600;
}

#about a:hover {
  color: #ff6600;
}

/* Education Section */
#education {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#education p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

/* Skills Section */
#skills {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#skills p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

/* Projects Section */
#projects {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.project {
  background-color: #f9f9f9;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.project h3 {
  font-size: 1.6rem;
  color: #333;
  margin-bottom: 10px;
  font-weight: 600;
}

.project p {
  font-size: 1rem;
  color: #666;
}

/* Internships Section */
#internships {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.internship {
  background-color: #f9f9f9;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.internship h3 {
  font-size: 1.6rem;
  color: #333;
  margin-bottom: 10px;
  font-weight: 600;
}

.internship p {
  font-size: 1rem;
  color: #666;
}

/* Achievements Section */
#achievements {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#achievements p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

#achievements ul {
  list-style-type: none;
  padding: 0;
}

#achievements ul p {
  margin: 10px 0;
  font-size: 1.1rem;
  color: #555;
}

/* Contact Section */
#contact {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#contact p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

#contact a {
  color: #ff6600;
  font-weight: 600;
}

#contact a:hover {
  color: #1e1e2f;
}

/* Footer */
footer {
  background-color: #1e1e2f;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}

footer p {
  margin: 0;
  font-size: 1rem;
}

/* Responsive Design */
@media screen and (max-width: 768px) {
  header h1 {
      font-size: 2rem;
  }

  nav ul li {
      display: block;
      margin: 10px 0;
  }

  nav ul li a {
      font-size: 1rem;
  }

  section {
      padding: 40px 20px;
  }
}
```


## OUTPUT
![image](https://github.com/user-attachments/assets/4b5b733f-5bad-4522-b4e7-c9ab5825c1b7)

![image](https://github.com/user-attachments/assets/eb2f665e-392d-41f9-b9ae-4b584c218128)

![image](https://github.com/user-attachments/assets/fdc936e3-d8b9-4209-aa2e-a5739ddf9d30)

![image](https://github.com/user-attachments/assets/95b0baa5-6ccf-4a96-bc33-4af8d1a598b4)

![image](https://github.com/user-attachments/assets/057f1623-c6f0-485c-b17d-a9c92f639262)

![image](https://github.com/user-attachments/assets/8d0d95ff-8305-49b0-bd1e-188840c0e5c8)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
