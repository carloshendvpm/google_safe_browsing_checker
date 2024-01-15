<script>
  async function handleSubmit(){
   
  }
</script>
<div class="bg-sky-950 w-screen h-screen flex items-center justify-center">
  <div class="bg-white shadow-lg w-1/3 flex items-center justify-center p-8 rounded-md">
    <form on:submit|preventDefault={handleSubmit} class="w-full flex flex-col gap-4">
      <p class="text-center font-bold text-2xl text-zinc-700">Check if your desire URL is safe!🚀</p>
      <div class="flex gap-2">
        <input type="text" class="outline-none border-2 border-red w-full" placeholder="https:sksksks">
        <button class="bg-sky-500 rounded-md px-4 py-2">Check</button>
      </div>
    </form>
  </div>
</div>