<script setup lang="ts">
// @ts-expect-error missing types
import ScrollSync from 'scroll-sync'

onNuxtReady(() => {
  const ss = new ScrollSync({
    disabled: false, // [Boolean] Default value, allow to be empty.
    relative: true, // [Boolean] Default value, allow to be empty.
    doms: document.querySelectorAll('.scroll-container'), // [Array] These elements must set scroll attributes.
  })
})
</script>

<template>
  123456
  <div class="h-full flex">
    <div class="scroll-container h-100px overflow-auto">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita est tenetur corporis blanditiis deserunt optio porro maiores illum, enim eveniet beatae, culpa totam odit, molestias quos adipisci! Perferendis, temporibus facilis.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut dolorum ullam praesentium accusantium, inventore quisquam natus impedit suscipit itaque ad dolorem ratione expedita doloremque nostrum laboriosam voluptate atque deleniti? Excepturi.
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, soluta accusamus? Magnam expedita labore non ipsam. Debitis nulla nisi totam porro facilis ab, maxime, nihil iure doloremque veritatis excepturi. Voluptatem!
    </div>
    <div class="scroll-container h-100px overflow-auto">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad quasi aliquid dolores magnam perspiciatis expedita voluptatem laudantium excepturi nulla molestias, explicabo praesentium ullam pariatur dignissimos! Cum quos doloremque laboriosam omnis!
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, optio facilis! Fugiat et placeat natus adipisci eius, tempore iusto suscipit. Deleniti ducimus inventore harum, repudiandae mollitia unde fuga voluptates molestias.
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quos cupiditate tenetur voluptate atque mollitia dignissimos necessitatibus est eos culpa laborum repellendus magni ab nulla, voluptatum velit! Dolor dolores voluptas mollitia.
    </div>
  </div>
</template>

<style>

</style>
