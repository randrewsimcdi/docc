<template>
  <Layout>
    
  <CMAHeader />
  <CMAMenu />

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
import CMAMenu from "@/components/CMAMenu";
import CMAHeader from "@/components/CMAHeader";


export default {
  metaInfo: {
    title: "CMA",
  },
  components: {
    CMAMenu,
    CMAHeader
  },
};
</script>