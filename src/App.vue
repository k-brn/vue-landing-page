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

        <!-- Responsive Menu -->
        <div class="lg:hidden">
          <!-- Add responsive menu icon/button here -->
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
  <section
    class="about-section bg-black py-16 flex flex-col-reverse items-center lg:flex-row"
  >
    <div
      class="container mx-auto flex flex-col lg:flex-row justify-between items-center"
    >
      <!-- About Us Text (To the Left) -->
      <div class="w-full lg:w-1/2 lg:pr-8 mb-8 lg:mb-0">
        <!-- Section Title -->
        <h2 class="text-creamy-white text-3xl lg:text-4xl font-bold mb-8">
          About Us
        </h2>

        <!-- Description -->
        <p class="text-creamy-white text-lg mb-4">
          Paperclip Studios is a creative hub dedicated to digital design and
          crafting unique products. Our mission is to unleash creativity and
          bring innovative ideas to life. We are passionate about delivering
          high-quality digital experiences and products that resonate with our
          clients and users.
        </p>

        <p class="text-creamy-white text-lg mb-4">
          Our team comprises skilled individuals with expertise in various areas
          of digital design.
        </p>

        <p class="text-creamy-white text-lg mb-4">
          Over the years, we have successfully delivered digital solutions to a
          diverse range of clients, earning recognition for our creativity and
          quality.
        </p>

        <!-- Call to Action -->
        <p class="text-creamy-white text-lg">
          Ready to collaborate with us?
          <a href="#" class="no-underline hover:underline"
            >Contact Paperclip Studios</a
          >
          today.
        </p>
      </div>

      <!-- Photo -->
      <div class="w-full lg:w-1/2 lg:pl-8">
        <img
          src="./assets/images/team-photo.jpg"
          alt="Team Photo"
          class="w-full h-full object-cover"
        />
      </div>
    </div>
  </section>
  <!-- Portfolio -->
  <section class="portfolio-section bg-gray-100 py-16">
    <div class="container mx-auto">
      <!-- Portfolio Title -->
      <h2 class="text-3xl font-bold mb-8">Featured Work</h2>

      <!-- Portfolio Items Container -->
      <div class="flex mb-8">
        <!-- Portfolio Item 1 -->
        <div class="w-1/2 pr-8">
          <!-- Image -->
          <img
            src="./assets/images/portfolio-item1.jpg"
            alt="Portfolio Item 1"
            class="w-full h-full object-cover mb-4"
          />

          <!-- Details (Text) -->
          <div>
            <p class="text-soft-blue text-lg mb-2">
              Website URL:
              <a href="https://www.example.com" target="_blank"
                >www.NovaSyncTechnologies.com</a
              >
            </p>
            <p class="text-black text-sm">Year: 2022</p>
          </div>
        </div>

        <!-- Portfolio Item 2 -->
        <div class="w-1/2 pl-8">
          <!-- Image -->
          <img
            src="./assets/images/portfolio-item2.jpg"
            alt="Portfolio Item 2"
            class="w-full h-full object-cover mb-4"
          />

          <!-- Details (Text) -->
          <div>
            <p class="text-soft-blue text-lg mb-2">
              Website URL:
              <a href="https://www.anotherexample.com" target="_blank"
                >www.QuantumByteSolutions.com</a
              >
            </p>
            <p class="text-black text-sm">Year: 2021</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Footer -->
  <footer class="bg-black text-creamy-white py-8">
    <div class="container mx-auto flex items-center justify-between">
      <div class="text-white text-lg font-bold">Paperclip Studios</div>

      <!-- Navigation Links -->
      <nav class="flex space-x-4 mr-4">
        <a href="#" class="hover:text-white">Home</a>
        <a href="#" class="hover:text-white">Services</a>
        <a href="#" class="hover:text-white">Portfolio</a>
        <a href="#" class="hover:text-white">About Us</a>
        <a href="#" class="hover:text-white">Contact</a>
      </nav>

      <!-- Social Media Icons -->
      <div class="flex space-x-4">
        <!-- Replace the href attribute with your actual social media links -->
        <a href="#" target="_blank" class="hover:text-white">
          <img
            src="./assets/images/facebook-icon.png"
            alt="Facebook"
            class="h-6 w-6"
          />
        </a>
        <a href="#" target="_blank" class="hover:text-white">
          <img
            src="./assets/images/twitter-icon.png"
            alt="Twitter"
            class="h-6 w-6"
          />
        </a>
        <a href="#" target="_blank" class="hover:text-white">
          <img
            src="./assets/images/instagram-icon.png"
            alt="Instagram"
            class="h-6 w-6"
          />
        </a>
        <a href="#" target="_blank" class="hover:text-white">
          <img
            src="./assets/images/tiktok-icon.png"
            alt="TikTok"
            class="h-6 w-6"
          />
        </a>
        <a href="#" target="_blank" class="hover:text-white">
          <img
            src="./assets/images/discord-icon.png"
            alt="Discord"
            class="h-6 w-6"
          />
        </a>
      </div>
    </div>
  </footer>
</template>

<style setup>
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
