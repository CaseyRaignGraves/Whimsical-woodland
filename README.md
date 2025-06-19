# Whimsical-woodland
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Whimsical Woodland Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: linear-gradient(to bottom, #fdf6f9, #e9fbe7);
      color: #2c2c2c;
    }

    header {
      background-image: url('banner.jpg');
      background-size: cover;
      background-position: center;
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-shadow: 0 0 8px #5e3150;
    }

    header h1 {
      font-size: 3.5rem;
      background: rgba(0, 0, 0, 0.4);
      padding: 1rem 2rem;
      border-radius: 12px;
    }

    .section {
      padding: 60px 10%;
    }

    .section h2 {
      font-family: 'Palatino Linotype', serif;
      font-size: 2.5rem;
      color: #47583a;
      margin-bottom: 30px;
      border-left: 6px solid #d17aa0;
      padding-left: 20px;
    }

    .gallery, .video-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 40px;
    }

    .card {
      background: #fff8fa;
      border: 1px solid #dbcad1;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      border-radius: 15px;
      overflow: hidden;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .card img, .card video {
      width: 100%;
      display: block;
    }

    .caption {
      padding: 15px;
      font-size: 1rem;
      font-style: italic;
      color: #5a2e46;
    }

    footer {
      text-align: center;
      padding: 40px 0;
      background-color: #f2f2f2;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>

<body>

  <!-- 🌿 Banner -->
  <header>
    <h1>Whimsical Visions</h1>
  </header>

  <!-- 📷 Photo Gallery -->
  <section class="section">
    <h2>Photo Gallery</h2>
    <div class="gallery">

      <div class="card">
        <img src="gallery/photo1.jpeg" alt="Bramblelight Gaze" />
        <div class="caption">“A quiet moment caught between light and leaves.”</div>
      </div>

      <div class="card">
        <img src="gallery/photo2.jpeg" alt="Whispers in Moss" />
        <div class="caption">“Velvet green wraps around whispered secrets.”</div>
      </div>

      <div class="card">
        <img src="gallery/photo3.jpeg" alt="Lanterns and Petals" />
        <div class="caption">“Lantern glow meets a trail of floating petals.”</div>
      </div>

      <div class="card">
        <img src="gallery/photo4.jpeg" alt="Candlelit Reflection" />
        <div class="caption">“Reflections in wax and wandering thoughts.”</div>
      </div>

      <div class="card">
        <img src="gallery/photo5.jpeg" alt="Thistle & Veil" />
        <div class="caption">“Caught between brambles and dreaming eyes.”</div>
      </div>

    </div>
  </section>

  <!-- 🎥 Video Section -->
  <section class="section">
    <h2>Moving Magic</h2>
    <div class="video-gallery">

      <div class="card">
        <video controls poster="videos/thumb1.jpg">
          <source src="videos/video1.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
        <div class="caption">“Wandering the golden mossscape.”</div>
      </div>

      <div class="card">
        <video controls poster="videos/thumb2.jpg">
          <source src="videos/video2.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
        <div class="caption">“Twilight petals in motion.”</div>
      </div>

      <div class="card">
        <video controls poster="videos/thumb3.jpg">
          <source src="videos/video3.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
        <div class="caption">“Soft spells and candle flickers.”</div>
      </div>

    </div>
  </section>

  <!-- 🌸 Footer -->
  <footer>
    Created with love and wildflowers.
  </footer>

</body>
</html>
