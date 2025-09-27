<!-- index.html -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hi, I'm Zoe</title>
  <style>
    body { font: 16px/1.6 system-ui, sans-serif; max-width: 720px; margin: 40px auto; padding: 0 16px; }
    header { margin-bottom: 24px; }
    nav a { margin-right: 12px; }
    .card { border: 1px solid #ddd; border-radius: 12px; padding: 16px; margin: 12px 0; }
  </style>
</head>
<body>
  <header>
    <h1>Zoe Jaramillo</h1>
    <nav>
      <a href="/">Home</a>
      <a href="/projects.html">Projects</a>
      <a href="/resume.pdf">Resume</a>
    </nav>
  </header>
  <section class="card">
    <h2>About</h2>
    <p>EE @ Cal Poly SLO. Embedded systems, PCB design, and photography after hours.</p>
  </section>
  <section class="card">
    <h2>Featured Project</h2>
    <p>4-bit DAC PCB + audio demo. <a href="https://github.com/your-username/dac-demo">Code</a></p>
  </section>
  <footer>© <span id="y"></span> Zoe</footer>
  <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
</body>
</html>
