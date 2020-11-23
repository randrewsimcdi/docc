<template>
  <Layout>
    
  <SimblistHeader />
  <SimblistMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=1LVqTNcMd7H8FBkbrzg5oXH-EB6DtCarv#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import SimblistMenu from "@/components/SimblistMenu";
import SimblistHeader from "@/components/SimblistHeader";


export default {
  metaInfo: {
    title: "Simblist Payment Gateways",
  },
  components: {
    SimblistMenu,
    SimblistHeader,
  },
};
</script>