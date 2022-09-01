<template>
  <div>
    <Nav />
    <div id="hero" class="flex flex-col h-screen bg-slate-600 align-middle text-white text-center">
      <div class="m-auto flex flex-col">
        <h1 class="text-5xl">BOVAEA revision site</h1>
        <p class="mt-5">part 1 exam practice &#38; revision materials</p>
        <button id="box" class="m-10 w-60 h-60 bg-blue-500" @click="incrementCount">
          <p class="m-auto font-bold text-3xl">Box</p>
        </button>
        <p>{{ count }}</p>
        <div>
            <div v-for="event in events" :key="event.clientX" :value="event.clientY">{{ event.clientX }}: {{ event.clientY }}</div>
              <!--
              <div v-for="(value, key) in event" :key="key" :value="value">
                {{ key }}: {{ value}}
              </div>
              -->
            <p> hello </p>
            <p> {{ events[1] }} </p>
            <p> {{ events[2] }} </p>
        </div>
      </div>
    </div>
    <Contact />
    <Footer />
  </div>
</template>

<script>
export default {
  loading: {
    color: 'blue',
    height: '5px'
  },
  data() {
    return {
      count: 0,
      // box: process.client.window,
      events: [{}],
    }
  },
  head() {

  },
  computed: {

  },
  beforeCreate () {
    if (process.client) {
      if (document) {
        console.log('document');
      } else {
        console.log('=(');
      }
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$nuxt.$loading.start()
      setTimeout(() => this.$nuxt.$loading.finish(), 3000)
    });
  },
  methods: {
    incrementCount(e) {
      this.count++;
      console.log(this.count); // logging
      this.events.push(e);
      console.log('length = ' + this.events.length);
    }
  },
}
</script>
