<template>
  <Layout>
    
  <SpotlightHeader />
  <SpotlightMenu />

    

  </Layout>
</template>

<script>
import SpotlightMenu from "@/components/SpotlightMenu";
import SpotlightHeader from "@/components/SpotlightHeader";


export default {
  metaInfo: {
    title: "Spotlight Sales App",
  },
  components: {
    SpotlightMenu,
    SpotlightHeader
  },
};
</script>