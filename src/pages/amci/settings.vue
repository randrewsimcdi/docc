<template>
  <Layout>
    
  <AMCIHeader />
    <AMCIMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=1wk-HFh04dJqEumfSVlrG18dHEtc7nBdF#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import AMCIMenu from "@/components/AMCIMenu";
import AMCIHeader from "@/components/AMCIHeader";


export default {
  metaInfo: {
    title: "AMCI Settings",
  },
  components: {
    AMCIMenu,
    AMCIHeader,
  },
};
</script>