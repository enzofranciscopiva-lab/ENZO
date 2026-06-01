<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Garagem Tech - O Blog do Antigomobilismo e Superesportivos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="header">
        <h1>Garagem Tech</h1>
        <p>Compartilhando a paixão por motores, design e velocidade.</p>
    </header>

    <main class="container">
        <article class="post">
            <h2>O Futuro dos Superesportivos: O rugido dos motores vai sumir?</h2>
            <p class="autor">Por: <strong>Marcelo Paludetto</strong></p>
            
            <img class="post-imagem" src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?w=800&auto=format&fit=crop&q=60" alt="Porsche escuro em uma estrada vazia">

            <p class="conteudo-texto">
                Bem-vindos ao meu novo blog sobre carros! Aqui vamos discutir as novidades do mundo automotivo, tecnologias de motores elétricos, clássicos que marcaram época e curiosidades sobre o design das maiores montadoras do mundo.
            </p>

            <div class="interacao">
                <button class="btn-interagir">❤️ Curtir (<span>0</span>)</button>
                <button class="btn-interagir">🔥 Favoritar (<span>0</span>)</button>
            </div>
        </article>
    </main>

    <script>
        const botoes = document.querySelectorAll(".btn-interagir");

        botoes.forEach(function(botao) {
            botao.addEventListener("click", function botaoClicado() {
                let textoContador = botao.querySelector("span");
                textoContador.textContent++;
