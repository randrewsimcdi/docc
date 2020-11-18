<template>
  <Layout>
    
  <AMCIHeader />
    <AMCIMenu />

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
import AMCIMenu from "@/components/AMCIMenu";
import AMCIHeader from "@/components/AMCIHeader";


export default {
  metaInfo: {
    title: "AMCI",
  },
  components: {
    AMCIMenu,
    AMCIHeader
  },
};
</script>