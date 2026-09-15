# Ex01 Portfolio
## Date:20/07/2026

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
about.jsx
```
import "../styles/About.css";

function About() {
  return (
    <section className="about" id="about">

      <h2 className="section-title">About Me</h2>

      <div className="about-container">

        <div className="about-content">

          <h3>Who am I?</h3>

          <p>
            Hello! I'm <span>M.Sreyas</span>, a Computer Science Engineering
            student with a passion for creating modern websites and learning
            cutting-edge technologies.

            <br /><br />

            I enjoy developing responsive web applications, exploring Artificial
            Intelligence, Machine Learning, and solving real-world problems
            through programming.

            <br /><br />

            My goal is to become a Full Stack Developer and AI Engineer while
            continuously improving my technical and problem-solving skills.
          </p>

        </div>

      </div>

    </section>
  );
}

export default About;
```
contact.jsx
```
import "../styles/Contact.css";

function Contact() {
  return (
    <section className="contact" id="contact">

      <h2 className="section-title">Contact Me</h2>

      <div className="contact-container">

        {/* Contact Information */}
        <div className="contact-info">

          <h3>Let's Connect!</h3>

          <p>
            I'm always interested in new opportunities, collaborations,
            and exciting projects. Feel free to reach out!
          </p>

          <div className="info">
            <strong>Email:</strong>
            <p>sreyas0113@gmail.com</p>
          </div>

          <div className="info">
            <strong>Phone:</strong>
            <p>+91 7395852654</p>
          </div>

          <div className="info">
            <strong>Location:</strong>
            <p>Tamil Nadu, India</p>
          </div>

          <div className="social-links">

            <a href="https://github.com/" target="_blank" rel="noreferrer">
              GitHub
            </a>

            <a href="https://linkedin.com/" target="_blank" rel="noreferrer">
              LinkedIn
            </a>

            <a href="https://instagram.com/" target="_blank" rel="noreferrer">
              Instagram
            </a>

          </div>

          <button className="resume-btn">
            Download Resume
          </button>

        </div>

        {/* Contact Form */}
        <div className="contact-form">

          <form>

            <input
              type="text"
              placeholder="Your Name"
            />

            <input
              type="email"
              placeholder="Your Email"
            />

            <textarea
              rows="6"
              placeholder="Write your message..."
            ></textarea>

            <button type="submit">
              Send Message
            </button>

          </form>

        </div>

      </div>

    </section>
  );
}

export default Contact;
```
hero.jsx
```
import "../styles/Hero.css";
import profile from "../images/Profile.png";

function Hero() {

  return (

<section className="hero" id="home">

<div className="hero-text">

<h3>Hello, I'm</h3>

<h1>M.Sreyas</h1>

<h2>Computer Science Student</h2>

<p>

Passionate about Web Development, Artificial Intelligence,
Machine Learning and Software Development.

</p>

<a href="#contact">

<button>Contact Me</button>

</a>

</div>


<div className="hero-image">
  <img
    src="/profile.png.png"
    alt="Profile"
    className="profile-img"
  />


</div>

</section>

  );
}

export default Hero;
```
projects.jsx
```
import "../styles/Projects.css";

function Projects() {
  const projects = [
    {
      title: "Portfolio Website",
      description:
        "A modern and responsive personal portfolio built using React and CSS with smooth scrolling and interactive UI.",
      tech: "React • CSS • JavaScript"
    },
    {
      title: "Student Management System",
      description:
        "A Java application that manages student records, attendance, and academic details using object-oriented programming.",
      tech: "Java • MySQL"
    },
    {
      title: "Customer Segmentation",
      description:
        "Machine Learning project that groups customers into different categories using the K-Means clustering algorithm.",
      tech: "Python • Scikit-Learn • Pandas"
    }
  ];

  return (
    <section className="projects" id="projects">

      <h2 className="section-title">
        My Projects
      </h2>

      <div className="projects-container">

        {projects.map((project, index) => (

          <div className="project-card" key={index}>

            <h3>{project.title}</h3>

            <p>{project.description}</p>

            <span>{project.tech}</span>

            <button>View Project</button>

          </div>

        ))}

      </div>

    </section>
  );
}

export default Projects;
```
skills.jsx
```
import "../styles/Skills.css";

function Skills() {

  const skills = [
    "HTML",
    "CSS",
    "JavaScript",
    "React",
    "Python",
    "Java",
    "C",
    "Machine Learning",
    "Artificial Intelligence",
    "Git",
    "GitHub",
    "SQL"
  ];

  return (

    <section className="skills" id="skills">

      <h2 className="section-title">
        My Skills
      </h2>

      <div className="skills-grid">

        {skills.map((skill, index) => (

          <div className="skill-card" key={index}>

            {skill}

          </div>

        ))}

      </div>

    </section>

  );
}

export default Skills;
```




<img width="1902" height="1146" alt="image" src="https://github.com/user-attachments/assets/66edbbe9-10f0-49a2-9e8c-13d73c54aece" />
<img width="1897" height="1101" alt="image" src="https://github.com/user-attachments/assets/848d3791-ef98-42b3-8dbf-df04ea603010" />
<img width="1915" height="1083" alt="image" src="https://github.com/user-attachments/assets/a4ec79e4-9646-4f6b-aeed-94da2b2dd81c" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
