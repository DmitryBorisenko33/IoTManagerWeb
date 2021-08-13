<script>
  export let title;
</script>

<div class="container">
  <!-- Card Container -->
  <div class="grid place-items-center mx-2 sm:my-auto">
    <!-- Card -->
    <div class="w-11/12 p-12 sm:w-8/12 md:w-6/12 lg:w-5/12 2xl:w-4/12 px-6 py-10 my-5 sm:px-10 sm:py-6 bg-white rounded-lg shadow-md lg:shadow-lg">
      <!-- Card Title -->
      <h1 class="text-center text-lg text-gray-500 font-bold pb-6">{title}</h1>
      <slot />
    </div>
  </div>
</div>
