<template>
  <main class="container">

    <!-- HERO -->
    <section class="hero">
      <h1>Beautiful Matching Outfits for Kids & Families</h1>
      <p class="subtitle">
        Handcrafted birthday outfits, family matching clothing and festive wear.
        Premium quality. Custom sizes. Worldwide support.
      </p>

      <div class="cta-group">
        <a href="https://www.pinkblueindia.com" class="btn primary">
          Shop Collection
        </a>
        <a
          href="https://wa.me/91XXXXXXXXXX?text=Hi%20PinkBlueIndia,%20I%20want%20to%20buy%20a%20kids%20outfit"
          class="btn whatsapp"
          target="_blank"
        >
          WhatsApp to Customize
        </a>
      </div>
    </section>

    <!-- TRUST STRIP -->
    <section class="trust">
      <ul>
        <li>Handmade with Care</li>
        <li>Premium Fabrics</li>
        <li>Custom Sizing</li>
        <li>Fast Delivery</li>
        <li>WhatsApp Support</li>
      </ul>
    </section>

    <!-- CATEGORIES -->
    <section class="categories">
      <h2>Shop by Category</h2>

      <div class="grid">
        <div class="card">
          <h3>Kids Birthday Outfits</h3>
          <p>Perfect outfits for first birthdays and celebrations.</p>
          <a href="https://www.pinkblueindia.com" class="link">View Collection</a>
        </div>

        <div class="card">
          <h3>Mother Daughter Matching</h3>
          <p>Elegant matching dresses for special moments.</p>
          <a href="https://www.pinkblueindia.com" class="link">View Collection</a>
        </div>

        <div class="card">
          <h3>Family Matching Outfits</h3>
          <p>Coordinated looks for photoshoots and events.</p>
          <a href="https://www.pinkblueindia.com" class="link">View Collection</a>
        </div>

        <div class="card">
          <h3>Festive Wear for Kids</h3>
          <p>Comfortable outfits for festivals and occasions.</p>
          <a href="https://www.pinkblueindia.com" class="link">View Collection</a>
        </div>
      </div>
    </section>

    <!-- BRAND STORY -->
    <section class="about">
      <h2>Why Parents Choose PinkBlueIndia</h2>
      <p>
        PinkBlueIndia creates thoughtfully designed outfits for kids and families.
        Every piece is handmade with attention to comfort, fit and timeless style.
        Custom sizing and personal support make every order special.
      </p>
    </section>

    <!-- WHATSAPP CTA -->
    <section class="whatsapp-cta">
      <h2>Need help with size or customization?</h2>
      <p>
        Chat directly with our team on WhatsApp for size guidance,
        custom orders and delivery questions.
      </p>

      <a
        href="https://wa.me/91XXXXXXXXXX?text=Hi%20PinkBlueIndia,%20I%20need%20help%20with%20an%20order"
        class="btn whatsapp large"
        target="_blank"
      >
        Chat on WhatsApp
      </a>
    </section>

    <!-- REVIEWS -->
    <section class="reviews">
      <h2>What Parents Say</h2>

      <blockquote>
        “Quality is amazing and fitting was perfect. WhatsApp support helped a lot.”
        <span>— Neha, Bangalore</span>
      </blockquote>

      <blockquote>
        “My daughter’s birthday outfit looked exactly like the photos.”
        <span>— Pooja, Jaipur</span>
      </blockquote>

      <blockquote>
        “Beautiful fabric quality and very responsive team.”
        <span>— Ritu, Delhi</span>
      </blockquote>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
      <div class="footer-top">
        <div>
          <strong>PinkBlueIndia</strong>
          <p>Handmade kids & family outfits crafted with love.</p>
        </div>

        <div>
          <strong>Quick Links</strong>
          <a href="https://www.pinkblueindia.com">Shop</a>
          <a href="https://www.pinkblueindia.com">Birthday Outfits</a>
          <a href="https://www.pinkblueindia.com">Family Matching</a>
        </div>

        <div>
          <strong>Support</strong>
          <a href="https://wa.me/91XXXXXXXXXX" target="_blank">WhatsApp</a>
          <a href="#">Shipping</a>
          <a href="#">Returns</a>
        </div>
      </div>

      <div class="payments">
        <p>Secure Payments Accepted</p>
        <span>Visa • MasterCard • RuPay • UPI • Google Pay • PhonePe • Paytm • COD</span>
      </div>

      <div class="copyright">
        © PinkBlueIndia. All rights reserved.
      </div>
    </footer>

  </main>
</template>

<script setup>
useHead({
  title: 'PinkBlueIndia | Kids Birthday Outfits & Family Matching Clothing',
  meta: [
    {
      name: 'description',
      content:
        'Shop handcrafted kids birthday outfits, mother daughter matching dresses and family matching clothing. Premium quality, custom sizing and easy WhatsApp support worldwide.'
    },
    {
      property: 'og:title',
      content: 'PinkBlueIndia | Kids Birthday & Family Matching Outfits'
    },
    {
      property: 'og:description',
      content:
        'Handcrafted kids and family matching outfits for birthdays and special occasions. Custom sizing with WhatsApp support.'
    }
  ]
})
</script>

<style scoped>
.container {
  font-family: system-ui, sans-serif;
  line-height: 1.6;
  color: #222;
}

.hero {
  padding: 60px 20px;
  text-align: center;
}

.subtitle {
  max-width: 640px;
  margin: 16px auto;
}

.cta-group {
  margin-top: 24px;
}

.btn {
  display: inline-block;
  margin: 8px;
  padding: 14px 22px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
}

.primary {
  background: #000;
  color: #fff;
}

.whatsapp {
  background: #25d366;
  color: #fff;
}

.large {
  padding: 16px 28px;
}

.trust ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 16px;
  list-style: none;
  padding: 20px;
}

.categories {
  padding: 40px 20px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  border: 1px solid #eee;
  padding: 20px;
}

.link {
  display: inline-block;
  margin-top: 10px;
  color: #000;
  font-weight: 600;
}

.about,
.whatsapp-cta,
.reviews {
  padding: 40px 20px;
  text-align: center;
}

.reviews blockquote {
  max-width: 600px;
  margin: 20px auto;
  font-style: italic;
}

.reviews span {
  display: block;
  margin-top: 8px;
  font-style: normal;
  font-weight: 600;
}

.footer {
  background: #f8f8f8;
  padding: 30px 20px;
}

.footer-top {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.footer a {
  display: block;
  margin-top: 6px;
  color: #000;
  text-decoration: none;
}

.payments {
  text-align: center;
  margin-top: 20px;
}

.copyright {
  text-align: center;
  margin-top: 16px;
  font-size: 14px;
}
</style>
