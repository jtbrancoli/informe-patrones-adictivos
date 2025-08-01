<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informe Interactivo: Patrones Adictivos y Derechos Digitales</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Chosen Palette: Calm Neutral Harmony -->
    <!-- Application Structure Plan: A thematic, single-page scrolling structure is used to create a narrative flow. It starts with a Hero Section to grab attention, followed by an interactive "Pattern Explorer" using a tabbed layout to make the taxonomy digestible. An "Impact Visualization" section uses a Chart.js radar chart and interactive cards to explain the violations of data rights in a more engaging way than a simple list. It concludes with the specific context for Chile and a call to action. This structure prioritizes user exploration and understanding over a rigid report format. -->
    <!-- Visualization & Content Choices: 1. Taxonomy of Patterns: Presented as an interactive tabbed section (HTML/CSS/JS) to allow users to explore each category without being overwhelmed. Goal: Organize & Inform. 2. Data Rights Implications: Visualized with a Chart.js radar chart to compare the risk profile (Data Intensity vs. Harm Potential) of the four main pattern categories. This is paired with interactive cards for each violated principle. Goal: Inform & Compare. 3. All icons and visual elements are created with Unicode characters and Tailwind CSS. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F7F4;
            color: #3D405B;
        }
        .nav-link {
            transition: color 0.3s ease, border-bottom-color 0.3s ease;
            border-bottom: 2px solid transparent;
        }
        .nav-link:hover {
            color: #E07A5F;
            border-bottom-color: #E07A5F;
        }
        .tab-button.active {
            background-color: #E07A5F;
            color: #FFFFFF;
        }
        .tab-button {
            transition: all 0.3s ease;
        }
        .content-card {
            background-color: rgba(255, 255, 255, 0.7);
            border: 1px solid #e2e8f0;
            backdrop-filter: blur(5px);
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
    </style>
</head>
<body class="antialiased">

    <header class="bg-[#F8F7F4]/80 backdrop-blur-sm sticky top-0 z-50 shadow-sm">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold text-[#3D405B]">Observatorio Ciudadan@ Digital</a>
            <div class="hidden md:flex space-x-8">
                <a href="#patterns" class="nav-link font-semibold">Los Patrones</a>
                <a href="#impact" class="nav-link font-semibold">El Impacto</a>
                <a href="#chile" class="nav-link font-semibold">Contexto Chile</a>
            </div>
            <button id="mobile-menu-button" class="md:hidden text-2xl">☰</button>
        </nav>
        <div id="mobile-menu" class="hidden md:hidden bg-[#F8F7F4] py-4">
            <a href="#patterns" class="block text-center py-2 px-4 text-sm font-semibold">Los Patrones</a>
            <a href="#impact" class="block text-center py-2 px-4 text-sm font-semibold">El Impacto</a>
            <a href="#chile" class="block text-center py-2 px-4 text-sm font-semibold">Contexto Chile</a>
        </div>
    </header>

    <main>
        <section id="hero" class="py-20 md:py-32">
            <div class="container mx-auto px-6 text-center">
                <h1 class="text-4xl md:text-6xl font-bold text-[#3D405B] mb-4">Diseñados para Enganchar</h1>
                <p class="text-lg md:text-xl max-w-3xl mx-auto text-[#3D405B]/80 mb-8">
                    Un análisis interactivo sobre cómo las plataformas digitales usan "patrones adictivos" para captar tu atención, recolectar tus datos y los riesgos que esto implica para tus derechos.
                </p>
                <a href="#patterns" class="bg-[#E07A5F] text-white font-bold py-3 px-8 rounded-full hover:bg-[#d46a50] transition-colors duration-300">
                    Explorar los Patrones
                </a>
            </div>
        </section>

        <section id="patterns" class="py-16 bg-[#f0efe9]">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-[#3D405B]">Las 4 Tácticas de Manipulación</h2>
                    <p class="mt-4 max-w-2xl mx-auto text-lg text-[#3D405B]/80">
                        El informe de la AEPD clasifica los patrones adictivos en cuatro grandes estrategias. Haz clic en cada una para descubrir cómo te afectan directamente.
                    </p>
                </div>

                <div id="tabs-container" class="max-w-4xl mx-auto">
                    <div class="flex flex-wrap justify-center gap-2 md:gap-4 mb-8">
                        <button data-tab="tab1" class="tab-button active text-sm md:text-base font-semibold py-2 px-4 rounded-full bg-white shadow">
                            <span class="mr-2"> coercion </span> Acción Forzada
                        </button>
                        <button data-tab="tab2" class="tab-button text-sm md:text-base font-semibold py-2 px-4 rounded-full bg-white shadow">
                            <span class="mr-2"> 👥 </span> Ingeniería Social
                        </button>
                        <button data-tab="tab3" class="tab-button text-sm md:text-base font-semibold py-2 px-4 rounded-full bg-white shadow">
                            <span class="mr-2"> 🎨 </span> Interferencia en Interfaz
                        </button>
                        <button data-tab="tab4" class="tab-button text-sm md:text-base font-semibold py-2 px-4 rounded-full bg-white shadow">
                            <span class="mr-2"> 🔄 </span> Persistencia
                        </button>
                    </div>

                    <div id="tabs-content" class="mt-8">
                        <div id="tab1" class="tab-content">
                            <div class="content-card p-6 md:p-8 rounded-lg shadow-lg">
                                <h3 class="text-2xl font-bold mb-4 text-[#3D405B]">Acción Forzada</h3>
                                <p class="mb-6 text-[#3D405B]/90">Te presionan o engañan para que realices acciones que no tenías intención de hacer, a cambio de algo que deseas. El objetivo es forzar una interacción continua.</p>
                                <ul class="space-y-4">
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Scrolling infinito:</strong> Te desplazas sin fin por el contenido, eliminando los puntos de parada que te permitirían reconsiderar tu tiempo.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Streaming infinito:</strong> El siguiente video o canción se reproduce automáticamente, manteniéndote pasivamente enganchado.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Gamificación:</strong> Usa puntos, trofeos y recompensas para convertir la interacción en un juego y motivar la participación constante.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Temporizadores:</strong> Crean una falsa urgencia o espera, obligándote a volver a la plataforma en un momento determinado.</div></li>
                                </ul>
                            </div>
                        </div>
                        <div id="tab2" class="tab-content hidden">
                           <div class="content-card p-6 md:p-8 rounded-lg shadow-lg">
                                <h3 class="text-2xl font-bold mb-4 text-[#3D405B]">Ingeniería Social</h3>
                                <p class="mb-6 text-[#3D405B]/90">Explotan tus sesgos psicológicos y necesidades sociales para manipular tu comportamiento. Es la categoría que más depende de tus datos personales.</p>
                                <ul class="space-y-4">
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Escasez:</strong> "¡Oferta limitada!" o "Solo quedan 3", para forzar una decisión impulsiva.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Aprobación social:</strong> Los "me gusta", comentarios y notificaciones de actividad apelan a tu necesidad de validación para mantenerte conectado.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Miedo a perderse algo (FOMO):</strong> Te inunda de notificaciones sobre lo que otros hacen para que sientas la ansiedad de quedarte fuera.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Recomendaciones algorítmicas:</strong> El motor de la adicción. Usa tus datos para personalizar el contenido y predecir qué te mantendrá enganchado por más tiempo.</div></li>
                                </ul>
                            </div>
                        </div>
                        <div id="tab3" class="tab-content hidden">
                            <div class="content-card p-6 md:p-8 rounded-lg shadow-lg">
                                <h3 class="text-2xl font-bold mb-4 text-[#3D405B]">Interferencia en la Interfaz</h3>
                                <p class="mb-6 text-[#3D405B]/90">Manipulan el diseño visual y la experiencia de usuario para dirigir tu atención hacia donde ellos quieren, dificultando la toma de decisiones conscientes.</p>
                                <ul class="space-y-4">
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Misdirection (distracción):</strong> Usan colores llamativos, fuentes grandes o diseños confusos para que hagas clic en la opción que les beneficia.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Sobrecarga cognitiva:</strong> Te abruman con tanta información, opciones y notificaciones que tu capacidad para evaluar las consecuencias disminuye.</div></li>
                                </ul>
                            </div>
                        </div>
                        <div id="tab4" class="tab-content hidden">
                           <div class="content-card p-6 md:p-8 rounded-lg shadow-lg">
                                <h3 class="text-2xl font-bold mb-4 text-[#3D405B]">Persistencia</h3>
                                <p class="mb-6 text-[#3D405B]/90">Explotan el impulso psicológico humano de querer terminar las tareas que hemos empezado, creando bucles de interacción difíciles de romper.</p>
                                <ul class="space-y-4">
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Efecto Zeigarnik:</strong> Las barras de progreso ("Perfil completo al 85%") o las tareas inacabadas crean una tensión mental que te impulsa a completarlas.</div></li>
                                    <li class="flex items-start"><span class="text-[#E07A5F] font-bold mr-3">→</span><div><strong class="text-[#3D405B]">Microinterrupciones:</strong> Anuncios, pop-ups o notificaciones que interrumpen tu flujo, obligándote a recuperar el hilo y, a menudo, extendiendo tu sesión.</div></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="impact" class="py-16">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-[#3D405B]">El Impacto en Tus Derechos</h2>
                    <p class="mt-4 max-w-2xl mx-auto text-lg text-[#3D405B]/80">
                        Estos patrones no son inofensivos. Violan directamente los principios fundamentales de la protección de datos. El gráfico muestra el nivel de riesgo de cada táctica.
                    </p>
                </div>
                <div class="flex flex-col lg:flex-row gap-8 items-center">
                    <div class="w-full lg:w-1/2">
                        <div class="chart-container">
                            <canvas id="impactChart"></canvas>
                        </div>
                    </div>
                    <div class="w-full lg:w-1/2 grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div class="content-card p-4 rounded-lg shadow-md">
                            <h4 class="font-bold text-lg mb-2">🛡️ Lealtad y Transparencia</h4>
                            <p class="text-sm text-[#3D405B]/90">El tratamiento de tus datos es opaco y engañoso, contrario a tus expectativas razonables.</p>
                        </div>
                         <div class="content-card p-4 rounded-lg shadow-md">
                            <h4 class="font-bold text-lg mb-2">⚖️ Licitud y Consentimiento</h4>
                            <p class="text-sm text-[#3D405B]/90">Tu consentimiento no es libre ni informado, ya que se obtiene a través de la manipulación.</p>
                        </div>
                         <div class="content-card p-4 rounded-lg shadow-md">
                            <h4 class="font-bold text-lg mb-2">🎯 Minimización y Finalidad</h4>
                            <p class="text-sm text-[#3D405B]/90">Se recopilan más datos de los necesarios para fines que no son claros ni legítimos.</p>
                        </div>
                         <div class="content-card p-4 rounded-lg shadow-md">
                            <h4 class="font-bold text-lg mb-2">👶 Protección Especial</h4>
                            <p class="text-sm text-[#3D405B]/90">El riesgo es especialmente grave para niños y adolescentes, más vulnerables a la manipulación.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="chile" class="py-16 bg-[#f0efe9]">
            <div class="container mx-auto px-6">
                <div class="text-center max-w-3xl mx-auto">
                    <h2 class="text-3xl md:text-4xl font-bold text-[#3D405B]">¿Y qué significa esto para Chile?</h2>
                    <p class="mt-4 text-lg text-[#3D405B]/80 mb-6">
                        Este debate es crucial para nuestro país. Con la inminente entrada en vigor de la **nueva ley de protección de datos en Chile**, tenemos la oportunidad y la obligación de actuar.
                    </p>
                    <div class="content-card p-8 rounded-lg shadow-lg text-left">
                        <p class="text-[#3D405B]/90">
                            El marco legal que se está construyendo en Chile debe incorporar explícitamente la prohibición de estas prácticas de diseño adictivo. No basta con pedir consentimiento; este debe ser genuinamente libre e informado, algo imposible en un entorno diseñado para manipular. Debemos aprender de la experiencia internacional para construir un ecosistema digital que sea seguro, ético y respetuoso con los derechos de todos los ciudadanos, especialmente los más vulnerables.
                        </p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-[#3D405B] text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p class="font-bold text-lg">Observatorio Ciudadan@ Digital</p>
            <p class="text-sm mt-2 opacity-80">Promoviendo un entorno digital justo, transparente y respetuoso con los derechos humanos.</p>
            <p class="text-xs mt-4 opacity-60">&copy; 2024. Todos los derechos reservados.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            const navLinks = mobileMenu.querySelectorAll('a');

            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
            
            navLinks.forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                });
            });

            const tabs = document.querySelectorAll('.tab-button');
            const tabContents = document.querySelectorAll('.tab-content');

            tabs.forEach(tab => {
                tab.addEventListener('click', () => {
                    const target = tab.getAttribute('data-tab');

                    tabs.forEach(t => t.classList.remove('active'));
                    tab.classList.add('active');

                    tabContents.forEach(content => {
                        if (content.id === target) {
                            content.classList.remove('hidden');
                        } else {
                            content.classList.add('hidden');
                        }
                    });
                });
            });

            const ctx = document.getElementById('impactChart').getContext('2d');
            const impactChart = new Chart(ctx, {
                type: 'radar',
                data: {
                    labels: ['Intensidad de Datos', 'Potencial de Daño', 'Manipulación Psicológica', 'Falta de Transparencia'],
                    datasets: [{
                        label: 'Acción Forzada',
                        data: [4, 6, 5, 7],
                        backgroundColor: 'rgba(224, 122, 95, 0.2)',
                        borderColor: 'rgba(224, 122, 95, 1)',
                        pointBackgroundColor: 'rgba(224, 122, 95, 1)',
                        pointBorderColor: '#fff',
                        pointHoverBackgroundColor: '#fff',
                        pointHoverBorderColor: 'rgba(224, 122, 95, 1)'
                    }, {
                        label: 'Ingeniería Social',
                        data: [9, 8, 9, 8],
                        backgroundColor: 'rgba(61, 64, 91, 0.2)',
                        borderColor: 'rgba(61, 64, 91, 1)',
                        pointBackgroundColor: 'rgba(61, 64, 91, 1)',
                        pointBorderColor: '#fff',
                        pointHoverBackgroundColor: '#fff',
                        pointHoverBorderColor: 'rgba(61, 64, 91, 1)'
                    },
                    {
                        label: 'Interferencia en Interfaz',
                        data: [2, 5, 7, 9],
                        backgroundColor: 'rgba(131, 145, 125, 0.2)',
                        borderColor: 'rgba(131, 145, 125, 1)',
                        pointBackgroundColor: 'rgba(131, 145, 125, 1)',
                        pointBorderColor: '#fff',
                        pointHoverBackgroundColor: '#fff',
                        pointHoverBorderColor: 'rgba(131, 145, 125, 1)'
                    },
                    {
                        label: 'Persistencia',
                        data: [3, 7, 8, 6],
                        backgroundColor: 'rgba(242, 204, 143, 0.2)',
                        borderColor: 'rgba(242, 204, 143, 1)',
                        pointBackgroundColor: 'rgba(242, 204, 143, 1)',
                        pointBorderColor: '#fff',
                        pointHoverBackgroundColor: '#fff',
                        pointHoverBorderColor: 'rgba(242, 204, 143, 1)'
                    }
                    ]
                },
                options: {
                    maintainAspectRatio: false,
                    scales: {
                        r: {
                            angleLines: {
                                color: 'rgba(61, 64, 91, 0.2)'
                            },
                            grid: {
                                color: 'rgba(61, 64, 91, 0.2)'
                            },
                            pointLabels: {
                                font: {
                                    size: 12,
                                    weight: 'bold'
                                },
                                color: '#3D405B'
                            },
                            ticks: {
                                backdropColor: '#F8F7F4',
                                color: '#3D405B',
                                stepSize: 2
                            },
                             suggestedMin: 0,
                             suggestedMax: 10
                        }
                    },
                    plugins: {
                        legend: {
                            position: 'bottom',
                             labels: {
                                color: '#3D405B'
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    let label = context.dataset.label || '';
                                    if (label) {
                                        label += ': ';
                                    }
                                    if (context.parsed.r !== null) {
                                        label += context.parsed.r;
                                    }
                                    return label;
                                }
                            }
                        }
                    }
                }
            });
        });
    </script>
</body>
</html>
