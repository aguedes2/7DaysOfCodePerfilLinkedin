# 7DaysOfCodePerfilLinkedin

Desafio para fortalecer aprendizado no desenvolvimento de HTML e CSS

Criação da interface da tela de perfil do linkedin (dark mode).

# Barra de navegação

## Inclui um input de buscas e os links de navegação.

![Imgur](https://i.imgur.com/DRqSfxG.png)

É possível perceber que o conteúdo não é exatamente centralizado, estando um pouco mais à esquerda. Para reproduzir isso de modo que se aproximasse do original foi necessário atribuir margen à esquerda.

Os ícones foram retirados do https://fonts.google.com/icons.
Utilizei um único ícone da categoria Material Icons (apps), todos os outros utilizando a categoria Material Symbols.

---

# Seção Followers `<aside>`

## Cards de pessoas que nos seguem

Esta seção é composta por vários cards com o nome e sobrenome das pessoas que estão em nossa rede e que também viram certo conteúdo.
Nos cards há um resumo do perfil da pessoa: Título, cargo e tecnologias, além de algum texto relacionado a suas habilidades.

![Imgur](https://i.imgur.com/x1sB4iR.png)

# Seção Pessoas que talvez você conheça

## Cards de sugestão de pessoas à nossa rede.

É construída exatamente igual à seção anterior (Pessoas que também viram).

![Imgur](https://i.imgur.com/fhC4RYG.png)

OBS.: As duas seções acima foram construídas numa tag aside.

---

# Seção Principal `<main>`

## Informações do Perfil

![Imgur](https://i.imgur.com/xtijUw3.png)

Seção construída como cartão de visita do usuário.

- Um resumo de suas habilidades
- Indentificação da empresa que trabalha
- Instituição de ensino que estuda(ou)
- Localização
- Possibilidade de enviar mensagem para a pessoa por meio do botão Mensagem
- Mais informações relacionadas à pessoa pelo botão 'Mais'

## Destaques

![Imgur](https://i.imgur.com/h0d92QO.png)

Seção que visa aprensentar as publicações resentes do usuário.

- Título da publicação
- Legenda da publicação
- Imagem ou Conteúdo da publicação
- Quantidade de curtidas
- Quantidade de comentários desta publicação

---

## Atividades

![Imgur](https://i.imgur.com/eXyZV6B.png)

Seção atividades, mostra as últimas atividades do usuário.
**Também desenvolvido em forma de cards**
Desta vez os cards estão alinhados dispostos em coluna.

---

## Experiências

![Imgur](https://i.imgur.com/OFRlonc.png)

Seção que visa apresentar um curriculo resynudi do usuário.

---

## Formação acadêmica

![Imgur](https://i.imgur.com/AJa3TlG.png)
Histórico escolar do usuário.

---

## Idiomas

![Imgur](https://i.imgur.com/ErKyIro.png)

Relação do(s) dioma(s) falado(s) pelo usuário.

---

_Próximo passo:_ _refatorar arquivos de estilo pensando na manutenibilidade._
