<script setup>
</script>
<template>
    <div class="min-h-screen bg-gray-100 flex items-start justify-start p-8">
        <div class="w-full max-w-4xl flex flex-col gap-6">
            <div class="w-full flex rounded-2xl shadow-lg overflow-hidden bg-white">

                <!-- Colonne gauche : 1/4 -->
                <div class="w-1/4 bg-gray-200 flex items-center justify-center p-4">
                    <img
                        src="/img/moi3.png"
                        alt="Photo de profil"
                        class="rounded-xl object-cover w-full shadow-md"
                    />
                </div>

                <!-- Colonne droite : 3/4 -->
                <div class="w-3/4 p-8 flex flex-col justify-center gap-3">
                    <h2 class="text-2xl font-bold text-gray-800">Portefolio</h2>
                    <h2 class="text-2xl font-bold text-gray-800">Martin Bergeron</h2>
                    <p class="text-gray-500 text-sm italic">Développeur Web Automatisations et Rapports</p>
                    <hr class="my-2 border-gray-200" />
                    <p class="text-gray-500 text-sm">Veuillez noter que le présent portfolio est en cours de développement.</p>
                    <p class="text-gray-500 text-sm">Je vous prie de ne pas juger trop sévèrement, il s’agit d’un travail inachevé.</p>


                    <hr class="my-2 border-gray-200" />

                    <div class="grid grid-cols-1 gap-3 text-sm text-gray-700">
                        <div class="flex items-baseline gap-2">
                            <p class="font-semibold text-gray-500 uppercase tracking-wide text-xs">Courriel</p>
                            <p>martin.bergeron@marxtinus.net</p>
                        </div>
                        <a
                            href="https://www.linkedin.com/in/martin-bergeron-48868461"
                            target="_blank"
                            rel="noopener noreferrer"
                            aria-label="LinkedIn"
                            class="inline-flex items-center gap-2"
                        >
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                viewBox="0 0 24 24"
                                class="h-5 w-5 text-[#0A66C2]"
                                fill="currentColor"
                                role="img"
                            >
                                <path
                                    d="M19 3A2 2 0 0 1 21 5V19A2 2 0 0 1 19 21H5A2 2 0 0 1 3 19V5A2 2 0 0 1 5 3H19M8.34 10.58H5.67V18H8.34V10.58M7 9.36A1.55 1.55 0 1 0 7 6.27A1.55 1.55 0 0 0 7 9.36M18.33 13.78C18.33 11.66 17.2 10.32 15.2 10.32C14.24 10.32 13.58 10.85 13.32 11.35V10.58H10.76C10.8 11.09 10.76 18 10.76 18H13.32V13.86C13.32 13.64 13.34 13.42 13.4 13.26C13.58 12.82 13.98 12.36 14.67 12.36C15.57 12.36 15.93 13.04 15.93 14.03V18H18.33V13.78Z"
                                />
                            </svg>
                            <span class="text-blue-700 underline hover:text-blue-800 leading-none">
                                https://www.linkedin.com/in/martin-bergeron-48868461
                            </span>
                        </a>

                    </div>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <a
                    href="https://wheel.marxtinus.net"
                    target="_blank"
                    @click.stop
                    class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition-shadow duration-200"
                >
    <img src="/img/wheel.jpg" alt="Projet 1" class="w-full h-40 object-cover" />
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Projet 1</h3>
                        <p class="text-sm text-gray-600">Expérimentation Vue.js :librairie vue-winwheel.
                        </p>
                    </div>
                </a>

                <a href="#" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition-shadow duration-200">
                    <img src="/img/en%20construction" alt="Projet 2" class="w-full h-40 object-cover" />
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Projet 2</h3>
                        <p class="text-sm text-gray-600">Description courte du deuxieme projet.</p>
                    </div>
                </a>

                <a href="#" class="block bg-white rounded-xl shadow-md overflow-hidden hover:shadow-lg transition-shadow duration-200">
                    <img src="/img/en%20construction" alt="Projet 3" class="w-full h-40 object-cover" />
                    <div class="p-4">
                        <h3 class="text-lg font-semibold text-gray-800">Projet 3</h3>
                        <p class="text-sm text-gray-600">Description courte du troisieme projet.</p>
                    </div>
                </a>
            </div>

        </div>
    </div>
</template>

