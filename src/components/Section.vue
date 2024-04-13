<template>
  <div class="flex flex-col space-y-4">
    <span class="text-base font-bold tracking-wide text-neutral-200">
      <slot name="heading"></slot>
    </span>
    <div class="text-neutral-400 leading-6">
      <slot name="details"></slot>
    </div>
  </div>
</template>
