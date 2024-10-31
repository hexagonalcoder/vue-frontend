<template>
  <div class="min-h-screen bg-gray-900 text-gray-100 font-sans">
    <!-- Navbar -->
    <header class="bg-gray-800 p-4 shadow-lg">
      <nav class="container mx-auto flex justify-between items-center">
        <h1 class="text-3xl font-bold">My Tailwind App</h1>
        <ul class="flex space-x-6 text-lg">
          <li><a href="#" class="hover:text-blue-400">Home</a></li>
          <li><a href="#" class="hover:text-blue-400">About</a></li>
          <li><a href="#" class="hover:text-blue-400">Contact</a></li>
        </ul>
      </nav>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto mt-8 px-4">
      <!-- Hero Section -->
      <section class="text-center mb-12">
        <h2 class="text-5xl font-extrabold mb-4">Welcome to My Vue App</h2>
        <p class="text-xl text-gray-300 mb-6">This app is styled with Tailwind CSS</p>
        <button class="px-6 py-3 bg-blue-500 text-white font-semibold rounded-lg shadow hover:bg-blue-600 transition">
          Get Started
        </button>
      </section>

      <!-- Responsive Grid of Cards -->
      <section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-12">
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 class="text-2xl font-bold mb-2">Feature One</h3>
          <p class="text-gray-400 mb-4">This is an example of a card. It can contain any content you'd like.</p>
          <a href="#" class="text-blue-400 hover:underline">Learn more</a>
        </div>
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 class="text-2xl font-bold mb-2">Feature Two</h3>
          <p class="text-gray-400 mb-4">Another card to show off Tailwind's grid and spacing utilities.</p>
          <a href="#" class="text-blue-400 hover:underline">Learn more</a>
        </div>
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 class="text-2xl font-bold mb-2">Feature Three</h3>
          <p class="text-gray-400 mb-4">Add as many cards as you like to demonstrate the grid layout.</p>
          <a href="#" class="text-blue-400 hover:underline">Learn more</a>
        </div>
      </section>

      <!-- Flexbox Layout Example -->
      <section class="flex flex-col md:flex-row items-center justify-around bg-gray-700 p-8 rounded-lg">
        <div class="text-center md:text-left">
          <h3 class="text-3xl font-semibold mb-4">Another Section</h3>
          <p class="text-gray-400 max-w-md">Tailwind makes it easy to build responsive layouts with flexbox and grid. Resize the screen to see the layout change.</p>
        </div>
        <div class="mt-8 md:mt-0">
          <button class="px-6 py-3 bg-green-500 text-white font-semibold rounded-lg shadow hover:bg-green-600 transition">
            Explore More
          </button>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 p-4 text-center text-gray-400 mt-12">
      &copy; 2024 My Tailwind App. All rights reserved.
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style scoped>
/* Scoped styles if needed, but Tailwind covers most of the styling */
</style>
