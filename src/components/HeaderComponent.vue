<template>
  <header class="header">
    <div class="logo">Rob<span></span></div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
    </nav>

    <a href="#contact" class="contact-btn">Contact Me</a>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent"
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 25px 8%;
  background: #111827;
  color: white;
}

.logo {
  font-size: 28px;
  font-weight: bold;
}

.logo span {
  color: #d4a373;
}

nav {
  display: flex;
  gap: 30px;
}

nav a {
  color: white;
  text-decoration: none;
  transition: 0.3s;
}

nav a:hover {
  color: #d4a373;
}

.contact-btn {
  background: #d4a373;
  color: #111827;
  padding: 12px 20px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
}

@media (max-width: 650px) {
  .header {
    flex-direction: column;
    gap: 20px;
  }

  nav {
    flex-wrap: wrap;
    justify-content: center;
  }
}
</style>