<script setup lang="ts">
import HomeItem from './HomeItem.vue'
import TerminalIcon from './icons/IconTerminal.vue'
import AndroidIcon from './icons/IconAndroid.vue'
import AppleIcon from './icons/IconApple.vue'
import DevicesIcon from './icons/IconDevices.vue'
import ImportMaterial from './ImportMaterial.vue'
</script>

<template>
  <ImportMaterial />
  <HomeItem>
    <template #icon>
      <DevicesIcon />
    </template>
    <template #heading>Tech Collector</template>
      I collect tech. Dunno what else to say here.
  </HomeItem>

  <HomeItem>
    <template #icon>
      <AndroidIcon />
    </template>
    <template #heading>Android Enthusiast</template>
      Custom ROMs, Root, and most importantly, unlocked bootloaders, are my thing.
  </HomeItem>

  <HomeItem>
    <template #icon>
      <AppleIcon />
    </template>
    <template #heading>iOS Enthusiast too</template>
      The heading of this section is foreshadowing. 
  </HomeItem>

  <HomeItem>
    <template #icon>
      <TerminalIcon />
    </template>
    <template #heading>Wannabe programmer</template>
      I'm learning C# and Vue.js
      <br>
      The language I know best is JavaScript(ironic, innit?)
  </HomeItem>
</template>
