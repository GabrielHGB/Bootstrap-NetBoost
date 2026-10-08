# NetBoost

Projeto desenvolvido com HTML, CSS e Bootstrap com o objetivo de praticar os principais recursos da biblioteca, principalmente responsividade, Grid, Flexbox, componentes e classes utilitárias.

O projeto foi desenvolvido sem JavaScript.

---

## Estrutura do projeto

O site está concentrado em uma única página principal:

- `index.html`

As diferentes partes do projeto foram organizadas em seções dentro dessa página.

---

## Etapa 1 — Header e Navbar

A Navbar possui:

- Logo NetBoost
- Menu horizontal no desktop
- Menu vertical no mobile
- Navegação entre as seções da página

Principais classes Bootstrap utilizadas:

- `navbar`
- `navbar-expand-md`
- `navbar-nav`
- `nav-item`
- `nav-link`
- `navbar-brand`
- `collapse`
- `d-md-block`
- `d-md-none`
- `d-flex`
- `flex-row`
- `flex-column`
- `gap-*`

Como o JavaScript do Bootstrap não poderia ser utilizado, o menu mobile foi criado utilizando classes responsivas de exibição.

---

## Etapa 2 — Hero

A Hero apresenta:

- Título principal
- Subtítulo
- Dois botões
- Imagem do mascote NetBoost

Principais classes:

- `container`
- `row`
- `col-12`
- `col-lg-6`
- `order-*`
- `align-items-center`
- `display-*`
- `fw-bold`
- `lead`
- `btn`
- `btn-primary`
- `btn-outline-primary`
- `img-fluid`

A ordem entre texto e imagem é alterada dependendo do tamanho da tela.

---

## Etapa 3 — Cards

Foram criados 12 cards com dicas para melhorar a conexão com a internet.

O layout possui:

- 1 coluna no mobile
- 2 colunas no tablet
- 4 colunas no desktop

Principais classes:

- `row`
- `g-4`
- `col-12`
- `col-md-6`
- `col-lg-3`
- `card`
- `card-body`
- `h-100`
- `d-flex`
- `flex-column`
- `badge`
- `mt-auto`

---

## Etapa 4 — Tabela

Foi criada uma tabela comparando diferentes tipos de conexão.

A tabela possui:

- Cabeçalho destacado
- Linhas alternadas
- Efeito hover
- Bootstrap Icons
- Responsividade para telas menores

Principais classes:

- `table`
- `table-striped`
- `table-hover`
- `table-dark`
- `table-responsive`
- `align-middle`

Bootstrap Icons utilizados:

- `bi`
- `bi-wifi`
- `bi-router`
- `bi-lightning-charge-fill`
- `bi-broadcast-pin`

---

## Etapa 5 — Formulários

Foram criados dois formulários:

### Cadastro

Possui:

- Inputs de texto
- E-mail
- Senha
- Data
- Select
- Radio
- Checkbox
- Input Group

### Contato

Possui:

- Nome
- E-mail
- Assunto
- Velocidade
- Textarea

Principais classes:

- `form-control`
- `form-label`
- `form-select`
- `form-check`
- `form-check-input`
- `form-check-label`
- `input-group`
- `input-group-text`
- `form-text`
- `is-valid`
- `is-invalid`
- `valid-feedback`
- `invalid-feedback`

---

## Etapa 6 — Modal

Como JavaScript não poderia ser utilizado, o modal foi criado utilizando HTML e CSS.

Foi utilizado o Checkbox Hack para controlar se o modal está aberto ou fechado.

Principais classes Bootstrap:

- `position-fixed`
- `top-0`
- `start-0`
- `w-100`
- `h-100`
- `d-flex`
- `align-items-center`
- `justify-content-center`
- `z-3`

O comportamento de abrir e fechar foi desenvolvido com CSS próprio.

---

## Etapa 7 — Responsividade

Foram utilizadas diferentes classes responsivas para alterar a interface conforme o tamanho da tela.

Principais classes:

- `d-none`
- `d-sm-block`
- `d-md-flex`
- `d-lg-inline`
- `text-center`
- `text-md-start`
- `justify-content-md-end`
- `mt-md-0`

Essas classes permitem esconder, exibir, reposicionar e alterar o alinhamento dos elementos.

---

## Etapa 8 — Sistema de Design

Foram utilizadas diferentes cores, botões e badges do Bootstrap.

### 5 cores Bootstrap

- `bg-primary`
- `bg-success`
- `bg-danger`
- `bg-warning`
- `bg-info`

### 4 variações de botão

- `btn-primary`
- `btn-success`
- `btn-warning`
- `btn-danger`

### Badges

- `text-bg-primary`
- `text-bg-success`
- `text-bg-warning`
- `text-bg-danger`

---

## Etapa 9 — Dashboard

O Dashboard apresenta:

- Sidebar
- Cards de métricas
- Alerts
- Tabela de dispositivos

A Sidebar aparece somente em telas maiores.

Principais classes:

- `row`
- `col-lg-3`
- `col-lg-9`
- `d-none`
- `d-lg-flex`
- `flex-column`
- `sticky-top`
- `card`
- `alert`
- `table-responsive`

---

## CSS próprio

Apesar de grande parte da estilização ter sido feita utilizando Bootstrap, algumas situações precisaram de CSS próprio.

### Navbar

Foi utilizado CSS para criar uma linha abaixo do item ativo do menu. E uma validação visual com hover.

### Hero

Foi utilizado CSS para definir:

- Altura mínima
- Tamanho máximo da imagem
- Pequenos ajustes de responsividade

### Cards

Foi adicionado um efeito de movimento no `hover`.

### Modal

O CSS próprio foi necessário para controlar:

- Visibilidade
- Fundo escuro
- Animação
- Checkbox Hack

### Dashboard

Foi utilizado CSS para complementar o visual da Sidebar e seus links.

---

## Principais dificuldades

As principais dificuldades durante o desenvolvimento foram:

- Entender como funcionam os breakpoints do Bootstrap
- Entender que classes como `flex-sm-row` funcionam de `sm` para cima
- Trabalhar com o sistema Grid de 12 colunas
- Entender as classes de espaçamento, como `mt-*`, `mb-*`, `py-*` e `gap-*`
- Criar uma Navbar responsiva sem JavaScript
- Criar um modal funcional sem JavaScript
- Entender quando utilizar Bootstrap e quando complementar com CSS próprio
- Trabalhar com mudanças de ordem utilizando `order-*`
- Conseguir lembrar das classes do Bootstrap, que mesmo sendo intuítivas, ainda são muitas!

---

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons