<!--
  K-Deal version 1.0

  Copyright© 2023 kt corp. All rights reserved.

  This is a proprietary software of kt corp, and you may not use this file except in
  compliance with license agreement with kt corp. Any redistribution or use of this
  software, with or without modification shall be strictly prohibited without prior written
  approval of kt corp, and the copyright notice above does not evidence any actual or
  intended publication of such software.
-->
<template>
  <div id="app">
    <div class="content-container">
      <MainHeader/>
    </div>
  </div>
</template>

<script>
// Button Components
import MainHeader from '@/components/Header.vue'

export default {
  name: 'App',
  components: { MainHeader }
}
</script>

<style>

div.content-container {
  min-height: 100vh;
  max-width: 640px;
  margin: 0 auto;
}

</style>
