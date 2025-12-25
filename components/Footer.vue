<template>
  <footer class="site-footer">
    <div class="footer-inner">

      <div class="footer-col">
        <h4>PinkBlueIndia</h4>
        <p>Handcrafted kids and family matching outfits.</p>
      </div>

      <div class="footer-col">
        <h4>Quick Links</h4>
        <a href="#collections">Collections</a>
        <a href="#why">Why Us</a>
        <a href="https://www.pinkblueindia.com">Shop</a>
      </div>

      <div class="footer-col">
        <h4>Connect</h4>
        <a href="https://www.instagram.com/pinkblueindia" target="_blank">
          Instagram
        </a>
        <a href="https://www.facebook.com/pinkblueindia" target="_blank">
          Facebook
        </a>
        <a href="https://wa.me/918003550118" target="_blank">
          WhatsApp
        </a>
      </div>

    </div>

    <div class="footer-bottom">
      © PinkBlueIndia. All rights reserved.
    </div>
  </footer>
</template>

<style scoped>
.site-footer {
  background: #111;
  color: #fff;
  padding: 50px 20px 20px;
}

.footer-inner {
  max-width: 1100px;
  margin: auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 30px;
}

.footer-col h4 {
  font-size: 16px;
  margin-bottom: 12px;
}

.footer-col p {
  font-size: 14px;
  color: #ccc;
}

.footer-col a {
  display: block;
  font-size: 14px;
  color: #ccc;
  text-decoration: none;
  margin-bottom: 8px;
}

.footer-col a:hover {
  color: #fff;
}

.footer-bottom {
  text-align: center;
  font-size: 13px;
  color: #aaa;
  margin-top: 30px;
  border-top: 1px solid #333;
  padding-top: 15px;
}
</style>
