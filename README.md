# Checkpoint — Portal Gamer Responsivo

Portal independente sobre videogames, desenvolvido como trabalho da disciplina **Desenvolvimento Front-End Para Web** (Universidade Positivo, curso de Análise e Desenvolvimento de Sistemas), sob orientação do professor Fabricio Gabriel Olivo.

**Autores:** Eduardo Ducca de Melo e Marcelo Luz

> Todo o conteúdo do site é **demonstrativo**: as matérias são textos explicativos escritos para o projeto, os lançamentos futuros são títulos fictícios, as notas das análises são avaliações da própria equipe e as imagens são ilustrações originais.

## Sobre o projeto

O nome *Checkpoint* vem dos jogos: o ponto em que o progresso é salvo. No site, os favoritos e as mensagens do visitante ficam guardados no navegador (`localStorage`), então o progresso do usuário também fica salvo.

O projeto reúne **10 páginas interligadas**, responsivas (de smartphones a desktops) e que funcionam **offline**, sem depender de CDN ou fontes externas.

## Páginas

| Página | Arquivo |
|---|---|
| Home | `index.html` |
| Notícias | `noticias.html` |
| Catálogo | `catalogo.html` |
| Análises | `analises.html` |
| Lançamentos | `lancamentos.html` |
| Plataformas | `plataformas.html` |
| História | `historia.html` |
| Favoritos | `favoritos.html` |
| Comunidade | `comunidade.html` |
| Sobre | `sobre.html` |

As páginas **História** e **Sobre** usam apenas HTML, CSS e JavaScript puros, sem Bootstrap. As outras oito combinam o CSS próprio com o Bootstrap.

## Tecnologias

- **HTML5** semântico (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `video`, `audio`, `table`, `form`)
- **CSS3** (Grid, Flexbox, variáveis CSS, media queries, estados `:hover`, `:focus` e `:invalid`)
- **JavaScript** puro (eventos, manipulação do DOM, busca, filtros, ordenação, validação de formulário e `localStorage`)
- **Bootstrap 5.3** (navbar, botões, formulários, alertas, cards e tabelas), incluído localmente
- **SVG** para ilustrações, logotipo e avatares

## Funcionalidades

- Catálogo de jogos com busca instantânea e filtros combináveis por plataforma, gênero e situação
- Notícias com filtro por categoria e leitura expansível
- Lançamentos e comparativo de plataformas em tabelas
- Favoritos salvos no navegador, com ordenação
- Formulário da comunidade com validação e mensagens salvas no navegador
- Linha do tempo da história dos videogames
- Vídeo e áudio com controles nativos
- Acessibilidade: atalho "Ir para o conteúdo", atributos ARIA, foco visível e respeito à preferência por menos animações

## Como executar

Não é necessário instalar nada nem ter internet.

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/duccatheone/DefesaCodigoHtml_Jogos.git
   ```
2. Abra o arquivo `index.html` em um navegador moderno (Chrome, Edge, Firefox).
3. Navegue pelo menu entre as páginas.

## Estrutura de pastas

```
CHECKPOINT/
├── index.html
├── noticias.html
├── catalogo.html
├── analises.html
├── lancamentos.html
├── plataformas.html
├── historia.html
├── favoritos.html
├── comunidade.html
├── sobre.html
├── css/
│   ├── bootstrap.min.css
│   ├── style.css
│   └── responsivo.css
├── js/
│   ├── bootstrap.bundle.min.js
│   ├── main.js
│   ├── catalogo.js
│   ├── favoritos.js
│   └── formulario.js
├── img/        (ilustrações SVG originais)
├── video/      abertura-checkpoint.mp4
├── audio/      trilha-checkpoint.mp3
└── doc/        Documentacao-Checkpoint
```

## Documentação

A documentação completa do projeto (tema, UX e UI, paleta de cores, tipografia, mapa do site, telas, aplicações de JavaScript e atendimento aos requisitos) está na pasta `doc/`.

## Créditos e direitos autorais

As ilustrações foram geradas para o projeto, evitando o uso de imagens de terceiros protegidas por direitos autorais. O Checkpoint se inspira na estrutura editorial de portais como IGN Brasil e GameSpot, mas possui nome, logotipo, paleta, ilustrações e textos próprios.

## Autoria

Projeto acadêmico desenvolvido por **Eduardo Ducca de Melo** e **Marcelo Luz**.
