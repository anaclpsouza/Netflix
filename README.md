# Netflix_flexbox

# Tarefa Prática – Clone da Página Inicial da Netflix

## Objetivo

Desenvolver uma página inspirada na tela inicial da Netflix utilizando **HTML5 e CSS3**, com foco na utilização de **Flexbox** para organização e alinhamento dos elementos.

---

## Requisitos da Página

# 1. Página Inicial

### 1.1 Header

Criar um cabeçalho contendo:

* Logo da plataforma
* Menu de navegação
* Botão "Entrar"

O header deve utilizar **Flexbox** para organizar os elementos.

---

### 1.2 Banner Principal (Hero Section)

Criar uma seção principal contendo:

* Imagem de fundo
* Título de um filme ou série fictícia
* Descrição resumida
* Botão "Assistir"
* Botão "Mais Informações"

Os botões devem ficar alinhados lado a lado utilizando Flexbox.

---

### 1.3 Categorias de Filmes

Criar as seguintes categorias:

* Em Alta
* Ação
* Comédia
* Terror

Cada categoria deve possuir **6 cards de filmes**.

---

### 1.4 Cards dos Filmes

Cada card deve conter:

* Imagem do filme
* Nome do filme

Os cards devem ser organizados utilizando Flexbox.

Ao passar o mouse sobre um card, aplicar um efeito visual utilizando `:hover`.

---

### 1.5 Rodapé (Footer)

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

# 2. Página de Login

### 2.1 Estrutura da Página

Criar uma página de login contendo:

* Logo da plataforma
* Título "Entrar"
* Campo de e-mail
* Campo de senha
* Botão "Entrar"
* Checkbox "Lembrar de mim"
* Link "Esqueceu a senha?"
* Link "Ainda não possui uma conta?"

---

### 2.2 Formulário

Criar um formulário utilizando HTML semântico.

O formulário deverá conter:

* `label`
* `input`
* `button`

Os campos deverão possuir estilos personalizados utilizando CSS.

---

### 2.3 Layout

O formulário deverá ficar centralizado horizontal e verticalmente na página.

Utilizar **Flexbox** para realizar o alinhamento.

O fundo da página deverá possuir:

* Cor escura
* Imagem ou gradiente
* Overlay para melhorar o contraste

---

### 2.4 Botão Entrar

O botão deverá possuir:

* Cor de destaque
* Texto "Entrar"
* Efeito `:hover`
* Transição utilizando `transition`

O botão deverá direcionar para a página de escolha de perfil.

---

## Estrutura Esperada

```text
---------------------------------------------------
                    LOGO
---------------------------------------------------

                 ENTRAR

          [ E-mail                  ]

          [ Senha                   ]

          [        ENTRAR           ]

          □ Lembrar de mim

          Esqueceu sua senha?

          Ainda não possui uma conta?

---------------------------------------------------
                    FOOTER
---------------------------------------------------
```

---

# 3. Página de Escolha de Perfil

### 3.1 Título

Criar um título centralizado:

**"Quem está assistindo?"**

---

### 3.2 Perfis

Criar pelo menos **4 perfis**.

Cada perfil deverá conter:

* Imagem/avatar
* Nome do perfil

Sugestões:

* João
* Maria
* Pedro
* Infantil

---

### 3.3 Cards dos Perfis

Os perfis deverão ser organizados lado a lado utilizando **Flexbox**.

Cada perfil deverá possuir:

* Imagem quadrada ou circular
* Nome abaixo da imagem
* Efeito `:hover`

Ao passar o mouse sobre o perfil:

* A imagem deverá receber destaque
* O nome poderá alterar sua aparência
* O card poderá receber uma borda

---

### 3.4 Gerenciamento de Perfis

Adicionar um botão ou link:

**"Gerenciar perfis"**

O elemento deverá fazer parte da composição visual da página.

---

## Estrutura Esperada

```text
---------------------------------------------------

              QUEM ESTÁ ASSISTINDO?

       [Avatar]   [Avatar]   [Avatar]   [Avatar]

        João       Maria      Pedro      Infantil


               [Gerenciar perfis]

---------------------------------------------------
```

---

# 4. Página Principal / Catálogo

### 4.1 Header

Criar um cabeçalho contendo:

* Logo
* Início
* Séries
* Filmes
* Novidades
* Minha Lista
* Avatar do usuário

Os elementos deverão ser organizados utilizando **Flexbox**.

---

### 4.2 Banner Principal

Criar uma seção Hero contendo:

* Imagem de fundo
* Título
* Descrição
* Ano
* Gênero
* Classificação indicativa
* Botão "Assistir"
* Botão "Mais Informações"

Os botões deverão ficar lado a lado utilizando Flexbox.

---

### 4.3 Categorias

Criar as seguintes categorias:

* Em Alta
* Continuar Assistindo
* Ação
* Comédia
* Terror
* Ficção Científica

Cada categoria deverá possuir **6 cards**.

---

### 4.4 Cards

Cada card deverá conter:

* Imagem
* Nome do filme

Os cards deverão ser organizados utilizando Flexbox.

Aplicar efeito visual ao passar o mouse utilizando:

```css
.card:hover
```

---

## Estrutura Esperada

```text
HEADER
---------------------------------------------------
LOGO   INÍCIO   SÉRIES   FILMES   NOVIDADES   👤
---------------------------------------------------

HERO
---------------------------------------------------
             IMAGEM DE FUNDO

              Título

              Descrição

       [Assistir] [Mais Informações]
---------------------------------------------------

EM ALTA

[Poster] [Poster] [Poster] [Poster] [Poster] [Poster]

---------------------------------------------------

CONTINUAR ASSISTINDO

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

# 5. Página de Detalhes do Filme

### 5.1 Banner

Criar um banner contendo:

* Imagem de fundo
* Título do filme
* Descrição
* Ano
* Duração
* Classificação
* Gênero

---

### 5.2 Informações do Filme

Criar uma seção contendo:

* Poster do filme
* Nome
* Descrição
* Diretor
* Elenco
* Gênero
* Ano de lançamento
* Duração

Organizar poster e informações utilizando **Flexbox**.

---

### 5.3 Botões

Adicionar:

* Botão "Assistir"
* Botão "Minha Lista"
* Botão "Voltar"

Os botões deverão ficar alinhados utilizando Flexbox.

---

### 5.4 Conteúdos Semelhantes

Criar uma seção:

**"Você também pode gostar"**

Adicionar **6 cards** de filmes semelhantes.

---

## Estrutura Esperada

```text
HEADER
---------------------------------------------------

BANNER
---------------------------------------------------
              IMAGEM DE FUNDO

                TÍTULO

           Ano • Duração • Gênero

              Descrição

       [Assistir] [Minha Lista]
---------------------------------------------------

DETALHES
---------------------------------------------------

[POSTER]       Título do Filme

               Descrição

               Diretor:
               Elenco:
               Gênero:
               Ano:
               Duração:

               [Voltar]
---------------------------------------------------

VOCÊ TAMBÉM PODE GOSTAR

[Poster] [Poster] [Poster] [Poster] [Poster] [Poster]

---------------------------------------------------

FOOTER
```

---

# 6. Página de Reprodução

### 6.1 Player

Criar uma página destinada à reprodução de um filme ou série.

Utilizar um elemento `<video>` do HTML ou criar uma representação visual de um player.

O player deverá ocupar grande parte da tela.

---

### 6.2 Controles

Caso seja utilizado apenas HTML e CSS, criar visualmente os controles:

* Play
* Barra de progresso
* Volume
* Configurações
* Tela cheia

Os controles não precisam possuir funcionalidades.

---

### 6.3 Informações

Abaixo do player, apresentar:

* Título
* Descrição
* Ano
* Gênero
* Duração

---

### 6.4 Próximos conteúdos

Criar uma seção:

**"Mais conteúdos para assistir"**

Adicionar **6 cards**.

---

## Estrutura Esperada

```text
HEADER
---------------------------------------------------

PLAYER
---------------------------------------------------
|                                                 |
|                                                 |
|                    ▶                            |
|                                                 |
|                                                 |
---------------------------------------------------
▶ ━━━━━━━━━━━━━━━━━━━━━━━ 🔊 ⚙ ⛶

TÍTULO DO FILME

Descrição do filme...

2026 • Ação • 2h 10min

---------------------------------------------------

MAIS CONTEÚDOS PARA ASSISTIR

[Poster] [Poster] [Poster] [Poster] [Poster] [Poster]

---------------------------------------------------

FOOTER
```

---

# 7. Responsividade

Todas as páginas deverão ser responsivas.

O projeto deverá funcionar corretamente em:

* Celular
* Tablet
* Desktop

Utilizar **Media Queries** para adaptar os elementos.

---

### Mobile

Em telas pequenas:

* Menu deverá ser reorganizado
* Cards deverão ocupar menos espaço
* Categorias poderão possuir rolagem horizontal
* Hero deverá se adaptar à largura da tela
* Textos deverão possuir tamanhos adequados
* Botões deverão se adaptar à tela

---

### Tablet

Adaptar:

* Quantidade de cards por linha
* Tamanho das imagens
* Espaçamento
* Tamanho dos textos

---

### Desktop

Utilizar o espaço disponível para apresentar:

* Menus horizontais
* Cards lado a lado
* Banners maiores
* Seções com maior espaçamento

---

# 8. Navegação entre as páginas

Todas as páginas deverão estar conectadas utilizando links HTML.

Fluxo esperado:

```text
Página Inicial
      ↓
    Login
      ↓
Escolha de Perfil
      ↓
Página Principal
      ↓
Detalhes do Filme
      ↓
Reprodução
```

Os links deverão ser criados utilizando a tag:

```html
<a href="...">
```

Não utilizar JavaScript para realizar a navegação.

---

# 9. Requisitos Técnicos

O projeto deverá utilizar **somente HTML5 e CSS3**.

É obrigatório utilizar:

* HTML semântico
* Flexbox
* CSS Grid ou Flexbox
* Media Queries
* `:hover`
* `:focus`
* `transition`
* `position`
* Pseudo-elementos
* Organização de arquivos CSS
* Layout responsivo

Não utilizar:

* JavaScript
* Bootstrap
* Tailwind
* React
* Angular
* Vue
* Bibliotecas externas de componentes

---

# 10. Estrutura Final do Projeto

```text
PROJETO
│
├── index.html
│
├── pages/
│   ├── login.html
│   ├── profiles.html
│   ├── home.html
│   ├── details.html
│   └── watch.html
│
├── css/
│   ├── style.css
│   ├── login.css
│   ├── profiles.css
│   ├── home.css
│   ├── details.css
│   └── watch.css
│
└── assets/
    ├── images/
    └── icons/
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