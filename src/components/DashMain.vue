<template>
    <div class="main">
        <dash-header />
        <div class="main-content">
            <h2>Content displayed ⭐</h2>
        </div>
    </div>
</template>

<script>
import DashHeader from './DashHeader.vue'

export default{
    components: {
        DashHeader
    }
}
</script>


<style scoped>
.main{
    width: 100%;
    margin-left: .9em;
}

.main-content{
    background: rgba(255, 255, 255, 0.849);
    margin-top: .9em;
    height: 93vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>