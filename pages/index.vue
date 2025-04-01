<template>
  <div class="container">
    <!-- Header -->
    <header>
      <div class="profile">
        <img src="https://via.placeholder.com/150" alt="Ciprian Stavovei" class="profile-pic">
        <h1>Ciprian Stavovei</h1>
        <p class="tagline">Senior Drupal Developer & Technical Lead</p>
      </div>
    </header>

    <!-- Main Content -->
    <main>
      <section class="about">
        <h2>About My Services</h2>
        <p>
          I am an experienced Drupal Developer and Technical Lead with over 8 years of expertise in building scalable, high-performance web applications. Specializing in Drupal architecture, decoupled solutions, and multi-platform integrations, I deliver secure, efficient, and innovative digital solutions tailored to your business needs. Whether you need custom development, system optimization, or technical leadership, I bring a passion for clean code, automation, and modern DevOps practices to every project.
        </p>
      </section>

      <section class="services">
        <h2>Business Offerings</h2>
        <div class="service-grid">
          <div class="service-item">
            <i class="fas fa-code"></i>
            <h3>Drupal Development</h3>
            <p>Custom module and theme development, full-stack Drupal solutions, and decoupled architecture with Vue.js/Nuxt.js integration.</p>
          </div>
          <div class="service-item">
            <i class="fas fa-cogs"></i>
            <h3>System Optimization</h3>
            <p>Performance tuning with AWS, Elasticsearch, Redis, and Docker to ensure scalability and high availability.</p>
          </div>
          <div class="service-item">
            <i class="fas fa-users"></i>
            <h3>Technical Leadership</h3>
            <p>Team guidance, code reviews, and architecture design for enterprise-level projects integrating Drupal with IoT, mobile apps, and more.</p>
          </div>
        </div>
      </section>

      <section class="experience">
        <h2>Experience</h2>
        <div class="experience-item">
          <h3>Senior Drupal Developer - drunomics, Vienna</h3>
          <p class="date">Dec 2021 - Present</p>
          <ul>
            <li>Collaborated with Vue.js/Nuxt.js frontend teams to integrate APIs from Drupal’s decoupled architecture, ensuring seamless data flow.</li>
            <li>Optimized systems using Redis, AWS, and Elasticsearch to handle large content volumes and improve application performance.</li>
            <li>Conducted code reviews to maintain clean, secure, and scalable codebases while enforcing development best practices.</li>
            <li>Developed custom Drupal features to streamline content publishing workflows and enhance usability for editors.</li>
            <li>Integrated third-party tools and services for automation and data synchronization, reducing manual overhead.</li>
            <li>Utilized Xdebug, Docker, and REST APIs for efficient debugging and API optimization.</li>
          </ul>
        </div>
        <div class="experience-item">
          <h3>Drupal Technical Leader - Hogarth Worldwide, Bucharest</h3>
          <p class="date">Feb 2020 - Dec 2021</p>
          <ul>
            <li>Led the technical direction of a development team, ensuring adherence to Drupal best practices and architectural standards.</li>
            <li>Resolved technical disagreements to minimize errors and eliminate bottlenecks in project delivery.</li>
            <li>Architected a large-scale enterprise project integrating Drupal with IoT devices, iOS/Android apps, and Magento e-commerce platforms.</li>
            <li>Collaborated with stakeholders in strategy meetings to define integration approaches across multiple technologies.</li>
            <li>Positioned Drupal as the central hub for a multi-platform ecosystem, ensuring robust data connectivity.</li>
            <li>Investigated and resolved complex system issues, implementing corrective actions to maintain stability.</li>
            <li>Oversaw deployment processes across environments, ensuring smooth and reliable release cycles.</li>
            <li>Mentored developers, providing debugging assistance and architectural guidance to enhance team capabilities.</li>
          </ul>
        </div>
        <div class="experience-item">
          <h3>Drupal Developer - Hogarth Worldwide, Bucharest</h3>
          <p class="date">Aug 2017 - Feb 2020</p>
          <ul>
            <li>Developed and maintained Drupal-based websites, handling both backend and frontend development tasks.</li>
            <li>Mentored junior developers, teaching Drupal best practices and fostering skill development.</li>
            <li>Implemented new features based on architectural designs, enhancing functionality and user experience.</li>
            <li>Integrated external APIs for product reviews, user activity tracking, and performance monitoring.</li>
            <li>Created reusable components aligned with frontend designs, improving development efficiency.</li>
            <li>Collaborated with designers and stakeholders to deliver tailored Drupal solutions meeting business needs.</li>
            <li>Designed custom modules and themes to enhance usability and elevate the overall user experience.</li>
          </ul>
        </div>
        <div class="experience-item">
          <h3>Drupal Developer - Assist Software, Suceava</h3>
          <p class="date">Jan 2016 - Aug 2017</p>
          <ul>
            <li>Built full-stack Drupal projects, managing both front-end and back-end development workflows.</li>
            <li>Developed an online video streaming platform using Drupal, Video.js, jQuery, SQL, and Stripe for payments.</li>
            <li>Implemented subscription systems and video view tracking for user analytics and revenue generation.</li>
            <li>Created a health industry fundraising platform, integrating third-party APIs for payments and donor management.</li>
          </ul>
        </div>
      </section>

      <section class="contact">
        <h2>Contact Me</h2>
        <p>Email: stavovei.ciprian@gmail.com</p>
        <p>Phone: +40 756 289 558</p>
        <div class="social-links">
          <a href="https://linkedin.com/in/ciprian-stavovei364419b9" target="_blank"><i class="fab fa-linkedin"></i></a>
          <a href="https://www.drupal.org/u/ciprianstavovei" target="_blank"><i class="fab fa-drupal"></i></a>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer>
      <p>© 2025 All Around Software Solutions SRL. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  font-family: 'Arial', sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  color: #333;
  background: linear-gradient(to bottom, #f9f9f9, #e6f0fa);
}

header {
  text-align: center;
  padding: 40px 0;
  background: #3498db;
  color: white;
  border-bottom: 4px solid #2980b9;
}

.profile-pic {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  object-fit: cover;
  margin-bottom: 20px;
  border: 3px solid #fff;
}

h1 {
  font-size: 2.5em;
  margin: 0;
  color: #fff;
}

.tagline {
  font-size: 1.2em;
  color: #ecf0f1;
  margin-top: 10px;
}

main {
  padding: 40px 0;
}

section {
  margin-bottom: 40px;
}

h2 {
  font-size: 2em;
  color: #2980b9;
  margin-bottom: 20px;
  text-align: center;
  text-transform: uppercase;
}

p {
  line-height: 1.6;
  font-size: 1.1em;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.service-item {
  text-align: center;
  padding: 20px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border: 2px solid #3498db;
}

.service-item:hover {
  transform: translateY(-10px);
  box-shadow: 0 6px 15px rgba(0,0,0,0.2);
}

.service-item i {
  font-size: 2.5em;
  color: #e74c3c;
  margin-bottom: 15px;
}

.service-item h3 {
  font-size: 1.5em;
  color: #2c3e50;
}

.experience-item {
  margin-bottom: 30px;
  padding: 20px;
  background: #fff;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.experience-item h3 {
  font-size: 1.5em;
  color: #2c3e50;
  margin-bottom: 5px;
}

.date {
  font-style: italic;
  color: #7f8c8d;
  margin-bottom: 10px;
}

.experience-item ul {
  list-style-type: disc;
  padding-left: 20px;
}

.experience-item li {
  margin-bottom: 10px;
  line-height: 1.5;
}

.contact {
  text-align: center;
  background: #3498db;
  padding: 20px;
  border-radius: 8px;
  color: white;
}

.contact p {
  color: #ecf0f1;
}

.social-links a {
  font-size: 1.8em;
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  transition: color 0.3s ease;
}

.social-links a:hover {
  color: #e74c3c;
}

footer {
  text-align: center;
  padding: 20px 0;
  background: #2c3e50;
  color: #ecf0f1;
  border-top: 4px solid #34495e;
}
</style>
