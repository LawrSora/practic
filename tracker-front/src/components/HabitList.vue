<template>
    <div class="habit-list-base">
        <div class="habit-list-content">
            <div class="habit-list-title">Сегодня</div>
            <div class="habit-block">
                <div class="habit-title-block">
                    <div class="habit-icon">
                        <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-sport-shoe-icon lucide-sport-shoe"><path d="m15 10.42 4.8-5.07"/><path d="M19 18h3"/><path d="M9.5 22 21.414 9.415A2 2 0 0 0 21.2 6.4l-5.61-4.208A1 1 0 0 0 14 3v2a2 2 0 0 1-1.394 1.906L8.677 8.053A1 1 0 0 0 8 9c-.155 6.393-2.082 9-4 9a2 2 0 0 0 0 4h14"/></svg>
                    </div>
                    <div class="habit-title">Habit</div>
                </div>
                <div class="habit-buttons-block">
                    <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-ellipsis-vertical-icon lucide-ellipsis-vertical">
                        <circle cx="12" cy="12" r="1"/><circle cx="12" cy="5" r="1"/><circle cx="12" cy="19" r="1"/></svg>
                    <div class="done-button"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.habit-list-base {
    background-color: var(--component-background-light);
    margin-top: 10px;
    margin-right: 10px;
    height: 100vh;
    border-top-left-radius: 40px;
    border-top-right-radius: 40px;
    width: 100%;
    display: flex;
}

.habit-list-content {
    margin-top: 30px;
    width: 100%;
    align-items: center;
    display: flex;
    flex-direction: column;
}

.habit-block {
    border-bottom: 3px solid #292929;
    width: 95%;
    margin-top: 30px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}

.habit-title-block {
    display: flex;
    flex-direction: row;
    align-items: center;
}

.habit-title {
    font-size: 24pt;
    font-family: Montserrat-regular;
    margin-left: 30px;
}

.habit-icon {
    width: 75px;
    height: 75px;
    border-radius: 100%;
    background-color: aqua;
    margin-bottom: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.habit-buttons-block {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-bottom: 10px;
    margin-right: 30px;
}

.done-button {
    width: 50px;
    height: 50px;
    border-radius: 100%;
    fill: none;
    border: 5px solid #292929;
}

.habit-list-title {
    font-family: Montserrat-semi-bold;
    font-size: 36pt;
}
</style>