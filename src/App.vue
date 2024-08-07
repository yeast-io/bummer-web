<script setup>
import Header from './components/Header.vue';
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="min-h-screen bg-slate-200 dark:text-white">
    <Header />
    <main class="flex-1 mx-auto min-h-screen px-20 pt-32">
      <div class="items-center justify-center card bg-white w-auto shadow-xl text-black">

        <div class="card-body">
          <div class="card-title pt-4">
            <label class="input input-bordered flex items-center gap-2 bg-white">
              <input type="text" class="grow" placeholder="Search" />
              <span class="badge badge-info">Optional</span>
            </label>
            <p> - </p>
            <label class="input input-bordered flex items-center gap-2 bg-white">
              <input type="text" class="grow" placeholder="Search" />
              <span class="badge badge-info">Optional</span>
            </label>
          </div>
          <div class="divider divider-accent"></div>
          <p>If a dog chews shoes whose shoes does he choose?</p>
          <div class="card-actions justify-end">
            <button class="btn btn-primary">Buy Now</button>
          </div>
        </div>
      </div>
    </main>
<!--    <Footer />-->
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
