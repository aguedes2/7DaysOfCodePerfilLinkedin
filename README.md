# 7DaysOfCodePerfilLinkedin
Desafio para fortalecer aprendizado no desenvolvimento de HTML e CSS

Criação da interface da tela de perfil do linkedin (dark mode).

# Barra de navegação

## Inclui um input de buscas e os links de navegação.
![img](https://i.imgur.com/DRqSfxG.png)

É possível perceber que o conteúdo não é exatamente centralizado, estando um pouco mais à esquerda. Para reproduzir isso de modo que se aproximasse do original foi necessário atribuir margen à esquerda.

Os ícones foram retirados do https://fonts.google.com/icons.
Utilizei um único ícone da categoria Material Icons (apps), todos os outros utilizando a categoria Material Symbols.

<details>
<summary>Clique aqui para exibir o código HTML</summary>
```~~~HTML
  <header id="header">
      <nav class="nav-container">
        <div class="nav-container-icon">
          <a class="nav-icone-link" href="#">
            <img
              src="imgs/linkedin.svg"
              alt="logo linkedin"
              width="34"
              height="34"
            />
          </a>
          <div class="input">
            <span class="material-symbols-outlined">search</span>
            <input type="search" placeholder="Pesquisar" />
          </div>
        </div>

        <div class="icones">
          <div class="icones-icone">
            <a class="nav-icone-link" href="#">
              <span class="material-symbols-outlined">home</span>
              <span class="icone-span">inicio</span>
            </a>
          </div>
          <div class="icones-icone">
            <a class="nav-icone-link" href="#">
              <span class="material-symbols-outlined">group</span>
              <span class="icone-span">minha rede</span>
            </a>
          </div>
          <div class="icones-icone">
            <a class="nav-icone-link" href="#">
              <span class="material-symbols-outlined">business_center</span>
              <span class="icone-span">vagas</span>
            </a>
          </div>
          <div class="icones-icone">
            <a class="nav-icone-link" href="#">
              <span class="material-symbols-outlined">sms</span>
              <span class="icone-span">mensagem</span>
            </a>
          </div>
          <div class="icones-icone">
            <a class="nav-icone-link" href="#">
              <span class="material-symbols-outlined">notifications</span>
              <span class="icone-span">notificacoes</span>
            </a>
          </div>
          <div class="divisao"></div>

          <div class="icones-icone">
            <a class="nav-icone-link" href="#">
              <span class="material-icons">apps</span>
              <span class="icone-span">solucoes</span>
            </a>
          </div>
        </div>
      </nav>
    </header>
```
</details>

***

# Seção Followers

## Cards de pessoas que nos seguem

Esta seção é composta por vários cards com o nome e sobrenome das pessoas que estão em nossa rede e que também viram certo conteúdo.
Nos cards há um resumo do perfil da pessoa: Título, cargo e tecnologias, além de algum texto relacionado a suas habilidades.

<center>
  ![img](https://i.imgur.com/x1sB4iR.png)
</center>

<details>
  <summary>Clique para ver o código do card</summary>
  ```~~~HTML
  <div class="pessoas-viram">
          <h1 class="cabecalho-card">As pessoas que também viram</h1>
          <div class="follower-card">
            <a href="#" class="btn-img"><img src="imgs/user1.png" alt="" /></a>
            <div>
              <h2>Nome e sobrenome</h2>
              <p>Título, Cargo e tecnologias. Lorem ipsum Dolor sit Amet</p>
              <button>Enviar mensagem</button>
            </div>
          </div>

          <div class="follower-card">
            <a href="#" class="btn-img"><img src="imgs/user5.png" alt="" /></a>
            <div>
              <h2>Nome e sobrenome</h2>
              <p>Título, Cargo e tecnologias. Lorem ipsum Dolor sit Amet</p>
              <button>Enviar mensagem</button>
            </div>
          </div>
          <div class="follower-card">
            <a href="#" class="btn-img"><img src="imgs/user3.png" alt="" /></a>
            <div>
              <h2>Nome e sobrenome</h2>
              <p>Título, Cargo e tecnologias. Lorem ipsum Dolor sit Amet</p>
              <button>Enviar mensagem</button>
            </div>
          </div>
          <div class="follower-card">
            <a href="#" class="btn-img"><img src="imgs/user2.png" alt="" /></a>
            <div>
              <h2>Nome e sobrenome</h2>
              <p>Título, Cargo e tecnologias. Lorem ipsum Dolor sit Amet</p>
              <button>Enviar mensagem</button>
            </div>
          </div>
          <div class="follower-card">
            <a href="#" class="btn-img"><img src="imgs/user4.png" alt="" /></a>
            <div>
              <h2>Nome e sobrenome</h2>
              <p>Título, Cargo e tecnologias. Lorem ipsum Dolor sit Amet</p>
              <button>Enviar mensagem</button>
            </div>
          </div>
        </div>
  ```
</details>

# Seção Pessoas que talvez você conheça

## Cards de sugestão de pessoas à nossa rede.

É construída exatamente igual à seção anterior (Pessoas que também viram).

<center>![img](https://i.imgur.com/fhC4RYG.png)</center>

OBS.: As duas seções acima foram construídas numa tag aside.
___
___
# Seção Principali <main>
  
  ## Informações do Perfil
  
  <center>![Imgur](https://i.imgur.com/xtijUw3.png)</center>
  
  Seção construída como cartão de visita do usuário.
  * Um resumo de suas habilidades
  * Indentificação da empresa que trabalha
  * Instituição de ensino que estuda(ou)
  * Localização
  * Possibilidade de enviar mensagem para a pessoa por meio do botão Mensagem
  * Mais informações relacionadas à pessoa pelo botão 'Mais'
  ***
  ## Destaques
  <center>![Imgur](https://i.imgur.com/h0d92QO.png)</center>
  
  Seção que visa aprensentar as publicações resentes do usuário.
  
  * Título da publicação
  * Legenda da publicação
  * Imagem ou Conteúdo da publicação
  * Quantidade de curtidas
  * Quantidade de comentários desta publicação
  
