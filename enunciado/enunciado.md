# Exercício de consolidação: site Patas Amigas

Replica a página da imagem `modelo.png`, a homepage de uma associação de adoção de animais.

## Ficheiros a entregar

```
patas-amigas/
├── index.html
├── css/
│   └── style.css
└── img/          (já fornecida: cao.svg, gato.svg, coelho.svg)
```

O CSS tem de estar num ficheiro externo, ligado com `<link>`. Não uses `style=""` no HTML.

## Parte 1. Estrutura HTML

1. Usa `header`, `nav`, `main`, `section`, `article` e `footer`.
2. O menu é uma lista `ul` com quatro links que levam às secções da página (`#animais`, `#adotar`, `#visitas` e `#contacto`).
3. Só pode haver um `h1`. Os títulos das secções são `h2` e os nomes dos animais são `h3`.
4. As três imagens têm um `alt` que descreve o animal.
5. A secção "Como adotar" é uma lista numerada (`ol`).
6. O horário é uma tabela com `thead` e `tbody`.
7. O formulário tem `label` ligados aos campos (`for` e `id`), campos de texto e email obrigatórios, um `select` com os três animais, uma `textarea` e um botão.

## Parte 2. CSS

| Elemento | Regras |
|---|---|
| Página | Letra Arial (com alternativas), texto `#1d1148`, fundo `#f7f7f9`, `line-height: 1.6` |
| Contentor | Largura máxima de 1000px, centrado com `margin: 0 auto` |
| Cabeçalho | Fundo branco, logótipo à esquerda (a palavra "Amigas" em `#e40084`), menu à direita com flexbox |
| Destaque | Fundo `#1d1148`, texto branco e centrado, botão cor-de-rosa `#e40084` |
| Cartões | `box-sizing: border-box`, 300px de largura, padding de 16px, borda de 3px `#1d1148`, `border-radius: 20px`, sombra suave, os três lado a lado com flexbox e um espaço de 24px |
| Tabela | Largura máxima de 500px, cabeçalho com fundo `#1d1148`, células com borda de 1px |
| Formulário | Fundo branco, cantos arredondados, campos com a largura toda |
| Rodapé | Fundo `#1d1148`, texto branco e centrado |

## Parte 3. Desafios

1. Os links do menu e os botões mudam de cor com `:hover` (`#b8006a` nos botões).
2. O selo "Novo" fica no canto superior direito do cartão do Rex, com `position: absolute`, dentro de um cartão com `position: relative`.
3. Num ecrã estreito, o menu e os cartões passam para a linha de baixo sem criar scroll horizontal (dica: `flex-wrap`).

## Verificação final

- Abre a DevTools (F12) e confirma que cada cartão mede 300px de largura.
- Faz `commit` e `push` para o teu repositório no GitHub.
