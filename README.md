<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  Thakhani Tshimbudzi | IT Portfolio
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>👨‍💻 Thakhani Tshimbudzi</h1>
    <p>Certified IT Field Technician | Strategic Tech Thinker | Ethical Innovator</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I’m a certified IT Field Technician with 5+ years of experience in technical support, hardware/software troubleshooting, and network configuration across banking, insurance, and education sectors. I’m passionate about ethical tech, strategic planning, and transitioning into consultancy.
    </p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Network Configuration (Cisco, VLANs, SSH)</li>
      <li>System Administration (Active Directory, Fortinet)</li>
      <li>Remote Support & Diagnostics</li>
      <li>Cloud Fundamentals (Azure)</li>
      <li>End-User Training & Documentation</li>
      <li>Strategic Risk Planning & Ethical Tech</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Smart Home Design Blueprint:</strong> IoT integration with ethical tech principles</li>
      <li><strong>Mining Insights Booklet:</strong> Strategic risk planning for mining sector</li>
      <li><strong>IT Technician Showcase:</strong> Visual portfolio of support tools and certifications</li>
    </ul>
  </section>

  <section id="goals">
    <h2>Goals</h2>
    <p><strong>Short-Term:</strong> Secure an entry-level IT role and grow visibility in professional networks</p>
    <p><strong>Long-Term:</strong> Transition into consultancy focused on ethical tech, strategic planning, and risk management</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email:tshimbudzithakhani@gmail.com</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/thakhani-tshimbudzi.">linkedin.com/in/thakhani-tshimbudzi</a></p>
    <p>Location: Polokwane, South Africa (open to remote and SA-wide opportunities)</p>
  </section>

  <footer>
    <p>© 2025 Thakhani Tshimbudzi</p>
  </footer>
</body>
</html>
/* Base Styles */
body {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background-color: #f5f5f5;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
  padding: 2rem 0;
}

/* Header */
header {
  text-align: center;
  padding: 2rem 1rem;
  background-color: #004080;
  color: white;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

header p {
  font-size: 1.2rem;
}

/* Navigation */
nav {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1rem;
  background-color: #003366;
  padding: 1rem;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

/* Sections */
section {
  margin: 2rem 0;
  padding: 1rem;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Grid Layout for Projects or Skills */
.grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.grid-item {
  flex: 1 1 calc(33.333% - 1rem);
  background-color: #e6f0ff;
  padding: 1rem;
  border-radius: 6px;
}

/* Footer */
footer {
  text-align: center;
  padding: 1rem;
  background-color: #004080;
  color: white;
}

/* 📱 Responsive Breakpoints */
@media (max-width: 1024px) {
  .grid-item {
    flex: 1 1 calc(50% - 1rem);
  }

  header h1 {
    font-size: 2rem;
  }
}

@media (max-width: 768px) {
  nav {
    flex-direction: column;
    align-items: center;
  }

  .grid-item {
    flex: 1 1 100%;
  }

  header h1 {
    font-size: 1.8rem;
  }

  header p {
    font-size: 1rem;
  }
}

@media (max-width: 480px) {
  body {
    font-size: 0.9rem;
  }

  header h1 {
    font-size: 1.5rem;
  }

  .container {
    width: 95%;
  }
}
