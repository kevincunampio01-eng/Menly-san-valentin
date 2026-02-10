# Menly-san-valentin
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>¿Quieres ser mi San Valentín, Menly?</title>

<style>
body {
  background: linear-gradient(180deg, #ffd6e8, #fff);
  font-family: 'Comic Sans MS', 'Arial', cursive;
  text-align: center;
  padding: 40px;
}

.card {
  background: white;
  border-radius: 25px;
  padding: 30px;
  max-width: 420px;
  margin: auto;
  box-shadow: 0 15px 30px rgba(0,0,0,0.15);
}

h1 {
  color: #ff4d88;
  font-size: 28px;
}

p {
  color: #555;
  font-size: 16px;
}

h2 {
  color: #ff6fa5;
}

button {
  padding: 14px 28px;
  border: none;
  border-radius: 30px;
  font-size: 18px;
  margin: 12px;
  cursor: pointer;
  transition: 0.3s;
}

#yes {
  background: #ff4d88;
  color: white;
  box-shadow: 0 5px 15px rgba(255,77,136,0.4);
}

#no {
  background: #e0e0e0;
}
</style>
</head>

<body>

<div class="card">
  <h1>💖 Hey Menly 💖</h1>

  <p>
    Entre risas, miradas y momentos bonitos ✨  
    me di cuenta de algo muy simple pero muy real…  
    <br><br>
    <strong>quiero vivir este San Valentín contigo</strong> 💌
  </p>

  <h2>¿Quieres ser mi San Valentín? 💕</h2>

  <button id="yes" onclick="accept()">💖 SÍ, OBVIO 💖</button>
  <button id="no" onmouseover="moveNo()">NO 😢</button>
</div>

<script>
function accept() {
  alert("💘 SABÍA QUE DIRÍAS QUE SÍ, MENLY 💘\nGracias por hacerme tan feliz 🥰");
}

function moveNo() {
  const btn = document.getElementById("no");
  btn.style.position = "absolute";
  btn.style.top = Math.random() * (window.innerHeight - 50) + "px";
  btn.style.left = Math.random() * (window.innerWidth - 100) + "px";
}
</script>

</body>
</html>
