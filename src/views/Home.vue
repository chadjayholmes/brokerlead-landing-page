<template>
  <div>
    <Banner class="banner"></Banner>
  </div>
</template>

<script>
import Banner from "@/components/Banner";
//import ProjectsRow from "@/components/ProjectsRow";

export default {
  data() {
    return {
    };
  },
  methods: {
  },
  name: 'Home',
  components: {
    //ProjectsRow,
    Banner,
  },
}
</script>

<style scoped>

template{
  background: #000000;
}

.banner{
  padding-bottom: 25px;
  z-index: -1;
}

</style>
