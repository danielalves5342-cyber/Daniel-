<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guia Definitivo do Relacionamento Perfeito</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .font-serif {
            font-family: 'Playfair Display', serif;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .glass-effect {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .pulse-button {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0%, 100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(239, 68, 68, 0.7); }
            50% { transform: scale(1.05); box-shadow: 0 0 0 20px rgba(239, 68, 68, 0); }
        }
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        @keyframes floating {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
        .heart-beat {
            animation: heartBeat 1.5s ease-in-out infinite;
        }
        @keyframes heartBeat {
            0%, 100% { transform: scale(1); }
            14% { transform: scale(1.1); }
            28% { transform: scale(1); }
            42% { transform: scale(1.1); }
            70% { transform: scale(1); }
        }
        .fade-in {
            animation: fadeIn 1s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 overflow-x-hidden">

    <!-- Urgency Bar -->
    <div class="bg-red-600 text-white text-center py-2 px-4 text-sm font-semibold animate-pulse">
        🔥 OFERTA ESPECIAL: Últimas vagas com 60% OFF - Termina em <span id="countdown">23:59:59</span>
    </div>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 z-0">
            <img src="https://kimi-web-img.moonshot.cn/img/images.pexels.com/a5315b7f9545b50c2816adf84737300e065eaba0.jpeg" 
                 alt="Casal feliz" 
                 class="w-full h-full object-cover opacity-90">
            <div class="absolute inset-0 bg-gradient-to-b from-purple-900/80 via-purple-800/60 to-pink-600/80"></div>
        </div>

        <div class="relative z-10 container mx-auto px-4 text-center text-white max-w-4xl">
            <div class="mb-6 floating">
                <span class="text-6xl">💔➡️❤️</span>
            </div>
            
            <h1 class="font-serif text-4xl md:text-6xl lg:text-7xl font-bold mb-6 leading-tight drop-shadow-lg">
                Descubra o Segredo Para Transformar Seu Relacionamento em <span class="text-yellow-300 underline decoration-wavy">Menos de 30 Dias</span>
            </h1>
            
            <p class="text-xl md:text-2xl mb-8 font-light leading-relaxed drop-shadow-md">
                Mesmo que você esteja passando por uma crise, sinta que perdeu a conexão ou já tenha tentado de tudo...
            </p>

            <div class="bg-white/10 backdrop-blur-md rounded-2xl p-6 mb-8 border border-white/20 max-w-2xl mx-auto">
                <p class="text-lg md:text-xl mb-4">
                    "Finalmente entendi por que meu parceiro se afastava. Hoje temos o relacionamento dos sonhos!"
                </p>
                <div class="flex items-center justify-center gap-2 text-yellow-300 text-2xl mb-2">
                    ⭐⭐⭐⭐⭐
                </div>
                <p class="text-sm opacity-90">— Maria S., São Paulo</p>
            </div>

            <div class="space-y-4">
                <a href="https://pay.cakto.com.br/tzsb5bh_767798" 
                   class="inline-block bg-gradient-to-r from-red-500 to-pink-600 hover:from-red-600 hover:to-pink-700 text-white font-bold text-xl md:text-2xl py-5 px-12 rounded-full shadow-2xl transform transition hover:scale-105 pulse-button border-4 border-white/30">
                    QUERO SALVAR MEU RELACIONAMENTO AGORA! 💕
                </a>
                
                <p class="text-sm opacity-90 mt-4">
                    🔒 Pagamento 100% seguro • Acesso imediato • 7 dias de garantia
                </p>
            </div>
        </div>
    </section>

    <!-- Problem Section -->
    <section class="py-20 bg-white">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="font-serif text-3xl md:text-5xl text-center mb-12 text-gray-800">
                Você se identifica com alguma dessas situações?
            </h2>
            
            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-red-50 p-6 rounded-xl border-l-4 border-red-500 shadow-lg transform hover:scale-105 transition">
                    <div class="text-4xl mb-3">😢</div>
                    <h3 class="font-bold text-xl mb-2">Conversas viram brigas</h3>
                    <p class="text-gray-600">Toda tentativa de diálogo acaba em discussão e você não sabe mais como se comunicar</p>
                </div>
                
                <div class="bg-red-50 p-6 rounded-xl border-l-4 border-red-500 shadow-lg transform hover:scale-105 transition">
                    <div class="text-4xl mb-3">😔</div>
                    <h3 class="font-bold text-xl mb-2">Sente que perdeu a conexão</h3>
                    <p class="text-gray-600">Vocês moram juntos mas parecem estranhos, sem intimidade emocional</p>
                </div>
                
                <div class="bg-red-50 p-6 rounded-xl border-l-4 border-red-500 shadow-lg transform hover:scale-105 transition">
                    <div class="text-4xl mb-3">😰</div>
                    <h3 class="font-bold text-xl mb-2">Medo de terminar</h3>
                    <p class="text-gray-600">Você ama essa pessoa mas está perdendo as esperanças de que dê certo</p>
                </div>
                
                <div class="bg-red-50 p-6 rounded-xl border-l-4 border-red-500 shadow-lg transform hover:scale-105 transition">
                    <div class="text-4xl mb-3">🥺</div>
                    <h3 class="font-bold text-xl mb-2">Já tentou de tudo</h3>
                    <p class="text-gray-600">Livros, terapia, conselhos de amigos... e nada funcionou</p>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <p class="text-2xl font-serif text-gray-700 mb-6">
                    Se você concordou com pelo menos uma...<br>
                    <span class="text-red-600 font-bold">existe uma solução!</span>
                </p>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section class="py-20 bg-gradient-to-br from-purple-100 to-pink-100">
        <div class="container mx-auto px-4 max-w-5xl">
            <div class="text-center mb-16">
                <span class="bg-purple-600 text-white px-4 py-2 rounded-full text-sm font-bold uppercase tracking-wide">O Método</span>
                <h2 class="font-serif text-4xl md:text-5xl mt-4 mb-6 text-gray-800">
                    O Guia Definitivo do Relacionamento Perfeito
                </h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Um método passo a passo baseado em psicologia comportamental e neurociência do amor
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-8 mb-16">
                <div class="bg-white p-8 rounded-2xl shadow-xl text-center transform hover:-translate-y-2 transition">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4 text-3xl">
                        🧠
                    </div>
                    <h3 class="font-bold text-xl mb-3">Comunicação Não-Violenta</h3>
                    <p class="text-gray-600">Técnicas para expressar suas necessidades sem gerar defesa no parceiro</p>
                </div>

                <div class="bg-white p-8 rounded-2xl shadow-xl text-center transform hover:-translate-y-2 transition">
                    <div class="w-16 h-16 bg-pink-100 rounded-full flex items-center justify-center mx-auto mb-4 text-3xl">
                        🔥
                    </div>
                    <h3 class="font-bold text-xl mb-3">Reacenda a Paixão</h3>
                    <p class="text-gray-600">Estratégias cientificamente comprovadas para recuperar a intimidade física e emocional</p>
                </div>

                <div class="bg-white p-8 rounded-2xl shadow-xl text-center transform hover:-translate-y-2 transition">
                    <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4 text-3xl">
                        💎
                    </div>
                    <h3 class="font-bold text-xl mb-3">Conexão Profunda</h3>
                    <p class="text-gray-600">Exercícios práticos para criar vínculos que resistem ao tempo</p>
                </div>
            </div>

            <!-- What's Inside -->
            <div class="bg-white rounded-3xl p-8 md:p-12 shadow-2xl">
                <h3 class="font-serif text-3xl text-center mb-8">O que você vai receber:</h3>
                
                <div class="space-y-4 max-w-2xl mx-auto">
                    <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg">
                        <div class="text-green-500 text-2xl">✓</div>
                        <div>
                            <span class="font-bold">E-book completo</span> com 150+ páginas de conteúdo prático
                        </div>
                    </div>
                    
                    <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg">
                        <div class="text-green-500 text-2xl">✓</div>
                        <div>
                            <span class="font-bold">Workbook de exercícios</span> para aplicar imediatamente
                        </div>
                    </div>
                    
                    <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg">
                        <div class="text-green-500 text-2xl">✓</div>
                        <div>
                            <span class="font-bold">Scripts de conversação</span> para situações difíceis
                        </div>
                    </div>
                    
                    <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg">
                        <div class="text-green-500 text-2xl">✓</div>
                        <div>
                            <span class="font-bold">Checklists diários</span> para manter o relacionamento saudável
                        </div>
                    </div>
                    
                    <div class="flex items-center gap-4 p-4 bg-purple-50 rounded-lg border-2 border-purple-200">
                        <div class="text-purple-600 text-2xl">🎁</div>
                        <div>
                            <span class="font-bold">BÔNUS:</span> 30 dias de acesso ao grupo de apoio exclusivo
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gray-900 text-white">
        <div class="container mx-auto px-4 max-w-5xl">
            <h2 class="font-serif text-4xl text-center mb-12">Histórias de quem já transformou:</h2>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-gray-800 p-8 rounded-2xl border border-gray-700">
                    <div class="text-yellow-400 text-xl mb-4">⭐⭐⭐⭐⭐</div>
                    <p class="text-gray-300 mb-4 italic">"Estávamos a um passo da separação. Apliquei as técnicas do primeiro capítulo e no mesmo dia vimos uma mudança. Hoje somos mais felizes que no início!"</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 bg-purple-500 rounded-full flex items-center justify-center font-bold">JF</div>
                        <div>
                            <p class="font-bold">João F.</p>
                            <p class="text-sm text-gray-400">Rio de Janeiro</p>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-800 p-8 rounded-2xl border border-gray-700">
                    <div class="text-yellow-400 text-xl mb-4">⭐⭐⭐⭐⭐</div>
                    <p class="text-gray-300 mb-4 italic">"Pensei que fosse impossível recuperar o que tínhamos perdido. Este guia me mostrou que eu estava comunicando tudo errado. Gratidão eterna!"</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 bg-pink-500 rounded-full flex items-center justify-center font-bold">AC</div>
                        <div>
                            <p class="font-bold">Ana C.</p>
                            <p class="text-sm text-gray-400">São Paulo</p>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-800 p-8 rounded-2xl border border-gray-700">
                    <div class="text-yellow-400 text-xl mb-4">⭐⭐⭐⭐⭐</div>
                    <p class="text-gray-300 mb-4 italic">"Meu casamento de 15 anos estava monótono. Agora parece que estamos namorando de novo. Minha esposa não acredita na mudança!"</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 bg-blue-500 rounded-full flex items-center justify-center font-bold">RM</div>
                        <div>
                            <p class="font-bold">Roberto M.</p>
                            <p class="text-sm text-gray-400">Belo Horizonte</p>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-800 p-8 rounded-2xl border border-gray-700">
                    <div class="text-yellow-400 text-xl mb-4">⭐⭐⭐⭐⭐</div>
                    <p class="text-gray-300 mb-4 italic">"Investimento que vale cada centavo. Paguei 10x mais em terapia e não tive nem 10% do resultado que tive com este material."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 bg-green-500 rounded-full flex items-center justify-center font-bold">LS</div>
                        <div>
                            <p class="font-bold">Luciana S.</p>
                            <p class="text-sm text-gray-400">Curitiba</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Price Section -->
    <section class="py-20 bg-gradient-to-r from-purple-600 to-pink-600 text-white relative overflow-hidden">
        <div class="absolute inset-0 opacity-20">
            <div class="absolute top-0 left-0 w-64 h-64 bg-white rounded-full mix-blend-overlay filter blur-3xl animate-pulse"></div>
            <div class="absolute bottom-0 right-0 w-96 h-96 bg-yellow-300 rounded-full mix-blend-overlay filter blur-3xl animate-pulse"></div>
        </div>

        <div class="container mx-auto px-4 max-w-3xl relative z-10 text-center">
            <h2 class="font-serif text-4xl md:text-5xl mb-6">Investimento Único</h2>
            
            <div class="bg-white/10 backdrop-blur-lg rounded-3xl p-8 md:p-12 border border-white/20 shadow-2xl">
                <p class="text-lg mb-2 opacity-90">Valor normal:</p>
                <p class="text-3xl line-through opacity-60 mb-4">R$ 197,00</p>
                
                <div class="bg-yellow-400 text-gray-900 inline-block px-6 py-2 rounded-full font-bold text-lg mb-6 transform -rotate-2">
                    HOJE: 60% OFF
                </div>
                
                <p class="text-lg mb-2">12x de</p>
                <p class="text-6xl md:text-7xl font-bold mb-2">R$ 8,04</p>
                <p class="text-xl mb-6">ou R$ 80,00 à vista</p>
                
                <div class="space-y-3 mb-8 text-left max-w-md mx-auto">
                    <div class="flex items-center gap-2">
                        <span class="text-green-300 text-xl">✓</span>
                        <span>Acesso vitalício ao material</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="text-green-300 text-xl">✓</span>
                        <span>Atualizações gratuitas</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="text-green-300 text-xl">✓</span>
                        <span>Suporte por email</span>
                    </div>
                </div>

                <a href="https://pay.cakto.com.br/tzsb5bh_767798" 
                   class="inline-block bg-white text-purple-600 font-bold text-2xl py-6 px-12 rounded-full shadow-2xl transform transition hover:scale-105 pulse-button w-full md:w-auto">
                    COMPRAR AGORA POR R$ 80 💳
                </a>
                
                <img src="https://kimi-web-img.moonshot.cn/img/img.freepik.com/ef78409b18ca3a14092a8498e7bed75391bec3c0.jpg" 
                     alt="Casal feliz" 
                     class="mt-8 rounded-2xl mx-auto shadow-2xl w-full max-w-md object-cover h-64">
            </div>
        </div>
    </section>

    <!-- Guarantee -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4 max-w-3xl text-center">
            <div class="inline-block bg-green-100 p-8 rounded-full mb-6">
                <span class="text-6xl">🛡️</span>
            </div>
            <h2 class="font-serif text-3xl md:text-4xl mb-4">Garantia Incondicional de 7 Dias</h2>
            <p class="text-xl text-gray-600 leading-relaxed">
                Você tem 7 dias para acessar todo o conteúdo. Se por qualquer motivo achar que não é para você, 
                ou se não ver resultados, devolvemos 100% do seu dinheiro. Sem perguntas, sem burocracia. 
                <span class="font-bold text-green-600">Risco zero para você!</span>
            </p>
        </div>
    </section>

    <!-- FAQ -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4 max-w-3xl">
            <h2 class="font-serif text-3xl text-center mb-12">Perguntas Frequentes</h2>
            
            <div class="space-y-4">
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="font-bold text-lg mb-2 text-purple-700">Como vou receber o produto?</h3>
                    <p class="text-gray-600">Imediatamente após a confirmação do pagamento, você receberá um email com o link de acesso ao material digital. Pode acessar do celular, tablet ou computador.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="font-bold text-lg mb-2 text-purple-700">Funciona para relacionamentos em crise grave?</h3>
                    <p class="text-gray-600">Sim! O método foi desenvolvido especificamente para situações difíceis. Temos casos de sucesso até em separações iminentes.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h3 class="font-bold text-lg mb-2 text-purple-700">Preci
