<template>
    <div class="dash-flex">
        <dash-side />
        <dash-main />
    </div>
</template>

<script>
import DashSide from "./DashSide.vue"
import DashMain from "./DashMain.vue"

export default{
    components: {
        DashSide,
        DashMain
    }
}
</script>

<style scoped>
.dash-flex{
    display: flex;
    margin-top: .5em;
}

</style>
