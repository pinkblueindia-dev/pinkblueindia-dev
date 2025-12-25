<template>
  <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-content">
      <h1>Handmade Kids & Family Outfits</h1>
      <p>Birthday, festive & matching outfits made with love</p>
      <a
        href="https://wa.me/919999999999"
        class="cta-btn"
        target="_blank"
      >
        Shop on WhatsApp
      </a>
    </div>
  </section>

  <!-- COLLECTIONS SECTION (FIXED) -->
  <section id="collections" class="collections">
    <h2>Shop by Collection</h2>

    <div class="grid">
      <div class="box">
        <img
          src="/images/birthday-category.jpg"
          alt="Kids Birthday Outfits"
        />
        <h3>Kids Birthday Outfits</h3>
        <p>Perfect outfits for first birthdays and celebrations.</p>
      </div>

      <div class="box">
        <img
          src="/images/family-category.jpg"
          alt="Family Matching Outfits"
        />
        <h3>Family Matching Outfits</h3>
        <p>Coordinated looks for photos and events.</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  height: 75vh;
  background-image: url("/images/hero.jpg");
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-content {
  background: rgba(255, 255, 255, 0.85);
  padding: 40px;
  border-radius: 16px;
  text-align: center;
  max-width: 600px;
}

.hero h1 {
  font-size: 36px;
  margin-bottom: 12px;
}

.hero p {
  font-size: 16px;
  margin-bottom: 20px;
}

.cta-btn {
  display: inline-block;
  padding: 14px 26px;
  background: #25d366;
  color: #fff;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
}

.collections {
  padding: 80px 20px;
  max-width: 1100px;
  margin: auto;
}

.collections h2 {
  text-align: center;
  font-size: 32px;
  margin-bottom: 40px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 28px;
}

.box {
  background: #fff;
  border-radius: 18px;
  padding: 18px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.08);
  text-align: center;
}

.box img {
  width: 100%;
  height: 260px;
  object-fit: cover;
  border-radius: 14px;
  margin-bottom: 14px;
}

.box h3 {
  font-size: 20px;
  margin-bottom: 6px;
}

.box p {
  font-size: 14px;
  color: #555;
}
</style>
