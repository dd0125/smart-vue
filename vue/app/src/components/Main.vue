<script>
import Sub from '@/components/Sub'
export default {
  components: { Sub }
}
</script>

<template>
    <div>
        Main
        <div class="sub-area">
            <Sub color="#f00"/>
            <Sub color="#0f0"/>
            <Sub color="#00f"/>
        </div>
    </div>
</template>

<style scoped>
.sub-area {
  display: flex;
  justify-content: center;
}
</style>
