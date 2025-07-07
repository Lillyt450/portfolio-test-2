<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Creative Design Portfolio</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap">
  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-[#f7f7f7] text-gray-900 font-inter">
  <!-- Hero Section -->
  <header class="pt-32 pb-20 px-6 md:px-12 lg:px-24 text-center relative overflow-hidden">
    <div class="hero-bg"></div>
    <h1 class="text-5xl md:text-7xl font-black mb-6 leading-tight tracking-tight animate-fade-in-up">
      Creative<br>Design<br>Portfolio
    </h1>
    <p class="text-xl md:text-2xl max-w-xl mb-8 mx-auto animate-fade-in-up delay-150">
      Showcasing a collection of graphic and motion design projects that push creative boundaries.
    </p>
    <a href="#work" class="inline-block bg-black text-white px-8 py-3 rounded-full hover:bg-gray-800 transition-colors shadow-lg animate-bounce-once focus:outline-none focus:ring-4 focus:ring-black/10">
      View Work
    </a>
  </header>

  <!-- About Section -->
  <section id="about" class="py-20 px-6 md:px-12 lg:px-24 bg-white">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-3xl font-bold mb-8 fade-in-section">About</h2>
      <div class="flex flex-col md:flex-row gap-12">
        <div class="md:w-1/2 fade-in-section delay-100">
          <p class="text-lg mb-4">I'm a multidisciplinary designer specializing in graphic design and motion design with over 5 years of experience creating compelling visual narratives.</p>
          <p class="text-lg">My approach combines strategic thinking with creative execution to deliver designs that not only look beautiful but also effectively communicate the intended message.</p>
        </div>
        <div class="md:w-1/2 fade-in-section delay-200">
          <h3 class="text-xl font-semibold mb-4">Skills</h3>
          <div class="grid grid-cols-2 gap-4">
            <div>
              <h4 class="font-medium">Design</h4>
              <ul class="text-gray-600 space-y-1">
                <li>Brand Identity</li>
                <li>Typography</li>
                <li>UI/UX Design</li>
                <li>Print Design</li>
              </ul>
            </div>
            <div>
              <h4 class="font-medium">Motion</h4>
              <ul class="text-gray-600 space-y-1">
                <li>Animation</li>
                <li>Video Editing</li>
                <li>Motion Graphics</li>
                <li>3D Modeling</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Work Section -->
  <section id="work" class="py-20 px-6 md:px-12 lg:px-24">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold mb-12 fade-in-section">Selected Work</h2>
      <!-- Portfolio Navigation -->
      <div class="flex border-b border-gray-200 mb-12">
        <button id="graphicBtn" class="py-2 px-4 mr-8 section-active text-lg font-medium transition-all duration-200" onclick="showSection('graphic')">Graphic Design</button>
        <button id="motionBtn" class="py-2 px-4 section-inactive text-lg font-medium transition-all duration-200" onclick="showSection('motion')">Motion Design</button>
      </div>
      <!-- Graphic Design Portfolio -->
      <div id="graphicDesign" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 fade-in-section">
        <!-- Project Cards -->
        <div class="portfolio-item rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl">
          <div class="h-64 bg-[#E8D5C4] flex items-center justify-center relative">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-gray-800 opacity-80 group-hover:scale-110 transition-transform"></svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Brand Identity</h3>
            <p class="text-gray-600">Complete visual identity system for a sustainable fashion brand.</p>
          </div>
        </div>
        <div class="portfolio-item rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl">
          <div class="h-64 bg-[#7D9D9C] flex items-center justify-center relative">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90 group-hover:scale-110 transition-transform"></svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Editorial Design</h3>
            <p class="text-gray-600">Magazine layout and typography for an arts publication.</p>
          </div>
        </div>
        <div class="portfolio-item rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl">
          <div class="h-64 bg-[#576F72] flex items-center justify-center relative">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90 group-hover:scale-110 transition-transform"></svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Packaging Design</h3>
            <p class="text-gray-600">Product packaging for an artisanal coffee company.</p>
          </div>
        </div>
        <div class="portfolio-item rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl">
          <div class="h-64 bg-[#F0EBE3] flex items-center justify-center relative">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-gray-800 opacity-80 group-hover:scale-110 transition-transform"></svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">UI/UX Design</h3>
            <p class="text-gray-600">Mobile app interface for a wellness platform.</p>
          </div>
        </div>
        <div class="portfolio-item rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl">
          <div class="h-64 bg-[#E3CAA5] flex items-center justify-center relative">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-gray-800 opacity-80 group-hover:scale-110 transition-transform"></svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Poster Series</h3>
            <p class="text-gray-600">Collection of event posters for a music festival.</p>
          </div>
        </div>
        <div class="portfolio-item rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl">
          <div class="h-64 bg-[#CEAB93] flex items-center justify-center relative">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-gray-800 opacity-80 group-hover:scale-110 transition-transform"></svg>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Brand Guidelines</h3>
            <p class="text-gray-600">Comprehensive style guide for a tech startup.</p>
          </div>
        </div>
      </div>
      <!-- Motion Design Portfolio -->
      <div id="motionDesign" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 hidden fade-in-section">
        <!-- Motion Projects -->
        <div class="portfolio-item motion-card rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl cursor-pointer" onclick="openModal('Motion Reel', 'A compilation of motion graphics work showcasing various techniques and styles.')">
          <div class="h-64 bg-[#3D5656] flex items-center justify-center relative group">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90"></svg>
            <div class="motion-overlay group-hover:opacity-100">
              <div class="play-button"></div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Motion Reel</h3>
            <p class="text-gray-600">A compilation of motion graphics work.</p>
          </div>
        </div>
        <div class="portfolio-item motion-card rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl cursor-pointer" onclick="openModal('Brand Animation', 'Logo animation and motion identity system for a technology company.')">
          <div class="h-64 bg-[#395B64] flex items-center justify-center relative group">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90"></svg>
            <div class="motion-overlay group-hover:opacity-100">
              <div class="play-button"></div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Brand Animation</h3>
            <p class="text-gray-600">Logo animation and motion identity system.</p>
          </div>
        </div>
        <div class="portfolio-item motion-card rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl cursor-pointer" onclick="openModal('Explainer Video', 'Animated explainer video for a fintech app that simplifies complex concepts through visual storytelling.')">
          <div class="h-64 bg-[#2C3333] flex items-center justify-center relative group">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90"></svg>
            <div class="motion-overlay group-hover:opacity-100">
              <div class="play-button"></div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Explainer Video</h3>
            <p class="text-gray-600">Animated explainer for a fintech app.</p>
          </div>
        </div>
        <div class="portfolio-item motion-card rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl cursor-pointer" onclick="openModal('Title Sequence', 'Opening title sequence for a documentary film with dynamic typography and visual effects.')">
          <div class="h-64 bg-[#4F4557] flex items-center justify-center relative group">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90"></svg>
            <div class="motion-overlay group-hover:opacity-100">
              <div class="play-button"></div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Title Sequence</h3>
            <p class="text-gray-600">Opening titles for a documentary film.</p>
          </div>
        </div>
        <div class="portfolio-item motion-card rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl cursor-pointer" onclick="openModal('3D Animation', 'Product visualization with 3D animation showcasing features and design details.')">
          <div class="h-64 bg-[#6D5D6E] flex items-center justify-center relative group">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90"></svg>
            <div class="motion-overlay group-hover:opacity-100">
              <div class="play-button"></div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">3D Animation</h3>
            <p class="text-gray-600">Product visualization with 3D animation.</p>
          </div>
        </div>
        <div class="portfolio-item motion-card rounded-lg overflow-hidden bg-white group hover:scale-[1.03] transition-transform shadow-lg hover:shadow-xl cursor-pointer" onclick="openModal('Social Media Animations', 'Series of short animations designed for social media campaigns with engaging visual storytelling.')">
          <div class="h-64 bg-[#393646] flex items-center justify-center relative group">
            <svg xmlns="http://www.w3.org/2000/svg" width="80" height="80" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-white opacity-90"></svg>
            <div class="motion-overlay group-hover:opacity-100">
              <div class="play-button"></div>
            </div>
          </div>
          <div class="p-6">
            <h3 class="text-xl font-semibold mb-2">Social Media Animations</h3>
            <p class="text-gray-600">Short animations for social campaigns.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 px-6 md:px-12 lg:px-24 bg-white">
    <div class="max-w-4xl mx-auto">
      <h2 class="text-3xl font-bold mb-12 fade-in-section">Get in Touch</h2>
      <div class="flex flex-col md:flex-row gap-12">
        <div class="md:w-1/2 fade-in-section delay-100">
          <p class="text-lg mb-8">Interested in working together? Feel free to reach out for collaborations or just a friendly hello.</p>
          <div class="space-y-4">
            <div class="flex items-center gap-3">
              <span class="icon-email"></span>
              <span>hello@designportfolio.com</span>
            </div>
            <div class="flex items-center gap-3">
              <span class="icon-phone"></span>
              <span>+1 (555) 123-4567</span>
            </div>
            <div class="flex items-center gap-3">
              <span class="icon-location"></span>
              <span>New York, NY</span>
            </div>
          </div>
          <div class="mt-8 flex space-x-4">
            <a href="#" class="social-icon icon-linkedin"></a>
            <a href="#" class="social-icon icon-twitter"></a>
            <a href="#" class="social-icon icon-instagram"></a>
            <a href="#" class="social-icon icon-youtube"></a>
          </div>
        </div>
        <div class="md:w-1/2 fade-in-section delay-200">
          <form class="space-y-4" id="contactForm">
            <div>
              <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Name</label>
              <input type="text" id="name" required class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-black focus:border-transparent">
            </div>
            <div>
              <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
              <input type="email" id="email" required class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-black focus:border-transparent">
            </div>
            <div>
              <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
              <textarea id="message" rows="4" required class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-black focus:border-transparent"></textarea>
            </div>
            <button type="submit" class="bg-black text-white px-6 py-3 rounded-md hover:bg-gray-800 transition-colors shadow-md">Send Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-8 px-6 md:px-12 bg-gray-100 text-center text-gray-500">
    <p>© 2025 Design Portfolio. All rights reserved.</p>
  </footer>

  <!-- Video Modal -->
  <div id="videoModal" class="fixed inset-0 bg-black bg-opacity-80 z-50 flex items-center justify-center hidden modal">
    <div class="bg-white rounded-lg max-w-3xl w-full mx-4 shadow-2xl animate-fade-in-up">
      <div class="p-6">
        <div class="flex justify-between items-center mb-4">
          <h3 id="modalTitle" class="text-xl font-bold"></h3>
          <button onclick="closeModal()" class="text-gray-500 hover:text-gray-700 focus:outline-none">
            <span class="icon-close"></span>
          </button>
        </div>
        <div class="bg-gray-100 h-64 flex items-center justify-center rounded-lg mb-4">
          <span class="icon-play-lg"></span>
        </div>
        <p id="modalDescription" class="text-gray-600 mb-6"></p>
        <div class="flex justify-end">
          <button onclick="closeModal()" class="bg-black text-white px-4 py-2 rounded-md hover:bg-gray-800 transition-colors shadow-md">Close</button>
        </div>
      </div>
    </div>
  </div>

  <script src="scripts.js"></script>
</body>
</html>
