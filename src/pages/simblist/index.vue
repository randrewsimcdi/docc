<template>
  <Layout>
    
  <SimblistHeader />
  <SimblistMenu />

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
import SimblistMenu from "@/components/SimblistMenu";
import SimblistHeader from "@/components/SimblistHeader";


export default {
  metaInfo: {
    title: "Simblist",
  },
  components: {
    SimblistMenu,
    SimblistHeader
  },
};
</script>