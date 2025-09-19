<template>
        <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 glass-effect">
        <div class="max-w-7xl mx-auto px-4 md:px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2 md:space-x-3">
                    <div class="w-8 h-8 md:w-10 md:h-10 premium-gradient rounded-lg flex items-center justify-center">
                        <i class="fas fa-trophy text-white text-sm md:text-lg"></i>
                    </div>
                    <span class="text-white font-bold text-lg md:text-xl">Lomba SMA 2025</span>
                </div>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-8">
                    <a href="#beranda" class="text-white hover:text-[#FF2D20] transition-colors">Beranda</a>
                    <a href="#kategori" class="text-white hover:text-[#FF2D20] transition-colors">Kategori</a>
                    <a href="#jadwal" class="text-white hover:text-[#FF2D20] transition-colors">Jadwal</a>
                    <a href="#hadiah" class="text-white hover:text-[#FF2D20] transition-colors">Hadiah</a>
                    <a href="#kontak" class="text-white hover:text-[#FF2D20] transition-colors">Kontak</a>
                </div>
                
                <!-- Desktop CTA Button -->
                <button class="hidden md:block premium-gradient text-white px-6 py-2 rounded-lg font-semibold hover:shadow-lg transition-all">
                    Daftar Sekarang
                </button>
                
                <!-- Mobile Hamburger Button -->
                <button id="mobile-menu-button" class="md:hidden text-white p-2 rounded-lg hover:bg-white hover:bg-opacity-10 transition-colors">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
            
            <!-- Mobile Menu -->
            <div id="mobile-menu" class="md:hidden hidden mt-4 pb-4">
                <div class="flex flex-col space-y-4">
                    <a href="#beranda" class="text-white hover:text-[#FF2D20] transition-colors py-2 px-4 rounded-lg hover:bg-white hover:bg-opacity-10">Beranda</a>
                    <a href="#kategori" class="text-white hover:text-[#FF2D20] transition-colors py-2 px-4 rounded-lg hover:bg-white hover:bg-opacity-10">Kategori</a>
                    <a href="#jadwal" class="text-white hover:text-[#FF2D20] transition-colors py-2 px-4 rounded-lg hover:bg-white hover:bg-opacity-10">Jadwal</a>
                    <a href="#hadiah" class="text-white hover:text-[#FF2D20] transition-colors py-2 px-4 rounded-lg hover:bg-white hover:bg-opacity-10">Hadiah</a>
                    <a href="#kontak" class="text-white hover:text-[#FF2D20] transition-colors py-2 px-4 rounded-lg hover:bg-white hover:bg-opacity-10">Kontak</a>
                    <button class="premium-gradient text-white px-6 py-3 rounded-lg font-semibold hover:shadow-lg transition-all text-center mt-2">
                        Daftar Sekarang
                    </button>
                </div>
            </div>
        </div>
    </nav>
</template>