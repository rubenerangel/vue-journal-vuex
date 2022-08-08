<template>
  <div 
    @click="$router.push({ name: 'entry', params: { id: 10 } })"
    class="mb-3 pointer p-2 entry-container"
    >
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">15</span>
        <span class="mx-1 fs-5">July</span>
        <span class="mx-2" fw-light>2021, jueves</span>
    </div>
    <div class="entry-descripton">
        Consequat est dolore occaecat reprehenderit quis consectetur do cupidatat magna velit deserunt. Sunt est nostrud eu ex mollit elit elit id Lorem. Aute ipsum commodo esse aliquip deserunt est magna reprehenderit nisi nisi culpa laboris reprehenderit. Proident pariatur culpa velit esse exercitation deserunt sit enim laboris cupidatat cillum Lorem. Labore culpa anim cillum consectetur cillum aliquip commodo eu do commodo ex esse cillum. Proident mollit Lorem irure enim nostrud quis veniam magna voluptate dolor Lorem enim. Pariatur sint sunt irure ex magna ut consequat sunt aliqua velit elit anim.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-descripton{
        font-size: 12px;
    }
}
</style>