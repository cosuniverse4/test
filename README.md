<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Twinfinity - Cosmic Streetwear</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;700&family=Playfair+Display&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: 'Playfair Display', serif;
      background: linear-gradient(180deg, #0A1A2F, #000000);
      color: white;
    }
    h1, h2, h3, button {
      font-family: 'Space Grotesk', sans-serif;
    }

    /* Hero Section */
    .hero {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      color: #FFD700;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .hero button {
      padding: 1rem 2rem;
      background: #FFD700;
      color: black;
      border: none;
      border-radius: 50px;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    .hero button:hover {
      transform: scale(1.1);
    }

    /* Featured Collections */
    .collections {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    .collection-item {
      position: relative;
      overflow: hidden;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
      transition: all 0.3s ease;
    }
    .collection-item img {
      width: 100%;
      height: auto;
      transition: all 0.3s ease;
    }
    .collection-item:hover img {
      transform: scale(1.1);
    }
    .collection-item .overlay {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      background: rgba(0, 0, 0, 0.7);
      color: white;
      padding: 1rem;
      opacity: 0;
      transition: all 0.3s ease;
    }
    .collection-item:hover .overlay {
      opacity: 1;
    }

    /* Mission Statement */
    .mission {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 2rem;
      background: rgba(10, 26, 47, 0.8);
    }
    .mission-text {
      max-width: 50%;
    }
    .mission-image {
      max-width: 50%;
    }
    .mission-image img {
      width: 100%;
      height: auto;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Wear the Universe, Find Your Light</h1>
    <p>Your journey is written in the stars.</p>
    <button>Explore the Cosmos</button>
  </section>

  <!-- Featured Collections -->
  <section class="collections">
    <div class="collection-item">
      <img src="https://via.placeholder.com/300x300?text=Mental+Health+Line" alt="Mental Health Line">
      <div class="overlay">Your scars are constellations.</div>
    </div>
    <div class="collection-item">
      <img src="https://via.placeholder.com/300x300?text=Astrology+Streetwear" alt="Astrology Streetwear">
      <div class="overlay">Align with your zodiac sign.</div>
    </div>
    <div class="collection-item">
      <img src="https://via.placeholder.com/300x300?text=Customizable+Cosmic" alt="Customizable Cosmic">
      <div class="overlay">Personalize your universe.</div>
    </div>
  </section>

  <!-- Mission Statement -->
  <section class="mission">
    <div class="mission-text">
      <h2>Twinfinity</h2>
      <p>Where cosmic art meets mental resilience. Every stitch carries stardust.</p>
    </div>
    <div class="mission-image">
      <img src="https://via.placeholder.com/400x300?text=Constellation+Art" alt="Constellation Art">
    </div>
  </section>

</body>
</html>
