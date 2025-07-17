# Tailwind-css-Trusha
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trusha Tanna | ECE Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <!-- Navigation -->
    <nav class="bg-indigo-600 p-4 text-white sticky top-0">
        <div class="container mx-auto flex justify-between">
            <span class="font-bold">Trusha Tanna</span>
            <div class="space-x-4">
                <a href="#home" class="hover:underline">Home</a>
                <a href="#about" class="hover:underline">About</a>
                <a href="#projects" class="hover:underline">Projects</a>
                <a href="#contact" class="hover:underline">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="min-h-screen flex items-center justify-center">
        <div class="text-center">
            <h1 class="text-4xl font-bold mb-2">Trusha Tanna</h1>
            <p class="text-xl text-indigo-600 mb-4">Electronics & Communication Engineer</p>
            <p class="mb-6">"Bridging hardware and software for smart solutions"</p>
            <button class="bg-indigo-600 text-white px-6 py-2 rounded hover:bg-indigo-700">Download Resume</button>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-8 text-center">About Me</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <p class="mb-4">ECE professional with expertise in wireless communication and networking. Passionate about 5G technologies and beyond.</p>
                    <p>I enjoy working on cutting-edge communication technologies that connect the world.</p>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-3">Skills</h3>
                    <ul class="list-disc pl-5 space-y-2">
                        <li>Wireless Communication</li>
                        <li>Network Protocols</li>
                        <li>Python Programming</li>
                        <li>RF Engineering</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold mb-8 text-center">My Projects</h2>
            <div class="grid md:grid-cols-3 gap-6">
                <!-- Project 1 -->
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
                    <h3 class="text-xl font-semibold mb-2">LoRa Network</h3>
                    <p class="text-gray-600 mb-4">Long-range wireless network for IoT applications.</p>
                    <span class="text-sm text-indigo-600">LoRa, IoT</span>
                </div>
                <!-- Project 2 -->
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
                    <h3 class="text-xl font-semibold mb-2">Spectrum Analyzer</h3>
                    <p class="text-gray-600 mb-4">Software-defined radio spectrum analysis tool.</p>
                    <span class="text-sm text-indigo-600">SDR, Python</span>
                </div>
                <!-- Project 3 -->
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
                    <h3 class="text-xl font-semibold mb-2">Network Simulator</h3>
                    <p class="text-gray-600 mb-4">5G network simulation using NS-3.</p>
                    <span class="text-sm text-indigo-600">NS-3, C++</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-white">
        <div class="container mx-auto px-4 max-w-md">
            <h2 class="text-3xl font-bold mb-8 text-center">Contact Me</h2>
            <form class="space-y-4">
                <input type="text" placeholder="Name" class="w-full p-2 border rounded">
                <input type="email" placeholder="Email" class="w-full p-2 border rounded">
                <textarea placeholder="Message" class="w-full p-2 border rounded" rows="4"></textarea>
                <button type="submit" class="bg-indigo-600 text-white px-6 py-2 rounded hover:bg-indigo-700 w-full">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center p-4">
        <p>© 2023 Trusha Tanna. All rights reserved.</p>
    </footer>
</body>
</html>
