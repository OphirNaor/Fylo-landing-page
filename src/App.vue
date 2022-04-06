
<template>
  <HeaderCmp />
  <HeroCmp />
  <MainFeatures />
  <productiveCmp />
</template>



<script>
import HeaderCmp from "./components/header-cmp.vue";
import HeroCmp from "./components/hero-cmp.vue"
import MainFeatures from "./components/main-features.vue"
import productiveCmp from "./components/productive-cmp.vue"

export default {
  name: "App",
  data() {
    return {
    };
  },
  created() {
  },
  components: {
    HeaderCmp,
    HeroCmp,
    MainFeatures,
    productiveCmp
  },
  computed: {},
  methods: {},
  mounted() { },
};
</script>
