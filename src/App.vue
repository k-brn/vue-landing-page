<template>
  <!-- Navbar -->
  <div>
    <nav class="bg-black p-4 text-creamy-white">
      <div class="container mx-auto flex items-center justify-between">
        <!-- Branding -->
        <div class="text-lg font-bold">Paperclip Studios</div>

        <!-- Navigation Links -->
        <div class="space-x-4">
          <router-link to="/" class="no-underline hover:underline"
            >Home</router-link
          >
          <router-link to="/services" class="no-underline hover:underline"
            >Services</router-link
          >
          <router-link to="/portfolio" class="no-underline hover:underline"
            >Portfolio</router-link
          >
          <router-link to="/about" class="no-underline hover:underline"
            >About Us</router-link
          >
          <router-link to="contact" class="no-underline hover:underline"
            >Contact</router-link
          >
        </div>

        <!-- Responsive Menu (for smaller screens) -->
        <div class="lg:hidden">
          <!-- Add your responsive menu icon/button here -->
        </div>
      </div>
    </nav>
  </div>
  <!-- Hero -->
  <section
    class="hero-section relative overflow-hidden bg-soft-blue h-screen flex items-center"
  >
    <!-- Hero Image -->
    <div class="absolute inset-0 overflow-hidden">
      <img
        src="./assets/images/hero-image.jpg"
        alt="Workspace"
        class="w-full h-full object-cover"
      />
      <!-- Semi-transparent overlay -->
      <div class="absolute inset-0 bg-black opacity-40"></div>
    </div>

    <!-- Container -->
    <div class="container mx-auto text-center relative z-10">
      <!-- Headline -->
      <h1
        class="text-4xl lg:text-5xl xl:text-6xl font-bold text-creamy-white mb-6"
      >
        Unleash Your Creativity with Paperclip Studios
      </h1>

      <!-- Call to Action -->
      <router-link to="/start" class="btn-primary">
        Start Crafting
      </router-link>
    </div>
  </section>
  <!-- About Us -->
  <!-- Services -->
  <!-- Portfolio -->
  <!--  skip Creative Process -->
  <!--  skip Testimonials -->
  <!-- Contact -->
  <!-- Footer -->
</template>

<style setup>
/* Global styles here */

.btn-primary {
  background-color: #ff0000;
  color: #f9f9f9;
  padding: 10px 20px;
  font-size: 18px;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.btn-primary:hover {
  background-color: #a00000;
}

.text-creamy-white {
  color: #f9f9f9;
}

nav a {
  color: #f9f9f9;
}

nav a:hover {
  color: #b8d9bf;
}
</style>
