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
            <a href="https://wa.me/918003550118" class="btn whatsapp" target="_blank">
              WhatsApp to Customize
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- COLLECTIONS -->
    <section id="collections" class="collections">
      <h2>Shop by Collection</h2>

      <div class="grid">
        <div class="box">
          <img src="/images/birthday-category.jpg" alt="Kids Birthday Outfits">
          <h3>Kids Birthday Outfits</h3>
          <p>Perfect outfits for first birthdays.</p>
        </div>

        <div class="box">
          <img src="/images/mother-daughter-category.jpg" alt="Mother Daughter Matching">
          <h3>Mother Daughter Matching</h3>
          <p>Elegant matching styles.</p>
        </div>

        <div class="box">
          <img src="/images/family-category.jpg" alt="Family Matching Outfits">
          <h3>Family Matching Outfits</h3>
          <p>Perfect for photos and events.</p>
        </div>

        <div class="box">
          <img src="/images/festive-category.jpg" alt="Festive Wear">
          <h3>Festive Wear</h3>
          <p>Comfortable festive outfits.</p>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="whatsapp-section">
      <h2>Need help with size or customization?</h2>
      <a href="https://wa.me/918003550118" class="btn whatsapp large" target="_blank">
        Chat on WhatsApp
      </a>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
      <p>© PinkBlueIndia. All rights reserved.</p>
    </footer>

  </div>
</template>

<script setup>
useHead({
  title: 'PinkBlueIndia | Kids Birthday & Family Matching Outfits',
  meta: [
    {
      name: 'description',
      content:
        'Shop handcrafted kids birthday outfits, mother daughter matching dresses and family matching clothing with worldwide delivery.'
    }
  ]
})
</script>

<style scoped>
.nav {
  border-bottom: 1px solid #eee;
  padding: 14px 20px;
}
.nav-inner {
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
}
.logo {
  font-weight: 700;
}
.nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #000;
}
.hero {
  height: 85vh;
  background: url('/images/hero-banner.jpg') center/cover no-repeat;
  position: relative;
}
.hero-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,.55);
  display: flex;
  align-items: center;
  justify-content: center;
}
.hero-content {
  color: #fff;
  text-align: center;
  max-width: 800px;
}
.hero-content h1 {
  font-size: 40px;
}
.hero-content p {
  margin: 20px 0;
}
.btn {
  padding: 14px 26px;
  border-radius: 8px;
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
  padding: 16px 32px;
}
.collections {
  padding: 60px 20px;
  text-align: center;
}
.grid {
  max-width: 1100px;
  margin: 40px auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 24px;
}
.box img {
  width: 100%;
  height: 320px;
  object-fit: cover;
  border-radius: 8px;
}
.footer {
  padding: 30px;
  text-align: center;
  background: #f5f5f5;
}
</style>
