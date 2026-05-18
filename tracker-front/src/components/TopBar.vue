<template>
    <div class="top-bar-base">
        <div class="top-bar-content">
            <div style="display: flex; margin-left: 30px;">
                <div><svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-funnel-icon lucide-funnel">
                        <path
                            d="M10 20a1 1 0 0 0 .553.895l2 1A1 1 0 0 0 14 21v-7a2 2 0 0 1 .517-1.341L21.74 4.67A1 1 0 0 0 21 3H3a1 1 0 0 0-.742 1.67l7.225 7.989A2 2 0 0 1 10 14z" />
                    </svg></div>
                <div class="current-group">
                    <div><svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none"
                            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                            class="lucide lucide-house-heart-icon lucide-house-heart">
                            <path
                                d="M8.62 13.8A2.25 2.25 0 1 1 12 10.836a2.25 2.25 0 1 1 3.38 2.966l-2.626 2.856a.998.998 0 0 1-1.507 0z" />
                            <path
                                d="M3 10a2 2 0 0 1 .709-1.528l7-6a2 2 0 0 1 2.582 0l7 6A2 2 0 0 1 21 10v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z" />
                        </svg></div>
                    Личные
                </div>
            </div>
            <div style="margin-right: 30px;"><svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none"
                        stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                        class="lucide lucide-bell-icon lucide-bell">
                        <path d="M10.268 21a2 2 0 0 0 3.464 0" />
                        <path
                            d="M3.262 15.326A1 1 0 0 0 4 17h16a1 1 0 0 0 .74-1.673C19.41 13.956 18 12.499 18 8A6 6 0 0 0 6 8c0 4.499-1.411 5.956-2.738 7.326" />
                    </svg></div>
        </div>
    </div>


</template>

<style scoped>
.top-bar-content {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.top-bar-base {
    width: 100%;
    height: 103px;
    background-color: var(--component-background-light);
    border-radius: 75px;
}

.current-group {
    width: 185px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 24pt;
    font-family: Montserrat-regular;
    margin-left: 50px;
}
</style>