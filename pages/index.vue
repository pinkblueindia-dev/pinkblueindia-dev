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
            Handcrafted birthday outfits, family matching sets and festive wear.
            Premium fabrics. Custom sizes. Worldwide shipping.
          </p>
          <div class="hero-cta">
            <a href="#collections" class="btn primary">Shop Collections</a>
            <a
              href="https://wa.me/918003550118"
              target="_blank"
              class="btn whatsapp"
            >
              WhatsApp to Customize
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- COLLECTIONS -->
    <section id="collections" class="collections">
      <h2>Shop by Collection</h2>

      <div class="collection-grid">

        <div class="collection-card">
          <img
            src="https://pinkblueindia.netlify.app/images/birthday-category.jpg"
            alt="Kids Birthday Outfits"
          />
          <div class="card-content">
            <h3>Kids Birthday Outfits</h3>
            <p>Perfect outfits for first birthdays and celebrations.</p>
          </div>
        </div>

        <div class="collection-card">
          <img
            src="https://pinkblueindia.netlify.app/images/family-category.jpg"
            alt="Family Matching Outfits"
          />
          <div class="card-content">
            <h3>Family Matching Outfits</h3>
            <p>Coordinated looks for photos, events and special days.</p>
          </div>
        </div>

      </div>
    </section>

    <!-- WHY US -->
    <section id="why" class="why">
      <h2>Why PinkBlueIndia</h2>
      <p>
        Every outfit is handcrafted with care. We focus on comfort, fit and
        premium fabrics. Custom sizing and direct WhatsApp support make every
        order personal.
      </p>
    </section>

    <!-- WHATSAPP CTA -->
    <section id="contact" class="cta">
      <h2>Need help with size or customization?</h2>
      <p>Chat directly with our team for quick assistance.</p>
      <a
        href="https://wa.me/918003550118"
        target="_blank"
        class="btn whatsapp large"
      >
        Chat on WhatsApp
      </a>
    </section>
<template>
  <div>
    <slot />
    <Footer />
  </div>
</template>


  </div>
</template>

<script setup>
useHead({
  title: 'PinkBlueIndia | Kids Birthday & Family Matching Outfits',
  meta: [
    {
      name: 'description',
      content:
        'Shop handcrafted kids birthday outfits and family matching clothing. Premium fabrics, custom sizing and WhatsApp support.'
    }
  ]
})
</script>

<style scoped>
/* NAV */
.nav {
  background: #fff;
  border-bottom: 1px solid #eee;
}
.nav-inner {
  max-width: 1200px;
  margin: auto;
  padding: 16px 20px;
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

/* HERO */
.hero {
  height: 85vh;
  background-image: url('https://pinkblueindia.netlify.app/images/hero-banner.jpg');
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
  text-align: center;
  color: #fff;
  max-width: 800px;
  padding: 20px;
}
.hero-content h1 {
  font-size: 42px;
  margin-bottom: 16px;
}
.hero-content p {
  font-size: 18px;
  margin-bottom: 28px;
}

/* BUTTONS */
.btn {
  padding: 14px 26px;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  display: inline-block;
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
.hero-cta {
  display: flex;
  gap: 14px;
  justify-content: center;
  flex-wrap: wrap;
}

/* COLLECTIONS */
.collections {
  padding: 70px 20px;
  text-align: center;
}
.collection-grid {
  max-width: 1100px;
  margin: 40px auto 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 30px;
}
.collection-card {
  border: 1px solid #eee;
  overflow: hidden;
}
.collection-card img {
  width: 100%;
  height: 320px;
  object-fit: cover;
}
.card-content {
  padding: 20px;
}

/* WHY */
.why {
  padding: 70px 20px;
  background: #fafafa;
  text-align: center;
}
.why p {
  max-width: 800px;
  margin: auto;
}

/* CTA */
.cta {
  padding: 70px 20px;
  text-align: center;
}

/* FOOTER */
.footer {
  padding: 30px 20px;
  background: #f5f5f5;
  text-align: center;
  font-size: 14px;
}

/* MOBILE */
@media (max-width: 768px) {
  .hero-content h1 {
    font-size: 28px;
  }
  .collection-card img {
    height: 240px;
  }
}
</style>
