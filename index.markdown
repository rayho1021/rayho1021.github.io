---
layout: default
title: "Ray Ho's Persenal Website"
permalink: /
---

<div class="profile-container">
  <div class="left-section">
    <div class="profile-photo">
      <img src="{{ '/assets/images/picture.JPG' | relative_url }}" alt="你的個人照片">
    </div>
    <div class="contact-info">
      <h3><b>Information</b></h3>
      <p><b>Email :</b></p>
      <p>rechun5147@gmail.com</p>
      <p><b>Phone : </b></p>
      <p>(+886) 983-351-985</p>
      <p><b>Linkedin : </b></p>
      <p>www.linkedin.com/in/rayho-1021-profile</p>
    </div>
  </div>

  <div class="right-section">
    <div class="intro-section">
      <h1>Hello! I'm Ray Ho</h1>
      <p>I haven't come up with any ideas yet, wait a moment. :) </p>
    </div>

    <div class="nav-section">
      <ul class="nav-links">
        <li><a href="{{ '/resume' | relative_url }}">Resume</a></li>
        <li><a href="{{ '/experience' | relative_url }}">Experience</a></li>
        <li><a href="{{ '/blog' | relative_url }}">Blog</a></li>
        <li><a href="{{ '/projects' | relative_url }}">Projects</a></li>
      </ul>
    </div>

    <div class="contact-form-section">
      <h3><b>Contact Me</b></h3>
      <form action="https://formspree.io/f/myzdzvpl" method="POST">
        <div class="form-group">
          <input type="text" name="first_name" placeholder="First Name*" required>
          <input type="text" name="last_name" placeholder="Last Name*" required>
        </div>
        <div class="form-group">
          <input type="email" name="Email" placeholder="Email*" required>
          <input type="text" name="message" placeholder="Type your message here...*" required>
        </div>
        <button type="submit">Submit</button>
      </form>
    </div>
  </div>
</div>