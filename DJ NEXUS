<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>DJ NEXUS TOUR 2025</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #121212 0%, #1c1c1c 100%);
            color: #f0f0f0;
            margin: 0;
            padding: 0;
            animation: fadeIn 1s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        #countdown {
            text-align: center;
            font-size: 1.5em;
            color: #1db954;
            font-weight: bold;
            animation: pulse 2s infinite;
        }
        .table-row:hover {
            background-color: rgba(255, 255, 255, 0.1);
            transform: translateY(-2px);
            transition: all 0.3s ease;
        }
        .tooltip {
            position: relative;
            cursor: pointer;
        }
        .tooltip .tooltip-text {
            visibility: hidden;
            width: 220px;
            background-color: #1db954;
            color: #121212;
            text-align: center;
            border-radius: 6px;
            padding: 8px;
            position: absolute;
            z-index: 10;
            bottom: 125%;
            left: 50%;
            margin-left: -110px;
            opacity: 0;
            transition: opacity 0.3s;
            font-size: 0.9em;
        }
        .tooltip:hover .tooltip-text {
            visibility: visible;
            opacity: 1;
        }
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0, 0, 0, 0.8);
        }
        .modal-content {
            background-color: #222;
            margin: 15% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            max-width: 500px;
            border-radius: 10px;
            text-align: center;
            color: #f0f0f0;
        }
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
            cursor: pointer;
        }
        .close:hover,
        .close:focus {
            color: white;
            text-decoration: none;
        }
        .btn-scroll-top {
            position: fixed;
            bottom: 80px;
            right: 30px;
            background: #1db954;
            color: #121212;
            border: none;
            padding: 12px 16px;
            border-radius: 50%;
            font-size: 24px;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(29, 185, 84, 0.7);
            transition: background 0.3s ease;
            display: none;
            z-index: 100;
        }
        .btn-scroll-top:hover {
            background: #17a44d;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #1db954;
            color: #121212;
            font-weight: bold;
            letter-spacing: 1px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .fade-in {
            animation: fadeIn 2s ease-in;
        }
        input:focus, label:focus {
            outline: 2px solid #1db954;
            outline-offset: 2px;
        }
    </style>
</head>
<body>
    <!-- Botão Scroll to Top -->
    <button class="btn-scroll-top" onclick="scrollToTop()" aria-label="Voltar ao topo">&uarr;</button>

    <header class="text-center py-10 bg-gray-900 shadow-lg">
        <h1 class="text-4xl md:text-6xl font-bold text-green-400 uppercase tracking-wider">DJ NEXUS TOUR 2025</h1>
        <p class="mt-4 text-lg md:text-xl text-gray-300">Prepare-se para uma jornada musical épica ao redor do mundo!</p>
    </header>

    <main class="max-w-6xl mx-auto py-10 px-4 md:px-8">
        <!-- Countdown Section -->
        <section class="fade-in mb-12">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-4 text-green-400">Countdown para a Turnê</h2>
            <div id="countdown" aria-live="polite" aria-atomic="true">Calculando...</div>
        </section>

        <!-- Datas e Cidades -->
        <section class="fade-in mb-12" aria-label="Tabela de datas e cidades da turnê">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-6 text-green-400">Datas e Cidades</h2>
            <div class="overflow-x-auto">
                <table class="w-full border-collapse bg-gray-800 rounded-lg shadow-lg" role="table">
                    <thead>
                        <tr class="bg-green-400 text-gray-900">
                            <th class="py-3 px-4 text-left font-bold uppercase tracking-wide" scope="col">Data</th>
                            <th class="py-3 px-4 text-left font-bold uppercase tracking-wide" scope="col">Cidade</th>
                            <th class="py-3 px-4 text-left font-bold uppercase tracking-wide" scope="col">País</th>
                        </tr>
                    </thead>
                    <tbody id="tourTable">
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">09 de setembro de 2025</td><td>Londres</td><td>Reino Unido<span class="tooltip-text">Show no icônico O2 Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">13 de setembro de 2025</td><td>Paris</td><td>França<span class="tooltip-text">Local: Le Zénith</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">17 de setembro de 2025</td><td>Sydney</td><td>Austrália<span class="tooltip-text">Festival ao ar livre no Sydney Showground</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">21 de setembro de 2025</td><td>Tóquio</td><td>Japão<span class="tooltip-text">Evento exclusivo no Tokyo Dome</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">25 de setembro de 2025</td><td>Cidade do México</td><td>México<span class="tooltip-text">Local: Palacio de los Deportes</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">29 de setembro de 2025</td><td>Buenos Aires</td><td>Argentina<span class="tooltip-text">Show no Estádio Luna Park</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">02 de outubro de 2025</td><td>Moscou</td><td>Rússia<span class="tooltip-text">Local: Crocus City Hall</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">06 de outubro de 2025</td><td>Cairo</td><td>Egito<span class="tooltip-text">Evento especial ao ar livre</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">10 de outubro de 2025</td><td>Toronto</td><td>Canadá<span class="tooltip-text">Local: Scotiabank Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">14 de outubro de 2025</td><td>Berlim</td><td>Alemanha<span class="tooltip-text">Show no Mercedes-Benz Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">18 de outubro de 2025</td><td>Cidade do Cabo</td><td>África do Sul<span class="tooltip-text">Festival no Green Point Stadium</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">22 de outubro de 2025</td><td>Nova Délhi</td><td>Índia<span class="tooltip-text">Evento cultural especial</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">26 de outubro de 2025</td><td>Dubai</td><td>Emirados Árabes Unidos<span class="tooltip-text">Local: Dubai Opera</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">30 de outubro de 2025</td><td>Seul</td><td>Coreia do Sul<span class="tooltip-text">Show no Jamsil Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">04 de novembro de 2025</td><td>Roma</td><td>Itália<span class="tooltip-text">Local: Palazzo dello Sport</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">08 de novembro de 2025</td><td>Miami</td><td>EUA<span class="tooltip-text">Evento no American Airlines Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">12 de novembro de 2025</td><td>Bangcoc</td><td>Tailândia<span class="tooltip-text">Festival ao ar livre</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">16 de novembro de 2025</td><td>Barcelona</td><td>Espanha<span class="tooltip-text">Local: Palau Sant Jordi</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">20 de novembro de 2025</td><td>Auckland</td><td>Nova Zelândia<span class="tooltip-text">Evento especial no Spark Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">24 de novembro de 2025</td><td>Lima</td><td>Peru<span class="tooltip-text">Show no Jockey Club del Perú</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">28 de novembro de 2025</td><td>Varsóvia</td><td>Polônia<span class="tooltip-text">Local: Torwar Hall</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">01 de dezembro de 2025</td><td>São Paulo</td><td>Brasil<span class="tooltip-text">Show no Allianz Parque</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">05 de dezembro de 2025</td><td>Helsinque</td><td>Finlândia<span class="tooltip-text">Local: Hartwall Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">09 de dezembro de 2025</td><td>Jakarta</td><td>Indonésia<span class="tooltip-text">Evento no Istora Senayan</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">13 de dezembro de 2025</td><td>Vancouver</td><td>Canadá<span class="tooltip-text">Local: Rogers Arena</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">17 de dezembro de 2025</td><td>Atenas</td><td>Grécia<span class="tooltip-text">Show no Tae Kwon Do Stadium</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">19 de dezembro de 2025</td><td>Rio de Janeiro</td><td>Brasil<span class="tooltip-text">Evento no Maracanãzinho</span></td></tr>
                        <tr class="table-row tooltip" tabindex="0"><td class="py-3 px-4">21 de dezembro de 2025</td><td>Ceará</td><td>Brasil<span class="tooltip-text">Show no Centro de Eventos do Ceará</span></td></tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Seleção e Formulário -->
        <section class="fade-in" aria-label="Formulário de pré-venda">
            <h2 class="text-2xl md:text-3xl font-bold text-center mb-6 text-green-400">Pré-venda - Selecione Datas e Lugares de Interesse</h2>
            <form id="preVendaForm" class="bg-gray-800 p-6 rounded-lg shadow-lg" onsubmit="return handleSubmit(event)" novalidate>
                <label for="nome" class="block mb-4 text-lg font-semibold">Nome completo:</label>
                <input type="text" id="nome" name="nome" required class="w-full p-3 rounded bg-gray-700 border-none text-white" placeholder="Seu nome completo" aria-required="true" />

                <label for="email" class="block mb-4 text-lg font-semibold">Email:</label>
                <input type="email" id="email" name="email" required class="w-full p-3 rounded bg-gray-700 border-none text-white" placeholder="seuemail@exemplo.com" aria-required="true" />

                <label class="block mb-4 text-lg font-semibold" id="checkbox-group-label">Datas e Lugares:</label>
                <div class="checkbox-group max-h-64 overflow-y-auto bg-gray-700 p-4 rounded" id="cidadesCheckboxes" role="group" aria-labelledby="checkbox-group-label">
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="09 de setembro de 2025 - Londres, Reino Unido" class="mr-2 scale-125" /> 09 de setembro de 2025 - Londres, Reino Unido</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="13 de setembro de 2025 - Paris, França" class="mr-2 scale-125" /> 13 de setembro de 2025 - Paris, França</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="17 de setembro de 2025 - Sydney, Austrália" class="mr-2 scale-125" /> 17 de setembro de 2025 - Sydney, Austrália</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="21 de setembro de 2025 - Tóquio, Japão" class="mr-2 scale-125" /> 21 de setembro de 2025 - Tóquio, Japão</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="25 de setembro de 2025 - Cidade do México, México" class="mr-2 scale-125" /> 25 de setembro de 2025 - Cidade do México, México</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="29 de setembro de 2025 - Buenos Aires, Argentina" class="mr-2 scale-125" /> 29 de setembro de 2025 - Buenos Aires, Argentina</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="02 de outubro de 2025 - Moscou, Rússia" class="mr-2 scale-125" /> 02 de outubro de 2025 - Moscou, Rússia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="06 de outubro de 2025 - Cairo, Egito" class="mr-2 scale-125" /> 06 de outubro de 2025 - Cairo, Egito</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="10 de outubro de 2025 - Toronto, Canadá" class="mr-2 scale-125" /> 10 de outubro de 2025 - Toronto, Canadá</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="14 de outubro de 2025 - Berlim, Alemanha" class="mr-2 scale-125" /> 14 de outubro de 2025 - Berlim, Alemanha</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="18 de outubro de 2025 - Cidade do Cabo, África do Sul" class="mr-2 scale-125" /> 18 de outubro de 2025 - Cidade do Cabo, África do Sul</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="22 de outubro de 2025 - Nova Délhi, Índia" class="mr-2 scale-125" /> 22 de outubro de 2025 - Nova Délhi, Índia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="26 de outubro de 2025 - Dubai, Emirados Árabes Unidos" class="mr-2 scale-125" /> 26 de outubro de 2025 - Dubai, Emirados Árabes Unidos</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="30 de outubro de 2025 - Seul, Coreia do Sul" class="mr-2 scale-125" /> 30 de outubro de 2025 - Seul, Coreia do Sul</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="04 de novembro de 2025 - Roma, Itália" class="mr-2 scale-125" /> 04 de novembro de 2025 - Roma, Itália</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="08 de novembro de 2025 - Miami, EUA" class="mr-2 scale-125" /> 08 de novembro de 2025 - Miami, EUA</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="12 de novembro de 2025 - Bangcoc, Tailândia" class="mr-2 scale-125" /> 12 de novembro de 2025 - Bangcoc, Tailândia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="16 de novembro de 2025 - Barcelona, Espanha" class="mr-2 scale-125" /> 16 de novembro de 2025 - Barcelona, Espanha</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="20 de novembro de 2025 - Auckland, Nova Zelândia" class="mr-2 scale-125" /> 20 de novembro de 2025 - Auckland, Nova Zelândia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="24 de novembro de 2025 - Lima, Peru" class="mr-2 scale-125" /> 24 de novembro de 2025 - Lima, Peru</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="28 de novembro de 2025 - Varsóvia, Polônia" class="mr-2 scale-125" /> 28 de novembro de 2025 - Varsóvia, Polônia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="01 de dezembro de 2025 - São Paulo, Brasil" class="mr-2 scale-125" /> 01 de dezembro de 2025 - São Paulo, Brasil</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="05 de dezembro de 2025 - Helsinque, Finlândia" class="mr-2 scale-125" /> 05 de dezembro de 2025 - Helsinque, Finlândia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="09 de dezembro de 2025 - Jakarta, Indonésia" class="mr-2 scale-125" /> 09 de dezembro de 2025 - Jakarta, Indonésia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="13 de dezembro de 2025 - Vancouver, Canadá" class="mr-2 scale-125" /> 13 de dezembro de 2025 - Vancouver, Canadá</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="17 de dezembro de 2025 - Atenas, Grécia" class="mr-2 scale-125" /> 17 de dezembro de 2025 - Atenas, Grécia</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="19 de dezembro de 2025 - Rio de Janeiro, Brasil" class="mr-2 scale-125" /> 19 de dezembro de 2025 - Rio de Janeiro, Brasil</label>
                    <label class="flex items-center mb-2 cursor-pointer"><input type="checkbox" name="cidades" value="21 de dezembro de 2025 - Ceará, Brasil" class="mr-2 scale-125" /> 21 de dezembro de 2025 - Ceará, Brasil</label>
                </div>
                <button type="submit" class="w-full mt-6 bg-green-400 text-gray-900 py-3 rounded font-bold text-lg hover:bg-green-500 transition-colors">Enviar Pré-venda</button>
            </form>
        </section>
    </main>

    <!-- Modal de Confirmação -->
    <div id="myModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal()">&times;</span>
            <h2 class="text-green-400">Pré-venda Enviada!</h2>
            <p>Obrigado por se interessar. Entraremos em contato em breve!</p>
        </div>
    </div>

    <footer>
        &copy; 2025 DJ NEXUS. Todos os direitos reservados.
    </footer>

    <script>
        function handleSubmit(event) {
            event.preventDefault();

            const nome = document.getElementById('nome').value.trim();
            const email = document.getElementById('email').value.trim();
            const checkboxes = document.querySelectorAll('input[name="cidades"]:checked');
            const cidadesSelecionadas = Array.from(checkboxes).map(cb => cb.value);

            if (cidadesSelecionadas.length === 0) {
                alert('Por favor, selecione pelo menos uma data e lugar de interesse.');
                return false;
            }

            // Salva no localStorage
            const dados = { nome, email, cidades: cidadesSelecionadas };
            localStorage.setItem('preVenda', JSON.stringify(dados));

            // Mostra modal
            document.getElementById('myModal').style.display = 'block';

            document.getElementById('preVendaForm').reset();

            return false;
        }

        function closeModal() {
            document.getElementById('myModal').style.display = 'none';
        }

        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Countdown
        function updateCountdown() {
            const targetDate = new Date(2025, 8, 9, 0, 0, 0); // Setembro é mês 8 (0-indexed)
            const now = new Date();
            const diff = targetDate.getTime() - now.getTime();

            if (diff > 0) {
                const days = Math.floor(diff / (1000 * 60 * 60 * 24));
                const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((diff % (1000 * 60)) / 1000);

                document.getElementById('countdown').textContent = `${days}d ${hours}h ${minutes}m ${seconds}s até o início da turnê!`;
            } else {
                document.getElementById('countdown').textContent = 'A turnê iniciou! 🎉';
            }
        }

        // Chamadas iniciais
        updateCountdown();
        setInterval(updateCountdown, 1000);

        // Interatividade na tabela
        const rows = document.querySelectorAll('.table-row');
        rows.forEach(row => {
            row.addEventListener('mouseenter', () => {
                row.style.transform = 'scale(1.02)';
            });
            row.addEventListener('mouseleave', () => {
                row.style.transform = 'scale(1)';
            });
        });

        // Mostrar botão scroll to top após rolar
        window.addEventListener('scroll', () => {
            if (window.scrollY > 200) {
                document.querySelector('.btn-scroll-top').style.display = 'block';
            } else {
                document.querySelector('.btn-scroll-top').style.display = 'none';
            }
        });
    </script>
</body>
</html>
</content>
</create_file>
