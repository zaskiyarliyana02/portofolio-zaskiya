<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zaskiya Erliyana Ariyadi - Software Engineer Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            800: '#1e3a8a',
                            900: '#0f172a',
                        },
                        gold: {
                            500: '#d97706',
                            600: '#b45309',
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased selection:bg-gold-500 selection:text-white">
    <!-- Header / Navbar -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md shadow-sm border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="text-xl font-bold text-navy-900 tracking-wide">
                Zaskiya<span class="text-gold-600">.</span>
            </a>
            <nav class="hidden md:flex items-center space-x-8 font-medium text-slate-600">
                <a href="#about" class="hover:text-navy-900 transition">About</a>
                <a href="#experience" class="hover:text-navy-900 transition">Experience</a>
                <a href="#projects" class="hover:text-navy-900 transition">Projects</a>
                <a href="#certifications" class="hover:text-navy-900 transition">Certifications</a>
                <a href="#skills" class="hover:text-navy-900 transition">Skills</a>
                <a href="#contact" class="hover:text-navy-900 transition">Contact</a>
            </nav>
            <!-- Tombol Download CV -->
            <a href="CV_Zaskiya_Software_Engineer_2026.pdf" download="CV_Zaskiya_Software_Engineer_2026.pdf" class="bg-navy-900 text-white px-5 py-2.5 rounded-full font-medium hover:bg-gold-600 transition shadow-md shadow-navy-900/10 flex items-center gap-2">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"/></svg>
                Download CV
            </a>
        </div>
    </header>
    <!-- Hero Section -->
    <section class="relative overflow-hidden py-24 lg:py-32 bg-gradient-to-b from-white to-slate-100">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-12 gap-12 ites-center">
            <div class="lg:col-span-7 space-y-6">
                <span class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full text-xs font-semibold bg-gold-500/10 text-gold-600 border border-gold-500/20">
                    <span class="w-2 h-2 rounded-full bg-gold-600 animate-pulse"></span>
                    Software Engineering Student (Binusian 2028)
                </span>
                <h1 class="text-4xl lg:text-6xl font-extrabold text-navy-900 tracking-tight leading-tight">
                    Building Digital Solutions with <span class="text-gold-600">Logic & Aesthetics</span>
                </h1>
                <p class="text-lg text-slate-600 max-w-2xl leading-relaxed">
                    Hello! My name is Zaskiya Erliyana Ariyadi. I am a Software Engineering student at BINUS University specializing in web development, digital product design, and database architecture.
                </p>
                <div class="flex flex-wrap gap-4 pt-4">
                    <a href="#projects" class="bg-navy-900 text-white px-7 py-3.5 rounded-xl font-medium hover:bg-gold-600 transition shadow-lg shadow-navy-900/20 flex items-center gap-2">
                        View Projects 
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <a href="#contact" class="border-2 border-slate-300 text-navy-900 px-7 py-3.5 rounded-xl font-medium hover:border-navy-900 transition">
                        Contact
                    </a>
                </div>
            </div>
            <div class="lg:col-span-5 flex justify-center">
                <div class="relative w-72 h-72 sm:w-80 sm:h-80 lg:w-96 lg:h-96">
                    <div class="absolute inset-0 bg-gold-500 rounded-3xl rotate-6 opacity-20 transform scale-105"></div>
                    <div class="absolute inset-0 bg-navy-900 rounded-3xl -rotate-3 opacity-10"></div>
                    <img src="profile.jpeg" alt="Zaskiya Erliyana Ariyadi" class="relative w-full h-full object-cover rounded-3xl shadow-xl border-4 border-white">
                </div>
            </div>
        </div>
    </section>
    <!-- About Me Section -->
    <section id="about" class="py-24 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
                <h2 class="text-xs uppercase tracking-widest text-gold-600 font-bold">About Me</h2>
                <h3 class="text-3xl font-bold text-navy-900">A Combination of Technical and Operational Skills</h3>
                <div class="w-16 h-1 bg-gold-600 mx-auto rounded-full"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-200 shadow-sm space-y-4">
                    <h4 class="text-xl font-bold text-navy-900">Brief Profile</h4>
                    <p class="text-slate-600 leading-relaxed text-justify">
                        I am a Software Engineering student at BINUS University (Binusian 2028) specializing in web development and digital product design. With a combination of UI/UX skills (Figma) and front-end development (HTML/CSS), along with a strong foundation in programming (C++, Java, PHP), I am accustomed to designing applications that strike a balance between user aesthetics and system logic. Supported by my proficiency in databases, VS Code, XAMPP, and CMD, I am ready to build functional and well-structured digital solutions.
                    </p>
                </div>
                <div class="space-y-6">
                    <div class="bg-slate-50 p-6 rounded-2xl border border-slate-200 flex items-start gap-4">
                        <div class="p-3 bg-navy-900 text-white rounded-xl shadow-md">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"/></svg>
                        </div>
                        <div>
                            <h5 class="font-bold text-navy-900">Education</h5>
                            <p class="text-sm text-slate-600 font-medium">Bina Nusantara University (BINUS)</p>
                            <p class="text-xs text-slate-500">Bachelor of Computer Science in Software Engineering (2024 – Present / Binusian 2028)</p>
                        </div>
                    </div>
                    <div class="bg-slate-50 p-6 rounded-2xl border border-slate-200 flex items-start gap-4">
                        <div class="p-3 bg-navy-900 text-white rounded-xl shadow-md">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
                        </div>
                        <div>
                            <h5 class="font-bold text-navy-900">Professional Experience</h5>
                            <p class="text-sm text-slate-600 font-medium">PT ISUZU Astra Motor Indonesia</p>
                            <p class="text-xs text-slate-500">Warehouse Administration (08 August 2022 – 08 October 2022)</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Work Experience Section -->
    <section id="experience" class="py-24 bg-slate-50 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
                <h2 class="text-xs uppercase tracking-widest text-gold-600 font-bold">Career History</h2>
                <h3 class="text-3xl font-bold text-navy-900">Work Experience</h3>
                <div class="w-16 h-1 bg-gold-600 mx-auto rounded-full"></div>
            </div>
            <div class="max-w-3xl mx-auto bg-white p-8 rounded-3xl border border-slate-200 shadow-sm relative overflow-hidden">
                <div class="absolute top-0 left-0 w-2 h-full bg-gold-600"></div>
                <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-4">
                    <div>
                        <h4 class="text-xl font-bold text-navy-900">Administration</h4>
                        <p class="text-slate-600 font-medium">PT ISUZU Astra Motor Indonesia</p>
                    </div>
                    <span class="inline-block mt-2 sm:mt-0 text-xs font-semibold bg-slate-100 text-slate-600 px-3 py-1 rounded-full border border-slate-200">
                        08 August 2022 – 08 October 2022 (2 months)
                    </span>
                </div>
                <p class="text-slate-600 text-sm leading-relaxed">
                    Managed warehouse administration at PT Isuzu Astra Motor Indonesia, with full responsibility for entering tax documents, managing shipping documents via email, and verifying the accuracy of inventory data.
                </p>
            </div>
        </div>
    </section>
    <!-- Projects Section -->
    <section id="projects" class="py-24 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
                <h2 class="text-xs uppercase tracking-widest text-gold-600 font-bold">Portfolio</h2>
                <h3 class="text-3xl font-bold text-navy-900">Featured Projects</h3>
                <div class="w-16 h-1 bg-gold-600 mx-auto rounded-full"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Project 1 -->
                <div class="bg-slate-50 rounded-3xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div class="p-8 space-y-4">
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-bold text-gold-600 uppercase tracking-wider">Web Platform</span>
                            <span class="text-xs text-slate-400">UI/UX Design</span>
                        </div>
                        <h4 class="text-2xl font-bold text-navy-900">SeatUp - Web E-Ticketing & Security Platform</h4>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            A desktop web-based e-ticketing platform that integrates a Gender-Based Seat Selection feature and an emergency reporting system to alleviate anxiety and enhance the safety of female passengers.
                        </p>
                    </div>
                    <div class="px-8 pb-8 pt-0">
                        <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-200">
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">UI/UX Design</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">Figma</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">Front-End</span>
                        </div>
                    </div>
                    <div class="px-8 pb-8 pt-0 space-y-4">
                        <button onclick="openProjectDetail('seatup')" class="w-full bg-navy-900 text-white py-3 rounded-xl font-medium hover:bg-gold-600 transition flex items-center justify-center gap-2 text-sm shadow-md">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                            View Project Detail
                        </button>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="bg-slate-50 rounded-3xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div class="p-8 space-y-4">
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-bold text-gold-600 uppercase tracking-wider">IoT & AI System</span>
                            <span class="text-xs text-slate-400">Frontend Web Application</span>
                        </div>
                        <h4 class="text-2xl font-bold text-navy-900">AI & IoT-Based Automatic Soil Irrigation System (Terradrop)</h4>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            An ESP32- and AI-based precision irrigation solution for maximum water efficiency, supported by real-time automation and a remote monitoring dashboard.
                        </p>
                    </div>
                    <div class="px-8 pb-8 pt-0">
                        <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-200">
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">HTML-5</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">UI/UX Design</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">Prototyping</span>
                        </div>
                    </div>
                     <div class="px-8 pb-8 pt-0 space-y-4">
                        <button onclick="openProjectDetail('terradrop')" class="w-full bg-navy-900 text-white py-3 rounded-xl font-medium hover:bg-gold-600 transition flex items-center justify-center gap-2 text-sm shadow-md">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                            View Project Detail
                        </button>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="bg-slate-50 rounded-3xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div class="p-8 space-y-4">
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-bold text-gold-600 uppercase tracking-wider">Database Technology</span>
                            <span class="text-xs text-slate-400">Database CMD</span>
                        </div>
                        <h4 class="text-2xl font-bold text-navy-900">Design of a Relational Database for a Freight Logistics Management System (3NF)</h4>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            An end-to-end database design project for a package delivery logistics system. Decomposing the raw data structure (Unnormalized Form) through a series of normalization steps up to Third Normal Form (3NF) to eliminate data redundancy, prevent anomalies (insert, update, delete), and design a fully integrated Entity-Relationship Diagram (ERD).
                        </p>
                    </div>
                    <div class="px-8 pb-8 pt-0">
                        <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-200">
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">MySQL</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">Normalization (3NF)</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">ERD</span>
                        </div>
                    </div>
                     <div class="px-8 pb-8 pt-0 space-y-4">
                        <button onclick="openProjectDetail('database')" class="w-full bg-navy-900 text-white py-3 rounded-xl font-medium hover:bg-gold-600 transition flex items-center justify-center gap-2 text-sm shadow-md">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                            View Project Detail
                        </button>
                    </div>
                </div>
                <!-- Project 4 -->
                <div class="bg-slate-50 rounded-3xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div class="p-8 space-y-4">
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-bold text-gold-600 uppercase tracking-wider">Community Platform</span>
                            <span class="text-xs text-slate-400">Frontend Web Application</span>
                        </div>
                        <h4 class="text-2xl font-bold text-navy-900">Clash of baNG - Game Community Platform</h4>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            An interactive community website for gamers, developed as a Human-Computer Interaction (HCI) lab project focusing on user experience.
                        </p>
                    </div>
                    <div class="px-8 pb-8 pt-0">
                        <div class="flex flex-wrap gap-2 pt-4 border-t border-slate-200">
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">Web Design</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">HCI</span>
                            <span class="text-xs bg-white text-slate-600 px-3 py-1 rounded-md border border-slate-200">User Experience</span>
                        </div>
                    </div>
                    <div class="px-8 pb-8 pt-0 space-y-4">
                        <button onclick="openProjectDetail('clashofbang')" class="w-full bg-navy-900 text-white py-3 rounded-xl font-medium hover:bg-gold-600 transition flex items-center justify-center gap-2 text-sm shadow-md">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                            View Project Detail
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Certifications Section -->
    <section id="certifications" class="py-24 bg-slate-50 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
                <h2 class="text-xs uppercase tracking-widest text-gold-600 font-bold">Credentials</h2>
                <h3 class="text-3xl font-bold text-navy-900">Certifications & Seminars</h3>
                <div class="w-16 h-1 bg-gold-600 mx-auto rounded-full"></div>
            </div>
            <!-- Grid Kartu Sertifikat -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Sertifikat 1 -->
                <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col justify-between space-y-6">
                    <div class="space-y-4">
                        <div class="flex items-center justify-between">
                            <div class="p-2.5 bg-gold-500/10 text-gold-600 rounded-xl">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                            </div>
                            <span class="text-xs font-bold uppercase tracking-wider bg-gold-500/10 text-gold-600 px-3 py-1 rounded-full">Internship / PKL</span>
                        </div>
                        <h4 class="text-xl font-bold text-navy-900">PRAKTEK KERJA INDUSTRI - PT ISUZU ASTRA MOTOR INDONESIA</h4>
                        <p class="text-xs text-slate-500 font-medium">Administrasi Sparepart • PT Isuzu Astra Motor Indonesia</p>
                        <p class="text-xs text-slate-400">08 Agustus 2022 – 08 Oktober 2022 • Predikat: Baik Sekali (Nilai: 8.3)</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                        Mengelola operasional administrasi sparepart di PT Isuzu Astra Motor Indonesia dengan performa kerja dan tingkat kedisiplinan yang sangat baik.
                        </p>
                    </div>
                    <div>
                        <!-- Ubah path gambar 'sertifikat_uiux_techfest.jpg' sesuai dengan nama file gambar sertifikat Anda -->
                        <button onclick="openCredentialModal('sertifikat/SertiPKL.jpg', 'UI/UX Competition Participant - Techfest 2026')" class="w-full border-2 border-slate-200 text-navy-900 py-3 rounded-xl font-medium hover:border-gold-600 hover:text-gold-600 transition flex items-center justify-center gap-2 text-sm">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                            View Official Credential
                        </button>
                    </div>
                </div>
                <!-- Sertifikat 2 -->
                <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col justify-between space-y-6">
                    <div class="space-y-4">
                        <div class="flex items-center justify-between">
                            <div class="p-2.5 bg-gold-500/10 text-gold-600 rounded-xl">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                            </div>
                           <span class="text-xs font-bold uppercase tracking-wider bg-gold-500/10 text-gold-600 px-3 py-1 rounded-full">Transcript</span>
                            </div>
                            <h4 class="text-xl font-bold text-navy-900">EVALUASI PENILAIAN WORK EXPERIENCE - ISUZU ASTRA</h4>
                            <p class="text-xs text-slate-500 font-medium">Department Head of Sparepart • PT Isuzu Astra Motor Indonesia</p>
                            <p class="text-xs text-slate-400">10 Oktober 2022 • Skor Rata-Rata: 8.3 / 10</p>
                            <p class="text-slate-600 text-sm leading-relaxed">
                            Penilaian resmi kinerja lapangan mencakup komponen Disiplin (8.7), Kerjasama (8.7), Inisiatif (8.0), Tanggung Jawab (8.0), dan Sikap Kerja.
                            </p>
                        </div>
                    <div>
                        <!-- Ubah path gambar 'sertifikat_webinar_techfest.jpg' sesuai dengan nama file gambar sertifikat Anda -->
                        <button onclick="openCredentialModal('sertifikat/SertiNilaiPKL.jpg', 'Webinar Participant - Techfest 2026')" class="w-full border-2 border-slate-200 text-navy-900 py-3 rounded-xl font-medium hover:border-gold-600 hover:text-gold-600 transition flex items-center justify-center gap-2 text-sm">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                            View Official Credential
                        </button>
                    </div>
                </div>
                <!-- Sertifikat 3 -->
                <div class="bg-white p-8 rounded-3xl border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col justify-between space-y-6">
                    <div class="space-y-4">
                        <div class="flex items-center justify-between">
                            <div class="p-2.5 bg-gold-500/10 text-gold-600 rounded-xl">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                            </div>
                           <span class="text-xs font-bold uppercase tracking-wider bg-gold-500/10 text-gold-600 px-3 py-1 rounded-full">Soft Skills / Workshop</span>
                        </div>
                        <h4 class="text-xl font-bold text-navy-900">SELF-DEVELOPMENT: ETIKET BERSIKAP DALAM DUNIA KERJA</h4>
                        <p class="text-xs text-slate-500 font-medium">Speaker: Dheta Arlinta, S.Ikom., MM., EPC</p>
                        <p class="text-xs text-slate-400">03 Februari 2024 • Professional Coaching</p>
                        <p class="text-slate-600 text-sm leading-relaxed">
                        Pelatihan profesional mengenai etika berkomunikasi, etiket kerja, serta pengembangan karakter profesional untuk persiapan dunia kerja.
                        </p>
                        </div>
                    <div>
                        <!-- Ubah path gambar 'sertifikat_seminar_se.jpg' sesuai dengan nama file gambar sertifikat Anda -->
                        <button onclick="openCredentialModal('sertifikat/SertiSelfDevelop.jpg', 'Seminar Participant - Breaking Into Software Engineering')" class="w-full border-2 border-slate-200 text-navy-900 py-3 rounded-xl font-medium hover:border-gold-600 hover:text-gold-600 transition flex items-center justify-center gap-2 text-sm">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"/></svg>
                            View Official Credential
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Modal Popup untuk Menampilkan Gambar Sertifikat -->
    <div id="credentialModal" class="fixed inset-0 z-50 bg-black/70 backdrop-blur-sm hidden items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-3xl w-full p-6 relative shadow-2xl space-y-4 border border-slate-200">
            <div class="flex justify-between items-center pb-3 border-b border-slate-200">
                <h3 id="credentialModalTitle" class="text-lg font-bold text-navy-900">Credential Preview</h3>
                <button onclick="closeCredentialModal()" class="text-slate-400 hover:text-navy-900 p-1 rounded-full hover:bg-slate-100 transition">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="flex justify-center items-center overflow-hidden rounded-2xl bg-slate-100 max-h-[75vh]">
                <img id="credentialModalImg" src="" alt="Official Credential" class="object-contain w-full h-full">
            </div>
        </div>
    </div>
    <!-- Modal Detail Project -->
    <div id="projectModal" class="fixed inset-0 z-50 bg-black/70 backdrop-blur-sm hidden items-center justify-center p-4 overflow-y-auto">
        <div class="bg-[#0b0f19] text-slate-200 rounded-3xl max-w-4xl w-full p-6 md:p-8 relative shadow-2xl my-8 border border-slate-800">
            <button onclick="closeProjectDetail()" class="absolute top-6 right-6 text-slate-400 hover:text-white p-2 rounded-full hover:bg-slate-800 transition">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start mt-4">
                <div class="lg:col-span-6 space-y-6">
                    <div>
                        <span id="modalCategory" class="text-xs font-bold text-red-500 uppercase tracking-widest"></span>
                        <h3 id="modalTitle" class="text-2xl font-bold text-white mt-1"></h3>
                    </div>
                    <p id="modalDesc" class="text-slate-400 text-sm leading-relaxed"></p>
                    <div class="space-y-3">
                        <h4 class="text-xs font-bold text-slate-300 uppercase tracking-wider">Key Highlights</h4>
                        <ul id="modalHighlights" class="space-y-2 text-xs text-slate-300 font-mono"></ul>
                    </div>
                    <div class="space-y-3">
                        <h4 class="text-xs font-bold text-slate-300 uppercase tracking-wider">Technologies Used</h4>
                        <div id="modalTech" class="flex flex-wrap gap-2"></div>
                    </div>
                    <div class="flex flex-wrap gap-4 pt-4 border-t border-slate-800">
                        <a id="modalLiveDemo" href="#" target="_blank" class="bg-red-600 hover:bg-red-700 text-white px-5 py-2.5 rounded-xl font-medium text-xs transition flex items-center gap-2">
                            Live Demo
                        </a>
                        <a id="modalGithub" href="#" target="_blank" class="border border-slate-700 hover:border-slate-500 text-slate-300 px-5 py-2.5 rounded-xl font-medium text-xs transition flex items-center gap-2">
                            Source Code
                        </a>
                    </div>
                </div>
                <div class="lg:col-span-6">
                    <div class="bg-[#121824] border border-red-900/40 rounded-2xl p-6 shadow-2xl relative">
                        <div class="flex items-center justify-between pb-4 mb-6 border-b border-slate-800">
                            <div class="flex items-center gap-2">
                                <span class="w-3 h-3 rounded-full bg-red-500 inline-block"></span>
                                <span class="w-3 h-3 rounded-full bg-yellow-500 inline-block"></span>
                                <span class="w-3 h-3 rounded-full bg-green-500 inline-block"></span>
                            </div>
                            <span id="modalFileName" class="text-xs font-mono text-slate-500">project.tsx</span>
                        </div>
                        <div class="bg-[#0f131d] border border-red-900/20 p-6 rounded-xl space-y-6 relative overflow-hidden">
                            <span class="inline-block bg-red-950/80 border border-red-800 text-red-400 text-[10px] font-bold px-2.5 py-1 rounded">PRODUCTION READY</span>
                            <h4 id="modalCardTitle" class="text-xl font-bold text-white"></h4>
                            <p id="modalCardCategorySub" class="text-xs text-slate-400"></p>
                            <div class="flex items-center justify-between pt-6 border-t border-slate-800 text-xs">
                                <span class="text-amber-400 font-medium">⭐ 4 Stars</span>
                                <span class="text-emerald-400 font-mono font-bold">STATUS: ACTIVE</span>
                            </div>
                        </div>
                        <div class="grid grid-cols-2 gap-4 mt-6 pt-6 border-t border-slate-800 text-xs">
                            <div>
                                <span class="text-slate-500 block mb-1">CATEGORY</span>
                                <span id="modalFooterCat" class="text-white font-medium"></span>
                            </div>
                            <div>
                                <span class="text-slate-500 block mb-1">RELEASED</span>
                                <span class="text-white font-medium">2026</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- My Skills Section -->
    <section id="skills" class="py-24 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
                <h2 class="text-xs uppercase tracking-widest text-gold-600 font-bold">Skills</h2>
                <h3 class="text-3xl font-bold text-navy-900">Hard Skills & Soft Skills</h3>
                <div class="w-16 h-1 bg-gold-600 mx-auto rounded-full"></div>
            </div>
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <!-- Hard Skills -->
                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-200 shadow-sm space-y-6">
                    <h4 class="text-xl font-bold text-navy-900 flex items-center gap-2">
                        <svg class="w-5 h-5 text-gold-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"/></svg>
                        Hard Skills
                    </h4>
                    <div class="space-y-4">
                        <div>
                            <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider block mb-2">Programming & Web</span>
                            <div class="flex flex-wrap gap-2">
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">C++</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">Java</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">PHP</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">HTML5</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">CSS3</span>
                            </div>
                        </div>
                        <div>
                            <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider block mb-2">Database & Systems</span>
                            <div class="flex flex-wrap gap-2">
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">Database Design</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">Normalization (3NF)</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">ERD</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">XAMPP</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">CMD</span>
                            </div>
                        </div>
                        <div>
                            <span class="text-xs font-semibold text-slate-400 uppercase tracking-wider block mb-2">Administration & Tools</span>
                            <div class="flex flex-wrap gap-2">
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">Tax Form Entry</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">Document Management</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">Figma</span>
                                <span class="bg-white text-navy-900 px-3.5 py-1.5 rounded-lg text-sm font-medium border border-slate-200">VS Code</span>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Soft Skills -->
                <div class="bg-slate-50 p-8 rounded-3xl border border-slate-200 shadow-sm space-y-6">
                    <h4 class="text-xl font-bold text-navy-900 flex items-center gap-2">
                        <svg class="w-5 h-5 text-gold-600" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>
                        Soft Skills
                    </h4>
                    <div class="space-y-4">
                        <div class="p-4 bg-white rounded-2xl border border-slate-100">
                            <h5 class="font-bold text-navy-900 text-sm">Problem Solving</h5>
                            <p class="text-xs text-slate-600 mt-1">Able to analyze problems and design logical structures for complex systems.</p>
                        </div>
                        <div class="p-4 bg-white rounded-2xl border border-slate-100">
                            <h5 class="font-bold text-navy-900 text-sm">User-Centric Design</h5>
                            <p class="text-xs text-slate-600 mt-1">Focused on user experience when designing application interfaces.</p>
                        </div>
                        <div class="p-4 bg-white rounded-2xl border border-slate-100">
                            <h5 class="font-bold text-navy-900 text-sm">Administrative Accuracy</h5>
                            <p class="text-xs text-slate-600 mt-1">Meticulous in managing company documents, tax matters, and inventory records.</p>
                        </div>
                        <div class="p-4 bg-white rounded-2xl border border-slate-100">
                            <h5 class="font-bold text-navy-900 text-sm">Teamwork & Collaboration</h5>
                            <p class="text-xs text-slate-600 mt-1">Experienced in collaborating on cross-functional projects spanning both technology and operations.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section id="contact" class="py-24 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
                <h2 class="text-xs uppercase tracking-widest text-gold-600 font-bold">Contact</h2>
                <h3 class="text-3xl font-bold text-navy-900">Let's Connect</h3>
                <div class="w-16 h-1 bg-gold-600 mx-auto rounded-full"></div>
                <p class="text-slate-600 text-sm">Interested in collaborating or discussing professional opportunities? Feel free to reach out.</p>
            </div>
            <div class="max-w-xl mx-auto bg-slate-50 p-8 rounded-3xl border border-slate-200 shadow-sm space-y-6">
                <div class="flex items-center gap-4">
                    <div class="p-3 bg-navy-900 text-white rounded-xl">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
                    </div>
                    <div>
                        <span class="text-xs text-slate-400 font-medium block">Academic Email</span>
                        <a href="mailto:zaskiya.ariyadi@binus.ac.id" class="text-navy-900 font-semibold hover:text-gold-600 transition">zaskiya.ariyadi@binus.ac.id</a>
                    </div>
                </div>
                <div class="flex items-center gap-4">
                    <div class="p-3 bg-navy-900 text-white rounded-xl">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
                    </div>
                    <div>
                        <span class="text-xs text-slate-400 font-medium block">Personal Email</span>
                        <a href="mailto:zaskiya.erliyana28@gmail.com" class="text-navy-900 font-semibold hover:text-gold-600 transition">zaskiya.erliyana28@gmail.com</a>
                    </div>
                </div>
                <div class="flex items-center gap-4">
                    <div class="p-3 bg-navy-900 text-white rounded-xl">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    </div>
                    <div>
                        <span class="text-xs text-slate-400 font-medium block">Phone / WhatsApp</span>
                        <a href="tel:+6287861860496" class="text-navy-900 font-semibold hover:text-gold-600 transition">+62 878-6186-0496</a>
                    </div>
                </div>
                <div class="flex items-center gap-4">
                    <div class="p-3 bg-navy-900 text-white rounded-xl">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13.828 10.172a4 4 0 00-5.656 0l-4 4a4 4 0 105.656 5.656l1.102-1.101m-.758-4.899a4 4 0 005.656 0l4-4a4 4 0 00-5.656-5.656l-1.1 1.1"/></svg>
                    </div>
                    <div>
                        <span class="text-xs text-slate-400 font-medium block">Line Profile</span>
                        <a href="https://line.me/ti/p/rcNtrFQnfW" target="_blank" class="text-navy-900 font-semibold hover:text-gold-600 transition">line.me/ti/p/rcNtrFQnfW</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-navy-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-6 text-center space-y-4">
            <p class="text-xl font-bold tracking-wide">Zaskiya Erliyana Ariyadi</p>
            <p class="text-sm text-slate-400">Software Engineering Student | Binusian 2028</p>
            <p class="text-xs text-slate-500 pt-4 border-t border-slate-800">&copy; 2026 Zaskiya Erliyana Ariyadi. All rights reserved.</p>
        </div>
    </footer>
    <!-- JavaScript Handlers -->
    <!-- JavaScript Handlers -->
    <script>
        // Modal Sertifikat
        function openCredentialModal(imageSrc, titleText) {
            const modal = document.getElementById('credentialModal');
            const imgElement = document.getElementById('credentialModalImg');
            const titleElement = document.getElementById('credentialModalTitle');
            imgElement.src = imageSrc;
            titleElement.innerText = titleText;
            imgElement.onerror = function() {
                alert("Gagal memuat gambar! Pastikan nama file dan lokasi gambar sudah sesuai: " + imageSrc);
            };
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }
        function closeCredentialModal() {
            const modal = document.getElementById('credentialModal');
            modal.classList.remove('flex');
            modal.classList.add('hidden');
            document.body.style.overflow = 'auto';
        }
        // Modal Project Details Data & Functions
        const projectData = {
            seatup: {
                category: "WEB PLATFORM",
                title: "SeatUp - Web E-Ticketing & Security Platform",
                desc: "A desktop web-based e-ticketing platform that integrates a Gender-Based Seat Selection feature and an emergency reporting system to alleviate anxiety and enhance the safety of female passengers.",
                fileName: "project-seatup.tsx",
                highlights: [
                    "Gender-Based Seat Selection system for passenger peace of mind",
                    "Integrated emergency reporting button and live alert system",
                    "Built with responsive layout and clean component structure",
                    "Optimized user flow reducing booking friction"
                ],
                tech: ["UI/UX Design", "Figma", "Front-End", "HTML5", "CSS3"],
                liveDemo: "https://www.figma.com/proto/ozE6WIQhkbDOqlyw346wXb/HCI-LEC?node-id=0-1&t=ueZHINg5prlhFLh2-1",
                github: "https://github.com/username/seatup-project"
            },
            terradrop: {
                category: "IOT & AI SYSTEM",
                title: "AI & IoT-Based Automatic Soil Irrigation System (Terradrop)",
                desc: "An ESP32- and AI-based precision irrigation solution for maximum water efficiency, supported by real-time automation and a remote monitoring dashboard.",
                fileName: "project-terradrop.tsx",
                highlights: [
                    "ESP32 microcontroller integration with soil moisture sensors",
                    "AI-driven predictive watering schedule algorithms",
                    "Real-time monitoring dashboard with remote control capability",
                    "Maximum water conservation and automated valve control"
                ],
                tech: ["HTML-5", "UI/UX Design", "Prototyping", "ESP32", "Sensors"],
                liveDemo: "https://your-terradrop-demo.com",
                github: "https://github.com/username/terradrop-iot"
            },
            database: {
                category: "DATABASE TECHNOLOGY",
                title: "Design of a Relational Database for a Freight Logistics Management System (3NF)",
                desc: "An end-to-end database design project for a package delivery logistics system. Decomposing the raw data structure (Unnormalized Form) through a series of normalization steps up to Third Normal Form (3NF) to eliminate data redundancy, prevent anomalies, and design a fully integrated Entity-Relationship Diagram (ERD).",
                fileName: "project-database.sql",
                highlights: [
                    "Comprehensive data normalization from unnormalized form up to 3NF",
                    "Elimination of data redundancy and prevention of update/insert anomalies",
                    "Fully integrated Entity-Relationship Diagram (ERD) architecture",
                    "Optimized relational schema for freight and package tracking"
                ],
                tech: ["MySQL", "Normalization (3NF)", "ERD", "Database Design"],
                liveDemo: "https://your-database-demo.com",
                github: "https://github.com/username/freight-logistics-db"
            },
            clashofbang: {
                category: "COMMUNITY PLATFORM",
                title: "Clash of baNG - Game Community Platform",
                desc: "An interactive community website for gamers, developed as a Human-Computer Interaction (HCI) lab project focusing on user experience.",
                fileName: "project-clashofbang.tsx",
                highlights: [
                    "Interactive user interface tailored for gaming community engagement",
                    "Human-Computer Interaction (HCI) centered layout and user flow",
                    "Discussion forums and gamer profile management system",
                    "Responsive design optimized for smooth cross-device navigation"
                ],
                tech: ["Web Design", "HCI", "User Experience", "HTML5", "CSS3"],
                liveDemo: "https://your-clashofbang-demo.com",
                github: "https://github.com/username/clash-of-bang"
            }
        };
        function openProjectDetail(projectId) {
            const data = projectData[projectId];
            if (!data) return;
            document.getElementById('modalCategory').innerText = data.category;
            document.getElementById('modalTitle').innerText = data.title;
            document.getElementById('modalDesc').innerText = data.desc;
            document.getElementById('modalFileName').innerText = data.fileName;
            document.getElementById('modalCardTitle').innerText = data.title;
            document.getElementById('modalCardCategorySub').innerText = data.category;
            document.getElementById('modalFooterCat').innerText = data.category;
            const highlightsEl = document.getElementById('modalHighlights');
            highlightsEl.innerHTML = '';
            data.highlights.forEach(item => {
                highlightsEl.innerHTML += `<li class="flex items-center gap-2"><span class="text-red-500 font-bold">↳</span> ${item}</li>`;
            });
            const techEl = document.getElementById('modalTech');
            techEl.innerHTML = '';
            data.tech.forEach(t => {
                techEl.innerHTML += `<span class="bg-[#1a2233] text-red-400 border border-red-900/30 px-3 py-1 rounded-md text-xs font-mono">${t}</span>`;
            });
            document.getElementById('modalLiveDemo').href = data.liveDemo;
            document.getElementById('modalGithub').href = data.github;
            const modal = document.getElementById('projectModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }
        function closeProjectDetail() {
            const modal = document.getElementById('projectModal');
            modal.classList.remove('flex');
            modal.classList.add('hidden');
            document.body.style.overflow = 'auto';
        }
        // Global Event Listener untuk menutup modal saat klik backdrop luar
        window.onclick = function(event) {
            const projectModal = document.getElementById('projectModal');
            const credentialModal = document.getElementById('credentialModal');
            if (event.target === projectModal) {
                closeProjectDetail();
            }
            if (event.target === credentialModal) {
                closeCredentialModal();
            }
        };
    </script>
</body>
</html>