<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    /* Reset & base styles */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: "Helvetica Neue", Arial, sans-serif;
      background-color: #f8f8f8;
      color: #333;
      line-height: 1.6;
      padding: 40px 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      max-width: 800px;
      text-align: center;
      margin-bottom: 40px;
    }

    h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    p.subtitle {
      font-size: 1rem;
      color: #777;
    }

    main {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 30px;
      max-width: 1000px;
      width: 100%;
    }

    /* Media and video styling */
    .portfolio-item {
      background: #fff;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s ease;
    }

    .portfolio-item:hover {
      transform: translateY(-5px);
    }

    iframe, img {
      width: 100%;
      height: auto;
      display: block;
      border: none;
    }

    .caption {
      padding: 15px;
      font-size: 0.9rem;
      color: #555;
    }

    footer {
      margin-top: 60px;
      font-size: 0.8rem;
      color: #aaa;
    }

    a {
      color: inherit;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>My Minimal Portfolio</h1>
    <p class="subtitle">A collection of my works and experiments</p>
  </header>

  <main>
    <!-- Vimeo Example -->
    <div class="portfolio-item">
      <iframe src="https://player.vimeo.com/video/76979871" 
              allow="autoplay; fullscreen; picture-in-picture" 
              allowfullscreen>
      </iframe>
      <div class="caption">Vimeo Project Title</div>
    </div>

    <!-- Image Example -->
    <div class="portfolio-item">
      <img src="https://via.placeholder.com/800x450" alt="Project Image" />
      <div class="caption">Photography Project</div>
    </div>

    <!-- Add more items below -->
    <!--
    <div class="portfolio-item">
      <iframe src="https://player.vimeo.com/video/YOUR_VIDEO_ID" allowfullscreen></iframe>
      <div class="caption">Another Vimeo Video</div>
    </div>
    -->
  </main>

  <footer>
    <p>© 2025 Your Name · <a href="https://github.com/yourusername">GitHub</a></p>
  </footer>

</body>
</html>
