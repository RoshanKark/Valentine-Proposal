<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Be My Valentine 💖</title>

<style>
* {
  -webkit-tap-highlight-color: transparent;
  touch-action: manipulation;
}

body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(180deg, #ff758c, #ff7eb3);
  font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.phone {
  width: 100%;
  max-width: 420px;
  height: 100%;
  background: white;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 30px 20px;
  box-sizing: border-box;
  text-align: center;
  position: relative;
}

h1, p, button {
  user-select: none;
  -webkit-user-select: none;
}

h1 {
  font-size: 26px;
  color: #ff3b6f;
  margin-top: 60px;
}

p {
  font-size: 18px;
  color: #444;
  margin: 20px 0;
}

.buttons {
  margin-bottom: 50px;
  position: relative;
  height: 140px;
}

button {
  width: 100%;
  padding: 16px;
  font-size: 18px;
  border-radius: 14px;
  border: none;
  margin-top: 12px;
  cursor: pointer;
  transition: all 0.3s ease;
}

#yesBtn {
  background: #ff3b6f;
  color: white;
  font-weight: bold;
}

#noBtn {
  background: #eee;
  color: #333;
  position: absolute;
  left: 0;
}

/* Popup */
.popup {
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.6);
  display: none;
  justify-content: center;
  align-items: center;
  z-index: 10;
}

.popup-box {
  background: white;
  padding: 25px;
  border-radius: 16px;
  width: 80%;
  max-width: 300px;
  text-align: center;
  animation: pop 0.3s ease;
}

@keyframes pop {
  from { transform: scale(0.8); opacity: 0; }
  to { transform: scale(1); opacity: 1; }
}

.popup-box h2 {
  color: #ff3b6f;
}

/* Floating hearts */
.heart {
  position: absolute;
  bottom: 0;
  font-size: 18px;
  animation: float 6s linear forwards;
}

@keyframes float {
  from { transform: translateY(0); opacity: 1; }
  to { transform: translateY(-800px); opacity: 0; }
}

/* Confetti */
.confetti {
  position: fixed;
  top: -10px;
  width: 10px;
  height: 10px;
  opacity: 0.9;
  animation: fall linear forwards;
  z-index: 20;
}

@keyframes fall {
  to {
    transform: translateY(110vh) rotate(720deg);
    opacity: 0;
  }
}
</style>
</head>

<body>

<div class="phone" id="main">
  <h1>💘 Will you be my Valentine? 💘</h1>

  <p id="text">
    Just imagine us 💭<br>
    laughter, late-night talks ✨<br>
    and a thousand little memories together 💞
  </p>

  <div class="buttons">
    <button id="yesBtn" onclick="yesClicked()" aria-label="Yes Valentine">
      YES 💖
    </button>

    <button id="noBtn" onclick="noClicked()" aria-label="No Valentine">
      NO 🙈
    </button>
  </div>
</div>

<div class="popup" id="popup">
  <div class="popup-box">
    <h2>😢 Are you REALLY sure?</h2>
    <p>My heart might crack just a tiny bit… 💔</p>
    <button onclick="closePopup()">Okay okay 😅</button>
  </div>
</div>

<script>
let noCount = 0;
let yesScale = 1;

function noClicked() {
  noCount++;
  document.getElementById("popup").style.display = "flex";

  const noBtn = document.getElementById("noBtn");
  const container = document.querySelector(".buttons");

  const maxX = container.offsetWidth - noBtn.offsetWidth;
  const maxY = 90;

  noBtn.style.left = Math.random() * maxX + "px";
  noBtn.style.top = Math.random() * maxY + "px";

  yesScale += 0.15;
  document.getElementById("yesBtn").style.transform = `scale(${yesScale})`;

  if (noCount >= 4) {
    noBtn.style.display = "none";
    document.getElementById("text").innerHTML =
      "I’ll stop asking… 🥺<br>but my heart already knows your answer 💕";
  }
}

function closePopup() {
  document.getElementById("popup").style.display = "none";
}

function yesClicked() {
  launchConfetti();

  document.getElementById("main").innerHTML = `
    <h1>🎉 IT'S A YES 🎉</h1>
    <p>
      You didn’t just make my day…<br>
      you made my heart smile 😊💓<br><br>

      Thank you for choosing me 🥹<br>
      for choosing <b>us</b> 💞<br><br>

      I promise love that feels safe,<br>
      laughter that never fades 😂,<br>
      and choosing you — today, tomorrow,<br>
      and every day after 💍✨<br><br>

      Happy Valentine’s Day,<br>
      my favourite person 💘
    </p>
  `;
}

/* Confetti */
function launchConfetti() {
  const colors = ["#ff3b6f", "#ff7eb3", "#ffd1dc", "#fff", "#ffb347"];

  for (let i = 0; i < 140; i++) {
    const c = document.createElement("div");
    c.className = "confetti";
    c.style.left = Math.random() * window.innerWidth + "px";
    c.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
    c.style.animationDuration = (Math.random() * 3 + 2) + "s";
    document.body.appendChild(c);

    setTimeout(() => c.remove(), 5000);
  }
}

/* Floating hearts */
setInterval(() => {
  const heart = document.createElement("div");
  heart.className = "heart";
  heart.innerHTML = "💖";
  heart.style.left = Math.random() * window.innerWidth + "px";
  heart.style.fontSize = (Math.random() * 20 + 14) + "px";
  document.body.appendChild(heart);

  setTimeout(() => heart.remove(), 6000);
}, 400);
</script>

</body>
</html>
