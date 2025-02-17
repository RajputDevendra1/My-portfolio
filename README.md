<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans">


  <header class="bg-blue-900 text-white shadow-md">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-3xl font-bold">My Portfolio</h1>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="#home" class="hover:text-blue-300">Home</a></li>
          <li><a href="#about" class="hover:text-blue-300">About</a></li>
          <li><a href="#projects" class="hover:text-blue-300">Projects</a></li>
          <li><a href="#contact" class="hover:text-blue-300">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

 
  <section id="home" class="flex items-center justify-center min-h-screen bg-blue-900 text-white text-center">
    <div>
      <h2 class="text-5xl font-bold">Hello, I'm RAJPUT DEVENDRA SINGH</h2>
      <p class="mt-4 text-lg">Web Developer | Designer | Creator</p>
    </div>
  </section>


  <section id="about" class="py-16 bg-gray-200">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold">About Me</h2>
      <p class="mt-4 text-lg text-gray-700 max-w-2xl mx-auto">
        I'm a passionate web developer with a knack for creating modern, responsive websites and web applications. I enjoy working with the latest technologies and continuously improving my skills.
      </p>
    </div>
  </section>


  <section id="projects" class="py-16 bg-white">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold">My Experience</h2>
      <div class="mt-8 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-gray-200 p-6 rounded-lg shadow-lg">
          <h3 class="text-2xl font-semibold">Work</h3>
          <p class="mt-4 text-gray-700">Learing little-bit about building website using HTML, CSS, and JavaScript.</p>
      </div>
    </div>
  </section>

 
  <section id="contact" class="py-16 bg-blue-900 text-white">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold">Contact Me</h2>
      <p class="mt-4 text-lg">Feel free to reach out to me via email or follow me on social media.</p>
      <div class="mt-8">
        <a href="mailto:your.email@example.com" class="px-6 py-3 bg-blue-500 rounded-md text-white hover:bg-blue-700">Email Me</a>
      </div>
    </div>
  </section>

  
  <footer class="bg-gray-800 text-white py-6 text-center">
    <p>&copy; 2025 Rajput Devendra Singh. All rights reserved.</p>
  </footer>

</body>
</html>
