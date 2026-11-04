<template>
  <section class="projects" id="projects">


<p class="subtitle">MY PORTFOLIO</p>

<h2>Featured Projects</h2>

<div class="project-grid">

  <div class="project-card">
    <h3>Mechanic Website</h3>
    <p>
      A professional website for an automotive repair business.
    </p>
    <span>HTML • CSS • JavaScript</span>
  </div>

  <div class="project-card">
    <h3>Shopping Cart</h3>
    <p>
      An interactive shopping experience with a checkout page.
    </p>
    <span>JavaScript • Cookies</span>
  </div>

  <div class="project-card">
    <h3>API Explorer</h3>
    <p>
      An application that retrieves information from external APIs.
    </p>
    <span>JavaScript • Axios</span>
  </div>

</div>

  </section>
</template>

<script>
export default {
  name: "ProjectsShowcase"
};
</script>

<style scoped>
.projects {
  padding: 80px 10%;
  text-align: center;
  background: #f8f7f4;
}

.subtitle {
  color: #b8895b;
  letter-spacing: 3px;
  font-weight: bold;
}

h2 {
  font-size: 38px;
  margin: 20px 0 35px;
  color: #111827;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 25px;
}

.project-card {
  background: white;
  padding: 30px;
  border-radius: 10px;
  text-align: left;
  box-shadow: 0 5px 20px #00000010;
}

.project-card h3 {
  color: #b8895b;
  margin-bottom: 15px;
}

.project-card p {
  color: #555;
  line-height: 1.7;
  margin-bottom: 20px;
}

.project-card span {
  font-size: 12px;
  font-weight: bold;
}

@media (max-width: 700px) {
  .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>
