
<template>
    <div>
        <slot/>
        <app-nabar></app-nabar>
    </div>
</template>
<style>
.page-enter-active,
.page-leave-active {
    transition: all 0.5s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}

.page-enter-from,
.page-leave-to {
    opacity: 0;
    transform: scale(0.8) rotateY(-20deg);
}
</style>
