<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conoce MIRA: Valores en Acción</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero-gradient {
            background: linear-gradient(135deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,119,255,1) 100%);
        }
        .section-title {
            font-weight: 900;
            font-size: 2.5rem;
            line-height: 1.2;
        }
        @media (min-width: 768px) {
            .section-title {
                font-size: 3.5rem;
            }
        }
        .counter-number {
            font-weight: 900;
            font-size: 4rem;
            color: #0077ff;
        }
        /* Estilos para la línea de tiempo */
        .timeline-item {
            position: relative;
            padding-bottom: 2.5rem;
            padding-left: 2.5rem;
        }
        .timeline-item:last-child {
            padding-bottom: 0;
        }
        .timeline-item::before {
            content: '';
            position: absolute;
            left: 0;
            top: 5px;
            width: 2px;
            height: 100%;
            background-color: #e2e8f0;
        }
        .timeline-dot {
            position: absolute;
            left: -8px;
            top: 5px;
            width: 18px;
            height: 18px;
            border-radius: 50%;
            background-color: #0077ff;
            border: 3px solid white;
        }
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        
        /* Estilos para el contenedor de video responsivo */
        .video-responsive-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* Proporción 16:9 */
            height: 0;
            overflow: hidden;
            max-width: 100%;
            background: #000;
        }
        .video-responsive-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="hero-gradient text-white shadow-lg">
        <div class="container mx-auto px-6 py-16 md:py-24 text-center">
            <h1 class="text-4xl md:text-6xl font-black uppercase tracking-wide">MIRA</h1>
            <h2 class="text-2xl md:text-4xl font-semibold mt-2">Una Forma Diferente de Hacer Política</h2>
            <p class="mt-6 text-lg md:text-xl max-w-3xl mx-auto">Descubre cómo transformamos valores en resultados reales para todos los colombianos. Más que promesas, son hechos.</p>
            <a href="#principios" class="mt-8 inline-block bg-white text-blue-700 font-bold py-3 px-8 rounded-full text-lg hover:bg-gray-200 transition duration-300">Conoce Nuestros Pilares</a>
        </div>
    </header>

    <main>
        <section id="principios" class="py-20 bg-white">
            <div class="container mx-auto px-6 text-center">
           
                 <h2 class="section-title text-gray-900">Nuestros Principios y Valores</h2>
                <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">No son solo palabras en un papel. Son la guía de cada una de nuestras acciones. Es nuestro ADN.</p>
                <div class="grid md:grid-cols-3 gap-8 mt-12 fade-in">
                    <div class="bg-gray-50 p-8 rounded-xl shadow-md border border-gray-100">
                   
                         <div class="text-blue-600 mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                        </div>
             
                        <h3 class="text-2xl font-bold mb-2">Coherencia</h3>
                        <p class="text-gray-600">Hacemos lo que decimos. Nuestras acciones reflejan nuestro discurso. Por eso, renunciamos a indemnizaciones millonarias, porque nuestro interés es la justicia, no el dinero.</p>
                    </div>
                    <div class="bg-gray-50 p-8 rounded-xl shadow-md border border-gray-100">
            
                         <div class="text-blue-600 mb-4">
                             <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" /></svg>
                        </div>
                
                        <h3 class="text-2xl font-bold mb-2">Practicidad</h3>
                        <p class="text-gray-600">La política debe servir a la gente. Creamos leyes que generan bienestar y resultados tangibles, como la Ley de Micronegocios, que apoya directamente a los pequeños emprendedores.</p>
                    </div>
                    <div class="bg-gray-50 p-8 rounded-xl shadow-md border border-gray-100">
            
                         <div class="text-blue-600 mb-4">
                            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mx-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" /></svg>
                        </div>
 
                       <h3 class="text-2xl font-bold mb-2">Veracidad</h3>
                        <p class="text-gray-600">Actuamos con autogestión consciente y responsable. La honestidad es el valor que une todo nuestro trabajo, garantizando un servicio leal y justo para todos.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="leyes" class="py-20 bg-gray-50">
    
             <div class="container mx-auto px-6 text-center">
                <h2 class="section-title text-gray-900">Resultados, No Promesas</h2>
                <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">Hemos impulsado leyes que cambian vidas. Este es nuestro legado.</p>
                <div class="mt-12 bg-white p-10 rounded-2xl shadow-xl border border-gray-200 fade-in">
                    <span class="counter-number" data-target="85">0</span>
                    <p class="text-2xl font-bold text-gray-700 mt-2">Leyes de la República gestionadas</p>
                    <p class="text-md text-gray-500">y contando...</p>
                </div>

                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 mt-12 text-left">
                    <div class="bg-white p-6 rounded-lg shadow-md fade-in">
             
                        <h4 class="font-bold text-xl mb-3 text-blue-700">Protección Social y Familia</h4>
                        <ul class="space-y-2 list-disc list-inside text-gray-600">
                            <li><span class="font-semibold">Ley del Adulto Mayor:</span> Defendemos sus derechos y penalizamos el abandono.</li>
               
                             <li><span class="font-semibold">Contra la Violencia Intrafamiliar:</span> Eliminamos barreras para que la justicia actúe de oficio.</li>
                            <li><span class="font-semibold">Cuidadores de Personas con Discapacidad:</span> Creamos beneficios y garantías para quienes cuidan a otros.</li>
                        </ul>
        
                     </div>
                    <div class="bg-white p-6 rounded-lg shadow-md fade-in">
                        <h4 class="font-bold text-xl mb-3 text-blue-700">Desarrollo Económico y Empleo</h4>
        
                         <ul class="space-y-2 list-disc list-inside text-gray-600">
                            <li><span class="font-semibold">Ley de Micronegocios:</span> Apoyo real con crédito justo y capacitación para los pequeños negocios.</li>
                            <li><span class="font-semibold">"Ley Empanada":</span> Formalización y apoyo para vendedores informales.</li>
  
                             <li><span class="font-semibold">Ley Retorno:</span> Incentivos para que los colombianos en el exterior regresen al país.</li>
                        </ul>
                    </div>
                 
                   <div class="bg-white p-6 rounded-lg shadow-md fade-in">
                        <h4 class="font-bold text-xl mb-3 text-blue-700">Derechos y Transparencia</h4>
                        <ul class="space-y-2 list-disc list-inside text-gray-600">
          
                             <li><span class="font-semibold">Ley Antidiscriminación:</span> Sancionamos los actos de odio y exclusión.</li>
                            <li><span class="font-semibold">Estatuto de Ciudadanía Juvenil:</span> Creamos los Consejos de Juventud, dándoles voz y voto.</li>
                            <li><span class="font-semibold">Gestión de Calidad:</span> Exigimos eficiencia y calidad en las entidades del Estado.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section id="historia" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="section-title text-gray-900 text-center">Nuestra Trayectoria: Crecimiento y Resiliencia</h2>
                <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto text-center">Una historia de convicción, lucha y crecimiento constante.</p>
                <div class="mt-16 max-w-3xl mx-auto fade-in">
  
                   <div class="timeline">
                        <div class="timeline-item">
                            
                             <div class="timeline-dot"></div>
                            <h3 class="text-xl font-bold">2000 - El Comienzo</h3>
                            <p class="text-gray-600">Nacimos como un movimiento ciudadano con más de 100,000 firmas, con un objetivo claro: renovar la política desde los valores.</p>
                  
                       </div>
                        <div class="timeline-item">
                            <div class="timeline-dot"></div>
            
                             <h3 class="text-xl font-bold">2002 - Llegada al Congreso</h3>
                            <p class="text-gray-600">Obtuvimos nuestra primera curul en el Senado, convirtiéndonos en una voz nueva y fuerte en el escenario nacional.</p>
                        </div>
        
                         <div class="timeline-item">
                            <div class="timeline-dot"></div>
                          
                             <h3 class="text-xl font-bold">2010 - Consolidación</h3>
                            <p class="text-gray-600">Alcanzamos 3 senadores y 1 representante, formando la única bancada paritaria (igual número de hombres y mujeres) del Congreso.</p>
                        </div>
                       
                         <div class="timeline-item">
                            <div class="timeline-dot"></div>
                            <h3 class="text-xl font-bold">2014 - La Prueba de Fuego</h3>
      
                             <p class="text-gray-600">Denunciamos un fraude electoral que nos dejó sin curules. No nos rendimos. Luchamos 4 años en los tribunales por la verdad.</p>
                        </div>
                        <div class="timeline-item">
            
                             <div class="timeline-dot"></div>
                            <h3 class="text-xl font-bold text-green-600">2018 - La Vindicación</h3>
                            <p class="text-gray-600">El Consejo de Estado nos dio la razón, probó el fraude y nos restituyó 3 curules. Demostramos que la lucha honesta da frutos.</p>
                        </div>
                         <div class="timeline-item">
                
                             <div class="timeline-dot"></div>
                            <h3 class="text-xl font-bold">Hoy - Más Fuertes que Nunca</h3>
                            <p class="text-gray-600">Con una bancada sólida y la Primera Vicepresidencia del Senado, seguimos trabajando con independencia y coherencia por Colombia.</p>
      
                       </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="liderazgo" class="py-20 bg-gray-50">
    
             <div class="container mx-auto px-6">
                <h2 class="section-title text-gray-900 text-center">Conoce a Nuestro Equipo</h2>
                <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto text-center">Líderes con experiencia y vocación de servicio.</p>

                <div class="mt-16">
    
                     <h3 class="text-3xl font-bold text-center text-gray-800">Líderes Fundadores</h3>
                    <div class="grid md:grid-cols-2 gap-10 mt-20 max-w-4xl mx-auto">
                        <div class="bg-white text-center p-6 rounded-xl shadow-lg fade-in">
                            <img class="w-32 h-32 rounded-full mx-auto -mt-16 border-4 border-white object-cover" src="https://carlosalbertobaena.com/wp-content/uploads/elementor/thumbs/carlos_alberto_baena_lopez_12104048-qv9kiu82526y2glgpx4jz0g64lwewyvtn8rulpjkn8.png" alt="Carlos Alberto Baena López" onerror="this.onerror=null;this.src='https://placehold.co/128x128/e2e8f0/64748b?text=Foto'">
                            <h4 class="text-2xl font-bold mt-4">Carlos A. Baena</h4>
                    
                         <p class="text-blue-600 font-semibold">Cofundador y Ex-Presidente</p>
                            <p class="text-gray-600 mt-2 text-sm">Abogado, Pastor General y ex-Viceministro. Una vida dedicada al servicio público y social.</p>
                        </div>
                        <div class="bg-white text-center p-6 rounded-xl shadow-lg fade-in">
           
                             <img class="w-32 h-32 rounded-full mx-auto -mt-16 border-4 border-white object-cover" src="https://redcontraelabusosexual.org/wp-content/uploads/2022/11/foto-doctora-532x1024.jpg" alt="Alexandra Moreno Piraquive" onerror="this.onerror=null;this.src='https://placehold.co/128x128/e2e8f0/64748b?text=Foto'">
                            <h4 class="text-2xl font-bold mt-4">Alexandra Moreno</h4>
                            <p class="text-blue-600 font-semibold">Cofundadora y Ex-Presidenta</p>
      
                             <p class="text-gray-600 mt-2 text-sm">Abogada, ex-Senadora y diplomática. Autora de 12 leyes enfocadas en la niñez y adultos mayores.</p>
                        </div>
                    </div>
                </div>

                <div class="mt-20">
                    <h3 class="text-3xl font-bold text-center text-gray-800">Dirección Actual</h3>
                    <div class="grid md:grid-cols-3 gap-10 mt-20 max-w-6xl mx-auto">
                        <div class="bg-white text-center p-6 rounded-xl shadow-lg fade-in">
                            <img class="w-32 h-32 rounded-full mx-auto -mt-16 border-4 border-white object-cover" src="https://manuelvirguez.com/wp-content/uploads/2022/11/senador-manuel.jpg" alt="Manuel Virgüez Piraquive" onerror="this.onerror=null;this.src='https://placehold.co/128x128/e2e8f0/64748b?text=Foto'">
                            <h4 class="text-2xl font-bold mt-4">Manuel Virgüez</h4>
             
                             <p class="text-blue-600 font-semibold">Presidente del Partido</p>
                             <p class="text-gray-600 mt-2 text-sm">Senador con vasta experiencia parlamentaria y actual Vicepresidente de la Comisión Segunda del Senado.</p>
                        </div>
            
                         <div class="bg-white text-center p-6 rounded-xl shadow-lg fade-in">
                             <img class="w-32 h-32 rounded-full mx-auto -mt-16 border-4 border-white object-cover" src="https://www.senado.gov.co/images/Fotos_Senadores_2022/Ana_paola_garcia.jpg" alt="Ana Paola Agudelo" onerror="this.onerror=null;this.src='https://placehold.co/128x128/e2e8f0/64748b?text=Foto'">
            
                             <h4 class="text-2xl font-bold mt-4">Ana Paola Agudelo</h4>
                            <p class="text-blue-600 font-semibold">Vicepresidenta y Senadora</p>
                            <p class="text-gray-600 mt-2 text-sm">Primera Vicepresidenta del Senado. Experta en temas de migración y políticas sociales.</p>
                        </div>
                         <div class="bg-white text-center p-6 rounded-xl shadow-lg fade-in">
          
                             <img class="w-32 h-32 rounded-full mx-auto -mt-16 border-4 border-white object-cover" src="https://www.irmaluzherrera.com/wp-content/uploads/2022/02/Diseno-sin-titulo-3-1024x1024.png" alt="Irma Luz Herrera" onerror="this.onerror=null;this.src='https://placehold.co/128x128/e2e8f0/64748b?text=Foto'">
                            <h4 class="text-2xl font-bold mt-4">Irma Luz Herrera</h4>
                            <p class="text-blue-600 font-semibold">Representante a la Cámara</p>
   
                             <p class="text-gray-600 mt-2 text-sm">Economista enfocada en la protección de la niñez y la modernización de Bogotá.</p>
                        </div>
                    </div>
               
                 </div>
            </div>
        </section>

        <section class="py-20 bg-white">
            <div class="container mx-auto px-6 text-center">
                 <h2 class="section-title text-gray-900">Tu Confianza Nos Hace Crecer</h2>
                <p class="mt-4 
 text-lg text-gray-600 max-w-2xl mx-auto">Cada voto cuenta y nos ha permitido consolidarnos.
 Este es el reflejo de nuestro trabajo.</p>
                <div class="mt-12 bg-white p-8 rounded-xl shadow-lg fade-in max-w-4xl mx-auto">
                    <h3 class="font-bold text-2xl text-left mb-6">Votos al Senado (2002-2022)</h3>
                    <div class="relative h-64 md:h-80">
                    
                         <canvas id="senateVotesChart"></canvas>
                    </div>
                </div>
            </div>
        </section>

        <section id="candidatura-exterior" class="py-20 bg-gray-50">
            <div class="container mx-auto px-6">
                <h2 class="section-title text-gray-900 text-center">Liderazgo para los Colombianos en el Exterior</h2>
                <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto text-center">Conoce a quien llevará la voz de los colombianos en el mundo al Congreso.</p>

                <div class="mt-16 max-w-md mx-auto">
                    <div class="bg-white text-center p-6 rounded-xl shadow-lg fade-in">
                        
                        <img class="w-32 h-32 rounded-full mx-auto -mt-16 border-4 border-white object-cover" 
                             src="https://scontent-bcn1-1.xx.fbcdn.net/v/t39.30808-6/580940162_10163912159157340_5350506802403917657_n.jpg?stp=cp6_dst-jpg_tt6&_nc_cat=108&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=dNC0zjBmsJIQ7kNvwHZrKh_&_nc_oc=Adny6y3ZYgV1Z2jOi4-DfN4MGUyw_6M8buvVWKVBK_4kBEMO6noYLc49aX9Pguy9kOOP2STEWEO4z4m4v7V08mLk&_nc_zt=23&_nc_ht=scontent-bcn1-1.xx&_nc_gid=DhwLM09BZhYeGfSIKT6_Hg&oh=00_Afhfjagk5RP_ycVgzLG0wjl0SXAKf9NCJ5LA3njY_wze6A&oe=691E74CC" 
                             alt="Alejandra Ospina" 
                             onerror="this.onerror=null;this.src='https://placehold.co/128x128/e2e8f0/64748b?text=Foto'">
                        
                        <h4 class="text-2xl font-bold mt-4">Alejandra Ospina</h4>
                        <p class="text-blue-600 font-semibold">Vocera Internacional (España) y Candidata 2026</p>
                        
                        <p class="text-gray-600 mt-2 text-sm">
                            Liderando la voz de MIRA en España. Próxima Representante a la Cámara por los Colombianos en el Exterior, por la coalición 'Ahora Colombia'.
                        </p>
                        
                        <a href="https://www.facebook.com/AlejandraOspinaOficial/" target="_blank" class="mt-6 inline-block bg-blue-600 text-white font-bold py-2 px-6 rounded-full text-md hover:bg-blue-700 transition duration-300">
                            Apoya su Candidatura
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <section id="video-exterior" class="py-20 bg-white">
            <div class="container mx-auto px-6 text-center">
                <h2 class="section-title text-gray-900">Mensaje para los Colombianos en el Exterior</h2>
                <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">Información importante sobre tu participación y representación.</p>
                <div class="mt-12 max-w-3xl mx-auto shadow-xl rounded-xl overflow-hidden fade-in">
                    <div class="video-responsive-wrapper">
                        <iframe 
                            src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2Fwatch%2F%3Fv%3D1149598983906422&show_text=false&width=560" 
                            scrolling="no" 
                            frameborder="0" 
                            allowfullscreen="true" 
                            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                        </iframe>
                    </div>
                </div>
            </div>
        </section>

        <section class="hero-gradient text-white">
            <div class="container mx-auto px-6 
 py-20 text-center">
                <h2 class="text-4xl font-black">Únete a la Renovación</h2>
                <p class="mt-4 text-xl max-w-2xl mx-auto">Si crees en una política honesta, transparente y al servicio de la gente, este es tu lugar. Tu voto tiene el poder de seguir construyendo un mejor país.</p>
                <a href="https://partidomira.com/" target="_blank" class="mt-8 inline-block bg-white text-blue-700 font-bold py-4 px-10 rounded-full text-xl hover:bg-gray-200 transition duration-300">Visita Nuestra Web Oficial</a>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2025 Partido Político MIRA. Todos los derechos reservados.</p>
            <p class="text-sm text-gray-400 mt-2">Esta es una aplicación informativa diseñada con base en el informe público del partido.</p>
        </div>
    </footer>
    
    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
    <script>
        // Script para animar contadores y elementos al hacer scroll
        document.addEventListener('DOMContentLoaded', () => {
            
             const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');

                        // Animación del contador
   
                         const counter = entry.target.querySelector('.counter-number');
                        if (counter && !counter.classList.contains('animated')) {
                            const target = +counter.getAttribute('data-target');
                 
                            counter.innerText = '0';
                            counter.classList.add('animated');

                            let current = 0;
                             const increment = target / 100;

                            const updateCounter = () => {
                                current += increment;
                                 if (current < target) {
                                    counter.innerText = Math.ceil(current);
                                     requestAnimationFrame(updateCounter);
                                } else {
                                    counter.innerText = target + "+";
                                 }
                            };
                             updateCounter();
                        }
                        observer.unobserve(entry.target);
                     }
                });
             }, {
                threshold: 0.1
            });
             document.querySelectorAll('.fade-in').forEach(el => {
                observer.observe(el);
            });
             // --- Chart.js implementation ---
            const senateYears = ['2002', '2006', '2010', '2014', '2018', '2022'];
             const senateVotes = [81061, 237512, 324109, 326943, 501489, 578195];

            const ctx = document.getElementById('senateVotesChart').getContext('2d');
             new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: senateYears,
                    datasets: [{
                      
                       label: 'Votos',
                        data: senateVotes,
                        backgroundColor: '#3b82f6',
                        borderColor: '#1d4ed8',
                      
                         borderWidth: 1,
                        borderRadius: 5,
                        hoverBackgroundColor: '#2563eb'
                    }]
                },
           
                 options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: {
      
                             display: false
                        },
                        tooltip: {
                            
                             callbacks: {
                                label: function(context) {
                                    let label = context.dataset.label || '';
                        
                                     if (label) {
                                        label += ': ';
                                     }
                                    if (context.parsed.y !== null) {
                                        label += new Intl.NumberFormat('es-CO').format(context.parsed.y);
                                     }
                                    return label;
                                 }
                            }
                        }
                    },
                    scales: {
       
                         y: {
                            beginAtZero: true,
                            ticks: {
                        
                                 callback: function(value) {
                                    if (value >= 1000) {
                                        return (value / 1000) + 'k';
                                     }
                                    return value;
                                 }
                            }
                        },
                        x: {
                       
                             grid: {
                                display: false
                            }
                        }
         
                     }
                }
            });
         });
    </script>
</body>
</html>
