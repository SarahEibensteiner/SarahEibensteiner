<template>
    <div class="c-singleLink">
        <img :src="require(`@/assets/icons/${filename}`)" />
        <a :href="link" target="_blank"> {{ text }} </a>
    </div>
</template>


<script>
export default {
  name: "SingleLink",
  props: {
    filename: String,
    text: String,
    link: String,
  }
}
</script>

<style scoped>
.c-singleLink svg {
    padding-right: 8px;
}

.c-singleLink a {
    padding-left: 6px;
    font-family: Inter;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    color: #2f363d;
    text-decoration: none;
    -webkit-font-smoothing: antialiased;
    cursor: pointer;
}

</style>