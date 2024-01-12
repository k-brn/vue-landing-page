<template>
  <!-- Navbar -->
  <div>
    <nav class="bg-soft-blue p-4 text-creamy-white">
      <div class="container mx-auto flex items-center justify-between">
        <!-- Branding -->
        <div class="text-lg font-bold">Paperclip Studios</div>

        <!-- Navigation Links -->
        <div class="space-x-4">
          <router-link to="/" class="hover:text-gentle-green">Home</router-link>
          <router-link to="/services" class="hover:text-gentle-green"
            >Services</router-link
          >
          <router-link to="/portfolio" class="hover:text-gentle-green"
            >Portfolio</router-link
          >
          <router-link to="/about" class="hover:text-gentle-green"
            >About Us</router-link
          >
          <router-link to="contact" class="hover:text-gentle-green"
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
  <!-- About Us -->
  <!-- Services -->
  <!-- Portfolio -->
  <!-- Creative Process -->
  <!-- Testimonials -->
  <!-- Contact -->
  <!-- Footer -->
</template>

<style setup>
/* Global styles here */

.bg-soft-blue {
  background-color: #8cc4d7;
}

.text-creamy-white {
  color: #f9f9f9;
}

.hover\:text-gentle-green:hover {
  color: #b8d9bf;
}

/* Additional adjustments */
nav a {
  color: #f9f9f9;
}

nav a:hover {
  color: #b8d9bf;
}
</style>
