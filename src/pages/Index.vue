<template>
  <Layout>
    <div class="pt-8 md:pt-16">
      <div class="flex flex-col items-center">
        <div class="flex flex-col items-center mb-2 text-ui-primary">
          <g-image src="../assets/pharos-imc_di-logo.png" />
        </div>
        <h1 class="text-4xl text-center lg:text-5xl">
          Our documentation starts here.
        </h1>

        <div class="flex justify-center mt-8">
          <g-link
            to="/docs/"
            class="flex items-center px-6 py-4 ml-auto text-2xl font-bold leading-none text-white border rounded-lg shadow-lg bg-ui-primary border-ui-primary transition-all duration-200 ease-out transform hover:shadow-xl hover:-translate-y-1"
          >
            Get started
            <ArrowRightCircleIcon class="ml-4" size="1x" />
          </g-link>
        </div>
      </div>


      <div class="flex flex-wrap justify-center -mx-3 mt-8">
        <div
          class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/4"
        >
          <g-link
            to="/docs/crm"
            class="ml-auto font-bold leading-none text-white transition-all duration-200 ease-out transform hover:shadow-xl hover:-translate-y-1"
          >
            <g-image src="../assets/pharos-crm.png" />
            <h3 class="font-bold tracking-wide uppercase text-ui-primary">
              Pharos CRM
            </h3>
            <div class="flex justify-center mt-8"></div>
          </g-link>
        </div>

        <div
          class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/4"
        >
          <g-link
            to="/docs/pfl"
            class="ml-auto font-bold leading-none text-white transition-all duration-200 ease-out transform hover:shadow-xl hover:-translate-y-1"
          >
            <g-image src="../assets/product-fastlane.png" />

            <h3 class="font-bold tracking-wide uppercase text-ui-primary">
              Product FastLane
            </h3>
            <div class="flex justify-center mt-8"></div>
          </g-link>
        </div>

        <div
          class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/4"
        >
         <!--  <g-link
            to="/docs/"
            class="ml-auto font-bold leading-none text-white transition-all duration-200 ease-out transform hover:shadow-xl hover:-translate-y-1"
          > -->
            <g-image src="../assets/pharos-sales-app.png" />
            <h3 class="font-bold tracking-wide uppercase text-ui-primary">
              Pharos Spotlight
            </h3>
            <div class="flex justify-center mt-8"></div>
<!--           </g-link>
 -->        </div>

        <div
          class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/4"
        >
          <!-- <g-link
            to="/docs/"
            class="ml-auto font-bold leading-none text-white transition-all duration-200 ease-out transform hover:shadow-xl hover:-translate-y-1"
          > -->
            <g-image src="../assets/pharos-web.png" />
            <h3 class="font-bold tracking-wide uppercase text-ui-primary">
              Pharos Web
            </h3>
            <div class="flex justify-center mt-8"></div>
<!--           </g-link>
 -->        </div>
      </div>

       <!--  <div
        class="pt-8 mx-auto mt-8 border-t md:mt-16 md:pt-16 border-top border-ui-border max-w-screen-sm"
      ></div> -->

      <div class="bg-green-400 text-center py-4 lg:px-4">
        <g-link to="https://www.junipercommerce.com/">
          <div
            class="p-2 bg-green-400 items-center text-green-100 leading-none lg:rounded-full flex lg:inline-flex"
            role="alert"
          >
            <span class="font-semibold mr-2 text-left flex-auto"
              >With the launch of Juniper, IMC now offers a complete,
              omnichannel approach to growing and managing your business</span
            >
            <span
              class="flex rounded-full bg-green-600 uppercase px-2 py-1 text-xs font-bold mr-3"
              >Learn More</span
            >
          </div>
        </g-link>
      </div>
    </div>
  </Layout>
</template>

<script>
import Logo from "@/components/Logo";
import {
  ArrowRightCircleIcon,
  ZapIcon,
  CodeIcon,
  MoonIcon,
  SearchIcon,
} from "vue-feather-icons";

export default {
  components: {
    ArrowRightCircleIcon,
    ZapIcon,
    CodeIcon,
    MoonIcon,
    SearchIcon,
  },

  metaInfo() {
    const title = "Pharos Documentation";
    const description =
      "Instant search and dark mode for great documentation on Pharos products";

    return {
      title: title,
      meta: [
        {
          name: "description",
          content: description,
        },
        {
          key: "og:title",
          name: "og:title",
          content: title,
        },
        {
          key: "twitter:title",
          name: "twitter:title",
          content: title,
        },
        {
          key: "og:description",
          name: "og:description",
          content: description,
        },
        {
          key: "twitter:description",
          name: "twitter:description",
          content: description,
        },
      ],
    };
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
