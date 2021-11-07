<template>
    <header class="AppHeader">
        <nav class="AppHeader__nav" aria-label="グローバルメニュー">
            <AppMenuTrigger />
            <div class="AppHeader__list" role="list">
                <div class="AppHeader__home" role="listitem">
                    <router-link to="/" class="AppHeader__homeLink"></router-link>
                </div>

                <div class="AppHeader__note" role="listitem">
                    <router-link to="/production-note" class="AppHeader__noteLink"></router-link>
                </div>

                <div class="AppHeader____content">
                    <AppMenu />>
                </div>
            </div>
        </nav>
    </header>
</template>

<style lang="scss" scoped>

</style>