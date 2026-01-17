# Aastha-birthday-
Birthday wish
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday Aastha 🎉</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }body {
  height: 100vh;
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.card {
  background: white;
  padding: 40px;
  border-radius: 20px;
  text-align: center;
  max-width: 500px;
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
  animation: pop 1s ease;
}

@keyframes pop {
  from { transform: scale(0.5); opacity: 0; }
  to { transform: scale(1); opacity: 1; }
}

h1 {
  font-size: 2.8rem;
  color: #ff4b5c;
  margin-bottom: 15px;
}

h2 {
  font-size: 1.5rem;
  color: #333;
  margin-bottom: 20px;
}

p {
  font-size: 1.1rem;
  color: #555;
  line-height: 1.6;
  margin-bottom: 25px;
}

button {
  padding: 12px 25px;
  font-size: 1rem;
  border: none;
  border-radius: 25px;
  background: #ff4b5c;
  color: white;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: #e63946;
}

.confetti {
  position: absolute;
  width: 10px;
  height: 10px;
  background: red;
  top: -10px;
  animation: fall linear infinite;
}

@keyframes fall {
  to {
    transform: translateY(110vh) rotate(360deg);
  }
}

  </style>
</head>
<body>  <div class="card">
    <h1>🎂 Happy Birthday 🎂</h1>
    <h2>Dear Aastha 💖</h2>
    <p>
      Aastha, as your brother, I may not say it often,<br>
      but you are truly special to me.<br>
      I’ll always wish the best for you, stand by you, and pray for your happiness.<br>
      <strong>Happy Birthday, behen 🎂✨</strong>
    </p>
    <p style="margin-top:10px;font-weight:600;color:#ff4b5c;">– Dhruv 🤍</p>
    <button onclick="celebrate()">Click to Celebrate 🎉</button>
  </div>  <script>
    function celebrate() {
      for (let i = 0; i < 100; i++) {
        const confetti = document.createElement('div');
        confetti.classList.add('confetti');
        confetti.style.left = Math.random() * window.innerWidth + 'px';
        confetti.style.backgroundColor = `hsl(${Math.random() * 360}, 100%, 50%)`;
        confetti.style.animationDuration = Math.random() * 3 + 2 + 's';
        document.body.appendChild(confetti);

        setTimeout(() => confetti.remove(), 5000);
      }
    }
  </script></body>
</html>
