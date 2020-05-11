# aula_html5_css3
Aula de como usar HTML5 e CSS3
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="utf-8">
        <title>Minha página</title>
    </head>

    <body>
        <h1>Minha primeira página</h1>
        <nav>
            <ul type="square">         //cria menus
                <li><a href="#Serviços">Serviços</a></li>   //a tag <a href= com # define um hiperlink>
                <li><a href="#Produtos">Produtos</a></li>
                <li><a href="#Contato">Contato</a></li>
            </ul>
        </nav>
        <header>
            <p>Treinando a criação de páginas HTML com CSS3</p>   cabeça da página, abaixo de títulos
        </header>

        <section id="Serviços">   //cria seções na página
            <h2>SERVIÇOS</h2>
            <p>Oferecemos os melhores serviços no desenvolvimento de sites e aplicativos</p>
            <div>
                <img src="img/impacto.jpg"/>
            </div>
        </section>

        <section id="Produtos">
            <h2>PRODUTOS</h2>
            <p>Nossos clientes ficaram muito satisfeitos com nossos serviços</p>
            <img src="img/virus.jpg" width="500px"/>    //adiciona uma imagem em uma seção definida e pode alterar o tamanho
        </section>

        <section id="Contato">
            <h2>CONTATO</h2>
            <p>Entre em contato conosco</p>
            <p><a href="https://media1.tenor.com/images/01106f38e5c6a006af02eda6e2a17f6b/tenor.gif?itemid=11228252" target="_blank">    //indica que o link será aberto em uma nova guia
                <img src="img/clique.jpg" width="500px"</a></p>  //adiciona um link a uma imagem
        </section>
    
        <footer>      //usado para o redapé
            <p><b>Desenvolvido por<i> Rafael Lopes</i></b></p>    //define o termo dentro de <b></b> em negrito e <i></i> em itálico
        </footer>
    </body>

</html>