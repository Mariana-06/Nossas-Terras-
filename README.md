# Nossas-Terras-
<html>
    <head>
        <title>Terras do Nosso Mundo</title>
        <link rel="stylesheet" href="estilo.css">
    </head>
    <body>
        <div id="img_fundo">
          <h1 id="tit_principal">Terras do Nosso Mundo:</h1>
          <h2 id="sub_principal">Acabar com a fome e promover uma Agricultura Sustentável.</h2>
        </div>
        <section class="destaque" id="projeto">

            <div class="coluna">
               <iframe width="100%" height="315" src="https://www.youtube.com/embed/IvS2cQYzSto" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>

            <div class="coluna">
               <h3 id="tit_2" class="centralizado">Finalidade do Projeto:</h3>
               <p class="justificado">Esse Projeto foi idealizado pela ONU,no ano de 2015 o projeto tem o nome "Objetivos do Desenvolvimento Sustentável" essa idealização foi feita com o propósito de termos um mundo melhor até o ano de 2030.</p>
               <p class="justificado">A ODS de ênfase deste site é a ODS2 (Fome Zero e Agricultura Sustentável).</p>
               <p class="justificado">Como explicado no vídeo exibido na plataforma do youtube pela Unesco a ODS2 tem um propósito de acabar com a fome (daquelas pessoas que não tenha uma condição adequada para o sustento de sua família), e também promover uma Agricultura Sustentável (também conhecida como Agricultura Familiar), que tem a sustentabilidade do meio ambiente mais preservada. Como por exemplo alimentos ôrganicos.</p>
            </div>

            </section>
            <section id="saiba_mais">
                <h3 id="tit_2" class="centralizado">Saiba Mais...</h3>

                <div class="colunatres">
                   <img class="icones" src="logos/logo3.png" >
                   <h4 class="centralizado">Sustentabilidade</h4>
                   <p class="centralizado">O que precisamos para ter mais sustentabilidadeno mundo?</p>
                </div> 

                <div class="colunatres">
                  <img class="icones" src="logos/logo3.png">
                  <h4 class="centralizado">Meio Ambiente</h4>
                  <p class="centralizado">O que o Meio Ambiente em nossas Vidas?</p>
                </div>

                <div class="colunatres">
                   <img class="icones" src="logos/logo3.png">
                   <h4 class="centralizado">Fome Zero e Agricultura Sustentável</h4>
                   <p class="centralizado">Afinal como funciona?</p>
                </div>

            </section>
            <section class="destaque" id="Curiosidades">
                  <h3 id="tit_2" class="centralizado">Curiosidades</h3>
                  <p>Saiba como funciona o sistema da ODS!</p>
                  <img class="site" id="ods" src="imagens/ods.png">
                  <h4>Imagem representativa de todos os objetivos da ODS.</h4>
            </section>
            <section id="sobre">
                 <h3 id="tit_2" class="centralizado">Minha biografia</h3>
                 <div class="coluna4">
                 <p class="justificado">Mariana C. de Siqueira</p>
                 <p class="justificado">Meu nome é Mariana tenho 16 anos, sou de Goiânia - Goiás. Entrei em um progama chamado: "Meu Primeiro Site" da JA Goiás com parceria com a Microsoft, proporcionando a mim,um curso em que eu deveria produzir um site do Zero com um dos temas da ODS, o desafio foi lançado e executado com êxodo e excelência. Com auxilio de monitores e professores da rede JA, fiz esse site com base nas informações e aprendizados repassados pelos mesmos. E aqui vai meu agradecimentos a todos da equipe JA Goiás! </p>
                </div>
                <div class="coluna4">
                 <img class="site" id="eu" src="imagens/eu2.jpeg">
                </div>
                </section>
    </body>
</html>



#html,body{
    margin: 0%;
}
#img_fundo{
    background: url("imagens/capa.jpg");
    height: 100%;
    text-align: center;
    background-size: cover;
}
#tit_principal{
    padding-top: 15%;
    color: white;
    font-family: 'Times New Roman', Times, serif;
    font-style: italic;
    font-size: 350%;
}
#sub_principal{
    color: white;
    font-family: 'Times New Roman', Times, serif;
    font-style: italic;
    font-size: 250%;
    border-top: solid white 3px;
    margin-left: 20%;
    margin-right: 20%;
}
#projeto{
    background-color: palegoldenrod;
    width: 100%;
    height: 60%;
}
#saiba_mais{
    width: 100%;
    height: 70%;
    padding-top: 5%;
    padding-bottom: 5%;
}
.icones{
    width: 10%
    center;
}
#section{
    padding: 20px;
    float: left;
}
.destaque{
    background-color: palegoldenrod;
}
.site{
    width:50%
}
.coluna{
    float: left;
    padding: 10 5%;
    padding-top: 5%;
    position: relative;
    width: 40%;
}
.justificado{
    text-align: justify;
}
.centralizado{
    text-align: center;
}
.colunatres{
    float: left;
    padding: 10 5%;
    padding-top: 5%;
    position: relative;
    width: 22,5%;
}
#tit_2{
    font-style: italic;
    font-size: 250%;
    padding-top: 0%;
}
.coluna4{
    float: left;
    padding: 5 0%;
    padding-top: 5%;
    position: relative;
    width: 22,5%;
}
