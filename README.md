[!DOCTYPE.html](https://github.com/user-attachments/files/22476855/DOCTYPE.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>C Unhas - Nail Designer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(90deg, #f59e0b 0%, #eab308 100%);
        }
        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: #25d366;
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 3px #999;
            z-index: 100;
            display: flex;
            align-items: center;
            justify-content: center;
        }
    </style>
</head>
<body class="bg-white text-gray-800">
    <!-- Botão do WhatsApp Flutuante -->
    <a href="https://wa.me/5588999981878?text=Olá! Gostaria de agendar um horário." class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp"></i>
    </a>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-20 text-center">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">C Unhas - Nail Designer</h1>
            <p class="text-lg md:text-xl mb-8">Beleza e cuidado em cada detalhe ✨</p>
            <a href="#agendamento">
                <button class="bg-white text-yellow-600 font-bold px-6 py-3 rounded-full shadow-lg hover:bg-gray-100 transition duration-300">
                    Agende seu horário
                </button>
            </a>
        </div>
    </section>

    <!-- Sobre -->
    <section class="py-16 max-w-5xl mx-auto px-4 text-center">
        <h2 class="text-3xl font-bold mb-6">Sobre Mim</h2>
        <p class="text-lg leading-relaxed">
            Designer de unhas especializada em cuidados com mãos e pés, alongamentos
            e esmaltação artística. Cada atendimento é feito com dedicação para realçar sua beleza.
            Com mais de 5 anos de experiência, trago as melhores técnicas e produtos para garantir
            a saúde e beleza das suas unhas.
        </p>
    </section>

    <!-- Serviços -->
    <section class="py-16 bg-gray-50">
        <h2 class="text-3xl font-bold mb-10 text-center">Serviços</h2>

        <div class="grid md:grid-cols-2 gap-8 max-w-6xl mx-auto px-4">
            <!-- Mãos e Pés -->
            <div class="overflow-hidden shadow-lg rounded-2xl bg-white card-hover">
                <div class="w-full h-64 bg-yellow-100 flex items-center justify-center">
                    <i class="fas fa-hand-paper text-6xl text-yellow-500"></i>
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-semibold mb-2">Mãos e Pés</h3>
                    <p class="mb-4 text-gray-600">
                        Serviços de manicure e pedicure com opções decoradas e clássicas.
                    </p>
                    <p class="font-bold text-yellow-600">A partir de R$ 20,00</p>
                </div>
            </div>

            <!-- Esmaltação -->
            <div class="overflow-hidden shadow-lg rounded-2xl bg-white card-hover">
                <div class="w-full h-64 bg-pink-100 flex items-center justify-center">
                    <i class="fas fa-paint-brush text-6xl text-pink-500"></i>
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-semibold mb-2">Esmaltação</h3>
                    <p class="mb-4 text-gray-600">
                        Esmaltação delicada e artística, com acabamento em gel ou tradicional.
                    </p>
                    <p class="font-bold text-yellow-600">A partir de R$ 40,00</p>
                </div>
            </div>

            <!-- Alongamento -->
            <div class="overflow-hidden shadow-lg rounded-2xl bg-white card-hover">
                <div class="w-full h-64 bg-purple-100 flex items-center justify-center">
                    <i class="fas fa-plus-circle text-6xl text-purple-500"></i>
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-semibold mb-2">Alongamento</h3>
                    <p class="mb-4 text-gray-600">
                        Alongamento em gel e unhas postiças para alongar e dar formato perfeito.
                    </p>
                    <p class="font-bold text-yellow-600">A partir de R$ 45,00</p>
                </div>
            </div>

            <!-- Manutenção -->
            <div class="overflow-hidden shadow-lg rounded-2xl bg-white card-hover">
                <div class="w-full h-64 bg-blue-100 flex items-center justify-center">
                    <i class="fas fa-tools text-6xl text-blue-500"></i>
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-semibold mb-2">Manutenção</h3>
                    <p class="mb-4 text-gray-600">
                        Manutenção em gel, reposição e remoção de unhas com segurança e cuidado.
                    </p>
                    <p class="font-bold text-yellow-600">A partir de R$ 20,00</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Galeria -->
    <section class="py-16 max-w-6xl mx-auto px-4">
        <h2 class="text-3xl font-bold mb-10 text-center">Galeria de Trabalhos</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
            <div class="h-40 bg-yellow-200 rounded-lg flex items-center justify-center">
                <i class="fas fa-image text-4xl text-yellow-500"></i>
            </div>
            <div class="h-40 bg-pink-200 rounded-lg flex items-center justify-center">
                <i class="fas fa-image text-4xl text-pink-500"></i>
            </div>
            <div class="h-40 bg-purple-200 rounded-lg flex items-center justify-center">
                <i class="fas fa-image text-4xl text-purple-500"></i>
            </div>
            <div class="h-40 bg-blue-200 rounded-lg flex items-center justify-center">
                <i class="fas fa-image text-4xl text-blue-500"></i>
            </div>
        </div>
    </section>

    <!-- Contato -->
    <section id="agendamento" class="py-16 max-w-4xl mx-auto px-4 text-center bg-gray-50 rounded-lg">
        <h2 class="text-3xl font-bold mb-6">Agende seu Horário</h2>
        <p class="text-lg mb-4">Entre em contato pelo WhatsApp e garanta já sua vaga!</p>
        <a href="https://wa.me/5588999981878?text=Olá! Gostaria de agendar um horário." target="_blank">
            <button class="bg-yellow-500 text-white font-bold px-6 py-3 rounded-full shadow-lg hover:bg-yellow-600 transition duration-300">
                <i class="fab fa-whatsapp mr-2"></i> WhatsApp: (88) 9998-1878
            </button>
        </a>
        
        <div class="mt-10">
            <h3 class="text-xl font-semibold mb-4">Ou preencha o formulário:</h3>
            <form class="max-w-md mx-auto">
                <input type="text" placeholder="Seu nome" class="w-full px-4 py-2 mb-4 border rounded-lg focus:outline-none focus:ring-2 focus:ring-yellow-500">
                <input type="tel" placeholder="Seu WhatsApp" class="w-full px-4 py-2 mb-4 border rounded-lg focus:outline-none focus:ring-2 focus:ring-yellow-500">
                <textarea placeholder="Descreva o serviço desejado" class="w-full px-4 py-2 mb-4 border rounded-lg focus:outline-none focus:ring-2 focus:ring-yellow-500 h-24"></textarea>
                <button type="submit" class="bg-yellow-500 text-white font-bold px-6 py-3 rounded-lg shadow-lg hover:bg-yellow-600 transition duration-300 w-full">
                    Solicitar contato
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="gradient-bg text-white py-8 text-center">
        <div class="container mx-auto px-4">
            <p>© 2023 C Unhas - Nail Designer. Todos os direitos reservados.</p>
            <div class="mt-4 flex justify-center space-x-4">
                <a href="#" class="text-white hover:text-gray-200"><i class="fab fa-instagram text-2xl"></i></a>
                <a href="#" class="text-white hover:text-gray-200"><i class="fab fa-facebook text-2xl"></i></a>
                <a href="#" class="text-white hover:text-gray-200"><i class="fab fa-tiktok text-2xl"></i></a>
            </div>
        </div>
    </footer>
</body>
</html>
