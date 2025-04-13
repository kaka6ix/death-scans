<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Death Scans</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap');* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  height: 100vh;
  width: 100vw;
  background-color: #000;
  color: #fff;
  font-family: 'Orbitron', sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}
img {
  width: 200px;
  height: auto;
  margin-bottom: 20px;
  animation: fadeIn 2s ease-in-out;
}
h1 {
  font-size: 3em;
  letter-spacing: 3px;
  text-align: center;
  animation: glitch 1s infinite;
}
@keyframes fadeIn {
  0% { opacity: 0; transform: scale(0.8); }
  100% { opacity: 1; transform: scale(1); }
}
@keyframes glitch {
  0% { text-shadow: 2px 2px red; }
  20% { text-shadow: -2px -2px cyan; }
  40% { text-shadow: 2px -2px lime; }
  60% { text-shadow: -2px 2px magenta; }
  80% { text-shadow: 2px 2px yellow; }
  100% { text-shadow: none; }
}
.text-glow {
  animation: glow 2s infinite alternate;
}
@keyframes glow {
  from { text-shadow: 0 0 10px #fff; }
  to { text-shadow: 0 0 20px #0ff, 0 0 30px #0ff; }
}
@media (max-width: 600px) {
  h1 {
    font-size: 2em;
  }
  img {
    width: 150px;
  }
}

  </style>
</head>
<body>
  <img src="/mnt/data/file-FqaXkzHZaU5wzQ9aWSbYUV" alt="Death Scans Logo">
  <h1 class="text-glow">DEATH SCANS</h1>
</body>
</html>
