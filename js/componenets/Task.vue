<template>
    <li>
        <del v-if="taskk.isCompleted">{{ taskk.title }}</del>
        <span v-else>{{ taskk.title }}</span>
    </li>
</template>


<style>

</style>


<script>
export default {
    props: {
        taskk: {
            required: true,
        }
    }
}
</script>