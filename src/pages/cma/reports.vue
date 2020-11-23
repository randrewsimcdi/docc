<template>
  <Layout>
    
  <CMAHeader />
  <CMAMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=1-HMF_qJyVKWppfSFa1dPR9dzMI6Fakdu#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import CMAMenu from "@/components/CMAMenu";
import CMAHeader from "@/components/CMAHeader";


export default {
  metaInfo: {
    title: "CMA Reports",
  },
  components: {
    CMAMenu,
    CMAHeader,
  },
};
</script>