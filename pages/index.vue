<template>
  <div>

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
            <p>Coordinated looks for photos and special days.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- WHY -->
    <section id="why" class="why">
      <h2>Why PinkBlueIndia</h2>
      <p>
        Handcrafted outfits with premium fabrics, custom sizing and direct
        WhatsApp support.
      </p>
    </section>

    <!-- CTA -->
    <section id="contact" class="cta">
      <h2>Need help with size or customization?</h2>
      <a
        href="https://wa.me/918003550118"
        target="_blank"
        class="btn whatsapp large"
      >
        Chat on WhatsApp
      </a>
    </section>

  </div>
</template>

<script setup>
useHead({
  title: 'PinkBlueIndia | Kids Birthday & Family Matching Outfits',
  meta: [
    {
      name: 'description',
      content:
        'Shop handcrafted kids birthday outfits and family matching clothing.'
    }
  ]
})
</script>
