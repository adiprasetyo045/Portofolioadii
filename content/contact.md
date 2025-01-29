---
title: ""
layout: page
---
<div class="flex flex-col items-center min-h-screen bg-gray-900 text-white py-12 px-4">   
    <!-- Judul -->
    <h1 class="text-5xl font-bold tracking-wide text-gray-100">Hubungi saya</h1>
    <p class="text-gray-400 mt-2">Saya akan senang menjawab pertanyaan anda!</p>
    <!-- Formulir -->
    <form class="mt-6 bg-gray-800 p-6 w-full max-w-lg rounded-lg shadow-lg">
        <div class="mb-4">
            <label for="name" class="block text-white mb-1">Nama:</label>
            <input type="text" id="name" name="name" required class="w-full p-3 border rounded bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-blue-500">
        </div>
        <div class="mb-4">
            <label for="email" class="block text-white mb-1">Alamat Email:</label>
            <input type="email" id="email" name="email" required class="w-full p-3 border rounded bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-blue-500">
        </div>
        <div class="mb-4">
            <label for="subject" class="block text-white mb-1">Subjek:</label>
            <input type="text" id="subject" name="subject" required class="w-full p-3 border rounded bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-blue-500">
        </div>
        <div class="mb-4">
            <label for="message" class="block text-white mb-1">Pesan Anda:</label>
            <textarea id="message" name="message" required class="w-full p-3 border rounded bg-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
        </div>
        <button type="submit" class="w-full bg-blue-500 text-white p-3 rounded-lg hover:bg-blue-600 transition duration-300">Kirim Pesan</button>
    </form>
    <!-- Bagian Sosial Media -->
    <div class="mt-8">
        <p class="text-gray-400 text-lg font-semibold">MEDIA SOSIAL SAYA</p>
        <div class="flex justify-center space-x-6 mt-3">
            <a href="https://x.com/AadyprazZy">
                <img src="/assets/media/icons/twitter.png" alt="Twitter" class="w-8 h-8 hover:opacity-75">
            </a>
            <a href="https://github.com/adiprasetyo045">
                <img src="/assets/media/icons/github.png" 
                alt="GitHub" class="w-8 h-8 hover:opacity-75">
            </a>
            <a href=" https://www.instagram.com/adiprasetyo/">
                <img src="/assets/media/icons/instagram.png" alt="Instagram" class="w-8 h-8 hover:opacity-75">
            </a>
            <a href="mailto:prasetyaadhi398@gmail.com">
                <img src="/assets/media/icons/email.png" alt="Email" class="w-8 h-8 hover:opacity-75">
            </a>
        </div>
    </div>