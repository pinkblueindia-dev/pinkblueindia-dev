<template>
  <div>

    <!-- NAVBAR -->
    <header class="nav">
      <div class="nav-inner">
        <div class="logo">PinkBlueIndia</div>
        <nav>
          <a href="#collections">Collections</a>
          <a href="#why">Why Us</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>
    </header>

    <!-- HERO -->
    <section class="hero">
      <div class="hero-overlay">
        <div class="hero-content">
          <h1>Beautiful Matching Outfits for Kids & Families</h1>

          <p>
            Handcrafted birthday outfits and family matching clothing.
            Premium quality, custom sizes, worldwide delivery.
          </p>

          <div class="hero-cta">
            <a href="https://www.pinkblueindia.com" class="btn primary">
              Shop Collection
            </a>

            <a
              href="https://wa.me/91XXXXXXXXXX"
              class="btn whatsapp"
              target="_blank"
            >
              WhatsApp to Customize
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- TRUST STRIP -->
    <section class="trust">
      <span>Handmade</span>
      <span>Premium Fabrics</span>
      <span>Custom Sizes</span>
      <span>Fast Delivery</span>
      <span>WhatsApp Support</span>
    </section>

    <!-- COLLECTIONS -->
    <section id="collections" class="collections">
      <h2>Shop by Collection</h2>

      <div class="grid">
        <div class="box">
          <h3>Kids Birthday Outfits</h3>
          <p>Perfect outfits for first birthdays and celebrations.</p>
        </div>

        <div class="box">
          <h3>Mother Daughter Matching</h3>
          <p>Elegant matching styles for special moments.</p>
        </div>

        <div class="box">
          <h3>Family Matching Outfits</h3>
          <p>Coordinated looks for photos and events.</p>
        </div>

        <div class="box">
          <h3>Festive Wear</h3>
          <p>Comfortable outfits for festive occasions.</p>
        </div>
      </div>
    </section>

    <!-- WHY US -->
    <section id="why" class="why">
      <h2>Why PinkBlueIndia</h2>
      <p>
        Every outfit is handcrafted with care, keeping comfort and fit in mind.
        We offer custom sizing, premium fabrics and direct WhatsApp support
        so every order feels personal.
      </p>
    </section>

    <!-- WHATSAPP CTA -->
    <section id="contact" class="whatsapp-section">
      <h2>Need help with size or customization?</h2>
      <p>Chat with us directly for quick assistance.</p>

      <a
        href="https://wa.me/91XXXXXXXXXX"
        class="btn whatsapp large"
        target="_blank"
      >
        Chat on WhatsApp
      </a>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
      <div class="footer-grid">
        <div>
          <strong>PinkBlueIndia</strong>
          <p>Handcrafted kids & family matching outfits.</p>
        </div>

        <div>
          <strong>Social</strong>
          <p>Instagram • Facebook • Pinterest</p>
        </div>

        <div>
          <strong>Payments Accepted</strong>
          <p>Visa • MasterCard • RuPay • UPI • GPay • PhonePe • COD</p>
        </div>
      </div>

      <div class="copy">
        © PinkBlueIndia. All rights reserved.
      </div>
    </footer>

  </div>
</template>

<script setup>
useHead({
  title: 'PinkBlueIndia | Kids Birthday Outfits & Family Matching Clothing',
  meta: [
    {
      name: 'description',
      content:
        'Shop handcrafted kids birthday outfits, mother daughter matching dresses and family matching clothing. Premium quality, custom sizing and WhatsApp support worldwide.'
    }
  ]
})
</script>

<style scoped>
.nav {
  background: #fff;
  border-bottom: 1px solid #eee;
}

.nav-inner {
  max-width: 1200px;
  margin: auto;
  padding: 14px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 18px;
  font-weight: 700;
}

.nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #000;
}

.hero {
  height: 85vh;
  background-image: url('/images/hero.jpg');
  background-size: cover;
  background-position: center;
  position: relative;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.55);
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-content {
  max-width: 900px;
  text-align: center;
  color: #fff;
  padding: 20px;
}

.hero-content h1 {
  font-size: 42px;
  line-height: 1.2;
  margin-bottom: 16px;
}

.hero-content p {
  font-size: 18px;
  line-height: 1.6;
  max-width: 650px;
  margin: 0 auto 28px;
}

.hero-cta {
  display: flex;
  gap: 14px;
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  padding: 14px 26px;
  border-radius: 8px;
  font-weight: 600;
  text-decoration: none;
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
  padding: 16px 32px;
}

.trust {
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 18px;
  background: #fafafa;
  flex-wrap: wrap;
}

.collections,
.why,
.whatsapp-section {
  padding: 60px 20px;
  text-align: center;
}

.grid {
  max-width: 1000px;
  margin: 30px auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.box {
  border: 1px solid #eee;
  padding: 24px;
}

.footer {
  background: #f5f5f5;
  padding: 40px 20px;
}

.footer-grid {
  max-width: 1000px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.copy {
  text-align: center;
  margin-top: 20px;
  font-size: 14px;
}

@media (max-width: 768px) {
  .hero-content h1 {
    font-size: 28px;
  }

  .hero-content p {
    font-size: 16px;
  }
}
</style>
