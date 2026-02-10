<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Angel ❤️</title>

<style>
body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(#ffb6c1, #ffe4e1);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Comic Sans MS', cursive, sans-serif;
}

.page {
  display: none;
  text-align: center;
}

.page.active {
  display: block;
}

.paper {
  background: white;
  padding: 28px;
  width: 320px;
  border-radius: 14px;
  box-shadow: 0 10px 20px rgba(0,0,0,0.25);
  margin: auto;
  position: relative;
  top: 25px;
}

.paper h1 {
  color: #e75480;
  font-size: 24px;
}

.paper p {
  color: #444;
  font-size: 16px;
  line-height: 1.6;
}

.bear {
  font-size: 160px;
  margin-top: 5px;
}

button {
  margin-top: 18px;
  padding: 10px 20px;
  border: none;
  border-radius: 20px;
  background: #ff69b4;
  color: white;
  font-size: 14px;
  cursor: pointer;
}

button:hover {
  background: #ff1493;
}
</style>
</head>

<body>

<!-- PAGE 1 -->
<div class="page active">
  <div class="paper">
    <h1>Angel ❤️</h1>
    <p>
      I made this just for you.<br><br>
      Take your time reading it.<br>
      Every word here comes straight from my heart.
    </p>
    <button onclick="nextPage()">Next</button>
  </div>
  <div class="bear">🧸</div>
</div>

<!-- PAGE 2 -->
<div class="page">
  <div class="paper">
    <p>
      I don’t think you truly realize how much you mean to me.<br><br>
      You’re not just someone important —
      you’re someone who changed the way I see the world.
    </p>
    <button onclick="nextPage()">Next</button>
  </div>
  <div class="bear">🧸</div>
</div>

<!-- PAGE 3 -->
<div class="page">
  <div class="paper">
    <p>
      When life feels heavy,<br>
      you make it lighter.<br><br>
      Just knowing you’re there
      gives me comfort, peace, and strength.
    </p>
    <button onclick="nextPage()">Next</button>
  </div>
  <div class="bear">🧸</div>
</div>

<!-- PAGE 4 -->
<div class="page">
  <div class="paper">
    <p>
      Your smile stays in my mind.<br>
      Your voice stays in my heart.<br><br>
      Even on the days we’re apart,
      you’re never far from me.
    </p>
    <button onclick="nextPage()">Next</button>
  </div>
  <div class="bear">🧸</div>
</div>

<!-- PAGE 5 -->
<div class="page">
  <div class="paper">
    <p>
      You make me feel seen.<br>
      You make me feel understood.<br>
      You make me feel loved.<br><br>
      And that means more to me than I can explain.
    </p>
    <button onclick="nextPage()">Next</button>
  </div>
  <div class="bear">🧸</div>
</div>

<!-- PAGE 6 -->
<div class="page">
  <div class="paper">
    <p>
      I want to be there for you —
      in the happy moments,
      in the hard ones,
      and in all the quiet in between.<br><br>
      You’re worth choosing every day.
    </p>
    <button onclick="nextPage()">Next</button>
  </div>
  <div class="bear">🧸</div>
</div>

<!-- PAGE 7 -->
<div class="page">
  <div class="paper">
    <h1>My Angel 💖</h1>
    <p>
      I care about you deeply.<br>
      I believe in you.<br>
      And I’m so grateful to have you in my life.<br><br>
      My heart will always choose you.
    </p>
  </div>
  <div class="bear">🧸❤️</div>
</div>

<script>
let currentPage = 0;
const pages = document.querySelectorAll('.page');

function nextPage() {
  pages[currentPage].classList.remove('active');
  currentPage++;
  pages[currentPage].classList.add('active');
}
</script>

</body>
</html>
