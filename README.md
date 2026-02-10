# SyntaxWear - Tênis e Sneakers Online

Este é um projeto de um e-commerce front-end focado na venda de tênis e sneakers. O site apresenta um design responsivo e uma estrutura clara para exibição de produtos e categorias.

## Visão Geral

A SyntaxWear oferece uma experiência de compra online para entusiastas de tênis, com modelos exclusivos, ofertas e frete grátis. O projeto é construído utilizando tecnologias web padrão para um carregamento rápido e uma interface intuitiva.

## Tecnologias Utilizadas

*   **HTML5:** Estrutura semântica da página.
*   **CSS3:** Estilização completa, incluindo:
    *   **CSS Variables:** Para gestão de temas e cores de forma eficiente (`variables.css`).
    *   **Modularização de Componentes:** Estilos divididos por componentes (e.g., `header.css`, `hero.css`, `footer.css`, `product-grid.css`, `product-category.css`) para melhor organização e manutenção.
    *   **Reset CSS:** Para padronização de estilos entre navegadores (`reset.css`).
    *   **Layout CSS:** Para a organização geral da página (`layout.css`).
    *   **Base CSS:** Estilos base para elementos HTML (`base.css`).

## Estrutura de Pastas

```
ecommerce-syntaxwear/
├───index.html                  # Página principal do e-commerce
├───README.md                   # Este arquivo README
├───.git/                       # Metadados do Git (controle de versão)
├───css/
│   ├───base.css                # Estilos base para o projeto
│   ├───layout.css              # Definições de layout (ex: grid, flexbox)
│   ├───reset.css               # Reset de CSS para consistência entre navegadores
│   ├───variables.css           # Variáveis CSS para cores, fontes, etc.
│   └───componentes/            # Estilos específicos para componentes da UI
│       ├───footer.css
│       ├───header.css
│       ├───hero.css
│       ├───product-category.css
│       └───product-grid.css
├───imagens/
│   ├───banners/                # Imagens de banner para seções como o hero
│   ├───favicons/               # Ícones de favoritos para o navegador
│   ├───icons/                  # Ícones utilizados na navegação e em outras partes da UI (SVG)
│   └───logo/                   # Logo da SyntaxWear (SVG)
└───products/                   # (Esta pasta parece estar vazia ou conter apenas placeholders,
                                # talvez para futuras imagens de produtos)
```

## Como Visualizar o Projeto

Para visualizar este projeto no seu navegador, siga os passos abaixo:

1.  **Clone o repositório** (se ainda não o fez):
    ```bash
    git clone <URL_DO_REPOSITORIO>
    ```
    (Substitua `<URL_DO_REPOSITORIO>` pela URL real do seu repositório Git, se aplicável.)
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd ecommerce-syntaxwear
    ```
3.  **Abra o arquivo `index.html`** no seu navegador de preferência. Você pode fazer isso diretamente pelo explorador de arquivos ou usando um comando como:
    *   No Windows: `start index.html`
    *   No macOS: `open index.html`
    *   No Linux: `xdg-open index.html` (ou o comando equivalente para seu ambiente de desktop)

Não há necessidade de um servidor web para rodar este projeto, pois ele consiste apenas de arquivos HTML e CSS estáticos.

## Contribuição

Contribuições são bem-vindas! Se você quiser melhorar este projeto, por favor, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto é de código aberto e está disponível sob a licença [inserir licença, se houver].