<template>
    <section id="kategori" class="py-16 md:py-20">
        <div class="max-w-7xl mx-auto px-4 md:px-6">
            <div class="text-center mb-12 md:mb-16">
                <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold text-white mb-4">Kategori Lomba Unggulan</h2>
                <p class="text-lg md:text-xl text-gray-200 px-4">Temukan passion-mu dan raih prestasi gemilang di kompetisi bergengsi ini</p>
            </div>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 md:gap-8">
                <!-- Card 1: Matematika -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 premium-gradient flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <circle cx="50" cy="50" r="45" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <text x="50" y="35" text-anchor="middle" font-size="16" font-weight="bold">π</text>
                            <text x="30" y="55" text-anchor="middle" font-size="12">∑</text>
                            <text x="70" y="55" text-anchor="middle" font-size="12">∫</text>
                            <text x="50" y="70" text-anchor="middle" font-size="10">x²+y²=r²</text>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">PREMIUM</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Olimpiade Matematika</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Kompetisi matematika tingkat nasional dengan soal-soal menantang yang menguji kemampuan logika dan analisis matematis terdepan.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-users mr-2 text-[#FF2D20]"></i>
                                <span>1,500+ Peserta</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-clock mr-2 text-[#FF2D20]"></i>
                                <span>3 Jam Ujian</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-trophy mr-2 text-[#FF2D20]"></i>
                                <span>50 Finalis</span>
                            </div>
                        </div>
                        <div class="premium-gradient text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 50.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>

                <!-- Card 2: Sains -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 bg-gradient-to-br from-blue-500 to-purple-600 flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <circle cx="50" cy="50" r="45" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <circle cx="35" cy="40" r="8" fill="rgba(255,255,255,0.3)"/>
                            <circle cx="65" cy="40" r="6" fill="rgba(255,255,255,0.5)"/>
                            <circle cx="50" cy="60" r="10" fill="rgba(255,255,255,0.4)"/>
                            <path d="M35 40 L50 60 L65 40" stroke="currentColor" stroke-width="2" fill="none"/>
                            <text x="50" y="80" text-anchor="middle" font-size="8">H₂O</text>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">POPULER</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Olimpiade Sains</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Kompetisi sains terpadu meliputi Fisika, Kimia, dan Biologi dengan eksperimen praktis dan teori mendalam.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-users mr-2 text-blue-400"></i>
                                <span>2,000+ Peserta</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-flask mr-2 text-blue-400"></i>
                                <span>Lab Praktikum</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-medal mr-2 text-blue-400"></i>
                                <span>3 Kategori</span>
                            </div>
                        </div>
                        <div class="bg-gradient-to-r from-blue-500 to-purple-600 text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 45.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>

                <!-- Card 3: Teknologi -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 bg-gradient-to-br from-green-500 to-teal-600 flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <rect x="20" y="30" width="60" height="40" rx="4" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <rect x="25" y="35" width="50" height="25" fill="rgba(255,255,255,0.2)"/>
                            <circle cx="30" cy="65" r="2" fill="currentColor"/>
                            <circle cx="40" cy="65" r="2" fill="currentColor"/>
                            <circle cx="50" cy="65" r="2" fill="currentColor"/>
                            <text x="50" y="50" text-anchor="middle" font-size="8" fill="currentColor">&lt;/&gt;</text>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">TRENDING</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Kompetisi Teknologi</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Lomba programming, web development, dan inovasi teknologi untuk menciptakan solusi masa depan.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-code mr-2 text-green-400"></i>
                                <span>Programming</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-mobile-alt mr-2 text-green-400"></i>
                                <span>App Development</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-robot mr-2 text-green-400"></i>
                                <span>AI & Machine Learning</span>
                            </div>
                        </div>
                        <div class="bg-gradient-to-r from-green-500 to-teal-600 text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 40.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>

                <!-- Card 4: Seni & Kreativitas -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 bg-gradient-to-br from-pink-500 to-orange-500 flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <circle cx="50" cy="50" r="45" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <path d="M30 40 Q50 20 70 40 Q50 60 30 40" fill="rgba(255,255,255,0.3)"/>
                            <circle cx="40" cy="45" r="3" fill="currentColor"/>
                            <circle cx="60" cy="45" r="3" fill="currentColor"/>
                            <path d="M35 60 Q50 70 65 60" stroke="currentColor" stroke-width="2" fill="none"/>
                            <path d="M25 30 L30 25 L35 30" stroke="currentColor" stroke-width="2" fill="none"/>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">KREATIF</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Seni & Kreativitas</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Ekspresikan kreativitasmu melalui desain grafis, lukis digital, fotografi, dan karya seni inovatif lainnya.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-paint-brush mr-2 text-pink-400"></i>
                                <span>Desain Grafis</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-camera mr-2 text-pink-400"></i>
                                <span>Fotografi</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-video mr-2 text-pink-400"></i>
                                <span>Video Editing</span>
                            </div>
                        </div>
                        <div class="bg-gradient-to-r from-pink-500 to-orange-500 text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 35.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>
            </div>

            <!-- Additional Categories Row -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 md:gap-8 mt-8">
                <!-- Card 5: Bahasa & Sastra -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 bg-gradient-to-br from-indigo-500 to-blue-600 flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <rect x="25" y="20" width="50" height="60" rx="3" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <line x1="35" y1="35" x2="65" y2="35" stroke="currentColor" stroke-width="2"/>
                            <line x1="35" y1="45" x2="60" y2="45" stroke="currentColor" stroke-width="1"/>
                            <line x1="35" y1="55" x2="65" y2="55" stroke="currentColor" stroke-width="1"/>
                            <line x1="35" y1="65" x2="55" y2="65" stroke="currentColor" stroke-width="1"/>
                            <circle cx="30" cy="35" r="2" fill="currentColor"/>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">SASTRA</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Bahasa & Sastra</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Kompetisi menulis kreatif, puisi, cerpen, dan debat bahasa Indonesia untuk mengasah kemampuan literasi.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-pen-fancy mr-2 text-indigo-400"></i>
                                <span>Menulis Kreatif</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-book mr-2 text-indigo-400"></i>
                                <span>Analisis Sastra</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-microphone mr-2 text-indigo-400"></i>
                                <span>Debat Bahasa</span>
                            </div>
                        </div>
                        <div class="bg-gradient-to-r from-indigo-500 to-blue-600 text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 30.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>

                <!-- Card 6: Sosial & Lingkungan -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 bg-gradient-to-br from-emerald-500 to-green-600 flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <circle cx="50" cy="50" r="40" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <path d="M30 45 Q40 35 50 45 Q60 35 70 45" fill="rgba(255,255,255,0.3)"/>
                            <circle cx="35" cy="55" r="3" fill="currentColor"/>
                            <circle cx="50" cy="60" r="4" fill="currentColor"/>
                            <circle cx="65" cy="55" r="3" fill="currentColor"/>
                            <path d="M25 65 Q50 75 75 65" stroke="currentColor" stroke-width="2" fill="none"/>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">ECO</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Sosial & Lingkungan</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Ciptakan solusi inovatif untuk masalah sosial dan lingkungan demi masa depan yang berkelanjutan.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-leaf mr-2 text-emerald-400"></i>
                                <span>Proyek Lingkungan</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-hands-helping mr-2 text-emerald-400"></i>
                                <span>Inovasi Sosial</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-recycle mr-2 text-emerald-400"></i>
                                <span>Sustainability</span>
                            </div>
                        </div>
                        <div class="bg-gradient-to-r from-emerald-500 to-green-600 text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 25.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>

                <!-- Card 7: Bisnis & Kewirausahaan -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 bg-gradient-to-br from-yellow-500 to-orange-500 flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <rect x="20" y="40" width="60" height="35" rx="3" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <path d="M30 50 L40 40 L50 45 L60 35 L70 40" stroke="currentColor" stroke-width="3" fill="none"/>
                            <circle cx="40" cy="40" r="2" fill="currentColor"/>
                            <circle cx="50" cy="45" r="2" fill="currentColor"/>
                            <circle cx="60" cy="35" r="2" fill="currentColor"/>
                            <text x="50" y="68" text-anchor="middle" font-size="8">PROFIT</text>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">BISNIS</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Bisnis & Kewirausahaan</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Kembangkan ide bisnis inovatif dan rencana kewirausahaan untuk menjadi entrepreneur muda sukses.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-lightbulb mr-2 text-yellow-400"></i>
                                <span>Business Plan</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-chart-line mr-2 text-yellow-400"></i>
                                <span>Market Analysis</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-handshake mr-2 text-yellow-400"></i>
                                <span>Pitching</span>
                            </div>
                        </div>
                        <div class="bg-gradient-to-r from-yellow-500 to-orange-500 text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 35.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>

                <!-- Card 8: Olahraga & Kesehatan -->
                <div class="glass-effect rounded-2xl overflow-hidden hover-lift group">
                    <div class="relative h-48 bg-gradient-to-br from-red-500 to-pink-600 flex items-center justify-center">
                        <svg class="w-24 h-24 text-white group-hover:scale-110 transition-transform duration-300" viewBox="0 0 100 100" fill="currentColor">
                            <circle cx="50" cy="50" r="35" fill="rgba(255,255,255,0.1)" stroke="currentColor" stroke-width="2"/>
                            <path d="M40 35 Q50 25 60 35 Q50 45 40 35" fill="rgba(255,255,255,0.3)"/>
                            <circle cx="35" cy="50" r="8" fill="rgba(255,255,255,0.2)"/>
                            <circle cx="65" cy="50" r="8" fill="rgba(255,255,255,0.2)"/>
                            <path d="M35 58 Q50 68 65 58" stroke="currentColor" stroke-width="2" fill="none"/>
                            <text x="50" y="75" text-anchor="middle" font-size="8">❤️</text>
                        </svg>
                        <div class="absolute top-4 right-4 bg-white bg-opacity-20 rounded-full px-3 py-1">
                            <span class="text-white text-xs font-bold">SEHAT</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-white mb-3">Olahraga & Kesehatan</h3>
                        <p class="text-gray-300 text-sm mb-4 leading-relaxed">Kompetisi multi-cabang olahraga dan inovasi kesehatan untuk mempromosikan gaya hidup sehat.</p>
                        <div class="space-y-2 mb-4">
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-running mr-2 text-red-400"></i>
                                <span>Atletik</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-heartbeat mr-2 text-red-400"></i>
                                <span>Kesehatan</span>
                            </div>
                            <div class="flex items-center text-gray-300 text-xs">
                                <i class="fas fa-medal mr-2 text-red-400"></i>
                                <span>Multi Cabang</span>
                            </div>
                        </div>
                        <div class="bg-gradient-to-r from-red-500 to-pink-600 text-white px-4 py-2 rounded-lg text-center text-sm font-bold mb-4">
                            Hadiah: Rp 30.000.000
                        </div>
                        <button class="w-full glass-effect text-white py-2 rounded-lg font-semibold hover:bg-white hover:bg-opacity-10 transition-all">
                            Daftar Sekarang
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>