<!DOCTYPE html>

<html>
<head>
  <meta charset="UTF-8">
  <title>Desktop mode</title>
  
      <style>
          body {
            background-color: #141414;
            color: white; /*Isso aqui define o estilo do negócio*/
            font-family: Arial;
          }
  
          .games {
            display: flex;
            gap: 20px;
            overflow-x: auto;
            padding: 20px;

            
          }

          .card {
            background-color: #2b2b2b;
            padding: 20px;
            border-radius: 55px; /*Se eu colocar um "game" dentro de uma <div class= "#"> vai ficar com um estilo de card */
            margin-bottom: 45px;
            box-shadow: 0px 0px 10px black;
            
            min-width: 500px;    /* largura fixa do card */
            flex-shrink: 0;      /* impede que encolha */
        }
  
          img {
            width: 850px; /*Essa budega faz o formato da imagem*/
            border-radius: 24px;
            display: block;
            height: 450px;
            object-fit: cover; 
            
         }
         
        h1 {
            text-align: center;
            font-size: 95px;
            color: #FFA500;
        }
      
        h2 {
            text-align: center;
            font-size: 75px;
            background-color: grey; #808080:
        }
  
        h3 {
            font-size: 48px;
            color: #C0C0C0;
            text-align: center;
        }
        .movie {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .movie img {
            width: 450px;
            height: 700px;
            border-radius: 24px;
            object-fit: cover;
            margin-right: auto;
        }

        button {
            color: black;
     
            width: 750px;
            height: 120px; /*E isso define o tamanho do botão*/
          
            display: block;        /* Transforma o botão em bloco */
            margin-left: auto;     /* Empurra para a direita */
            margin-right: auto;    /* Empurra para a esquerda */
            text- align: center;
    
            font-size: 40px;      /* tamanho da letra */
            font-weight: bold;    /* negrito */
            font-family: Arial;   /* fonte */
            color: black;         /* cor do texto */
            
        }
        button:hover {
            transform: scale(1.0); /*E isso aqui dá uma animaçãozinha no botão*/
            transition: 0.2s;
        }
        h4 {
            font-size: 24px;
            color: #C0C0C0;
            transform: translateX(650px);
        }
        p {
            text-align: center;
            font-size: 48px;
            color: #C0C0C0;
        }
        .galaxy {
            border-left: 15px solid #FF0000;
        }
        .minecraft {
            border-left: 15px solid #008000;
        }
        .bros {
            border-left: 15px solid #FF0000;
        }
        gif {
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 150px;
        }
        .simbolo {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
        }

        .simbolo img {
            width: 150px;
            height: 150px;
            object-fit: contain;
        }
      </style>
</head>
      <body>
        <div class="card">
            <h1>STEAM HUB</h1>
            <p>Jogos que foram adaptados para filmes</p>
            <div class="simbolo">
                <img src="https://images.icon-icons.com/622/PNG/512/playstation-logo_icon-icons.com_57094.png" alt="playstation">
                <img src="https://img.icons8.com/?size=512&id=12504&format=png" alt="xbox">
                <img src="https://img.icons8.com/?size=512&id=XaIQdSh4y3F9&format=png" alt="nintendo">
                <img src="https://www.iconpacks.net/icons/2/free-icon-mobile-phone-2636.png" alt="mobile">
                <img src="https://uxwing.com/wp-content/themes/uxwing/download/computers-mobile-hardware/pc-icon.png" alt="pc">
            </div>
        </div>
        
        <div class="games">
          <div class="card galaxy">
          <h2 style="color: #FF0000">Super Mário Galaxy o filme</h2>
            <a href="https://www.nintendo.com/pt-br/store/products/super-mario-galaxy-switch/" target="_blank">
                <br><img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000104187/7ccc1c07ba3995da1dbd7320e726e063eaba9445a5741281d19c3b8fb1c144df" alt="Super Mário Galaxy game banner">
            </a>
            <h4>Jogo adaptado</h4>
            <h3>Plataforma 3D | Ação | Aventura</h3>
            <a href="https://www.nintendo.com/pt-br/store/products/super-mario-galaxy-2-switch/?srsltid=AfmBOoqTIjxtQ3lKQcQR5bB4u0sCRJQZA_OLGn_hL3xwnMHpAH-ay1E-" target="_blank">
              <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000104192/5731782c9e89d2f492b44f1445f5df3d65660cdf75fe4f47a17e2bed7f82f99e" alt="super mario galaxy 2 game banner">
            </a>
            <h4>Jogo adaptado</h4>
            <h3>Aventura espacial | Plataforma 3D | Ação</h3>
            <a href="https://www.nintendo.com/pt-br/store/products/super-mario-odyssey-switch/" target="_blank">
                    <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000001130/c42553b4fd0312c31e70ec7468c6c9bccd739f340152925b9600631f2d29f8b5" alt="super mario odyssey game banner">
            </a>
            <h4>Jogo adaptado</h4>
            <h3>Mundo aberto | Plataforma 3D | Aventura</h3>
            <a href="https://www.nintendo.com/pt-pt/Jogos/Jogos-para-a-Wii-U/Super-Mario-Maker-892704.html?srsltid=AfmBOoqisz2NJFahiKSQJguGQjKrWBLVNe5HDBgI3lx-QfOeJvWpDWZw" target="_blank">
              <img src="https://www.nintendo.com/eu/media/images/10_share_images/games_15/wiiu_14/SI_WiiU_SuperMarioMaker_v01_image1600w.jpg" alt="super mario maker game banner">
            </a>
            <h4>Jogo adaptado</h4>
            <h3>Quebra-cabeça | Sandbox | Speedrun</h3>
            <div class="movie img">
                <br><img src="https://static.wixstatic.com/media/ee5d2f_0d42f6f0c0e14b9094f0971b4f17aa13~mv2.jpg/v1/fill/w_497,h_789,al_c,lg_1,q_85,enc_avif,quality_auto/ee5d2f_0d42f6f0c0e14b9094f0971b4f17aa13~mv2.jpg" alt="super mario galaxy: o filme banner">
                <a href="https://www.imdb.com/pt/title/tt28650488/" target="_blank"><br>
                    <br><button style="background-color: #FF0000">Sobre o filme ></button>
                </a>               
            </div>
          </div>            
        <div class="card minecraft">
            <h2 style="color: #008000">Um filme Minecraft</h2>
                <a href="https://www.minecraft.net/pt-pt" target="_blank">
                    <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000000964/a28a81253e919298beab2295e39a56b7a5140ef15abdb56135655e5c221b2a3a" alt="minecraft game banner">
                </a>
                <h4>Jogo adaptado</h4>
                <h3>Aventura | Sandbox | Ação | Sobrevivência </h3>
                <a href="https://www.minecraft.net/pt-br/about-dungeons" target="_blank">
                  <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000021401/59686225dba24636062a421593effdb4fe136bbfd67b11c621fe92ed36a65734" alt="minecraft dungeons game banner">
                </a>
                <h4>Jogo adaptado</h4>
                <h3>RPG de ação | Casual | Dungeon Crawler</h3>
                <a href="https://www.minecraft.net/pt-br/about-legends" target="_blank">
                  <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000033696/be89eb9c1c6a57cf58e8d14b03d26b4c42d988e02c082fd0fe368417c43b959e" alt="minecraft legends game banner">
                </a>
                    <h4>Jogo adaptado</h4>
                    <h3>Competitivo | RPG | Estratégico</h3>
          <div class="movie img">
                    <br><img src="https://static.wikia.nocookie.net/dublagem/images/2/28/Um_filme_minecraft_poster_brasileiro.jpg/revision/latest?cb=20250406151734&path-prefix=pt-br" alt="um filme minecraft banner"><br>
                    <a href="https://www.imdb.com/pt/title/tt3566834/" target="_blank">
                        <br><button style="background-color: #008000">Sobre o filme ></button>
                    </a>
              <div class="gif">
                    <img src="https://media.tenor.com/ozw2st3MO9UAAAAi/elgatitolover-elgatitoloves.gif" alt="gif">
              </div>
          </div>
        </div>
          <div class="card bros">
            <h2 style="color: #FF0000">Super Mário Bros: O filme</h2>
                <a href="https://www.nintendo.com/pt-pt/Jogos/NES/Super-Mario-Bros-803853.html?srsltid=AfmBOooGXDqpB11tZ60sdAJ_qtreJ3HwCgwZwiE-2Dy5ggqe9fqVkuno" target="_blank">
                    <img src="https://www.nintendo.com/eu/media/images/10_share_images/games_15/virtual_console_nintendo_3ds_7/SI_3DSVC_SuperMarioBros_image1600w.jpg" alt="super mario bros 1985 game banner">
                </a><br>       
            <h4>Jogo adaptado</h4>
            <h3>Plataforma 2D | Arcade | Ação</h3>
            <a href="https://www.nintendo.com/pt-br/store/products/super-mario-odyssey-switch/" target="_blank">
                    <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000001130/c42553b4fd0312c31e70ec7468c6c9bccd739f340152925b9600631f2d29f8b5" alt="super mario odyssey game banner">
            </a><br>
            <h4>Jogo adaptado</h4>
            <h3>Mundo aberto | Plataforma 3D | Aventura</h3>
                <a href="https://www.nintendo.com/pt-pt/Jogos/Portal-Nintendo/Portal-Donkey-Kong/Portal-Donkey-Kong-846642.html?srsltid=AfmBOoqFvSIEeTuRFGWdwx1BJizqVY1_HrVMaEBO0tKC1JM9NuxJo0uB" target="_blank">
                    <img src="https://www.nintendo.com/eu/media/images/other_22/character_hubs/donkey_kong/2x1_Other_CharactersHub_DonkeyKong_image1600w.jpg" alt="donkey kong games banner">
                </a><br>
            <h4>Jogo adaptado</h4>
            <h3>Puzzle | Aventura | Ação | Plataforma 2D</h3>
            <a href="https://www.nintendo.com/pt-br/store/products/mario-kart-8-deluxe-switch/?srsltid=AfmBOorGidfa6qarcazbxyVJ_9vUUwXiUuvBd_KiVBwDVoQaXZLFIE2j" target="_blank">
                    <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000000153/de697f487a36d802dd9a5ff0341f717c8486221f2f1219b675af37aca63bc453" alt="game banner">
            </a>
                <h4>Jogo adaptado</h4>
                <h3>Corrida | Party game | Battle mode</h3>
                <hr>
            <div class="movie img">
                    <br><img src="https://leiturafilmica.com.br/wp-content/uploads/2023/04/super-mario-bros-o-filme-poster.jpg" alt="super mario bros o filme banner"><br>
                        <a href="https://www.imdb.com/pt/title/tt6718170/" target="_blank">
                            <br><button style="background-color: #FF0000">Sobre o filme ></button>
                        </a>
            </div>
          </div>
        </div>
      </body>
</html>

