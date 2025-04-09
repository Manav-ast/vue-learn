<!-- <script setup>
const model = defineModel();

function update() {
    model.value++;
}
</script>

<template>
  <div>Parent bound v-model is: {{ model }}</div>
  <button @click="update">Increment</button>
</template> -->


<!-- <script setup>
import { computed } from 'vue'

const [model, modifiers] = defineModel({
  set(value) {
    if (modifiers.capitalize) {
      return value.charAt(0).toUpperCase() + value.slice(1)
    }
    return value
  }
})

console.log(modifiers);

</script>

<template>
  <input type="text" v-model="model" />
</template> -->


<!-- <script setup>

</script> -->

<template>
    <button>
        <slot>
            <span>Default slot content</span>
        </slot>
    </button>
</template>