<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <script src="https://cdn.tailwindcss.com"></script>
    <title>Document</title>
  </head>
  <body class="bg-gray-100 text-gray-900">

    <!-- Header Section -->
    <header class="bg-blue-600 text-white p-4">
        <nav>
            <ul class="flex space-x-6">
                <li><a href="index.html" class="hover:text-gray-400">Home</a></li>
                <li><a href="about.html" class="hover:text-gray-400">About</a></li>
                <li><a href="portfolio.html" class="hover:text-gray-400">Portfolio</a></li>
                <li><a href="contact.html" class="hover:text-gray-400">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Section -->
    <section class="container mx-auto py-20 text-center">
        <h1 class="text-4xl font-bold mb-4 text-gray-900">Welcome to My Portfolio</h1>
        <p class="text-lg text-gray-600">Discover my work and get to know me better.</p>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white p-4 text-center mt-8">
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>

  </body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <!-- TailwindCSS CDN link -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 font-sans text-gray-800">

    <!-- Header Section -->
    <header class="bg-blue-600 p-4 text-white">
        <nav>
            <ul class="flex space-x-6">
                <li><a href="index.html" class="hover:text-gray-300">Home</a></li>
                <li><a href="about.html" class="hover:text-gray-300">About</a></li>
                <li><a href="portfolio.html" class="hover:text-gray-300">Portfolio</a></li>
                <li><a href="contact.html" class="hover:text-gray-300">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section class="about py-12 px-6 max-w-3xl mx-auto">
        <h1 class="text-3xl font-semibold text-center mb-6">About Me</h1>
        <p class="text-lg mb-4">Hello, I'm <strong>Muhammad Memon</strong>, a passionate <strong>full stake React/Tailwindcss Developer</strong>. I specialize in <strong>React/Nextjs/Tailwindcss and Typescript</strong>, and I'm excited to share my work with you.</p>
        <p class="text-lg">Here's a bit about my journey and how I got to where I am today...</p>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white py-4 text-center">
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Me</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900">
    <header class="bg-blue-600 text-white p-4">
        <nav>
            <ul class="flex space-x-6">
                <li><a href="index.html" class="hover:underline">Home</a></li>
                <li><a href="about.html" class="hover:underline">About</a></li>
                <li><a href="portfolio.html" class="hover:underline">Portfolio</a></li>
                <li><a href="contact.html" class="hover:underline">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact container mx-auto my-12 p-8 bg-white shadow-lg rounded-lg max-w-lg">
        <h1 class="text-2xl font-bold mb-6 text-center">Contact Me</h1>
        <form action="submit_contact_form.php" method="post" class="space-y-4">
            <div>
                <label for="name" class="block font-medium">Your Name:</label>
                <input type="text" id="name" name="name" required class="w-full p-2 border border-gray-300 rounded">
            </div>
            
            <div>
                <label for="email" class="block font-medium">Your Email:</label>
                <input type="email" id="email" name="email" required class="w-full p-2 border border-gray-300 rounded">
            </div>
            
            <div>
                <label for="message" class="block font-medium">Message:</label>
                <textarea id="message" name="message" required class="w-full p-2 border border-gray-300 rounded h-32"></textarea>
            </div>
            
            <button type="submit" class="w-full bg-blue-600 text-white p-2 rounded hover:bg-blue-700">Send Message</button>
        </form>
    </section>

    <footer class="bg-blue-600 text-white text-center p-4 mt-12">
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="font-sans bg-gray-100 text-gray-900">

    <header class="bg-blue-600 p-4">
        <nav>
            <ul class="flex space-x-6">
                <li><a href="index.html" class="text-white hover:text-blue-300">Home</a></li>
                <li><a href="about.html" class="text-white hover:text-blue-300">About</a></li>
                <li><a href="portfolio.html" class="text-white hover:text-blue-300">Portfolio</a></li>
                <li><a href="contact.html" class="text-white hover:text-blue-300">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="portfolio py-16 px-4">
        <h1 class="text-4xl font-semibold text-center text-blue-800 mb-4">My Work</h1>
        <p class="text-center text-xl text-gray-700 mb-8">Here are some of the projects I have worked on:</p>
        <div class="portfolio-items grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8">
            <div class="portfolio-item bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="project1.jpg" alt="Project 1" class="w-full h-64 object-cover">
                <div class="p-4">
                    <h3 class="text-xl font-semibold text-blue-600 mb-2">Project 1</h3>
                    <p class="text-gray-600">Description of the project...</p>
                </div>
            </div>
            <div class="portfolio-item bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="project2.jpg" alt="Project 2" class="w-full h-64 object-cover">
                <div class="p-4">
                    <h3 class="text-xl font-semibold text-blue-600 mb-2">Project 2</h3>
                    <p class="text-gray-600">Description of the project...</p>
                </div>
            </div>
            <div class="portfolio-item bg-white rounded-lg shadow-lg overflow-hidden">
                <img src="project3.jpg" alt="Project 3" class="w-full h-64 object-cover">
                <div class="p-4">
                    <h3 class="text-xl font-semibold text-blue-600 mb-2">Project 3</h3>
                    <p class="text-gray-600">Description of the project...</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-blue-600 text-white text-center py-4">
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
    </footer>

</body>

</html>

