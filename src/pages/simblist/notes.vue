<template>
  <Layout>
    
  <SimblistHeader />
  <SimblistMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=161eEsNwJuzwYEVmwOvHPPqRXw-roBwq8#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import SimblistMenu from "@/components/SimblistMenu";
import SimblistHeader from "@/components/SimblistHeader";


export default {
  metaInfo: {
    title: "Simblist Release Notes",
  },
  components: {
    SimblistMenu,
    SimblistHeader,
  },
};
</script>