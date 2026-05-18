<template>
    <main>
    <LeftMenu />
    <div style="width: 100%; margin: 10px;">
    <TopBar />
    <div style="display: flex; flex-direction: row; width: 100%; height: 100%; justify-content: space-between; margin-top: 15px;">
    <HabitList />
    <div style="display: flex; flex-direction: column; margin-left: 10px;">
        <Calendar />
        <Progress />
    </div>
    </div>
    </div>
    </main>
</template>

<script setup>
import LeftMenu from './LeftBar.vue';
import TopBar from './TopBar.vue';
import HabitList from './HabitList.vue';
import Calendar from './Calendar.vue';
import Progress from './Progress.vue';

</script>

<style scoped>
    main {
        display: flex;
        flex-direction: row;
        width: 100%;
        height: 100%;
        justify-content: space-between;
    }
</style>
