# meu-portifolio-oficial

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- GOOGLE FONTS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- BOOTSTRAP ICONS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
    <link rel="stylesheet" href="style.css">
    <script src="menu.js" defer></script>
    <title>Portfólio de Luana</title>
</head>
<body>

<header>
    <div class="interface">
        <div class="logo">
            <a href="#">
                <img src="images/Logo DATa.png.ico.png" alt="Logo">
            </a>
        </div>
        <nav class="menu-desktop">
            <ul>
                <li><a href="#topo">Início</a></li>
                <li><a href="#especialidades">Especialidades</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#portfolio">Projetos</a></li>
                <li><a href="#formulario">Contato</a></li>
            </ul>
        </nav>
        <div class="btn-abrir-menu" id="btn-menu">
            <i class="bi bi-list"></i>
        </div>
        <div class="menu-mobile" id="menu-mobile">
            <div class="btn-fechar">
                <i class="bi bi-x-lg"></i>
            </div>
            <nav>
                <ul>
                    <li><a href="#topo" class="link-menu-mobile">Início</a></li>
                    <li><a href="#especialidades" class="link-menu-mobile">Especialidades</a></li>
                    <li><a href="#sobre" class="link-menu-mobile">Sobre</a></li>
                    <li><a href="#portfolio" class="link-menu-mobile">Projetos</a></li>
                    <li><a href="#formulario" class="link-menu-mobile">Contato</a></li>
                </ul>
            </nav>
        </div>
        <div class="overlay-menu" id="overlay-menu"></div>
    </div>
</header>

<main>
    <!-- TOPO -->
    <section id="topo" class="topo-do-site">
        <div class="interface">
            <div class="flex">
                <div class="txt-topo-site">
                    <h1>TRANSFORMANDO IDEIAS EM REALIDADE DIGITAL.</h1>
                    <p>Criatividade e inovação andam lado a lado. Com uma combinação única de design impactante, funcionalidade intuitiva e otimização para resultados, estou pronta para criar a presença online dos seus sonhos.</p>
                    <div class="btn-contato">
                        <a href="#formulario"><button>Entre em contato</button></a>
                    </div>
                </div>
                <div class="img-topo-site">
                    <img src="images/Logo DATa.png.ico.png" alt="Logo topo">
                </div>
            </div>
        </div>
    </section>

    <!-- ESPECIALIDADES -->
    <section id="especialidades" class="especiliadades">
        <div class="interface">
            <h2 class="titulo">MINHAS <span>ESPECIALIDADES.</span></h2>
            <div class="flex">
         <div class="especialidades-box">
    <a href="https://github.com/Luanatris"" target="_blank">
        <i class="bi bi-github"></i>
    </a>
    <h3>GitHub</h3>
    <p>Meu espaço de criação e aprendizado no mundo tech.
Aqui compartilho projetos em Java, Spring Boot e Data Science, explorando soluções que conectam tecnologia, inovação e agronegócio.</p>
</div>

<div class="especialidades-box">
    <a href="https://medium.com/@luanatristan" target="_blank">
        <i class="bi bi-wordpress"></i>
    </a>
    <h3>Blog</h3>
    <p>Aqui compartilho minhas descobertas e aprendizados no mundo da tecnologia,
    ciência de dados e inovação no agronegócio.  
    Este espaço é onde transformo experiências, desafios e códigos em
    histórias que inspiram outros a explorar o poder dos dados.</p>
</div>

    </section>

    <!-- SOBRE -->
    <section id="sobre" class="sobre">
        <div class="interface">
            <div class="flex">
                <div class="img-sobre">
                </div>
                <div class="txt-sobre">
                    <h2>MUITO PRAZER, <span>ME CHAMO LUANA ALVES.</span></h2>
                    <p>Sou Luana Alves da Silva, estudante do 4º semestre de Tecnologia em Ciências de Dados pela Uninter e no segundo semestre de Análise de Sistemas no IFRS, apaixonada por transformar dados e tecnologia em soluções que geram impacto real. Meu foco está no desenvolvimento de sistemas, análise de dados e criação de dashboards interativos, unindo organização, design moderno e usabilidade para entregar valor ao usuário final.</p>
                    <p>Valoriza inovação e aprendizado contínuo explorando novas ferramentas e metodologias para acompanhar a evolução do mercado.</p>
                    <p>Constrói soluções inteligentes desde APIs seguras com autenticação e controle de permissões até dashboards dinâmicos para tomada de decisão.</p>
                    <p>Une técnica e design utilizando boas práticas de programação, banco de dados e visualização de dados com interfaces modernas e intuitivas.</p>
                    <p>Coloca o usuário no centro garantindo que cada projeto entregue praticidade, eficiência e resultados mensuráveis.</p>
                    <div class="btn-social">
                        <a href="https://github.com/Luanatris"><button><i class="bi bi-github"></i></button></a>
                        <a href="https://www.linkedin.com/in/"><button><i class="bi bi-linkedin"></i></button></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- PORTFÓLIO -->
    <section id="portfolio" class="portfolio">
        <div class="interface">
            <h2 class="titulo">MEU <span>PORTFÓLIO.</span></h2>
            <div class="flex">
                <div class="img-port" style="background-image: url(images/rolagem.jpeg);">
                    <div class="overlay">Projeto 1</div>
                </div>
                <div class="img-port" style="background-image: url(images/rolagem.jpeg);">
                    <div class="overlay">Projeto 2</div>
                </div>
                <div class="img-port" style="background-image: url(images/rolagem.jpeg);">
                    <div class="overlay">Projeto 3</div>
                </div>
            </div>
        </div>
    </section>

    <!-- FORMULÁRIO -->
    <section id="formulario" class="formulario">
        <div class="interface">
            <h2 class="titulo">FALE <span>COMIGO.</span></h2>
            <form action="">
                <input type="text" placeholder="Seu nome completo:" required>
                <input type="email" placeholder="Seu e-mail:" required>
                <input type="text" placeholder="Seu celular:">
                <textarea placeholder="Sua mensagem" required> </textarea>
                <div class="btn-enviar"><input type="submit" value="ENVIAR"> </div>
            </form>
        </div>
    </section>
</main>

<footer>
    <div class="interface">
        <div class="line-footer">
            <div class="flex">
                <div class="logo-footer">
                    <img src="images/Logo DATa.png.ico.png" alt="Logo Footer">
                </div>
                <div class="btn-social">
                    <a href="https://www.instagram.com/luanat.i"><button><i class="bi bi-instagram"></i></button></a>
                    <a href="https://www.linkedin.com/luana-silva-a87005287"><button><i class="bi bi-linkedin"></i></button></a>
                </div>
            </div>
        </div>
        <div class="line-footer borda">
            <p><i class="bi bi-envelope-fill"></i> <a href="mailto:luanatristan@gmail.com">luanatristan@gmail.com</a></p>
        </div>
    </div>
</footer>

</body>
</html>
