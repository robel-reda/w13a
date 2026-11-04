<template>
  <section class="skills" id="skills">


<p class="subtitle">MY DEVELOPMENT JOURNEY</p>

<h2>Technical Skills</h2>

<p class="description">
  Technologies I am learning during my full stack development journey.
</p>

<div class="skills-grid">
  <div class="skill">HTML5</div>
  <div class="skill">CSS3</div>
  <div class="skill">JavaScript</div>
  <div class="skill">Vue.js</div>
  <div class="skill">Git & GitHub</div>
  <div class="skill">Axios & APIs</div>
</div>


  </section>
</template>

<script>
export default {
  name: "SkillsPanel"
};
</script>

<style scoped>
.skills {
  padding: 80px 10%;
  text-align: center;
  background: white;
}

.subtitle {
  color: #b8895b;
  letter-spacing: 3px;
  font-weight: bold;
}

h2 {
  font-size: 38px;
  margin: 20px;
  color: #111827;
}

.description {
  color: #777;
  margin-bottom: 35px;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.skill {
  padding: 25px;
  background: #f8f7f4;
  border-bottom: 3px solid #d4a373;
  border-radius: 8px;
  font-weight: bold;
}

@media (max-width: 600px) {
  .skills-grid {
    grid-template-columns: 1fr;
  }
}
</style>
