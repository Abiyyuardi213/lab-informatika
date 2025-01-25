<template>
    <div
        class="min-h-screen bg-gradient-to-br from-blue-50 to-white text-gray-800"
    >
        <!-- Header -->
        <header class="py-6 bg-blue-600 text-white shadow-lg sticky top-0 z-50">
            <div
                class="container mx-auto px-6 flex justify-between items-center"
            >
                <h1 class="text-2xl font-bold">Laboratorium Informatika</h1>
                <nav>
                    <ul class="flex space-x-6">
                        <li>
                            <a href="#about" class="hover:underline">Tentang</a>
                        </li>
                        <li>
                            <a href="#features" class="hover:underline"
                                >Fitur</a
                            >
                        </li>
                        <li>
                            <a href="#contact" class="hover:underline"
                                >Kontak</a
                            >
                        </li>
                    </ul>
                </nav>
            </div>
        </header>

        <!-- Hero Section -->
        <section
            class="text-center py-20 bg-gradient-to-r from-blue-100 to-blue-200"
        >
            <div class="container mx-auto px-6">
                <h2 class="text-4xl md:text-6xl font-bold text-blue-800">
                    Selamat Datang di Laboratorium Informatika
                </h2>
                <p class="mt-4 text-lg md:text-xl text-gray-700">
                    Temukan inovasi, pembelajaran, dan riset teknologi terkini
                    di sini.
                </p>
                <button
                    class="mt-6 px-6 py-3 bg-blue-600 text-white rounded-lg shadow hover:bg-blue-700 transition duration-300"
                >
                    Jelajahi Sekarang
                </button>
            </div>
        </section>

        <!-- Features Section -->
        <section id="features" class="py-16">
            <div class="container mx-auto px-6">
                <h3 class="text-3xl font-bold text-center text-gray-800">
                    Fitur Utama
                </h3>
                <p class="text-center text-gray-600 mt-2">
                    Kami menyediakan fasilitas dan layanan terbaik.
                </p>

                <div class="mt-10 grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div
                        class="p-6 bg-white rounded-lg shadow hover:shadow-lg transition duration-300"
                    >
                        <div class="text-blue-600 mb-4">
                            <svg
                                class="w-12 h-12 mx-auto"
                                fill="none"
                                stroke="currentColor"
                                stroke-width="2"
                                viewBox="0 0 24 24"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M13 16h-1v-4h-1m1 0V9m0 7h1m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                                ></path>
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center">
                            Riset Terkini
                        </h4>
                        <p class="mt-2 text-gray-600 text-center">
                            Laboratorium kami mendukung riset teknologi terbaru.
                        </p>
                    </div>

                    <div
                        class="p-6 bg-white rounded-lg shadow hover:shadow-lg transition duration-300"
                    >
                        <div class="text-blue-600 mb-4">
                            <svg
                                class="w-12 h-12 mx-auto"
                                fill="none"
                                stroke="currentColor"
                                stroke-width="2"
                                viewBox="0 0 24 24"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M5.121 17.804A9.003 9.003 0 0112 3v9h9a9.003 9.003 0 01-8.879 8.804z"
                                ></path>
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center">
                            Fasilitas Modern
                        </h4>
                        <p class="mt-2 text-gray-600 text-center">
                            Dilengkapi dengan peralatan canggih dan terkini.
                        </p>
                    </div>

                    <div
                        class="p-6 bg-white rounded-lg shadow hover:shadow-lg transition duration-300"
                    >
                        <div class="text-blue-600 mb-4">
                            <svg
                                class="w-12 h-12 mx-auto"
                                fill="none"
                                stroke="currentColor"
                                stroke-width="2"
                                viewBox="0 0 24 24"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M9.75 9.75l-2.5 2.5m0 0l2.5 2.5m-2.5-2.5H14.5m5 2.5l2.5-2.5m0 0l-2.5-2.5m2.5 2.5H10"
                                ></path>
                            </svg>
                        </div>
                        <h4 class="text-xl font-bold text-center">
                            Kolaborasi Global
                        </h4>
                        <p class="mt-2 text-gray-600 text-center">
                            Bekerjasama dengan universitas dan industri dunia.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="py-6 bg-gray-800 text-white">
            <div class="container mx-auto px-6 text-center">
                <p>
                    &copy; 2025 Laboratorium Informatika. All rights reserved.
                </p>
            </div>
        </footer>
    </div>
</template>

<script>
export default {
    name: "Wellcome",
};
</script>
