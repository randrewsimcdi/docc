<template>
  <Layout>
    
  <CMAHeader />
  <CMAMenu />

  <div class="flex flex-wrap items-center">
  <iframe class="w-full mt-6" src="https://drive.google.com/embeddedfolderview?id=1-6RZSX8tS8d98EdQlXRqJsxpCmja5Int#list" height="1080"></iframe>
</div>


  </Layout>
</template>

<script>
import CMAMenu from "@/components/CMAMenu";
import CMAHeader from "@/components/CMAHeader";


export default {
  metaInfo: {
    title: "CMA Bookings",
  },
  components: {
    CMAMenu,
    CMAHeader,
  },
};
</script>