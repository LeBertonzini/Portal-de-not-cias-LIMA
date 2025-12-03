# 🗞️ Nova Era News: Projeto de Portal de Notícias Responsivo

## Descrição do Projeto
Este projeto simula um portal de notícias moderno, focado em implementar as melhores práticas de **HTML Semântico** e **CSS Avançado**. O desenvolvimento seguiu um fluxo de trabalho dividido em Sprints, culminando na criação de um site **100% responsivo** com interatividade avançada.

## 👩🏻‍💻 Tecnologias e Ferramentas
* **HTML5:** Estrutura semântica para todas as páginas (`index.html`, `noticia.html`, `contato.html`).
* **CSS3:** Utilização de Flexbox, Grid Layout, e propriedades avançadas (Transitions, Transforms, Media Queries).
* **Google Fonts:** Tipografia consistente.
* **Validação W3C:** Código verificado para conformidade com padrões web (HTML e CSS).

***

## Funcionalidades e Destaques (SPRINT 3)

O projeto final inclui os seguintes recursos avançados de Front-end:

### Interatividade e Efeitos Visuais
* **Efeitos `Hover`:** Cards de notícias e botões de navegação apresentam transições suaves (`transition`) e efeitos de profundidade (`box-shadow` e `transform: translateY`) ao passar o mouse.
* **Estilização de Foco:** Campos de formulário (`input`, `textarea`) são destacados com bordas e sombras ao receberem foco (`:focus`) para melhorar a acessibilidade.
* **Tabelas Acessíveis:** As tabelas de horário/audiência utilizam a pseudo-classe `:nth-child` para criar o efeito "zebrado", facilitando a leitura de dados.
* **Estilo de Lista Customizado:** Listas de itens em artigos de notícia são formatadas com bolinhas (`::before`) na cor primária do site.

### Responsividade (Mobile First)
* **Media Queries:** O layout é otimizado para telas pequenas.
* **Menu Responsivo:** Em dispositivos móveis (abaixo de 768px), o menu horizontal se transforma em uma lista vertical centralizada.
* **Layout Adaptativo:** O layout principal (Notícias + Sidebar) e o Grid de Cards (`news-grid`) transformam-se em colunas únicas para garantir a legibilidade em smartphones.

***

##  Estrutura de Arquivos
O projeto é composto por três páginas principais e uma folha de estilos:

* **`index.html`:** Página inicial com o Hero Banner e o Grid de Cards de Notícias.
* **`noticia.html`:** Página de artigo completo com layout limpo e otimizado para leitura.
* **`contato.html`:** Página com formulário de contato e tabelas de informações.
* **`style.css`:** Folha de estilos principal do projeto.

***

##  Como Executar o Projeto
1.  **Download:** Baixe ou clone o repositório do projeto.
2.  **Execução:** Abra qualquer um dos arquivos `.html` (`index.html`, `noticia.html` ou `contato.html`) diretamente no seu navegador web.