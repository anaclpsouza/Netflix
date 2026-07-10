# Netflix_flexbox

# Tarefa Prática – Clone da Página Inicial da Netflix

## Objetivo

Desenvolver uma página inspirada na tela inicial da Netflix utilizando **HTML5 e CSS3**, com foco na utilização de **Flexbox** para organização e alinhamento dos elementos.

---

## Requisitos da Página

### 1. Cabeçalho (Header)

O cabeçalho deve conter:

* Logo da plataforma
* Menu de navegação

  * Início
  * Séries
  * Filmes
  * Minha Lista
* Botão "Entrar"

**Todo o alinhamento deve ser realizado utilizando Flexbox.**

---

### 2. Banner Principal (Hero Section)

Criar uma seção principal contendo:

* Imagem de fundo
* Título de um filme ou série fictícia
* Descrição resumida
* Botão "Assistir"
* Botão "Mais Informações"

Os botões devem ficar alinhados lado a lado utilizando Flexbox.

---

### 3. Categorias de Filmes

Criar as seguintes categorias:

* Em Alta
* Ação
* Comédia
* Terror

Cada categoria deve possuir **6 cards de filmes**.

---

### 4. Cards dos Filmes

Cada card deve conter:

* Imagem do filme
* Nome do filme

Os cards devem ser organizados utilizando Flexbox.

---

### 5. Rodapé (Footer)

O rodapé deve conter:

* Redes sociais
* Links úteis
* Texto de direitos autorais

---

## Estrutura Esperada

```text
HEADER
---------------------------------------------------
LOGO                MENU                ENTRAR
---------------------------------------------------

HERO
---------------------------------------------------
          IMAGEM DE FUNDO

      Título do Filme

      Descrição

 [Assistir] [Mais Informações]
---------------------------------------------------

EM ALTA

[Poster] [Poster] [Poster] [Poster] [Poster] [Poster]

---------------------------------------------------

AÇÃO

[Poster] [Poster] [Poster] [Poster] [Poster] [Poster]

---------------------------------------------------

COMÉDIA

[Poster] [Poster] [Poster] [Poster] [Poster] [Poster]

---------------------------------------------------

TERROR

[Poster] [Poster] [Poster] [Poster] [Poster] [Poster]

---------------------------------------------------

FOOTER
```

---

## Requisitos Técnicos Obrigatórios

Durante o desenvolvimento, utilize obrigatoriamente os seguintes recursos do Flexbox:

* display: flex
* justify-content
* align-items
* flex-direction
* gap
* flex-wrap
* flex-grow
* margin: auto

---

## Responsividade

A página deve funcionar corretamente em:

* Desktop
* Tablet
* Smartphone

### No celular:

* O menu deve se reorganizar adequadamente.
* Os cards devem se ajustar ao tamanho da tela.
* Não deve existir rolagem horizontal desnecessária.

---

## Desafios Extras

1. Efeito de zoom nos cards ao passar o mouse.
2. Mudança de cor nos botões utilizando :hover.
3. Sombras nos cards utilizando box-shadow.
4. Menu fixo no topo da página.
5. Rolagem horizontal nas categorias.
6. Ícones utilizando Font Awesome.
7. Seção adicional "Continuar Assistindo".

Entregar uma pasta contendo:

* index.html
* style.css
* pasta de imagens (caso utilizada)
