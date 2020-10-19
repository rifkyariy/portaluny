<template>
    <div
      :class="{ hasOpenLoading }">
      <div
        v-for="(type, i) in types"
        :ref="`box${i}`"
        @click="handleClickLoading(type)"
        class="box-loading" />
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>