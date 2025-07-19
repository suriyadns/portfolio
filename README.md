S. Suriya's Personal Portfolio
Welcome to the GitHub repository for S. Suriya's personal portfolio website! This site showcases my academic journey, technical skills, achievements, and projects as a B.Tech Computer Science and Business Systems student.

About Me
I'm S. Suriya, a second-year undergraduate student at Rajalakshmi Engineering College. I'm deeply passionate about leveraging technology to solve real-world challenges, with a particular focus on Artificial Intelligence. My journey involves continuously exploring new technologies, upskilling, and applying my knowledge practically.

Features
Interactive Navigation: Easily browse through sections like About Me, Education, Skills, and Achievements.

Direct Contact Form: Reach out directly via the "Get In Touch" section, powered by FormSubmit.co, ensuring your message goes straight to my inbox.

Integrated Resume: View my professional resume directly on the website, with an option to download it.

Social Media Links: Quick access to my GitHub, LinkedIn, and Instagram profiles.

Responsive Design: Optimized for seamless viewing across desktops, tablets, and mobile devices.

Live Demo
Explore the live version of my portfolio here:

🌐 suriya777.netlify.app

Getting Started (Local Setup)
To run this project locally, follow these simple steps:

Clone the repository:

Bash

git clone https://github.com/suriyadns/portfolio.git
Navigate to the project directory:

Bash

cd portfolio
Open index.html:
Simply open the index.html file in your preferred web browser.

Customization
Update Content: Modify the text in the index.html file to reflect your latest experiences, skills, and projects.

Replace Images/Assets: If you add any images or other assets, ensure their paths are correctly updated in the HTML and CSS.

Resume Download: Place your resume PDF file (e.g., s_suriya_resume.pdf) in the same directory as index.html and update the href in the "Download Resume" button:

HTML

<a href="s_suriya_resume.pdf" download="S.Suriya_Resume.pdf">
    <button>Download Resume</button>
</a>
FormSubmit.co Email: Ensure the action attribute in the contact forms is set to your correct email:

HTML

<form action="https://formsubmit.co/dnssuriya@gmail.com" method="POST">
And remember to verify your email with FormSubmit.co after the first submission from your live site.

FormSubmit.co Redirect URL: Update the _next hidden input with your deployed portfolio URL for the redirect after submission:

HTML

<input type="hidden" name="_next" value="https://suriya777.netlify.app/#intro-section">
Contact
Feel free to connect with me through my portfolio's contact form or directly via the links below:

Email: dnssuriya@gmail.com

LinkedIn: Suriya S

GitHub: suriyadns

Instagram: suriya.__777

