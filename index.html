<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Алматы облысының киелі жерлері</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        .modal { transition: opacity 0.25s ease; }
        body.modal-active { overflow: hidden; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans min-h-screen flex flex-col">

    <!-- Header -->
    <header class="bg-emerald-800 text-white shadow-lg sticky top-0 z-40">
        <div class="max-w-5xl mx-auto px-4 py-4 flex flex-col sm:flex-row justify-between items-center gap-2">
            <h1 class="text-xl sm:text-2xl font-bold tracking-wide text-center sm:text-left">
                <i class="fa-solid fa-monument mr-2 text-amber-400"></i>
                Алматы облысының киелі жерлері
            </h1>
            <span class="text-xs bg-emerald-700 text-emerald-100 px-3 py-1 rounded-full border border-emerald-600">
                QR-Энциклопедия
            </span>
        </div>
    </header>

    <!-- Main Content -->
    <main class="flex-grow max-w-5xl mx-auto px-4 py-6 w-full">
        <div class="bg-amber-50 border-l-4 border-amber-500 p-4 mb-6 rounded shadow-sm">
            <p class="text-sm text-amber-900">
                <strong>Нұсқаулық:</strong> Объект туралы толық ақпаратты, орналасқан жерін және картасын көру үшін кез келген карточканы басыңыз.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6" id="cards-container">
            <!-- Cards will be populated by JS -->
        </div>
    </main>

    <!-- Modal -->
    <div id="modal" class="modal opacity-0 pointer-events-none fixed inset-0 z-50 flex items-center justify-center p-4 bg-black/60 backdrop-blur-sm">
        <div class="bg-white rounded-2xl shadow-2xl max-w-lg w-full max-h-[90vh] overflow-y-auto transform transition-all p-6 relative">
            <button onclick="closeModal()" class="absolute top-4 right-4 text-slate-400 hover:text-slate-600 bg-slate-100 rounded-full w-8 h-8 flex items-center justify-center text-lg font-bold">
                ✕
            </button>
            <div id="modal-content"></div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-slate-800 text-slate-400 text-center py-4 text-sm mt-8">
        <p>© Алматы облысындағы киелі жерлердің QR-энциклопедиясы</p>
    </footer>

    <script>
        const sites = {
            1: {
                title: "Танбалы (Тамғалы) петроглифтері",
                location: "Жамбыл ауданы, Алматы облысы",
                period: "Қола дәуірінен б.з. б. ХІІІ–ХІІ ғғ.",
                desc: "Танбалы археологиялық ландшафты – Орталық Азиядағы жартас өнерінің ең танымал және зерттелген ескерткіштерінің бірі.",
                significance: "ЮНЕСКО-ның Дүниежүзілік мұралар тізіміне енгізілген.",
                mapUrl: "https://maps.google.com/?q=Tanbaly+Petroglyphs"
            },
            2: {
                title: "Тамғалы тас",
                location: "Іле өзенінің шатқалы",
                period: "Орта ғасырлар / Көне буддалық жазбалар",
                desc: "Іле өзені маңындағы жартастардағы Будда бейнелері мен тибет жазулары бар бірегей ескерткіш.",
                significance: "Өңірдің мәдени басылымдары мен тарихи тоғысының белгісі.",
                mapUrl: "https://maps.google.com/?q=Tamgaly+Tas"
            },
            3: {
                title: "Талғар (Талхир) қалашығы",
                location: "Талғар қаласының оңтүстік-шығыс шеті",
                period: "Орта ғасырлар (ХІІ-ХІІІ ғғ.)",
                desc: "Ортағасырлық Талхир қалашығы – Ұлы Жібек жолы бойындағы ірі сауда және қолөнер орталығы болған.",
                significance: "Ұлы Жібек жолы ескерткіші ретінде ЮНЕСКО тізімінде.",
                mapUrl: "https://maps.google.com/?q=Talhiz"
            },
            4: {
                title: "Бесшатыр қорымы",
                location: "«Алтынемел» ұлттық паркі",
                period: "Сақ дәуірі, ерте темір дәуірі",
                desc: "Іле өзенінің оң жағалауында орналасқан сақ патшаларының алып обалары топтасқан кешен.",
                significance: "Сақ қоғамының мәдениеті мен сәулет өнерінің куәсі.",
                mapUrl: "https://maps.google.com/?q=Besshatyr"
            },
            5: {
                title: "Жамбыл Жабаев кесенесі",
                location: "Жамбыл ауылы, Жамбыл ауданы",
                period: "ХХ ғасыр",
                desc: "Ұлы ақын Жамбыл Жабаевтың мәңгілік мекені, саябақ пен мұражай кешені.",
                significance: "Қазақ әдебиеті мен руханиятының киелі орталығы.",
                mapUrl: "https://maps.google.com/?q=Zhambyl+Zhabayev+Museum"
            },
            6: {
                title: "Қарамерген қалашығы",
                location: "Балқаш ауданы",
                period: "IX–XIII ғғ.",
                desc: "Іле дельтасындағы ең ірі ортағасырлық қала. Суармалы егіншілік пен сауда орталығы болған.",
                significance: "Жетісудың көне қалалық мәдениетінің бірегей ескерткіші.",
                mapUrl: "https://maps.google.com/?q=Karamergen"
            }
        };

        function renderCards() {
            const container = document.getElementById('cards-container');
            container.innerHTML = '';
            
            Object.keys(sites).forEach(id => {
                const site = sites[id];
                const card = document.createElement('div');
                card.className = "bg-white rounded-xl shadow-md hover:shadow-xl transition duration-300 p-5 cursor-pointer border border-slate-100 flex flex-col justify-between hover:-translate-y-1";
                card.onclick = () => openModal(id);
                card.innerHTML = `
                    <div>
                        <span class="text-xs font-semibold px-2.5 py-0.5 rounded bg-emerald-100 text-emerald-800 mb-2 inline-block">
                            Объект #${id}
                        </span>
                        <h3 class="text-lg font-bold text-slate-800 mb-2">${site.title}</h3>
                        <p class="text-xs text-slate-500 mb-2"><i class="fa-solid fa-location-dot mr-1 text-emerald-600"></i> ${site.location}</p>
                        <p class="text-sm text-slate-600 line-clamp-2">${site.desc}</p>
                    </div>
                    <button class="mt-4 w-full bg-emerald-600 hover:bg-emerald-700 text-white font-medium py-2 px-4 rounded-lg text-sm transition">
                        Толығырақ
                    </button>
                `;
                container.appendChild(card);
            });
        }

        function openModal(id) {
            const site = sites[id];
            const content = document.getElementById('modal-content');
            content.innerHTML = `
                <span class="text-xs font-semibold px-2.5 py-0.5 rounded bg-emerald-100 text-emerald-800 mb-2 inline-block">
                    ${site.period}
                </span>
                <h2 class="text-2xl font-bold text-slate-800 mb-2">${site.title}</h2>
                <p class="text-sm text-slate-500 mb-4"><i class="fa-solid fa-location-dot mr-1 text-emerald-600"></i> ${site.location}</p>
                <div class="space-y-3 text-slate-700 text-sm mb-6">
                    <p><strong>Сипаттамасы:</strong> ${site.desc}</p>
                    <p><strong>Маңызы:</strong> ${site.significance}</p>
                </div>
                <a href="${site.mapUrl}" target="_blank" class="block text-center w-full bg-amber-500 hover:bg-amber-600 text-white font-bold py-3 px-4 rounded-xl shadow transition">
                    <i class="fa-solid fa-map-location-dot mr-2"></i> Картадан қарау
                </a>
            `;
            
            const modal = document.getElementById('modal');
            modal.classList.remove('opacity-0', 'pointer-events-none');
            document.body.classList.add('modal-active');
        }

        function closeModal() {
            const modal = document.getElementById('modal');
            modal.classList.add('opacity-0', 'pointer-events-none');
            document.body.classList.remove('modal-active');
        }

        document.getElementById('modal').addEventListener('click', function(e) {
            if (e.target === this) closeModal();
        });

        // Initialize cards on load
        window.onload = renderCards;
    </script>
</body>
</html>
