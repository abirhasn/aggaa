<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Psychology Quiz Competition - kittcha</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        * {
            scroll-behavior: smooth;
        }
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
        }
        .gradient-text {
            background: linear-gradient(to right, #9333ea, #a855f7);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        ::-webkit-scrollbar {
            width: 10px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        ::-webkit-scrollbar-thumb {
            background: #9333ea;
            border-radius: 5px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #7e22ce;
        }
    </style>
</head>
<body class="bg-white">

    <!-- Header -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-purple-100">
        <div class="container mx-auto px-6 py-4 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <img src="https://customer-assets.emergentagent.com/job_quiz-logo/artifacts/m5qs1euk_image.png" 
                     alt="kittcha logo" 
                     class="h-12 w-auto rounded-lg shadow-sm">
            </div>
            <nav class="hidden md:flex gap-8">
                <a href="#about" class="text-gray-700 hover:text-purple-600 transition-colors font-medium">About</a>
                <a href="#details" class="text-gray-700 hover:text-purple-600 transition-colors font-medium">Details</a>
                <a href="#register" class="text-gray-700 hover:text-purple-600 transition-colors font-medium">Register</a>
            </nav>
            <button onclick="openGoogleForm()" class="bg-purple-600 hover:bg-purple-700 text-white px-6 py-2 rounded-md font-medium transition-all">
                Register Now
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 px-6 bg-gradient-to-b from-purple-50 to-white">
        <div class="container mx-auto max-w-6xl">
            <div class="text-center space-y-8">
                <div class="inline-flex items-center gap-2 px-4 py-2 bg-purple-100 rounded-full text-purple-700 font-medium">
                    <span>✨</span>
                    Social Science Organization
                </div>
                <h1 class="text-5xl md:text-7xl font-bold text-gray-900 leading-tight">
                    Psychology Quiz
                    <span class="block mt-2 gradient-text">Competition</span>
                </h1>
                <p class="text-xl md:text-2xl text-gray-600 max-w-3xl mx-auto">
                    Test your knowledge of the human mind and behavior in this exciting online quiz competition
                </p>
                <div class="flex flex-wrap justify-center gap-4 pt-4">
                    <button onclick="openGoogleForm()" class="bg-purple-600 hover:bg-purple-700 text-white px-8 py-4 rounded-md text-lg font-medium shadow-lg hover:shadow-xl transition-all">
                        Register for Free
                    </button>
                    <button onclick="scrollToSection('details')" class="border-2 border-purple-600 text-purple-600 hover:bg-purple-50 px-8 py-4 rounded-md text-lg font-medium transition-all">
                        Learn More
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Event Highlights -->
    <section class="py-16 px-6 bg-white">
        <div class="container mx-auto max-w-6xl">
            <div class="grid md:grid-cols-3 gap-8">
                <div class="rounded-xl border-2 border-purple-200 hover:border-purple-400 bg-white shadow hover:shadow-lg transition-all p-6 text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-3xl">📅</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">29 December</h3>
                    <p class="text-gray-600">Mark your calendar for this exciting event</p>
                </div>

                <div class="rounded-xl border-2 border-purple-200 hover:border-purple-400 bg-white shadow hover:shadow-lg transition-all p-6 text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-3xl">🕘</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">9:00 PM</h3>
                    <p class="text-gray-600">Evening competition slot</p>
                </div>

                <div class="rounded-xl border-2 border-purple-200 hover:border-purple-400 bg-white shadow hover:shadow-lg transition-all p-6 text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-3xl">🌐</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Online Event</h3>
                    <p class="text-gray-600">Join from anywhere in the world</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-6 bg-purple-50">
        <div class="container mx-auto max-w-6xl">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900">
                        About kittcha
                    </h2>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        kittcha is a dynamic social science organization dedicated to fostering intellectual curiosity and academic excellence. We create engaging platforms for students and enthusiasts to explore various disciplines within the social sciences.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        Through competitions, workshops, and community events, kittcha brings together like-minded individuals passionate about understanding human behavior, society, and the complexities of the social world.
                    </p>
                </div>
                <div class="grid grid-cols-2 gap-6">
                    <div class="bg-white border-2 border-purple-200 rounded-xl shadow p-6">
                        <span class="text-4xl mb-2 block">🧠</span>
                        <h4 class="font-bold text-gray-900 mb-1">Mind & Behavior</h4>
                        <p class="text-sm text-gray-600">Explore psychological concepts</p>
                    </div>
                    <div class="bg-white border-2 border-purple-200 rounded-xl shadow p-6">
                        <span class="text-4xl mb-2 block">👥</span>
                        <h4 class="font-bold text-gray-900 mb-1">Open to All</h4>
                        <p class="text-sm text-gray-600">Everyone is welcome</p>
                    </div>
                    <div class="bg-white border-2 border-purple-200 rounded-xl shadow p-6">
                        <span class="text-4xl mb-2 block">✨</span>
                        <h4 class="font-bold text-gray-900 mb-1">Interactive</h4>
                        <p class="text-sm text-gray-600">Engaging questions</p>
                    </div>
                    <div class="bg-white border-2 border-purple-200 rounded-xl shadow p-6">
                        <span class="text-4xl mb-2 block">🌐</span>
                        <h4 class="font-bold text-gray-900 mb-1">Virtual</h4>
                        <p class="text-sm text-gray-600">Accessible online</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Event Details -->
    <section id="details" class="py-20 px-6 bg-white">
        <div class="container mx-auto max-w-4xl">
            <div class="text-center space-y-4 mb-12">
                <h2 class="text-4xl md:text-5xl font-bold text-gray-900">Event Details</h2>
                <p class="text-xl text-gray-600">Everything you need to know</p>
            </div>

            <div class="space-y-6">
                <div class="border-2 border-purple-200 rounded-xl shadow p-6">
                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center flex-shrink-0">
                            <span class="text-2xl">📅</span>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Date & Time</h3>
                            <p class="text-gray-700">29th December 2025 at 9:00 PM</p>
                        </div>
                    </div>
                </div>

                <div class="border-2 border-purple-200 rounded-xl shadow p-6">
                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center flex-shrink-0">
                            <span class="text-2xl">🌐</span>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Mode</h3>
                            <p class="text-gray-700">Online - Join from the comfort of your home</p>
                        </div>
                    </div>
                </div>

                <div class="border-2 border-purple-200 rounded-xl shadow p-6">
                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center flex-shrink-0">
                            <span class="text-2xl">🧠</span>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Topic</h3>
                            <p class="text-gray-700">Psychology - Questions covering various aspects of human psychology, behavior, cognition, and mental processes</p>
                        </div>
                    </div>
                </div>

                <div class="border-2 border-purple-200 rounded-xl shadow p-6">
                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center flex-shrink-0">
                            <span class="text-2xl">👥</span>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Participation</h3>
                            <p class="text-gray-700">Free and open to all psychology enthusiasts</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Registration CTA -->
    <section id="register" class="py-20 px-6 bg-gradient-to-b from-purple-50 to-purple-100">
        <div class="container mx-auto max-w-4xl text-center space-y-8">
            <h2 class="text-4xl md:text-5xl font-bold text-gray-900">
                Ready to Challenge Yourself?
            </h2>
            <p class="text-xl text-gray-700 max-w-2xl mx-auto">
                Register now and test your knowledge of psychology in this exciting competition
            </p>
            <button onclick="openGoogleForm()" class="bg-purple-600 hover:bg-purple-700 text-white px-12 py-4 rounded-md text-lg font-medium shadow-xl hover:shadow-2xl transition-all">
                Register via Google Form
            </button>
            <p class="text-sm text-gray-600">Registration closes on 28th December</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12 px-6">
        <div class="container mx-auto max-w-6xl">
            <div class="grid md:grid-cols-3 gap-8">
                <div class="space-y-4">
                    <div class="flex items-center gap-3">
                        <img src="https://customer-assets.emergentagent.com/job_quiz-logo/artifacts/m5qs1euk_image.png" 
                             alt="kittcha logo" 
                             class="h-16 w-auto rounded-lg">
                    </div>
                    <p class="text-gray-400">A social science organization bringing creative events to life</p>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Quick Links</h4>
                    <div class="space-y-2">
                        <a href="#about" class="block text-gray-400 hover:text-purple-400 transition-colors">About kittcha</a>
                        <a href="#details" class="block text-gray-400 hover:text-purple-400 transition-colors">Event Details</a>
                        <a href="#register" class="block text-gray-400 hover:text-purple-400 transition-colors">Register</a>
                    </div>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Event Info</h4>
                    <div class="space-y-2 text-gray-400">
                        <p>Date: 29 December 2025</p>
                        <p>Time: 9:00 PM</p>
                        <p>Mode: Online</p>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2025 kittcha. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Replace this URL with your actual Google Form link
        const GOOGLE_FORM_URL = 'YOUR_GOOGLE_FORM_LINK_HERE';

        function openGoogleForm() {
            window.open(GOOGLE_FORM_URL, '_blank');
        }

        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
        }
    </script>

</body>
</html>
