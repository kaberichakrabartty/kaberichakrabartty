# 👋 Hi, I'm Kaberi Chakrabartty!

Welcome to my GitHub profile!





---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kaberi Chakrabartty Animated Intro</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff;
      color: #333;
      display: flex;
      height: 100vh;
      align-items: center;
      justify-content: center;
    }
    .container {
      text-align: center;
      font-size: 2em;
    }
    .fade-in {
      opacity: 0;
      transition: opacity 1s;
    }
    .fade-in.visible {
      opacity: 1;
    }
    .emoji {
      font-size: 2.5em;
      margin-right: 0.3em;
      vertical-align: middle;
      animation: wave 1.5s infinite;
      display: inline-block;
    }
    @keyframes wave {
      0% { transform: rotate(0deg);}
      20% { transform: rotate(-20deg);}
      40% { transform: rotate(0deg);}
      100% { transform: rotate(0deg);}
    }
  </style>
</head>
<body>
  <div class="container">
    <span class="emoji">👋</span>
    <span id="hi-text">Hi</span>
    <div id="name-text" class="fade-in">I am Kaberi Chakrabartty</div>
  </div>
  <script>
    // Initially hide the name
    document.getElementById('name-text').style.display = 'none';
    // After a short delay, show the name with fade-in effect
    setTimeout(function() {
      const nameText = document.getElementById('name-text');
      nameText.style.display = 'block';
      setTimeout(function() {
        nameText.classList.add('visible');
      }, 100); // Ensure display triggers before adding visible
    }, 1500); // Show after 1.5 seconds
  </script>
</body>
</html>


🚀 Languages and Tools

<p align="left">
  <a href="https://getbootstrap.com/" target="_blank">
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
  </a>
  <a href="https://www.w3.org/Style/CSS/" target="_blank">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  </a>
  <a href="https://www.figma.com/" target="_blank">
    <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/>
  </a>
  <a href="https://developer.mozilla.org/docs/Web/HTML" target="_blank">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  </a>
  <a href="https://www.javascript.com/" target="_blank">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  </a>
</p>


