<template>
  <Card>
    <ParticlesComponent id="jkawhdlkjawhdkjawh"/>
  </Card>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import HelloWorld from '@/components/HelloWorld.vue'
import Card from '@/components/Card.vue'
import { ParticlesComponent } from 'particles.vue3'

@Options({
  components: {
    ParticlesComponent,
    Card,
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>
