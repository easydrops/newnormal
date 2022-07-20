<template>
  <main
    class="bg-top flex flex-col justify-center items-center relative bg-no-repeat main-bg-color"
    :style="{ backgroundImage: `url(${image})` }"
  >
    <div class="w-9/12 p-12">
      <h1 class="w-4 text-black">NEW NORMAL 2022</h1>
      <h2 class="w-4 text-black">2.−4. SEPTEMBER PROJEKTRAUM KUNSTVEREIN WAGENHALLE STUTTGART</h2>
    </div>
  </main>
</template>

<script>
import nnRoots from 'assets/nn_roots.png'
export default {
  data() {
    return {
      image: nnRoots,
    }
  },
}
</script>
<style></style>
