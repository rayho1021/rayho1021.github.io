---
layout: default
title: Ray Ho's Personal Website
---

<nav class="nav-section">
  <ul class="nav-links">
    <li><a href="{{ '/' | relative_url }}" class="{% if page.url == '/' %}active{% endif %}">Home</a></li>
    <li><a href="{{ '/about.html' | relative_url }}">About</a></li>
    <li><a href="{{ '/projects.html' | relative_url }}">Projects</a></li>
    <li><a href="{{ '/articles.html' | relative_url }}">Articles</a></li>
  </ul>
</nav>

<div class="top-section-wrapper">
  <div class="profile-container">
    <div class="left-section">
      <div class="profile-photo">
        <img src="/assets/images/picture.JPG" alt="Ray Ho's Photo">
      </div>
      <div class="contact-info">
        <h3>Information</h3>
        <p><strong>Email</strong>: rechun5147@gmail.com</p>
        <p><strong>Phone</strong>: (+886) 983-351-985</p>
        <p><strong>Linkedin</strong>: www.linkedin.com/in/rayho-1021-profile</p>
      </div>
    </div>

    <div class="right-section">
      <div class="intro-section">
        <h1>Hello! I'm Ray Ho</h1>
        <p>I haven't come up with any ideas yet, wait a moment. :)</p>
      </div>
    </div>
  </div>
</div>

<div class="preview-container">
  <div class="preview-card">
    <h3>About Me</h3>
    <p>我的背景和經歷，還沒放東西，點擊了解更多。</p>
    <a href="{{ '/about.html' | relative_url }}" class="read-more">Read More...</a>
  </div>

  <div class="preview-card">
    <h3>My Projects</h3>
    <p>我的一些專案，還沒放東西，點擊了解更多。</p>
    <a href="{{ '/projects.html' | relative_url }}" class="read-more">Read More...</a>
  </div>

  <div class="preview-card">
    <h3>My Articles</h3>
    <p>我的文章部落格，學習筆記、閱讀心得或個人觀點，還沒放東西，點擊了解更多。</p>
    <a href="{{ '/articles.html' | relative_url }}" class="read-more">Read More...</a>
  </div>
</div>

<div class="contact-section">
  <div class="contact-container">
    <div class="contact-form-section">
      <h3>Contact Me</h3>
      <form action="https://formspree.io/f/myzdzvpl" method="POST">
        <div class="form-group">
          <input type="text" name="first_name" placeholder="First Name*" required>
          <input type="text" name="last_name" placeholder="Last Name*" required>
        </div>
        <div class="form-group">
          <input type="email" name="_replyto" placeholder="Email*" required>
          <input type="text" name="message" placeholder="Type your message here...*" required>
        </div>
        <button type="submit">Submit</button>
      </form>
    </div>
  </div>
</div>