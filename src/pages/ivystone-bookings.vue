<template>
  <Layout>
    
  <IvystoneHeader />
    <AgencyMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=1-6RZSX8tS8d98EdQlXRqJsxpCmja5Int#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import AgencyMenu from "@/components/AgencyMenu";
import IvystoneHeader from "@/components/IvystoneHeader";


export default {
  metaInfo: {
    title: "Ivystone Bookings",
  },
  components: {
    AgencyMenu,
    IvystoneHeader,
  },
};
</script>