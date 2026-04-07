<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Introduction</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&family=Poppins:wght@600;700&display=swap" rel="stylesheet">
</head>
<body>
  <div class="container">
    <!-- Hero Section -->
    <header class="hero">
      <div class="hero-content">
        <div class="profile-pic">
          <img src="https://image2url.com/r2/default/images/1775557878542-5efe04fc-b569-4835-a17b-454662d370c4.jpg" alt="Profile Picture"/>
        </div>
        <h1>Lale Mardon Torres</h1>
        <p class="tagline">First-Year IT Student | Aspiring Developer</p>
      </div>
    </header>

    <!-- About Me Section -->
    <main>
      <section class="about">
        <h2>About Me</h2>
        <p>
          Hi! I'm a passionate first-year IT student with a genuine interest in web development and technology.
        </p>
      </section>
    </main>

    <!-- Footer -->
    <footer>
      <p>&copy; 2026 Torres, Mardon. All rights reserved.</p>
    </footer>



* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  gap: 40px; /* spacing between sections */
  max-width: 800px;
  width: 100%;
}

/* Hero Section */
.hero-content {
  max-width: 600px;
}

.profile-pic {
  margin-bottom: 20px;
}

.profile-pic img {
  width: 160px;
  height: 160px;
  border-radius: 45%;
  border: 5px solid white;
  transition: all 0.4s ease;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}

.profile-pic img:hover {
  transform: scale(1.1) rotate(5deg);
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.4);
}

h1 {
  font-family: 'Poppins', sans-serif;
  font-size: 3.5rem;
  font-weight: 700;
  margin-bottom: 15px;
  transition: all 0.3s ease;
}

h1:hover {
  transform: translateY(-10px);
  text-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
}

.tagline {
  font-size: 1.4rem;
  opacity: 0.95;
  font-weight: 300;
  letter-spacing: 1px;
}

/* About Section */
.about {
  background: white;
  padding: 40px;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  color: #333;
  max-width: 600px;
  width: 100%;
  transition: all 0.3s ease;
}

.about:hover {
  box-shadow: 0 15px 35px rgba(0,0,0,0.15);
  transform: translateY(-5px);
}

.about h2 {
  font-family: 'Poppins', sans-serif;
  font-size: 2.2rem;
  margin-bottom: 25px;
  color: #667eea;
}

.about p {
  font-size: 1.1rem;
  line-height: 1.9;
  color: #555;
  text-align: justify;
}

/* Footer */
footer {
  font-size: 0.95rem;
  color: white;
}
    
  </div>
</body>
</html>
