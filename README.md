<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Tadaco Lubricants and Petroleums</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0; padding: 0;
    color: #333;
    background: #f9f9f9;
  }
  header {
    background: #004080;
    color: white;
    padding: 15px 30px;
    position: sticky;
    top: 0;
    z-index: 100;
  }
  header h1 {
    margin: 0;
    font-size: 1.8rem;
  }
  nav {
    margin-top: 8px;
  }
  nav a {
    color: white;
    margin-right: 20px;
    text-decoration: none;
    font-weight: bold;
  }
  nav a:hover {
    text-decoration: underline;
  }
  .hero {
    background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
    color: white;
    text-align: center;
    padding: 120px 20px;
  }
  .hero h2 {
    font-size: 2.8rem;
    margin-bottom: 10px;
    text-shadow: 2px 2px 6px #000;
  }
  .hero button {
    background: #ffcc00;
    border: none;
    padding: 15px 30px;
    font-size: 1rem;
    font-weight: bold;
    cursor: pointer;
    border-radius: 5px;
    box-shadow: 0 3px 6px rgba(0,0,0,0.2);
  }
  .hero button:hover {
    background: #e6b800;
  }
  section {
    max-width: 900px;
    margin: 50px auto;
    padding: 0 20px;
  }
  section h2 {
    color: #004080;
    border-bottom: 3px solid #004080;
    padding-bottom: 8px;
  }
  .about p, .products p, .certifications p {
    font-size: 1.1rem;
    line-height: 1.6;
  }
  .products ul {
    list-style: none;
    padding-left: 0;
  }
  .products li {
    background: #e0e7f2;
    margin-bottom: 12px;
    padding: 15px;
    border-radius: 5px;
  }
  .contact form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
  }
  .contact label {
    margin: 10px 0 5px;
  }
  .contact input, .contact textarea {
    padding: 10px;
    font-size: 1rem;
    border-radius: 4px;
    border: 1px solid #ccc;
  }
  .contact textarea {
    resize: vertical;
    min-height: 100px;
  }
  .contact button {
    margin-top: 15px;
    background: #004080;
    color: white;
    border: none;
    padding: 12px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 4px;
  }
  .contact button:hover {
    background: #003060;
  }
  footer {
    background: #222;
    color: #ccc;
    text-align: center;
    padding: 15px 20px;
    margin-top: 40px;
  }
  @media (max-width: 600px) {
    .hero h2 {
      font-size: 2rem;
    }
    nav a {
      display: block;
      margin-bottom: 8px;
    }
    .contact form {
      width: 100%;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Tadaco Lubricants and Petroleums</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products & Services</a>
    <a href="#certifications">Certifications</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">
  <h2>Powering Progress. Fueling Namibia’s Future.</h2>
  <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Get a Quote</button>
</section>

<section class="about" id="about">
  <h2>About Us</h2>
  <p>
    Founded in 2021, Tadaco Lubricants and Petroleums is a Namibian-owned company based in Windhoek, dedicated to providing reliable, high-quality petroleum products across the country. Our mission is to fuel progress with integrity, safety, and commitment.
  </p>
  <p><strong>Director:</strong> Naftal Kashikuka</p>
  <p><strong>Location:</strong> Taurus Street, Dorado Park, Windhoek | Storage: Brahman Industrial Warehouse, Northern Industry, Windhoek</p>
</section>

<section class="products" id="products">
  <h2>Products & Services</h2>
  <ul>
    <li><strong>Diesel Supply:</strong> Bulk delivery, quality-tested, meeting Namibia’s industry standards.</li>
    <li><strong>Petrol Supply:</strong> Premium petrol options with competitive pricing.</li>
    <li><strong>Automotive Lubricants:</strong> Suitable for cars, trucks, and machinery to improve performance and longevity.</li>
    <li><strong>Industrial Lubricants:</strong> Designed for heavy-duty equipment and industrial plants.</li>
  </ul>
  <p>Our storage facilities cover 10,000–25,000 sq ft, ensuring reliable stock availability and supply chain efficiency.</p>
</section>

<section class="certifications" id="certifications">
  <h2>Certifications & Compliance</h2>
  <p><strong>Company Registration:</strong> CC/2021/03729</p>
  <p><strong>Environmental Assessment:</strong> In progress</p>
  <p><strong>Environmental Clearance Certificate:</strong> Pending, currently being processed with the Ministry of Mines and Energy</p>
  <p><strong>Safety Protocols:</strong> Our storage and handling meet Namibian petroleum safety regulations.</p>

<section class="blog" id="blog">
  <h2>Blog</h2>
  <p>Coming soon: Industry news, tips on lubricant storage, fuel safety guidelines, and Tadaco announcements.</p>
</section>

<section class="contact" id="contact">
  <h2>Contact Us</h2>
  <form onsubmit="event.preventDefault(); alert('Thank you for your message! We will get back to you soon.'); this.reset();">
    <label for="name">Name</label>
    <input id="name" name="name" required />
    <label for="email">Email</label>
    <input id="email" name="email" type="email" required />
    <label for="phone">Phone</label>
    <input id="phone" name="phone" required />
    <label for="message">Message</label>
    <textarea id="message" name="message" required></textarea>
    <button type="submit">Send Message</button>
  </form>
  <p><strong>Phone:</strong> +264814355985</p>
  <p><strong>Email:</strong> tadacoinvest@yahoo.com</p>
  <p><strong>Address:</strong> Taurus Street, Dorado Park, Windhoek</p>
  <p><strong>Postal:</strong> 10575 Khomasdal, Windhoek, Namibia</p>
</section>

<footer>
  &copy; 2025 Tadaco Lubricants and Petroleums — All rights reserved.
  <!-- Add this new section right before the footer -->

<section class="business-plan" id="business-plan">
  <h2>Investor Relations / Business Plan</h2>
  <p>
    Tadaco Lubricants & Petroleums’ comprehensive business plan is now available for investors, partners, and stakeholders. 
    This document includes detailed operations, financial projections, crude oil recycling & refining expansion plans, 
    and Namibia-specific market analysis.
  </p>
  <p>
    <strong>Key Highlights:</strong>
    <ul>
      <li>Refinery & recycled petroleum operations in Windhoek</li>
      <li>City of Windhoek feedstock contract projections</li>
      <li>5-year financial projections in Namibian Dollars</li>
      <li>CAPEX, OPEX, and EBITDA analysis</li>
      <li>Compliance, environmental, and safety plans</li>
    </ul>
  </p>
  <a 
</style>
</footer>


    
