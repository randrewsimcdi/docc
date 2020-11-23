<template>
  <Layout>
    
  <CMAHeader />
  <CMAMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=161eEsNwJuzwYEVmwOvHPPqRXw-roBwq8#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import CMAMenu from "@/components/CMAMenu";
import CMAHeader from "@/components/CMAHeader";


export default {
  metaInfo: {
    title: "CMA Release Notes",
  },
  components: {
    CMAMenu,
    CMAHeader,
  },
};
</script>