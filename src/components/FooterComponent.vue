<template>
  <footer class="footer" id="contact">


<div class="footer-content">
  <h2>Let's Create Something Amazing.</h2>

  <p>
    Thank you for visiting my portfolio.
    Let's connect and build something great together.
  </p>

  <a href="mailto:hello@example.com" class="email-button">
    Get In Touch
  </a>
</div>

<div class="footer-bottom">
  <p>© 2026 Robel. All Rights Reserved.</p>
  <p>Designed with Vue.js</p>
</div>


  </footer>
</template>

<script>
export default {
  name: "FooterComponent"
};
</script>

<style scoped>
.footer {
  background: #111827;
  color: white;
  padding: 65px 10% 25px;
  text-align: center;
}

.footer-content h2 {
  color: #d4a373;
  font-size: 32px;
  margin-bottom: 20px;
}

.footer-content p {
  color: #d1d5db;
  line-height: 1.8;
  margin-bottom: 25px;
}

.email-button {
  display: inline-block;
  background: #d4a373;
  color: #111827;
  padding: 14px 28px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.email-button:hover {
  background: white;
}

.footer-bottom {
  border-top: 1px solid #374151;
  margin-top: 55px;
  padding-top: 25px;
  display: flex;
  justify-content: space-between;
  font-size: 13px;
}

@media (max-width: 600px) {
  .footer-bottom {
    flex-direction: column;
    gap: 15px;
  }
}
</style>
