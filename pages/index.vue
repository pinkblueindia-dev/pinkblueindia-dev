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
        <h1>Beautiful Matching Outfits for Kids & Families</h1>
        <p>
          Handcrafted birthday outfits and family matching clothing.
          Premium quality. Custom sizes. Worldwide support.
        </p>

        <div class="hero-cta">
          <a href="https://www.pinkblueindia.com" class="btn primary">
            Shop Collection
          </a>
          <a
            href="https://wa.me/918003550118?text=Hi%20PinkBlueIndia,%20I%20want%20to%20buy%20a%20kids%20outfit"
            class="btn whatsapp"
            target="_blank"
          >
            WhatsApp to Customize
          </a>
        </div>
      </div>
    </section>

    <!-- TRUST -->
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
          <p>Perfect looks for first birthdays and celebrations.</p>
        </div>

        <div class="box">
          <h3>Mother Daughter Matching</h3>
          <p>Elegant matching dresses for special moments.</p>
        </div>

        <div class="box">
          <h3>Family Matching Outfits</h3>
          <p>Coordinated outfits for photos and events.</p>
        </div>

        <div class="box">
          <h3>Festive Wear</h3>
          <p>Comfortable styles for festive occasions.</p>
        </div>
      </div>
    </section>

    <!-- WHY US -->
    <section id="why" class="why">
      <h2>Why PinkBlueIndia</h2>
      <p>
        We create thoughtfully designed outfits for kids and families.
        Every piece is handmade with attention to comfort, fit and timeless style.
        Custom sizing and personal WhatsApp support make every order special.
      </p>
    </section>

    <!-- WHATSAPP CTA -->
    <section id="contact" class="whatsapp">
      <h2>Need help with size or customization?</h2>
      <p>Chat directly with us for quick assistance and custom orders.</p>
      <a
        href="https://wa.me/918003550118?text=Hi%20PinkBlueIndia,%20I%20need%20help%20with%20an%20order"
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
          <p>Handcrafted kids & family outfits.</p>
        </div>

        <div>
          <strong>Follow Us</strong>
          <p>Instagram • Facebook • Pinterest</p>
        </div>

        <div>
          <strong>Payments</strong>
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
    },
    {
      property: 'og:title',
      content: 'PinkBlueIndia | Kids & Family Matching Outfits'
    },
    {
      property: 'og:description',
      content:
        'Beautifully handcrafted kids and family matching outfits for birthdays and special moments.'
    }
  ]
})
</script>

<style scoped>
body {
  margin: 0;
}

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
  font-weight: 700;
  font-size: 18px;
}

.nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #000;
}

.hero {
  height: 85vh;
  background: url('/images/hero.jpg') center / cover no-repeat;
  position: relative;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.45);
  color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 20px;
}

.hero h1 {
  max-width: 720px;
  font-size: 36px;
}

.hero p {
  max-width: 620px;
  margin: 16px 0;
}

.btn {
  padding: 14px 22px;
  margin: 6px;
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

.trust {
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 20px;
  background: #fafafa;
  flex-wrap: wrap;
}

.collections,
.why,
.whatsapp {
  padding: 50px 20px;
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
  padding: 20px;
}

.footer {
  background: #f5f5f5;
  padding: 30px 20px;
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
</style>
