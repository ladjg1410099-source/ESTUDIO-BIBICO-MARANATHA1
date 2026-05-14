[index_v2.html](https://github.com/user-attachments/files/27780422/index_v2.html)

<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capacitación Ministerial 2026 | Liderazgo Bíblico</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Playfair+Display:ital,wght@0,700;0,900;1,700&display=swap" rel="stylesheet">
    <style>
        :root {
            --brand-primary: #0f172a;
            --brand-accent: #2563eb;
            --brand-gold: #d4af37;
        }
        body { font-family: 'Plus Jakarta Sans', sans-serif; background-color: #f8fafc; }
        h1, h2, h3, .font-serif { font-family: 'Playfair Display', serif; }
        
        .glass-nav {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(12px);
            border-bottom: 1px solid rgba(226, 232, 240, 0.8);
        }

        .hero-visual {
            background: linear-gradient(135deg, rgba(15, 23, 42, 0.95) 0%, rgba(30, 41, 59, 0.8) 100%), 
                        url('https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&q=80&w=2000');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .card-premium {
            background: white;
            border: 1px solid #e2e8f0;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .card-premium:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.05), 0 10px 10px -5px rgba(0, 0, 0, 0.02);
            border-color: #3b82f6;
        }

        .text-gradient {
            background: linear-gradient(to right, #2563eb, #7c3aed);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .verse-box {
            position: relative;
            padding-left: 2rem;
            border-left: 3px solid #3b82f6;
        }
        
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        .section-divider {
            height: 1px;
            background: linear-gradient(to right, transparent, #e2e8f0, transparent);
        }
    </style>
</head>
<body class="text-slate-900">

    <!-- Navegación Premium -->
    <nav class="fixed w-full z-50 glass-nav px-8 py-5">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="flex items-center gap-2">
                <div class="w-10 h-10 bg-blue-600 rounded-xl flex items-center justify-center text-white font-bold shadow-lg shadow-blue-200">L</div>
                <div class="text-xl font-extrabold tracking-tighter text-slate-900">
                    LIDERAZGO <span class="text-blue-600 font-medium">2026</span>
                </div>
            </div>
            <div class="hidden md:flex space-x-10 text-[13px] font-bold uppercase tracking-[0.15em] text-slate-500">
                <a href="#inicio" class="hover:text-blue-600 transition-colors">Inicio</a>
                <a href="#fundamentos" class="hover:text-blue-600 transition-colors">Fundamentos</a>
                <a href="#deberes" class="hover:text-blue-600 transition-colors">Deberes</a>
                <a href="#salud" class="hover:text-blue-600 transition-colors">Bienestar</a>
                <a href="#equipo" class="hover:text-blue-600 transition-colors">Equipo</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="relative min-h-screen flex items-center justify-center hero-visual px-6 pt-20">
        <div class="absolute inset-0 bg-gradient-to-b from-transparent to-slate-900/50"></div>
        <div class="relative z-10 max-w-4xl text-center">
            <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-white/10 backdrop-blur-md border border-white/20 text-blue-300 text-xs font-bold uppercase tracking-widest mb-8 floating">
                <span class="relative flex h-2 w-2">
                  <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-blue-400 opacity-75"></span>
                  <span class="relative inline-flex rounded-full h-2 w-2 bg-blue-500"></span>
                </span>
                Edición Ministerial 2026
            </div>
            <h1 class="text-6xl md:text-8xl font-black text-white mb-6 leading-tight">
                El Deber y la <span class="text-blue-500">Responsabilidad</span>
            </h1>
            <p class="text-xl md:text-2xl text-slate-300 font-light max-w-2xl mx-auto mb-12 italic">
                "Velando por las almas como quienes han de dar cuenta."
            </p>
            <div class="flex flex-col sm:flex-row gap-5 justify-center">
                <a href="#fundamentos" class="px-10 py-5 bg-blue-600 text-white rounded-2xl font-bold hover:bg-blue-700 transition shadow-2xl shadow-blue-600/30">Iniciar Módulo</a>
                <a href="#equipo" class="px-10 py-5 bg-white/10 backdrop-blur-md text-white rounded-2xl font-bold hover:bg-white/20 transition border border-white/30">Conocer al Equipo</a>
            </div>
        </div>
    </section>

    <!-- Fundamentos Teológicos -->
    <section id="fundamentos" class="py-32 px-8 bg-white overflow-hidden">
        <div class="max-w-7-xl mx-auto">
            <div class="flex flex-col lg:flex-row gap-20 items-center">
                <div class="lg:w-1/2">
                    <h2 class="text-5xl font-black text-slate-900 mb-8 leading-[1.1]">El Carácter del <span class="text-gradient">Líder Siervo</span></h2>
                    <div class="space-y-10">
                        <div class="verse-box">
                            <h4 class="font-bold text-xl mb-3 text-slate-800">El Llamado al Sacrificio</h4>
                            <p class="text-slate-600 leading-relaxed mb-4">El liderazgo en el Reino de Dios no es una posición de poder, sino una de servicio absoluto. Jesús redefinió la autoridad lavando los pies de sus discípulos.</p>
                            <span class="text-sm font-bold text-blue-600 italic">Cita Clave: Marcos 10:43-45</span>
                        </div>
                        <div class="verse-box">
                            <h4 class="font-bold text-xl mb-3 text-slate-800">La Integridad Irreprochable</h4>
                            <p class="text-slate-600 leading-relaxed mb-4">Para el 2026, la mayor moneda del líder es su testimonio. Ser la misma persona en el altar y en la intimidad es el fundamento de la confianza ministerial.</p>
                            <span class="text-sm font-bold text-blue-600 italic">Cita Clave: 1 Timoteo 3:2</span>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 relative">
                    <div class="absolute -top-10 -right-10 w-64 h-64 bg-blue-50 rounded-full blur-3xl opacity-60"></div>
                    <div class="relative z-10 p-4 bg-slate-100 rounded-[2.5rem]">
                        <img src="https://images.unsplash.com/photo-1544427920-c49ccfb85579?auto=format&fit=crop&q=80&w=1000" class="rounded-[2rem] shadow-2xl" alt="Liderazgo">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Responsabilidades Core -->
    <section id="deberes" class="py-32 px-8 bg-slate-50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-20">
                <h2 class="text-4xl font-black text-slate-900 mb-4 uppercase tracking-tighter">Deberes Ministeriales</h2>
                <div class="w-20 h-1.5 bg-blue-600 mx-auto rounded-full"></div>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="card-premium p-10 rounded-[2rem]">
                    <div class="w-14 h-14 bg-blue-50 text-blue-600 rounded-2xl flex items-center justify-center text-2xl mb-8">🛡️</div>
                    <h3 class="text-2xl font-bold mb-4">Protección</h3>
                    <p class="text-slate-500 text-sm leading-relaxed mb-6">Velar por el rebaño contra falsas doctrinas y ataques espirituales, manteniendo la unidad del cuerpo de Cristo.</p>
                    <div class="pt-6 border-t border-slate-100 text-[11px] font-bold text-blue-600 uppercase tracking-widest">Hechos 20:28</div>
                </div>
                <div class="card-premium p-10 rounded-[2rem]">
                    <div class="w-14 h-14 bg-purple-50 text-purple-600 rounded-2xl flex items-center justify-center text-2xl mb-8">🥖</div>
                    <h3 class="text-2xl font-bold mb-4">Alimento</h3>
                    <p class="text-slate-500 text-sm leading-relaxed mb-6">Administrar fielmente la Palabra de Dios, alimentando a los santos con verdad exegética y aplicación práctica.</p>
                    <div class="pt-6 border-t border-slate-100 text-[11px] font-bold text-purple-600 uppercase tracking-widest">Juan 21:17</div>
                </div>
                <div class="card-premium p-10 rounded-[2rem]">
                    <div class="w-14 h-14 bg-amber-50 text-amber-600 rounded-2xl flex items-center justify-center text-2xl mb-8">🌱</div>
                    <h3 class="text-2xl font-bold mb-4">Sucesión</h3>
                    <p class="text-slate-500 text-sm leading-relaxed mb-6">Identificar y mentorear a la próxima generación de líderes, garantizando que la obra continúe con excelencia.</p>
                    <div class="pt-6 border-t border-slate-100 text-[11px] font-bold text-amber-600 uppercase tracking-widest">2 Timoteo 2:2</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bienestar del Líder -->
    <section id="salud" class="py-32 px-8 bg-blue-900 text-white relative overflow-hidden">
        <div class="absolute inset-0 opacity-10">
            <svg class="h-full w-full" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C 20 0 50 0 100 100 Z" fill="currentColor"></path>
            </svg>
        </div>
        <div class="max-w-5xl mx-auto relative z-10">
            <div class="grid lg:grid-cols-2 gap-20 items-center">
                <div>
                    <h2 class="text-5xl font-black mb-8 leading-tight italic">Autocuidado & <br>Sostenibilidad</h2>
                    <p class="text-blue-200 text-lg mb-10">El ministerio no es una carrera de velocidad, es un maratón de fidelidad. Para cuidar de otros en 2026, primero debes cuidar el templo del Espíritu que eres tú.</p>
                    <div class="space-y-6">
                        <div class="flex items-center gap-4 group">
                            <div class="w-10 h-10 rounded-full border border-blue-400 flex items-center justify-center group-hover:bg-blue-400 transition">✓</div>
                            <span class="font-bold">Retiro Espiritual (Marcos 6:31)</span>
                        </div>
                        <div class="flex items-center gap-4 group">
                            <div class="w-10 h-10 rounded-full border border-blue-400 flex items-center justify-center group-hover:bg-blue-400 transition">✓</div>
                            <span class="font-bold">Límites Saludables (Proverbios 4:23)</span>
                        </div>
                    </div>
                </div>
                <div class="bg-white/10 backdrop-blur-xl p-12 rounded-[3rem] border border-white/20">
                    <h4 class="text-3xl font-serif italic mb-6">Mateo 18:15-17</h4>
                    <p class="text-blue-100 leading-relaxed italic text-lg">"La resolución de conflictos en 2026 requiere un corazón que busque la paz y una lengua que hable la verdad en amor."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Equipo -->
    <footer id="equipo" class="bg-white pt-32 pb-16 px-8">
        <div class="max-w-7xl mx-auto">
            <div class="flex flex-col items-center mb-24">
                <div class="relative mb-8">
                    <div class="absolute inset-0 bg-blue-200 rounded-full blur-2xl animate-pulse"></div>
                    <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?auto=format&fit=crop&q=80&w=200" class="relative w-32 h-32 rounded-full object-cover border-4 border-white shadow-2xl" alt="Pastora">
                </div>
                <h3 class="text-3xl font-black text-slate-900">Pastora Leanny Delgado</h3>
                <p class="text-blue-600 font-bold uppercase tracking-[0.2em] text-xs mt-2">Dirección Ministerial 2026</p>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-12 text-center border-t border-slate-100 pt-16 mb-20">
                <div class="group">
                    <p class="text-slate-400 text-xs font-bold uppercase tracking-widest mb-1 group-hover:text-blue-600 transition">Líder</p>
                    <p class="font-black text-slate-900 text-lg">Luis Ángel</p>
                </div>
                <div class="group">
                    <p class="text-slate-400 text-xs font-bold uppercase tracking-widest mb-1 group-hover:text-blue-600 transition">Apoyo</p>
                    <p class="font-black text-slate-900 text-lg">Scarlett</p>
                </div>
                <div class="group">
                    <p class="text-slate-400 text-xs font-bold uppercase tracking-widest mb-1 group-hover:text-blue-600 transition">Apoyo</p>
                    <p class="font-black text-slate-900 text-lg">Yossendy</p>
                </div>
                <div class="group">
                    <p class="text-slate-400 text-xs font-bold uppercase tracking-widest mb-1 group-hover:text-blue-600 transition">Apoyo</p>
                    <p class="font-black text-slate-900 text-lg">Martín</p>
                </div>
                <div class="group">
                    <p class="text-slate-400 text-xs font-bold uppercase tracking-widest mb-1 group-hover:text-blue-600 transition">Apoyo</p>
                    <p class="font-black text-slate-900 text-lg">Alberto</p>
                </div>
                <div class="group">
                    <p class="text-slate-400 text-xs font-bold uppercase tracking-widest mb-1 group-hover:text-blue-600 transition">Apoyo</p>
                    <p class="font-black text-slate-900 text-lg">Daniel</p>
                </div>
            </div>

            <div class="text-center text-slate-400 text-[10px] font-bold uppercase tracking-[0.3em]">
                &copy; 2026 Capacitación de Liderazgo Bíblico. Todos los derechos reservados.
            </div>
        </div>
    </footer>

</body>
</html>
