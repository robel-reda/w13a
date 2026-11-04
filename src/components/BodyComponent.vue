<template>
  <main>


<DeveloperProfile />

<SkillsPanel />

<ProjectsShowcase />


  </main>
</template>

<script>
import DeveloperProfile from "./DeveloperProfile.vue";
import SkillsPanel from "./SkillsPanel.vue";
import ProjectsShowcase from "./ProjectsShowcase.vue";

export default {
  name: "BodyComponent",

  components: {
    DeveloperProfile,
    SkillsPanel,
    ProjectsShowcase
  }
};
</script>
