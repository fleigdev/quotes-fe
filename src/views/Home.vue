<template>
  <div class="home">
    <div class="mx-auto max-w-screen-lg">
      <div class="flex items-center flex-col justify-center">
        <div class="btn" @click="$store.commit('GetRandomQuote')">
          Get Random Quote
        </div>
        <p class="my-5 text-2x1 text-center text-gray-500">
          <span> "{{ $store.state.quote.content }}" </span><br />
          <span class="text-gray-400"> "{{ $store.state.quote.author }}" </span>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {};
</script>
