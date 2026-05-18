<template>
    <div class="left-bar-base">
        <div class="logo-block">
            <div class="logo"></div>
            <div class="logo-title">Grail</div>
        </div>
        <div class="left-nav">
                <ul>
                <li>
                    <div class="nav-icon"><svg xmlns="http://www.w3.org/2000/svg" width="44" height="44" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-house-icon lucide-house"><path d="M15 21v-8a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v8"/>
                        <path d="M3 10a2 2 0 0 1 .709-1.528l7-6a2 2 0 0 1 2.582 0l7 6A2 2 0 0 1 21 10v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/></svg></div>
                    Профиль
                </li>
                <li class="select-page"><div class="nav-icon"><svg xmlns="http://www.w3.org/2000/svg" width="44" height="44" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circle-user-round-icon lucide-circle-user-round">
                    <path d="M17.925 20.056a6 6 0 0 0-11.851.001"/><circle cx="12" cy="11" r="4"/><circle cx="12" cy="12" r="10"/></svg>
                </div>Главная</li>
                <li><div class="nav-icon"><svg xmlns="http://www.w3.org/2000/svg" width="44" height="44" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-settings-icon lucide-settings">
                    <path d="M9.671 4.136a2.34 2.34 0 0 1 4.659 0 2.34 2.34 0 0 0 3.319 1.915 2.34 2.34 0 0 1 2.33 4.033 2.34 2.34 0 0 0 0 3.831 2.34 2.34 0 0 1-2.33 4.033 2.34 2.34 0 0 0-3.319 1.915 2.34 2.34 0 0 1-4.659 0 2.34 2.34 0 0 0-3.32-1.915 2.34 2.34 0 0 1-2.33-4.033 2.34 2.34 0 0 0 0-3.831A2.34 2.34 0 0 1 6.35 6.051a2.34 2.34 0 0 0 3.319-1.915"/>
                    <circle cx="12" cy="12" r="3"/></svg>
                </div>Настройки</li>
                <li><div class="nav-icon"><svg xmlns="http://www.w3.org/2000/svg" width="44" height="44" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circle-plus-icon lucide-circle-plus">
                    <circle cx="12" cy="12" r="10"/><path d="M8 12h8"/><path d="M12 8v8"/></svg>
                </div>Создать</li>
            </ul>
            </div>
    </div>
</template>

<style scoped>
.left-bar-base {
    width: 335px;
    margin: 10px;
    background-color: var(--component-background-light);
    border-radius: 25px;
    padding-top: 40px;
    max-height: max-content;
}

.logo-block {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-left: 15px;
}

.logo {
    border-radius: 100%;
    background-color: black;
    width: 77px;
    height: 77px;
    margin-bottom: 30px;
}

.logo-title {
    margin-left: 20px;
    font-size: 42pt;
    font-family: Montserrat-semi-bold;
}

.left-nav li{
    display: flex;
    justify-content: start;
    align-items: center;
    margin-bottom: 40px;
    font-size: 20pt;
    font-family: Montserrat-regular;
    list-style-type: none;
    margin-left: 25px;
}

.nav-icon {
    height: 45px;
    width: 45px;
    margin-right: 7px;
}

.select-page {
    background-color: var(--background-light);
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 10px !important;
    border-top-left-radius: 25px;
    border-bottom-left-radius: 25px;
    padding-left: 15px;
    margin-left: 10px;
}
</style>

<script setup>

</script>