<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1" name="viewport"/>
  <title>
   Rafa - Personal Portfolio
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
      font-family: 'Poppins', sans-serif;
    }
  </style>
 </head>
 <body class="bg-white text-gray-900">
  <!-- Navbar -->
  <nav class="fixed w-full bg-white shadow-md z-50">
   <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
    <a class="text-2xl font-bold text-indigo-600" href="#">
     Rafa
    </a>
    <div class="hidden md:flex space-x-8 text-gray-700 font-semibold">
     <a class="hover:text-indigo-600 transition" href="#home">
      Home
     </a>
     <a class="hover:text-indigo-600 transition" href="#about">
      About
     </a>
     <a class="hover:text-indigo-600 transition" href="#projects">
      Projects
     </a>
     <a class="hover:text-indigo-600 transition" href="#contact">
      Contact
     </a>
    </div>
    <div class="md:hidden">
     <button class="focus:outline-none" id="menu-btn">
      <i class="fas fa-bars text-2xl text-gray-700">
      </i>
     </button>
    </div>
   </div>
   <div class="hidden md:hidden px-6 pb-4 space-y-3 text-gray-700 font-semibold" id="mobile-menu">
    <a class="block hover:text-indigo-600 transition" href="#home">
     Home
    </a>
    <a class="block hover:text-indigo-600 transition" href="#about">
     About
    </a>
    <a class="block hover:text-indigo-600 transition" href="#projects">
     Projects
    </a>
    <a class="block hover:text-indigo-600 transition" href="#contact">
     Contact
    </a>
   </div>
  </nav>
  <!-- Hero Section -->
  <section class="pt-24 bg-indigo-50 min-h-screen flex items-center" id="home">
   <div class="max-w-7xl mx-auto px-6 flex flex-col-reverse md:flex-row items-center md:space-x-12">
    <div class="w-full md:w-1/2 text-center md:text-left">
     <h1 class="text-4xl md:text-5xl font-extrabold text-indigo-700 leading-tight">
      Hi, I'm
      <span class="text-indigo-900">
       Rafa
      </span>
     </h1>
     <p class="mt-4 text-lg text-indigo-800 max-w-md mx-auto md:mx-0">
      A passionate web developer crafting beautiful and performant websites.
     </p>
     <div class="mt-6 flex justify-center md:justify-start space-x-4">
      <a class="px-6 py-3 bg-indigo-600 text-white rounded-md font-semibold hover:bg-indigo-700 transition" href="#projects">
       View Projects
      </a>
      <a class="px-6 py-3 border-2 border-indigo-600 text-indigo-600 rounded-md font-semibold hover:bg-indigo-600 hover:text-white transition" href="#contact">
       Contact Me
      </a>
     </div>
    </div>
    <div class="w-full md:w-1/2 mb-10 md:mb-0">
     <img alt="Portrait of Rafa smiling with modern web developer style, wearing casual clothes and glasses, bright background" class="rounded-full mx-auto md:mx-0 w-64 h-64 object-cover shadow-lg" height="600" loading="lazy" src="https://storage.googleapis.com/a1aa/image/66493fc6-8f44-4312-af30-9871c67c4c07.jpg" width="600"/>
    </div>
   </div>
  </section>
  <!-- About Section -->
  <section class="max-w-7xl mx-auto px-6 py-20" id="about">
   <h2 class="text-3xl font-bold text-indigo-700 text-center mb-12">
    About Me
   </h2>
   <div class="flex flex-col md:flex-row md:space-x-12 items-center">
    <div class="md:w-1/3 mb-10 md:mb-0">
     <img alt="Rafa working on a laptop in a modern office environment with natural light and plants" class="rounded-lg shadow-lg mx-auto md:mx-0 w-72 h-72 object-cover" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/a86c00fe-526f-4707-9811-fb6c590dfb5b.jpg" width="400"/>
    </div>
    <div class="md:w-2/3 text-gray-700 text-lg leading-relaxed">
     <p>
      Hello! I'm Rafa, a dedicated web developer with a passion for creating clean, efficient, and user-friendly websites. With a strong foundation in HTML, CSS, JavaScript, and modern frameworks like React and Tailwind CSS, I strive to build digital experiences that are both beautiful and functional.
     </p>
     <p class="mt-4">
      When I'm not coding, I enjoy exploring new technologies, contributing to open source projects, and sharing knowledge with the developer community. Let's build something amazing together!
     </p>
    </div>
   </div>
  </section>
  <!-- Projects Section -->
  <section class="bg-indigo-50 py-20" id="projects">
   <div class="max-w-7xl mx-auto px-6">
    <h2 class="text-3xl font-bold text-indigo-700 text-center mb-12">
     Projects
    </h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-10">
     <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition">
      <img alt="Project 1 dashboard UI design with charts and graphs on a laptop screen" class="w-full h-48 object-cover" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/cae9c1a7-8658-43f6-dd23-7b4937700e55.jpg" width="600"/>
      <div class="p-6">
       <h3 class="text-xl font-semibold text-indigo-800 mb-2">
        Dashboard UI
       </h3>
       <p class="text-gray-600 mb-4">
        A responsive dashboard interface featuring interactive charts and real-time data visualization.
       </p>
       <a class="text-indigo-600 font-semibold hover:underline flex items-center space-x-2" href="#">
        <span>
         View Details
        </span>
        <i class="fas fa-arrow-right">
        </i>
       </a>
      </div>
     </div>
     <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition">
      <img alt="Project 2 e-commerce website product page with clean layout and product images" class="w-full h-48 object-cover" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/5b5a9725-31d9-41fc-a8f6-c6d7e5d0c265.jpg" width="600"/>
      <div class="p-6">
       <h3 class="text-xl font-semibold text-indigo-800 mb-2">
        E-commerce Website
       </h3>
       <p class="text-gray-600 mb-4">
        Developed a modern e-commerce platform with smooth navigation and seamless checkout experience.
       </p>
       <a class="text-indigo-600 font-semibold hover:underline flex items-center space-x-2" href="#">
        <span>
         View Details
        </span>
        <i class="fas fa-arrow-right">
        </i>
       </a>
      </div>
     </div>
     <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition">
      <img alt="Project 3 portfolio website with minimalist design and smooth scrolling" class="w-full h-48 object-cover" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/e8bfc7c8-2745-4995-5954-f1f1090e019d.jpg" width="600"/>
      <div class="p-6">
       <h3 class="text-xl font-semibold text-indigo-800 mb-2">
        Portfolio Website
       </h3>
       <p class="text-gray-600 mb-4">
        A clean and minimalist portfolio site showcasing projects and skills with smooth animations.
       </p>
       <a class="text-indigo-600 font-semibold hover:underline flex items-center space-x-2" href="#">
        <span>
         View Details
        </span>
        <i class="fas fa-arrow-right">
        </i>
       </a>
      </div>
     </div>
     <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition">
      <img alt="Project 4 blog platform with modern typography and clean user interface" class="w-full h-48 object-cover" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/39dbc417-9862-4bcb-ada7-8713f443a52c.jpg" width="600"/>
      <div class="p-6">
       <h3 class="text-xl font-semibold text-indigo-800 mb-2">
        Blog Platform
       </h3>
       <p class="text-gray-600 mb-4">
        Built a user-friendly blog platform with easy content management and responsive design.
       </p>
       <a class="text-indigo-600 font-semibold hover:underline flex items-center space-x-2" href="#">
        <span>
         View Details
        </span>
        <i class="fas fa-arrow-right">
        </i>
       </a>
      </div>
     </div>
     <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition">
      <img alt="Project 5 mobile app landing page with call to action buttons and vibrant colors" class="w-full h-48 object-cover" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/4a840724-2ecf-4824-0603-b806671a8862.jpg" width="600"/>
      <div class="p-6">
       <h3 class="text-xl font-semibold text-indigo-800 mb-2">
        Mobile App Landing
       </h3>
       <p class="text-gray-600 mb-4">
        Designed a vibrant landing page for a mobile app with clear call-to-action and testimonials.
       </p>
       <a class="text-indigo-600 font-semibold hover:underline flex items-center space-x-2" href="#">
        <span>
         View Details
        </span>
        <i class="fas fa-arrow-right">
        </i>
       </a>
      </div>
     </div>
     <div class="bg-white rounded-lg shadow-lg overflow-hidden hover:shadow-xl transition">
      <img alt="Project 6 social media dashboard with analytics and user engagement metrics" class="w-full h-48 object-cover" height="400" loading="lazy" src="https://storage.googleapis.com/a1aa/image/69634033-61ed-4673-7e1d-b0e9032ce320.jpg" width="600"/>
      <div class="p-6">
       <h3 class="text-xl font-semibold text-indigo-800 mb-2">
        Social Media Dashboard
       </h3>
       <p class="text-gray-600 mb-4">
        Created a dashboard to monitor social media analytics and user engagement in real-time.
       </p>
       <a class="text-indigo-600 font-semibold hover:underline flex items-center space-x-2" href="#">
        <span>
         View Details
        </span>
        <i class="fas fa-arrow-right">
        </i>
       </a>
      </div>
     </div>
    </div>
   </div>
  </section>
  <!-- Contact Section -->
  <section class="max-w-7xl mx-auto px-6 py-20" id="contact">
   <h2 class="text-3xl font-bold text-indigo-700 text-center mb-12">
    Get In Touch
   </h2>
   <div class="max-w-3xl mx-auto bg-white rounded-lg shadow-lg p-8">
    <form action="#" class="space-y-6" method="POST">
     <div>
      <label class="block text-gray-700 font-semibold mb-2" for="name">
       Name
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-3 focus:outline-none focus:ring-2 focus:ring-indigo-500" id="name" name="name" placeholder="Your full name" required="" type="text"/>
     </div>
     <div>
      <label class="block text-gray-700 font-semibold mb-2" for="email">
       Email
      </label>
      <input class="w-full border border-gray-300 rounded-md px-4 py-3 focus:outline-none focus:ring-2 focus:ring-indigo-500" id="email" name="email" placeholder="you@example.com" required="" type="email"/>
     </div>
     <div>
      <label class="block text-gray-700 font-semibold mb-2" for="message">
       Message
      </label>
      <textarea class="w-full border border-gray-300 rounded-md px-4 py-3 focus:outline-none focus:ring-2 focus:ring-indigo-500" id="message" name="message" placeholder="Write your message here..." required="" rows="5"></textarea>
     </div>
     <button class="w-full bg-indigo-600 text-white font-semibold py-3 rounded-md hover:bg-indigo-700 transition" type="submit">
      Send Message
     </button>
    </form>
   </div>
  </section>
  <!-- Footer -->
  <footer class="bg-indigo-900 text-indigo-200 py-8">
   <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center space-y-4 md:space-y-0">
    <p>
     © 2024 Rafa. All rights reserved.
    </p>
    <div class="flex space-x-6 text-xl">
     <a aria-label="GitHub" class="hover:text-white transition" href="https://github.com/rafa" rel="noopener noreferrer" target="_blank">
      <i class="fab fa-github">
      </i>
     </a>
     <a aria-label="LinkedIn" class="hover:text-white transition" href="https://linkedin.com/in/rafa" rel="noopener noreferrer" target="_blank">
      <i class="fab fa-linkedin">
      </i>
     </a>
     <a aria-label="Twitter" class="hover:text-white transition" href="https://twitter.com/rafa" rel="noopener noreferrer" target="_blank">
      <i class="fab fa-twitter">
      </i>
     </a>
    </div>
   </div>
  </footer>
  <script>
   const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');

    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>
 </body>
</html>
