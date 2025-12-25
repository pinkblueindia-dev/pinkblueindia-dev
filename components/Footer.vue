<template>
  <footer class="site-footer">
    <div class="footer-wrap">

      <div class="footer-col">
        <h3>PinkBlueIndia</h3>
        <p>Handcrafted kids and family matching outfits.</p>
      </div>

      <div class="footer-col">
        <h4>Explore</h4>
        <a href="#collections">Collections</a>
        <a href="#why">Why Us</a>
        <a href="#contact">Contact</a>
        <a href="https://www.pinkblueindia.com">Shop</a>
      </div>

      <div class="footer-col">
        <h4>Social</h4>
        <a href="https://instagram.com/pinkblueindia" target="_blank">Instagram</a>
        <a href="https://facebook.com/pinkblueindia" target="_blank">Facebook</a>
        <a href="https://pinterest.com/pinkblueindia" target="_blank">Pinterest</a>
      </div>

      <div class="footer-col">
        <h4>Payments</h4>
        <p>UPI · Cards · RuPay · COD</p>
      </div>

    </div>

    <div class="footer-bottom">
      © 2025 PinkBlueIndia. All rights reserved.
    </div>
  </footer>
</template>

<style scoped>
.site-footer {
  background: #f7f7f7;
  padding: 40px 20px 20px;
  font-size: 14px;
  color: #222;
}

.footer-wrap {
  max-width: 1100px;
  margin: auto;
  display: grid;
  gap: 30px;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}

.footer-col h3,
.footer-col h4 {
  font-weight: 600;
  margin-bottom: 10px;
}

.footer-col p {
  margin: 0;
  line-height: 1.6;
}

.footer-col a {
  display: block;
  margin-bottom: 6px;
  color: #222;
  text-decoration: none;
}

.footer-col a:hover {
  text-decoration: underline;
}

.footer-bottom {
  text-align: center;
  margin-top: 30px;
  padding-top: 15px;
  border-top: 1px solid #ddd;
  font-size: 13px;
  color: #555;
}
</style>
