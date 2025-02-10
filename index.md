---
layout: default
---

<div class="container">
  <div class="sidebar">
    <nav class="menu">
      <ul>
        <li><a href="#about" class="current">About Me</a></li>
        <li><a href="#publications">Publications</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#cv">CV/Resume</a></li> <!-- 将CV作为独立菜单项 -->
      </ul>
    </nav>
  </div>

  <div class="main-content">
    <section id="about">
      <div class="profile-header">
        <img src="{{ site.baseurl }}/assets/images/profile.jpg" alt="我的照片" class="profile-img"/>
        <div class="info">
          <h1>Zihao Chen</h1>
          <p><strong>Ph.D. Candidate</strong></p>
          <p>School of Microelectronics & State Key Laboratory of Integrated Chips and Systems,</p>
          <p>Fudan University, Shanghai, China</p>
          <p>Contact: <a href="mailto:zhchen17@fudan.edu.cn">zhchen17@fudan.edu.cn</a></p>
        </div>
      </div>
    </section>

    <section id="publications">
      <h2>Publications</h2>
      <p>List of publications...</p>
    </section>

    <section id="services">
      <h2>Services</h2>
      <p>List of services...</p>
    </section>

    <!-- 将CV放入独立小节，作为菜单项 -->
    <section id="cv">
      <h2>CV/Resume</h2>
      <p><a href="path/to/your/cv.pdf" target="_blank">Download CV</a></p>
    </section>
  </div>
</div>
