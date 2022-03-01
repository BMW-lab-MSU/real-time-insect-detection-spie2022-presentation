<template>
    <footer 
    v-if="
        $slidev.nav.currentLayout !== 'cover' && 
        $slidev.nav.currentLayout !== 'section' &&
        $slidev.nav.currentLayout !== 'intro'" 
    class="absolute bottom-0 right-0 p-1 text-gray-500 text-xs" > 
        {{ $slidev.nav.currentPage }}
    </footer>
</template>
