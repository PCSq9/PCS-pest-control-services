
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PCS - Pest Control Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background-color: white;
      color: black;
      padding: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
      border-bottom: 1px solid #ccc;
    }
    header img {
      height: 120px; /* Increased logo size */
      margin-right: 20px;
    }
    .header-text {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
    }
    .header-text h1 {
      margin: 0;
      font-size: 32px;
    }
    .header-text span {
      font-size: 20px;
      color: #555;
    }
    .section {
      padding: 30px 20px;
      background: white;
      margin: 20px;
      border-radius: 8px;
    }
    .section img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    .button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 12px 24px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background-color: #2d2d2d;
      color: white;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

  <header>
    <img src="pcs logo.jpeg" alt="PCS Logo" />
    <div class="header-text">
      <h1>PCS</h1>
      <span>Pest Control Services</span>
    </div>
  </header>

  <div class="section">
    <h2>About Us</h2>
    <p>
      PCS is a trusted American  pest control company, dedicated to protecting homes and businesses from unwanted pests. With a team of licensed professionals and eco-safe methods, we deliver fast, reliable, and long-lasting pest management solutions across the country.
      At PCS Pest Control Services, we are committed to providing reliable, eco-friendly, and professional pest management solutions across louisiana , California , los angeles. Our experienced team specializes in the safe removal and prevention of common pests such as termites, rodents, cockroaches, ants, and spiders in addition we provide general maintenance services. We serve both residential and commercial properties, using advanced techniques and environmentally safe products to ensure long-lasting protection. At PCS, customer satisfaction is our top priority, which is why we offer flexible scheduling, thorough inspections, and tailored treatment plans to suit every need. Whether it's a one-time service or a long-term maintenance plan, PCS is your trusted partner in creating pest-free environments.
    </p>
  </div>

  <div class="section">
    <h2>Our Services</h2>
    <ul>
      <li>Home Pest Control</li>
      <li>Commercial Pest Management</li>
      <li>Termite Inspection & Treatment</li>
      <li>Rodent and Cockroach Removal</li>
      <li>Preventive Treatments</li>
    </ul>
  </div>

  <div class="section">
    <h2> </h2>
    <img src="p1.jpg" alt="PCS Action 1" />
    <img src="p2.jpg" alt="PCS Action 2" />
  </div>

  <div class="section">
    <h2>Contact Us</h2>
    <p>📧 Email: <a href="mailto:carla.miller.pcs@gmail.com">carla.miller.pcs@gmail.com</a></p>
    <button class="button" onclick="contactMessage()">Send Inquiry</button>
  </div>

  <footer>
    &copy; 2025 PCS USA - All rights reserved.
  </footer>

  <script>
    function contactMessage() {
      alert("Thank you for reaching out to PCS! We will reply to your email shortly.");
    }
  </script>

</body>
</html>
