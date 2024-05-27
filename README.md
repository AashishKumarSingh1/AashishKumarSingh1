<h1>🏢Hello College Web Application</h1>

<p>👋Welcome to Hello College, a user-friendly full-stack web application designed to solve users' problems and create a community for different domains. Our website also provides important materials and resources for students.</p>
<hr>
<h3>🧑‍💼Tech Stack Used: </h3>
<ul>
  <li><b>Backend:</b>Express JS, Node JS, AJAX</li>
  <li><b>Database:</b>My SQL</li>
  <li><b>Frontend:</b>JavaScript, jQuery, Bootstrap, HTML, CSS</li>
</ul>
<h3>🪧Installation Steps:</h3>
<ol>
  <li>Clone the Project</li>
  <li>npm init</li>
  <li>npm install</li>
  <li>In the server.js file and SqlFunction.js, update the database connection configuration with your MySQL credentials.</li>
  <li>Open MySQL Workbench and run the following command to create the community table:
  <pre>
    CREATE TABLE community (
    id INT PRIMARY KEY AUTO_INCREMENT,
    issue VARCHAR(1000) NOT NULL,
    time TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
    date DATETIME DEFAULT CURRENT_TIMESTAMP,
    upvote INT DEFAULT 0,
    downvote INT DEFAULT 0
);
   
  </pre>
  </li>
  <li>Run the command node server.js in the code editor(VS Code)</li>
  <li>Now Open your Browser and go to http://127.0.0.1:3000</li>
</ol>
<h3>✅Libraries and Dependencies</h3>
<ul>
  <li>mysql</li>
  <li>express</li>
  <li>nodemailer</li>
  <li>body-parser</li>
  <li>cookie-parser</li>
  <li>path</li>
</ul>
<h3>▶Overview Video</h3>
<p>For a detailed overview of the application , please watch the <a target="_blank" href="https://www.loom.com/share/f763872a339c407aa0e3ebcdfe606ab9?sid=9dba8129-af8d-499f-9d01-07ef5b0fe921">video.</a></p>
<h3>Features</h3>
<ul>
  <li>User-friendly interface.</li>
  <li>Community creation for different domains.</li>
  <li>Access to important materials and </li>
<li>Added OTP verification through G-Mail account for the user authentication.</li>
  <li>Upvote and downvote system for community issues</li>
</ul>
<h3>🤝Contact</h3>
<p>For any queries or suggestions</p>

- **Email**: [aashishs.ug23.cs@nitp.ac.in](mailto:aashishs.ug23.cs@nitp.ac.in)
- **LinkedIn**: [LinkedIn Profile](<www.linkedin.com/in/aashish-kumar-singh-7110b02a9>)
- **GitHub**: [GitHub Profile](<https://github.com/AashishKumarSingh1/AashishKumarSingh1>)
<hr>
<h2>👨‍🦱Thank you for visiting this project "Hello College".</h2>

