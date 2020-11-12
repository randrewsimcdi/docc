<template>
  <Layout>
    
  <IvystoneHeader />
    <AgencyMenu />

    <div class="flex flex-wrap items-center">
      <iframe
        class="w-full mt-6"
        src="https://drive.google.com/file/d/1V3BE_nYEhMdt4mZM0HlXt1XfiSNjU5Ho/preview"
        height="1080"
      ></iframe>
    </div>
  </Layout>
</template>

<script>
import AgencyMenu from "@/components/AgencyMenu";
import IvystoneHeader from "@/components/IvystoneHeader";


export default {
  metaInfo: {
    title: "Ivystone",
  },
  components: {
    AgencyMenu,
    IvystoneHeader
  },
};
</script>