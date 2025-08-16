<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - CONECTA Rural Telecom</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #1B4D3E 0%, #2D5A4F 100%);
            min-height: 100vh;
        }
        .glass {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .logo-bg {
            background: linear-gradient(135deg, #2D5A4F 0%, #1B4D3E 100%);
        }
        .feature-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .tech-badge {
            background: linear-gradient(135deg, #007BFF 0%, #0056B3 100%);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 50px;
            display: inline-block;
            margin: 0.25rem;
            font-size: 0.875rem;
            font-weight: 500;
        }
        .section-divider {
            height: 3px;
            background: linear-gradient(90deg, #007BFF, #4A7C59, #007BFF);
            border-radius: 2px;
            margin: 2rem 0;
        }
    </style>
</head>
<body>
    <div class="min-h-screen py-12 px-4">
        <div class="max-w-6xl mx-auto">
            <!-- Header -->
            <div class="glass rounded-2xl p-8 mb-8 text-center">
                <div class="logo-bg w-24 h-24 rounded-full mx-auto mb-6 flex items-center justify-center">
                    <i class="fas fa-wifi text-3xl text-white"></i>
                </div>
                <h1 class="text-4xl font-bold text-white mb-4">
                    <i class="fas fa-leaf text-green-400 mr-2"></i>
                    CONECTA Rural Telecom
                </h1>
                <p class="text-xl text-gray-200 mb-4">Landing Page Profissional</p>
                <div class="flex justify-center space-x-4">
                    <span class="bg-green-500 text-white px-4 py-2 rounded-full text-sm">
                        <i class="fas fa-check mr-1"></i>Responsivo
                    </span>
                    <span class="bg-blue-500 text-white px-4 py-2 rounded-full text-sm">
                        <i class="fas fa-mobile-alt mr-1"></i>Mobile-First
                    </span>
                    <span class="bg-purple-500 text-white px-4 py-2 rounded-full text-sm">
                        <i class="fas fa-robot mr-1"></i>Chatbot IA
                    </span>
                </div>
            </div>

            <!-- Sobre o Projeto -->
            <div class="glass rounded-2xl p-8 mb-8">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center">
                    <i class="fas fa-globe text-blue-400 mr-3"></i>
                    Sobre o Projeto
                </h2>
                <p class="text-gray-200 text-lg leading-relaxed">
                    Landing page profissional da CONECTA Rural Telecom, especializada em fornecer 
                    <strong class="text-green-400">internet de alta velocidade</strong> para áreas rurais 
                    onde a fibra óptica não está disponível. Desenvolvida com foco em 
                    <strong class="text-blue-400">conversão máxima</strong> e 
                    <strong class="text-purple-400">experiência cinematográfica</strong>.
                </p>
            </div>

            <!-- Características -->
            <div class="glass rounded-2xl p-8 mb-8">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center">
                    <i class="fas fa-star text-yellow-400 mr-3"></i>
                    Características
                </h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="feature-card glass rounded-lg p-6 text-center">
                        <i class="fas fa-mobile-alt text-3xl text-green-400 mb-4"></i>
                        <h3 class="text-white font-semibold mb-2">Responsivo Mobile-First</h3>
                        <p class="text-gray-300 text-sm">Design adaptativo para todos dispositivos</p>
                    </div>
                    <div class="feature-card glass rounded-lg p-6 text-center">
                        <i class="fas fa-video text-3xl text-blue-400 mb-4"></i>
                        <h3 class="text-white font-semibold mb-2">Vídeos Cinematográficos</h3>
                        <p class="text-gray-300 text-sm">Fundos dinâmicos com paisagens rurais</p>
                    </div>
                    <div class="feature-card glass rounded-lg p-6 text-center">
                        <i class="fas fa-robot text-3xl text-purple-400 mb-4"></i>
                        <h3 class="text-white font-semibold mb-2">Chatbot Inteligente</h3>
                        <p class="text-gray-300 text-sm">IA direcionando para WhatsApp</p>
                    </div>
                    <div class="feature-card glass rounded-lg p-6 text-center">
                        <i class="fas fa-map-marked-alt text-3xl text-red-400 mb-4"></i>
                        <h3 class="text-white font-semibold mb-2">Verificação Cobertura</h3>
                        <p class="text-gray-300 text-sm">Formulário com validação tempo real</p>
                    </div>
                    <div class="feature-card glass rounded-lg p-6 text-center">
                        <i class="fab fa-whatsapp text-3xl text-green-500 mb-4"></i>
                        <h3 class="text-white font-semibold mb-2">WhatsApp Business</h3>
                        <p class="text-gray-300 text-sm">Integração completa para vendas</p>
                    </div>
                    <div class="feature-card glass rounded-lg p-6 text-center">
                        <i class="fas fa-search text-3xl text-orange-400 mb-4"></i>
                        <h3 class="text-white font-semibold mb-2">SEO Completo</h3>
                        <p class="text-gray-300 text-sm">Otimização para mecanismos busca</p>
                    </div>
                </div>
            </div>

            <!-- Tecnologias -->
            <div class="glass rounded-2xl p-8 mb-8">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center">
                    <i class="fas fa-code text-blue-400 mr-3"></i>
                    Tecnologias Utilizadas
                </h2>
                <div class="text-center">
                    <span class="tech-badge"><i class="fab fa-html5 mr-2"></i>HTML5 Semântico</span>
                    <span class="tech-badge"><i class="fab fa-css3-alt mr-2"></i>CSS3 Avançado</span>
                    <span class="tech-badge"><i class="fab fa-js-square mr-2"></i>JavaScript ES6+</span>
                    <span class="tech-badge"><i class="fab fa-bootstrap mr-2"></i>Bootstrap</span>
                    <span class="tech-badge"><i class="fas fa-font mr-2"></i>Google Fonts</span>
                    <span class="tech-badge"><i class="fas fa-video mr-2"></i>HTML5 Video</span>
                    <span class="tech-badge"><i class="fas fa-mobile-alt mr-2"></i>Responsive Design</span>
                    <span class="tech-badge"><i class="fas fa-rocket mr-2"></i>Performance</span>
                </div>
            </div>

            <!-- Funcionalidades -->
            <div class="glass rounded-2xl p-8 mb-8">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center">
                    <i class="fas fa-cogs text-purple-400 mr-3"></i>
                    Funcionalidades
                </h2>
                <div class="grid md:grid-cols-2 gap-6">
                    <div>
                        <ul class="space-y-3">
                            <li class="flex items-center text-gray-200">
                                <i class="fas fa-robot text-purple-400 mr-3"></i>
                                Chatbot automatizado direcionando para WhatsApp
                            </li>
                            <li class="flex items-center text-gray-200">
                                <i class="fas fa-check-circle text-green-400 mr-3"></i>
                                Formulários com validação em tempo real
                            </li>
                            <li class="flex items-center text-gray-200">
                                <i class="fas fa-comments text-blue-400 mr-3"></i>
                                Carrossel de depoimentos interativo
                            </li>
                        </ul>
                    </div>
                    <div>
                        <ul class="space-y-3">
                            <li class="flex items-center text-gray-200">
                                <i class="fas fa-counter text-yellow-400 mr-3"></i>
                                Contador animado de clientes
                            </li>
                            <li class="flex items-center text-gray-200">
                                <i class="fas fa-video text-red-400 mr-3"></i>
                                Vídeos de fundo otimizados
                            </li>
                            <li class="flex items-center text-gray-200">
                                <i class="fas fa-universal-access text-orange-400 mr-3"></i>
                                Design acessível (WCAG AA)
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Conversão Otimizada -->
            <div class="glass rounded-2xl p-8 mb-8">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center">
                    <i class="fas fa-bullseye text-red-400 mr-3"></i>
                    Conversão Otimizada
                </h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-4">
                    <div class="bg-gradient-to-r from-green-500 to-green-600 p-4 rounded-lg text-center">
                        <i class="fas fa-mouse-pointer text-white text-2xl mb-2"></i>
                        <h4 class="text-white font-semibold">CTAs Estratégicos</h4>
                        <p class="text-green-100 text-sm">Em toda a página</p>
                    </div>
                    <div class="bg-gradient-to-r from-blue-500 to-blue-600 p-4 rounded-lg text-center">
                        <i class="fas fa-user-plus text-white text-2xl mb-2"></i>
                        <h4 class="text-white font-semibold">Captura de Leads</h4>
                        <p class="text-blue-100 text-sm">Formulários otimizados</p>
                    </div>
                    <div class="bg-gradient-to-r from-purple-500 to-purple-600 p-4 rounded-lg text-center">
                        <i class="fab fa-whatsapp text-white text-2xl mb-2"></i>
                        <h4 class="text-white font-semibold">WhatsApp Multi</h4>
                        <p class="text-purple-100 text-sm">Múltiplos pontos contato</p>
                    </div>
                </div>
            </div>

            <!-- Performance -->
            <div class="glass rounded-2xl p-8 mb-8">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center">
                    <i class="fas fa-tachometer-alt text-green-400 mr-3"></i>
                    Performance
                </h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-4">
                    <div class="text-center">
                        <div class="bg-green-500 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-3">
                            <i class="fas fa-video text-white text-xl"></i>
                        </div>
                        <h4 class="text-white font-semibold">Vídeos < 5MB</h4>
                        <p class="text-gray-300 text-sm">Otimizados para web</p>
                    </div>
                    <div class="text-center">
                        <div class="bg-blue-500 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-3">
                            <i class="fas fa-lazy text-white text-xl"></i>
                        </div>
                        <h4 class="text-white font-semibold">Lazy Loading</h4>
                        <p class="text-gray-300 text-sm">Carregamento inteligente</p>
                    </div>
                    <div class="text-center">
                        <div class="bg-purple-500 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-3">
                            <i class="fas fa-compress text-white text-xl"></i>
                        </div>
                        <h4 class="text-white font-semibold">Compressão</h4>
                        <p class="text-gray-300 text-sm">Recursos otimizados</p>
                    </div>
                    <div class="text-center">
                        <div class="bg-yellow-500 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-3">
                            <i class="fas fa-mobile-alt text-white text-xl"></i>
                        </div>
                        <h4 class="text-white font-semibold">Mobile-First</h4>
                        <p class="text-gray-300 text-sm">Prioridade mobile</p>
                    </div>
                </div>
            </div>

            <!-- Desenvolvedor -->
            <div class="glass rounded-2xl p-8 text-center">
                <h2 class="text-2xl font-bold text-white mb-6 flex items-center justify-center">
                    <i class="fas fa-user-tie text-yellow-400 mr-3"></i>
                    Desenvolvido por
                </h2>
                <div class="bg-gradient-to-r from-green-600 to-blue-600 p-6 rounded-xl text-center">
                    <div class="w-20 h-20 bg-white rounded-full mx-auto mb-4 flex items-center justify-center">
                        <i class="fas fa-user text-3xl text-green-600"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-2">Tiago Cordeiro</h3>
                    <p class="text-gray-100 mb-4">
                        <i class="fas fa-gavel mr-2"></i>Vereador de Apucarana/PR pelo PDT
                        <br>
                        <i class="fas fa-satellite-dish mr-2"></i>Empresário do setor de telecomunicações
                    </p>
                    <div class="flex justify-center space-x-4">
                        <span class="bg-red-500 px-3 py-1 rounded-full text-sm text-white">
                            <i class="fas fa-map-marker-alt mr-1"></i>Apucarana/PR
                        </span>
                        <span class="bg-blue-800 px-3 py-1 rounded-full text-sm text-white">
                            <i class="fas fa-flag mr-1"></i>PDT
                        </span>
                    </div>
                </div>
            </div>

            <!-- Footer -->
            <div class="text-center mt-8 text-gray-300">
                <div class="section-divider"></div>
                <p class="text-lg">
                    <i class="far fa-copyright mr-2"></i>
                    2024 CONECTA Rural Telecom - Todos os direitos reservados.
                </p>
                <p class="text-sm mt-2 opacity-75">
                    Landing page desenvolvida com <i class="fas fa-heart text-red-400"></i> 
                    para revolucionar a internet rural no Brasil
                </p>
            </div>
        </div>
    </div>

    <!-- Animation Script -->
    <script>
        // Animate elements on scroll
        window.addEventListener('scroll', () => {
            const cards = document.querySelectorAll('.feature-card');
            cards.forEach(card => {
                const rect = card.getBoundingClientRect();
                if (rect.top < window.innerHeight && rect.bottom > 0) {
                    card.style.opacity = '1';
                    card.style.transform = 'translateY(0)';
                }
            });
        });

        // Initial load animation
        window.addEventListener('load', () => {
            document.querySelectorAll('.glass').forEach((el, index) => {
                setTimeout(() => {
                    el.style.opacity = '1';
                    el.style.transform = 'translateY(0)';
                }, index * 200);
            });
        });

        // Initialize styles
        document.addEventListener('DOMContentLoaded', () => {
            document.querySelectorAll('.glass').forEach(el => {
                el.style.opacity = '0';
                el.style.transform = 'translateY(50px)';
                el.style.transition = 'all 0.6s ease';
            });
            
            document.querySelectorAll('.feature-card').forEach(el => {
                el.style.opacity = '0';
                el.style.transform = 'translateY(30px)';
                el.style.transition = 'all 0.4s ease';
            });
        });
    </script>
</body>
</html>
    <script id="html_badge_script1">
        window.__genspark_remove_badge_link = "https://www.genspark.ai/api/html_badge/" +
            "remove_badge?token=To%2FBnjzloZ3UfQdcSaYfDk1nfevcYwsF5DtuC0B2HO%2FitZHXZc13u14KjIPZWaXsC8mTH3R6X9%2FM7OULTCvQR97T6zCMdBb3Tl%2F43hRZAbCHMJ8POYcXvzWwzOkjt4Aw5qqQP23zaoVI%2BopVNlka3wMYyARv9qFHHCtYCOZvbwKGXcFMmgz4uLMj37mk0fNxq02tNcFDc4RM9zBxboqswQwvHZdCa4l4qUh5C8klvY9FWKPyPgdYju8RlLVUwoTdneGc3sNMklavjHnM4Ry8Lr6KSLa%2BigTc%2FGa7xU7z8tFdONGNfELxmTq4gLFPMHTdm76OmjpeNICesMrWHyPqQGkXb6zNGjw5QTg%2FdxB4tKV5hPpboQYV8XamEYsnoJXIzJd6HQW%2FuuzKz8aFhJHZCg58wT20r%2BnRaKKOQ0HhmLTDml9LMTsJiH81AfFu3ZgVpsqgADKOCqqBNzMBb9uc5X0oZl5VoICl0pD9%2FyZKTnwdpJEaxbqj2k9xhRJa55EA";
        window.__genspark_locale = "pt-BR";
        window.__genspark_token = "To/BnjzloZ3UfQdcSaYfDk1nfevcYwsF5DtuC0B2HO/itZHXZc13u14KjIPZWaXsC8mTH3R6X9/M7OULTCvQR97T6zCMdBb3Tl/43hRZAbCHMJ8POYcXvzWwzOkjt4Aw5qqQP23zaoVI+opVNlka3wMYyARv9qFHHCtYCOZvbwKGXcFMmgz4uLMj37mk0fNxq02tNcFDc4RM9zBxboqswQwvHZdCa4l4qUh5C8klvY9FWKPyPgdYju8RlLVUwoTdneGc3sNMklavjHnM4Ry8Lr6KSLa+igTc/Ga7xU7z8tFdONGNfELxmTq4gLFPMHTdm76OmjpeNICesMrWHyPqQGkXb6zNGjw5QTg/dxB4tKV5hPpboQYV8XamEYsnoJXIzJd6HQW/uuzKz8aFhJHZCg58wT20r+nRaKKOQ0HhmLTDml9LMTsJiH81AfFu3ZgVpsqgADKOCqqBNzMBb9uc5X0oZl5VoICl0pD9/yZKTnwdpJEaxbqj2k9xhRJa55EA";
    </script>
    
    <script id="html_notice_dialog_script" src="https://www.genspark.ai/notice_dialog.js"></script>
    