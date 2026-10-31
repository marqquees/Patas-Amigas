# Patas Amigas

Este projeto foi desenvolvido com o objetivo de aplicar e consolidar os conhecimentos teóricos adquiridos em **HTML** e **CSS**, focando na criação de uma página web responsiva e esteticamente agradável para uma associação de adoção de animais.

## Tecnologias Utilizadas

*   **HTML5:** Estrutura semântica para organizar o conteúdo da página.
*   **CSS3:** Estilização, incluindo Flexbox, Posicionamento (`position`), Variáveis CSS (`:root`), e Media Queries implícitas (via `flex-wrap`).

## Objetivos de Aprendizagem

Este projeto serviu como um laboratório prático para trabalhar os seguintes conceitos:

### HTML
*   **Estrutura da Página:** Utilização correta de tags semânticas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) para dar significado ao conteúdo da página.
*   **Organização de Dados:** Implementação correta de listas (`<ul>`, `<ol>`) e tabelas (`<table>`, `<thead>`, `<tbody>`) para apresentar informações de forma organizada.
*   **Acessibilidade:** Uso de atributos importantes como `alt` em imagens para melhorar a acessibilidade.

### CSS
*   **Layout Flexbox:** Utilização de `display: flex` e `justify-content/align-items` para criar layouts, como a navegação do menu e o alinhamento dos cartões de animais.
*   **Controlo de Fluxo:** Aplicação de **`flex-wrap: wrap;`** para garantir que o menu e os cartões se ajustem automaticamente a ecrãs estreitos, prevenindo a necessidade indesejada de *scroll* horizontal.
*   **Posicionamento Relativo/Absoluto:** Demonstração da diferença entre `position: relative` (no contentor pai) e `position: absolute` (no selo "Novo") para posicionar um elemento.
*   **Estilização e Coerência:**
    *   Uso de **Variáveis CSS (`:root`)** para gerir cores (ex: `--primary-color`, `--white-color`), facilitando a manutenção da identidade visual.
    *   Aplicação de `box-sizing: border-box;` para garantir que o cálculo das larguras dos cartões seja preciso.
    *   Criação de efeitos visuais como sombras (`box-shadow`) e transições de estado (`:hover`) para tornar a interface interativa e viva.

## Verificação Final

*   **Estrutura:** Todos os requisitos de estrutura HTML foram cumpridos.
*   **Estilização:** Todas as regras de estilo definidas no `enunciado.md` foram implementadas no `style.css`.
*   **Responsividade:** O layout responde corretamente ao requisito de que o menu e os cartões se ajustem verticalmente em ecrãs estreitos, utilizando o `flex-wrap`.