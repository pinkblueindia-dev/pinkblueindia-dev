<template>
  <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-overlay">
      <div class="hero-content">
        <h1>Beautiful Matching Outfits for Kids & Families</h1>
        <p>
          Handcrafted kids birthday outfits and family matching clothing.
          Premium quality, custom sizing, worldwide delivery.
        </p>

        <div class="hero-cta">
          <a
            href="https://www.pinkblueindia.com"
            class="btn primary"
            target="_blank"
          >
            Shop Collection
          </a>

          <a
            href="https://wa.me/918003550118"
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
  <section class="collections" id="collections">
    <h2>Shop by Collection</h2>

    <div class="grid">
      <div class="box">
        <img
          src="/images/birthday-category.jpg"
          alt="Kids Birthday Outfits"
          class="collection-img"
        />
        <h3>Kids Birthday Outfits</h3>
        <p>Perfect outfits for first birthdays and celebrations.</p>
      </div>

      <div class="box">
        <img
          src="/images/family-category.jpg"
          alt="Family Matching Outfits"
          class="collection-img"
        />
        <h3>Family Matching Outfits</h3>
        <p>Coordinated looks for photos and events.</p>
      </div>
    </div>
  </section>

  <!-- WHY US -->
  <section class="why" id="why">
    <h2>Why PinkBlueIndia</h2>
    <p>
      Every outfit is handcrafted with care, keeping comfort and fit in mind.
      We offer custom sizing, premium fabrics and direct WhatsApp support so
      every order feels personal.
    </p>
  </section>

  <!-- WHATSAPP CTA -->
  <section class="whatsapp-section" id="contact">
    <h2>Need help with size or customization?</h2>
    <p>Chat with us directly on WhatsApp for quick assistance.</p>

    <a
      href="https://wa.me/918003550118"
      class="btn whatsapp large"
      target="_blank"
    >
      Chat on WhatsApp
    </a>
  </section>
</template>

<style scoped>
.hero {
  background-image: url("/images/hero-banner.jpg");
  background-size: cover;
  background-position: center;
  height: 85vh;
  position: relative;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.55);
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-content {
  text-align: center;
  color: #fff;
  max-width: 900px;
  padding: 20px;
}

.hero-content h1 {
  font-size: 42px;
  margin-bottom: 16px;
}

.hero-content p {
  font-size: 18px;
  line-height: 1.6;
  margin-bottom: 28px;
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
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
  padding: 18px;
  background: #fafafa;
}

.collections,
.why,
.whatsapp-section {
  padding: 60px 20px;
  text-align: center;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  max-width: 1000px;
  margin: 30px auto;
}

.box {
  border: 1px solid #eee;
  padding: 24px;
  border-radius: 14px;
}

.collection-img {
  width: 100%;
  height: 260px;
  object-fit: cover;
  border-radius: 14px;
  margin-bottom: 14px;
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
