<template>
  <section class="profile" id="about">


<div class="profile-content">
  <p class="subtitle">GET TO KNOW ME</p>

  <h1>Hello, I'm Robel.</h1>

  <h2>Future Full Stack Web Developer</h2>

  <p>
    I am passionate about technology and web development.
    I enjoy learning new programming languages and building
    modern websites that solve real-world problems.
  </p>

  <a href="#projects" class="button">Explore My Projects</a>
</div>

<div class="profile-card">
  <div class="avatar">R</div>
  <h3>Creative Thinker</h3>
  <p>Learning Today, Building Tomorrow.</p>
</div>


  </section>
</template>

<script>
export default {
  name: "DeveloperProfile"
};
</script>

<style scoped>
.profile {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 40px;
  padding: 90px 10%;
  background: #f8f7f4;
}

.profile-content {
  max-width: 550px;
}

.subtitle {
  color: #b8895b;
  letter-spacing: 3px;
  font-weight: bold;
}

h1 {
  font-size: 50px;
  color: #111827;
  margin: 20px 0;
}

h2 {
  color: #b8895b;
  margin-bottom: 20px;
}

.profile-content p {
  color: #555;
  line-height: 1.8;
}

.button {
  display: inline-block;
  margin-top: 25px;
  padding: 14px 25px;
  background: #111827;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

.profile-card {
  background: white;
  padding: 40px;
  text-align: center;
  border-radius: 15px;
  box-shadow: 0 10px 30px #00000015;
}

.avatar {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  background: #d4a373;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 60px;
  margin: auto auto 20px;
}

@media (max-width: 700px) {
  .profile {
    flex-direction: column;
    text-align: center;
  }
}
</style>
