<template>
  <div 
    v-if="$slidev.nav.currentPage !== 1 && $slidev.nav.currentPage !== $slidev.nav.total"
    class="absolute bottom-2 left-2 text-[10px] flex gap-2"
    style="color: var(--slidev-theme-primary);"
  >
    <span>INTED 2026: From Shape to Sound</span>
    <span class="opacity-50">|</span>
    <span>Kjetil Falkenberg</span>
    <span class="opacity-50">|</span>
    <span>{{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}</span>
  </div>
</template>