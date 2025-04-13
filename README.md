<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Death Scans</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Orbitron', sans-serif; background: #000; color: #fff; }
    header { background: #6a0dad; display: flex; align-items: center; justify-content: space-between; padding: 10px 20px; }
    .logo { display: flex; align-items: center; gap: 10px; }
    .logo img { height: 40px; }
    .menu { display: flex; gap: 20px; }
    .menu a { color: #fff; text-decoration: none; font-size: 16px; }
    .search-bar { background: #222; padding: 10px; display: flex; justify-content: center; }
    .search-bar input { padding: 8px; width: 90%; border: none; border-radius: 5px; background: #111; color: white; }
    .section-title { padding: 20px; font-size: 24px; border-bottom: 2px solid #444; }
    .grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(140px, 1fr)); gap: 15px; padding: 20px; }
    .card { background: #111; border-radius: 8px; overflow: hidden; text-align: center; }
    .card img { width: 100%; height: 200px; object-fit: cover; }
    .badge { background: #b22222; display: inline-block; padding: 2px 6px; font-size: 12px; border-radius: 4px; margin-top: 5px; }
    .card-title { padding: 5px; font-weight: bold; }
    .card-sub { font-size: 13px; color: #aaa; }
    footer { text-align: center; padding: 20px; font-size: 14px; color: #aaa; background: #111; margin-top: 30px; }.auth-box, .dashboard { background: #111; padding: 30px; border-radius: 10px; max-width: 500px; margin: 40px auto; text-align: center; }
.auth-box h2, .dashboard h2 { margin-bottom: 20px; }
.auth-box input, .dashboard input, .dashboard textarea { display: block; width: 100%; margin: 10px 0; padding: 10px; border-radius: 5px; border: none; background: #222; color: #fff; }
.auth-box button, .dashboard button { padding: 10px 20px; background: #6a0dad; border: none; border-radius: 5px; color: #fff; cursor: pointer; margin-top: 10px; }
.reader { max-width: 800px; margin: 20px auto; background: #111; padding: 10px; border-radius: 10px; }
.reader img { width: 100%; margin-bottom: 10px; border-radius: 5px; }

  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="logo.png" alt="Logo">
      <span>DEATH SCANS</span>
    </div>
    <div class="menu">
      <a href="#">Home</a>
      <a href="#login">Login</a>
      <a href="#register">Register</a>
      <a href="#reader">Baca</a>
      <a href="#dashboard">Upload</a>
    </div>
  </header>  <div class="search-bar">
    <input type="text" placeholder="Search manga or manhwa...">
  </div>  <div class="section-title">Popular Today</div>
  <div class="grid">
    <div class="card">
      <img src="https://via.placeholder.com/150x200">
      <div class="badge">Manhwa</div>
      <div class="card-title">Mercenary Enrollment</div>
      <div class="card-sub">Chapter 233</div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/150x200">
      <div class="badge">Manhwa</div>
      <div class="card-title">Lookism</div>
      <div class="card-sub">Chapter 550</div>
    </div>
  </div>  <div class="section-title">Project Update</div>
  <div class="grid">
    <div class="card">
      <img src="https://via.placeholder.com/150x200">
      <div class="badge">Original</div>
      <div class="card-title">True Education</div>
      <div class="card-sub">Ch. 123 FIX</div>
    </div>
  </div>  <div id="login" class="auth-box">
    <h2>Login</h2>
    <input type="text" placeholder="Username">
    <input type="password" placeholder="Password">
    <button>Login</button>
  </div>  <div id="register" class="auth-box">
    <h2>Register</h2>
    <input type="text" placeholder="Username">
    <input type="email" placeholder="Email">
    <input type="password" placeholder="Password">
    <button>Register</button>
  </div>  <div id="reader" class="reader">
    <h2 style="text-align: center; margin-bottom: 20px;">Chapter 1 - Death Scans</h2>
    <img src="https://via.placeholder.com/800x1200" alt="Page 1">
    <img src="https://via.placeholder.com/800x1200" alt="Page 2">
    <img src="https://via.placeholder.com/800x1200" alt="Page 3">
  </div>  <div id="dashboard" class="dashboard">
    <h2>Upload Chapter</h2>
    <input type="text" placeholder="Judul Proyek">
    <input type="text" placeholder="Judul Chapter">
    <textarea placeholder="Deskripsi singkat..."></textarea>
    <input type="file" multiple>
    <button>Upload Chapter</button>
  </div>  <footer>
    &copy; 2025 Death Scans. All rights reserved.
  </footer>
</body>
</html>
