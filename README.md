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

  /* Center the pricing table section */
  .price-table-wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .price-table {
    border-collapse: collapse;
    width: 80%;
    max-width: 700px;
    background-color: white;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    overflow: hidden;
  }
  .price-table th, .price-table td {
    border: 1px solid #ccc;
    padding: 15px;
    text-align: center;
  }
  .price-table th {
    background-color: #005b99;
    color: white;
    font-size: 18px;
  }
  .price-table td {
    background-color: #f9f9f9;
    font-size: 16px;
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

  /* Services section styling */
  .services-section {
    max-width: 800px;
    margin: auto;
  }
  .service-item {
    background-color: #f0f8ff;
    border: 1px solid #cce0ff;
    border-radius: 12px;
    padding: 20px;
    margin: 15px auto;
    text-align: center;
    font-size: 18px;
    box-shadow: 0 3px 6px rgba(0,0,0,0.08);
  }
  .service-item span {
    font-size: 26px;
    display: block;
    margin-bottom: 10px;
  }
    /* Form section */
  #book form {
    max-width: 500px;
    margin: 20px auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
    background-color: #f9f9f9;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }
  #book label {
    font-weight: bold;
    margin-bottom: 5px;
  }
  #book input, #book textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-size: 16px;
  }
  #book input[type="submit"] {
    background-color: #005b99;
    color: white;
    border: none;
    padding: 12px;
    cursor: pointer;
    font-size: 16px;
    border-radius: 8px;
    transition: background-color 0.3s;
  }
  #book input[type="submit"]:hover {
    background-color: #007acc;
  }
</style>

<section class="lightblue center">
  <h1>🧼 The01Bros</h1>
  <p>Your trusted local team for bin cleaning, snow removal, and duct care in <b>Burlington, Ontario</b>.</p>
  <a href="https://formspree.io/f/xnngzglz" class="button" target="_blank">📅 Book Online</a>
</section>

<section class="white">
  <h2 class="center">🧰 Our Services</h2>

  <div class="services-section">
    <div class="service-item"><span>🚮</span>Garbage Bin Cleaning – Sparkling clean and odor-free bins using eco-friendly detergents.</div>
    <div class="service-item"><span>♻️</span>Recycling Bin Cleaning – Keep your blue bins looking new and free of residue.</div>
    <div class="service-item"><span>🌿</span>Compost Bin Cleaning – Deep sanitize your compost bins to eliminate bacteria and smells.</div>
    <div class="service-item"><span>❄️</span>Snow Removal – Driveway and walkway clearing all winter long.</div>
    <div class="service-item"><span>🌬️</span>Duct Cleaning – Improve indoor air quality and efficiency.</div>
    <div class="service-item"><span>💳</span>Subscriptions – Monthly pass: <b>5 all-inclusive cleans per month</b>.</div>
    <div class="service-item"><span>🤝</span>Referrals – Refer a friend and get a <b>free cleaning for all 3 bins!</b></div>
    <div class="service-item"><span>✨</span>Deep Cleaning – For tough grime (prices double).</div>
  </div>
</section>

<section class="lightblue center">
  <h2>💰 Pricing</h2>
  <div class="price-table-wrapper">
    <table class="price-table">
      <tr><th>Service</th><th>Price</th></tr>
      <tr><td>Blue Bin Cleaning</td><td>$2.99</td></tr>
      <tr><td>Garbage Bin Cleaning</td><td>$4.99</td></tr>
      <tr><td>Compost Bin Cleaning</td><td>$9.99</td></tr>
      <tr><td>Package Deal (All 3)</td><td>$15.00</td></tr>
      <tr><td>Monthly Subscription (5 cleans/month)</td><td>$30.00</td></tr>
      <tr><td>Deep Cleaning</td><td>Double listed price</td></tr>
    </table>
  </div>
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

<section class="white center">
  <h2>📞 Contact Us</h2>
  <p>📧 <a href="mailto:the01bros@outlook.com">the01bros@outlook.com</a><br>
     📞 (289) 707 0312</p>
 
<!-- ✅ FORM SECTION -->
<section id="book" class="white center">
  <h2>📅 Book a Cleaning</h2>
  <form action="https://formspree.io/f/xnngzglz" method="POST">
    <label for="name">Full Name</label>
    <input type="text" name="name" id="name" required>

    <label for="email">Email Address</label>
    <input type="email" name="_replyto" id="email" required>

    <label for="service">Service Requested</label>
    <input type="text" name="service" id="service" placeholder="e.g., Garbage Bin Cleaning" required>

    <label for="message">Additional Details</label>
    <textarea name="message" id="message" rows="4" placeholder="Tell us anything else we should know..."></textarea>

    <input type="submit" value="Submit Booking Request">
  </form>
</section>

<section class="lightblue center">
  <p>© 2025 the01bros. All rights reserved.<br>
  “We clean it like we own it.” 🧢</p>
</section>

