<script setup>
import hero from '@/assets/images/hero-banner.jpg'
import birthday from '@/assets/images/birthday-category.jpg'
import family from '@/assets/images/family-category.jpg'
import mother from '@/assets/images/mother-daughter-category.jpg'
import festive from '@/assets/images/festive-category.jpg'

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

<template>
  <div>

    <header class="nav">
      <div class="nav-inner">
        <div class="logo">PinkBlueIndia</div>
        <nav>
          <a href="#collections">Collections</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>
    </header>

    <!-- HERO -->
    <section class="hero" :style="{ backgroundImage: `url(${hero})` }">
      <div class="hero-overlay">
        <div class="hero-content">
          <h1>Beautiful Matching Outfits for Kids & Families</h1>
          <p>Handcrafted birthday outfits and family matching clothing.</p>

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
          <img :src="birthday" />
          <h3>Kids Birthday Outfits</h3>
        </div>

        <div class="box">
          <img :src="mother" />
          <h3>Mother Daughter Matching</h3>
        </div>

        <div class="box">
          <img :src="family" />
          <h3>Family Matching Outfits</h3>
        </div>

        <div class="box">
          <img :src="festive" />
          <h3>Festive Wear</h3>
        </div>
      </div>
    </section>

    <section id="contact" class="whatsapp-section">
      <a href="https://wa.me/918003550118" class="btn whatsapp large" target="_blank">
        Chat on WhatsApp
      </a>
    </section>

  </div>
</template>

<style scoped>
.hero {
  height: 85vh;
  background-size: cover;
  background-position: center;
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
</style>
