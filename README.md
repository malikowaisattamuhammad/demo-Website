# demo-Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IDARA AL-KHAIR</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
    }

    body {
  background-size: cover;
  color: #444;
  line-height: 1.6;
  padding: 20px;
}
  

    header {
      text-align: center;
      padding: 2rem 0;
      background: #e0e5ec;
      border-radius: 25px;
      box-shadow: 10px 10px 30px #bec3c9, -10px -10px 30px #ffffff;
      margin-bottom: 2rem;
    }

    header h1 {
      font-size: 2rem;
      color: #333;
    }

    .container {
      max-width: 1000px;
      margin: auto;
    }
    
nav {
  margin-right: 25px;
}

nav ul {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
  margin-left: 530px;
}

nav ul li {
  margin-left: 25px;
}

nav a {
  color:#222;
  text-decoration: none;
  font-weight: 600;
  font-size: 16px;
  transition: color 0.3s ease-in-out;
  text-align: center;

}

nav a:hover {
  color: #ffbf00;
}

    /* Hero */
    .hero {
  height: 70vh;
  display: flex;
  align-items: center;
  color: white;
  text-align: center;
}
/*before and after*/
.ba-container {
  position: relative;
  width: 100%;
  max-width: 700px;
  margin: 40px auto;
  overflow: hidden;
  border-radius: 12px;
  box-shadow: 5px 5px 15px rgba(0,0,0,0.2);
}


.ba-img {
  display: block;
  width: 100%;
  height: auto;
}

.ba-after {
  position: absolute;
  top: 0;
  left: 0;
  width: 50%;
  overflow: hidden;
  height: 100%;
  transition: width 0.2s ease;
}

.ba-slider {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 4px;
  height: 100%;
  background: #ffffff;
  cursor: ew-resize;
  z-index: 2;
}

.ba-label {
  position: absolute;
  top: 10px;
  background: rgba(0, 0, 0, 0.6);
  color: #fff;
  padding: 4px 10px;
  border-radius: 10px;
  font-size: 14px;
  z-index: 3;
}

.before-label {
  left: 10px;
}

.after-label {
  right: 10px;
}





.hero .container {
  background: rgba(0, 0, 0, 0.5);
  padding: 30px;
  border-radius: 10px;
}

.btn {
  background: #ff9800;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  display: inline-block;
  margin-top: 20px;
  border-radius: 5px;
  transition: background 0.3s ease-in-out;
}

.btn:hover {
  background: #e67e00;
}

    .section {
      background: #e0e5ec;
      border-radius: 20px;
      box-shadow: 10px 10px 30px #bec3c9, -10px -10px 30px #ffffff;
      padding: 2rem;
      margin-bottom: 2rem;
    }

    .section h2 {
      margin-bottom: 1rem;
      font-size: 1.5rem;
      color: #222;
    }

    .section p {
      color: #555;
      font-size: 15px;
    }

    .program-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1rem;
    }

    .program {
      background: #e0e5ec;
      border-radius: 15px;
      padding: 1rem;
      box-shadow: inset 5px 5px 10px #bec3c9,
                  inset -5px -5px 10px #ffffff;
    }

    .program h3 {
      font-size: 1.1rem;
      margin-bottom: 0.5rem;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    input, textarea {
      padding: 0.7rem;
      border-radius: 10px;
      border: none;
      background: #e0e5ec;
      box-shadow: inset 3px 3px 6px #bec3c9,
                  inset -3px -3px 6px #ffffff;
      font-size: 14px;
      color: #555;
    }

    input:focus, textarea:focus {
      outline: none;
      box-shadow: inset 2px 2px 5px #bec3c9,
                  inset -2px -2px 5px #ffffff;
    }

    button {
      padding: 0.8rem;
      border-radius: 15px;
      border: none;
      background: #e0e5ec;
      box-shadow: 5px 5px 10px #bec3c9,
                  -5px -5px 10px #ffffff;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
      color: #333;
    }

    button:hover {
      box-shadow: 3px 3px 8px #bec3c9,
                  -3px -3px 8px #ffffff;
    }

    footer {
      text-align: center;
      padding: 1rem;
      font-size: 13px;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    
    <img src="idaraalkhair0-black-logo.png" alt="IDARA AL-KHAIR Logo" style="max-width: 10%; height: 20px;; margin-right:auto ;" /><h1>IDARA AL-KHAIR</h1>
    <p>Empowering the Future Through Education & Welfare</p>
    <br>
     </div>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#programs">Programs</a></li>
          <li><a href="#donate">Donate</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
  <!--before and after-->
<!-- Transformation Section -->
<section class="section">
  <h2 style="text-align:center; margin-bottom: 1rem;">See the Impact</h2>
  <div class="ba-container" id="slider-container">
    <img src="before.jpg" alt="Before" class="ba-img">
    <div class="ba-after" id="after-img">
      <img src="after.jpeg" alt="After" class="ba-img">
    </div>
    <div class="ba-slider" id="slider-bar"></div><h3 style=margin-right:100px;>slide bar to left/right</h3>
        <div class="ba-label before-label">Before</div>
    <div class="ba-label after-label">After</div>
  </div>
</section>


    <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="container">
      <h1>Welcome to Idara Al-Khair</h1>
      <p>Empowering underprivileged children through education, care and support.</p>
      <a href="#donate" class="btn">Donate Now</a>
    </div>
  </section>

  <div class="container">
    <section class="section">
      <h2>About Us</h2>
      <p>IDARA AL-KHAIR is a non-profit educational welfare organization dedicated to uplifting underprivileged communities through quality education, basic healthcare, and social support. We believe in building a brighter tomorrow by educating children and empowering families.</p>
    </section>

    <section class="section">
      <h2>Our Mission</h2>
      <p>Our mission is to provide accessible and affordable education to all children, especially those in marginalized areas. We run various programs to improve literacy, healthcare, vocational training, and social awareness.</p>
    </section>

    <section class="section">
      <h2>Our Programs</h2>
      <div class="program-list">
        <div class="program">
          <h3>Free Schooling</h3>
          <p>We provide free primary and secondary education to children from low-income families.</p>
        </div>
        <div class="program">
          <h3>Vocational Training</h3>
          <p>Training youth in skills like tailoring, computing, and mechanics to promote self-employment.</p>
        </div>lll
        <div class="program">
          <h3>Health Camps</h3>
          <p>Regular medical camps and awareness programs for poor communities.</p>
        </div>
        <div class="program">
          <h3>Ramzan Ration Drive</h3>
          <p>Food and ration packages for needy families during the month of Ramzan.</p>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>Contact Us</h2>
      <form onsubmit="submitContactForm(event)">
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </div>

  <footer>
    &copy; 2025 IDARA AL-KHAIR. All rights reserved.
  </footer>

  <script>
    function submitContactForm(e) {
      e.preventDefault();
      alert("Thank you! Your message has been sent.");
    }
  </script>
  <script>
  const slider = document.getElementById("slider-bar");
  const afterImg = document.getElementById("after-img");
  const container = document.getElementById("slider-container");

  let isDragging = false;

  slider.addEventListener("mousedown", () => isDragging = true);
  document.addEventListener("mouseup", () => isDragging = false);

  document.addEventListener("mousemove", (e) => {
    if (!isDragging) return;

    const rect = container.getBoundingClientRect();
    let offsetX = e.clientX - rect.left;

    offsetX = Math.max(0, Math.min(offsetX, rect.width));

    slider.style.left = offsetX + "px";
    afterImg.style.width = offsetX + "px";
  });
</script>

</body>

</html>
