# Meu Curriculum vitae

O projeto passado pelo professor Marcio, na matéria de Desenvolvimento Web I no curso de DSM - FATEC Franca - 1ºsemestre. Foi pensando em termos nosso currículo em uma versão web page, nos forçando a por em prática os conhecimentos adquiridos em HTML e CSS.

## 💻 **[Link do site](https://joaoluquetti.github.io/cv-versionado/)**

## 🚀 Código-fonte e imagens utilizadas

No site foi utilizado:
 - HTML
 - CSS

 Cógido-fonte:
  - HTML
```
    <!DOCTYPE html>
    <html lang="pt-BR">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>João Luquetti</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="icon" type="image/x-icon" href="img/icon.png">
    </head>
    <body>
    <div class="esquerda">
        <div class="circle">
            <img src="img/perfil.PNG">
        </div>

        <h1>JOÃO VITOR<br>LUQUETTI</h1>
        <h3>Analista de Redes Jr.</h3>
        <h2>EDUCAÇAO</h2>
        <p class="destaque">Universidade Municipal de Franca - FACEF</p>
        <p>Engenharia de Software: 2018 - 2020</p>
        <br>
        <p class="destaque">Fatec Franca - Faculdade de Tecnologia de Franca Dr Thomaz Novelino</p>
        <p>Desenvolvimento de Software Multiplataforma: 2024 - 2026</p>
        <br>
        <h2>LÍNGUAS</h2>
        <p>Português</p>
        <p>Inglês avançado</p>
        <br>

        <div class="icon">
            <img src="img/mobile.png" class="rotate">
            <p>(16) 99997-1007</p>
        </div>

        <div class="icon">
            <a href="mailto:joaovitorluquetti@gmail.com">
                <img src="img/circle.png">
                <p>joaovitorluquetti@gmail.com</p>
            </a>
        </div>

        <div class="icon">
            <a href="https://www.linkedin.com/in/joao-luquetti/" target="_blank">
                <img src="img/linkedin.png" class="linkedin">
                <p>joao_luquetti</p>
            </a>
        </div>

        <div class="icon">
            <img src="img/location.png">
            <p>Franca - SP</p>
        </div>
    </div>

    <div class="direita">
        <div class="direita-exp">
            <h2>EXPERIÊNCIA</h2>
            <h4>Mercado8 | Agosto/2018 - Fevereiro/2019</h4>
            <p>Programador Full-Stack</p>
            <p>Desenvolvimento de web pages, e-commerce e marketplace. Utilizando HTML 5, CSS3, PHP, C# e Javascript</p>
            <h4>Centro Universitário Municipal de Franca | Fevereiro/2019 - Agosto/2019</h4>
            <p>Analista de Suporte</p>
            <p>Atendimento e manutenção de toda estrutura de computadores e rede da Universidade.</p>
            <h4>Estofados Elegance | Dezembro/2019 - Janeiro/2021</h4>
            <p>Gerente de Ecommerce</p>
            <p>Gerente de ecommerce de estofados. Realizava atendimento com clientes e fornecedores (B2C e B2B), realizava planejamento diárias para melhor logística e prazo de entrega<br><br>Integração entre o Bling e marketplaces (Mercado Livre, B2W, Americanas, MadeiraMadeira)</p>
            <h4>LuTech Vitaminas e Eletronicos LTDA | Janeiro/2021 - Dezembro/2023</h4>
            <p>Gerente de Ecommerce</p>
            <p>Gerente geral da empresa, cuido desde a importação até a entrega ao cliente<br><br>Responsável pela contabilidade e transações tanto com do cliente, quanto dos fornecedores<br><br>Responsável pelo planejamento da logistíca da empresa para melhor experiência do cliente<br><br>Responsável pelo atendimento dos clientes (SAC)</p>
        </div>
        <div class="direita-hab">
            <h2>HABILIDADES</h2>
            <p>Em linguagem de programação:</p>
            <div>
                <p>● C#</p>
                <p>● Javascript</p>
                <p>● PHP</p>
                <br>
            </div>
            <p>● Habilidades com Microsoft Excel, Word e Power Point</p>
            <p></p>
        </div>
    </div>
    </body>
    </html>
```

  - CSS 
```
      @import url('https://fonts.googleapis.com/css2?family=Dosis:wght@200..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Red+Hat+Display:ital,wght@0,300..900;1,300..900&family=Rubik+Mono+One&display=swap');

    .circle {
        background-color: black;
        border-radius: 50%;
        border: 10px solid green;
        width: 250px;
        height: 250px;
        overflow: hidden;
        position: relative;
        margin: 30px 0px 30px 75px;
        text-align: none !important;
    }
    
    .circle img {
        position: absolute;
        bottom: -40%;
        width: 100%;
    }
    
    body{
        display: flex;
        background-color: none;
        justify-content: center;
        align-items: center;
        font-family: "Red Hat Display";
        margin: 0;
        background-color: #f0f0f0;
    }
    
    .esquerda{
        flex: 1;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background-color: black;
        color: #f0f0f0;
        margin:0;
        display: flex;
        padding: 5%;
    }
    
    
    .destaque{
        border-bottom: 1px solid #f0f0f0;
        width: 390px;
    }
    
    .esquerda h3{
        color: green;
    }
    
    .esquerda h2{
        color: green;
    }
    
    .esquerda h1{
        color:#f0f0f0;
        font-size: 35px;
        align-items: center;
        justify-content: center;
        text-align: left;
    }
    
    .direita{
        display: flex;
        flex: 1.75;
        /* justify-content: center;
        align-items: center; */
        flex-direction: column;
        background-color: #f0f0f0;
        margin:0;
        padding: 5%;
    }
    
    .direita h2{
        border-bottom: 1px solid black;
        padding-bottom: 5px;
        width: 250px;
    }
    
    .icon{
        display: flex;
        align-items: center;
        margin-bottom: -15px;
    }
    
    .icon img{
        width: 25px;
        height: 25px;
    }
    
    .rotate{
        transform: rotate(-90deg);
    }
    
    .linkedin{
        background-color: green;
        align-items: center;
    }
    
    .icon p{
        align-items: center;
        padding-left: 5px;
    }
    
    .icon a{
        color: white;
        text-decoration: none;
        display: flex;
        text-align: center;
        justify-content: center;
        align-items: center;
        gap: 5px;
    }
```
  - Fotos:
    - Minha foto:
      <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/perfil.PNG" width="250px" />

    - Ícones:

    <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/mobile.png" width="50px" />
    <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/location.png" width="50px" />
    <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/circle.png" width="50px" />
    <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/linkedin.png" width="50px" />
    <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/icon.png" width="50px" />

## 📋 Print do site
   <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/print1.png" width="500px" />
   <img src="https://raw.githubusercontent.com/joaoluquetti/cv-versionado/main/img/print2.png" width="500px" />
