# GymFit

Projeto Bootstrap 5 para site de academia.

## Tema escolhido
Site institucional de academia (GymFit), com foco em apresentação de planos, benefícios e contato.

## Link do projeto publicado no GitHub Pages
https://nicolasaoliveira1.github.io/ap2-bootstrap/

## Explicação da estrutura do projeto
- index.html: página inicial com apresentação e destaques.
- plans.html: página de planos e preços.
- contact.html: página de contato e formulário.
- css/style.css: estilos personalizados por cima do Bootstrap.
- img/: imagens usadas no layout.

## Componentes Bootstrap utilizados

### Navbar
- **Onde foi usado**: Em todas as páginas (index.html, planos.html, contato.html)
- **Descrição**: Barra de navegação fixa no topo com menu responsivo, dropdown para "Modalidades" e botão de "Matricule-se"

### Grid System (container, row, col)
- **Onde foi usado**: Em todas as páginas
- **Descrição**: Estrutura responsiva para organizar o layout em diferentes tamanhos de tela (col-lg, col-md, col-12)

### Cards
- **Onde foi usado**: 
  - index.html: Card de horários de funcionamento
  - planos.html: Cards de benefícios e planos (Start, Performance, Elite)
  - contato.html: Cards de informações de contato, redes sociais e mapa
- **Descrição**: Componentes de conteúdo em blocos com sombras e bordas personalizadas

### Buttons
- **Onde foi usado**: Em todas as páginas
- **Descrição**: Botões primários (btn-primary) para ações principais como "Matricule-se", botões secundários (btn-outline-secondary) para ações secundárias

### Forms
- **Onde foi usado**: contato.html (seção de formulário)
- **Descrição**: Formulário completo com campos de nome, telefone, email, assunto (select) e mensagem (textarea), usando form-control, form-select e form-textarea

### Utilities
- **Onde foi usado**: Em todas as páginas
- **Descrição**: Classes utilitárias para:
  - **Spacing**: mb-*, mt-*, p-*, g-* (gap)
  - **Typography**: fw-bold, display-5, h3, text-muted, text-white
  - **Colors**: bg-dark, bg-primary, bg-light, text-white
  - **Flexbox**: d-flex, flex-wrap, align-items-center, justify-content-between
  - **Border & Radius**: rounded, shadow-sm, border

### Carousel
- **Onde foi usado**: index.html (seção de estrutura da academia)
- **Descrição**: Carrossel de imagens com indicadores e legendas para mostrar as áreas da academia

### List Group
- **Onde foi usado**: 
  - index.html: Lista de horários de funcionamento
  - planos.html: Lista de benefícios de cada plano
- **Descrição**: Listas estilizadas com list-group e list-group-item

### Badges
- **Onde foi usado**: planos.html (identificação de planos: Mensal, Trimestral, Anual)
- **Descrição**: Marcadores coloridos para categorizar os diferentes planos

## Decisões de layout e design
- Layout claro e direto, priorizando leitura rápida.
- Destaques visuais para chamadas de ação.
- Seções separadas por blocos para facilitar a navegação.

## Utilização do display flex
- Alinhamento horizontal de elementos em seções de destaque.
- Centralização de conteúdo em blocos específicos.

## Observações relevantes sobre o desenvolvimento
- CSS customizado apenas para ajustes finos de tipografia e espaçamento.
- Estrutura pensada para ser responsiva em telas menores.
