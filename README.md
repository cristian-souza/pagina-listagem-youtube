# Clone Youtuber

Este projeto é uma página de listagem de vídeos inspirada no layout do YouTube, desenvolvida com HTML e CSS puro.

## Estrutura do Projeto

-   `index.html`: Página principal contendo o layout da sidebar (menu lateral), barra de busca, cabeçalho e a listagem dos vídeos.
-   `assets/css/global.css`: Estilos globais (não detalhado aqui).
-   `assets/css/header.css`: Estilos do cabeçalho (não detalhado aqui).
-   `assets/css/main.css`: Estilos principais da página, incluindo grid de vídeos e sidebar.
-   `assets/images/`: Imagens utilizadas para miniaturas, avatares de canal e ícones do menu.

## Principais Funcionalidades

-   **Sidebar fixa** com navegação semelhante ao YouTube.
-   **Barra de busca** no topo.
-   **Listagem de vídeos** em grid responsivo, com miniatura, avatar do canal, título, visualizações e data.
-   **Layout responsivo** e alinhamento visual próximo ao YouTube.

## Como visualizar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em seu navegador.

## Estrutura HTML resumida

```html
<div class="main-content">
    <aside class="sidebar">...</aside>
    <section class="video-list">
        <div class="video-item">
            <img src="..." alt="Miniatura" />
            <div class="video-info">
                <img src="..." alt="Avatar" />
                <div class="video-info-text">
                    <h3>Título</h3>
                    <p>Visualizações</p>
                    <p>Data</p>
                </div>
            </div>
        </div>
        <!-- Outros vídeos -->
    </section>
</div>
```

## Estilo principal (main.css)

-   Utiliza `display: flex` para alinhar sidebar e listagem lado a lado.
-   Utiliza `display: grid` para a listagem de vídeos.
-   Avatar e textos dos vídeos ficam alinhados horizontalmente.

## Créditos

Desenvolvido para fins de estudo e prática de HTML/CSS.
