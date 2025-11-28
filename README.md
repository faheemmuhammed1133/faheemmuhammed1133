<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enhanced GitHub Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @keyframes typing {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.3; }
        }
        .typing-animation {
            animation: typing 4s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        .float-animation {
            animation: float 3s ease-in-out infinite;
        }
        @keyframes gradient {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        .gradient-animation {
            background-size: 200% 200%;
            animation: gradient 3s ease infinite;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-gray-900 via-blue-900 to-purple-900 min-h-screen text-white">
    <div class="container mx-auto px-4 py-8 max-w-6xl">
        <!-- Header Section -->
        <div class="text-center mb-12">
            <div class="inline-block">
                <h1 class="text-6xl font-bold mb-4 typing-animation bg-gradient-to-r from-blue-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
                    Ciao, Salve 👋
                </h1>
                <div class="flex justify-center gap-2 mb-4">
                    <span class="inline-block px-4 py-2 bg-blue-500 bg-opacity-20 rounded-full text-sm backdrop-blur-sm border border-blue-400">
                        Visitor Count: 1,337
                    </span>
                </div>
            </div>
            <h3 class="text-2xl text-gray-300 mb-6">Passionate Tech & Football Enthusiast ⚽</h3>
        </div>

        <!-- Main Content Grid -->
        <div class="grid md:grid-cols-2 gap-8 mb-12">
            <!-- About Me Card -->
            <div class="bg-white bg-opacity-10 backdrop-blur-lg rounded-2xl p-6 border border-white border-opacity-20 hover:border-opacity-40 transition-all duration-300 hover:shadow-2xl hover:shadow-purple-500/50">
                <h2 class="text-3xl font-bold mb-6 flex items-center gap-2">
                    <span class="text-4xl">👨‍💻</span> About Me
                </h2>
                <div class="space-y-4 text-gray-200">
                    <div class="flex items-start gap-3 p-3 bg-blue-500 bg-opacity-10 rounded-lg hover:bg-opacity-20 transition-all">
                        <span class="text-2xl">🎓</span>
                        <p><strong>Third year B.Tech student</strong> at ITM Skills University</p>
                    </div>
                    <div class="flex items-start gap-3 p-3 bg-purple-500 bg-opacity-10 rounded-lg hover:bg-opacity-20 transition-all">
                        <span class="text-2xl">💡</span>
                        <p>Turning passions into innovative solutions</p>
                    </div>
                    <div class="flex items-start gap-3 p-3 bg-green-500 bg-opacity-10 rounded-lg hover:bg-opacity-20 transition-all">
                        <span class="text-2xl">📊</span>
                        <p>Currently learning <strong>Data Analytics</strong></p>
                    </div>
                    <div class="flex items-start gap-3 p-3 bg-yellow-500 bg-opacity-10 rounded-lg hover:bg-opacity-20 transition-all">
                        <span class="text-2xl">🇮🇹</span>
                        <p>Learning <strong>Italian</strong> - Ciao bella!</p>
                    </div>
                </div>
            </div>

            <!-- Interests Card -->
            <div class="bg-white bg-opacity-10 backdrop-blur-lg rounded-2xl p-6 border border-white border-opacity-20 hover:border-opacity-40 transition-all duration-300 hover:shadow-2xl hover:shadow-blue-500/50">
                <h2 class="text-3xl font-bold mb-6 flex items-center gap-2">
                    <span class="text-4xl">🌟</span> Interests
                </h2>
                <div class="grid grid-cols-2 gap-3">
                    <div class="bg-gradient-to-br from-orange-500 to-red-500 p-4 rounded-xl text-center hover:scale-105 transition-transform cursor-pointer">
                        <span class="text-3xl block mb-2">🏀</span>
                        <span class="font-semibold">NBA</span>
                    </div>
                    <div class="bg-gradient-to-br from-blue-500 to-cyan-500 p-4 rounded-xl text-center hover:scale-105 transition-transform cursor-pointer">
                        <span class="text-3xl block mb-2">🚗</span>
                        <span class="font-semibold">Cars</span>
                    </div>
                    <div class="bg-gradient-to-br from-purple-500 to-pink-500 p-4 rounded-xl text-center hover:scale-105 transition-transform cursor-pointer">
                        <span class="text-3xl block mb-2">📊</span>
                        <span class="font-semibold">Data Science</span>
                    </div>
                    <div class="bg-gradient-to-br from-green-500 to-teal-500 p-4 rounded-xl text-center hover:scale-105 transition-transform cursor-pointer">
                        <span class="text-3xl block mb-2">🤖</span>
                        <span class="font-semibold">AI & ML</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Tech Stack Section -->
        <div class="bg-white bg-opacity-10 backdrop-blur-lg rounded-2xl p-8 mb-12 border border-white border-opacity-20">
            <h2 class="text-3xl font-bold mb-8 text-center">
                <span class="bg-gradient-to-r from-blue-400 to-purple-400 bg-clip-text text-transparent">Tech Stack</span>
            </h2>
            <div class="flex flex-wrap justify-center gap-6">
                <div class="group relative">
                    <div class="bg-gradient-to-br from-blue-500 to-blue-700 p-4 rounded-xl hover:scale-110 transition-transform">
                        <span class="text-4xl">🐍</span>
                    </div>
                    <span class="absolute -bottom-8 left-1/2 transform -translate-x-1/2 bg-black px-2 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap">Python</span>
                </div>
                <div class="group relative">
                    <div class="bg-gradient-to-br from-blue-600 to-blue-800 p-4 rounded-xl hover:scale-110 transition-transform">
                        <span class="text-4xl">⚙️</span>
                    </div>
                    <span class="absolute -bottom-8 left-1/2 transform -translate-x-1/2 bg-black px-2 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap">C++</span>
                </div>
                <div class="group relative">
                    <div class="bg-gradient-to-br from-purple-500 to-purple-700 p-4 rounded-xl hover:scale-110 transition-transform">
                        <span class="text-4xl">©️</span>
                    </div>
                    <span class="absolute -bottom-8 left-1/2 transform -translate-x-1/2 bg-black px-2 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap">C</span>
                </div>
                <div class="group relative">
                    <div class="bg-gradient-to-br from-orange-500 to-red-500 p-4 rounded-xl hover:scale-110 transition-transform">
                        <span class="text-4xl">🔧</span>
                    </div>
                    <span class="absolute -bottom-8 left-1/2 transform -translate-x-1/2 bg-black px-2 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap">Git</span>
                </div>
                <div class="group relative">
                    <div class="bg-gradient-to-br from-gray-700 to-gray-900 p-4 rounded-xl hover:scale-110 transition-transform">
                        <span class="text-4xl">📁</span>
                    </div>
                    <span class="absolute -bottom-8 left-1/2 transform -translate-x-1/2 bg-black px-2 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap">GitHub</span>
                </div>
                <div class="group relative">
                    <div class="bg-gradient-to-br from-blue-400 to-blue-600 p-4 rounded-xl hover:scale-110 transition-transform">
                        <span class="text-4xl">💻</span>
                    </div>
                    <span class="absolute -bottom-8 left-1/2 transform -translate-x-1/2 bg-black px-2 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap">VS Code</span>
                </div>
                <div class="group relative">
                    <div class="bg-gradient-to-br from-green-500 to-green-700 p-4 rounded-xl hover:scale-110 transition-transform">
                        <span class="text-4xl">📱</span>
                    </div>
                    <span class="absolute -bottom-8 left-1/2 transform -translate-x-1/2 bg-black px-2 py-1 rounded text-xs opacity-0 group-hover:opacity-100 transition-opacity whitespace-nowrap">AppSheet</span>
                </div>
            </div>
        </div>

        <!-- Social Links -->
        <div class="bg-white bg-opacity-10 backdrop-blur-lg rounded-2xl p-8 mb-12 border border-white border-opacity-20">
            <h2 class="text-3xl font-bold mb-6 text-center">Connect With Me 🤝</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="mailto:muhammedfaheem1133@gmail.com" class="group flex items-center gap-2 bg-red-500 hover:bg-red-600 px-6 py-3 rounded-full transition-all transform hover:scale-105 hover:shadow-lg">
                    <span class="text-xl">📧</span>
                    <span class="font-semibold">Gmail</span>
                </a>
                <a href="https://www.linkedin.com/in/muhammed--faheem/" target="_blank" class="group flex items-center gap-2 bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded-full transition-all transform hover:scale-105 hover:shadow-lg">
                    <span class="text-xl">💼</span>
                    <span class="font-semibold">LinkedIn</span>
                </a>
                <a href="https://www.instagram.com/muhammed___fahee_m" target="_blank" class="group flex items-center gap-2 bg-gradient-to-r from-purple-500 to-pink-500 hover:from-purple-600 hover:to-pink-600 px-6 py-3 rounded-full transition-all transform hover:scale-105 hover:shadow-lg">
                    <span class="text-xl">📸</span>
                    <span class="font-semibold">Instagram</span>
                </a>
                <a href="https://twitter.com/faeem6327" target="_blank" class="group flex items-center gap-2 bg-blue-400 hover:bg-blue-500 px-6 py-3 rounded-full transition-all transform hover:scale-105 hover:shadow-lg">
                    <span class="text-xl">🐦</span>
                    <span class="font-semibold">Twitter</span>
                </a>
            </div>
        </div>

        <!-- Stats Section -->
        <div class="grid md:grid-cols-3 gap-6 mb-12">
            <div class="bg-gradient-to-br from-blue-500 to-purple-600 rounded-2xl p-6 text-center hover:scale-105 transition-transform">
                <div class="text-5xl font-bold mb-2">150+</div>
                <div class="text-lg text-gray-200">Commits</div>
            </div>
            <div class="bg-gradient-to-br from-purple-500 to-pink-600 rounded-2xl p-6 text-center hover:scale-105 transition-transform">
                <div class="text-5xl font-bold mb-2">25+</div>
                <div class="text-lg text-gray-200">Projects</div>
            </div>
            <div class="bg-gradient-to-br from-pink-500 to-red-600 rounded-2xl p-6 text-center hover:scale-105 transition-transform">
                <div class="text-5xl font-bold mb-2">500+</div>
                <div class="text-lg text-gray-200">Contributions</div>
            </div>
        </div>

        <!-- Footer -->
        <div class="text-center text-gray-400 mt-12 pb-8">
            <p class="text-sm">Made with ❤️ and Tailwind CSS</p>
            <p class="text-xs mt-2">© 2024 Muhammed Faheem. All rights reserved.</p>
        </div>
    </div>
</body>
</html>
