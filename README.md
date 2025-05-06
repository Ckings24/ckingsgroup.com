# ckingsgroup.com <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CKINGS Group of Companies</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>

<body class="bg-gray-100 font-sans">
    <!-- Navbar -->
    <nav class="bg-blue-600 text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-xl font-bold">CKINGS Group of Companies</h1>
            <ul class="flex space-x-4">
                <li><a href="#about" class="hover:underline">About Us</a></li>
                <li><a href="#services" class="hover:underline">Services</a></li>
                <li><a href="#contact" class="hover:underline">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="bg-blue-500 text-white text-center py-20">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold mb-4">Welcome to CKINGS Group of Companies</h2>
            <p class="text-lg">Delivering excellence in e-commerce, importation, and business solutions.</p>
            <a href="#services" class="mt-6 inline-block bg-white text-blue-600 px-6 py-2 rounded-lg shadow hover:bg-gray-200">Explore Our Services</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-200">
        <div class="container mx-auto text-center">
            <h3 class="text-3xl font-bold mb-4">About Us</h3>
            <p class="text-gray-700">CKINGS Group of Companies is a trusted leader in e-commerce and importation. We pride ourselves on innovation, integrity, and delivering exceptional value to our customers.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-white">
        <div class="container mx-auto text-center">
            <h3 class="text-3xl font-bold mb-8">Our Services</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-gray-100 p-6 rounded-lg shadow">
                    <h4 class="text-xl font-semibold mb-2">E-Commerce Solutions</h4>
                    <p class="text-gray-600">Providing a seamless online shopping experience with a vast range of products.</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow">
                    <h4 class="text-xl font-semibold mb-2">Importation Services</h4>
                    <p class="text-gray-600">Specializing in importing high-quality goods efficiently and affordably.</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow">
                    <h4 class="text-xl font-semibold mb-2">Business Consulting</h4>
                    <p class="text-gray-600">Helping businesses thrive with tailored strategies and expert advice.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-200">
        <div class="container mx-auto text-center">
            <h3 class="text-3xl font-bold mb-4">Contact Us</h3>
            <p class="text-gray-700 mb-8">Get in touch with CKINGS Group of Companies for inquiries or partnerships.</p>
            <form class="max-w-lg mx-auto bg-white p-6 rounded-lg shadow">
                <div class="mb-4">
                    <label for="name" class="block text-gray-700">Name</label>
                    <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-gray-700">Email</label>
                    <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-700">Message</label>
                    <textarea id="message" rows="4" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600"></textarea>
                </div>
                <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-blue-600 text-white py-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 CKINGS Group of Companies. All Rights Reserved.</p>
        </div>
    </footer>
</body>

</html>
