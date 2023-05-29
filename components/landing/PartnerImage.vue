<template>
  <div>
    <img :src="require(`~/assets/img/partner/${img}`)" class="sm:w-1/2 lg:w-72 mx-auto" alt="" style="height: 200px" />
  </div>
</template>
<script>
export default {
  props: {
    img: {
      type: String,
      default: '',
    },
  },
}
</script>
