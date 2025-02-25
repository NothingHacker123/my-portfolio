import React from "react";
import ReactDOM from "react-dom";
import "./styles.css";

function App() {
  return (
    <div className="container">
      <header>
        <h1>Sudheer Tripathi</h1>
        <p>Ethical Hacker | Web Penetration Tester | SOC Analyst</p>
      </header>
      <section className="about">
        <h2>About Me</h2>
        <p>I am an ethical hacker with expertise in web penetration testing and SOC analysis.</p>
      </section>
      <section className="skills">
        <h2>Skills</h2>
        <ul>
          <li>Web Penetration Testing</li>
          <li>Cybersecurity</li>
          <li>Python & Scripting</li>
          <li>Burp Suite</li>
          <li>CCNA</li>
          <li>Network Security</li>
          <li>Threat Intelligence</li>
          <li>Incident Response</li>
          <li>SIEM (Security Information and Event Management)</li>
          <li>Red Teaming</li>
        </ul>
      </section>
      <section className="certifications">
        <h2>Certifications</h2>
        <ul>
          <li>CCNA</li>
          <li>CEH (Certified Ethical Hacker)</li>
          <li>PT (Penetration Testing)</li>
          <li>Web PT (Web Penetration Testing)</li>
          <li>Basic Python</li>
        </ul>
      </section>
      <section className="contact">
        <h2>Contact</h2>
        <p>Email: st8195599@gmail.com</p>
        <p>Phone: 6386772931</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/sudheer-tripathi-01282a258" target="_blank">linkedin.com/in/sudheer-tripathi</a></p>
        <p>Instagram: <a href="https://www.instagram.com/mr_lucckyy_?igsh=N2Myd3RjeGxkYzZ4" target="_blank">@mr_lucckyy_</a></p>
        <p>Facebook: <a href="https://www.facebook.com/share/12CJUkWcu7R/" target="_blank">Facebook Profile</a></p>
      </section>
    </div>
  );
}

ReactDOM.render(<App />, document.getElementById("root"));

