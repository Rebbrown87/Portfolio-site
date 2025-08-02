# Rebbrown87 Portfolio Website

## 🗒️ Overview
This is a responsive personal portfolio for showcasing my technical skills, educational background, interests, and projects. It is developed using semantic HTML5 and custom CSS with accessibility and clarity at its core.

## ⚙️ Technologies Used
- HTML5
- CSS3 (Custom styling and responsive design)
- GitHub Pages (for deployment)

## 📁 Project Structure
📁 root/ ├── index.html └── /assets └── rebbrown.jpg
## ✨ Features
- **Responsive Design**: Mobile-friendly layout using media queries and flexible containers.
- **Semantic HTML**: Ensures accessibility and SEO best practices.
- **Inline Form**: Simple contact form using `mailto` for quick communication.
- **CV Download**: Easily accessible resume link.
- **Project Showcase**: Highlights work with direct links.

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/rebbrown87/portfolio-site.git
2.	Open index.html in any modern browser.
3.	Customize sections to match updated personal details or projects.
4.	Deploy via GitHub Pages under repository settings.
🔭 Future Enhancements
•	Add preview images for each project.
•	Integrate backend functionality for the contact form.
•	Expand styling with external CSS and animation libraries.
•	Include site analytics and SEO meta tags.
📬 Contact
•	Email: rebbrownlikalani87@gmail.com

---

## 🧾 Clear Code Comments (Fully Commented HTML)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Meta settings for charset and mobile responsiveness -->
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rebbrown87</title>

  <!-- Internal CSS for styling -->
  <style>
    /* Base body styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    /* Intro section: name and profile photo */
    .intro {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #4b6cb7;
      color: white;
      padding: 20px;
      flex-wrap: wrap; /* Wrap on small screens */
    }

    /* Text block next to image */
    .intro-text {
      max-width: 70%;
    }

    /* Circular image container */
    .intro-img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      overflow: hidden;
      flex-shrink: 0;
    }

    /* Image inside the container */
    .intro-img img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    /* Section styling for each content block */
    section {
      padding: 20px;
      max-width: 800px;
      margin: auto;
      background: white;
      margin-bottom: 10px;
      border-radius: 5px;
    }

    /* Heading styles */
    h2 {
      color: #4b6cb7;
    }

    /* Bullet list padding */
    ul {
      padding-left: 20px;
    }

    /* Button style for CV download */
    .btn {
      display: inline-block;
      padding: 0.75em 1.5em;
      background: #4b6cb7;
      color: #fff;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 10px;
      font-size: 1rem;
      transition: background 0.3s ease;
      width: 100%;
      max-width: 250px;
      text-align: center;
    }

    /* Input and textarea styling */
    form input,
    form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    /* Mobile responsiveness */
    @media (max-width: 600px) {
      .intro-text {
        max-width: 100%;
        margin-bottom: 20px;
      }
      .btn {
        font-size: 0.875rem;
        padding: 0.5em 1em;
      }
    }
  </style>
</head>
<body>

  <!-- Profile intro with name and image -->
  <div class="intro">
    <div class="intro-text">
      <h1>Likalani Shadrack</h1>
      <p>Educator & Tech Enthusiast | Software Engineering Student | Quantum Computing Advocate</p>
    </div>
    <div class="intro-img">
      <img src="rebbrown.jpg" alt="Profile picture">
    </div>
  </div>

  <!-- About Me block -->
  <section>
    <h2>📝 About Me</h2>
    <p>I'm an educator with a strong foundation in physics, computing, design, and diagnostics. I bring over 3 years of experience in graphic design and branding, currently expanding into software engineering and tech at PLP Academy.</p>
  </section>

  <!-- Skills listing -->
  <section>
    <h2>💻 Programming Languages</h2>
    <ul>
      <li>HTML, CSS, JavaScript</li>
      <li>React, Node.js</li>
      <li>MongoDB</li>
      <li>Python (learning)</li>
    </ul>
  </section>

  <!-- Education background -->
  <section>
    <h2>🎓 Educational Background</h2>
    <p>Expertise in teaching physics, computer studies, networking, database management, and electronics. Studying software engineering via PLP Academy.</p>
    <!-- Button to download CV -->
    <a class="btn" href="https://drive.google.com/file/d/1DdqYqDR6VrEPjqR62-pdVw01QOyPzV71/view?usp=drive_link" target="_blank">Download My CV</a>
  </section>

  <!-- Interests list -->
  <section>
    <h2>💡 Interests</h2>
    <ul>
      <li>Quantum Computing & AI</li>
      <li>Cloud Platforms: AWS, Azure</li>
      <li>Python frameworks & Android Dev</li>
      <li>Technical education and collaboration</li>
    </ul>
  </section>

  <!-- Projects showcase -->
  <section>
    <h2>🛠️ Projects</h2>
    <ul>
      <li><strong>Online Exam App</strong>: Secure student/admin interface. <a href="#" target="_blank">View Project</a></li>
      <li><strong>Semantic HTML Site</strong>: Accessibility-focused page. <a href="#" target="_blank">View Project</a></li>
      <li><strong>Portfolio Website</strong>: Your journey and skills. <a href="#" target="_blank">Live Demo</a></li>
    </ul>
  </section>

  <!-- Contact form using mailto -->
  <section>
    <h2>📬 Contact Me</h2>
    <form action="mailto:rebbrownlikalani87@gmail.com" method="POST" enctype="text/plain">
      <input type="text" name="Name" placeholder="Likalani Shadrack" required />
      <input type="email" name="Email" placeholder="rebbrownlikalani87@gmail.com" required />
      <textarea name="Message" rows="5" placeholder="Your message..." required></textarea>
    </form>
  </section>

</body>
</html>





Here’s how you can deploy and host your portfolio on GitHub Pages, Rebbrown:
🚀 Step-by-Step Deployment Guide
1. Create a GitHub Repository
•	Go to github.com and sign in.
•	Click “New” to create a new repository.
•	Name it something like portfolio-site.
•	Choose Public.
•	Check "Add a README file" (optional, but helpful).
•	Click Create Repository.
2. Upload Your Code
•	On the repo page, click “Add file” > “Upload files”.
•	Upload your index.html file and image (e.g., rebbrown.jpg).
•	Click Commit changes to save.
3. Enable GitHub Pages
•	Go to the Settings tab of your repository.
•	Scroll down to the "Pages" section.
•	Under “Source,” choose Deploy from a branch.
•	Select the main branch and click Save.
•	GitHub will generate a link like:
•	https://rebbrown87.github.io/portfolio-site/
4. Verify Deployment
•	Wait a few seconds.
•	Visit the link to confirm your website is live.
🛠️ Tips for Success
•	Ensure your main file is named index.html.
•	Keep image and resource links relative (e.g., rebbrown.jpg).
•	Want a custom domain later? GitHub Pages supports it.
Want help writing a killer project description or setting up a favicon next?

