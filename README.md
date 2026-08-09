<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PK Consulting | Sustainable Mining Advocates</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: '#0b192c',
                        navyLight: '#1e293b',
                        gold: '#f39c12',
                        goldHover: '#d35400'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- Header / Navigation -->
    <header class="bg-navy text-white sticky top-0 z-50 shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <div class="bg-gold p-2 rounded-lg text-navy font-black text-xl">PK</div>
                <div>
                    <span class="text-xl font-bold tracking-wide block leading-tight">PK CONSULTING</span>
                    <span class="text-xs text-gold uppercase tracking-wider block">Sustainable Mining Advocates</span>
                </div>
            </div>
            <nav class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#about" class="hover:text-gold transition">About Us</a>
                <a href="#services" class="hover:text-gold transition">Services</a>
                <a href="#training" class="hover:text-gold transition">Training</a>
                <a href="#leadership" class="hover:text-gold transition">Leadership</a>
                <a href="#contact" class="hover:text-gold transition">Contact</a>
            </nav>
            <a href="https://wa.me/260765912830" target="_blank" class="bg-gold hover:bg-yellow-500 text-navy font-bold py-2 px-4 rounded-lg transition text-sm flex items-center gap-2">
                <i class="fa-brands fa-whatsapp text-lg"></i> Contact Us
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-navy text-white py-24 relative overflow-hidden border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
            <span class="bg-gold/20 text-gold border border-gold/40 font-semibold text-xs uppercase px-3 py-1 rounded-full tracking-widest inline-block mb-4">
                Regional Engineering Expertise
            </span>
            <h1 class="text-4xl sm:text-6xl font-extrabold mt-2 mb-6 leading-tight">
                Sustainable Mining Advocates
            </h1>
            <p class="text-lg sm:text-xl text-gray-300 max-w-3xl mx-auto mb-10 leading-relaxed">
                Specialized consulting in Geology, Mining, Geotechnical, and Environmental Engineering. Delivering precise data collection, advanced analysis, and reporting across Zambia, DRC, and Zimbabwe.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#services" class="bg-gold hover:bg-yellow-500 text-navy font-bold py-3 px-8 rounded-lg text-base transition shadow-lg">Our Expertise</a>
                <a href="#contact" class="border border-white/30 hover:border-gold hover:text-gold py-3 px-8 rounded-lg text-base transition">Get in Touch</a>
            </div>
            
            <!-- Regional Presence Strip -->
            <div class="mt-16 pt-8 border-t border-slate-800 grid grid-cols-1 md:grid-cols-3 gap-6 text-slate-400 text-sm">
                <div class="flex items-center justify-center gap-2">
                    <i class="fa-solid fa-location-dot text-gold"></i>
                    <span><strong>Headquarters:</strong> Lusaka, Zambia</span>
                </div>
                <div class="flex items-center justify-center gap-2">
                    <i class="fa-solid fa-earth-africa text-gold"></i>
                    <span><strong>Regional Operations:</strong> DRC & Zimbabwe</span>
                </div>
                <div class="flex items-center justify-center gap-2">
                    <i class="fa-solid fa-leaf text-gold"></i>
                    <span>Focus on Sustainable Mining Practices</span>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid md:grid-cols-2 gap-12 items-center">
            <div>
                <span class="text-gold font-bold text-sm uppercase tracking-wider">About PK Consulting</span>
                <h2 class="text-3xl sm:text-4xl font-bold text-navy mt-2 mb-6">Driving Sustainable Development in Mining Projects</h2>
                <p class="text-gray-600 mb-4 leading-relaxed">
                    PK Consulting is a premier engineering consulting firm dedicated to assisting mining companies, geological enterprises, and academic bodies in executing high-precision technical operations.
                </p>
                <p class="text-gray-600 mb-6 leading-relaxed">
                    We cover every phase of the mining lifecycle—from initial geological data collection and structural analysis to geotechnical rock stability, mine planning, and environmental impact management.
                </p>
                <div class="grid grid-cols-2 gap-4">
                    <div class="p-4 bg-white rounded-lg shadow-sm border border-gray-100">
                        <i class="fa-solid fa-database text-gold text-2xl mb-2"></i>
                        <h4 class="font-bold text-navy">Data Excellence</h4>
                        <p class="text-xs text-gray-500">Rigorous collection, cleaning, and validation workflows.</p>
                    </div>
                    <div class="p-4 bg-white rounded-lg shadow-sm border border-gray-100">
                        <i class="fa-solid fa-chart-line text-gold text-2xl mb-2"></i>
                        <h4 class="font-bold text-navy">Advanced Analysis</h4>
                        <p class="text-xs text-gray-500">Industry-standard modeling and numerical simulation.</p>
                    </div>
                </div>
            </div>
            <div class="bg-navy p-8 rounded-2xl text-white relative shadow-xl">
                <h3 class="text-2xl font-bold mb-4 text-gold">Our Core Pillars</h3>
                <ul class="space-y-4 text-gray-300">
                    <li class="flex items-start gap-3">
                        <i class="fa-solid fa-check-circle text-gold text-lg mt-1"></i>
                        <div>
                            <strong class="text-white block">Geological & Resource Accuracy</strong>
                            Ensuring reliable drillhole databases, wireframing, and block modeling.
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fa-solid fa-check-circle text-gold text-lg mt-1"></i>
                        <div>
                            <strong class="text-white block">Geotechnical & Mine Safety</strong>
                            Slope stability evaluations, blast simulation, and underground design safety.
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fa-solid fa-check-circle text-gold text-lg mt-1"></i>
                        <div>
                            <strong class="text-white block">Environmental Stewardship</strong>
                            Advocating for sustainable extraction methods and compliant reporting across Southern and Central Africa.
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="bg-gray-100 py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="text-gold font-bold text-sm uppercase tracking-wider">What We Do</span>
                <h2 class="text-3xl sm:text-4xl font-bold text-navy mt-1">Our Core Disciplines</h2>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Geology -->
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-blue-50 text-blue-800 rounded-lg flex items-center justify-center text-xl font-bold mb-6">
                        <i class="fa-solid fa-gem"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy mb-3">Geology</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Exploration management, geological mapping, database construction, wireframing, and 3D deposit modeling.
                    </p>
                </div>

                <!-- Mining Engineering -->
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-amber-50 text-amber-800 rounded-lg flex items-center justify-center text-xl font-bold mb-6">
                        <i class="fa-solid fa-truck-monster"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy mb-3">Mining Engineering</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Mine design, drill & blast optimization, production scheduling, equipment selection, and resource estimation.
                    </p>
                </div>

                <!-- Geotechnical Engineering -->
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-orange-50 text-orange-800 rounded-lg flex items-center justify-center text-xl font-bold mb-6">
                        <i class="fa-solid fa-mountain"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy mb-3">Geotechnical Engineering</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Rock mechanics, slope stability analysis, kinematic modeling, and ground support design for open-pit & underground mines.
                    </p>
                </div>

                <!-- Environmental Engineering -->
                <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100 hover:shadow-xl transition">
                    <div class="w-12 h-12 bg-green-50 text-green-800 rounded-lg flex items-center justify-center text-xl font-bold mb-6">
                        <i class="fa-solid fa-seedling"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy mb-3">Environmental Engineering</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Environmental impact assessments, water management integration, sustainable mine closure, and regulatory compliance.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Specialized Training Section -->
    <section id="training" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
            <span class="text-gold font-bold text-sm uppercase tracking-wider">Capacity Building</span>
            <h2 class="text-3xl font-bold text-navy mt-1">Professional Software Training</h2>
            <p class="text-gray-600 mt-2">Specialized online training programs for Geologists, Mining Engineers, Students, and Academics.</p>
        </div>

        <div class="grid md:grid-cols-2 gap-8">
            <!-- Surpac -->
            <div class="bg-white rounded-xl shadow-lg border border-gray-200 overflow-hidden flex flex-col justify-between">
                <div class="p-8">
                    <div class="flex justify-between items-start mb-4">
                        <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-3 py-1 rounded-full uppercase">Geovia Surpac</span>
                        <span class="text-xs font-semibold text-gray-500">Duration: Flexible</span>
                    </div>
                    <h3 class="text-2xl font-bold text-navy mb-3">Online Resources Estimation</h3>
                    <p class="text-gray-600 mb-6 text-sm">Comprehensive hands-on training covering geological database validation to block modeling and grade estimation.</p>
                    
                    <h4 class="font-semibold text-navy mb-2 text-sm uppercase tracking-wider">Course Modules:</h4>
                    <ul class="space-y-2 mb-6 text-gray-600 text-sm">
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Geological Database Setup & QA/QC</li>
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Resource Modeling & Wireframing</li>
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Block Modeling & Attribute Assignment</li>
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Grade Interpolation & Resource Reporting</li>
                    </ul>
                </div>
                <div class="bg-gray-50 px-8 py-4 border-t border-gray-100 flex justify-between items-center">
                    <span class="text-navy font-bold text-sm">Cost: Flexible</span>
                    <a href="https://wa.me/260765912830?text=I%20am%20interested%20in%20the%20Surpac%20Course" target="_blank" class="bg-navy hover:bg-gold hover:text-navy text-white font-semibold text-xs py-2 px-4 rounded transition">Enquire Now</a>
                </div>
            </div>

            <!-- SHOTPlus -->
            <div class="bg-white rounded-xl shadow-lg border border-gray-200 overflow-hidden flex flex-col justify-between">
                <div class="p-8">
                    <div class="flex justify-between items-start mb-4">
                        <span class="bg-orange-100 text-orange-800 text-xs font-semibold px-3 py-1 rounded-full uppercase">SHOTPlus</span>
                        <span class="text-xs font-semibold text-gray-500">Duration: Flexible</span>
                    </div>
                    <h3 class="text-2xl font-bold text-navy mb-3">Online Blast Simulation Course</h3>
                    <p class="text-gray-600 mb-6 text-sm">Master electronic initiation design, blast sequencing, timing optimization, and fragmentation prediction.</p>
                    
                    <h4 class="font-semibold text-navy mb-2 text-sm uppercase tracking-wider">Course Modules:</h4>
                    <ul class="space-y-2 mb-6 text-gray-600 text-sm">
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Drill Pattern & Blast Design</li>
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Fragmentation & Heap Shape Prediction</li>
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Explosives Loading & In-hole Designs</li>
                        <li class="flex items-center"><i class="fa-solid fa-check text-gold mr-2"></i> Vibration & Environmental Safety Analysis</li>
                    </ul>
                </div>
                <div class="bg-gray-50 px-8 py-4 border-t border-gray-100 flex justify-between items-center">
                    <span class="text-navy font-bold text-sm">Cost: Flexible</span>
                    <a href="https://wa.me/260765912830?text=I%20am%20interested%20in%20the%20SHOTPlus%20Course" target="_blank" class="bg-navy hover:bg-gold hover:text-navy text-white font-semibold text-xs py-2 px-4 rounded transition">Enquire Now</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Leadership Section -->
    <section id="leadership" class="bg-navy text-white py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-3xl mx-auto text-center">
                <span class="text-gold font-bold text-sm uppercase tracking-wider">Leadership</span>
                <h2 class="text-3xl font-bold mt-1 mb-8">Founder & Chief Engineer</h2>
                
                <div class="bg-slate-800/80 p-8 rounded-2xl border border-slate-700 text-left md:flex items-center gap-8 shadow-2xl">
                    <div class="w-24 h-24 bg-gold rounded-full flex items-center justify-center text-navy font-black text-3xl mx-auto md:mx-0 shrink-0 mb-6 md:mb-0">
                        PK
                    </div>
                    <div>
                        <h3 class="text-2xl font-bold text-white">Eng. Patrice Kizito</h3>
                        <p class="text-gold text-sm font-semibold mb-3">Founder & Chief Engineer</p>
                        <p class="text-gray-300 text-sm leading-relaxed mb-4">
                            Eng. Patrice Kizito holds a Master of Engineering (M.Eng.) degree in Mining Engineering from <strong>The University of Zambia</strong>. With deep technical expertise in mine design, geotechnical stability, and resource modeling, he guides PK Consulting's mission to champion sustainable and optimized mining practices across Southern Africa.
                        </p>
                        <div class="flex items-center gap-2 text-xs text-slate-400">
                            <i class="fa-solid fa-graduation-cap text-gold"></i>
                            <span>School of Mines, The University of Zambia</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact & Location Section -->
    <section id="contact" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
            <span class="text-gold font-bold text-sm uppercase tracking-wider">Get In Touch</span>
            <h2 class="text-3xl font-bold text-navy mt-1">Connect With PK Consulting</h2>
            <p class="text-gray-600 mt-2">Reach out to discuss consulting projects, data modeling, or software training programs.</p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
            <!-- Address Card -->
            <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100 text-center">
                <div class="w-12 h-12 bg-gold/10 text-gold rounded-full flex items-center justify-center text-xl mx-auto mb-4">
                    <i class="fa-solid fa-location-dot"></i>
                </div>
                <h3 class="font-bold text-navy mb-2">Physical Address</h3>
                <p class="text-gray-600 text-sm">Great East Road<br>Lusaka, Zambia</p>
            </div>

            <!-- Operations Card -->
            <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100 text-center">
                <div class="w-12 h-12 bg-gold/10 text-gold rounded-full flex items-center justify-center text-xl mx-auto mb-4">
                    <i class="fa-solid fa-globe"></i>
                </div>
                <h3 class="font-bold text-navy mb-2">Regional Reach</h3>
                <p class="text-gray-600 text-sm">Zambia | Democratic Republic of Congo (DRC) | Zimbabwe</p>
            </div>

            <!-- Direct Contact Card -->
            <div class="bg-white p-8 rounded-xl shadow-md border border-gray-100 text-center">
                <div class="w-12 h-12 bg-gold/10 text-gold rounded-full flex items-center justify-center text-xl mx-auto mb-4">
                    <i class="fa-solid fa-phone"></i>
                </div>
                <h3 class="font-bold text-navy mb-2">Direct Phone & WhatsApp</h3>
                <p class="text-gray-600 text-sm font-semibold mb-4">+260 765912830</p>
                <a href="https://wa.me/260765912830" target="_blank" class="inline-flex items-center gap-2 bg-gold hover:bg-yellow-500 text-navy font-bold py-2 px-4 rounded-lg text-xs transition">
                    <i class="fa-brands fa-whatsapp text-sm"></i> Send Message
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 text-gray-500 py-8 border-t border-slate-900 text-center text-xs">
        <div class="max-w-7xl mx-auto px-4 flex flex-col sm:flex-row justify-between items-center gap-4">
            <div>
                <strong class="text-white">PK Consulting</strong> — Sustainable Mining Advocates
            </div>
            <div>
                &copy; 2026 PK Consulting. All rights reserved.
            </div>
        </div>
    </footer>

</body>
</html>
