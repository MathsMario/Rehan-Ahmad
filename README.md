<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Creative Services Portfolio</title>
    <!-- Tailwind CSS CDN for utility-first styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter for a clean, modern look -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Custom CSS to ensure Inter font is applied globally and for smooth scrolling */
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth; /* Smooth scrolling for anchor links */
        }
        /* Custom styles for section padding and background colors */
        .section-padding {
            padding: 4rem 1rem; /* Default padding for sections */
        }
        @media (min-width: 768px) {
            .section-padding {
                padding: 6rem 4rem; /* Larger padding for medium screens and up */
            }
        }
        @media (min-width: 1024px) {
            .section-padding {
                padding: 8rem 8rem; /* Even larger padding for large screens and up */
            }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header Section -->
    <header class="bg-white shadow-sm fixed w-full z-50">
        <nav class="container mx-auto px-4 py-4 flex justify-between items-center">
            <!-- Logo/Your Name -->
            <a href="#hero" class="text-2xl font-bold text-indigo-600 hover:text-indigo-700 transition duration-300 ease-in-out rounded-md p-2">Your Name Creative</a>

            <!-- Desktop Navigation -->
            <div class="hidden md:flex space-x-8">
                <a href="#services" class="text-gray-600 hover:text-indigo-600 font-medium transition duration-300 ease-in-out rounded-md p-2">Services</a>
                <a href="#portfolio" class="text-gray-600 hover:text-indigo-600 font-medium transition duration-300 ease-in-out rounded-md p-2">Portfolio</a>
                <a href="#about" class="text-gray-600 hover:text-indigo-600 font-medium transition duration-300 ease-in-out rounded-md p-2">About</a>
                <a href="#contact" class="text-gray-600 hover:text-indigo-600 font-medium transition duration-300 ease-in-out rounded-md p-2">Contact</a>
            </div>

            <!-- Mobile Menu Button (Hamburger Icon) -->
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-600 hover:text-indigo-600 focus:outline-none focus:ring-2 focus:ring-indigo-500 rounded-md p-2">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                    </svg>
                </button>
            </div>
        </nav>

        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white py-2 shadow-lg">
            <a href="#services" class="block px-4 py-2 text-gray-800 hover:bg-indigo-50 hover:text-indigo-600 rounded-md mx-2 transition duration-300 ease-in-out">Services</a>
            <a href="#portfolio" class="block px-4 py-2 text-gray-800 hover:bg-indigo-50 hover:text-indigo-600 rounded-md mx-2 transition duration-300 ease-in-out">Portfolio</a>
            <a href="#about" class="block px-4 py-2 text-gray-800 hover:bg-indigo-50 hover:text-indigo-600 rounded-md mx-2 transition duration-300 ease-in-out">About</a>
            <a href="#contact" class="block px-4 py-2 text-gray-800 hover:bg-indigo-50 hover:text-indigo-600 rounded-md mx-2 transition duration-300 ease-in-out">Contact</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="relative bg-gradient-to-r from-indigo-500 to-purple-600 text-white section-padding pt-24 md:pt-32 lg:pt-40 flex items-center min-h-screen">
        <div class="container mx-auto text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-4 animate-fade-in-up">
                Unleash Your Brand's Potential.
            </h1>
            <p class="text-lg md:text-xl mb-8 opacity-90 animate-fade-in-up delay-100">
                Crafting compelling visuals and engaging social media content that drives results.
            </p>
            <a href="#services" class="bg-white text-indigo-700 hover:bg-indigo-100 px-8 py-3 rounded-full text-lg font-semibold shadow-lg transition duration-300 ease-in-out transform hover:scale-105 animate-fade-in-up delay-200">
                Explore My Services
            </a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="bg-gray-50 section-padding">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-12">My Services</h2>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service Card 1: Social Media Post Design -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col items-center transform hover:scale-105 transition duration-300 ease-in-out">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-16 h-16" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Social Media Post Design</h3>
                    <p class="text-gray-600 text-center mb-4">
                        Visually stunning and engaging graphics tailored for Instagram, Facebook, LinkedIn, and more. Drive engagement and brand awareness.
                    </p>
                    <div class="w-full text-left mt-auto">
                        <h4 class="font-semibold text-gray-700 mb-2">Packages:</h4>
                        <ul class="text-sm text-gray-500 list-disc list-inside space-y-1 mb-4">
                            <li>**Basic:** 3 Posts, 1 Revision - $50</li>
                            <li>**Standard:** 7 Posts, 2 Revisions, Basic Animation - $120</li>
                            <li>**Premium:** 15 Posts, Unlimited Revisions, Custom Illustrations, Video Edits - $250</li>
                        </ul>
                        <button class="bg-indigo-600 text-white px-6 py-2 rounded-full font-medium hover:bg-indigo-700 transition duration-300 ease-in-out shadow-md">
                            Order Now
                        </button>
                    </div>
                </div>

                <!-- Service Card 2: Logo & Brand Identity -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col items-center transform hover:scale-105 transition duration-300 ease-in-out">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-16 h-16" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Logo & Brand Identity</h3>
                    <p class="text-gray-600 text-center mb-4">
                        Create a memorable brand identity with unique logos, color palettes, and typography guidelines.
                    </p>
                    <div class="w-full text-left mt-auto">
                        <h4 class="font-semibold text-gray-700 mb-2">Packages:</h4>
                        <ul class="text-sm text-gray-500 list-disc list-inside space-y-1 mb-4">
                            <li>**Basic:** 2 Logo Concepts, 1 Revision - $150</li>
                            <li>**Standard:** 3 Logo Concepts, 2 Revisions, Brand Guidelines - $300</li>
                            <li>**Premium:** 5 Logo Concepts, Unlimited Revisions, Full Brand Kit, Stationery Design - $500</li>
                        </ul>
                        <button class="bg-indigo-600 text-white px-6 py-2 rounded-full font-medium hover:bg-indigo-700 transition duration-300 ease-in-out shadow-md">
                            Order Now
                        </button>
                    </div>
                </div>

                <!-- Service Card 3: Web Graphic Design -->
                <div class="bg-white rounded-xl shadow-lg p-6 flex flex-col items-center transform hover:scale-105 transition duration-300 ease-in-out">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-16 h-16" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-1.25-3M15 10V5a2 2 0 00-2-2H7a2 2 0 00-2 2v5mba 6h10a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold text-gray-900 mb-3">Web Graphic Design</h3>
                    <p class="text-gray-600 text-center mb-4">
                        Eye-catching banners, website elements, and digital ads optimized for web performance.
                    </p>
                    <div class="w-full text-left mt-auto">
                        <h4 class="font-semibold text-gray-700 mb-2">Packages:</h4>
                        <ul class="text-sm text-gray-500 list-disc list-inside space-y-1 mb-4">
                            <li>**Basic:** 3 Web Banners, 1 Revision - $80</li>
                            <li>**Standard:** 5 Web Banners, 2 Revisions, Basic UI Elements - $180</li>
                            <li>**Premium:** 10 Web Banners, Unlimited Revisions, Full UI Kit, Iconography - $350</li>
                        </ul>
                        <button class="bg-indigo-600 text-white px-6 py-2 rounded-full font-medium hover:bg-indigo-700 transition duration-300 ease-in-out shadow-md">
                            Order Now
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="bg-white section-padding">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-12">My Portfolio</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Portfolio Item 1 -->
                <div class="relative group rounded-xl overflow-hidden shadow-lg transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/600x400/A78BFA/ffffff?text=Social+Post+1" alt="Social Media Post Design" class="w-full h-64 object-cover">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">Engaging Social Post</p>
                    </div>
                </div>
                <!-- Portfolio Item 2 -->
                <div class="relative group rounded-xl overflow-hidden shadow-lg transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/600x400/6366F1/ffffff?text=Logo+Design+1" alt="Logo Design" class="w-full h-64 object-cover">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">Modern Logo Design</p>
                    </div>
                </div>
                <!-- Portfolio Item 3 -->
                <div class="relative group rounded-xl overflow-hidden shadow-lg transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/600x400/8B5CF6/ffffff?text=Web+Banner+1" alt="Web Banner Design" class="w-full h-64 object-cover">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">Dynamic Web Banner</p>
                    </div>
                </div>
                <!-- Portfolio Item 4 -->
                <div class="relative group rounded-xl overflow-hidden shadow-lg transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/600x400/C084FC/ffffff?text=Social+Post+2" alt="Social Media Post Design" class="w-full h-64 object-cover">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">Creative Social Post</p>
                    </div>
                </div>
                <!-- Portfolio Item 5 -->
                <div class="relative group rounded-xl overflow-hidden shadow-lg transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/600x400/A78BFA/ffffff?text=Brand+Identity+1" alt="Brand Identity" class="w-full h-64 object-cover">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">Cohesive Brand Identity</p>
                    </div>
                </div>
                <!-- Portfolio Item 6 -->
                <div class="relative group rounded-xl overflow-hidden shadow-lg transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/600x400/6366F1/ffffff?text=Digital+Ad+1" alt="Digital Ad Design" class="w-full h-64 object-cover">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">Compelling Digital Ad</p>
                    </div>
                </div>
            </div>
            <div class="mt-12">
                <a href="#contact" class="bg-indigo-600 text-white px-8 py-3 rounded-full font-semibold hover:bg-indigo-700 transition duration-300 ease-in-out transform hover:scale-105 shadow-md">
                    View More Work
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="bg-gray-50 section-padding">
        <div class="container mx-auto text-center max-w-3xl">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-8">About Me</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-8">
                <div class="md:w-1/3 mb-6 md:mb-0">
                    <img src="https://placehold.co/300x300/E0E7FF/6366F1?text=Your+Photo" alt="Your Photo" class="rounded-full w-48 h-48 object-cover mx-auto shadow-lg border-4 border-indigo-200">
                </div>
                <div class="md:w-2/3 text-left">
                    <p class="text-lg text-gray-700 mb-4">
                        Hello! I'm [Your Name], a passionate graphic designer and social media content creator dedicated to helping brands tell their unique stories through captivating visuals. With a keen eye for detail and a commitment to innovative design, I transform ideas into impactful digital experiences.
                    </p>
                    <p class="text-lg text-gray-700">
                        My goal is to provide high-quality, tailor-made design solutions that not only look great but also achieve your business objectives. Let's create something amazing together!
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-white section-padding">
        <div class="container mx-auto text-center max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-8">Get in Touch</h2>
            <p class="text-lg text-gray-700 mb-8">
                Have a project in mind or just want to say hello? Fill out the form below or reach out directly!
            </p>
            <form class="space-y-6 bg-gray-50 p-8 rounded-xl shadow-lg border border-gray-100">
                <div>
                    <label for="name" class="block text-left text-sm font-medium text-gray-700 mb-1">Name</label>
                    <input type="text" id="name" name="name" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Your Name" required>
                </div>
                <div>
                    <label for="email" class="block text-left text-sm font-medium text-gray-700 mb-1">Email</label>
                    <input type="email" id="email" name="email" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="you@example.com" required>
                </div>
                <div>
                    <label for="message" class="block text-left text-sm font-medium text-gray-700 mb-1">Message</label>
                    <textarea id="message" name="message" rows="5" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm" placeholder="Tell me about your project..." required></textarea>
                </div>
                <button type="submit" class="w-full bg-indigo-600 text-white px-6 py-3 rounded-full font-semibold hover:bg-indigo-700 transition duration-300 ease-in-out transform hover:scale-105 shadow-md">
                    Send Message
                </button>
            </form>
            <p class="mt-8 text-gray-600">
                You can also reach me at: <a href="mailto:your.email@example.com" class="text-indigo-600 hover:underline">your.email@example.com</a>
            </p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p class="text-sm">&copy; 2025 Your Name Creative. All rights reserved.</p>
            <div class="flex justify-center space-x-6 mt-4">
                <!-- Social Media Links (replace with your actual links) -->
                <a href="#" class="text-gray-400 hover:text-white transition duration-300 ease-in-out">Facebook</a>
                <a href="#" class="text-gray-400 hover:text-white transition duration-300 ease-in-out">Instagram</a>
                <a href="#" class="text-gray-400 hover:text-white transition duration-300 ease-in-out">LinkedIn</a>
            </div>
        </div>
    </footer>

    <script>
        // JavaScript for mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileMenuLinks = mobileMenu.querySelectorAll('a');
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Basic form submission handling (for demonstration)
        // In a real-world scenario, you would send this data to a backend server.
        const contactForm = document.querySelector('#contact form');
        contactForm.addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent default form submission

            // You can add a custom message box here instead of alert()
            // For example, display a div with a success message
            const messageBox = document.createElement('div');
            messageBox.textContent = 'Thank you for your message! I will get back to you soon.';
            messageBox.className = 'fixed bottom-4 right-4 bg-green-500 text-white px-6 py-3 rounded-lg shadow-xl z-50';
            document.body.appendChild(messageBox);

            // Automatically remove the message after a few seconds
            setTimeout(() => {
                messageBox.remove();
            }, 3000);

            // Clear the form fields
            contactForm.reset();
        });
    </script>
</body>
</html>
