<template>
  <Layout>
    
  <IvystoneHeader />
    <AgencyMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=1LVqTNcMd7H8FBkbrzg5oXH-EB6DtCarv#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import AgencyMenu from "@/components/AgencyMenu";
import IvystoneHeader from "@/components/IvystoneHeader";


export default {
  metaInfo: {
    title: "Ivystone Payment Gateways",
  },
  components: {
    AgencyMenu,
    IvystoneHeader,
  },
};
</script>