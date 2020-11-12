<template>
  <Layout>
    
  <IvystoneHeader />
    <AgencyMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=161eEsNwJuzwYEVmwOvHPPqRXw-roBwq8#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import AgencyMenu from "@/components/AgencyMenu";
import IvystoneHeader from "@/components/IvystoneHeader";


export default {
  metaInfo: {
    title: "Ivystone Release Notes",
  },
  components: {
    AgencyMenu,
    IvystoneHeader,
  },
};
</script>