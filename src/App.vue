<script setup>
import { ref } from 'vue';
import HelloWorld from './components/HelloWorld.vue';

// const msg = ref('Hello World');

// const dynamicId = false;
// const isButtonDisabled = ref(true);
// const seen = ref(false);

// function increment() {
//   msg.value += '!';
// }

// const count = ref(0);
// function countNum() {
//   count.value++;
// }

// import { reactive, computed } from 'vue'

// const state = reactive({ count: 0 })


// const author = reactive({
//   name: 'John Doe',
//   books: [
//     'vue 2 - The Complete Guide',
//     'vue 3 - The Complete Guide adjf',
//     'vue 4 - The Complete Guide - 2023 Edition',]
// })

// const publishedBooksMessage = computed(() => {
//   return author.books.length > 0 ? 'Yes' : 'No'
// })

// const carList = reactive([
//     { make: 'Honda', model: 'Accord', year: 1998 },
//     { make: 'Toyota', model: 'Camry', year: 2008 },
//     { make: 'Ford', model: 'Focus', year: 2020 },
// ])

// const myObject = reactive({
//   title: 'How to do lists in Vue',
//   author: 'Jane Doe',
//   publishedAt: '2016-04-10'
// })


// const numbers = ref([1, 2, 3, 4, 5])

// const evenNumbers = computed(() => {
//   return numbers.value.filter((n) => n % 2 === 0)
// })


// const sets = ref([
//   [1, 2, 3, 4, 5],
//   [6, 7, 8, 9, 10]
// ])

// function even(numbers) {
//   return numbers.filter((number) => number % 2 === 0)
// }
// const fontSize = ref(40)

// const name = ref('Vue.js')

// function greet(event) {
//   alert(`Hello ${name.value}!`)
//   // `event` is the native DOM event
//   if (event) {
//     alert(event.target.tagName)
//   }
// }

// function say(message) {
//   alert(message);
// }


// function warn(message, event) {
//   // now we have access to the native event
//   if (event) {
//     event.preventDefault()
//   }
//   alert(message)
// }
// const message = ref('Hello World!');


// const checkedNames = ref([]);

// const selected = ref();

// const selected = ref('A')

// const options = ref([
//   { text: 'One', value: 'A' },
//   { text: 'Two', value: 'B' },
//   { text: 'Three', value: 'C' }
// ])
</script>

<template>
<input
  type="checkbox"
  v-model="toggle"
  true-value="yes"
  false-value="no" />

<!-- <select v-model="selected">
  <option v-for="option in options" :value="option.text" :key="option.value">
    {{ option.text }}
  </option>
</select>

<div>Selected: {{ selected }}</div> -->
<!-- <div>Selected: {{ selected }}</div>

<select v-model="selected" multiple>
  <option disabled >Please select one</option>
  <option>A</option>
  <option>B</option>
  <option>C</option>
</select> -->

<!-- <div>Checked Name : {{ checkedNames }}</div>

<input type="checkbox" id="jack" value="Jack" v-model="checkedNames" />
<label for="jack">Jack</label>

<input type="checkbox" id="john" value="John" v-model="checkedNames" />
<label for="john">John</label>

<input type="checkbox" id="mike" value="Mike" v-model="checkedNames" /> -->
<!-- <label for="mike">Mike</label> -->

<!-- 
<textarea v-model="text"></textarea>

  <h1>Messge ; {{ message }}</h1><br>
  <input v-model="message" placeholder="edit me" /> -->
  <!-- <input type="text" @keyup.alt.enter="clear" /> -->

<!-- using $event special variable -->
<!-- <button @click="warn('Form cannot be submitted yet.', $event)">
  Submit
</button> -->

<!-- using inline arrow function -->
<!-- <button @click="(event) => warn('Form cannot be submitted yet.', event)">
  Submit
</button> -->


<!-- <button @click="say('Hello, World')">Say Hello</button>
<button @click="say('Good Bye')">Say Bye</button> -->
<!-- `greet` is the name of the method defined above -->
<!-- <button @click="greet">Greet</button> -->

  <!-- <button @click="count--">Minus -1</button>
  <button @click="count++">Add +1</button><br>
  <p :style="{ fontSize : fontSize + 'px'}">{{ count }}</p>
  <ul v-for="numbers in sets">
    <p >{{ numbers }}</p>
  <li v-for="n in even(numbers)">{{ n }}</li>
</ul> -->

<!-- <li v-for="n in even">{{ n }}</li> -->
<!-- <ul>
  <li v-for="(value, key) in myObject" :key="myObject.title">
   {{ value }} {{ key }}
  </li>
</ul> -->


<!-- <ul>
  <li v-for="({ make, model } , index ) in carList" :key="carList.make"> -->
    <!-- {{ car.make }} - {{ car.model }} - {{ car.year }} -->
    <!-- {{ make }}
    {{ model }}
    {{ index }}
  </li>
</ul> -->

<!-- <p>Has published books:</p>
<span>{{ publishedBooksMessage }}</span>

<button @click="state.count++">
  {{ state.count }}
</button>-->


<!-- 
  <button @click="countNum">
    {{ count }}
  </button> -->

  <!-- <h1>{{ msg }}</h1>
  <button @click="increment">Increment</button>

  <p v-for="item in [1, 2, 3, 4, 5]">
    {{ item }}
  </p> -->

  <!-- <button :disabled="isButtonDisabled">Button</button>

  <h1 :id="dynamicId"> {{ msg.length() }}</h1> -->

  <!-- message.split('').reverse().join('') -->
  <!-- <h1>{{ msg }}</h1> -->
</template>