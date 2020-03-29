<template>
  <vue-drawer-layout :right-width="200" :left-width="200">
    <div class="drawer" slot="drawer-right">
      <div class="text">This is right drawer</div>
    </div>
    <div class="drawer" slot="drawer-left">
      <div class="text">This is left drawer</div>
    </div>
    <div class="content" slot="content">
      <div class="text">This is content.</div>
    </div>
  </vue-drawer-layout>
</template>
