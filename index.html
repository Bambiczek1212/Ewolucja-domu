```html
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Ewolucja Domu - Klikacz Dewelopera</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=Space+Grotesk:wght@500;700&display=swap');
        
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #0b0f19;
            touch-action: manipulation;
        }

        .heading-font {
            font-family: 'Space Grotesk', sans-serif;
        }

        /* Animacja unoszenia się tekstu z monetami */
        @keyframes floatUpAndFade {
            0% {
                transform: translateY(0) scale(1);
                opacity: 1;
            }
            100% {
                transform: translateY(-120px) scale(0.8);
                opacity: 0;
            }
        }

        .click-particle {
            position: absolute;
            animation: floatUpAndFade 0.8s cubic-bezier(0.25, 1, 0.5, 1) forwards;
            pointer-events: none;
        }

        /* Pulsowanie dla elementów interaktywnych */
        @keyframes pulseGlow {
            0%, 100% { filter: drop-shadow(0 0 10px rgba(139, 92, 246, 0.4)); }
            50% { filter: drop-shadow(0 0 25px rgba(139, 92, 246, 0.8)); }
        }

        .active-glow {
            animation: pulseGlow 2s infinite;
        }
    </style>
</head>
<body class="min-h-screen text-slate-100 flex flex-col items-center justify-between p-4 md:p-6 select-none bg-gradient-to-b from-[#0f172a] to-[#020617]">

    <!-- GŁÓWNY KONTENER GRY -->
    <div class="w-full max-w-5xl grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch my-auto">
        
        <!-- PANEL LEWY: STATUS I KLIKANIE DOMU -->
        <div class="lg:col-span-7 bg-slate-900/60 border border-slate-800/80 backdrop-blur-md rounded-3xl p-6 flex flex-col justify-between items-center relative overflow-hidden shadow-2xl min-h-[500px] md:min-h-[580px]">
            
            <!-- Dekompozycja tła -->
            <div class="absolute -top-24 -left-24 w-48 h-48 bg-violet-600/10 rounded-full blur-3xl pointer-events-none"></div>
            <div class="absolute -bottom-24 -right-24 w-48 h-48 bg-emerald-600/10 rounded-full blur-3xl pointer-events-none"></div>

            <!-- Nagłówek statystyk finansowych -->
            <div class="w-full text-center z-10 flex flex-col items-center">
                <div class="flex items-center gap-2 justify-center mb-1">
                    <span class="text-xs font-bold uppercase tracking-widest text-slate-400 bg-slate-800/60 px-3 py-1 rounded-full border border-slate-700/50">Budżet</span>
                    <button id="btn-audio-toggle" class="p-1 rounded-full bg-slate-800 hover:bg-slate-700 border border-slate-700/50 text-xs transition duration-200">
                        🔊 Dźwięki Wł.
                    </button>
                </div>
                <!-- Wielki Stan Konta -->
                <h1 id="money-display" class="heading-font text-4xl md:text-5xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-emerald-400 via-teal-300 to-emerald-500 mb-1 transition-all duration-75">
                    $0
                </h1>
                <p id="dps-display" class="text-xs md:text-sm text-slate-400 font-semibold tracking-wide">
                    Przychód pasywny: <span class="text-emerald-400 font-bold">+$0 / sek</span>
                </p>
            </div>

            <!-- Główna Sekcja Klikania Domu -->
            <div class="relative w-full flex flex-col items-center justify-center my-6 z-10">
                <!-- Kontener klikalny z efektem sprężystości -->
                <div id="house-click-area" class="cursor-pointer select-none active:scale-95 transition-transform duration-75 ease-out relative p-4 flex items-center justify-center w-64 h-64 md:w-72 md:h-72 active-glow rounded-full bg-slate-950/20 border border-violet-900/10">
                    
                    <!-- DYNAMICZNE GRAFIKI DOMÓW (SVGs) -->
                    <!-- SZAŁAS Z KARTONU (Stage 0) -->
                    <svg id="svg-stage-0" class="house-svg w-4/5 h-4/5 transition-all duration-300" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <rect x="25" y="50" width="50" height="35" rx="4" fill="#a78bfa" stroke="#6d28d9" stroke-width="3"/>
                        <path d="M20 52 L50 25 L80 52" stroke="#6d28d9" stroke-width="4" stroke-linecap="round"/>
                        <rect x="35" y="55" width="12" height="12" rx="1" fill="#fef08a" stroke="#6d28d9" stroke-width="2"/>
                        <line x1="41" y1="55" x2="41" y2="67" stroke="#6d28d9" stroke-width="2"/>
                        <line x1="35" y1="61" x2="47" y2="61" stroke="#6d28d9" stroke-width="2"/>
                        <!-- Kartonowe klapy -->
                        <path d="M22 40 L38 32" stroke="#4c1d95" stroke-width="3" stroke-linecap="round"/>
                        <path d="M78 40 L62 32" stroke="#4c1d95" stroke-width="3" stroke-linecap="round"/>
                        <rect x="53" y="65" width="14" height="20" rx="1" fill="#78350f" stroke="#6d28d9" stroke-width="2"/>
                    </svg>

                    <!-- DREWNIANA CHATA (Stage 1) -->
                    <svg id="svg-stage-1" class="house-svg w-4/5 h-4/5 transition-all duration-300 hidden" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Komin -->
                        <rect x="70" y="20" width="8" height="20" fill="#78350f" stroke="#451a03" stroke-width="2"/>
                        <!-- Ściany i logi -->
                        <rect x="22" y="45" width="56" height="40" rx="3" fill="#b45309" stroke="#451a03" stroke-width="3"/>
                        <line x1="22" y1="55" x2="78" y2="55" stroke="#451a03" stroke-width="2"/>
                        <line x1="22" y1="65" x2="78" y2="65" stroke="#451a03" stroke-width="2"/>
                        <line x1="22" y1="75" x2="78" y2="75" stroke="#451a03" stroke-width="2"/>
                        <!-- Dach -->
                        <polygon points="15,48 50,18 85,48" fill="#d97706" stroke="#451a03" stroke-width="3" stroke-linejoin="round"/>
                        <!-- Drzwi -->
                        <rect x="44" y="60" width="14" height="25" fill="#78350f" stroke="#451a03" stroke-width="2"/>
                        <circle cx="54" cy="72" r="1.5" fill="#fef08a"/>
                        <!-- Okna -->
                        <rect x="28" y="54" width="10" height="10" fill="#fef08a" stroke="#451a03" stroke-width="2"/>
                        <rect x="62" y="54" width="10" height="10" fill="#fef08a" stroke="#451a03" stroke-width="2"/>
                    </svg>

                    <!-- MUROWANY DOM (Stage 2) -->
                    <svg id="svg-stage-2" class="house-svg w-4/5 h-4/5 transition-all duration-300 hidden" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Ściany z cegły -->
                        <rect x="20" y="40" width="60" height="45" rx="2" fill="#ef4444" stroke="#991b1b" stroke-width="3"/>
                        <!-- Wzorek cegły (kilka kresek) -->
                        <line x1="20" y1="50" x2="80" y2="50" stroke="#b91c1c" stroke-width="1.5"/>
                        <line x1="20" y1="60" x2="80" y2="60" stroke="#b91c1c" stroke-width="1.5"/>
                        <line x1="20" y1="70" x2="80" y2="70" stroke="#b91c1c" stroke-width="1.5"/>
                        <line x1="30" y1="40" x2="30" y2="50" stroke="#b91c1c" stroke-width="1.5"/>
                        <line x1="50" y1="50" x2="50" y2="60" stroke="#b91c1c" stroke-width="1.5"/>
                        <line x1="70" y1="40" x2="70" y2="50" stroke="#b91c1c" stroke-width="1.5"/>
                        <line x1="40" y1="60" x2="40" y2="70" stroke="#b91c1c" stroke-width="1.5"/>
                        <!-- Komin -->
                        <rect x="28" y="15" width="10" height="20" fill="#991b1b" stroke="#7f1d1d" stroke-width="2.5"/>
                        <!-- Dach dachówkowy -->
                        <polygon points="12,42 50,12 88,42" fill="#7f1d1d" stroke="#451a03" stroke-width="3"/>
                        <!-- Solidne drzwi wejściowe -->
                        <rect x="42" y="55" width="16" height="30" fill="#3f3f46" stroke="#18181b" stroke-width="2"/>
                        <circle cx="54" cy="70" r="2" fill="#fbbf24"/>
                        <!-- Okna na piętrze -->
                        <rect x="28" y="46" width="10" height="12" fill="#38bdf8" stroke="#1e3a8a" stroke-width="2"/>
                        <rect x="62" y="46" width="10" height="12" fill="#38bdf8" stroke="#1e3a8a" stroke-width="2"/>
                    </svg>

                    <!-- NOWOCZESNA WILLA (Stage 3) -->
                    <svg id="svg-stage-3" class="house-svg w-4/5 h-4/5 transition-all duration-300 hidden" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Basen po boku -->
                        <rect x="10" y="70" width="22" height="12" rx="2" fill="#22d3ee" stroke="#0891b2" stroke-width="2"/>
                        <!-- Garaż i dół -->
                        <rect x="25" y="45" width="55" height="38" rx="2" fill="#e2e8f0" stroke="#475569" stroke-width="3"/>
                        <rect x="28" y="58" width="22" height="25" fill="#94a3b8" stroke="#475569" stroke-width="2"/>
                        <!-- Górny moduł geometryczny -->
                        <rect x="18" y="25" width="48" height="26" rx="1" fill="#1e293b" stroke="#0f172a" stroke-width="3"/>
                        <!-- Panoramiczne wielkie okna -->
                        <rect x="22" y="30" width="40" height="16" fill="#06b6d4" opacity="0.8" stroke="#0891b2" stroke-width="2"/>
                        <line x1="42" y1="30" x2="42" y2="46" stroke="#0891b2" stroke-width="1.5"/>
                        <!-- Szklane drzwi tarasowe na dole -->
                        <rect x="58" y="52" width="16" height="31" fill="#06b6d4" opacity="0.8" stroke="#0891b2" stroke-width="2"/>
                        <!-- Oświetlenie zewnętrzne LED -->
                        <circle cx="25" cy="54" r="2" fill="#fbbf24"/>
                        <circle cx="75" cy="54" r="2" fill="#fbbf24"/>
                    </svg>

                    <!-- APARTAMENTOWIEC (Stage 4) -->
                    <svg id="svg-stage-4" class="house-svg w-4/5 h-4/5 transition-all duration-300 hidden" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Wieża lewa (mniejsza) -->
                        <rect x="15" y="35" width="22" height="50" rx="3" fill="#1e1b4b" stroke="#4f46e5" stroke-width="2.5"/>
                        <rect x="20" y="42" width="4" height="6" fill="#fbbf24"/>
                        <rect x="28" y="42" width="4" height="6" fill="#fbbf24"/>
                        <rect x="20" y="54" width="4" height="6" fill="#38bdf8"/>
                        <rect x="28" y="54" width="4" height="6" fill="#fbbf24"/>
                        <rect x="20" y="66" width="4" height="6" fill="#fbbf24"/>
                        <rect x="28" y="66" width="4" height="6" fill="#38bdf8"/>
                        
                        <!-- Główny drapacz chmur -->
                        <rect x="42" y="15" width="40" height="70" rx="4" fill="#0f172a" stroke="#8b5cf6" stroke-width="3"/>
                        <!-- Szklany rdzeń -->
                        <rect x="50" y="22" width="24" height="50" fill="#312e81" stroke="#6366f1" stroke-width="1.5"/>
                        <!-- Siatka okien -->
                        <rect x="53" y="26" width="6" height="8" fill="#a78bfa" opacity="0.9"/>
                        <rect x="65" y="26" width="6" height="8" fill="#a78bfa" opacity="0.9"/>
                        <rect x="53" y="38" width="6" height="8" fill="#38bdf8" opacity="0.9"/>
                        <rect x="65" y="38" width="6" height="8" fill="#a78bfa" opacity="0.9"/>
                        <rect x="53" y="50" width="6" height="8" fill="#a78bfa" opacity="0.9"/>
                        <rect x="65" y="50" width="6" height="8" fill="#38bdf8" opacity="0.9"/>
                        <rect x="53" y="62" width="6" height="8" fill="#a78bfa" opacity="0.9"/>
                        <rect x="65" y="62" width="6" height="8" fill="#fbbf24" opacity="0.9"/>
                        
                        <!-- Lądowisko dla helikopterów na dachu -->
                        <line x1="45" y1="15" x2="79" y2="15" stroke="#f43f5e" stroke-width="3"/>
                        <path d="M57 15 L62 8 L67 15" stroke="#f43f5e" stroke-width="2"/>
                    </svg>

                    <!-- KOSMICZNA ARKADIA (Stage 5) -->
                    <svg id="svg-stage-5" class="house-svg w-4/5 h-4/5 transition-all duration-300 hidden" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Holograficzne okręgi ochronne / lewitacja -->
                        <circle cx="50" cy="50" r="42" stroke="#22d3ee" stroke-width="1.5" stroke-dasharray="6 4" opacity="0.5"/>
                        <circle cx="50" cy="50" r="35" stroke="#d946ef" stroke-width="1" stroke-dasharray="2 4" opacity="0.7"/>

                        <!-- Lewitujące wyspy fundamentowe -->
                        <path d="M20 72 L32 82 L68 82 L80 72 C80 72 70 78 50 78 C30 78 20 72 20 72 Z" fill="#1e293b" stroke="#06b6d4" stroke-width="2.5"/>

                        <!-- Gwiezdny Kryształ Energii (Centrum) -->
                        <polygon points="50,22 68,48 50,74 32,48" fill="#ec4899" opacity="0.8" stroke="#d946ef" stroke-width="2"/>
                        <!-- Bioluminescencyjny rdzeń -->
                        <circle cx="50" cy="48" r="8" fill="#ffffff" filter="drop-shadow(0 0 8px #f472b6)"/>

                        <!-- Wiszące luksusowe kapsuły mieszkalne -->
                        <rect x="22" y="42" width="14" height="14" rx="7" fill="#0f172a" stroke="#06b6d4" stroke-width="2"/>
                        <circle cx="29" cy="49" r="3" fill="#22d3ee"/>

                        <rect x="64" y="42" width="14" height="14" rx="7" fill="#0f172a" stroke="#06b6d4" stroke-width="2"/>
                        <circle cx="71" cy="49" r="3" fill="#22d3ee"/>

                        <!-- Wieża centralna -->
                        <line x1="50" y1="22" x2="50" y2="10" stroke="#d946ef" stroke-width="3" stroke-linecap="round"/>
                        <circle cx="50" cy="8" r="2.5" fill="#ffffff"/>
                    </svg>

                </div>
            </div>

            <!-- Dolna sekcja: Nazwa domku i cel do ewolucji -->
            <div class="w-full z-10 text-center">
                <span id="evolution-badge" class="text-xs font-bold text-violet-300 bg-violet-950/80 border border-violet-800/60 px-4 py-1.5 rounded-full tracking-wide">
                    ETAP 1: Szałas z Kartonu
                </span>
                
                <p id="evolution-desc" class="text-xs text-slate-400 mt-3 max-w-sm mx-auto leading-relaxed h-10">
                    Zaczynasz od skromnego schronienia z tektury. Klikaj, aby zarobić na coś lepszego!
                </p>

                <!-- Pasek postępu do kolejnej ewolucji -->
                <div id="progress-container" class="w-full mt-4 bg-slate-950/80 p-1.5 rounded-2xl border border-slate-800">
                    <div class="flex justify-between text-[11px] font-bold text-slate-400 px-2 mb-1.5">
                        <span class="uppercase tracking-wider">Postęp Ewolucyjny</span>
                        <span id="progress-text">0 / 150 $</span>
                    </div>
                    <div class="w-full bg-slate-900 h-3.5 rounded-full overflow-hidden p-[2px]">
                        <div id="progress-bar" class="h-full bg-gradient-to-r from-violet-500 via-fuchsia-500 to-pink-500 rounded-full transition-all duration-300" style="width: 0%"></div>
                    </div>
                </div>
            </div>

        </div>

        <!-- PANEL PRAWY: SKLEP Z ULEPSZENIAMI -->
        <div class="lg:col-span-5 flex flex-col gap-4">
            
            <!-- Nagłówek sklepu -->
            <div class="bg-slate-900/60 border border-slate-800/80 backdrop-blur-md rounded-2xl p-4 flex justify-between items-center shadow-lg">
                <div class="flex items-center gap-2">
                    <span class="text-2xl">🏗️</span>
                    <div>
                        <h2 class="heading-font font-bold text-lg text-slate-100">BIURO INWESTYCJI</h2>
                        <p class="text-[11px] text-slate-400">Przyspiesz rozwój i automatyzację</p>
                    </div>
                </div>
                <div class="text-right">
                    <span class="text-xs text-slate-400 block">Zysk na klik</span>
                    <span id="dpc-display-right" class="text-sm font-black text-amber-400">+$1</span>
                </div>
            </div>

            <!-- Lista ulepszeń -->
            <div class="flex flex-col gap-3 max-h-[480px] lg:max-h-[580px] overflow-y-auto pr-1">
                
                <!-- ULEPSZENIE: KLIK (Moc kliknięcia) -->
                <button onclick="buyUpgrade('clickPower')" id="upgrade-clickPower" class="group text-left bg-slate-900/50 hover:bg-slate-900 border border-slate-800 hover:border-violet-500/40 rounded-2xl p-3.5 transition duration-200 flex items-center justify-between shadow-md relative overflow-hidden">
                    <div class="flex items-center gap-3 z-10">
                        <div class="w-12 h-12 rounded-xl bg-violet-600/10 border border-violet-500/30 flex items-center justify-center text-xl group-hover:scale-105 transition duration-200">
                            ⚡
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-slate-200 group-hover:text-white transition">Silny Palec</h3>
                            <p class="text-[11px] text-slate-400 mt-0.5">Zwiększa kasę za kliknięcie o +1</p>
                            <span class="text-[10px] font-bold text-violet-400 bg-violet-950/60 border border-violet-900/40 px-2 py-0.5 rounded-full mt-1.5 inline-block">
                                Poziom: <span id="lvl-clickPower">0</span>
                            </span>
                        </div>
                    </div>
                    <div class="text-right z-10">
                        <span id="cost-clickPower" class="font-extrabold text-sm text-emerald-400 block">$10</span>
                        <span class="text-[10px] text-slate-500 block uppercase font-bold tracking-wider mt-1">Kup</span>
                    </div>
                </button>

                <!-- ULEPSZENIE: BUDOWLANIEC (Passive) -->
                <button onclick="buyUpgrade('worker')" id="upgrade-worker" class="group text-left bg-slate-900/50 hover:bg-slate-900 border border-slate-800 hover:border-violet-500/40 rounded-2xl p-3.5 transition duration-200 flex items-center justify-between shadow-md relative overflow-hidden">
                    <div class="flex items-center gap-3 z-10">
                        <div class="w-12 h-12 rounded-xl bg-violet-600/10 border border-violet-500/30 flex items-center justify-center text-xl group-hover:scale-105 transition duration-200">
                            👷‍♂️
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-slate-200 group-hover:text-white transition">Zatrudnij Robotnika</h3>
                            <p class="text-[11px] text-slate-400 mt-0.5">Buduje powoli bez Twojego udziału. (+1 $/s)</p>
                            <span class="text-[10px] font-bold text-violet-400 bg-violet-950/60 border border-violet-900/40 px-2 py-0.5 rounded-full mt-1.5 inline-block">
                                Zatrudniono: <span id="lvl-worker">0</span>
                            </span>
                        </div>
                    </div>
                    <div class="text-right z-10">
                        <span id="cost-worker" class="font-extrabold text-sm text-emerald-400 block">$50</span>
                        <span class="text-[10px] text-slate-500 block uppercase font-bold tracking-wider mt-1">Wynajmij</span>
                    </div>
                </button>

                <!-- ULEPSZENIE: BETONIARKA (Passive) -->
                <button onclick="buyUpgrade('mixer')" id="upgrade-mixer" class="group text-left bg-slate-900/50 hover:bg-slate-900 border border-slate-800 hover:border-violet-500/40 rounded-2xl p-3.5 transition duration-200 flex items-center justify-between shadow-md relative overflow-hidden">
                    <div class="flex items-center gap-3 z-10">
                        <div class="w-12 h-12 rounded-xl bg-violet-600/10 border border-violet-500/30 flex items-center justify-center text-xl group-hover:scale-105 transition duration-200">
                            🔄
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-slate-200 group-hover:text-white transition">Wypożycz Betoniarkę</h3>
                            <p class="text-[11px] text-slate-400 mt-0.5">Przyspiesza kładzenie fundamentów. (+8 $/s)</p>
                            <span class="text-[10px] font-bold text-violet-400 bg-violet-950/60 border border-violet-900/40 px-2 py-0.5 rounded-full mt-1.5 inline-block">
                                Poziom: <span id="lvl-mixer">0</span>
                            </span>
                        </div>
                    </div>
                    <div class="text-right z-10">
                        <span id="cost-mixer" class="font-extrabold text-sm text-emerald-400 block">$250</span>
                        <span class="text-[10px] text-slate-500 block uppercase font-bold tracking-wider mt-1">Kup</span>
                    </div>
                </button>

                <!-- ULEPSZENIE: DŹWIG (Passive) -->
                <button onclick="buyUpgrade('crane')" id="upgrade-crane" class="group text-left bg-slate-900/50 hover:bg-slate-900 border border-slate-800 hover:border-violet-500/40 rounded-2xl p-3.5 transition duration-200 flex items-center justify-between shadow-md relative overflow-hidden">
                    <div class="flex items-center gap-3 z-10">
                        <div class="w-12 h-12 rounded-xl bg-violet-600/10 border border-violet-500/30 flex items-center justify-center text-xl group-hover:scale-105 transition duration-200">
                            🏗️
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-slate-200 group-hover:text-white transition">Dźwig Hydrauliczny</h3>
                            <p class="text-[11px] text-slate-400 mt-0.5">Automatyczna konstrukcja pięter. (+40 $/s)</p>
                            <span class="text-[10px] font-bold text-violet-400 bg-violet-950/60 border border-violet-900/40 px-2 py-0.5 rounded-full mt-1.5 inline-block">
                                Poziom: <span id="lvl-crane">0</span>
                            </span>
                        </div>
                    </div>
                    <div class="text-right z-10">
                        <span id="cost-crane" class="font-extrabold text-sm text-emerald-400 block">$1,200</span>
                        <span class="text-[10px] text-slate-500 block uppercase font-bold tracking-wider mt-1">Kup</span>
                    </div>
                </button>

                <!-- ULEPSZENIE: BIURO DEWELOPERA (Passive) -->
                <button onclick="buyUpgrade('developer')" id="upgrade-developer" class="group text-left bg-slate-900/50 hover:bg-slate-900 border border-slate-800 hover:border-violet-500/40 rounded-2xl p-3.5 transition duration-200 flex items-center justify-between shadow-md relative overflow-hidden">
                    <div class="flex items-center gap-3 z-10">
                        <div class="w-12 h-12 rounded-xl bg-violet-600/10 border border-violet-500/30 flex items-center justify-center text-xl group-hover:scale-105 transition duration-200">
                            🏢
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-slate-200 group-hover:text-white transition">Biuro Deweloperskie</h3>
                            <p class="text-[11px] text-slate-400 mt-0.5">Zarządza projektami w całym mieście. (+200 $/s)</p>
                            <span class="text-[10px] font-bold text-violet-400 bg-violet-950/60 border border-violet-900/40 px-2 py-0.5 rounded-full mt-1.5 inline-block">
                                Biura: <span id="lvl-developer">0</span>
                            </span>
                        </div>
                    </div>
                    <div class="text-right z-10">
                        <span id="cost-developer" class="font-extrabold text-sm text-emerald-400 block">$6,000</span>
                        <span class="text-[10px] text-slate-500 block uppercase font-bold tracking-wider mt-1">Kup</span>
                    </div>
                </button>

                <!-- ULEPSZENIE: SYNTEZATOR MATERII (Passive) -->
                <button onclick="buyUpgrade('synthesizer')" id="upgrade-synthesizer" class="group text-left bg-slate-900/50 hover:bg-slate-900 border border-slate-800 hover:border-violet-500/40 rounded-2xl p-3.5 transition duration-200 flex items-center justify-between shadow-md relative overflow-hidden">
                    <div class="flex items-center gap-3 z-10">
                        <div class="w-12 h-12 rounded-xl bg-violet-600/10 border border-violet-500/30 flex items-center justify-center text-xl group-hover:scale-105 transition duration-200">
                            ⚛️
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-slate-200 group-hover:text-white transition">Syntezator Kwantowy</h3>
                            <p class="text-[11px] text-slate-400 mt-0.5">Tworzy nano-ściany z czystej energii. (+1,000 $/s)</p>
                            <span class="text-[10px] font-bold text-violet-400 bg-violet-950/60 border border-violet-900/40 px-2 py-0.5 rounded-full mt-1.5 inline-block">
                                Poziom: <span id="lvl-synthesizer">0</span>
                            </span>
                        </div>
                    </div>
                    <div class="text-right z-10">
                        <span id="cost-synthesizer" class="font-extrabold text-sm text-emerald-400 block">$30,000</span>
                        <span class="text-[10px] text-slate-500 block uppercase font-bold tracking-wider mt-1">Kup</span>
                    </div>
                </button>

            </div>
        </div>

    </div>

    <!-- PANEL STATYSTYK DOLNY -->
    <div class="w-full max-w-5xl mt-6 p-4 bg-slate-900/30 border border-slate-800/60 rounded-2xl flex flex-wrap gap-4 items-center justify-around text-center text-xs text-slate-400">
        <div>
            <span class="block text-[10px] uppercase tracking-wider text-slate-500">Suma Kliknięć</span>
            <span id="stat-clicks" class="font-bold text-slate-200 text-sm">0</span>
        </div>
        <div class="h-6 w-[1px] bg-slate-800 hidden sm:block"></div>
        <div>
            <span class="block text-[10px] uppercase tracking-wider text-slate-500">Całkowity Zarobek</span>
            <span id="stat-total-earned" class="font-bold text-slate-200 text-sm">$0</span>
        </div>
        <div class="h-6 w-[1px] bg-slate-800 hidden sm:block"></div>
        <div>
            <span class="block text-[10px] uppercase tracking-wider text-slate-500">Czas Rozgrywki</span>
            <span id="stat-time" class="font-bold text-slate-200 text-sm">0s</span>
        </div>
    </div>

    <!-- SKRYPT INTEGRUJĄCY ROZGRYWKĘ -->
    <script>
        // --- PROFIL AUDIO (Web Audio API) ---
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        let audioEnabled = true;

        function playSound(type) {
            if (!audioEnabled) return;
            if (audioCtx.state === 'suspended') {
                audioCtx.resume();
            }
            try {
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                const now = audioCtx.currentTime;

                if (type === 'click') {
                    // Przyjemny, czysty dźwięk pop
                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(300, now);
                    osc.frequency.exponentialRampToValueAtTime(600, now + 0.08);
                    gain.gain.setValueAtTime(0.15, now);
                    gain.gain.linearRampToValueAtTime(0.001, now + 0.08);
                    osc.start(now);
                    osc.stop(now + 0.08);
                } else if (type === 'upgrade') {
                    // Arpeggio wznoszące (sukces)
                    osc.type = 'triangle';
                    osc.frequency.setValueAtTime(523.25, now); // C5
                    osc.frequency.setValueAtTime(659.25, now + 0.08); // E5
                    osc.frequency.setValueAtTime(783.99, now + 0.16); // G5
                    gain.gain.setValueAtTime(0.12, now);
                    gain.gain.linearRampToValueAtTime(0.001, now + 0.3);
                    osc.start(now);
                    osc.stop(now + 0.3);
                } else if (type === 'evolution') {
                    // Fanfara ewolucji
                    osc.type = 'sawtooth';
                    osc.frequency.setValueAtTime(261.63, now); // C4
                    osc.frequency.exponentialRampToValueAtTime(523.25, now + 0.15); // C5
                    osc.frequency.setValueAtTime(659.25, now + 0.2); // E5
                    osc.frequency.setValueAtTime(1046.5, now + 0.35); // C6
                    gain.gain.setValueAtTime(0.15, now);
                    gain.gain.linearRampToValueAtTime(0.001, now + 0.6);
                    osc.start(now);
                    osc.stop(now + 0.6);
                }
            } catch (e) {
                console.log("Audio API blocked or not supported yet");
            }
        }

        // --- STANY GRY (LOGIKA) ---
        let state = {
            money: 0,
            totalEarned: 0,
            clicks: 0,
            dps: 0,
            dpc: 1,
            evolutionStage: 0,
            timePlayed: 0,
            upgrades: {
                clickPower: { count: 0, cost: 10, costMultiplier: 1.4, dpcAdd: 1, dpsAdd: 0 },
                worker: { count: 0, cost: 50, costMultiplier: 1.15, dpcAdd: 0, dpsAdd: 1 },
                mixer: { count: 0, cost: 250, costMultiplier: 1.15, dpcAdd: 0, dpsAdd: 8 },
                crane: { count: 0, cost: 1200, costMultiplier: 1.15, dpcAdd: 0, dpsAdd: 40 },
                developer: { count: 0, cost: 6000, costMultiplier: 1.15, dpcAdd: 0, dpsAdd: 200 },
                synthesizer: { count: 0, cost: 30000, costMultiplier: 1.15, dpcAdd: 0, dpsAdd: 1000 }
            }
        };

        // Definicje ewolucji domków
        const evolutions = [
            { name: "Etap 1: Szałas z Kartonu", minMoney: 0, desc: "Zaczynasz od skromnego schronienia z tektury. Klikaj, aby zarobić na coś lepszego!" },
            { name: "Etap 2: Drewniana Chata", minMoney: 150, desc: "Solidniejsze, pachnące drewnem cztery ściany. Idealne schronienie w lesie." },
            { name: "Etap 3: Murowany Domek", minMoney: 1000, desc: "Klasyczna cegła, szczelny dach i przytulny kominek. Nic tego nie zdmuchnie!" },
            { name: "Etap 4: Nowoczesna Willa", minMoney: 8000, desc: "Minimalizm, wielkie przeszklenia i basen na tarasie. Luksus pełną gębą." },
            { name: "Etap 5: Apartamentowiec", minMoney: 50000, desc: "Wielopiętrowy kolos ze szkła i stali dominujący nad całym miastem." },
            { name: "Etap 6: Kosmiczna Arkadia", minMoney: 250000, desc: "Arcydzieło futurystycznej architektury lewitujące nad ziemią." }
        ];

        // Formatowanie pieniędzy
        function formatMoney(amount) {
            if (amount < 1000) {
                return "$" + Math.floor(amount);
            } else if (amount < 1000000) {
                return "$" + (amount / 1000).toFixed(1) + "k";
            } else {
                return "$" + (amount / 1000000).toFixed(2) + "M";
            }
        }

        // --- AKTUALIZACJA INTERFEJSU (UI) ---
        function updateUI() {
            // Waluty
            document.getElementById('money-display').innerText = formatMoney(state.money);
            document.getElementById('dps-display').innerHTML = `Przychód pasywny: <span class="text-emerald-400 font-bold">+${formatMoney(state.dps)} / sek</span>`;
            document.getElementById('dpc-display-right').innerText = `+$${state.dpc}`;

            // Statystyki na dole
            document.getElementById('stat-clicks').innerText = state.clicks;
            document.getElementById('stat-total-earned').innerText = formatMoney(state.totalEarned);
            
            // Format czasu gry
            let sec = state.timePlayed;
            if (sec < 60) {
                document.getElementById('stat-time').innerText = `${sec}s`;
            } else {
                let min = Math.floor(sec / 60);
                let remainingSec = sec % 60;
                document.getElementById('stat-time').innerText = `${min}m ${remainingSec}s`;
            }

            // Aktualizacja sklepu (koszty, poziomy, blokady)
            for (let key in state.upgrades) {
                const up = state.upgrades[key];
                document.getElementById(`lvl-${key}`).innerText = up.count;
                document.getElementById(`cost-${key}`).innerText = formatMoney(up.cost);

                const element = document.getElementById(`upgrade-${key}`);
                if (state.money >= up.cost) {
                    element.classList.remove('opacity-50', 'cursor-not-allowed');
                    element.classList.add('hover:scale-[1.01]', 'hover:bg-slate-900');
                } else {
                    element.classList.add('opacity-50', 'cursor-not-allowed');
                    element.classList.remove('hover:scale-[1.01]', 'hover:bg-slate-900');
                }
            }

            // Aktualizacja postępu ewolucyjnego
            updateEvolutionProgress();
        }

        // Logika obliczania i prezentacji postępu ewolucji
        function updateEvolutionProgress() {
            let currentStage = state.evolutionStage;
            let nextStage = currentStage + 1;

            if (nextStage >= evolutions.length) {
                // Osiągnięto maksymalną ewolucję
                document.getElementById('progress-text').innerText = "MAKSYMALNA EWOLUCJA!";
                document.getElementById('progress-bar').style.width = "100%";
                return;
            }

            let currentThreshold = evolutions[currentStage].minMoney;
            let nextThreshold = evolutions[nextStage].minMoney;

            // Ile kasy zebraliśmy ponad obecny próg, a ile brakuje do następnego
            let progressEarned = state.totalEarned - currentThreshold;
            let progressRequired = nextThreshold - currentThreshold;

            let percentage = Math.max(0, Math.min(100, (progressEarned / progressRequired) * 100));

            document.getElementById('progress-text').innerText = `${formatMoney(state.totalEarned)} / ${formatMoney(nextThreshold)}`;
            document.getElementById('progress-bar').style.width = `${percentage}%`;

            // Sprawdzenie, czy następuje awans ewolucyjny
            if (state.totalEarned >= nextThreshold) {
                state.evolutionStage = nextStage;
                triggerEvolution(nextStage);
            }
        }

        // Zmiana wyglądu domu w zależności od poziomu ewolucji
        function triggerEvolution(stageId) {
            playSound('evolution');

            // Ukryj wszystkie SVG
            const svgs = document.querySelectorAll('.house-svg');
            svgs.forEach(svg => svg.classList.add('hidden'));

            // Pokaż właściwe SVG
            const targetSvg = document.getElementById(`svg-stage-${stageId}`);
            if (targetSvg) {
                targetSvg.classList.remove('hidden');
                
                // Efektowne wejście (dodaj na chwilę klasę animacji)
                targetSvg.classList.add('scale-110');
                setTimeout(() => {
                    targetSvg.classList.remove('scale-110');
                }, 300);
            }

            // Zmień teksty
            document.getElementById('evolution-badge').innerText = evolutions[stageId].name;
            document.getElementById('evolution-desc').innerText = evolutions[stageId].desc;
        }

        // --- OBSŁUGA KLIKANIA DOMU ---
        const clickArea = document.getElementById('house-click-area');

        clickArea.addEventListener('pointerdown', (e) => {
            e.preventDefault();
            
            // Zwiększ stan konta
            state.money += state.dpc;
            state.totalEarned += state.dpc;
            state.clicks++;

            playSound('click');

            // Wyświetlenie latających liczb (cząsteczek)
            createClickParticle(e.clientX, e.clientY, `+$${state.dpc}`);

            // Natychmiastowe odświeżenie UI
            updateUI();
        });

        // Tworzenie dynamicznych cząsteczek z tekstem +$X
        function createClickParticle(x, y, text) {
            const particle = document.createElement('div');
            particle.className = 'click-particle font-black text-2xl heading-font text-emerald-400 select-none pointer-events-none drop-shadow-[0_2px_8px_rgba(16,185,129,0.5)]';
            particle.innerText = text;

            // Pozycjonowanie cząsteczki
            // Sprawdzamy czy współrzędne są poprawne (w przypadku sterowania dotykowego)
            if (x && y) {
                particle.style.left = `${x - 20}px`;
                particle.style.top = `${y - 20}px`;
            } else {
                // Fallback na środek ekranu domku
                const rect = clickArea.getBoundingClientRect();
                particle.style.left = `${rect.left + rect.width / 2 + (Math.random() - 0.5) * 50}px`;
                particle.style.top = `${rect.top + rect.height / 2}px`;
            }

            document.body.appendChild(particle);

            // Usunięcie cząsteczki po zakończeniu animacji
            setTimeout(() => {
                particle.remove();
            }, 800);
        }

        // --- OBSŁUGA SKLEPU ---
        function buyUpgrade(key) {
            const up = state.upgrades[key];
            if (state.money >= up.cost) {
                // Zapłać
                state.money -= up.cost;
                up.count++;

                // Zwiększ koszty
                up.cost = Math.floor(up.cost * up.costMultiplier);

                // Zastosuj ulepszenie
                if (up.dpcAdd > 0) {
                    state.dpc += up.dpcAdd;
                }
                
                // Przelicz DPS (zarobek na sekundę)
                recalculateDPS();

                playSound('upgrade');
                updateUI();
            }
        }

        function recalculateDPS() {
            let totalDps = 0;
            for (let key in state.upgrades) {
                totalDps += state.upgrades[key].count * state.upgrades[key].dpsAdd;
            }
            state.dps = totalDps;
        }

        // --- GŁÓWNA PĘTLA CZASOWA ---
        // Co 100ms dodajemy 1/10 przychodu pasywnego DPS
        setInterval(() => {
            if (state.dps > 0) {
                const increment = state.dps / 10;
                state.money += increment;
                state.totalEarned += increment;
                updateUI();
            }
        }, 100);

        // Licznik czasu gry (co 1 sekunda)
        setInterval(() => {
            state.timePlayed++;
            updateUI();
        }, 1000);

        // --- PRZYCISK AUDIO ---
        document.getElementById('btn-audio-toggle').addEventListener('click', () => {
            audioEnabled = !audioEnabled;
            const btn = document.getElementById('btn-audio-toggle');
            if (audioEnabled) {
                btn.innerText = "🔊 Dźwięki Wł.";
                btn.classList.remove('bg-red-950', 'border-red-800');
                btn.classList.add('bg-slate-800', 'border-slate-700/50');
            } else {
                btn.innerText = "🔇 Wyciszono";
                btn.classList.add('bg-red-950', 'border-red-800');
                btn.classList.remove('bg-slate-800', 'border-slate-700/50');
            }
        });

        // Pierwsza inicjalizacja interfejsu
        updateUI();
    </script>
</body>
</html>

```

