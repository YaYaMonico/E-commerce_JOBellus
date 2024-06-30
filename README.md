<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!------ LINK CSS STYLE ------->
  <link rel="stylesheet" href="assets/css/style.css">
  <!------ FAVICON ------->
  <link rel="shortcut icon" href="assets/img/favicon/830da1b9d031a459d1fc38de3c90197c_tn-removebg-preview.png"
    type="image/x-icon">
  <!------ LINK FONTAWESOME ------->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
    integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
  <!----- LINK SLICK JS ------>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.css">
  <!--icon Dark-->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.0/font/bootstrap-icons.css" />
  <!-- SCRIPT JIVOCHAT -->
  <script src="//code.jivosite.com/widget/1YD6UYyWt8" async></script>
  <!----- SCRIPT - FEATHERICONS ----- -->
  <script src="https://unpkg.com/feather-icons"></script>

  <!-- Um script que será baixado em paralelo para analisar a página e 
       executado depois que a página terminar de analisar: -->
  <script src="assets/js/index.js" defer></script>

  <title>E-Ecommerce - Home</title>

</head>

<body>

  <!------ MENU ------->
  <header id="header" class="container header">
    <nav class="menu nav">
      <div class="divDaLogo">
        <img src="assets/img/backgrounds/logo.png" alt="logo" class="logoEcommerce">
      </div>

      <!-- MENU RESPONSIVO -->
      <ul class='list menuMobile' id="menuMobile" role="menuMobile">
        <li id="active-link-menu"><a href="/index.html">Home</a></li>
        <li><a href="E-commerce_JOBellus/ecommerce/produtos.html">Produtos</a></li>
        <li><a href="javascript:void(0)">Sobre-nós</a></li>
        <li><a href="javascript:void(0)">Contatos</a></li>
      </ul>


      <div class="configs-menu">
        <!---- SCROLL ABRE FECHA CARRINHO ---->
        <div class="config">
          <a>
            <i class="fas fa-shopping-bag" id="cart-btn"></i>
            <!-- Total de itens na sacolinha do carrinho -->
            <p id="cont-itens-carrinho" class="sacolinhaDark"></p>
          </a>
        </div>

        <!--ABERTURA DA DIV SISTEMA DE CARRINHO -->
        <div class="cardCarrinho-container" id="meuCarrinho">

          <section class="box-cart">

            <section class="description">

              <div class="produtos" style="width: 45%;">
                <p>Produtos</p>
              </div>

              <div style="width: 30%;">
                <p>Quantidade</p>
              </div>

              <div style="width: 20%;">
                <p>Preço</p>
              </div>

            </section>
            <!-- Abertura da div cart-item -->
            <div class="cart-item">

              <!-- Fechamento da div cart-item -->
            </div>

            <span id="totalFinal" class="total">
              <h2> Nenhum item escolhido </h2>
            </span>

            <button id="btnFinalizarCarrinho">
              <h2>Comprar</h2>
            </button>

          </section>
        </div>

        <!-- Email do usuario CONFIG -->
        <span id="user-email"></span>

        <!---- OPEN CONFIG ---->

        <div style="width: 18%;" class="config">
          <button type="button" onclick="Mudarestado('openConfig')">
            <a><i class="fas fa-cog"></i></a>
          </button>
        </div>

        <!--Abertura da Div openConfig-->
        <div id="openConfig" class="btn-config">

          <ul id="ul-OpenConfig">

            <li>
              <p>Minha Conta</p>
            </li>

            <li>
              <p>Pagamentos</p>
            </li>

            <li>
              <p>Direitos</p>
            </li>

            <!-- Config Tema Dark & Light -->
            <!--Abertura da Div ul-OpenConfig-->
            <div class="ul-OpenConfig">
              <input type="checkbox" name="chenge-theme" id="chenge-theme" />
              <label for="chenge-theme">

                <li id="btn-theme">

                  <p>Tema</p>

                  <i class="bi bi-sun">
                    <p>Light</p>
                  </i>

                  <i class="bi bi-moon">
                    <p>Dark</p>
                  </i>

                </li>

              </label>

              <!--Fechamento da Div ul-OpenConfig-->
            </div>

            <li>
              <p>Feedbacks</p>
            </li>

            <span id='li-sair'></span>
          </ul>

          <!--Fechamento da Div openConfig-->
        </div>

        <!--ABERTURA DA DIV SISTEMA DE CARRINHO -->
      </div>

      <!-- SISTEMA DE MENU RESPONSIVEL -->
      <div class="divMenuMobile">
        <button class="btn-menu" aria-label="Abrir Menu" aria-haspopup="true" aria-controls="menu" aria-expanded="false"
          style="color: var(--important-color)">Menu<span class="hamburger"></span>
        </button>
      </div>

    </nav>

  </header>

  <!-------- BANNER INICIAL -------->
  <main class="banner-initial">
    <figure>
      <div class="search-banner">
        <h4>
          Temos produto a pronta entrega
        </h4>
        <div>
          <input type="search" placeholder="Buscar produtos, marcas e muito mais...">
          <i class="fas fa-search"></i>
        </div>
        <div class="frete">
          <p>Frete Grátis em compras acima de <b>R$ 99,99</b></p>
        </div>
      </div>
    </figure>
  </main>
  <!----------- CATALOGUE ---------->
  <section class="catalogue-initial">

    <div class="titles-page">
      <h5>CATÁLOGO</h5>
    </div>

    <ul class="box-catalogue">

      <li>
        <figure>
          <img src="assets/img/projects/COMBO_SIAGE.png" alt="COMBO SIAGE">
        </figure>
        <figcaption>
          <div>
            <h1>Combo Siàge - Acelera o Crescimento:</h1>
            <h4>R$ 162,97</h4>
          </div>

          <section>
            <i data-produtoid="0" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>

      <li>
        <figure>
          <img src="assets/img/projects/PRATA.png" alt="PRATA">
        </figure>
        <figcaption>
          <div>
            <h1>Colar "Tenha Fé" de Prata</h1>
            <h4>R$ 149,90</h4>
          </div>

          <section>
            <i data-produtoid="1" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>

      <li>
        <figure>
          <img src="assets/img/projects/KIT_NATURA.png" alt="KIT NATURA">
        </figure>
        <figcaption>
          <div>
            <h1>Presente Natura Todo Dia</h1>
            <h4>R$ 114,90</h4>
          </div>

          <section>
            <i data-produtoid="2" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>

      <li>
        <figure>
          <img src="assets/img/projects/BATHBOMBS.png" alt="bathbombs">
        </figure>
        <figcaption>
          <div>
            <h1>Bath Bombs</h1>
            <h4>R$ 99,99</h4>
          </div>

          <section>
            <i data-produtoid="3" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>

      <li>
        <figure>
          <img src="assets/img/projects/top-carnaval.png" alt="TOP CARNAVAL">
        </figure>
        <figcaption>
          <div>
            <h1>Top Sexy de Prata c Zirconias</h1>
            <h4>R$ 119,99</h4>
          </div>

          <section>
            <i data-produtoid="4" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>


      <li>
        <figure>
          <img src="assets/img/projects/KITINSTANCE.png" alt="KIT INSTANCE">
        </figure>
        <figcaption>
          <div>
            <h1>Kit Instance Karité</h1>
            <h4>R$ 113,97</h4>
          </div>

          <section>
            <i data-produtoid="5" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>

      <li>
        <figure>
          <img src="assets/img/projects/ANEISSOLELUA.png" alt="ANEISSOLELUA">
        </figure>
        <figcaption>
          <div>
            <h1>Aneis 2 em 1 Brilho Celestial</h1>
            <h4>R$ 198,90</h4>
          </div>

          <section>
            <i data-produtoid="6" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>

      <li>
        <figure>
          <img src="assets/img/projects/KITACAI.png" alt="KIT ACAI">
        </figure>
        <figcaption>
          <div>
            <h1>Kit Instance Açaí e Bambu</h1>
            <h4>R$ 136,90</h4>
          </div>

          <section>
            <i data-produtoid="7" class="fas fa-shopping-cart"></i>
            <i class="fas fa-heart"></i>
            </div>
          </section>
        </figcaption>
      </li>
    </ul>

  </section>

  <!------ TIPOS DE PAGAMENTOS ----->
  <section class="payments">
    <div>

      <section class="none-payment">
        <h1>Melhor forma de pagar</h1>
        <p>Fácil, prático e divertido</p>
      </section>

      <ul>
        <li>
          <i class="far fa-credit-card"></i>
          <section>
            <h3>Cartão</h3>
            <p>Em até 10x sem juros</p>
          </section>
        </li>

        <li>
          <i class="fas fa-barcode"></i>
          <section>
            <h3>Boleto</h3>
            <p>Escaneie na hora</p>
          </section>
        </li>

        <li>
          <i class="fas fa-qrcode"></i>
          <section>
            <h3>Via Pix</h3>
            <p>000.000.000-00</p>
          </section>
        </li>
      </ul>

    </div>

  </section>

  <!------------ SEE ALL ----------->
  <section class="see-all">
    <div class="see-all-left">
      <h5>Produtos elegantes</h5>
      <p>Para te fazer ainda mais confiante em 2024</p>

      <button class="btn-all">
        Ver todos
      </button>
    </div>

    <div class="see-all-image">

    </div>
  </section>

  <!-------------- FOOTER ---------------->
  <footer>
    <div class="menu-footer">
      <div class="media">
        <div class="media-title">
          <a href="">
            <h2><img src="assets/img/backgrounds/logo.png" alt="Logo E-commerce"></h2>
          </a>
        </div>

        <div class="social-media">
          <a href=""><i class="fa-brands fa-facebook-f"></i></a>
          <a href=""><i class="fa-brands fa-instagram"></i></a>
          <a href=""><i class="fa-brands fa-twitter"></i></a>
        </div>
      </div>
      <div class="shop">
        <h3>Shop</h3>
        <ul>
          <li><a href="#">Sobre Nós</a></li>
          <li><a href="#">Contato</a></li>
          <li><a href="#">Localização</a></li>
          <li><a href="#">FAQ</a></li>
        </ul>
      </div>

      <div class="links">
        <h3>Links</h3>
        <ul>
          <li><a href="#">Itens Exclusivos</a></li>
          <li><a href="#">Verão</a></li>
          <li><a href="#">Outono</a></li>
          <li><a href="#">Inverno</a></li>
        </ul>
      </div>

      <div class="contact">
        <h3>Contato</h3>
        <ul>
          <li><a href="tel:+55 000000-0000">+55 00  000000-0000</a></li>
          <li><a href="ecommerce@gmail.com">ecommerce@gmail.com</a></li>
          <li><a href="#">CB - BH - MG</a></li>
        </ul>
      </div>

    </div>

    <div class="copyright">
      <p>Termos, acordos e Política de Privacidade.</p>
      <p>© 2024 Dev Project. Todos os direitos reservados.</p>
    </div>
  </footer>

  <!-------------- SCRIPT SLICK JS ------------------->
  <script src="/assets/js/scriptCarrinho.js"></script>
  <script src="assets/js/menuMobile.js"></script>

  <!-- SWEETALERT PERSONALIZADO -->
  <script src="//cdn.jsdelivr.net/npm/sweetalert2@11"></script>

  <script src="https://unpkg.com/scrollreveal"></script>
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"
    integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>

  <!------ SCRIPT INDEX JS ------->
</body>

</html>
