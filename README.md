# 7DaysOfCodePerfilLinkedin
Desafio para fortalecer aprendizado no desenvolvimento de HTML e CSS

Criação da interface da tela de perfil do linkedin (dark mode).

# Barra de navegação

## Inclui um input de buscas e os links de navegação.
![img](https://i.imgur.com/DRqSfxG.png)

É possível perceber que o conteúdo não é exatamente centralizado, estando um pouco mais à esquerda. Para reproduzir isso de modo que se aproximasse do original foi necessário atribuir margen à esquerda.

Os ícones foram retirados do https://fonts.google.com/icons.
Utilizei um único ícone da categoria Material Icons (apps), todos os outros utilizando a categoria Material Symbols.

```
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

# Seção Followers

## Cards de pessoas que nos seguem

Esta seção é composta por vários cards com o nome e sobrenome das pessoas que estão em nossa rede e que também viram certo conteúdo.
Nos cards há um resumo do perfil da pessoa: Título, cargo e tecnologias, além de algum texto relacionado a suas habilidades.

![img](https://i.imgur.com/x1sB4iR.png)

# Seção Pessoas que talvez você conheça

## Cards de sugestão de pessoas à nossa rede.

É construída exatamente igual à seção anterior (Pessoas que também viram).

![img](https://i.imgur.com/fhC4RYG.png)

OBS.: As duas seções acima foram construídas numa tag aside.

# Seção Principali <main>
  
  ## Informações do Perfil
  
  ![Imgur](https://i.imgur.com/xtijUw3.png)
  
  Seção construída como cartão de visita do usuário.
  * Um resumo de suas habilidades
  * Indentificação da empresa que trabalha
  * Instituição de ensino que estuda(ou)
  * Localização
  * Possibilidade de enviar mensagem para a pessoa por meio do botão Mensagem
  * Mais informações relacionadas à pessoa pelo botão 'Mais'
  
  ## Destaques
  ![Imgur](https://i.imgur.com/h0d92QO.png)
  
  Seção que visa aprensentar as publicações resentes do usuário.
  
  * Título da publicação
  * Legenda da publicação
  * Imagem ou Conteúdo da publicação
  * Quantidade de curtidas
  * Quantidade de comentários desta publicação
  
