# DevTube — Clone de Página de Vídeo com Flexbox

Projeto desenvolvido como prática de HTML e CSS, inspirado no desafio **Clonando a Página do YouTube com CSS** da Formação CSS Web Developer da DIO.

## Objetivo

Reproduzir a estrutura visual de uma página de exibição de vídeo, colocando em prática principalmente os conceitos de **Flexbox**.

## Tecnologias

- HTML5
- CSS3
- Flexbox
- Media Queries
- Pseudo-classes e pseudo-elementos
- Transformações e transições simples

## O que foi praticado

- Estruturação semântica com `header`, `main`, `section`, `article` e `aside`
- Alinhamento com `display: flex`
- `justify-content`, `align-items`, `gap` e `flex-wrap`
- Controle de crescimento e encolhimento de flex-items
- Layout em duas colunas no desktop
- Reorganização do layout para tablet e celular
- Imagens responsivas
- Estados de `hover` e `focus-visible`
- Uso de `::before`
- Acessibilidade básica com labels e atributos ARIA

## Estrutura

```text
youtube-clone-flexbox/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── favicon.svg
│   ├── profile-davi.png
│   ├── thumb-*.webp
│   └── thumb-*.svg
└── README.md
```

## Como executar

Abra o arquivo `index.html` diretamente no navegador ou utilize a extensão **Live Server** no VS Code.

## Responsividade

O projeto possui adaptações para desktop, tablet e celular. A área principal usa Flexbox e muda de duas colunas para uma coluna em telas menores.

## Observação

Este projeto tem finalidade educacional e utiliza uma identidade visual própria (`DevTube`) para praticar a construção de interfaces inspiradas em plataformas de vídeo.