<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Heart Text Animation</title>

<style>
body {
  margin: 0;
  background: #000;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  font-family: Arial, sans-serif;
}

#ui {
  position: relative;
  width: 400px;
  height: 400px;
}

.love_word {
  position: absolute;
  color: #ea80b0;
  font-size: 1.2rem;
  transform: translate(-50%, -50%) rotate(-30deg);
  text-shadow: 0 0 8px #fff;
  white-space: nowrap;
  opacity: 0.8;
  animation: float 10s infinite alternate ease-in-out;
}

/* animation movement */
@keyframes float {
  from {
    transform: translate(-50%, -50%) translateY(0) rotate(-30deg);
  }
  to {
    transform: translate(-50%, -50%) translateY(-20px) rotate(-30deg);
  }
}
</style>
</head>

<body>

<div id="ui"></div>

<script>
// Heart equation
function heart(t) {
  let x = 16 * Math.pow(Math.sin(t), 3);
  let y =
    13 * Math.cos(t) -
    5 * Math.cos(2 * t) -
    2 * Math.cos(3 * t) -
    Math.cos(4 * t);

  return { x, y };
}

const ui = document.getElementById("ui");

// scale and center
const scale = 10;
const offsetX = 200;
const offsetY = 200;

// generate points
for (let i = 0; i < 200; i++) {
  let t = (i / 200) * Math.PI * 2;
  let pos = heart(t);

  let span = document.createElement("span");
  span.className = "love_word";
  span.innerText = "I love you";

  span.style.left = offsetX + pos.x * scale + "px";
  span.style.top = offsetY - pos.y * scale + "px";

  // random animation delay
  span.style.animationDelay = (i * 0.03) + "s";

  ui.appendChild(span);
}
</script>

</body>
</html>