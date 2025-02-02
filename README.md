<!-- Profile Image & Banner -->
<p align="center">
  <img src="https://i.ibb.co/BV4QD10L/Photoroom-20250202-200550-photoaidcom-cropped.png" alt="Subham Das" width="150" height="150" style="border-radius: 50%;">
</p>

<p align="center">
  <img src="https://your-banner-url.com/banner.png" alt="Banner">
</p>

<!-- Dynamic Greeting -->
<h1 align="center" id="greeting">Hi 👋, I'm Subham Das</h1>
<h3 align="center">A passionate developer building innovative gaming experiences</h3>

<script>
  function updateGreeting() {
    const now = new Date();
    const hours = now.getHours();
    let greeting = 'Good Evening';
    if (hours < 12) greeting = 'Good Morning';
    if (hours >= 12 && hours < 18) greeting = 'Good Afternoon';
    document.getElementById('greeting').innerText = `${greeting} 👋, I'm Subham Das`;
  }
  updateGreeting();
</script>

<!-- Real-time Clock -->
<p align="center">
  <img src="https://img.shields.io/badge/Current%20Time%20(UTC)-Loading...-blue?style=for-the-badge" id="clock">
</p>

<script>
  function updateClock() {
    const now = new Date();
    const utcTime = now.toISOString().split("T")[1].split(".")[0];
    document.getElementById("clock").setAttribute("src", `https://img.shields.io/badge/Current%20Time%20(UTC)-${utcTime}-blue?style=for-the-badge`);
  }
  setInterval(updateClock, 1000);
  updateClock();
</script>

---

### 📊 **GitHub Stats**
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SubhamDas&show_icons=true&theme=radical" alt="GitHub Stats">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SubhamDas&theme=radical" alt="GitHub Streak">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SubhamDas&layout=compact&theme=radical" alt="Top Languages">
</p>

---

### 🚀 **Tech Stack**
<p align="center">
  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript">
  <img src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js">
  <img src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react">
  <img src="https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb">
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python">
</p>

---

### 🎮 **Featured Projects**
<p align="center">
  <a href="https://github.com/yourprofile/project1">
    <img src="https://img.shields.io/badge/Project%201-4CAF50?style=flat-square&logo=github">
  </a>
  <a href="https://github.com/yourprofile/project2">
    <img src="https://img.shields.io/badge/Project%202-FF5722?style=flat-square&logo=github">
  </a>
</p>

---

### 🏆 **GitHub Trophies**
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=SubhamDas&theme=onedark">
</p>

---

### 📊 **GitHub Activity Graph**
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SubhamDas&theme=react-dark">
</p>

---

### 🌐 **Connect with Me**
<p align="center">
  <a href="https://linkedin.com/in/yourprofile">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin">
  </a>
  <a href="https://twitter.com/yourprofile">
    <img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter">
  </a>
  <a href="https://yourwebsite.com">
    <img src="https://img.shields.io/badge/-Portfolio-FF5722?style=flat-square&logo=google-chrome">
  </a>
</p>

---

### 📕 **Latest Blog Posts**
<!-- BLOG-POST-LIST:START -->
- [Post 1 Title](https://yourblog.com/post1)
- [Post 2 Title](https://yourblog.com/post2)
- [Post 3 Title](https://yourblog.com/post3)
<!-- BLOG-POST-LIST:END -->

---

### 🎥 **Latest YouTube Videos**
<!-- YOUTUBE:START -->
- [Video 1 Title](https://youtube.com/video1)
- [Video 2 Title](https://youtube.com/video2)
- [Video 3 Title](https://youtube.com/video3)
<!-- YOUTUBE:END -->

---

### 🔥 **Fun Fact**
```md
Did you know? The first-ever computer virus was called "Creeper" and was written in 1971! 👀
