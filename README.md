<!-- the01bros GitHub Pages main site -->
<style>
  body {
    font-family: 'Segoe UI', sans-serif;
    line-height: 1.6;
    margin: 0;
  }
  section {
    padding: 50px 20px;
  }
  .lightblue { background-color: #e6f2ff; }
  .white { background-color: #ffffff; }
  h1, h2, h3 { color: #005b99; }
  .center { text-align: center; }
  .price-table {
    border-collapse: collapse;
    margin: auto;
    width: 80%;
  }
  .price-table th, .price-table td {
    border: 1px solid #ccc;
    padding: 10px;
    text-align: center;
  }
  .price-table th {
    background-color: #005b99;
    color: white;
  }
  .button {
    background-color: #005b99;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 8px;
  }
  .button:hover {
    background-color: #007acc;
  }
  form {
    max-width: 500px;
    margin: auto;
    text-align: left;
  }
  input, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  input[type="submit"], button[type="submit"] {
    background-color: #005b99;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 8px;
    padding: 10px 20px;
  }
  input[type="submit"]:hover, button[type="submit"]:hover {
    background-color: #007acc;
  }

  /* ✅ New styling for services section */
  .services-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
    margin-top: 30px;
  }

  .service-card {
    background-color: #f7faff;
    border: 1px solid #d6e6f5;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.08);
    width: 280px;
    padding: 25px;
    text-align: center;
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .service-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 14px rgba(0,0,0,0.12);
  }

  .service-icon {
    font-size: 42px;
    display: block;
    margin-bottom: 12px;
  }

  .service-card h3 {
    color: #005b99;
    margin-bottom: 10px;
  }

  .service-card p {
    font-size: 15px;
    color: #333;
  }
</style>

<section class="lightblue center">
  <h1>🧼 The01Bros</h1>
  <p>Your trusted local team for bin cleaning, snow removal, and duct care in <b>Burlington, Ontario</b>.</p>
  <a href="#book" class="button">📅 Book Online</a>
</section>

<!-- ✅ Updated "Our Services" section -->
<section class="white center">
  <h2>🧰 Our Services</h2>

  <div class="services-container">
    <div class="service-card">
      <span class="service-icon">🚮</span>
      <h3>Garbage Bin Cleaning</h3>
      <p>Sparkling clean and odor-free bins using eco-friendly detergents.</p>
    </div>

    <div class="service-card">
      <span class="service-icon">♻️</span>
      <h3>Recycling Bin Cleaning</h3>
      <p>Keep your blue bins looking new and free of residue.</p>
    </div>

    <div class="service-card">
      <span class="service-icon">🌿</span>
      <h3>Compost Bin Cleaning</h3>
      <p>Deep sanitize your compost bins to eliminate bacteria and smells.</p>
    </div>

    <div class="service-card">
      <span class="service-icon">❄️</span>
      <h3>Snow Removal</h3>
      <p>Driveway and walkway clearing all winter long.</p>
    </div>

    <div class="service-card">
      <span class="service-icon">🌬️</span>
      <h3>Duct Cleaning</h3>
      <p>Improve indoor air quality and efficiency.</p>
    </div>

    <div class="service-card">
      <span class="service-icon">💳</span>
      <h3>Subscriptions</h3>
      <p>Monthly pass: <b>5 all-inclusive cleans per month</b> — perfect for busy households.</p>
    </div>

    <div class="service-card">
      <span class="service-icon">🤝</span>
      <h3>Referrals</h3>
      <p>Refer a friend and get a <b>free cleaning for all 3 bins!</b></p>
    </div>

    <div class="service-card">
      <span class="service-icon">✨</span>
      <h3>Deep Cleaning</h3>
      <p>For tough grime or buildup, our <b>deep clean service</b> is available (prices double).</p>
    </div>
  </div>
</section>

<section class="lightblue">
  <h2 class="center">💰 Pricing</h2>

  <table class="price-table">
    <tr><th>Service</th><th>Price</th></tr>
    <tr><td>Blue Bin Cleaning</td><td>$2.99</td></tr>
    <tr><td>Garbage Bin Cleaning</td><td>$4.99</td></tr>
    <tr><td>Compost Bin Cleaning</td><td>$9.99</td></tr>
    <tr><td>Package Deal (All 3)</td><td>$15.00</td></tr>
    <tr><td>Monthly Subscription (5 cleans/month)</td><td>$30.00</td></tr>
    <tr><td>Deep Cleaning</td><td>Double listed price</td></tr>
  </table>
</section>

<section class="white center">
  <h2>🕒 Hours of Operation</h2>
  <p><b>Monday – Friday:</b> 8:00 AM – 6:00 PM<br>
     <b>Saturday:</b> 9:00 AM – 4:00 PM<br>
     <b>Sunday:</b> Closed</p>
</section>

<section class="lightblue center">
  <h2>📍 Service Area</h2>
  <p>We proudly serve <b>Burlington, Ontario</b> and surrounding areas.</p>
  <a href="https://www.google.com/maps/place/Burlington,+Ontario" target="_blank">
    <img src="https://maps.googleapis.com/maps/api/staticmap?center=Burlington,Ontario&zoom=12&size=600x300&key=YOUR_API_KEY" 
         alt="Map of Burlington, Ontario" style="border-radius:12px;max-width:90%;"/>
  </a>
  <p><i>Click the map to open on Google Maps.</i></p>
</section>

<!-- ✅ Booking Form -->
<section id="book" class="white center">
  <h2>📅 Book a Cleaning</h2>
<form
  action="https://formspree.io/f/xnngzglz"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>

<section class="lightblue center">
  <p>© 2025 the01bros. All rights reserved.<br>
  “We clean it like we own it.” 🧢</p>
</section>
